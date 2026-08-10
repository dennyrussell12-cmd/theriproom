<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Rip Room Collectibles | Premium TCG & Sports Cards</title>
    <!-- Google Fonts & Tailwind CSS for modern styling -->
    <link href="https://googleapis.com" rel="stylesheet">
    <script src="https://tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Plus Jakarta Sans', 'sans-serif'],
                        display: ['Space Grotesk', 'sans-serif'],
                    },
                    colors: {
                        vault: {
                            bg: '#05070F',
                            card: 'rgba(15, 23, 42, 0.45)',
                            border: 'rgba(255, 255, 255, 0.06)',
                            neonBlue: '#38BDF8',
                            neonGreen: '#34D399',
                            neonPurple: '#A78BFA'
                        }
                    }
                }
            }
        }
    </script>
    <style>
        html { scroll-behavior: smooth; }
        /* Ultra-modern glowing accents */
        .glow-blue:hover { box-shadow: 0 0 30px rgba(56, 189, 248, 0.15); border-color: rgba(56, 189, 248, 0.4); }
        .glow-green:hover { box-shadow: 0 0 30px rgba(52, 211, 153, 0.15); border-color: rgba(52, 211, 153, 0.4); }
        .glow-purple:hover { box-shadow: 0 0 30px rgba(167, 139, 250, 0.15); border-color: rgba(167, 139, 250, 0.4); }
        
        /* Smooth infinite ticker animation */
        @keyframes marquee {
            0% { transform: translateX(0%); }
            100% { transform: translateX(-50%); }
        }
        .animate-marquee { animation: marquee 25s linear infinite; }
    </style>
