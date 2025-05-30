<h<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Viralize no TikTok - O Guia Definitivo</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link rel="icon" href="caminho/para/favicon.ico" type="image/x-icon">
    <style>
        .hero-gradient {
            background: linear-gradient(135deg, #69bcf4 0%, #25fde9 50%, #fe2c55 100%);
        }
        .pulse-animation {
            animation: pulse 2s infinite;
        }
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }
        .floating {
            animation: floating 3s ease-in-out infinite;
        }
        @keyframes floating {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-15px); }
            100% { transform: translateY(0px); }
        }
    </style>
</head>
<body class="font-sans bg-gray-50">
    <!-- Header/Navigation -->
    <header class="bg-white shadow-sm sticky top-0 z-50">
        <div class="container mx-auto px-4 py-3 flex justify-between items-center">
            <div class="flex items-center">
                <i class="fab fa-tiktok text-2xl text-pink-600 mr-2"></i>
                <span class="text-xl font-bold bg-gradient-to-r from-blue-400 to-pink-600 bg-clip-text text-transparent">UnkanownTIK</span>
            </div>
            <nav class="hidden md:flex space-x-8">
                <a href="#features" class="text-gray-700 hover:text-pink-600 font-medium">Benefícios</a>
                <a href="#content" class="text-gray-700 hover:text-pink-600 font-medium">Conteúdo</a>
                <a href="#testimonials" class="text-gray-700 hover:text-pink-600 font-medium">Depoimentos</a>
                <a href="#faq" class="text-gray-700 hover:text-pink-600 font-medium">FAQ</a>
            </nav>
            <button class="md:hidden text-gray-700">
                <i class="fas fa-bars text-2xl"></i>
            </button>
        </div>
    </header>

    <script>
        const menuButton = document.querySelector('button');
        const menu = document.querySelector('nav');

        menuButton.addEventListener('click', () => {
            menu.classList.toggle('hidden');
        });
    </script>

    <!-- Hero Section -->
    <section class="hero-gradient text-white py-16 md:py-24">
        <div class="container mx-auto px-4 flex flex-col md:flex-row items-center">
            <div class="md:w-1/2 mb-10 md:mb-0">
                <h1 class="text-4xl md:text-5xl font-bold mb-4">Domine o TikTok e Vire uma Estrela!</h1>
                <p class="text-xl mb-8">O guia definitivo para criar conteúdo viral, ganhar milhões de views e construir uma audiência fiel na plataforma que está dominando o mundo.</p>
                <div class="flex flex-col sm:flex-row gap-4">
                    <a href="http://bit.ly/tiktok-dark-7-dias" target="_blank" class="bg-white text-pink-600 font-bold py-3 px-8 rounded-full hover:bg-gray-100 transition duration-300 text-center pulse-animation">
                        Compre Agora <i class="fas fa-arrow-right ml-2"></i>
                    </a>
                    <a href="#features" class="border-2 border-white text-white font-bold py-3 px-8 rounded-full hover:bg-white hover:text-pink-600 transition duration-300 text-center">
                        Saiba Mais
                    </a>
                </div>
                <div class="mt-8 flex items-center">
                    <div class="flex -space-x-2">
                        <img src="https://randomuser.me/api/portraits/women/44.jpg" class="w-10 h-10 rounded-full border-2 border-white">
                        <img src="https://randomuser.me/api/portraits/men/32.jpg" class="w-10 h-10 rounded-full border-2 border-white">
                        <img src="https://randomuser.me/api/portraits/women/68.jpg" class="w-10 h-10 rounded-full border-2 border-white">
                    </div>
                    <p class="ml-3 text-sm">+5.000 criadores já transformaram seus perfis</p>
                </div>
            </div>
            <div class="md:w-1/2 flex justify-center">
                <div class="relative">
                    <img src="https://m.media-amazon.com/images/I/71YHjVXyR0L._AC_UF1000,1000_QL80_.jpg" alt="Capa do guia TikTok edição 2025" class="w-64 md:w-80 rounded-lg shadow-2xl floating">
                    <div class="absolute -bottom-5 -right-5 bg-yellow-400 text-gray-900 px-4 py-2 rounded-full font-bold text-sm">
                        <i class="fas fa-bolt mr-1"></i> NOVA EDIÇÃO 2025
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-8">
        <div class="container mx-auto px-4 text-center">
            <p>&copy; 2025 ViralTik. Todos os direitos reservados.</p>
        </div>
    </footer>
</body>
</html>
