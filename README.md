# digital-zen  <!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Digital Zen - Find Your Focus. Master Your Digital World.</title>
    <script src="https://cdn.tailwindcss.com?plugins=typography"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --background: #F8F9FA;
            --white: #FFFFFF;
            --light-gray: #EAECEF;
            --text-primary: #1F2937;
            --text-secondary: #4B5563;
            --accent: #3B82F6;
            --accent-dark: #2563EB;
        }

        body {
            font-family: 'Inter', sans-serif;
            background-color: var(--background);
            color: var(--text-primary);
        }

        .cta-button {
            display: inline-block;
            background-color: var(--accent);
            color: var(--white);
            padding: 12px 24px;
            border-radius: 8px;
            font-weight: 600;
            text-decoration: none;
            transition: background-color 0.3s ease, transform 0.2s ease;
            box-shadow: 0 4px 6px rgba(50, 50, 93, 0.11), 0 1px 3px rgba(0, 0, 0, 0.08);
        }

        .cta-button:hover {
            background-color: var(--accent-dark);
            transform: translateY(-2px);
        }

        .cta-button:active {
            transform: translateY(0);
        }

        .cta-button-large {
            padding: 16px 32px;
            font-size: 1.125rem; /* 18px */
        }

        .fade-in-section {
            opacity: 0;
            transform: translateY(20px);
            transition: opacity 0.6s ease-out, transform 0.6s ease-out;
        }

        .fade-in-section.is-visible {
            opacity: 1;
            transform: translateY(0);
        }
    </style>
