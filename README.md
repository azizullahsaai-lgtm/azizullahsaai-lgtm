# AZIZULLAHSAAI
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Professional GitHub Profile README Generator</title>
    <!-- Tailwind CSS for modern developer dashboard theme styling -->
    <script src="https://tailwindcss.com"></script>
    <!-- FontAwesome for professional modern vector icons UI elements -->
    <link rel="stylesheet" href="https://cloudflare.com">
    <!-- Marked JS to parse live compiled Markdown natively inside the preview container layout -->
    <script src="https://jsdelivr.net"></script>
</head>
<body class="bg-slate-950 text-slate-100 font-sans min-h-screen selection:bg-cyan-500 selection:text-slate-950">

    <!-- Top Navigation Header -->
    <header class="border-b border-slate-800 bg-slate-900/50 backdrop-blur sticky top-0 z-50 px-6 py-4">
        <div class="max-w-7xl mx-auto flex flex-col sm:flex-row justify-between items-center gap-4">
            <div class="flex items-center space-x-3">
                <div class="bg-gradient-to-tr from-cyan-500 to-blue-600 p-2.5 rounded-xl shadow-lg shadow-cyan-500/10">
                    <i class="fa-brands fa-github text-xl text-white"></i>
                </div>
                <div>
                    <h1 class="text-xl font-bold tracking-tight bg-gradient-to-r from-white via-slate-200 to-slate-400 bg-clip-text text-transparent">
                        ReadmeCraft Studio
                    </h1>
                    <p class="text-xs text-slate-400 font-medium">Professional Profile Engineer</p>
                </div>
            </div>
            <div class="flex items-center space-x-3">
                <button id="copyBtn" class="flex items-center space-x-2 bg-slate-800 hover:bg-slate-700 text-slate-200 font-semibold text-xs px-4 py-2.5 rounded-lg border border-slate-700 active:scale-95 transition-all shadow-sm">
                    <i class="fa-regular fa-copy"></i> <span>Copy Markdown</span>
                </button>
                <button id="downloadBtn" class="flex items-center space-x-2 bg-gradient-to-r from-cyan-500 to-blue-600 hover:from-cyan-400 hover:to-blue-500 text-white font-semibold text-xs px-4 py-2.5 rounded-lg active:scale-95 transition-all shadow-md shadow-cyan-500/10">
                    <i class="fa-solid fa-arrow-down-to-line"></i> <span>Export README.md</span>
                </button>
            </div>
        </div>
    </header>

    <!-- App Main Workspace Workspace Wrapper layout -->
    <main class="max-w-7xl mx-auto p-4 md:p-6 lg:p-8 grid grid-cols-1 lg:grid-cols-12 gap-8">
        
        <!-- Interactive Controls Pane Configuration Forms Panels (Left Side Grid Element) -->
        <div class="lg:col-span-5 space-y-6 max-h-[calc(100vh-140px)] lg:overflow-y-auto pr-0 lg:pr-2 custom-scrollbar">
            
            <!-- Step 1: Base Profile Metrics Details Forms -->
            <section class="bg-slate-900 border border-slate-800 rounded-xl p-5 shadow-xl space-y-4">
                <div class="flex items-center space-x-2 text-cyan-400 font-semibold text-sm tracking-wider uppercase">
                    <i class="fa-regular fa-user-circle text-base"></i>
                    <h2>Identity & Headline Configuration</h2>
                </div>
                <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                    <div>
                        <label class="block text-[11px] font-bold text-slate-400 uppercase tracking-widest mb-1.5">Profile Display Name</label>
                        <input type="text" id="name" value="Alex Morgan" class="w-full bg-slate-950 border border-slate-800 rounded-lg p-2.5 text-sm text-slate-200 focus:outline-none focus:border-cyan-500 transition-all font-medium">
                    </div>
                    <div>
                        <label class="block text-[11px] font-bold text-slate-400 uppercase tracking-widest mb-1.5">GitHub Target Handle</label>
                        <input type="text" id="username" value="alexmorgan" class="w-full bg-slate-950 border border-slate-800 rounded-lg p-2.5 text-sm text-slate-200 focus:outline-none focus:border-cyan-500 transition-all font-medium">
                    </div>
                </div>
                <div>
                    <label class="block text-[11px] font-bold text-slate-400 uppercase tracking-widest mb-1.5">Professional Banner Subtitle Headline</label>
                    <input type="text" id="title" value="Senior Full-Stack Engineer specializing in cloud-native microservices distributed systems architectures." class="w-full bg-slate-950 border border-slate-800 rounded-lg p-2.5 text-sm text-slate-200 focus:outline-none focus:border-cyan-500 transition-all font-medium">
                </div>
            </section>

            <!-- Step 2: About Me Pipeline Descriptions Elements -->
            <section class="bg-slate-900 border border-slate-800 rounded-xl p-5 shadow-xl space-y-3">
                <div class="flex items-center space-x-2 text-emerald-400 font-semibold text-sm tracking-wider uppercase">
                    <i class="fa-solid fa-briefcase text-base"></i>
                    <h2>Professional Status / Milestones</h2>
                </div>
                <div>
                    <input type="text" id="working" value="building high-throughput real-time analytics streaming pipelines." placeholder="🔭 Currently focused working infrastructure assignments..." class="w-full bg-slate-950 border border-slate-800 rounded-lg p-2.5 text-sm text-slate-300 focus:outline-none focus:border-emerald-500 transition-all">
                </div>
                <div>
                    <input type="text" id="learning" value="WebAssembly execution optimizations and advanced system safety routines in Rust language primitives." placeholder="🌱 Actively building knowledge proficiencies around..." class="w-full bg-slate-950 border border-slate-800 rounded-lg p-2.5 text-sm text-slate-300 focus:outline-none focus:border-emerald-500 transition-all">
                </div>
                <div>
                    <input type="text" id="collaborate" value="open-source distributed database scaling or high performance execution layers." placeholder="🤝 Open for prospective project collaboration avenues relative to..." class="w-full bg-slate-950 border border-slate-800 rounded-lg p-2.5 text-sm text-slate-300 focus:outline-none focus:border-emerald-500 transition-all">
                </div>
            </section>

            <!-- Step 3: Social Connectivity Handles Map Configurations -->
            <section class="bg-slate-900 border border-slate-800 rounded-xl p-5 shadow-xl space-y-4">
                <div class="flex items-center space-x-2 text-purple-400 font-semibold text-sm tracking-wider uppercase">
                    <i class="fa-solid fa-share-nodes text-base"></i>
                    <h2>Social Networks Networks Linkages</h2>
                </div>
                <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                    <div class="relative">
                        <span class="absolute inset-y-0 left-0 pl-3 flex items-center text-slate-500"><i class="fa-brands fa-linkedin"></i></span>
                        <input type="text" id="linkedin" placeholder="LinkedIn Username" class="w-full bg-slate-950 border border-slate-800 rounded-lg pl-9 p-2 text-xs focus:outline-none focus:border-purple-500 text-slate-300">
                    </div>
                    <div class="relative">
                        <span class="absolute inset-y-0 left-0 pl-3 flex items-center text-slate-500"><i class="fa-brands fa-x-twitter"></i></span>
                        <input type="text" id="twitter" placeholder="X / Twitter Username" class="w-full bg-slate-950 border border-slate-800 rounded-lg pl-9 p-2 text-xs focus:outline-none focus:border-purple-500 text-slate-300">
                    </div>
                    <div class="relative">
                        <span class="absolute inset-y-0 left-0 pl-3 flex items-center text-slate-500"><i class="fa-solid fa-envelope"></i></span>
                        <input type="text" id="email" placeholder="Professional Business Email" class="w-full bg-slate-950 border border-slate-800 rounded-lg pl-9 p-2 text-xs focus:outline-none focus:border-purple-500 text-slate-300">
                    </div>
                    <div class="relative">
                        <span class="absolute inset-y-0 left-0 pl-3 flex items-center text-slate-500"><i class="fa-solid fa-globe"></i></span>
                        <input type="text" id="portfolio" placeholder="Portfolio Website URL" class="w-full bg-slate-950 border border-slate-800 rounded-lg pl-9 p-2 text-xs focus:outline-none focus:border-purple-500 text-slate-300">
                    </div>
                </div>
            </section>

            <!-- Step 4: Tech Stack Matrix Groups Categories (Complete Architecture Inventory) -->
            <section class="bg-slate-900 border border-slate-800 rounded-xl p-5 shadow-xl space-y-5">
                <div class="flex items-center justify-between border-b border-slate-800 pb-3">
                    <div class="flex items-center space-x-2 text-amber-400 font-semibold text-sm tracking-wider uppercase">
                        <i class="fa-solid fa-layer-group text-base"></i>
                        <h2>Comprehensive Tech Stack Inventory</h2>
                    </div>
                    <button id="selectAllTech" class="text-[10px] uppercase font-bold text-slate-400 hover:text-amber-400 transition-colors">Select All</button>
                </div>
                <div id="tech-categories-container" class="space-y-4">
                    <!-- Dynamic rendering engine target pipeline insertion logic hooks -->
                </div>
            </section>








