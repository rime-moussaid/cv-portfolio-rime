# cv-portfolio-rime
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio | Rime Moussaid</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap');
        
        body {
            font-family: 'Inter', sans-serif;
            scroll-behavior: smooth;
        }

        .gradient-text {
            background: linear-gradient(135deg, #6366f1 0%, #a855f7 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .skill-card:hover {
            transform: translateY(-5px);
            transition: all 0.3s ease;
        }

        .section-fade {
            animation: fadeIn 1s ease-out;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-900">

    <!-- Navigation -->
    <nav class="fixed w-full bg-white/80 backdrop-blur-md z-50 shadow-sm">
        <div class="max-w-5xl mx-auto px-6 py-4 flex justify-between items-center">
            <span class="text-xl font-bold gradient-text">RM.</span>
            <div class="space-x-6 hidden md:block text-sm font-medium">
                <a href="#accueil" class="hover:text-indigo-600 transition">Accueil</a>
                <a href="#profil" class="hover:text-indigo-600 transition">Profil</a>
                <a href="#experience" class="hover:text-indigo-600 transition">Expérience</a>
                <a href="#competences" class="hover:text-indigo-600 transition">Compétences</a>
                <a href="#contact" class="bg-indigo-600 text-white px-4 py-2 rounded-full hover:bg-indigo-700 transition">Contact</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <header id="accueil" class="pt-32 pb-16 px-6">
        <div class="max-w-5xl mx-auto flex flex-col md:flex-row items-center gap-12">
            <div class="flex-1 space-y-6 section-fade">
                <h2 class="text-indigo-600 font-semibold tracking-wide uppercase text-sm">Étudiante en Marketing</h2>
                <h1 class="text-5xl md:text-6xl font-extrabold text-slate-900">Rime <span class="gradient-text">Moussaid</span></h1>
                <p class="text-lg text-slate-600 leading-relaxed max-w-lg">
                    Passionnée par le marketing digital et l'analyse du comportement consommateur. Actuellement étudiante à l'ESTS, je cherche à transformer mes connaissances académiques en impact réel.
                </p>
                <div class="flex gap-4">
                    <a href="#contact" class="px-8 py-3 bg-slate-900 text-white rounded-lg font-medium hover:bg-slate-800 transition shadow-lg">Me contacter</a>
                    <a href="https://github.com/rime-moussaid" target="_blank" class="p-3 border border-slate-200 rounded-lg hover:bg-slate-100 transition">
                        <i class="fab fa-github text-xl"></i>
                    </a>
                </div>
            </div>
            <div class="relative w-64 h-64 md:w-80 md:h-80">
                <div class="absolute inset-0 bg-indigo-200 rounded-3xl rotate-6"></div>
                <!-- Remplacer par une vraie photo si disponible -->
                <div class="absolute inset-0 bg-slate-200 rounded-3xl flex items-center justify-center overflow-hidden border-4 border-white shadow-xl">
                    <i class="fas fa-user text-6xl text-slate-400"></i>
                </div>
            </div>
        </div>
    </header>

    <!-- Profil Section -->
    <section id="profil" class="py-20 bg-white">
        <div class="max-w-5xl mx-auto px-6">
            <div class="grid md:grid-cols-2 gap-12 items-center">
                <div class="space-y-4">
                    <h3 class="text-3xl font-bold">Mon Profil</h3>
                    <div class="h-1 w-20 bg-indigo-600 rounded"></div>
                    <p class="text-slate-600 leading-relaxed">
                        Dotée d'un bon sens relationnel et d'une forte capacité d'analyse, je suis particulièrement intéressée par la communication commerciale et le marketing opérationnel. Mon parcours à l'ESTS m'a permis de développer une vision stratégique que j'ai hâte de mettre en pratique.
                    </p>
                </div>
                <div class="grid grid-cols-2 gap-4">
                    <div class="p-6 bg-slate-50 rounded-2xl border border-slate-100">
                        <i class="fas fa-graduation-cap text-indigo-600 mb-3 text-xl"></i>
                        <h4 class="font-bold">Formation</h4>
                        <p class="text-sm text-slate-500">Bac Économie & ESTS</p>
                    </div>
                    <div class="p-6 bg-slate-50 rounded-2xl border border-slate-100">
                        <i class="fas fa-globe text-indigo-600 mb-3 text-xl"></i>
                        <h4 class="font-bold">Langues</h4>
                        <p class="text-sm text-slate-500">Français, Arabe, Anglais</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Experience & Education -->
    <section id="experience" class="py-20 bg-slate-50">
        <div class="max-w-5xl mx-auto px-6">
            <h3 class="text-3xl font-bold mb-12 text-center">Parcours & Projets</h3>
            <div class="space-y-8">
                <!-- Expérience -->
                <div class="bg-white p-8 rounded-3xl shadow-sm border border-slate-100">
                    <div class="flex items-start justify-between mb-4">
                        <div>
                            <span class="px-3 py-1 bg-indigo-100 text-indigo-700 rounded-full text-xs font-bold uppercase">Expérience</span>
                            <h4 class="text-xl font-bold mt-2">Stage en Télémarketing</h4>
                            <p class="text-indigo-600">Access Téléservice | 2025</p>
                        </div>
                    </div>
                    <ul class="space-y-2 text-slate-600 italic">
                        <li>• Contact téléphonique, présentation de campagnes et sensibilisation.</li>
                        <li>• Collecte et suivi des dons, négociation et communication.</li>
                    </ul>
                </div>

                <!-- Projet -->
                <div class="bg-white p-8 rounded-3xl shadow-sm border border-slate-100">
                    <div class="flex items-start justify-between mb-4">
                        <div>
                            <span class="px-3 py-1 bg-purple-100 text-purple-700 rounded-full text-xs font-bold uppercase">Projet Académique</span>
                            <h4 class="text-xl font-bold mt-2">Mini-projet Marketing</h4>
                            <p class="text-slate-500 italic">Analyse de marché & Création web</p>
                        </div>
                    </div>
                    <p class="text-slate-600">
                        Étude de la concurrence locale et proposition de recommandations marketing. Création d'un mini-site web pour un produit fictif avec structuration du contenu.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Competences -->
    <section id="competences" class="py-20 bg-white">
        <div class="max-w-5xl mx-auto px-6">
            <h3 class="text-3xl font-bold mb-12 text-center">Expertises</h3>
            <div class="grid md:grid-cols-3 gap-8 text-center">
                <!-- Marketing -->
                <div class="skill-card p-8 bg-indigo-50 rounded-3xl border border-indigo-100">
                    <div class="w-12 h-12 bg-indigo-600 text-white rounded-xl flex items-center justify-center mx-auto mb-6">
                        <i class="fas fa-chart-line text-xl"></i>
                    </div>
                    <h4 class="text-xl font-bold mb-4">Marketing</h4>
                    <p class="text-sm text-slate-600 space-y-1">
                        Marketing Digital<br>Étude de marché<br>Segmentation & Ciblage
                    </p>
                </div>
                <!-- Outils -->
                <div class="skill-card p-8 bg-purple-50 rounded-3xl border border-purple-100">
                    <div class="w-12 h-12 bg-purple-600 text-white rounded-xl flex items-center justify-center mx-auto mb-6">
                        <i class="fas fa-laptop-code text-xl"></i>
                    </div>
                    <h4 class="text-xl font-bold mb-4">Outils</h4>
                    <p class="text-sm text-slate-600 space-y-1">
                        Excel & PowerPoint<br>Canva (Visual)<br>Google Analytics
                    </p>
                </div>
                <!-- Soft Skills -->
                <div class="skill-card p-8 bg-pink-50 rounded-3xl border border-pink-100">
                    <div class="w-12 h-12 bg-pink-600 text-white rounded-xl flex items-center justify-center mx-auto mb-6">
                        <i class="fas fa-users text-xl"></i>
                    </div>
                    <h4 class="text-xl font-bold mb-4">Transversal</h4>
                    <p class="text-sm text-slate-600 space-y-1">
                        Communication orale/écrite<br>Travail d'équipe<br>Organisation
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 bg-slate-900 text-white rounded-t-[3rem]">
        <div class="max-w-5xl mx-auto px-6">
            <div class="text-center mb-16">
                <h3 class="text-4xl font-bold mb-4">Collaborons ensemble</h3>
                <p class="text-slate-400">Ouverte aux opportunités de stage et de projets innovants.</p>
            </div>
            
            <div class="grid md:grid-cols-2 gap-12">
                <div class="space-y-6">
                    <div class="flex items-center gap-4">
                        <div class="w-12 h-12 bg-indigo-600/20 text-indigo-400 rounded-full flex items-center justify-center">
                            <i class="fas fa-envelope"></i>
                        </div>
                        <div>
                            <p class="text-xs text-slate-500 uppercase font-bold">Email</p>
                            <a href="mailto:rimemoussaid908@gmail.com" class="hover:text-indigo-400 transition">rimemoussaid908@gmail.com</a>
                        </div>
                    </div>
                    <div class="flex items-center gap-4">
                        <div class="w-12 h-12 bg-green-600/20 text-green-400 rounded-full flex items-center justify-center">
                            <i class="fas fa-phone"></i>
                        </div>
                        <div>
                            <p class="text-xs text-slate-500 uppercase font-bold">Téléphone</p>
                            <p>+212 6 79 40 08 12</p>
                        </div>
                    </div>
                </div>

                <form class="space-y-4" onsubmit="event.preventDefault(); document.getElementById('success').classList.remove('hidden');">
                    <input type="text" placeholder="Votre Nom" class="w-full bg-slate-800 border-none rounded-xl px-4 py-3 focus:ring-2 focus:ring-indigo-500 outline-none">
                    <textarea placeholder="Votre Message" rows="4" class="w-full bg-slate-800 border-none rounded-xl px-4 py-3 focus:ring-2 focus:ring-indigo-500 outline-none"></textarea>
                    <button type="submit" class="w-full py-3 bg-indigo-600 rounded-xl font-bold hover:bg-indigo-700 transition">Envoyer le message</button>
                    <p id="success" class="hidden text-green-400 text-sm text-center">Message envoyé avec succès ! (Simulation)</p>
                </form>
            </div>

            <div class="mt-20 pt-8 border-t border-slate-800 text-center text-slate-500 text-sm">
                <p>© 2025 Rime Moussaid. Fait avec passion pour le Marketing.</p>
            </div>
        </div>
    </section>

</body>
</html>