</head>
<body class="bg-vault-bg text-slate-100 min-h-screen selection:bg-sky-500/30 font-sans overflow-x-hidden">

    <!-- Top Live Ticker Banner -->
    <div class="w-full bg-blue-950/40 border-b border-blue-500/20 py-2.5 overflow-hidden backdrop-blur-sm">
        <div class="flex whitespace-nowrap animate-marquee text-xs font-display tracking-widest text-sky-400 font-bold uppercase space-x-12">
            <span>🔥 GRAND OPENING SPECIALS 🔥</span>
            <span>• BUYING SINGLE CARDS @ 70% CASH / 80% CREDIT •</span>
            <span>🚀 NEW JAPANESE TCG IMPORT SELECTION IN STOCK 🚀</span>
            <span>• VISIT THE VAULT STREAMING SUITE IN PEARLAND •</span>
            <!-- Duplicate for seamless looping loop -->
            <span>🔥 GRAND OPENING SPECIALS 🔥</span>
            <span>• BUYING SINGLE CARDS @ 70% CASH / 80% CREDIT •</span>
            <span>🚀 NEW JAPANESE TCG IMPORT SELECTION IN STOCK 🚀</span>
            <span>• VISIT THE VAULT STREAMING SUITE IN PEARLAND •</span>
        </div>
    </div>

    <!-- Header Navigation Layout -->
    <header class="sticky top-0 z-50 bg-vault-bg/70 backdrop-blur-xl border-b border-white/5">
        <div class="max-w-7xl mx-auto px-6 h-24 flex items-center justify-between">
            <a href="#" class="font-display font-extrabold text-2xl tracking-tighter bg-gradient-to-r from-sky-400 via-indigo-400 to-emerald-400 bg-clip-text text-transparent">
                THE RIP ROOM
            </a>
            <nav class="hidden md:flex items-center space-x-10 text-sm font-medium tracking-wide text-slate-400">
                <a href="#inventory" class="hover:text-sky-400 transition-colors">Vault Supply</a>
                <a href="#trade" class="hover:text-sky-400 transition-colors">Trade Appraisals</a>
                <a href="#contact" class="hover:text-sky-400 transition-colors">Hours & Directions</a>
            </nav>
            <a href="#trade" class="bg-gradient-to-r from-sky-500 to-indigo-500 hover:from-sky-400 hover:to-indigo-400 text-white px-6 py-3 rounded-xl text-xs font-bold font-display uppercase tracking-wider transition-all duration-300 shadow-lg shadow-sky-500/10 hover:shadow-sky-500/20 transform hover:-translate-y-0.5">
                Appraise My Cards
            </a>
        </div>
    </header>

    <!-- Main Hero Banner Section -->
    <main class="relative max-w-7xl mx-auto px-6 pt-12 pb-32">
        <!-- Abstract Background Glows -->
        <div class="absolute top-1/4 right-0 w-[500px] h-[500px] bg-sky-500/10 blur-[150px] rounded-full pointer-events-none"></div>
        <div class="absolute bottom-0 left-0 w-[400px] h-[400px] bg-emerald-500/5 blur-[120px] rounded-full pointer-events-none"></div>

        <div class="grid lg:grid-cols-12 gap-12 items-center">
            <div class="lg:col-span-7 space-y-8 text-center lg:text-left">
                <div class="inline-flex items-center space-x-2 bg-sky-500/10 border border-sky-500/20 rounded-full px-4 py-1.5 text-xs font-bold text-sky-400 font-display uppercase tracking-wider">
                    <span class="w-1.5 h-1.5 rounded-full bg-sky-400 animate-pulse"></span>
                    <span>Pearland's 5.0 Rated Showcase Hub</span>
                </div>
                <h1 class="text-4xl sm:text-6xl font-extrabold tracking-tight font-display leading-[1.1] text-white">
                    Where Collectors <br class="hidden sm:inline">
                    <span class="bg-gradient-to-r from-sky-400 via-blue-400 to-emerald-400 bg-clip-text text-transparent">Secure The Grails</span>
                </h1>
                <p class="text-slate-400 text-lg max-w-2xl mx-auto lg:mx-0 leading-relaxed">
                    Step into an ultra-premium storefront crafted exclusively for card enthusiasts. Discover master-grade sealed booster cases, pristine sports card slabs, and our state-of-the-art live streaming media lab.
                </p>
                <div class="pt-4 flex flex-col sm:flex-row space-y-4 sm:space-y-0 sm:space-x-4 justify-center lg:justify-start">
                    <a href="#inventory" class="bg-gradient-to-r from-sky-500 to-blue-600 px-8 py-4 rounded-xl font-bold font-display text-sm uppercase tracking-wider text-white transition-all shadow-xl shadow-sky-500/10 hover:shadow-sky-500/20">
                        Explore Inventory
                    </a>
                    <a href="#contact" class="bg-slate-900 hover:bg-slate-800 border border-white/10 px-8 py-4 rounded-xl font-bold font-display text-sm uppercase tracking-wider text-slate-300 transition-colors">
                        Store Location
                    </a>
                </div>
            </div>

            <!-- Sleek Card Showcases Layout -->
            <div class="lg:col-span-5 relative">
                <div class="bg-gradient-to-b from-white/[0.07] to-transparent border border-white/10 rounded-3xl p-8 backdrop-blur-xl shadow-2xl space-y-6">
                    <div class="flex justify-between items-center border-b border-white/5 pb-4">
                        <span class="text-xs uppercase tracking-widest text-slate-400 font-bold font-display">Live Vault Drops</span>
                        <span class="text-xs text-emerald-400 font-bold bg-emerald-500/10 px-2.5 py-1 rounded-md border border-emerald-500/20">In Stock</span>
                    </div>
                    
                    <div class="space-y-4">
                        <!-- Card Showcase 1 -->
                        <div class="flex items-center justify-between p-4 bg-white/[0.02] border border-white/5 rounded-2xl hover:bg-white/[0.04] transition-all">
                            <div class="flex items-center space-x-4">
                                <div class="w-14 h-14 rounded-xl bg-gradient-to-br from-sky-500/20 to-indigo-500/20 flex items-center justify-center text-xl border border-sky-500/30">📦</div>
                                <div>
                                    <h4 class="font-bold text-sm text-white">Sealed Booster Boxes</h4>
                                    <p class="text-xs text-slate-400">English & Japanese Editions</p>
                                </div>
                            </div>
                            <span class="text-xs font-bold font-display text-sky-400 uppercase">View Pack Pricing</span>
                        </div>
                        <!-- Card Showcase 2 -->
                        <div class="flex items-center justify-between p-4 bg-white/[0.02] border border-white/5 rounded-2xl hover:bg-white/[0.04] transition-all">
                            <div class="flex items-center space-x-4">
                                <div class="w-14 h-14 rounded-xl bg-gradient-to-br from-emerald-500/20 to-teal-500/20 flex items-center justify-center text-xl border border-emerald-500/30">🃏</div>
                                <div>
                                    <h4 class="font-bold text-sm text-white">Graded Slabs & Singles</h4>
                                    <p class="text-xs text-slate-400">PSA / BGS Investment Grade</p>
                                </div>
                            </div>
                            <span class="text-xs font-bold font-display text-emerald-400 uppercase">Inspect Slabs</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </main>

    <!-- Modern Feature Showcase Grid Layout -->
    <section id="inventory" class="bg-black/40 border-t border-b border-white/5 py-32">
        <div class="max-w-7xl mx-auto px-6">
            <div class="text-center max-w-2xl mx-auto space-y-4 mb-20">
                <h2 class="text-3xl md:text-4xl font-extrabold font-display text-white tracking-tight">The Rip Room Vault Standards</h2>
