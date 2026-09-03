<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Link na Bio / Página de Vendas</title>

  <!-- Tailwind CSS via CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            brandOrange: '#E77538',  /* Laranja topo */
            brandPink: '#F5D6EA',    /* Rosa suave */
            brandCream: '#FAF6EE',   /* Creme / Off-white */
            brandBurnt: '#C85A1B',   /* Terracota / Laranja escuro */
          }
        }
      }
    }
  </script>

  <!-- Ícones do FontAwesome -->
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet">
</head>
<body class="bg-brandCream text-gray-800 font-sans min-h-screen flex flex-col justify-between">

  <!-- CABEÇALHO / PERFIL -->
  <header class="w-full max-w-md mx-auto pt-10 px-4 text-center">
    <div class="relative w-28 h-28 mx-auto mb-4">
      <!-- Substitua a URL da imagem pela sua foto -->
      <img src="https://via.placeholder.com/150" alt="Sua Foto" class="w-full h-full rounded-full object-cover border-4 border-brandOrange shadow-md">
    </div>
    <h1 class="text-2xl font-bold text-gray-900">Seu Nome Aqui</h1>
    <p class="text-sm font-semibold text-brandBurnt mt-1">Sua Profissão ou Nicho</p>
    <p class="text-xs text-gray-600 mt-2 px-4 leading-relaxed">
      Ajudo pessoas e marcas a transformarem sua presença digital com estratégia e elegância.
    </p>
  </header>

  <!-- LINKS PRINCIPAIS (BOTÕES estilo Gleisy.cc) -->
  <main class="w-full max-w-md mx-auto px-4 py-6 space-y-4">

    <!-- Botão Destaque 1 (WhatsApp) -->
    <a href="https://wa.me/5500000000000" target="_blank" class="flex items-center justify-between w-full p-4 bg-white border border-brandPink rounded-2xl shadow-sm hover:shadow-md hover:border-brandOrange transition-all group">
      <div class="flex items-center space-x-3">
        <div class="w-10 h-10 rounded-xl bg-brandPink/50 flex items-center justify-center text-brandBurnt group-hover:bg-brandOrange group-hover:text-white transition-colors">
          <i class="fab fa-whatsapp text-xl"></i>
        </div>
        <span class="font-semibold text-gray-800">Falar Comigo no WhatsApp</span>
      </div>
      <i class="fas fa-chevron-right text-gray-400 group-hover:text-brandOrange text-sm transition-colors"></i>
    </a>

    <!-- Botão Chamada Principal (Cor Laranja Principal) -->
    <a href="#" class="flex items-center justify-between w-full p-4 bg-brandOrange text-white rounded-2xl shadow-md hover:bg-brandBurnt transition-all group">
      <div class="flex items-center space-x-3">
        <div class="w-10 h-10 rounded-xl bg-white/20 flex items-center justify-center text-white">
          <i class="fas fa-star text-lg"></i>
        </div>
        <span class="font-semibold">Agendar Serviço / Mentoria</span>
      </div>
      <i class="fas fa-chevron-right text-white/80 text-sm"></i>
    </a>

    <!-- Botão Destaque 2 (Site/Portfólio) -->
    <a href="#" class="flex items-center justify-between w-full p-4 bg-white border border-brandPink rounded-2xl shadow-sm hover:shadow-md hover:border-brandOrange transition-all group">
      <div class="flex items-center space-x-3">
        <div class="w-10 h-10 rounded-xl bg-brandPink/50 flex items-center justify-center text-brandBurnt group-hover:bg-brandOrange group-hover:text-white transition-colors">
          <i class="fas fa-globe text-lg"></i>
        </div>
        <span class="font-semibold text-gray-800">Conhecer meu Portfólio</span>
      </div>
      <i class="fas fa-chevron-right text-gray-400 group-hover:text-brandOrange text-sm transition-colors"></i>
    </a>

    <!-- BLOCO DESTAQUE / SOBRE (Usando tom Rosa Suave) -->
    <div class="bg-brandPink/40 p-5 rounded-2xl border border-brandPink/60 text-center mt-6">
      <h2 class="font-bold text-brandBurnt text-base mb-2">Sobre os Meus Serviços</h2>
      <p class="text-xs text-gray-700 leading-relaxed">
        Adicione aqui um breve parágrafo detalhando seus produtos, cursos ou serviços prestados para reforçar sua autoridade.
      </p>
    </div>

  </main>

  <!-- RODAPÉ & REDES SOCIAIS -->
  <footer class="w-full max-w-md mx-auto py-8 text-center">
    <div class="flex justify-center space-x-6 mb-4">
      <a href="#" class="text-brandBurnt hover:text-brandOrange text-xl transition-colors"><i class="fab fa-instagram"></i></a>
      <a href="#" class="text-brandBurnt hover:text-brandOrange text-xl transition-colors"><i class="fab fa-youtube"></i></a>
      <a href="#" class="text-brandBurnt hover:text-brandOrange text-xl transition-colors"><i class="fab fa-linkedin"></i></a>
    </div>
    <p class="text-xs text-gray-500">&copy; 2026 Seu Nome. Todos os direitos reservados.</p>
  </footer>

</body>
</html>