</head>
<body class="bg-background text-text-primary antialiased">

    <div id="root">
        <header class="bg-background/80 backdrop-blur-sm sticky top-0 z-50">
            <div class="container mx-auto px-6 py-4 flex justify-between items-center">
                <h1 class="text-2xl font-bold text-text-primary">Digital Zen</h1>
                <a href="#pricing" class="cta-button text-sm">Get The Kit</a>
            </div>
        </header>

        <main>
            <section class="relative overflow-hidden">
                <div class="container mx-auto px-6 pt-16 pb-24 lg:pt-24 lg:pb-32 grid lg:grid-cols-2 gap-12 items-center">
                    <div class="fade-in-section text-center lg:text-left">
                        <h1 class="text-4xl md:text-5xl lg:text-6xl font-bold tracking-tight text-text-primary leading-tight">
                            Find Your Focus. Master Your Digital World.
                        </h1>
                        <p class="mt-6 text-lg md:text-xl text-text-secondary max-w-xl mx-auto lg:mx-0">
                            The Ultimate Productivity &amp; Declutter Kit to Transform Digital Chaos into Digital Zen.
                        </p>
                        <div class="mt-10">
                            <a href="#pricing" class="cta-button cta-button-large">Start My Zen Journey</a>
                        </div>
                    </div>
                    <div class="fade-in-section relative h-64 lg:h-auto">
                        <img src="https://r2.flowith.net/files/o/1753097111052-digital_zen_landing_page_hero_image_index_0@1536x1024.png" alt="A serene and organized digital workspace representing the Digital Zen kit." class="rounded-2xl shadow-2xl object-cover w-full h-full">
                    </div>
                </div>
            </section>

            <section id="problem" class="py-20 lg:py-28 bg-white">
                <div class="container mx-auto px-6">
                    <div class="text-center max-w-3xl mx-auto">
                        <h2 class="fade-in-section text-3xl md:text-4xl font-bold text-text-primary">Is Your Digital Life a Source of Stress?</h2>
                        <p class="fade-in-section mt-4 text-lg text-text-secondary">If you feel like your brain has too many tabs open, you're not alone. You're like 'Overwhelmed Alex'—ambitious and capable, but undermined by digital chaos.</p>
                    </div>
                    <div class="mt-16 grid md:grid-cols-3 gap-8 text-center">
                        <div class="fade-in-section p-8 bg-background rounded-2xl">
                            <div class="inline-block p-4 bg-accent/10 rounded-full">
                                <i data-lucide="bell-off" class="w-8 h-8 text-accent"></i>
                            </div>
                            <h3 class="mt-4 text-xl font-semibold">Constant Distractions</h3>
                            <p class="mt-2 text-text-secondary">Endless notifications hijack your attention, leaving you feeling reactive and fragmented instead of proactive and focused.</p>
                        </div>
                        <div class="fade-in-section p-8 bg-background rounded-2xl">
                             <div class="inline-block p-4 bg-accent/10 rounded-full">
                                <i data-lucide="files" class="w-8 h-8 text-accent"></i>
                            </div>
                            <h3 class="mt-4 text-xl font-semibold">Wasted Time &amp; Energy</h3>
                            <p class="mt-2 text-text-secondary">Wasting 30-60 minutes every day searching for scattered files across your desktop, cloud drives, and random notes apps.</p>
                        </div>
                        <div class="fade-in-section p-8 bg-background rounded-2xl">
                             <div class="inline-block p-4 bg-accent/10 rounded-full">
                                <i data-lucide="shield-alert" class="w-8 h-8 text-accent"></i>
                            </div>
                            <h3 class="mt-4 text-xl font-semibold">Professional Insecurity</h3>
                            <p class="mt-2 text-text-secondary">The dread of a surprise screen share revealing a messy desktop, undermining your professional image and confidence.</p>
                        </div>
                    </div>
                </div>
            </section>

            <section id="solution" class="py-20 lg:py-28">
                <div class="container mx-auto px-6 grid lg:grid-cols-2 gap-16 items-center">
                    <div class="fade-in-section">
                        <span class="font-semibold text-accent">THE SOLUTION</span>
                        <h2 class="mt-2 text-3xl md:text-4xl font-bold text-text-primary">Reclaim Your Focus, Effortlessly</h2>
                        <p class="mt-4 text-lg text-text-secondary">The Digital Zen Kit isn't just another tool—it's a complete system designed to give you back control. It provides the structure to organize your entire digital life and the methods to build sustainable wellness habits. Move from overwhelmed to always in control.</p>
                        <a href="#whats-inside" class="mt-8 inline-block text-accent font-semibold hover:underline">See what's inside &rarr;</a>
                    </div>
                    <div class="fade-in-section bg-white p-8 rounded-2xl shadow-lg">
                        <div class="flex items-start">
                            <span class="text-3xl font-bold text-gray-300 mr-4">Before</span>
                            <p class="italic text-text-secondary">"I feel like my brain has too many tabs open... I know I could be so much more effective if I could just get a handle on the digital chaos, but I don't even know where to start."<br><span class="not-italic font-semibold text-gray-500">- 'Overwhelmed Alex' Persona</span></p>
                        </div>
                        <hr class="my-6 border-gray-200">
                        <div class="flex items-start">
                            <span class="text-3xl font-bold text-accent mr-6">After</span>
                            <p class="italic text-text-primary">"Everything has a home. I start my day with clarity and end it with a sense of accomplishment."</p>
                        </div>
                    </div>
                </div>
            </section>
            
            <section id="whats-inside" class="py-20 lg:py-28 bg-white">
                <div class="container mx-auto px-6">
                    <div class="text-center max-w-3xl mx-auto">
                        <h2 class="fade-in-section text-3xl md:text-4xl font-bold text-text-primary">Everything You Need To Succeed</h2>
                        <p class="fade-in-section mt-4 text-lg text-text-secondary">We've combined powerful, interconnected templates with a practical mini-course to ensure your transformation sticks.</p>
                    </div>

                    <div class="mt-16 grid lg:grid-cols-2 gap-8 lg:gap-12">
                        <div class="fade-in-section p-8 bg-background rounded-2xl border border-gray-200">
                            <h3 class="text-2xl font-bold text-text-primary">Powerful Notion Templates</h3>
                            <p class="mt-2 text-text-secondary">A suite of templates that work together to create a unified, calm command center.</p>
                            <ul class="mt-6 space-y-4">
                                <li class="flex items-start"><i data-lucide="check-circle-2" class="w-5 h-5 text-accent mr-3 mt-1 flex-shrink-0"></i><span><strong class="font-semibold">Master Life Dashboard:</strong> Your single source of truth for a clear, prioritized day.</span></li>
                                <li class="flex items-start"><i data-lucide="check-circle-2" class="w-5 h-5 text-accent mr-3 mt-1 flex-shrink-0"></i><span><strong class="font-semibold">Projects &amp; Tasks Hub:</strong> Centralize all actionable items and track progress automatically.</span></li>
                                <li class="flex items-start"><i data-lucide="check-circle-2" class="w-5 h-5 text-accent mr-3 mt-1 flex-shrink-0"></i><span><strong class="font-semibold">Knowledge &amp; Resource Vault:</strong> Your "second brain" to save anything and find it in seconds.</span></li>
                                <li class="flex items-start"><i data-lucide="check-circle-2" class="w-5 h-5 text-accent mr-3 mt-1 flex-shrink-0"></i><span><strong class="font-semibold">Digital Declutter Checklist:</strong> A guided project to clear existing digital chaos for good.</span></li>
                            </ul>
                        </div>
                        <div class="fade-in-section p-8 bg-background rounded-2xl border border-gray-200">
                            <h3 class="text-2xl font-bold text-text-primary">Digital Wellness Mini-Course</h3>
                            <p class="mt-2 text-text-secondary">Simple, actionable video lessons to change your relationship with technology.</p>
                            <ul class="mt-6 space-y-4">
                                <li class="flex items-start"><i data-lucide="check-circle-2" class="w-5 h-5 text-accent mr-3 mt-1 flex-shrink-0"></i><span><strong class="font-semibold">Module 1: The Zen Mindset:</strong> Shift from reactive and overwhelmed to intentional and in control.</span></li>
                                <li class="flex items-start"><i data-lucide="check-circle-2" class="w-5 h-5 text-accent mr-3 mt-1 flex-shrink-0"></i><span><strong class="font-semibold">Module 2: Building Your Command Center:</strong> Step-by-step setup and customization of your Notion suite.</span></li>
                                <li class="flex items-start"><i data-lucide="check-circle-2" class="w-5 h-5 text-accent mr-3 mt-1 flex-shrink-0"></i><span><strong class="font-semibold">Module 3: The Digital Zen Workflow:</strong> Learn the daily and weekly habits that make organization effortless.</span></li>
                                <li class="flex items-start"><i data-lucide="check-circle-2" class="w-5 h-5 text-accent mr-3 mt-1 flex-shrink-0"></i><span><strong class="font-semibold">Module 4: Sustainable System Mastery:</strong> Ensure long-term success with simple automations and habits.</span></li>
                            </ul>
                        </div>
                    </div>
                </div>
            </section>
            
            <section id="benefits" class="py-20 lg:py-28">
                <div class="container mx-auto px-6">
                     <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-10">
                        <div class="fade-in-section flex items-start space-x-4">
                            <i data-lucide="file-search" class="w-8 h-8 text-accent flex-shrink-0 mt-1"></i>
                            <div>
                                <h3 class="text-xl font-semibold">Never lose a file again</h3>
                                <p class="mt-1 text-text-secondary">A single, searchable "second brain" means every resource is retrievable in seconds.</p>
                            </div>
                        </div>
                        <div class="fade-in-section flex items-start space-x-4">
                            <i data-lucide="clock" class="w-8 h-8 text-accent flex-shrink-0 mt-1"></i>
                            <div>
                                <h3 class="text-xl font-semibold">Cut down on wasted time</h3>
                                <p class="mt-1 text-text-secondary">Save up to 5 hours a week by eliminating digital friction and decision fatigue.</p>
                            </div>
                        </div>
                        <div class="fade-in-section flex items-start space-x-4">
                            <i data-lucide="trending-up" class="w-8 h-8 text-accent flex-shrink-0 mt-1"></i>
                            <div>
                                <h3 class="text-xl font-semibold">Build a workflow that sticks</h3>
                                <p class="mt-1 text-text-secondary">Our mini-course helps you build habits for long-term focus and clarity.</p>
                            </div>
                        </div>
                     </div>
                </div>
            </section>

            <section id="testimonials" class="py-20 lg:py-28 bg-white">
                <div class="container mx-auto px-6">
                    <div class="text-center max-w-3xl mx-auto">
                        <h2 class="fade-in-section text-3xl md:text-4xl font-bold text-text-primary">Stop Drowning in Digital Chaos</h2>
                        <p class="fade-in-section mt-4 text-lg text-text-secondary">See how the Digital Zen kit has helped others just like you find their focus and calm.</p>
                    </div>
                    <div class="mt-16 grid lg:grid-cols-3 gap-8">
                        <div class="fade-in-section p-8 bg-background rounded-2xl">
                            <p class="text-text-primary">"I finally feel in control. I went from constantly anxious about missed tasks to feeling calm and prepared every day. This is a game-changer for anyone feeling overwhelmed."</p>
                            <p class="mt-6 font-semibold">- Alex R., Freelance Designer</p>
                        </div>
                        <div class="fade-in-section p-8 bg-background rounded-2xl">
                            <p class="text-text-primary">"The 'second brain' concept alone was worth it. I've stopped hoarding tabs and bookmarks. Now, every resource is organized and connected to my projects. Pure genius."</p>
                            <p class="mt-6 font-semibold">- Jamie L., Entrepreneur</p>
                        </div>
                        <div class="fade-in-section p-8 bg-background rounded-2xl">
                            <p class="text-text-primary">"As a student juggling multiple courses and a part-time job, this system saved my sanity. My grades have improved, and I'm less stressed than ever."</p>
                            <p class="mt-6 font-semibold">- Sam K., Graduate Student</p>
                        </div>
                    </div>
                </div>
            </section>

            <section id="pricing" class="py-20 lg:py-28">
                <div class="container mx-auto px-6">
                    <div class="fade-in-section max-w-2xl mx-auto bg-white rounded-2xl shadow-2xl p-8 lg:p-12 text-center">
                        <h2 class="text-2xl font-bold text-text-primary">Get Instant, Lifetime Access</h2>
                        <p class="mt-4 text-lg text-text-secondary">One-time payment. Endless clarity. Includes the complete Notion Template Suite, the Digital Wellness Mini-Course, and all future updates.</p>

                        <div class="mt-8 border-t border-b border-gray-200">
                             <div class="p-6 bg-slate-50/50">
                                <h3 class="font-bold text-accent text-lg">🔥 PREMIUM UPSELL</h3>
                                <p class="mt-2 text-text-secondary text-sm">Turn this kit into a business. Add the ultimate accelerator.</p>
                                <div class="mt-4 text-left p-4 rounded-lg bg-white border border-gray-200 hover:border-accent transition-colors">
                                    <label for="upsell-checkbox" class="flex items-center cursor-pointer">
                                        <input type="checkbox" id="upsell-checkbox" class="h-5 w-5 rounded border-gray-300 text-accent focus:ring-accent focus:ring-2 focus:ring-offset-2">
                                        <div class="ml-4 flex-grow">
                                            <span class="font-semibold text-text-primary">Add: Digital Zen Side Hustle Blueprint</span>
                                            <span class="block text-text-secondary text-sm">The complete business-in-a-box for launching a profitable side hustle with this kit. Includes marketing plans, viral video scripts, content assets &amp; more.</span>
                                        </div>
                                        <span class="ml-4 font-bold text-lg text-text-primary">+$49</span>
                                    </label>
                                </div>
                            </div>
                        </div>

                        <div class="my-8">
                            <div id="price-container">
                                <span class="text-6xl font-bold text-text-primary">$79</span>
                            </div>
                            <span class="text-text-secondary">one-time purchase</span>
                        </div>
                        <a href="#" class="cta-button cta-button-large w-full">Get Instant Access Now</a>
                        <p class="mt-4 text-sm text-gray-500">Secure payment via Stripe. 30-day money-back guarantee.</p>
                    </div>
                </div>
            </section>
        </main>

        <footer class="bg-white">
            <div class="container mx-auto px-6 py-8 text-center text-gray-500">
                <p>&copy; 2025 Digital Zen. All Rights Reserved.</p>
                <p class="text-sm mt-2">Find your focus. Master your world.</p>
            </div>
        </footer>
    </div>
    
    <script src="https://unpkg.com/lucide@latest"></script>
    <script>
    document.addEventListener('DOMContentLoaded', () => {

        try {
            if (lucide) {
                lucide.createIcons();
            }
        } catch (e) {
            console.error("Lucide icons failed to initialize.", e);
        }


        const fadeInSections = document.querySelectorAll('.fade-in-section');
        const sectionObserver = new IntersectionObserver((entries, observer) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('is-visible');
                    observer.unobserve(entry.target);
                }
            });
        }, {
            rootMargin: '0px',
            threshold: 0.1
        });

        fadeInSections.forEach(section => {
            sectionObserver.observe(section);
        });


        const upsellCheckbox = document.getElementById('upsell-checkbox');
        const priceContainer = document.getElementById('price-container');
        const basePrice = 79;
        const upsellPrice = 49;

        if (upsellCheckbox && priceContainer) {
            upsellCheckbox.addEventListener('change', () => {
                const newPrice = upsellCheckbox.checked ? basePrice + upsellPrice : basePrice;
                priceContainer.innerHTML = `<span class="text-6xl font-bold text-text-primary">$${newPrice}</span>`;
            });
        }
    });
    </script>
</body>
</html>
