<!DOCTYPE html>

<html class="dark" lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>DevPortfolio | Modern Developer</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;900&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
        tailwind.config = {
            darkMode: "class",
            theme: {
                extend: {
                    colors: {
                        "primary": "#f48c25",
                        "background-light": "#f8f7f5",
                        "background-dark": "#0a1120", // Adjusted to dark navy to match user request while keeping theme structure
                    },
                    fontFamily: {
                        "display": ["Inter", "sans-serif"]
                    },
                    borderRadius: {"DEFAULT": "0.25rem", "lg": "0.5rem", "xl": "0.75rem", "full": "9999px"},
                },
            },
        }
    </script>
<style>
        body {
            font-family: 'Inter', sans-serif;
        }
    </style>
</head>
<body class="bg-background-light dark:bg-background-dark text-slate-900 dark:text-slate-100 antialiased selection:bg-primary selection:text-background-dark">
<!-- Main Wrapper -->
<div class="relative flex min-h-screen flex-col overflow-x-hidden">
<div class="layout-container flex h-full grow flex-col">
<!-- Navigation -->
<header class="sticky top-0 z-50 w-full border-b border-slate-200/10 bg-background-light/80 dark:bg-background-dark/80 backdrop-blur-md px-4 md:px-20 py-4">
<div class="mx-auto flex max-w-[1200px] items-center justify-between whitespace-nowrap">
<div class="flex items-center gap-3">
<div class="flex items-center justify-center rounded-lg bg-primary p-2 text-background-dark">
<span class="material-symbols-outlined font-bold">terminal</span>
</div>
<h2 class="text-xl font-black tracking-tight text-slate-900 dark:text-white uppercase">DevPortfolio</h2>
</div>
<div class="hidden md:flex flex-1 justify-end gap-10 items-center">
<nav class="flex items-center gap-8">
<a class="text-sm font-semibold hover:text-primary transition-colors" href="#home">Home</a>
<a class="text-sm font-semibold hover:text-primary transition-colors" href="#about">About</a>
<a class="text-sm font-semibold hover:text-primary transition-colors" href="#contact">Contact</a>
</nav>
<button class="flex min-w-[100px] cursor-pointer items-center justify-center rounded-lg h-10 px-5 bg-primary text-background-dark text-sm font-bold transition-transform active:scale-95">
                            Hire Me
                        </button>
</div>
<!-- Mobile Menu Icon (Visual Only) -->
<div class="md:hidden">
<span class="material-symbols-outlined text-slate-100">menu</span>
</div>
</div>
</header>
<main class="mx-auto flex max-w-[1200px] flex-1 flex-col px-4 md:px-10">
<!-- Hero Section -->
<section class="@container py-12 md:py-24" id="home">
<div class="flex flex-col gap-10 md:flex-row md:items-center">
<div class="flex flex-1 flex-col gap-8">
<div class="flex flex-col gap-4">
<span class="text-primary font-bold tracking-widest text-xs uppercase">Welcome to my workspace</span>
<h1 class="text-slate-900 dark:text-white text-5xl font-black leading-[1.1] tracking-tight md:text-7xl">I am <span class="text-primary">Marielle Rodica</span>. This is my first <span class="text-primary">Github</span> Account Repo</h1>
<p class="text-slate-600 dark:text-slate-400 text-lg max-w-xl leading-relaxed">
                                    Full-stack developer specializing in modern, high-contrast web experiences with dark navy themes and vibrant accents. Crafting clean code and intuitive interfaces.
                                </p>
</div>
<div class="flex flex-wrap gap-4">
<button class="flex h-14 items-center justify-center rounded-xl px-8 bg-primary text-background-dark text-base font-bold transition-all hover:shadow-[0_0_20px_rgba(244,140,37,0.4)]">
                                    View My Work
                                </button>
<button class="flex h-14 items-center justify-center rounded-xl px-8 border-2 border-slate-700 hover:border-primary text-slate-100 text-base font-bold transition-all">
                                    Download CV
                                </button>
