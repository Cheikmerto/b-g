<!DOCTYPE html>
<html lang="es" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BLOOD & GUTS - La Filosofía Brutal de Dorian Yates</title>
    
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        blood: '#b71c1c',
                        bloodDark: '#7f0000',
                        void: '#0a0a0a',
                        iron: '#1a1a1a'
                    },
                    fontFamily: {
                        bebas: ['"Bebas Neue"', 'cursive'],
                        roboto: ['Roboto', 'sans-serif'],
                    },
                    boxShadow: {
                        'blood-glow': '0 0 20px rgba(183, 28, 28, 0.6)',
                        'blood-glow-lg': '0 0 40px rgba(183, 28, 28, 0.8)',
                    }
                }
            }
        }
    </script>

    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Roboto:wght@300;400;700;900&display=swap" rel="stylesheet">
    
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

    <style>
        body {
            background-color: #0a0a0a;
            color: #e5e5e5;
        }
        
        /* Custom Scrollbar */
        ::-webkit-scrollbar { width: 10px; }
        ::-webkit-scrollbar-track { background: #0a0a0a; }
        ::-webkit-scrollbar-thumb { background: #b71c1c; }
        ::-webkit-scrollbar-thumb:hover { background: #7f0000; }

        /* Typography */
        h1, h2, h3, h4, h5, h6, .font-bebas { font-family: 'Bebas Neue', sans-serif; letter-spacing: 2px; }
        p, li, span, td, th { font-family: 'Roboto', sans-serif; }

        /* Parallax Hero */
        .hero-bg {
            background-image: linear-gradient(to bottom, rgba(10,10,10,0.3) 0%, rgba(10,10,10,1) 100%), url('https://i1.sndcdn.com/artworks-5y0wN7EYErZcyFx1-Ja3P5Q-t500x500.jpg');
            background-size: cover;
            background-position: center 20%;
            background-attachment: fixed;
        }

        /* Animations */
        .fade-in { animation: fadeIn 1.5s ease-in forwards; opacity: 0; }
        .slide-up { animation: slideUp 1s ease-out forwards; opacity: 0; transform: translateY(30px); }
        
        @keyframes fadeIn { to { opacity: 1; } }
        @keyframes slideUp { to { opacity: 1; transform: translateY(0); } }

        /* Image Hover Effect */
        .brutal-hover {
            transition: all 0.4s ease;
            filter: grayscale(80%) contrast(120%);
        }
        .brutal-hover:hover {
            filter: grayscale(0%) contrast(110%);
            transform: scale(1.05);
            box-shadow: 0 0 25px rgba(183, 28, 28, 0.7);
            border-color: #b71c1c;
        }

        /* Blood Accents */
        .text-blood { color: #b71c1c; text-shadow: 2px 2px 4px rgba(0,0,0,0.8); }
        .border-blood-l { border-left: 4px solid #b71c1c; }
        
        /* Table Styles */
        .gym-table th { background-color: #b71c1c; color: white; text-transform: uppercase; letter-spacing: 1px; }
        .gym-table tr { border-bottom: 1px solid #333; transition: background-color 0.3s; }
        .gym-table tr:hover { background-color: #1a1a1a; }
        .gym-table td { color: #ccc; }
    </style>
</head>
<body class="antialiased selection:bg-blood selection:text-white">

    <header class="hero-bg h-screen w-full relative flex flex-col items-center justify-center text-center px-4">
        <div class="absolute inset-0 bg-black/70 z-0"></div>
        
        <div class="z-10 slide-up" style="animation-delay: 0.2s;">
            <h1 class="text-7xl md:text-9xl font-bebas text-white mb-2 tracking-widest drop-shadow-2xl">
                BLOOD <span class="text-blood">&</span> GUTS
            </h1>
            <h2 class="text-2xl md:text-4xl text-gray-300 font-bebas tracking-widest uppercase mb-8 border-b-2 border-blood pb-4 inline-block">
                La Filosofía de <span class="text-white">Dorian Yates</span>
            </h2>
            <p class="text-lg md:text-xl text-gray-400 max-w-2xl mx-auto font-light leading-relaxed mb-10">
                Olvida el volumen vacío. Olvida las horas interminables. Entra en el dominio de la intensidad máxima, el fallo absoluto y el crecimiento muscular real.
            </p>
            
            <a href="#filosofia" class="inline-block bg-blood hover:bg-bloodDark text-white font-bebas text-2xl py-4 px-10 transition-all duration-300 shadow-blood-glow hover:shadow-blood-glow-lg border border-blood hover:border-white uppercase tracking-wider">
                Entrena como un Campeón <i class="fas fa-chevron-down ml-2 text-sm"></i>
            </a>
        </div>
    </header>

    <section id="filosofia" class="py-24 bg-void px-4 md:px-8 lg:px-16">
        <div class="max-w-6xl mx-auto">
            <div class="text-center mb-20 fade-in" style="animation-delay: 0.3s;">
                <h2 class="text-5xl md:text-7xl font-bebas text-white mb-4">El Origen del <span class="text-blood">HIT</span></h2>
                <div class="w-24 h-1 bg-blood mx-auto"></div>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-16 items-center">
                <div class="space-y-6 slide-up" style="animation-delay: 0.4s;">
                    <h3 class="text-3xl font-bebas text-white border-blood-l pl-4">El Ascenso de "The Shadow"</h3>
                    <p class="text-gray-400 leading-relaxed text-lg">
                        Dorian Yates no solo ganó 6 títulos de Mr. Olympia (1992-1997); revolucionó el culturismo para siempre. En una era dominada por rutinas de alto volumen y doble sesión diaria, Dorian apareció desde las sombras del Temple Gym en Birmingham con una densidad muscular jamás vista, construida con menos de 4 horas de entrenamiento a la semana.
                    </p>
                    
                    <h3 class="text-3xl font-bebas text-white border-blood-l pl-4 mt-8">De Arthur Jones a Mike Mentzer</h3>
                    <p class="text-gray-400 leading-relaxed text-lg">
                        La base fue establecida por <strong>Arthur Jones</strong> (creador de Nautilus), quien postuló que el músculo necesita intensidad, no volumen. <strong>Mike Mentzer</strong> llevó esto al extremo con su filosofía <em>Heavy Duty</em>, recomendando entrenamientos infrecuentes y series únicas al fallo absoluto.
                    </p>
                    
                    <h3 class="text-3xl font-bebas text-white border-blood-l pl-4 mt-8">El Sistema DYHIT (Blood & Guts)</h3>
                    <p class="text-gray-400 leading-relaxed text-lg">
                        Dorian tomó la brutalidad del Heavy Duty y la adaptó. A diferencia de Mentzer, que prescribía descansos de hasta una semana, Yates estableció un split de 4 días. El núcleo se mantuvo: calentamiento progresivo seguido de <strong>una única serie efectiva llevada más allá del fallo absoluto</strong> utilizando técnicas de intensidad como repeticiones forzadas y negativas.
                    </p>
                </div>

                <div class="bg-iron p-8 border border-gray-800 shadow-2xl relative slide-up" style="animation-delay: 0.6s;">
                    <div class="absolute -top-6 -left-6 text-6xl text-blood opacity-30"><i class="fas fa-quote-left"></i></div>
                    
                    <div class="space-y-8">
                        <blockquote class="border-l-2 border-gray-600 pl-4">
                            <p class="text-xl italic text-gray-300 font-light">"Si puedes hacer 11 repeticiones, pero te detienes en 10, no has entrenado; solo has hecho ejercicio. Tienes que ir a lugares oscuros donde otros no están dispuestos a ir."</p>
                            <footer class="text-blood font-bebas text-xl mt-2">— Dorian Yates</footer>
                        </blockquote>
                        
                        <blockquote class="border-l-2 border-gray-600 pl-4">
                            <p class="text-xl italic text-gray-300 font-light">"Solo cuando operas al límite absoluto de tu capacidad actual, estimulas a tu cuerpo a aumentar esa capacidad."</p>
                            <footer class="text-gray-500 font-bebas text-xl mt-2">— Mike Mentzer</footer>
                        </blockquote>

                        <div class="bg-black p-6 border-t-4 border-blood mt-8">
                            <h4 class="font-bebas text-2xl text-white mb-2">Pilares del Blood & Guts</h4>
                            <ul class="text-gray-400 space-y-2 list-none">
                                <li><i class="fas fa-skull text-blood mr-2"></i> <strong>Intensidad Máxima:</strong> 100% de esfuerzo físico y mental.</li>
                                <li><i class="fas fa-dumbbell text-blood mr-2"></i> <strong>Series Únicas:</strong> 1 serie de trabajo por ejercicio al fallo.</li>
                                <li><i class="fas fa-stopwatch text-blood mr-2"></i> <strong>Cadencia Controlada:</strong> Positiva explosiva, negativa de 3-4 segundos.</li>
                                <li><i class="fas fa-bed text-blood mr-2"></i> <strong>Recuperación:</strong> El músculo crece descansando.</li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="py-20 bg-black px-4">
        <div class="max-w-7xl mx-auto">
            <div class="text-center mb-16">
                <h2 class="text-5xl md:text-7xl font-bebas text-white">Galería <span class="text-blood">Legendaria</span></h2>
                <p class="text-gray-500 mt-2 font-bebas text-xl tracking-widest">El Físico que Cambió las Reglas</p>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4">
                <div class="overflow-hidden relative group border border-gray-800 bg-iron">
                    <img src="https://www.evolutionofbodybuilding.net/wp-content/uploads/2017/04/Dorian-Yates4.jpeg" alt="Dorian Yates Back Double Biceps" class="w-full h-80 object-cover brutal-hover" style="object-position: center 45%;">
                    <div class="absolute bottom-0 left-0 w-full bg-gradient-to-t from-black to-transparent p-4 opacity-0 group-hover:opacity-100 transition-opacity">
                        <span class="font-bebas text-blood text-xl tracking-wider">Espalda Mutante</span>
                    </div>
                </div>
                <div class="overflow-hidden relative group border border-gray-800 bg-iron">
                    <img src="https://i0.wp.com/www.muscleandfitness.com/wp-content/uploads/2019/06/Dorian-Yates-Posing.jpg?quality=86&strip=all" alt="Dorian Yates Lat Spread Posing" class="w-full h-80 object-cover object-center brutal-hover">
                    <div class="absolute bottom-0 left-0 w-full bg-gradient-to-t from-black to-transparent p-4 opacity-0 group-hover:opacity-100 transition-opacity">
                        <span class="font-bebas text-blood text-xl tracking-wider">Lat Spread</span>
                    </div>
                </div>
                <div class="overflow-hidden relative group border border-gray-800 bg-iron">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS55e0eMDhkVkwzR6rHUB-GwrUfmravHXYi5s8UgILZlzMw9WiGlpfw-hrh&s=10" alt="Dorian Yates Training at Temple Gym" class="w-full h-80 object-cover object-center brutal-hover">
                    <div class="absolute bottom-0 left-0 w-full bg-gradient-to-t from-black to-transparent p-4 opacity-0 group-hover:opacity-100 transition-opacity">
                        <span class="font-bebas text-blood text-xl tracking-wider">Temple Gym</span>
                    </div>
                </div>
                <div class="overflow-hidden relative group border border-gray-800 bg-iron">
                    <img src="https://i.pinimg.com/736x/9e/93/4b/9e934bbf336d85930ff8297f893c2c26.jpg" alt="Dorian Yates Posing Mr. Olympia 1993" class="w-full h-80 object-cover object-top brutal-hover">
                    <div class="absolute bottom-0 left-0 w-full bg-gradient-to-t from-black to-transparent p-4 opacity-0 group-hover:opacity-100 transition-opacity">
                        <span class="font-bebas text-blood text-xl tracking-wider">Mr. Olympia '93</span>
                    </div>
                </div>
                <div class="overflow-hidden relative group border border-gray-800 bg-iron">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT6KswOJUqUvji5dH6H_jhUdR5_QeO_YXiKiqBuoCtnUxPmZuAY4ITq5J3E&s=10" alt="Dorian Yates Side Chest Pose" class="w-full h-80 object-cover object-top brutal-hover">
                    <div class="absolute bottom-0 left-0 w-full bg-gradient-to-t from-black to-transparent p-4 opacity-0 group-hover:opacity-100 transition-opacity">
                        <span class="font-bebas text-blood text-xl tracking-wider">Pecho de Perfil</span>
                    </div>
                </div>
                <div class="overflow-hidden relative group border border-gray-800 bg-iron">
                    <img src="https://i1.sndcdn.com/artworks-5y0wN7EYErZcyFx1-Ja3P5Q-t500x500.jpg" alt="Dorian Yates Blood and Guts Documentary Era" class="w-full h-80 object-cover object-top brutal-hover">
                    <div class="absolute bottom-0 left-0 w-full bg-gradient-to-t from-black to-transparent p-4 opacity-0 group-hover:opacity-100 transition-opacity">
                        <span class="font-bebas text-blood text-xl tracking-wider">Intensidad Pura</span>
                    </div>
                </div>
                <div class="overflow-hidden relative group border border-gray-800 bg-iron">
                    <img src="https://pbs.twimg.com/media/BldDgSjIQAA7BJ-.jpg" alt="Dorian Yates Most Muscular Pose" class="w-full h-80 object-cover object-top brutal-hover">
                    <div class="absolute bottom-0 left-0 w-full bg-gradient-to-t from-black to-transparent p-4 opacity-0 group-hover:opacity-100 transition-opacity">
                        <span class="font-beb<!DOCTYPE html>
<html lang="es" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BLOOD & GUTS - La Filosofía Brutal de Dorian Yates</title>
    
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        blood: '#b71c1c',
                        bloodDark: '#7f0000',
                        void: '#0a0a0a',
                        iron: '#1a1a1a'
                    },
                    fontFamily: {
                        bebas: ['"Bebas Neue"', 'cursive'],
                        roboto: ['Roboto', 'sans-serif'],
                    },
                    boxShadow: {
                        'blood-glow': '0 0 20px rgba(183, 28, 28, 0.6)',
                        'blood-glow-lg': '0 0 40px rgba(183, 28, 28, 0.8)',
                    }
                }
            }
        }
    </script>

    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Roboto:wght@300;400;700;900&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

    <style>
        body { background-color: #0a0a0a; color: #e5e5e5; }
        ::-webkit-scrollbar { width: 10px; }
        ::-webkit-scrollbar-track { background: #0a0a0a; }
        ::-webkit-scrollbar-thumb { background: #b71c1c; }
        ::-webkit-scrollbar-thumb:hover { background: #7f0000; }
        h1, h2, h3, h4, h5, h6, .font-bebas { font-family: 'Bebas Neue', sans-serif; letter-spacing: 2px; }
        p, li, span, td, th { font-family: 'Roboto', sans-serif; }
        .hero-bg {
            background-image: linear-gradient(to bottom, rgba(10,10,10,0.3) 0%, rgba(10,10,10,1) 100%), url('https://i1.sndcdn.com/artworks-5y0wN7EYErZcyFx1-Ja3P5Q-t500x500.jpg');
            background-size: cover; background-position: center 20%; background-attachment: fixed;
        }
        .fade-in { animation: fadeIn 1.5s ease-in forwards; opacity: 0; }
        .slide-up { animation: slideUp 1s ease-out forwards; opacity: 0; transform: translateY(30px); }
        @keyframes fadeIn { to { opacity: 1; } }
        @keyframes slideUp { to { opacity: 1; transform: translateY(0); } }
        .brutal-hover { transition: all 0.4s ease; filter: grayscale(80%) contrast(120%); }
        .brutal-hover:hover { filter: grayscale(0%) contrast(110%); transform: scale(1.05); box-shadow: 0 0 25px rgba(183, 28, 28, 0.7); border-color: #b71c1c; }
        .text-blood { color: #b71c1c; text-shadow: 2px 2px 4px rgba(0,0,0,0.8); }
        .border-blood-l { border-left: 4px solid #b71c1c; }
        .gym-table th { background-color: #b71c1c; color: white; text-transform: uppercase; letter-spacing: 1px; }
        .gym-table tr { border-bottom: 1px solid #333; transition: background-color 0.3s; }
        .gym-table tr:hover { background-color: #1a1a1a; }
    </style>
</head>
<body class="antialiased selection:bg-blood selection:text-white">

    <header class="hero-bg h-screen w-full relative flex flex-col items-center justify-center text-center px-4">
        <div class="absolute inset-0 bg-black/70 z-0"></div>
        <div class="z-10 slide-up" style="animation-delay: 0.2s;">
            <h1 class="text-7xl md:text-9xl font-bebas text-white mb-2 tracking-widest drop-shadow-2xl">BLOOD <span class="text-blood">&</span> GUTS</h1>
            <h2 class="text-2xl md:text-4xl text-gray-300 font-bebas tracking-widest uppercase mb-8 border-b-2 border-blood pb-4 inline-block">La Filosofía de <span class="text-white">Dorian Yates</span></h2>
            <p class="text-lg md:text-xl text-gray-400 max-w-2xl mx-auto font-light leading-relaxed mb-10">Olvida el volumen vacío. Entra en el dominio de la intensidad máxima y el fallo absoluto.</p>
            <a href="#filosofia" class="inline-block bg-blood hover:bg-bloodDark text-white font-bebas text-2xl py-4 px-10 transition-all duration-300 shadow-blood-glow hover:shadow-blood-glow-lg border border-blood hover:border-white uppercase tracking-wider">Entrena como un Campeón</a>
        </div>
    </header>

    <section id="filosofia" class="py-24 bg-void px-4 md:px-8 lg:px-16">
        <div class="max-w-6xl mx-auto">
            <div class="text-center mb-20 fade-in"><h2 class="text-5xl md:text-7xl font-bebas text-white mb-4">El Origen del <span class="text-blood">HIT</span></h2><div class="w-24 h-1 bg-blood mx-auto"></div></div>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-16 items-center">
                <div class="space-y-6">
                    <h3 class="text-3xl font-bebas text-white border-blood-l pl-4">El Ascenso de "The Shadow"</h3>
                    <p class="text-gray-400 leading-relaxed text-lg">Dorian Yates no solo ganó 6 títulos de Mr. Olympia; revolucionó el culturismo con una densidad muscular jamás vista, construida con menos de 4 horas de entrenamiento a la semana.</p>
                </div>
                <div class="bg-iron p-8 border border-gray-800 shadow-2xl relative">
                    <blockquote class="border-l-2 border-gray-600 pl-4"><p class="text-xl italic text-gray-300 font-light">"Si puedes hacer 11 repeticiones, pero te detienes en 10, no has entrenado; solo has hecho ejercicio."</p><footer class="text-blood font-bebas text-xl mt-2">— Dorian Yates</footer></blockquote>
                </div>
            </div>
        </div>
    </section>

    <section class="py-20 bg-black px-4">
        <div class="max-w-7xl mx-auto">
            <div class="text-center mb-16"><h2 class="text-5xl md:text-7xl font-bebas text-white">Galería <span class="text-blood">Legendaria</span></h2></div>
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4">
                <div class="overflow-hidden relative group border border-gray-800 bg-iron">
                    <img src="https://www.evolutionofbodybuilding.net/wp-content/uploads/2017/04/Dorian-Yates4.jpeg" alt="Espalda Mutante" class="w-full h-80 object-cover brutal-hover" style="object-position: center 45%;">
                    <div class="absolute bottom-0 left-0 w-full bg-gradient-to-t from-black to-transparent p-4 opacity-0 group-hover:opacity-100 transition-opacity"><span class="font-bebas text-blood text-xl tracking-wider">Espalda Mutante</span></div>
                </div>
                <img src="https://i0.wp.com/www.muscleandfitness.com/wp-content/uploads/2019/06/Dorian-Yates-Posing.jpg?quality=86&strip=all" class="w-full h-80 object-cover object-center brutal-hover">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS55e0eMDhkVkwzR6rHUB-GwrUfmravHXYi5s8UgILZlzMw9WiGlpfw-hrh&s=10" class="w-full h-80 object-cover object-center brutal-hover">
                <img src="https://i.pinimg.com/736x/9e/93/4b/9e934bbf336d85930ff8297f893c2c26.jpg" class="w-full h-80 object-cover object-top brutal-hover">
            </div>
        </div>
    </section>

    <footer class="bg-void py-12 border-t border-gray-900 text-center">
        <p class="text-gray-700 text-sm">Diseñado para los discípulos del HIT. &copy; 2026 The Shadow Legacy.</p>
    </footer>
</body>
</html>as text-blood text-xl tracking-wider">Most Muscular</span>
                    </div>
                </div>
                <div class="relative border border-gray-800 bg-iron flex items-center justify-center overflow-hidden h-80">
                    <video controls loop class="w-full h-full object-cover" src="https://www.youtube.com/embed/-gNZPzefdlI"></video>
                </div>
            </div>
        </div>
    </section>

    <section class="py-24 bg-void px-4 border-y-2 border-blood/30">
        <div class="max-w-5xl mx-auto">
            <div class="text-center mb-16">
                <h2 class="text-5xl md:text-7xl font-bebas text-white mb-4">El Split <span class="text-blood">Blood & Guts</span></h2>
                <p class="text-gray-400 max-w-2xl mx-auto text-lg">
                    La rutina exacta que Dorian usó para dominar el Olympia. No cuentes los calentamientos; solo cuenta la serie de trabajo final. Debe llegar al fallo positivo y, preferiblemente, incluir 2-3 repeticiones forzadas o negativas pesadas.
                </p>
            </div>

            <div class="overflow-x-auto shadow-2xl shadow-black">
                <table class="w-full text-left border-collapse gym-table font-roboto">
                    <thead>
                        <tr>
                            <th class="p-4 text-xl font-bebas w-1/4">Día</th>
                            <th class="p-4 text-xl font-bebas w-1/4">Grupo Muscular</th>
                            <th class="p-4 text-xl font-bebas w-1/2">Enfoque y Ejercicios Clave</th>
                        </tr>
                    </thead>
                    <tbody class="bg-iron text-lg">
                        <tr>
                            <td class="p-4 border-blood-l font-bold text-white">Día 1</td>
                            <td class="p-4 text-blood font-bold">Hombros, Tríceps, Abs</td>
                            <td class="p-4">Press Smith, Elevaciones Laterales, Extensiones de Tríceps en polea. 1 Serie de trabajo (6-8 reps al fallo).</td>
                        </tr>
                        <tr>
                            <td class="p-4 border-blood-l font-bold text-white">Día 2</td>
                            <td class="p-4 text-blood font-bold">Espalda, Trapecios, Deltoide Post.</td>
                            <td class="p-4">Pull-overs con mancuerna/Nautilus, Remos con barra (Yates Row), Peso Muerto parcial. El infierno en la tierra.</td>
                        </tr>
                        <tr>
                            <td class="p-4 border-blood-l font-bold text-gray-500">Día 3</td>
                            <td class="p-4 text-gray-400 font-bold italic">Descanso Absoluto</td>
                            <td class="p-4 text-gray-500 italic">Alimentación, hidratación y sueño. Sin actividad cardiovascular intensa.</td>
                        </tr>
                        <tr>
                            <td class="p-4 border-blood-l font-bold text-white">Día 4</td>
                            <td class="p-4 text-blood font-bold">Pecho, Bíceps, Abs</td>
                            <td class="p-4">Press Inclinado (Smith o Barra), Aperturas Inclinadas, Curl con Barra, Curl de Concentración.</td>
                        </tr>
                        <tr>
                            <td class="p-4 border-blood-l font-bold text-white">Día 5</td>
                            <td class="p-4 text-blood font-bold">Piernas, Gemelos</td>
                            <td class="p-4">Prensa de Piernas, Sentadilla Hack, Extensiones, Curl Femoral, Elevaciones de Talón.</td>
                        </tr>
                        <tr>
                            <td class="p-4 border-blood-l font-bold text-gray-500">Día 6 & 7</td>
                            <td class="p-4 text-gray-400 font-bold italic">Descanso Absoluto</td>
                            <td class="p-4 text-gray-500 italic">Recuperación del Sistema Nervioso Central (SNC).</td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </div>
    </section>

    <section class="py-20 bg-black px-4">
        <div class="max-w-6xl mx-auto grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
            
            <div class="relative w-full aspect-video border-4 border-blood shadow-blood-glow bg-iron">
                <video controls loop class="w-full h-full object-cover" src="https://www.youtube.com/embed/K4i856tQZvY"></video>
            </div>

            <div>
                <h2 class="text-4xl md:text-5xl font-bebas text-white mb-6">La <span class="text-blood">Mentalidad</span> de la Sombra</h2>
                <div class="space-y-6">
                    <div class="flex items-start">
                        <i class="fas fa-brain text-blood text-2xl mt-1 mr-4"></i>
                        <div>
                            <h4 class="font-bebas text-2xl text-white tracking-wide">El Diario de Entrenamiento</h4>
                            <p class="text-gray-400">Dorian no dejaba nada al azar. Anotaba cada repetición y cada peso. Si hoy levantaste 100kg por 8 repeticiones, el próximo entreno debes buscar 102.5kg o 9 repeticiones. La sobrecarga progresiva es la ley.</p>
                        </div>
                    </div>
                    <div class="flex items-start">
                        <i class="fas fa-link text-blood text-2xl mt-1 mr-4"></i>
                        <div>
                            <h4 class="font-bebas text-2xl text-white tracking-wide">Conexión Mente-Músculo</h4>
                            <p class="text-gray-400">Mover el peso del punto A al punto B no sirve. Debes sentir las fibras desgarrándose. Controla la fase excéntrica (negativa); ahí es donde ocurre la mayor parte de la micro-rotura miofibrilar.</p>
                        </div>
                    </div>
                    <div class="flex items-start">
                        <i class="fas fa-shield-alt text-blood text-2xl mt-1 mr-4"></i>
                        <div>
                            <h4 class="font-bebas text-2xl text-white tracking-wide">No Eres un Levantador de Pesas</h4>
                            <p class="text-gray-400">Los culturistas usan los pesos como herramientas para estimular el músculo, no para demostrar fuerza. Deja el ego en la puerta del gimnasio.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <footer class="bg-void py-12 border-t border-gray-900 text-center">
        <div class="max-w-4xl mx-auto px-4">
            <h2 class="font-bebas text-4xl text-gray-500 mb-4 tracking-widest uppercase">Sangre, Agallas y <span class="text-blood">Hierro</span></h2>
            <p class="text-gray-600 mb-8 italic">"El gimnasio es una herramienta. Lo que importa es el nivel de intensidad que traes contigo."</p>
            
            <p class="text-gray-700 text-sm">
                Diseñado para los discípulos del HIT. La hipertrofia no se negocia. <br>
                &copy; 2026 The Shadow Legacy. HTML/CSS Independiente.
            </p>
        </div>
    </footer>

</body>
</html>
