Guia de Estudo AI
Este projeto consiste em um Progressive Web App (PWA) para desktop que funciona como um guia de estudo interativo com um chatbot AI e um quadro branco, além de um código inicial para um aplicativo de chat em Flutter.

Funcionalidades
PWA Guia de Estudo
Chat AI: Interaja com um chatbot (alimentado pela API Gemini) para aprender sobre diversos tópicos.

Acompanhamento de Tópicos: Os chats são organizados por tópicos, com títulos gerados automaticamente pela IA com base na conversa.

Progresso de Fundamentos: A IA avalia o conhecimento do usuário durante o chat e atualiza o progresso em fundamentos essenciais para cada tópico.

Quadro Branco Interativo: Um quadro branco integrado permite adicionar post-its (com texto editável), desenhar com pincel e borracha, e navegar entre múltiplos quadros.

Ferramentas de Quadro Branco: Inclui ferramentas para adicionar post-its, usar lápis, lixeira, pincel (com seleção de cor e tamanho), borracha (com seleção de tamanho), desfazer e refazer ações, e navegar entre quadros brancos.

Pesquisa dinâmica: Capaz de pesquisar entre chats com palavras chave usadas no titulo, ou na conversa

Design Responsivo: A interface se adapta a diferentes tamanhos de tela (embora otimizada para desktop).


Tecnologias Utilizadas
PWA Guia de Estudo
 

Programação inteiramente feita pelo Gemini 2.5 flash

HTML5

CSS3 (com Tailwind CSS para estilização)

JavaScript

Google Gemini API (para chat, geração de fundamentos e avaliação de conhecimento)

Phosphor Icons (para ícones)


Configuração e Instalação
PWA Guia de Estudo
Baixe ou Clone o Código: Obtenha os arquivos HTML, CSS e JavaScript do projeto.

Obtenha uma Chave de API Gemini: Você precisará de uma chave da API do Google Gemini. Siga as instruções na documentação oficial do Google AI Studio (https://aistudio.google.com/) para obter sua chave.

Insira sua Chave de API: Abra o arquivo HTML (Untitled-1.html ou o nome que você salvou) em um editor de texto. Encontre a linha const GEMINI_API_KEY = 'YOUR_API_KEY'; e substitua 'YOUR_API_KEY' pela sua chave de API real.

Execute o Arquivo HTML: Abra o arquivo HTML em qualquer navegador web moderno. 

Como Usar (PWA)
Guia de Estudo: A tela inicial mostra o quadro branco e as conversas recentes

Criar Novo Tópico: Use a primeira barra de pesquisa ("O que você quer aprender hoje ?") para digitar um novo tópico. Pressione Enter para criar um novo chat sobre esse assunto e navegar para a tela de chat.

Chats Recentes: A seção "Temas de Conversa" exibe cartões para cada tópico iniciado, com um score indicando seu progresso geral. Clique em um cartão para continuar a conversa.

Tela de Chat: Converse com a IA na área de mensagens. A barra lateral "Fundamentos" mostrará os sub-tópicos essenciais e seu progresso neles.

Quadro Branco: Use as ferramentas na seção "Lembretes" para adicionar post-its, desenhar e organizar suas anotações.

Próximos Passos / Melhorias Futuras
Adicionar persistência de dados para tópicos, mensagens e estado do quadro branco (salvar/carregar localmente ou em nuvem).

Expandir as funcionalidades do quadro branco (mais ferramentas, cores, formas, etc.).

Refinar a lógica de avaliação de conhecimento da IA para ser mais precisa e adaptável.

Adicionar funcionalidade de anexar arquivos no chat.