</div>
</div>
<div class="relative w-full max-w-[500px] aspect-square flex-shrink-0">
<div class="absolute inset-0 bg-primary/20 blur-3xl rounded-full"></div>
<div class="relative w-full h-full bg-slate-800 rounded-2xl overflow-hidden border border-slate-700 shadow-2xl" data-alt="Abstract coding background with glowing lines" style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuCTbJ95ofIl6csJcHbzl1cq0KsAIH-fVeuwvt4HOol3ITxxbolIU_Tz7e-AZwZzvslbx8q6GV3hBRGj4d04poinoJs9OCXXlMdATySiKPjjX6a81urv7Gr0tj8aKDoR4X5m9XXijLVkVbr81j0E61m2AVTpW3JTNwrqIh446fBnTozfMbK0VM5g7Qwzucul3w_zB-yBHlMDsORcPCdiByITzlmCkwQ72calAjQrfgbUIqemVp5hZxBWMobOJ5d-R9nF4UzMOjM3CA"); background-position: center; background-size: cover;'>
</div>
</div>
</div>
</section>
<!-- Projects Section -->
<!-- About Me Section -->
<section class="py-20" id="about">
<div class="flex flex-col lg:flex-row gap-16 items-center">
<div class="lg:w-1/2 flex flex-col gap-6">
<div class="flex flex-col gap-2">
<h2 class="text-primary font-bold tracking-widest text-xs uppercase">Background</h2>
<h3 class="text-slate-900 dark:text-white text-4xl font-black">About Me</h3>
</div>
<p class="text-slate-400 text-lg leading-relaxed">
                                I'm a software engineer with a passion for building beautiful, high-performance web applications. My journey began with a curiosity for how things work under the hood, leading me to master the modern stack.
                            </p>
<p class="text-slate-400 text-lg leading-relaxed">
                                I believe in writing code that is not just functional, but clean, scalable, and easy to maintain. When I'm not coding, you'll find me exploring new tech trends or contributing to open-source projects.
                            </p>
