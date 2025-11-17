💌 Convite de Formatura Digital
Este é um projeto de um convite de formatura digital e interativo, criado como uma página web única (single-page). O design foca em uma experiência "premium" e luxuosa, utilizando tons de preto e dourado, animações suaves e música de fundo para criar um ambiente elegante.

Criado para a formatura de Ana Luisa Silva Leão.


✨ Funcionalidades Principais
Design Premium: Tema escuro (preto e dourado) com fontes elegantes (Cormorant Garamond e Inter).

Animação de Capa: Uma tela inicial ("Herói") que desaparece para revelar o convite principal.

Partículas Animadas: Um fundo sutil com partículas douradas que sobem suavemente.

Música de Fundo: Player de música ambiente com botão de play/pause e volume pré-definido.

Contador Regressivo: Script de contagem regressiva em tempo real para a data do evento.

Animações de Scroll: Efeitos de fade-in e escala nos elementos conforme o usuário rola a página (usando Intersection Observer).

Layout Responsivo: Adaptável para visualização em desktops e dispositivos móveis.

Link para Mapa: Seção de local clicável que abre o Google Maps.

🛠️ Tecnologias Utilizadas
HTML5: Estrutura semântica do site.

Tailwind CSS (via CDN): Para estilização rápida e responsiva.

JavaScript (Vanilla JS): Para todas as interatividades, incluindo:

Controle da música

Contador regressivo

Animações de scroll

Animação de entrada

Google Fonts: Para carregar as fontes personalizadas.

🚀 Como Usar
Como este é um projeto self-contained (tudo em um único arquivo HTML), não há necessidade de instalação ou processos de build.

Clone ou baixe este repositório.

Abra o arquivo index.html (ou o nome que você deu a ele) em qualquer navegador web.

🔧 Como Personalizar
Para adaptar este convite para o seu próprio evento, você precisará editar algumas partes-chave diretamente no arquivo HTML:

Textos Principais:

Nome do Formando: Altere o nome "Ana Luisa Silva Leão" na <section id="hero"> e na <section id="intro">.

Textos de Introdução: Edite os parágrafos dentro da <section id="intro">.

Citação: Altere o texto e o autor na <section id="quote">.

Mídia:

Foto do Formando: Na <section id="intro">, substitua o link src na tag <img> pela URL da sua foto.

Música de Fundo: Na tag <audio id="bg-music">, troque o link src pelo link da sua música (.mp3).

Informações do Evento:

Data, Hora e Local: Na <section id="event">, edite os textos dentro dos divs com a classe .info-card.

Link do Mapa: Na mesma seção, altere o atributo href da tag <a> para o link do Google Maps do seu local.

Configurações do JavaScript (no final do arquivo):

Volume da Música: Altere o valor na linha bgMusic.volume = 0.1; (0.1 = 10%, 1.0 = 100%).

Data do Contador: Encontre a linha const targetDate = new Date("Nov 27, 2025 19:00:00").getTime(); e altere a string para a data e hora exatas do seu evento. O formato é "Mês Dia, Ano HH:MM:SS" (ex: "Jan 1, 2026 20:00:00").

📜 Licença
Este projeto é de uso livre. Sinta-se à vontade para usá-lo e modificá-lo para seus próprios fins.
