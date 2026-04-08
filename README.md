# ETAPA TÉCNICA - CIMATEC JR.

## Descrição: 
Este repositório foi criado com o intuito de organizar e preparar o envio do projeto solicitado pelo Núcleo de Projetos de Computação (NPCP) da empresa júnior do SENAI CIMATEC. Este repositório está estruturado de modo a apresentar todos os arquivos utilizados na criação do site, bem como arquvos de HTML (index.html; donate.html), CSS (style.css; donate.css), JavaScript, JSON (JavaScript Object Notation) e a pasta img, que contém as imagens utilizadas. Além disso, foram utilizados também como processo criativo e de aprendizado o FIGMA e o GitHub Copilot, que foi integrado ao VSCode.

## Informações Importantes:
• Nome Completo do Candidato: Enzo Moitinho Almeida;

• Semestre Atual: 1º Semestre;

• Tema escolhido para a landing page: Combate à Fome (Projeto Mesa Viva; da empresa Prato Cheio);

• Tecnologias utilizadas: VS Code, HTML, CSS, JavaScript e FIGMA.

• Link do projeto hospedado: https://etapa-tec-cimatec-jr-enzo.vercel.app/main_page/index.html

• Link do protótipo no Figma: https://www.figma.com/make/Zs9ZE89I2iCXZWCqu3TjjI/Projeto-Mesa-Viva---Cimatec-Jr.?t=yHApGBTz2p5TgMFd-1

## Funcionalidades e Requisitos
Para a criação do site, foram utilizadas as seguintes funcionalidades:

•GitHub Copilot CLI: a ferramenta de Pair Programming foi utilizada para auxiliar na tomada de decisões técnicas a partir das minhas instruções e lógica, bem como a automação de processos repetitivos (por exemplo, a ferramenta foi utilizada para realizar a conversão da medida de elementos em pixels para rem's, a fim de otimizar a responsividade e clamp no CSS).

• Figma: a aplicação foi utilizada para criar um protótipo do site antes de sua criação propriamente dita. Utilizei da ferramenta "Figma Make" para prototipar a página, realizando um brainstorm e organização de ideias de forma clara e visual.

•Estrutura da Landing Page: na estruturação do HTML, foram atendidos todos os requisitos obrigatórios informados no repositório contendo as informações para a criação da Landing Page, com cada seção das páginas sendo divididas por estruturas de "section" e, quando necessário, "div".

• Interatividade: para interatividade, foram criados com JavaScript e CSS:
- Menu Responsivo (Função "abrefechamenu" em index.html e especificações em style.css);
- Animação de Fade nos elementos de index.html (utilizando funções de Observer em JavaScript combinadas com especificações em style.css);
- Scroll animado entre seções utilizando "scroll-behavior: smooth" em style.css;
- Menu fixo ao rolar a página com CSS, incluindo o botão para abrir o menu responsivo com JS;
- Hover effects em pontos em algumas imagens e botões utilizando CSS;

• Responsividade: Projetada de forma prática e eficiente para telas menores utilizando "clamp()", uma vez que enxerguei como mais eficiente do que realizar uma Media Query, definindo valores mínimos, ideais e máximos para cada elemento necessário de HTML. Foi necessário utilizar Media Queries em alguns casos específicos para corrigir falhas em pontos menores.

• Hospedagem do Projeto: Após análise das opções disponíveis para a hospedagem, foi selecionado o Vercel por conta de sua operação intuitiva e prática, além de sua integração e atualização automática com o repositório do GitHub. Além disso, foi necessário criar diretrizes e direcionamentos ao Vercel através do arquivo vercel.json, dando o "redirect" necessário para a página principal do site.