<div class="grid grid-cols-2 gap-6 mt-4">
<div class="flex flex-col gap-1">
<span class="text-primary text-3xl font-black">5+</span>
<span class="text-slate-500 text-sm font-bold uppercase tracking-tighter">Years Experience</span>
</div>
<div class="flex flex-col gap-1">
<span class="text-primary text-3xl font-black">50+</span>
<span class="text-slate-500 text-sm font-bold uppercase tracking-tighter">Projects Completed</span>
</div>
</div>
</div>
<div class="lg:w-1/2 grid grid-cols-2 gap-4">
<div class="p-6 rounded-2xl bg-slate-800/40 border border-slate-700/50 flex flex-col gap-3">
<span class="material-symbols-outlined text-primary text-3xl">javascript</span>
<h5 class="font-bold">Frontend</h5>
<p class="text-slate-500 text-sm">Expert in React, Next.js, and Tailwind CSS.</p>
</div>
<div class="p-6 rounded-2xl bg-slate-800/40 border border-slate-700/50 flex flex-col gap-3">
<span class="material-symbols-outlined text-primary text-3xl">database</span>
<h5 class="font-bold">Backend</h5>
<p class="text-slate-500 text-sm">Scalable APIs with Node.js and PostgreSQL.</p>
</div>
<div class="p-6 rounded-2xl bg-slate-800/40 border border-slate-700/50 flex flex-col gap-3">
<span class="material-symbols-outlined text-primary text-3xl">cloud</span>
<h5 class="font-bold">DevOps</h5>
<p class="text-slate-500 text-sm">AWS, Docker, and CI/CD pipelines.</p>
</div>
<div class="p-6 rounded-2xl bg-slate-800/40 border border-slate-700/50 flex flex-col gap-3">
<span class="material-symbols-outlined text-primary text-3xl">palette</span>
<h5 class="font-bold">UI Design</h5>
<p class="text-slate-500 text-sm">Crafting clean, accessible experiences.</p>
</div>
</div>
</div>
</section>
</main>
<!-- Footer / Contact Section -->
<footer class="mt-auto bg-slate-900/50 border-t border-slate-800 py-20 px-4" id="contact">
<div class="mx-auto max-w-[1200px]">
<div class="flex flex-col lg:flex-row gap-16">
<div class="lg:w-1/2 flex flex-col gap-8">
<div class="flex flex-col gap-4">
<h2 class="text-primary font-bold tracking-widest text-xs uppercase">Get in touch</h2>
<h3 class="text-slate-900 dark:text-white text-4xl font-black">Let's build something <br/> great together.</h3>
<p class="text-slate-400 max-w-md">Currently available for freelance opportunities and full-time positions. Send me a message and I'll get back to you within 24 hours.</p>
</div>
<div class="flex flex-col gap-4">
<div class="flex items-center gap-4 text-slate-300">
<div class="size-10 rounded-full bg-slate-800 flex items-center justify-center">
<span class="material-symbols-outlined text-primary text-sm">mail</span>
</div>
<span>hello@developer.io</span>
</div>
<div class="flex items-center gap-4 text-slate-300">
<div class="size-10 rounded-full bg-slate-800 flex items-center justify-center">
<span class="material-symbols-outlined text-primary text-sm">location_on</span>
</div>
<span>San Francisco, CA</span>
</div>
</div>
</div>
<div class="lg:w-1/2">
<form class="flex flex-col gap-4 bg-background-dark p-8 rounded-2xl border border-slate-700/50 shadow-xl">
<div class="grid grid-cols-1 md:grid-cols-2 gap-4">
<div class="flex flex-col gap-1.5">
<label class="text-xs font-bold text-slate-500 uppercase">Full Name</label>
<input class="bg-slate-800/50 border-slate-700 rounded-lg text-white focus:border-primary focus:ring-primary h-12" placeholder="John Doe" type="text"/>
</div>
<div class="flex flex-col gap-1.5">
<label class="text-xs font-bold text-slate-500 uppercase">Email Address</label>
<input class="bg-slate-800/50 border-slate-700 rounded-lg text-white focus:border-primary focus:ring-primary h-12" placeholder="john@example.com" type="email"/>
</div>
</div>
<div class="flex flex-col gap-1.5">
<label class="text-xs font-bold text-slate-500 uppercase">Subject</label>
<input class="bg-slate-800/50 border-slate-700 rounded-lg text-white focus:border-primary focus:ring-primary h-12" placeholder="How can I help you?" type="text"/>
</div>
<div class="flex flex-col gap-1.5">
<label class="text-xs font-bold text-slate-500 uppercase">Message</label>
<textarea class="bg-slate-800/50 border-slate-700 rounded-lg text-white focus:border-primary focus:ring-primary" placeholder="Tell me about your project..." rows="4"></textarea>
</div>
<button class="mt-4 flex h-14 items-center justify-center rounded-xl bg-primary text-background-dark text-base font-bold transition-all hover:bg-primary/90" type="submit">
                                    Send Message
                                </button>
</form>
</div>
</div>
<div class="mt-20 pt-8 border-t border-slate-800/50 flex flex-col md:flex-row justify-between items-center gap-6">
<div class="flex items-center gap-3">
<div class="size-6 rounded bg-primary flex items-center justify-center">
<span class="material-symbols-outlined text-[14px] font-bold text-background-dark">terminal</span>
</div>
<span class="text-sm font-bold text-slate-500">© 2024 DevPortfolio. Built with Tailwind.</span>
</div>
<div class="flex gap-6">
<a class="text-slate-500 hover:text-primary transition-colors font-bold text-xs uppercase tracking-widest" href="#">Github</a>
<a class="text-slate-500 hover:text-primary transition-colors font-bold text-xs uppercase tracking-widest" href="#">LinkedIn</a>
<a class="text-slate-500 hover:text-primary transition-colors font-bold text-xs uppercase tracking-widest" href="#">Twitter</a>
</div>
</div>
</div>
</footer>
</div>
</div>
</body></html>
