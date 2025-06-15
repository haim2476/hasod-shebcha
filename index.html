<!DOCTYPE html>
<html lang="he" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>הסוד שבך | הרב מאיר שלמה זצ"ל</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Assistant:wght@300;400;600;700&display=swap" rel="stylesheet">
    
    <!-- Chosen Palette: Warm Harmony (inspired by nature and spirituality - light sand, warm taupe, soft brown, with a gentle gold accent) -->
    <!-- Application Structure Plan: A single-page, vertical scrolling journey in 6 thematic sections: 1. The Search (immersive intro), 2. The Disconnect (interactive problem statement), 3. The Secret (book reveal), 4. Rabbi Biography, 5. Book Excerpts (new section), 6. The Journey (interactive exploration of benefits), 7. The Invitation (clear call to action). This narrative structure is chosen over a simple text dump to guide the user emotionally, build curiosity, and make the book's abstract concepts tangible and explorable, enhancing engagement and understanding. -->
    <!-- Visualization & Content Choices: 
    - The Search: Goal: Evoke emotion. Method: Full-screen section with animated text (JS) and a subtle Canvas background of floating light particles to create a contemplative mood. No library.
    - The Disconnect: Goal: Compare. Method: A grid of "stress" words using HTML/Tailwind that flashes and disappears (JS/CSS animation) to reveal a calm state. No library.
    - The Secret: Goal: Inform. Method: Interactive book cover reveal using HTML/CSS/JS. A Canvas ripple effect on click enhances the feeling of discovery. No library.
    - Rabbi Biography: Goal: Inform/Build Credibility. Method: Dedicated section with image and textual biography. No library.
    - Book Excerpts: Goal: Inform/Engage. Method: Text blocks with styling to highlight quotes, encouraging a direct taste of the book. No library.
    - The Journey: Goal: Organize/Inform. Method: Interactive HTML/Tailwind cards for book's benefits ('Peace', 'Purpose'). JS handles the click-to-reveal mechanism showing more text. No library.
    - The Invitation: Goal: Action. Method: Simple, clear HTML/Tailwind layout.
    - Justification: These choices create an interactive, emotional journey that translates the video script's feeling into a web experience without using complex libraries or static graphics. -->
    <!-- CONFIRMATION: NO SVG graphics used. NO Mermaid JS used. -->

    <style>
        body {
            font-family: 'Assistant', sans-serif;
            scroll-behavior: smooth;
            padding-top: 5rem; /* Adjust body padding to account for the fixed header */
        }
        .hero-section {
            height: 100vh;
            padding-top: 0; /* Remove top padding from hero since body has it */
        }
        .fade-in {
            animation: fadeIn 2s ease-in-out forwards;
        }
        .fade-in-delay {
            animation: fadeIn 2s 1s ease-in-out forwards;
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        .card {
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.05), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
        }
        .card .back {
            display: none;
        }
        .card.flipped .front {
            display: none;
        }
        .card.flipped .back {
            display: block;
        }
        #hero-canvas {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
        }
        .book-image {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
        /* New styles for flash and disappear effect */
        .initial-stress-visibility {
            opacity: 0.7; /* Start a bit more visible than before */
        }
        .flash-disappear-item {
            animation: flashThenDisappear 1.5s ease-out forwards;
        }
        @keyframes flashThenDisappear {
            0% { opacity: 0.7; transform: scale(1); }
            30% { opacity: 1; transform: scale(1.05); } /* Flash */
            100% { opacity: 0; transform: scale(0.9); visibility: hidden; } /* Disappear */
        }
        .rabbi-image {
            width: 200px;
            height: 200px;
            object-fit: cover;
            border-radius: 50%;
            border: 4px solid #C19A6B;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
        }
        .excerpt-box {
            background-color: #ffffff;
            border-left: 5px solid #C19A6B;
            padding: 1.5rem;
            border-radius: 0.5rem;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
            margin-bottom: 2rem;
        }
    </style>
</head>
<body class="bg-[#F5F5DC] text-[#4A238]">
    <!-- B"H (בס"ד) header -->
    <header class="absolute top-0 right-0 p-4 text-[#6F6253] font-semibold text-lg z-30">
        בס"ד
    </header>

    <!-- Sticky Navigation Bar -->
    <nav class="fixed top-0 left-0 right-0 bg-[#F5F5DC] bg-opacity-95 shadow-md p-4 flex justify-center items-center z-20">
        <div class="container mx-auto flex flex-wrap justify-center gap-4 text-sm md:text-base">
            <a href="#hero" class="text-[#6F6253] hover:text-[#C19A6B] font-semibold transition-colors duration-200 px-2 py-1 rounded-md">ראשי</a>
            <a href="#disconnect" class="text-[#6F6253] hover:text-[#C19A6B] font-semibold transition-colors duration-200 px-2 py-1 rounded-md">החיפוש</a>
            <a href="#the-secret" class="text-[#6F6253] hover:text-[#C19A6B] font-semibold transition-colors duration-200 px-2 py-1 rounded-md">הסוד</a>
            <a href="#rabbi-bio" class="text-[#6F6253] hover:text-[#C19A6B] font-semibold transition-colors duration-200 px-2 py-1 rounded-md">הרב המחבר</a>
            <a href="#book-excerpts" class="text-[#6F6253] hover:text-[#C19A6B] font-semibold transition-colors duration-200 px-2 py-1 rounded-md">טעימה מהספר</a>
            <a href="#the-journey" class="text-[#6F6253] hover:text-[#C19A6B] font-semibold transition-colors duration-200 px-2 py-1 rounded-md">המסע</a>
            <a href="#cta" class="bg-[#C19A6B] text-white hover:bg-[#a98458] font-bold transition-colors duration-300 px-3 py-1 rounded-md">הזמינו עכשיו</a>
        </div>
    </nav>

    <main>
        <!-- Section 1: The Search (החיפוש) -->
        <section id="hero" class="hero-section relative flex flex-col items-center justify-center text-center p-4 overflow-hidden">
            <canvas id="hero-canvas"></canvas>
            <div class="z-10">
                <h1 id="hero-text-1" class="text-3xl md:text-5xl lg:text-6xl font-light text-[#6F6253] opacity-0 fade-in">האם אתם מרגישים לפעמים שאתם מחפשים משהו...</h1>
                <h2 id="hero-text-2" class="text-xl md:text-3xl lg:text-4xl mt-6 font-extralight text-[#897967] opacity-0 fade-in-delay">אבל לא יודעים בדיוק מהו?</h2>
            </div>
            <a href="#disconnect" class="absolute bottom-10 animate-bounce text-3xl text-[#6F6253]">
                &#8595;
            </a>
        </section>

        <!-- Section 2: The Disconnect (הניתוק) -->
        <section id="disconnect" class="min-h-screen bg-[#EDECE6] py-20 px-4 flex flex-col items-center justify-center text-center">
            <div class="max-w-4xl mx-auto">
                <h2 class="text-3xl md:text-4xl font-semibold mb-6 text-[#4A238]">בעולם שרץ קדימה, קל לאבד את הקשר.</h2>
                <p class="text-lg md:text-xl text-[#6F6253] mb-12 max-w-2xl">המולת היומיום, הלחץ והריצה מרחיקים אותנו מהכוח האמיתי ששוכן בתוכנו. אנו מאבדים את החיבור אל הפנימיות, אל השקט.</p>
                <div class="grid grid-cols-2 md:grid-cols-4 gap-4 text-lg text-gray-400 initial-stress-visibility" id="stress-grid">
                    <span class="p-4 bg-white/50 rounded-lg shadow-sm">לחץ</span>
                    <span class="p-4 bg-white/50 rounded-lg shadow-sm">ריצה</span>
                    <span class="p-4 bg-white/50 rounded-lg shadow-sm">דאגות</span>
                    <span class="p-4 bg-white/50 rounded-lg shadow-sm">רעש</span>
                    <span class="p-4 bg-white/50 rounded-lg shadow-sm">חוסר שקט</span>
                    <span class="p-4 bg-white/50 rounded-lg shadow-sm">עומס</span>
                    <span class="p-4 bg-white/50 rounded-lg shadow-sm">בלבול</span>
                    <span class="p-4 bg-white/50 rounded-lg shadow-sm">חיפוש</span>
                </div>
                 <p class="text-xl md:text-2xl text-[#4A238] mt-12 transition-opacity duration-1000 opacity-0" id="revelation-text">אבל יש סוד. סוד עתיק שמחכה להתגלות.</p>
            </div>
        </section>
        
        <!-- Section 3: The Secret (הסוד) -->
        <section id="the-secret" class="py-20 px-4">
            <div class="max-w-5xl mx-auto flex flex-col md:flex-row items-center gap-12">
                <div class="md:w-1/2 text-center md:text-right">
                    <h2 class="text-4xl md:text-5xl font-bold mb-4 text-[#C19A6B]">הסוד שבך</h2>
                    <h3 class="text-2xl md:text-3xl mb-6 text-[#6F6253]">מאת הרב מאיר שלמה זצ"ל</h3>
                    <p class="text-lg text-[#4A238] leading-relaxed mb-4">בספרו המופלא, הרב מאיר שלמה זצ"ל נוגע בנקודה העמוקה ביותר. הוא חושף בפנינו דרך פשוטה ועוצמתית למצוא את אותה נקודה פנימית, טהורה ונצחית, המחברת אותנו לעצמנו ולמשמעות האמיתית של החיים.</p>
                    <p class="text-lg text-[#4A238] leading-relaxed">זה לא עוד ספר. זהו מפתח.</p>
                </div>
                <div class="md:w-1/2 flex justify-center">
                    <div id="book-cover" class="w-64 h-96 rounded-lg shadow-2xl flex items-center justify-center text-center p-0 cursor-pointer transform hover:scale-105 transition-transform duration-300 relative overflow-hidden">
                        <img src="https://i.imgur.com/AC82HLO.jpg" 
                             alt="[Image of כריכת הספר הסוד שבך]" 
                             class="book-image rounded-lg"
                             onerror="this.onerror=null;this.src='https://placehold.co/256x384/D7C4A5/4A238?text=טעינת+תמונה+נכשלה';">
                        <canvas id="ripple-canvas" class="absolute inset-0 w-full h-full"></canvas>
                    </div>
                </div>
            </div>
        </section>

        <!-- Section: Rabbi Biography (קורות חיים של הרב) -->
        <section id="rabbi-bio" class="bg-[#EDECE6] py-20 px-4">
            <div class="max-w-5xl mx-auto flex flex-col md:flex-row items-center gap-12 text-center md:text-right">
                <div class="md:w-1/3 flex justify-center">
                    <img src="https://i.imgur.com/eGtAnIb.jpeg" 
                         alt="[Image of הרב מאיר שלמה זצ''ל]" 
                         class="rabbi-image"
                         onerror="this.onerror=null;this.src='https://placehold.co/200x200/D7C4A5/4A238?text=טעינת+תמונה+נכשלה';">
                </div>
                <div class="md:w-2/3">
                    <h2 class="text-4xl md:text-5xl font-bold mb-4 text-[#4A238]">הרב מאיר שלמה זצ"ל</h2>
                    <h3 class="text-2xl md:text-3xl mb-6 text-[#6F6253]">המחבר והרועה הרוחני</h3>
                    <p class="text-lg text-[#4A238] leading-relaxed mb-4">הרב מאיר שלמה זצ"ל היה דמות רוחנית מיוחדת במינה, שחייו ופועלו הוקדשו להפצת תורה וחיבור נשמות למקורן. דרשותיו וכתביו שילבו עומק תורני עם נגישות ומסרים מחזקים לכל אדם.</p>
                    <p class="text-lg text-[#4A238] leading-relaxed">בכתביו, ובעיקר בספר "הסוד שבך", הרב שאף להאיר את הדרך לאנשים לגלות את הפוטנציאל הרוחני הטמון בהם, ולהגיע לשלמות פנימית מתוך חיבור אמיתי לעצמם ולבורא עולם. מורשתו ממשיכה להאיר את דרכם של רבים גם כיום.</p>
                </div>
            </div>
        </section>

        <!-- Section: Book Excerpts (טעימה מהספר) -->
        <section id="book-excerpts" class="py-20 px-4">
            <div class="max-w-4xl mx-auto text-center">
                <h2 class="text-4xl md:text-5xl font-bold mb-12 text-[#C19A6B]">טעימה מהספר: הסוד שבך – לגלות את אור הנשמה</h2>
                <div class="excerpt-box text-right">
                    <p class="text-xl text-[#4A238] leading-relaxed italic">"לפעמים אנחנו יכולים להרגיש שאין לנו כוח,
                        שאין לנו ערך, שאנחנו קטנים מול העולם.
                        אבל האמת היא, שבכל אחד ואחת מאיתנו
                        טמון כוח עצום – אור שמחכה להתגלות."</p>
                    <p class="text-base text-[#6F6253] mt-4">- מתוך 'הסוד שבך'</p>
                </div>
                <div class="excerpt-box text-right">
                    <p class="text-xl text-[#4A238] leading-relaxed italic">"אנחנו לא צריכים להיות מישהו אחר.
                        אנחנו צריכים להיות אנחנו.
                        וזה, בדיוק זה,
                        המתנה הגדולה ביותר שאנחנו יכולים לתת לעולם."</p>
                    <p class="text-base text-[#6F6253] mt-4">- מתוך 'הסוד שבך'</p>
                </div>
                <div class="excerpt-box text-right">
                    <p class="text-xl text-[#4A238] leading-relaxed italic">"כי כשאדם מגלה את האור שבו –
                        הוא מאיר את העולם כולו."</p>
                    <p class="text-base text-[#6F6253] mt-4">- מתוך 'הסוד שבך'</p>
                </div>
            </div>
        </section>

        <!-- Section 4: The Journey (המסע) -->
        <section id="the-journey" class="bg-[#EDECE6] py-20 px-4">
            <div class="max-w-6xl mx-auto">
                <h2 class="text-4xl md:text-5xl font-bold text-center mb-4 text-[#4A238]">צאו למסע אל עומק הנשמה</h2>
                <p class="text-xl text-center text-[#6F6253] mb-12">הספר הוא מורה דרך. גלו את הכלים שהוא מציע לחיים שלווים ומלאי משמעות.</p>
                <div class="grid md:grid-cols-3 gap-8">
                    <div class="card bg-white p-6 rounded-lg shadow-lg cursor-pointer text-center" data-card-id="1">
                        <div class="front">
                            <div class="text-5xl mb-4">✨</div>
                            <h3 class="text-2xl font-bold text-[#C19A6B] mb-2">שחרור מדאגות</h3>
                            <p class="text-[#6F6253]">למדו כיצד להניח למחשבות המטרידות ולהתחבר לשקט הפנימי.</p>
                            <p class="mt-4 text-sm font-semibold text-[#4A238]">לחצו לגילוי</p>
                        </div>
                        <div class="back p-4">
                            <h3 class="text-xl font-bold text-[#C19A6B] mb-2">אל השלווה</h3>
                            <p class="text-[#4A238] leading-relaxed">"דרך דברי חכמתו והדרכתו, תמצאו את הכלים לשחרר דאגות, להגיע לשלווה פנימית, ולראות את העולם באור חדש."</p>
                            <p class="mt-4 text-sm font-semibold text-[#4A238]">לחצו לסגירה</p>
                        </div>
                    </div>
                    <div class="card bg-white p-6 rounded-lg shadow-lg cursor-pointer text-center" data-card-id="2">
                         <div class="front">
                            <div class="text-5xl mb-4">🧭</div>
                            <h3 class="text-2xl font-bold text-[#C19A6B] mb-2">מציאת הייעוד</h3>
                            <p class="text-[#6F6253]">גלו את הכוח לממש את הפוטנציאל הייחודי הטמון בכם.</p>
                             <p class="mt-4 text-sm font-semibold text-[#4A238]">לחצו לגילוי</p>
                        </div>
                        <div class="back p-4">
                            <h3 class="text-xl font-bold text-[#C19A6B] mb-2">אל המימוש</h3>
                             <p class="text-[#4A238] leading-relaxed">"הספר מעניק הבנה עמוקה כיצד לממש את הייעוד שלכם בעולם, ולחיות חיים של סיפוק ותרומה מתוך חיבור אמיתי."</p>
                             <p class="mt-4 text-sm font-semibold text-[#4A238]">לחצו לסגירה</p>
                        </div>
                    </div>
                    <div class="card bg-white p-6 rounded-lg shadow-lg cursor-pointer text-center" data-card-id="3">
                         <div class="front">
                            <div class="text-5xl mb-4">🔗</div>
                            <h3 class="text-2xl font-bold text-[#C19A6B] mb-2">חיבור בלתי מתפשר</h3>
                            <p class="text-[#6F6253]">העמיקו את הקשר לעצמכם, למקור, ולעולם שסביבכם.</p>
                             <p class="mt-4 text-sm font-semibold text-[#4A238]">לחצו לגילוי</p>
                        </div>
                        <div class="back p-4">
                            <h3 class="text-xl font-bold text-[#C19A6B] mb-2">אל האחדות</h3>
                             <p class="text-[#4A238] leading-relaxed">"זהו ספר על חיבור. חיבור בלתי מתפשר אל האני האמיתי, אל הנשמה, ומתוך כך - אל הבורא ואל הבריאה כולה."</p>
                             <p class="mt-4 text-sm font-semibold text-[#4A238]">לחצו לסגירה</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Section 5: The Invitation (ההזמנה) -->
        <section id="cta" class="py-20 px-4 text-center">
            <div class="max-w-3xl mx-auto">
                <h2 class="text-4xl md:text-5xl font-bold mb-4 text-[#4A238]">המסע שלכם מתחיל עכשיו.</h2>
                <p class="text-xl text-[#6F6253] mb-8">אל תחכו לרגע אחר. גלו את האור, את הכוח, את הסוד שבכם.</p>
                <a href="https://wa.me/972527660731" target="_blank" class="bg-[#C19A6B] text-white text-xl font-bold py-4 px-10 rounded-full shadow-lg hover:bg-[#a98458] transition-colors duration-300">
                    <span style="font-size: 24px; vertical-align: middle; margin-left: 8px;">&#x1F4AC;</span> הזמינו בווטסאפ
                </a>
                <p class="mt-6 text-sm text-[#897967]">להשיג בחנויות הספרים המובחרות ובאתר</p>
            </div>
        </section>
    </main>
    
    <footer class="text-center py-6 bg-[#EDECE6] text-[#897967]">
        <p>&copy; 2024 | כל הזכויות שמורות להוצאת הספרים</p>
    </footer>

    <script>
        document.addEventListener('DOMContentLoaded', function() {
            // Section 1: Hero Canvas Animation
            const heroCanvas = document.getElementById('hero-canvas');
            const heroCtx = heroCanvas.getContext('2d');
            let particles = [];

            function resizeHeroCanvas() {
                heroCanvas.width = heroCanvas.offsetWidth;
                heroCanvas.height = heroCanvas.offsetHeight;
            }
            resizeHeroCanvas();
            window.addEventListener('resize', resizeHeroCanvas);

            class Particle {
                constructor() {
                    this.x = Math.random() * heroCanvas.width;
                    this.y = Math.random() * heroCanvas.height;
                    this.size = Math.random() * 2 + 1;
                    this.speedX = Math.random() * 0.5 - 0.25;
                    this.speedY = Math.random() * 0.5 - 0.25;
                    this.opacity = Math.random() * 0.5 + 0.3;
                }
                update() {
                    this.x += this.speedX;
                    this.y += this.speedY;
                    if (this.size > 0.1) this.size -= 0.01;
                    if (this.x < 0 || this.x > heroCanvas.width) this.speedX *= -1;
                    if (this.y < 0 || this.y > heroCanvas.height) this.speedY *= -1;
                }
                draw() {
                    heroCtx.fillStyle = `rgba(193, 154, 107, ${this.opacity})`;
                    heroCtx.beginPath();
                    heroCtx.arc(this.x, this.y, this.size, 0, Math.PI * 2);
                    heroCtx.fill();
                }
            }

            function initParticles() {
                for (let i = 0; i < 50; i++) {
                    particles.push(new Particle());
                }
            }
            initParticles();

            function animateParticles() {
                heroCtx.clearRect(0, 0, heroCanvas.width, heroCanvas.height);
                for (let i = 0; i < particles.length; i++) {
                    particles[i].update();
                    particles[i].draw();
                    if (particles[i].size <= 0.1) {
                        particles.splice(i, 1);
                        particles.push(new Particle());
                        i--;
                    }
                }
                requestAnimationFrame(animateParticles);
            }
            animateParticles();

            // Section 2: Intersection Observer for stress grid
            const revelationText = document.getElementById('revelation-text');
            const stressGrid = document.getElementById('stress-grid');
            const stressSpans = stressGrid.querySelectorAll('span');

            const observer = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        // Apply flash and disappear animation to each span
                        stressSpans.forEach((span, index) => {
                            // Delay each span slightly to create a ripple effect, or keep simultaneous
                            setTimeout(() => {
                                span.classList.add('flash-disappear-item');
                            }, index * 100); // Small delay per item
                        });

                        // After the animation, hide the grid and show the revelation text
                        setTimeout(() => {
                           stressGrid.style.display = 'none'; // Completely hide the grid
                           revelationText.style.opacity = '1';
                        }, 1500 + (stressSpans.length - 1) * 100); // Wait for the longest animation to finish + a little more
                    }
                });
            }, { threshold: 0.5 });
            observer.observe(stressGrid);

            // Section 3: Ripple effect on book cover
            const bookCover = document.getElementById('book-cover');
            const rippleCanvas = document.getElementById('ripple-canvas');
            const rippleCtx = rippleCanvas.getContext('2d');
            let ripples = [];

            function resizeRippleCanvas() {
                 rippleCanvas.width = bookCover.offsetWidth;
                 rippleCanvas.height = bookCover.offsetHeight;
            }
            resizeRippleCanvas();
            window.addEventListener('resize', resizeRippleCanvas)

            bookCover.addEventListener('click', (e) => {
                const rect = rippleCanvas.getBoundingClientRect();
                const x = e.clientX - rect.left;
                const y = e.clientY - rect.top;
                ripples.push({ x, y, radius: 0, opacity: 1 });
            });

            function animateRipples() {
                rippleCtx.clearRect(0, 0, rippleCanvas.width, rippleCanvas.height);
                for (let i = 0; i < ripples.length; i++) {
                    let r = ripples[i];
                    r.radius += 2;
                    r.opacity -= 0.02;
                    if (r.opacity <= 0) {
                        ripples.splice(i, 1);
                        i--;
                    }
                    else {
                        rippleCtx.beginPath();
                        rippleCtx.arc(r.x, r.y, r.radius, 0, Math.PI * 2);
                        rippleCtx.strokeStyle = `rgba(255, 255, 255, ${r.opacity})`;
                        rippleCtx.lineWidth = 2;
                        rippleCtx.stroke();
                    }
                }
                requestAnimationFrame(animateRipples);
            }
            animateRipples();

            // Section 4: Interactive Cards
            const cards = document.querySelectorAll('.card');
            cards.forEach(card => {
                card.addEventListener('click', () => {
                    card.classList.toggle('flipped');
                });
            });

        });
    </script>
</body>
</html>
