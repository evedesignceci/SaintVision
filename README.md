**<!DOCTYPE html>
<html lang="pt-BR" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Saint Vision | Ótica Móvel a Domicílio</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts: Cinzel & Montserrat -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@500;700&family=Montserrat:wght@300;400;500;600&display=swap" rel="stylesheet">
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        primary: '#0C1628',
                        gold: '#EDB765',
                        champagne: '#F6CC87',
                    },
                    fontFamily: {
                        cinzel: ['Cinzel', 'serif'],
                        montserrat: ['Montserrat', 'sans-serif'],
                    }
                }
            }
        }
    </script>
</head>
<body class="bg-white text-primary font-montserrat antialiased">

    <!-- CABEÇALHO -->
    <header class="fixed top-0 left-0 w-full bg-primary/95 backdrop-blur-md z-50 border-b border-gold/20">
        <div class="max-w-7xl mx-auto px-6 h-20 flex items-center justify-between">
            <div class="flex flex-col">
                <span class="font-cinzel text-xl font-bold tracking-widest text-white">SAINT VISION</span>
                <span class="text-[10px] uppercase tracking-widest text-gold font-semibold">Ótica Móvel</span>
            </div>
            
            <nav class="hidden md:flex items-center space-x-8 text-sm font-medium text-white">
                <a href="#inicio" class="hover:text-gold transition-colors">Início</a>
                <a href="#como-funciona" class="hover:text-gold transition-colors">Como Funciona</a>
                <a href="#diferenciais" class="hover:text-gold transition-colors">Vantagens</a>
            </nav>

            <a href="#contato" class="bg-gold text-primary font-semibold px-5 py-2.5 rounded-full text-sm hover:bg-champagne transition-all shadow-lg hover:shadow-gold/20">
                Agendar Visita
            </a>
        </div>
    </header>

    <!-- HERO SECTION -->
    <section id="inicio" class="pt-32 pb-20 md:pt-44 md:pb-32 bg-primary text-white relative overflow-hidden">
        <div class="max-w-7xl mx-auto px-6 grid grid-cols-1 md:grid-cols-2 gap-12 items-center">
            <div class="space-y-6">
                <span class="inline-block text-xs uppercase tracking-widest bg-gold/10 text-gold px-3 py-1 rounded-full border border-gold/30">
                    Atendimento Exclusivo em Domicílio
                </span>
                <h1 class="font-cinzel text-4xl md:text-5xl font-bold leading-tight">
                    A Ótica que Vai Até Você com <span class="text-gold">Elegância</span>
                </h1>
                <p class="text-gray-300 text-base md:text-lg font-light leading-relaxed">
                    Esqueça o trabalho de ir a lojas físicas. Levamos consultoria óptica completa, exames e armações exclusivas diretamente à sua casa ou escritório.
                </p>
                <div class="flex flex-col sm:flex-row gap-4 pt-4">
                    <a href="#contato" class="bg-gold text-primary text-center font-semibold px-8 py-3.5 rounded-full hover:bg-champagne transition-all">
                        Agendar Visita Gratuita
                    </a>
                </div>
            </div>
            <div class="relative flex justify-center">
                <div class="w-full h-80 md:h-[400px] rounded-2xl bg-gradient-to-tr from-primary via-primary/80 to-gold/20 border border-gold/30 flex items-center justify-center relative shadow-2xl">
                    <div class="text-center p-6">
                        <span class="font-cinzel text-2xl text-gold block mb-2">Saint Vision Experiência</span>
                        <p class="text-sm text-gray-300 font-light">Seu conforto em primeiro lugar</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- COMO FUNCIONA -->
    <section id="como-funciona" class="py-20 bg-gray-50">
        <div class="max-w-7xl mx-auto px-6 text-center">
            <h2 class="font-cinzel text-3xl font-bold text-primary mb-4">Como Funciona a Ótica Móvel</h2>
            <p class="text-gray-600 max-w-2xl mx-auto mb-16 text-sm md:text-base font-light">
                Três passos simples para renovar o seu visual sem sair do conforto da sua casa.
            </p>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="bg-white p-8 rounded-2xl shadow-sm border border-gray-100 hover:border-gold/50 transition-all">
                    <div class="w-12 h-12 bg-gold/10 text-gold rounded-xl flex items-center justify-center font-cinzel text-xl font-bold mx-auto mb-6">1</div>
                    <h3 class="font-cinzel text-lg font-bold text-primary mb-3">Agende Online</h3>
                    <p class="text-gray-600 text-sm leading-relaxed">Escolha o melhor dia, horário e endereço onde deseja receber nossa visita.</p>
                </div>
                
                <div class="bg-white p-8 rounded-2xl shadow-sm border border-gray-100 hover:border-gold/50 transition-all">
                    <div class="w-12 h-12 bg-gold/10 text-gold rounded-xl flex items-center justify-center font-cinzel text-xl font-bold mx-auto mb-6">2</div>
                    <h3 class="font-cinzel text-lg font-bold text-primary mb-3">Receba o Atendimento</h3>
                    <p class="text-gray-600 text-sm leading-relaxed">Nossa equipe vai até você com maletas exclusivas, diversidade de armações e suporte.</p>
                </div>
                
                <div class="bg-white p-8 rounded-2xl shadow-sm border border-gray-100 hover:border-gold/50 transition-all">
                    <div class="w-12 h-12 bg-gold/10 text-gold rounded-xl flex items-center justify-center font-cinzel text-xl font-bold mx-auto mb-6">3</div>
                    <h3 class="font-cinzel text-lg font-bold text-primary mb-3">Aproveite sem Esforço</h3>
                    <p class="text-gray-600 text-sm leading-relaxed">Faça testes, tire medidas e receba seus óculos prontos no conforto do seu lar.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- DIFERENCIAIS -->
    <section id="diferenciais" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-6 grid grid-cols-1 md:grid-cols-2 gap-12 items-center">
            <div class="space-y-6">
                <h2 class="font-cinzel text-3xl font-bold text-primary">Por que escolher a Saint Vision?</h2>
                <p class="text-gray-600 text-sm md:text-base leading-relaxed">
                    Unimos a qualidade das grandes óticas tradicionais com a praticidade extrema do atendimento móvel personalizado.
                </p>
                <ul class="space-y-4 text-sm text-gray-700">
                    <li class="flex items-center space-x-3">
                        <span class="w-2 h-2 rounded-full bg-gold"></span>
                        <span>Atendimento com hora marcada, sem filas ou trânsito.</span>
                    </li>
                    <li class="flex items-center space-x-3">
                        <span class="w-2 h-2 rounded-full bg-gold"></span>
                        <span>Variedade de armações de alto padrão para todos os estilos.</span>
                    </li>
                    <li class="flex items-center space-x-3">
                        <span class="w-2 h-2 rounded-full bg-gold"></span>
                        <span>Consultoria de imagem e ajuste profissional no local.</span>
                    </li>
                </ul>
            </div>
            <div class="bg-primary p-8 rounded-3xl text-white space-y-6 shadow-xl border border-gold/20">
                <h3 class="font-cinzel text-xl font-bold text-gold">Agende sua Experiência</h3>
                <p class="text-xs text-gray-300">Preencha rapidamente para conversarmos via WhatsApp.</p>
                <form class="space-y-4">
                    <input type="text" placeholder="Seu Nome" class="w-full bg-white/5 border border-white/20 rounded-lg px-4 py-3 text-sm text-white placeholder-gray-400 focus:outline-none focus:border-gold">
                    <input type="tel" placeholder="Seu WhatsApp" class="w-full bg-white/5 border border-white/20 rounded-lg px-4 py-3 text-sm text-white placeholder-gray-400 focus:outline-none focus:border-gold">
                    <button type="submit" class="w-full bg-gold text-primary font-semibold py-3 rounded-lg hover:bg-champagne transition-all">
                        Solicitar Visita Agora
                    </button>
                </form>
            </div>
        </div>
    </section>

    <!-- REDES SOCIAIS -->
    <section class="py-16 bg-gray-50 border-t border-gray-100">
        <div class="max-w-4xl mx-auto px-6 text-center">
            <h3 class="font-cinzel text-2xl font-bold text-primary mb-8">Siga-nos nas Redes</h3>
            <div class="flex justify-center items-center gap-8 flex-wrap">
                <!-- Instagram -->
                <a href="https://www.instagram.com" target="_blank" rel="noopener noreferrer" class="transition-transform hover:scale-110">
                    <img src="https://i.imgur.com/yIbaMKH.png" alt="Instagram" class="w-12 h-12">
                </a>
                <!-- WhatsApp -->
                <a href="https://wa.me/" target="_blank" rel="noopener noreferrer" class="transition-transform hover:scale-110">
                    <img src="https://i.imgur.com/A7v4OMz.png" alt="WhatsApp" class="w-12 h-12">
                </a>
            </div>
        </div>
    </section>

    <!-- RODAPÉ -->
    <footer id="contato" class="bg-primary text-white border-t border-gold/20 py-12">
        <div class="max-w-7xl mx-auto px-6 flex flex-col md:flex-row justify-between items-center gap-6">
            <div class="flex flex-col text-center md:text-left">
                <span class="font-cinzel text-xl font-bold tracking-widest text-white">SAINT VISION</span>
                <span class="text-[10px] uppercase tracking-widest text-gold font-semibold">Ótica Móvel</span>
            </div>
            <p class="text-xs text-gray-400">© 2026 Saint Vision. Todos os direitos reservados.</p>
        </div>
    </footer>

</body>
</html>
**
