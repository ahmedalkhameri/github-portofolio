<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ahmed Abdo Al-Khameri | Electrical & BIM Engineer Portfolio</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&family=JetBrains+Mono:wght@400;600&display=swap" rel="stylesheet">
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        slate: {
                            850: '#0f172a',
                            900: '#0b1120',
                            950: '#070c18',
                        },
                        electric: {
                            400: '#38bdf8',
                            500: '#0ea5e9',
                            600: '#0284c7',
                        }
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                        mono: ['JetBrains Mono', 'monospace'],
                    }
                }
            }
        }
    </script>

    <style>
        /* Custom Glowing & Backdrop Effects */
        .glow-cyan {
            box-shadow: 0 0 25px -5px rgba(14, 165, 233, 0.3);
        }
        .glow-cyan-lg {
            box-shadow: 0 0 40px -5px rgba(14, 165, 233, 0.45);
        }
        .bg-grid-pattern {
            background-image: radial-gradient(rgba(56, 189, 248, 0.1) 1px, transparent 1px);
            background-size: 30px 30px;
        }
        .text-gradient {
            background: linear-gradient(135deg, #ffffff 30%, #38bdf8 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .text-gradient-cyan {
            background: linear-gradient(135deg, #38bdf8 0%, #818cf8 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        /* Custom scrollbar */
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #0b1120;
        }
        ::-webkit-scrollbar-thumb {
            background: #1e293b;
            border-radius: 4px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #0ea5e9;
        }
    </style>
</head>
<body class="bg-slate-950 text-slate-200 font-sans antialiased selection:bg-electric-500 selection:text-white">

    <!-- NAVIGATION BAR -->
    <nav class="fixed top-0 left-0 right-0 z-50 bg-slate-900/80 backdrop-blur-md border-b border-slate-800/80 transition-all duration-300" id="navbar">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-20">
                <!-- Brand Logo -->
                <a href="#hero" class="flex items-center space-x-3 group">
                    <div class="w-10 h-10 rounded-xl bg-gradient-to-tr from-electric-600 to-cyan-400 flex items-center justify-center text-slate-950 font-bold text-xl shadow-lg group-hover:scale-105 transition-transform">
                        <i class="fa-solid font-mono fa-bolt"></i>
                    </div>
                    <div>
                        <span class="text-lg font-bold tracking-tight text-white block">AHMED AL-KHAMERI</span>
                        <span class="text-xs text-electric-400 font-mono tracking-wider uppercase block">Electrical & BIM Engineer</span>
                    </div>
                </a>

                <!-- Desktop Menu -->
                <div class="hidden md:flex items-center space-x-8 text-sm font-medium">
                    <a href="#about" class="text-slate-300 hover:text-electric-400 transition-colors">About</a>
                    <a href="#skills" class="text-slate-300 hover:text-electric-400 transition-colors">Skills & Stack</a>
                    <a href="#projects" class="text-slate-300 hover:text-electric-400 transition-colors">Projects</a>
                    <a href="#experience" class="text-slate-300 hover:text-electric-400 transition-colors">Experience</a>
                    <a href="#certifications" class="text-slate-300 hover:text-electric-400 transition-colors">Certifications</a>
                    <a href="#contact" class="px-4 py-2.5 rounded-lg bg-electric-500 hover:bg-electric-600 text-slate-950 font-semibold transition-all shadow-md hover:shadow-electric-500/20">Contact Me</a>
                </div>

                <!-- Mobile Menu Button -->
                <div class="md:hidden">
                    <button id="mobile-menu-btn" type="button" class="text-slate-400 hover:text-white focus:outline-none p-2" aria-label="Toggle Menu">
                        <i class="fa-solid fa-bars text-2xl"></i>
                    </button>
                </div>
            </div>
        </div>

        <!-- Mobile Menu Dropdown -->
        <div id="mobile-menu" class="hidden md:hidden bg-slate-900 border-b border-slate-800 px-4 pt-2 pb-6 space-y-3">
            <a href="#about" class="mobile-link block py-2 text-slate-300 hover:text-electric-400">About</a>
            <a href="#skills" class="mobile-link block py-2 text-slate-300 hover:text-electric-400">Skills & Stack</a>
            <a href="#projects" class="mobile-link block py-2 text-slate-300 hover:text-electric-400">Projects</a>
            <a href="#experience" class="mobile-link block py-2 text-slate-300 hover:text-electric-400">Experience</a>
            <a href="#certifications" class="mobile-link block py-2 text-slate-300 hover:text-electric-400">Certifications</a>
            <a href="#contact" class="mobile-link block py-2.5 text-center rounded-lg bg-electric-500 text-slate-950 font-semibold">Contact Me</a>
        </div>
    </nav>

    <!-- HERO SECTION -->
    <section id="hero" class="relative pt-32 pb-20 md:pt-44 md:pb-32 overflow-hidden bg-grid-pattern">
        <!-- Glow accents -->
        <div class="absolute top-1/4 left-1/2 -translate-x-1/2 -translate-y-1/2 w-[600px] h-[300px] bg-electric-500/10 blur-[120px] rounded-full pointer-events-none"></div>

        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
                <!-- Bio Text -->
                <div class="lg:col-span-7 space-y-6 text-center lg:text-left">
                    <div class="inline-flex items-center gap-2 px-3 py-1.5 rounded-full bg-slate-800/80 border border-slate-700 text-electric-400 text-xs font-mono uppercase tracking-wider">
                        <span class="w-2 h-2 rounded-full bg-emerald-400 animate-ping"></span>
                        Available for MEP & Solar Engineering Roles in the Gulf & MENA
                    </div>
                    
                    <h1 class="text-4xl sm:text-5xl lg:text-6xl font-extrabold text-white tracking-tight leading-tight">
                        Eng. Ahmed Abdo <br>
                        <span class="text-gradient">Al-Khameri</span>
                    </h1>

                    <p class="text-xl text-slate-400 font-medium max-w-2xl">
                        Electrical Power Engineer specialized in <span class="text-white font-semibold">Electrical Distribution Design</span>, <span class="text-white font-semibold">BIM / Revit MEP Coordination</span>, and <span class="text-white font-semibold">Utility/Industrial Solar PV Systems</span>.
                    </p>

                    <!-- Contact Quick Info -->
                    <div class="flex flex-wrap justify-center lg:justify-start gap-4 text-xs font-mono text-slate-400 pt-2">
                        <span class="flex items-center gap-2"><i class="fa-solid fa-location-dot text-electric-400"></i> Cairo, Egypt</span>
                        <span class="flex items-center gap-2"><i class="fa-solid fa-envelope text-electric-400"></i> ahmedalkhameri98@gmail.com</span>
                        <span class="flex items-center gap-2"><i class="fa-solid fa-phone text-electric-400"></i> +20 114 925 4924</span>
                    </div>

                    <!-- Call to action buttons -->
                    <div class="flex flex-wrap items-center justify-center lg:justify-start gap-4 pt-4">
                        <a href="#projects" class="px-6 py-3.5 rounded-xl bg-electric-500 hover:bg-electric-600 text-slate-950 font-bold transition-all shadow-lg glow-cyan flex items-center gap-2">
                            <i class="fa-solid fa-diagram-project"></i> Explore Projects
                        </a>
                        <button onclick="downloadCV()" class="px-6 py-3.5 rounded-xl bg-slate-800 hover:bg-slate-700 text-white font-semibold border border-slate-700 transition-all flex items-center gap-2">
                            <i class="fa-solid fa-file-arrow-down text-electric-400"></i> Download CV
                        </button>
                        <a href="https://linkedin.com/in/ahmedalkhameri" target="_blank" rel="noopener noreferrer" class="p-3.5 rounded-xl bg-slate-800 hover:bg-slate-700 text-slate-300 border border-slate-700 transition-all">
                            <i class="fa-brands fa-linkedin text-xl"></i>
                        </a>
                    </div>
                </div>

                <!-- Highlight Card / Banner -->
                <div class="lg:col-span-5">
                    <div class="bg-gradient-to-b from-slate-800/90 to-slate-900/90 rounded-2xl p-6 border border-slate-700/80 shadow-2xl relative">
                        <div class="absolute -top-3 -right-3 bg-electric-500 text-slate-950 text-xs font-bold px-3 py-1 rounded-full uppercase tracking-wider">
                            Verified Credentials
                        </div>
                        
                        <h3 class="text-slate-400 text-xs font-mono uppercase tracking-widest mb-4">Core Focus & Specializations</h3>

                        <div class="space-y-4">
                            <div class="p-4 rounded-xl bg-slate-950/60 border border-slate-800/80 flex items-start gap-4">
                                <div class="w-10 h-10 rounded-lg bg-cyan-500/10 border border-cyan-500/20 text-cyan-400 flex items-center justify-center flex-shrink-0">
                                    <i class="fa-solid fa-solar-panel text-lg"></i>
                                </div>
                                <div>
                                    <h4 class="text-white font-bold text-sm">Solar PV System Design</h4>
                                    <p class="text-slate-400 text-xs mt-1">1,500+ kWp utility/industrial PV design, grid integration, and PVsyst yield simulation.</p>
                                </div>
                            </div>

                            <div class="p-4 rounded-xl bg-slate-950/60 border border-slate-800/80 flex items-start gap-4">
                                <div class="w-10 h-10 rounded-lg bg-electric-500/10 border border-electric-500/20 text-electric-400 flex items-center justify-center flex-shrink-0">
                                    <i class="fa-solid fa-cubes text-lg"></i>
                                </div>
                                <div>
                                    <h4 class="text-white font-bold text-sm">Certified BIM Management</h4>
                                    <p class="text-slate-400 text-xs mt-1">Certified BIM Manager & BIM Coordinator (Niqat). Multi-discipline MEP clash resolution.</p>
                                </div>
                            </div>

                            <div class="p-4 rounded-xl bg-slate-950/60 border border-slate-800/80 flex items-start gap-4">
                                <div class="w-10 h-10 rounded-lg bg-indigo-500/10 border border-indigo-500/20 text-indigo-400 flex items-center justify-center flex-shrink-0">
                                    <i class="fa-solid fa-building-shield text-lg"></i>
                                </div>
                                <div>
                                    <h4 class="text-white font-bold text-sm">Electrical Distribution Design</h4>
                                    <p class="text-slate-400 text-xs mt-1">Single Line Diagrams, Panel Schedules, ETAP short-circuit analysis, and Low Current Systems.</p>
                                </div>
                            </div>
                        </div>

                        <!-- Syndicate Membership Badge -->
                        <div class="mt-5 pt-4 border-t border-slate-800 flex items-center justify-between text-xs text-slate-400">
                            <span class="flex items-center gap-1.5"><i class="fa-solid fa-id-card text-emerald-400"></i> Egyptian Engineers Syndicate</span>
                            <span class="text-slate-500 font-mono">Cairo Branch</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- KEY METRICS COUNTER BAR -->
    <section class="py-10 bg-slate-900 border-y border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-2 md:grid-cols-4 gap-6 text-center">
                <div class="p-4 rounded-xl bg-slate-850/50 border border-slate-800">
                    <div class="text-3xl lg:text-4xl font-extrabold text-electric-400 font-mono" id="counter-pv">1,500+</div>
                    <div class="text-xs uppercase tracking-wider text-slate-400 mt-1">kWp Solar PV Simulated</div>
                </div>
                <div class="p-4 rounded-xl bg-slate-850/50 border border-slate-800">
                    <div class="text-3xl lg:text-4xl font-extrabold text-white font-mono">3+</div>
                    <div class="text-xs uppercase tracking-wider text-slate-400 mt-1">Countries Project Experience (EG, YE, UAE)</div>
                </div>
                <div class="p-4 rounded-xl bg-slate-850/50 border border-slate-800">
                    <div class="text-3xl lg:text-4xl font-extrabold text-electric-400 font-mono">100%</div>
                    <div class="text-xs uppercase tracking-wider text-slate-400 mt-1">Clash-Free BIM Delivery Target</div>
                </div>
                <div class="p-4 rounded-xl bg-slate-850/50 border border-slate-800">
                    <div class="text-3xl lg:text-4xl font-extrabold text-white font-mono">Excellent</div>
                    <div class="text-xs uppercase tracking-wider text-slate-400 mt-1">Graduation Project Rating</div>
                </div>
            </div>
        </div>
    </section>

    <!-- EXECUTIVE SUMMARY / ABOUT SECTION -->
    <section id="about" class="py-20 bg-slate-950">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col md:flex-row md:items-end justify-between mb-12">
                <div>
                    <h2 class="text-xs font-mono uppercase tracking-widest text-electric-400 mb-2">// Executive Summary</h2>
                    <p class="text-3xl sm:text-4xl font-extrabold text-white tracking-tight">Engineering Precision & Technical Office Leadership</p>
                </div>
                <p class="text-slate-400 text-sm max-w-md mt-4 md:mt-0">
                    Bridging computational design, BIM standards, and practical site supervision for complex construction projects.
                </p>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-3 gap-8">
                <div class="p-6 rounded-2xl bg-slate-900 border border-slate-800 hover:border-slate-700 transition-all">
                    <div class="w-12 h-12 rounded-xl bg-electric-500/10 text-electric-400 flex items-center justify-center mb-6 text-xl">
                        <i class="fa-solid fa-compass-drafting"></i>
                    </div>
                    <h3 class="text-xl font-bold text-white mb-3">Electrical Distribution Design</h3>
                    <p class="text-slate-400 text-sm leading-relaxed">
                        Extensive hands-on experience in load calculations, panel schedules, cable tray routing, single-line diagrams (SLDs), and auxiliary low-current systems (Fire Alarm, CCTV, Data) according to international IEC and local codes.
                    </p>
                </div>

                <div class="p-6 rounded-2xl bg-slate-900 border border-slate-800 hover:border-slate-700 transition-all">
                    <div class="w-12 h-12 rounded-xl bg-cyan-500/10 text-cyan-400 flex items-center justify-center mb-6 text-xl">
                        <i class="fa-solid fa-layer-group"></i>
                    </div>
                    <h3 class="text-xl font-bold text-white mb-3">MEP/BIM Coordination</h3>
                    <p class="text-slate-400 text-sm leading-relaxed">
                        Certified BIM Coordinator and Manager skilled in Revit MEP, workset management, custom family creation, and automated clash detection. Seamlessly coordinates electrical infrastructure with HVAC, structural, and architectural elements.
                    </p>
                </div>

                <div class="p-6 rounded-2xl bg-slate-900 border border-slate-800 hover:border-slate-700 transition-all">
                    <div class="w-12 h-12 rounded-xl bg-emerald-500/10 text-emerald-400 flex items-center justify-center mb-6 text-xl">
                        <i class="fa-solid fa-sun"></i>
                    </div>
                    <h3 class="text-xl font-bold text-white mb-3">Solar PV Integration</h3>
                    <p class="text-slate-400 text-sm leading-relaxed">
                        Proficient in solar irradiance modeling, inverter matching, shadow mitigation, and grid injection design using PVsyst. Specialized in integrating solar PV into commercial, industrial, and oil & gas power infrastructure.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- CORE SKILLS & SOFTWARE MATRIX -->
    <section id="skills" class="py-20 bg-slate-900 border-t border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <h2 class="text-xs font-mono uppercase tracking-widest text-electric-400 mb-2">// Technical Expertise</h2>
                <p class="text-3xl sm:text-4xl font-extrabold text-white">Software Matrix & Technical Capabilities</p>
                <p class="text-slate-400 text-sm mt-3">Filter by domain to inspect engineering toolsets and methodologies.</p>
            </div>

            <!-- Skill Domain Filter Tabs -->
            <div class="flex flex-wrap justify-center gap-2 mb-12" id="skill-filter-buttons">
                <button data-filter="all" class="skill-tab active px-5 py-2.5 rounded-xl bg-electric-500 text-slate-950 font-semibold text-sm transition-all">All Capabilities</button>
                <button data-filter="software" class="skill-tab px-5 py-2.5 rounded-xl bg-slate-800 hover:bg-slate-700 text-slate-300 font-medium text-sm transition-all">Design Software</button>
                <button data-filter="electrical" class="skill-tab px-5 py-2.5 rounded-xl bg-slate-800 hover:bg-slate-700 text-slate-300 font-medium text-sm transition-all">Electrical & Low Current</button>
                <button data-filter="bim" class="skill-tab px-5 py-2.5 rounded-xl bg-slate-800 hover:bg-slate-700 text-slate-300 font-medium text-sm transition-all">BIM & Coordination</button>
                <button data-filter="solar" class="skill-tab px-5 py-2.5 rounded-xl bg-slate-800 hover:bg-slate-700 text-slate-300 font-medium text-sm transition-all">Solar PV Systems</button>
            </div>

            <!-- Skills Grid -->
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6" id="skills-container">

                <!-- Software Items -->
                <div class="skill-item software p-5 rounded-xl bg-slate-850 border border-slate-800 flex items-center space-x-4">
                    <div class="w-12 h-12 rounded-lg bg-blue-600/20 text-blue-400 flex items-center justify-center font-mono font-bold">Rvt</div>
                    <div>
                        <h4 class="text-white font-semibold text-sm">Revit (Electrical BIM)</h4>
                        <p class="text-xs text-slate-400 mt-0.5">Family creation, worksets, 3D MEP models</p>
                    </div>
                </div>

                <div class="skill-item software p-5 rounded-xl bg-slate-850 border border-slate-800 flex items-center space-x-4">
                    <div class="w-12 h-12 rounded-lg bg-red-600/20 text-red-400 flex items-center justify-center font-mono font-bold">CAD</div>
                    <div>
                        <h4 class="text-white font-semibold text-sm">AutoCAD</h4>
                        <p class="text-xs text-slate-400 mt-0.5">Detailed shop drawings & schematics</p>
                    </div>
                </div>

                <div class="skill-item software solar p-5 rounded-xl bg-slate-850 border border-slate-800 flex items-center space-x-4">
                    <div class="w-12 h-12 rounded-lg bg-amber-500/20 text-amber-400 flex items-center justify-center font-mono font-bold">PVs</div>
                    <div>
                        <h4 class="text-white font-semibold text-sm">PVsyst</h4>
                        <p class="text-xs text-slate-400 mt-0.5">Solar PV simulation & yield calculation</p>
                    </div>
                </div>

                <div class="skill-item software electrical p-5 rounded-xl bg-slate-850 border border-slate-800 flex items-center space-x-4">
                    <div class="w-12 h-12 rounded-lg bg-emerald-500/20 text-emerald-400 flex items-center justify-center font-mono font-bold">DLX</div>
                    <div>
                        <h4 class="text-white font-semibold text-sm">DIALux evo</h4>
                        <p class="text-xs text-slate-400 mt-0.5">Lux calculations & interior/outdoor lighting</p>
                    </div>
                </div>

                <div class="skill-item software electrical p-5 rounded-xl bg-slate-850 border border-slate-800 flex items-center space-x-4">
                    <div class="w-12 h-12 rounded-lg bg-purple-500/20 text-purple-400 flex items-center justify-center font-mono font-bold">ETP</div>
                    <div>
                        <h4 class="text-white font-semibold text-sm">ETAP & Ecodial</h4>
                        <p class="text-xs text-slate-400 mt-0.5">Short-circuit & protection sizing</p>
                    </div>
                </div>

                <div class="skill-item software bim p-5 rounded-xl bg-slate-850 border border-slate-800 flex items-center space-x-4">
                    <div class="w-12 h-12 rounded-lg bg-teal-500/20 text-teal-400 flex items-center justify-center font-mono font-bold">Frm</div>
                    <div>
                        <h4 class="text-white font-semibold text-sm">Autodesk Forma</h4>
                        <p class="text-xs text-slate-400 mt-0.5">Conceptual site design & planning</p>
                    </div>
                </div>

                <!-- Electrical Domain Items -->
                <div class="skill-item electrical p-5 rounded-xl bg-slate-850 border border-slate-800 flex items-center space-x-4">
                    <div class="w-12 h-12 rounded-lg bg-electric-500/10 text-electric-400 flex items-center justify-center text-xl"><i class="fa-solid fa-calculator"></i></div>
                    <div>
                        <h4 class="text-white font-semibold text-sm">Load Calculations & Panel Schedules</h4>
                        <p class="text-xs text-slate-400 mt-0.5">MDB/SMDB load balancing & feeder sizing</p>
                    </div>
                </div>

                <div class="skill-item electrical p-5 rounded-xl bg-slate-850 border border-slate-800 flex items-center space-x-4">
                    <div class="w-12 h-12 rounded-lg bg-electric-500/10 text-electric-400 flex items-center justify-center text-xl"><i class="fa-solid fa-bell"></i></div>
                    <div>
                        <h4 class="text-white font-semibold text-sm">Low Current Systems</h4>
                        <p class="text-xs text-slate-400 mt-0.5">Fire Alarm, CCTV, Access Control & Data</p>
                    </div>
                </div>

                <!-- BIM Items -->
                <div class="skill-item bim p-5 rounded-xl bg-slate-850 border border-slate-800 flex items-center space-x-4">
                    <div class="w-12 h-12 rounded-lg bg-cyan-500/10 text-cyan-400 flex items-center justify-center text-xl"><i class="fa-solid fa-triangle-exclamation"></i></div>
                    <div>
                        <h4 class="text-white font-semibold text-sm">Clash Detection & Resolution</h4>
                        <p class="text-xs text-slate-400 mt-0.5">Multi-disciplinary MEP interferences</p>
                    </div>
                </div>

                <div class="skill-item bim p-5 rounded-xl bg-slate-850 border border-slate-800 flex items-center space-x-4">
                    <div class="w-12 h-12 rounded-lg bg-cyan-500/10 text-cyan-400 flex items-center justify-center text-xl"><i class="fa-solid fa-file-contract"></i></div>
                    <div>
                        <h4 class="text-white font-semibold text-sm">Technical Office & Shop Drawings</h4>
                        <p class="text-xs text-slate-400 mt-0.5">Tender packages, BOQ & standard specs</p>
                    </div>
                </div>

                <!-- Solar Items -->
                <div class="skill-item solar p-5 rounded-xl bg-slate-850 border border-slate-800 flex items-center space-x-4">
                    <div class="w-12 h-12 rounded-lg bg-amber-500/10 text-amber-400 flex items-center justify-center text-xl"><i class="fa-solid fa-plug"></i></div>
                    <div>
                        <h4 class="text-white font-semibold text-sm">Grid Integration</h4>
                        <p class="text-xs text-slate-400 mt-0.5">PV injection into existing switchgear</p>
                    </div>
                </div>

                <div class="skill-item software p-5 rounded-xl bg-slate-850 border border-slate-800 flex items-center space-x-4">
                    <div class="w-12 h-12 rounded-lg bg-cyan-500/20 text-cyan-400 flex items-center justify-center font-mono font-bold">SKP</div>
                    <div>
                        <h4 class="text-white font-semibold text-sm">SketchUp</h4>
                        <p class="text-xs text-slate-400 mt-0.5">3D conceptual layout visualization</p>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ENGINEERING PROJECTS SECTION -->
    <section id="projects" class="py-20 bg-slate-950">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col md:flex-row md:items-end justify-between mb-16">
                <div>
                    <h2 class="text-xs font-mono uppercase tracking-widest text-electric-400 mb-2">// Featured Projects</h2>
                    <p class="text-3xl sm:text-4xl font-extrabold text-white tracking-tight">Engineering Portfolio Highlights</p>
                </div>
                <p class="text-slate-400 text-sm max-w-md mt-4 md:mt-0">
                    Detailed breakdown of key commercial, healthcare, mega-development, and energy sector deliverables.
                </p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                
                <!-- Project Card 1: 1500 kWp Solar -->
                <div class="group bg-slate-900 rounded-2xl border border-slate-800 overflow-hidden hover:border-electric-500/50 transition-all duration-300 hover:shadow-xl flex flex-col">
                    <div class="h-48 bg-gradient-to-br from-amber-950/40 via-slate-900 to-slate-900 p-6 flex flex-col justify-between border-b border-slate-800 relative">
                        <div class="flex justify-between items-start">
                            <span class="px-3 py-1 rounded-full bg-amber-500/10 border border-amber-500/30 text-amber-400 text-xs font-mono">Solar Energy</span>
                            <span class="text-xs text-slate-500 font-mono">Industrial Sector</span>
                        </div>
                        <div>
                            <i class="fa-solid fa-solar-panel text-3xl text-amber-400 mb-2"></i>
                            <h3 class="text-xl font-bold text-white group-hover:text-electric-400 transition-colors">1,500+ kWp Solar PV System Design</h3>
                        </div>
                    </div>
                    <div class="p-6 flex-1 flex flex-col justify-between space-y-4">
                        <p class="text-slate-400 text-sm leading-relaxed">
                            Complete system sizing, solar irradiance modeling, shading analysis, and grid interconnection design for a high-demand oil & gas facility.
                        </p>
                        <div class="flex flex-wrap gap-2 text-xs font-mono">
                            <span class="px-2.5 py-1 rounded bg-slate-800 text-slate-300">PVsyst</span>
                            <span class="px-2.5 py-1 rounded bg-slate-800 text-slate-300">AutoCAD</span>
                            <span class="px-2.5 py-1 rounded bg-slate-800 text-slate-300">DIALux evo</span>
                        </div>
                        <button onclick="openModal('project1')" class="w-full py-2.5 rounded-lg bg-slate-800 hover:bg-electric-500 hover:text-slate-950 text-slate-300 font-semibold text-xs transition-all flex items-center justify-center gap-2">
                            View Engineering Details <i class="fa-solid fa-arrow-right"></i>
                        </button>
                    </div>
                </div>

                <!-- Project Card 2: Healthcare Cairo -->
                <div class="group bg-slate-900 rounded-2xl border border-slate-800 overflow-hidden hover:border-electric-500/50 transition-all duration-300 hover:shadow-xl flex flex-col">
                    <div class="h-48 bg-gradient-to-br from-blue-950/40 via-slate-900 to-slate-900 p-6 flex flex-col justify-between border-b border-slate-800 relative">
                        <div class="flex justify-between items-start">
                            <span class="px-3 py-1 rounded-full bg-blue-500/10 border border-blue-500/30 text-blue-400 text-xs font-mono">Healthcare / Hospital</span>
                            <span class="text-xs text-slate-500 font-mono">Cairo, Egypt</span>
                        </div>
                        <div>
                            <i class="fa-solid fa-hospital text-3xl text-blue-400 mb-2"></i>
                            <h3 class="text-xl font-bold text-white group-hover:text-electric-400 transition-colors">Healthcare Facility Electrical & BIM</h3>
                        </div>
                    </div>
                    <div class="p-6 flex-1 flex flex-col justify-between space-y-4">
                        <p class="text-slate-400 text-sm leading-relaxed">
                            Designed power continuity layouts, critical circuit segregation, emergency feeders, and clash-free Revit MEP models for a Cairo hospital.
                        </p>
                        <div class="flex flex-wrap gap-2 text-xs font-mono">
                            <span class="px-2.5 py-1 rounded bg-slate-800 text-slate-300">Revit MEP</span>
                            <span class="px-2.5 py-1 rounded bg-slate-800 text-slate-300">ETAP</span>
                            <span class="px-2.5 py-1 rounded bg-slate-800 text-slate-300">Ecodial</span>
                        </div>
                        <button onclick="openModal('project2')" class="w-full py-2.5 rounded-lg bg-slate-800 hover:bg-electric-500 hover:text-slate-950 text-slate-300 font-semibold text-xs transition-all flex items-center justify-center gap-2">
                            View Engineering Details <i class="fa-solid fa-arrow-right"></i>
                        </button>
                    </div>
                </div>

                <!-- Project Card 3: UAE Mega Project -->
                <div class="group bg-slate-900 rounded-2xl border border-slate-800 overflow-hidden hover:border-electric-500/50 transition-all duration-300 hover:shadow-xl flex flex-col">
                    <div class="h-48 bg-gradient-to-br from-purple-950/40 via-slate-900 to-slate-900 p-6 flex flex-col justify-between border-b border-slate-800 relative">
                        <div class="flex justify-between items-start">
                            <span class="px-3 py-1 rounded-full bg-purple-500/10 border border-purple-500/30 text-purple-400 text-xs font-mono">Mega Development</span>
                            <span class="text-xs text-slate-500 font-mono">UAE</span>
                        </div>
                        <div>
                            <i class="fa-solid fa-city text-3xl text-purple-400 mb-2"></i>
                            <h3 class="text-xl font-bold text-white group-hover:text-electric-400 transition-colors">Multi-Discipline MEP Coordination</h3>
                        </div>
                    </div>
                    <div class="p-6 flex-1 flex flex-col justify-between space-y-4">
                        <p class="text-slate-400 text-sm leading-relaxed">
                            Pre-construction clash resolution between Electrical, HVAC, Plumbing, and Structural elements using Autodesk Forma and Revit.
                        </p>
                        <div class="flex flex-wrap gap-2 text-xs font-mono">
                            <span class="px-2.5 py-1 rounded bg-slate-800 text-slate-300">Autodesk Forma</span>
                            <span class="px-2.5 py-1 rounded bg-slate-800 text-slate-300">Revit</span>
                            <span class="px-2.5 py-1 rounded bg-slate-800 text-slate-300">Clash Matrix</span>
                        </div>
                        <button onclick="openModal('project3')" class="w-full py-2.5 rounded-lg bg-slate-800 hover:bg-electric-500 hover:text-slate-950 text-slate-300 font-semibold text-xs transition-all flex items-center justify-center gap-2">
                            View Engineering Details <i class="fa-solid fa-arrow-right"></i>
                        </button>
                    </div>
                </div>

                <!-- Project Card 4: Yemen Residential -->
                <div class="group bg-slate-900 rounded-2xl border border-slate-800 overflow-hidden hover:border-electric-500/50 transition-all duration-300 hover:shadow-xl flex flex-col">
                    <div class="h-48 bg-gradient-to-br from-emerald-950/40 via-slate-900 to-slate-900 p-6 flex flex-col justify-between border-b border-slate-800 relative">
                        <div class="flex justify-between items-start">
                            <span class="px-3 py-1 rounded-full bg-emerald-500/10 border border-emerald-500/30 text-emerald-400 text-xs font-mono">Residential Complex</span>
                            <span class="text-xs text-slate-500 font-mono">Yemen</span>
                        </div>
                        <div>
                            <i class="fa-solid fa-house-chimney text-3xl text-emerald-400 mb-2"></i>
                            <h3 class="text-xl font-bold text-white group-hover:text-electric-400 transition-colors">High-Density Residential Network</h3>
                        </div>
                    </div>
                    <div class="p-6 flex-1 flex flex-col justify-between space-y-4">
                        <p class="text-slate-400 text-sm leading-relaxed">
                            Full electrical distribution design, branch circuit protection, low-voltage power feeding, outdoor illuminance, and panel schedule sizing.
                        </p>
                        <div class="flex flex-wrap gap-2 text-xs font-mono">
                            <span class="px-2.5 py-1 rounded bg-slate-800 text-slate-300">AutoCAD</span>
                            <span class="px-2.5 py-1 rounded bg-slate-800 text-slate-300">DIALux evo</span>
                            <span class="px-2.5 py-1 rounded bg-slate-800 text-slate-300">Panel Sizing</span>
                        </div>
                        <button onclick="openModal('project4')" class="w-full py-2.5 rounded-lg bg-slate-800 hover:bg-electric-500 hover:text-slate-950 text-slate-300 font-semibold text-xs transition-all flex items-center justify-center gap-2">
                            View Engineering Details <i class="fa-solid fa-arrow-right"></i>
                        </button>
                    </div>
                </div>

                <!-- Project Card 5: Educational Campus Graduation Project -->
                <div class="group bg-slate-900 rounded-2xl border border-slate-800 overflow-hidden hover:border-electric-500/50 transition-all duration-300 hover:shadow-xl flex flex-col lg:col-span-2">
                    <div class="h-48 bg-gradient-to-br from-cyan-950/40 via-slate-900 to-slate-900 p-6 flex flex-col justify-between border-b border-slate-800 relative">
                        <div class="flex justify-between items-start">
                            <span class="px-3 py-1 rounded-full bg-cyan-500/10 border border-cyan-500/30 text-cyan-400 text-xs font-mono">Graduation Project (Grade: Excellent)</span>
                            <span class="text-xs text-emerald-400 font-bold font-mono">Al-Azhar University</span>
                        </div>
                        <div>
                            <i class="fa-solid fa-graduation-cap text-3xl text-cyan-400 mb-2"></i>
                            <h3 class="text-2xl font-bold text-white group-hover:text-electric-400 transition-colors">Educational Campus Electrical Design with Integrated PV Source</h3>
                        </div>
                    </div>
                    <div class="p-6 flex-1 flex flex-col justify-between space-y-4">
                        <p class="text-slate-400 text-sm leading-relaxed">
                            Comprehensive graduation thesis covering total electrical load forecasting, main distribution switchgear selection, voltage drop analysis, single-line diagrams, and rooftop PV array injection into the building network.
                        </p>
                        <div class="flex flex-wrap gap-2 text-xs font-mono">
                            <span class="px-2.5 py-1 rounded bg-slate-800 text-slate-300">PVsyst</span>
                            <span class="px-2.5 py-1 rounded bg-slate-800 text-slate-300">ETAP</span>
                            <span class="px-2.5 py-1 rounded bg-slate-800 text-slate-300">AutoCAD</span>
                            <span class="px-2.5 py-1 rounded bg-slate-800 text-slate-300">DIALux evo</span>
                        </div>
                        <button onclick="openModal('project5')" class="w-full py-2.5 rounded-lg bg-slate-800 hover:bg-electric-500 hover:text-slate-950 text-slate-300 font-semibold text-xs transition-all flex items-center justify-center gap-2">
                            View Engineering Details <i class="fa-solid fa-arrow-right"></i>
                        </button>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- PROFESSIONAL EXPERIENCE SECTION -->
    <section id="experience" class="py-20 bg-slate-900 border-t border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <h2 class="text-xs font-mono uppercase tracking-widest text-electric-400 mb-2">// Career History</h2>
                <p class="text-3xl sm:text-4xl font-extrabold text-white">Professional Experience Timeline</p>
            </div>

            <div class="max-w-4xl mx-auto relative border-l-2 border-slate-800 pl-6 sm:pl-10 space-y-12">
                
                <!-- Experience Item 1 -->
                <div class="relative group">
                    <!-- Timeline point -->
                    <div class="absolute -left-[31px] sm:-left-[47px] top-1.5 w-6 h-6 rounded-full bg-slate-950 border-2 border-electric-500 group-hover:scale-125 transition-transform flex items-center justify-center">
                        <div class="w-2 h-2 rounded-full bg-electric-400"></div>
                    </div>

                    <div class="bg-slate-850 p-6 sm:p-8 rounded-2xl border border-slate-800 hover:border-slate-700 transition-all">
                        <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-2 mb-4">
                            <div>
                                <h3 class="text-xl font-bold text-white">Electrical Engineer</h3>
                                <p class="text-electric-400 font-medium text-sm">Diar Consulting Group | Cairo, Egypt</p>
                            </div>
                            <span class="px-3 py-1 rounded-full bg-slate-800 text-slate-400 text-xs font-mono self-start sm:self-auto border border-slate-700">Jan 2026 – Present</span>
                        </div>
                        <ul class="space-y-3 text-slate-300 text-sm leading-relaxed list-disc list-inside marker:text-electric-400">
                            <li>Lead electrical design and technical office deliverables, producing shop drawings, panel schedules, and electrical layouts for large-scale building projects (Cairo Hospital, Yemen Residential, UAE Mega Project).</li>
                            <li>Design and simulate 1,500+ kWp solar PV systems for oil and gas infrastructure using PVsyst.</li>
                            <li>Coordinate MEP systems with cross-functional design teams using Revit and Autodesk Forma, identifying and resolving clashes prior to site mobilization.</li>
                            <li>Maintain rigorous quality control and code compliance across technical drawings and engineering calculations submitted for client review.</li>
                        </ul>
                    </div>
                </div>

                <!-- Experience Item 2 -->
                <div class="relative group">
                    <div class="absolute -left-[31px] sm:-left-[47px] top-1.5 w-6 h-6 rounded-full bg-slate-950 border-2 border-slate-600 group-hover:scale-125 transition-transform flex items-center justify-center">
                        <div class="w-2 h-2 rounded-full bg-slate-400"></div>
                    </div>

                    <div class="bg-slate-850 p-6 sm:p-8 rounded-2xl border border-slate-800 hover:border-slate-700 transition-all">
                        <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-2 mb-4">
                            <div>
                                <h3 class="text-xl font-bold text-white">Electrical Engineer (Site & Execution)</h3>
                                <p class="text-electric-400 font-medium text-sm">Epos Innovation | Cairo, Egypt</p>
                            </div>
                            <span class="px-3 py-1 rounded-full bg-slate-800 text-slate-400 text-xs font-mono self-start sm:self-auto border border-slate-700">Aug 2025 – Jan 2026</span>
                        </div>
                        <ul class="space-y-3 text-slate-300 text-sm leading-relaxed list-disc list-inside marker:text-electric-400">
                            <li>Supervised construction sites from project inception through completion, aligning electrical implementation with approved shop drawings.</li>
                            <li>Executed site inspections to identify technical spatial clashes and enforced health & safety compliance across subcontractor teams.</li>
                            <li>Coordinated with project managers to streamline workflow, improve installation efficiency, and ensure on-time milestone delivery.</li>
                        </ul>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- CERTIFICATIONS & CREDENTIALS SECTION -->
    <section id="certifications" class="py-20 bg-slate-950">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col md:flex-row md:items-end justify-between mb-16">
                <div>
                    <h2 class="text-xs font-mono uppercase tracking-widest text-electric-400 mb-2">// Accreditations & Diplomas</h2>
                    <p class="text-3xl sm:text-4xl font-extrabold text-white tracking-tight">Verified Certifications & Training</p>
                </div>
                <p class="text-slate-400 text-sm max-w-md mt-4 md:mt-0">
                    Official BIM management credentials, Autodesk learning partner certificates, and specialized engineering diplomas.
                </p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">

                <!-- Cert Card 1: Certified BIM Manager -->
                <div class="p-6 rounded-2xl bg-slate-900 border border-slate-800 hover:border-slate-700 transition-all relative flex flex-col justify-between">
                    <div>
                        <div class="flex items-center justify-between mb-4">
                            <span class="px-2.5 py-1 rounded bg-purple-500/10 text-purple-400 text-xs font-mono font-semibold">Niqat</span>
                            <span class="text-xs text-slate-500">Credential Never Expires</span>
                        </div>
                        <h3 class="text-lg font-bold text-white mb-2">Certified BIM Manager</h3>
                        <p class="text-xs text-slate-400 mb-4">3-Month Training Program (30 Hours). Certified by Niqat & Autodesk Learning Partners.</p>
                    </div>
                    <div class="pt-4 border-t border-slate-800 flex items-center justify-between text-xs">
                        <span class="text-slate-400 font-mono"><i class="fa-solid fa-award text-amber-400"></i> Verification ID: d8c3...e44c1</span>
                    </div>
                </div>

                <!-- Cert Card 2: Certified BIM Coordinator -->
                <div class="p-6 rounded-2xl bg-slate-900 border border-slate-800 hover:border-slate-700 transition-all relative flex flex-col justify-between">
                    <div>
                        <div class="flex items-center justify-between mb-4">
                            <span class="px-2.5 py-1 rounded bg-purple-500/10 text-purple-400 text-xs font-mono font-semibold">Niqat</span>
                            <span class="text-xs text-slate-500">Credential Never Expires</span>
                        </div>
                        <h3 class="text-lg font-bold text-white mb-2">Certified BIM Coordinator (Buildings)</h3>
                        <p class="text-xs text-slate-400 mb-4">3-Month Program covering multi-discipline MEP clash matrix and building transformations.</p>
                    </div>
                    <div class="pt-4 border-t border-slate-800 flex items-center justify-between text-xs">
                        <span class="text-slate-400 font-mono"><i class="fa-solid fa-award text-amber-400"></i> Verification ID: 0505...b36c5</span>
                    </div>
                </div>

                <!-- Cert Card 3: Electrical Revit Diploma -->
                <div class="p-6 rounded-2xl bg-slate-900 border border-slate-800 hover:border-slate-700 transition-all relative flex flex-col justify-between">
                    <div>
                        <div class="flex items-center justify-between mb-4">
                            <span class="px-2.5 py-1 rounded bg-blue-500/10 text-blue-400 text-xs font-mono font-semibold">Mohamed Emam Courses</span>
                            <span class="text-xs text-emerald-400 font-bold font-mono">Grade: Very Good</span>
                        </div>
                        <h3 class="text-lg font-bold text-white mb-2">Electrical Revit Diploma</h3>
                        <p class="text-xs text-slate-400 mb-4">Worksets management, family creation, cable tray design, panel schedules, and low current integration.</p>
                    </div>
                    <div class="pt-4 border-t border-slate-800 flex items-center justify-between text-xs text-slate-400 font-mono">
                        <span><i class="fa-regular fa-calendar"></i> Issued: Sept 2024</span>
                    </div>
                </div>

                <!-- Cert Card 4: Eduneers Advanced Course -->
                <div class="p-6 rounded-2xl bg-slate-900 border border-slate-800 hover:border-slate-700 transition-all relative flex flex-col justify-between">
                    <div>
                        <div class="flex items-center justify-between mb-4">
                            <span class="px-2.5 py-1 rounded bg-amber-500/10 text-amber-400 text-xs font-mono font-semibold">Eduneers</span>
                            <span class="text-xs text-slate-500">3-Month Intensive</span>
                        </div>
                        <h3 class="text-lg font-bold text-white mb-2">Electrical Technical Office & Design</h3>
                        <p class="text-xs text-slate-400 mb-4">Advanced course in Electrical Design, Technical Office, Site Implementation, and Tendering.</p>
                    </div>
                    <div class="pt-4 border-t border-slate-800 flex items-center justify-between text-xs text-slate-400 font-mono">
                        <span><i class="fa-regular fa-calendar"></i> July – Oct 2024</span>
                    </div>
                </div>

                <!-- Cert Card 5: Engovation Solar -->
                <div class="p-6 rounded-2xl bg-slate-900 border border-slate-800 hover:border-slate-700 transition-all relative flex flex-col justify-between">
                    <div>
                        <div class="flex items-center justify-between mb-4">
                            <span class="px-2.5 py-1 rounded bg-emerald-500/10 text-emerald-400 text-xs font-mono font-semibold">Engovation</span>
                            <span class="text-xs text-slate-500">30 Hours Training</span>
                        </div>
                        <h3 class="text-lg font-bold text-white mb-2">Solar Energy Training Diploma</h3>
                        <p class="text-xs text-slate-400 mb-4">Solar PV system sizing, inverter topology, battery storage integration, and tilt-angle optimization.</p>
                    </div>
                    <div class="pt-4 border-t border-slate-800 flex items-center justify-between text-xs text-slate-400 font-mono">
                        <span><i class="fa-regular fa-calendar"></i> July – Aug 2022</span>
                    </div>
                </div>

                <!-- Cert Card 6: Egyptian Syndicate Card -->
                <div class="p-6 rounded-2xl bg-slate-900 border border-slate-800 hover:border-slate-700 transition-all relative flex flex-col justify-between border-l-4 border-l-emerald-500">
                    <div>
                        <div class="flex items-center justify-between mb-4">
                            <span class="px-2.5 py-1 rounded bg-emerald-500/10 text-emerald-400 text-xs font-mono font-semibold">Official Syndicate</span>
                            <span class="text-xs text-emerald-400 font-bold">Active Member</span>
                        </div>
                        <h3 class="text-lg font-bold text-white mb-2">Egyptian Engineers Syndicate Member</h3>
                        <p class="text-xs text-slate-400 mb-4">Licensed Electrical Power & Machines Engineer. Registered at the Cairo Branch office.</p>
                    </div>
                    <div class="pt-4 border-t border-slate-800 flex items-center justify-between text-xs text-slate-400 font-mono">
                        <span><i class="fa-solid fa-passport text-emerald-400"></i> Reg No: 29810248801116</span>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- EDUCATION & LANGUAGES SECTION -->
    <section class="py-20 bg-slate-900 border-t border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-12">
                
                <!-- Education Column -->
                <div>
                    <h2 class="text-xs font-mono uppercase tracking-widest text-electric-400 mb-2">// Academic Background</h2>
                    <h3 class="text-3xl font-extrabold text-white mb-8">Bachelor of Science Degree</h3>

                    <div class="bg-slate-850 rounded-2xl p-6 sm:p-8 border border-slate-800 space-y-4">
                        <div class="flex items-start justify-between">
                            <div>
                                <h4 class="text-xl font-bold text-white">B.Sc. Electrical Power & Machine Engineering</h4>
                                <p class="text-electric-400 text-sm">Al-Azhar University, Cairo, Egypt</p>
                            </div>
                            <span class="px-3 py-1 rounded-full bg-slate-800 text-slate-300 text-xs font-mono">Graduated 2024</span>
                        </div>

                        <div class="pt-4 border-t border-slate-800 flex flex-wrap gap-4 text-xs font-mono">
                            <span class="px-3 py-1.5 rounded-lg bg-slate-900 border border-slate-700 text-slate-300">Overall Grade: <strong class="text-white">Good</strong></span>
                            <span class="px-3 py-1.5 rounded-lg bg-emerald-500/10 border border-emerald-500/30 text-emerald-400">Graduation Project Grade: <strong>Excellent</strong></span>
                        </div>

                        <p class="text-xs text-slate-400 leading-relaxed pt-2">
                            Curriculum focused on power system analysis, electrical machine modeling, high voltage engineering, electrical distribution networks, control systems, and renewable energy integration.
                        </p>
                    </div>
                </div>

                <!-- Languages & Soft Skills Column -->
                <div>
                    <h2 class="text-xs font-mono uppercase tracking-widest text-electric-400 mb-2">// Communication & Competencies</h2>
                    <h3 class="text-3xl font-extrabold text-white mb-8">Languages & Leadership</h3>

                    <div class="space-y-6">
                        <!-- Languages Card -->
                        <div class="bg-slate-850 rounded-2xl p-6 border border-slate-800 space-y-4">
                            <h4 class="text-sm font-bold text-slate-300 uppercase tracking-wider font-mono">Language Proficiency</h4>
                            
                            <div class="space-y-3">
                                <div>
                                    <div class="flex justify-between text-xs font-semibold mb-1">
                                        <span class="text-white">Arabic (Native)</span>
                                        <span class="text-electric-400 font-mono">100%</span>
                                    </div>
                                    <div class="w-full h-2 rounded-full bg-slate-900 overflow-hidden">
                                        <div class="h-full bg-electric-500 rounded-full w-full"></div>
                                    </div>
                                </div>

                                <div>
                                    <div class="flex justify-between text-xs font-semibold mb-1">
                                        <span class="text-white">English (Very Good / Professional)</span>
                                        <span class="text-electric-400 font-mono">85%</span>
                                    </div>
                                    <div class="w-full h-2 rounded-full bg-slate-900 overflow-hidden">
                                        <div class="h-full bg-electric-500 rounded-full w-[85%]"></div>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <!-- Professional Core Competencies -->
                        <div class="bg-slate-850 rounded-2xl p-6 border border-slate-800">
                            <h4 class="text-sm font-bold text-slate-300 uppercase tracking-wider font-mono mb-3">Project Execution Competencies</h4>
                            <div class="flex flex-wrap gap-2 text-xs">
                                <span class="px-3 py-1.5 rounded-lg bg-slate-900 border border-slate-800 text-slate-300">Site Supervision</span>
                                <span class="px-3 py-1.5 rounded-lg bg-slate-900 border border-slate-800 text-slate-300">Health & Safety Compliance</span>
                                <span class="px-3 py-1.5 rounded-lg bg-slate-900 border border-slate-800 text-slate-300">Quality Control (QC)</span>
                                <span class="px-3 py-1.5 rounded-lg bg-slate-900 border border-slate-800 text-slate-300">Agile Project Management</span>
                                <span class="px-3 py-1.5 rounded-lg bg-slate-900 border border-slate-800 text-slate-300">Interdisciplinary Teamwork</span>
                            </div>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- CONTACT & FOOTER SECTION -->
    <section id="contact" class="py-20 bg-slate-950 border-t border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12">
                
                <!-- Contact Direct Info -->
                <div class="lg:col-span-5 space-y-6">
                    <div>
                        <h2 class="text-xs font-mono uppercase tracking-widest text-electric-400 mb-2">// Get In Touch</h2>
                        <h3 class="text-3xl font-extrabold text-white">Let's Connect & Collaborate</h3>
                        <p class="text-slate-400 text-sm mt-3 leading-relaxed">
                            Open for engineering positions in MEP Design, BIM Coordination, and Solar PV Systems across the Gulf region and international consulting firms.
                        </p>
                    </div>

                    <div class="space-y-4 pt-4">
                        <a href="mailto:ahmedalkhameri98@gmail.com" class="p-4 rounded-xl bg-slate-900 border border-slate-800 hover:border-electric-500 transition-all flex items-center space-x-4">
                            <div class="w-10 h-10 rounded-lg bg-electric-500/10 text-electric-400 flex items-center justify-center">
                                <i class="fa-solid fa-envelope"></i>
                            </div>
                            <div>
                                <span class="text-xs text-slate-500 block uppercase font-mono">Direct Email</span>
                                <span class="text-white font-medium text-sm">ahmedalkhameri98@gmail.com</span>
                            </div>
                        </a>

                        <a href="tel:+201149254924" class="p-4 rounded-xl bg-slate-900 border border-slate-800 hover:border-electric-500 transition-all flex items-center space-x-4">
                            <div class="w-10 h-10 rounded-lg bg-electric-500/10 text-electric-400 flex items-center justify-center">
                                <i class="fa-solid fa-phone"></i>
                            </div>
                            <div>
                                <span class="text-xs text-slate-500 block uppercase font-mono">Phone & WhatsApp</span>
                                <span class="text-white font-medium text-sm">+20 114 925 4924</span>
                            </div>
                        </a>

                        <a href="https://linkedin.com/in/ahmedalkhameri" target="_blank" rel="noopener noreferrer" class="p-4 rounded-xl bg-slate-900 border border-slate-800 hover:border-electric-500 transition-all flex items-center space-x-4">
                            <div class="w-10 h-10 rounded-lg bg-electric-500/10 text-electric-400 flex items-center justify-center">
                                <i class="fa-brands fa-linkedin"></i>
                            </div>
                            <div>
                                <span class="text-xs text-slate-500 block uppercase font-mono">LinkedIn Profile</span>
                                <span class="text-white font-medium text-sm">linkedin.com/in/ahmedalkhameri</span>
                            </div>
                        </a>
                    </div>
                </div>

                <!-- Interactive Contact Form -->
                <div class="lg:col-span-7">
                    <div class="bg-slate-900 p-8 rounded-2xl border border-slate-800">
                        <h4 class="text-lg font-bold text-white mb-6">Send an Inquiry or Message</h4>
                        
                        <form id="contact-form" onsubmit="handleFormSubmit(event)" class="space-y-4">
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                                <div>
                                    <label class="block text-xs font-mono uppercase text-slate-400 mb-1">Your Name</label>
                                    <input type="text" required placeholder="e.g. Eng. Sarah Mansour" class="w-full px-4 py-3 rounded-xl bg-slate-950 border border-slate-800 text-white text-sm focus:outline-none focus:border-electric-500 transition-colors">
                                </div>
                                <div>
                                    <label class="block text-xs font-mono uppercase text-slate-400 mb-1">Your Email</label>
                                    <input type="email" required placeholder="name@company.com" class="w-full px-4 py-3 rounded-xl bg-slate-950 border border-slate-800 text-white text-sm focus:outline-none focus:border-electric-500 transition-colors">
                                </div>
                            </div>

                            <div>
                                <label class="block text-xs font-mono uppercase text-slate-400 mb-1">Subject</label>
                                <input type="text" required placeholder="MEP / BIM Project Collaboration" class="w-full px-4 py-3 rounded-xl bg-slate-950 border border-slate-800 text-white text-sm focus:outline-none focus:border-electric-500 transition-colors">
                            </div>

                            <div>
                                <label class="block text-xs font-mono uppercase text-slate-400 mb-1">Message</label>
                                <textarea rows="4" required placeholder="Write your project details or job inquiry here..." class="w-full px-4 py-3 rounded-xl bg-slate-950 border border-slate-800 text-white text-sm focus:outline-none focus:border-electric-500 transition-colors"></textarea>
                            </div>

                            <button type="submit" class="w-full py-3.5 rounded-xl bg-electric-500 hover:bg-electric-600 text-slate-950 font-bold transition-all shadow-md flex items-center justify-center gap-2">
                                <i class="fa-solid fa-paper-plane"></i> Send Message
                            </button>
                        </form>

                        <div id="form-feedback" class="hidden mt-4 p-4 rounded-xl bg-emerald-500/10 border border-emerald-500/30 text-emerald-400 text-xs text-center">
                            Thank you! Your message has been prepared for transmission.
                        </div>
                    </div>
                </div>

            </div>

            <!-- Footer Bottom -->
            <div class="mt-16 pt-8 border-t border-slate-800/80 flex flex-col sm:flex-row items-center justify-between gap-4 text-xs text-slate-500 font-mono">
                <p>© 2026 Eng. Ahmed Abdo Al-Khameri. All rights reserved.</p>
                <p>Designed for GitHub Pages | Cairo, Egypt</p>
            </div>
        </div>
    </section>

    <!-- PROJECT DETAILS MODAL -->
    <div id="project-modal" class="fixed inset-0 z-50 hidden bg-slate-950/80 backdrop-blur-md flex items-center justify-center p-4 overflow-y-auto">
        <div class="bg-slate-900 border border-slate-800 rounded-2xl max-w-2xl w-full p-6 sm:p-8 relative shadow-2xl max-h-[90vh] overflow-y-auto">
            <button onclick="closeModal()" class="absolute top-4 right-4 w-8 h-8 rounded-lg bg-slate-800 hover:bg-slate-700 text-slate-400 hover:text-white flex items-center justify-center transition-colors">
                <i class="fa-solid fa-xmark"></i>
            </button>
            <div id="modal-content">
                <!-- Content dynamically populated by JS -->
            </div>
        </div>
    </div>

    <!-- JAVASCRIPT FOR INTERACTION & MODALS -->
    <script>
        // Project Database for Modal Dialogs
        const projectData = {
            project1: {
                title: "1,500+ kWp Industrial Solar PV System Design",
                category: "Solar Energy & Infrastructure",
                location: "Oil & Gas Facility Project",
                description: "Complete design, simulation, and electrical distribution integration for a utility-scale solar PV system servicing high-demand oil & gas machinery.",
                details: [
                    "Performed comprehensive solar irradiance modeling and shading analysis in PVsyst.",
                    "Sized high-efficiency string inverters and optimized PV string configuration for high ambient temperatures.",
                    "Minimized cable voltage drops and designed low-loss interconnection layouts to existing facility switchboards.",
                    "Prepared full SLDs, bill of quantities (BOQ), and equipment protection schemes."
                ],
                tools: ["PVsyst", "AutoCAD", "DIALux evo", "IEC Standards"]
            },
            project2: {
                title: "Healthcare Facility Electrical & BIM Design",
                category: "Healthcare Engineering",
                location: "Cairo, Egypt",
                description: "Full electrical engineering design for a modern hospital, requiring strict adherence to medical power safety standards, emergency back-up systems, and low-current integration.",
                details: [
                    "Designed essential and non-essential electrical circuits with automatic transfer switch (ATS) feeds.",
                    "Developed clash-free 3D Revit MEP models for electrical equipment, cable trays, and lighting.",
                    "Calculated short-circuit currents and protection selectivity using ETAP & Ecodial.",
                    "Generated production-ready technical office shop drawings and panel Schedules."
                ],
                tools: ["Revit MEP", "AutoCAD", "ETAP", "Ecodial", "DIALux evo"]
            },
            project3: {
                title: "Multi-Discipline MEP Coordination",
                category: "Commercial Mega-Development",
                location: "UAE",
                description: "Comprehensive pre-construction coordination and clash detection between electrical, HVAC, plumbing, and structural disciplines for a massive commercial development.",
                details: [
                    "Utilized Autodesk Forma and Revit for early site layout planning and spatial clash detection.",
                    "Collaborated with cross-functional architecture and structural engineering teams to resolve hundreds of spatial interferences prior to site work.",
                    "Optimized cable tray pathways and ducting routes to preserve ceiling heights and structural integrity.",
                    "Maintained synchronized worksets and shared BIM models according to international standards."
                ],
                tools: ["Revit", "Autodesk Forma", "AutoCAD", "Clash Detection Matrix"]
            },
            project4: {
                title: "High-Density Residential Network",
                category: "Residential Infrastructure",
                location: "Yemen",
                description: "Low-voltage power distribution network design and indoor/outdoor illumination layout for a multi-building residential complex.",
                details: [
                    "Created load estimation profiles, feeder sizing calculations, and voltage drop verification.",
                    "Engineered outdoor street lighting and landscaping illuminance using DIALux evo.",
                    "Produced single-line diagrams, main distribution panel schedules, and cable tray routing drawings.",
                    "Integrated fire alarm and security data conduit pathways into structural architectural openings."
                ],
                tools: ["AutoCAD", "DIALux evo", "Panel Sizing Schedules"]
            },
            project5: {
                title: "Educational Campus Electrical Design with Integrated Solar PV",
                category: "Graduation Thesis (Grade: Excellent)",
                location: "Al-Azhar University, Cairo",
                description: "A comprehensive electrical distribution design featuring a grid-tied rooftop solar PV array to supply peak campus energy demands.",
                details: [
                    "Analyzed overall campus load demand and calculated transformer and backup generator ratings.",
                    "Designed rooftop PV solar array layout and simulated system yield and power injection points using PVsyst.",
                    "Developed detailed low-current networks including Fire Alarm, Data/Telecommunications, and CCTV.",
                    "Completed full tender package documentation, single-line diagrams, and short-circuit calculation sheets."
                ],
                tools: ["PVsyst", "ETAP", "AutoCAD", "DIALux evo", "Revit"]
            }
        };

        // Mobile Menu Toggle Logic
        const mobileMenuBtn = document.getElementById('mobile-menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');
        
        mobileMenuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        document.querySelectorAll('.mobile-link').forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
            });
        });

        // Skill Filtering Interactive Logic
        const filterButtons = document.querySelectorAll('#skill-filter-buttons button');
        const skillItems = document.querySelectorAll('#skills-container .skill-item');

        filterButtons.forEach(btn => {
            btn.addEventListener('click', () => {
                // Toggle active style
                filterButtons.forEach(b => {
                    b.classList.remove('bg-electric-500', 'text-slate-950', 'active', 'font-semibold');
                    b.classList.add('bg-slate-800', 'text-slate-300', 'font-medium');
                });
                btn.classList.remove('bg-slate-800', 'text-slate-300', 'font-medium');
                btn.classList.add('bg-electric-500', 'text-slate-950', 'active', 'font-semibold');

                const filter = btn.getAttribute('data-filter');

                skillItems.forEach(item => {
                    if (filter === 'all' || item.classList.contains(filter)) {
                        item.style.display = 'flex';
                    } else {
                        item.style.display = 'none';
                    }
                });
            });
        });

        // Modal Box Control Logic
        function openModal(projectId) {
            const modal = document.getElementById('project-modal');
            const content = document.getElementById('modal-content');
            const data = projectData[projectId];

            if (!data) return;

            content.innerHTML = `
                <div class="mb-4">
                    <span class="px-3 py-1 rounded-full bg-electric-500/10 border border-electric-500/30 text-electric-400 text-xs font-mono">${data.category}</span>
                    <span class="text-xs text-slate-400 font-mono ml-2"><i class="fa-solid fa-location-dot"></i> ${data.location}</span>
                </div>
                <h3 class="text-2xl font-bold text-white mb-3">${data.title}</h3>
                <p class="text-slate-300 text-sm leading-relaxed mb-6">${data.description}</p>
                
                <h4 class="text-xs font-mono uppercase text-electric-400 mb-3 tracking-wider">// Technical Scope & Deliverables</h4>
                <ul class="space-y-2 text-xs text-slate-300 list-disc list-inside marker:text-electric-400 mb-6">
                    ${data.details.map(detail => `<li>${detail}</li>`).join('')}
                </ul>

                <h4 class="text-xs font-mono uppercase text-electric-400 mb-3 tracking-wider">// Tools & Standards Used</h4>
                <div class="flex flex-wrap gap-2 text-xs font-mono">
                    ${data.tools.map(tool => `<span class="px-2.5 py-1 rounded bg-slate-800 text-slate-300 border border-slate-700">${tool}</span>`).join('')}
                </div>
            `;

            modal.classList.remove('hidden');
        }

        function closeModal() {
            document.getElementById('project-modal').classList.add('hidden');
        }

        // Close Modal on backdrop click
        document.getElementById('project-modal').addEventListener('click', (e) => {
            if (e.target.id === 'project-modal') {
                closeModal();
            }
        });

        // Form Submission Simulation
        function handleFormSubmit(e) {
            e.preventDefault();
            const feedback = document.getElementById('form-feedback');
            feedback.classList.remove('hidden');
            e.target.reset();
            setTimeout(() => {
                feedback.classList.add('hidden');
            }, 4000);
        }

        // CV Download Action Simulation
        function downloadCV() {
            const link = document.createElement('a');
            // Mock or actual CV download link
            link.href = 'mailto:ahmedalkhameri98@gmail.com?subject=Request%20for%20Official%20CV%20-%20Ahmed%20Al-Khameri';
            window.location.href = link.href;
        }
    </script>
</body>
</html>
