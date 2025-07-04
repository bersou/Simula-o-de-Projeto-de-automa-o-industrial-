⚙️ Simulação de Projeto de Automação Industrial
Uma demonstração interativa que integra a visão do Chão de Fábrica (Supervisório), da Gerência (Dashboard) e dos Bastidores Técnicos (CLP e Banco de Dados) em uma única página web.
🎯 Visão Geral
Este projeto é uma simulação educacional criada para demonstrar o fluxo completo de dados em um ambiente de automação industrial moderno. Ele materializa, de forma interativa, os três pilares de um sistema de monitoramento:
 * CPU/CLP: O cérebro da operação, simulado em JavaScript, que controla o estado da máquina.
 * Sistema Supervisório: A interface do operador para comandar a máquina (ligar/desligar) e visualizar dados em tempo real.
 * Dashboard Gerencial: A visão estratégica para o gestor, com indicadores de performance (KPIs) e gráficos históricos para tomada de decisão.
Tudo isso é consolidado em um único arquivo HTML, totalmente autossuficiente e portátil.
✨ Funcionalidades Principais
 * Navegação por Abas: Alterne facilmente entre as três personas do projeto: Operador, Gerente e Engenheiro.
 * Controle Interativo: Ligue, desligue e resete a máquina simulada através da interface do supervisório.
 * Visualização em Tempo Real: Observe os valores de temperatura, pressão e vibração mudarem dinamicamente de acordo com o estado da máquina.
 * Simulação de Falha: Veja o sistema entrar em modo de falha automaticamente quando a temperatura excede o limite pré-configurado.
 * Dashboard com Gráficos: Acompanhe o histórico de temperatura em um gráfico de linha e veja os principais KPIs de produção e tempo de atividade.
 * Visão dos Bastidores: Entenda como as "tags" do CLP (em formato JSON) e os registros do banco de dados (em uma tabela de log) são atualizados a cada segundo.
🚀 Tecnologias Utilizadas
Este projeto foi construído utilizando tecnologias web padrões e de código aberto, sem a necessidade de qualquer instalação ou configuração de backend.
 * HTML5: Estrutura semântica do conteúdo.
 * Tailwind CSS: Framework CSS para uma estilização rápida, moderna e responsiva.
 * JavaScript (ES6+): O motor da simulação, responsável por toda a lógica de controle, atualização de dados e interatividade.
 * Chart.js: Biblioteca para a criação dos gráficos dinâmicos e elegantes no dashboard.
 * Font Awesome: Biblioteca de ícones para uma interface mais intuitiva.
💻 Como Executar o Projeto
Existem duas maneiras simples de executar esta simulação:
1. Via GitHub Pages (Recomendado)
O projeto está hospedado e pode ser acessado diretamente pelo link:https://bersou.github.io/Simula-o-de-Projeto-de-automa-o-industrial-/)
2. Localmente
Basta baixar o arquivo index.html deste repositório e abri-lo em qualquer navegador web moderno (Google Chrome, Firefox, Microsoft Edge, etc.). Nenhuma dependência externa precisa ser instalada.
# Clone este repositório (opcional)
git clone https://github.com/seu-usuario/seu-repositorio.git

# Navegue até a pasta e abra o arquivo
cd seu-repositorio
# Abra o arquivo index.html no seu navegador

📄 Licença
Este projeto é distribuído sob a licença MIT. Veja o arquivo LICENSE para mais detalhes. Sinta-se à vontade para usar, modificar e distribuir este código para fins educacionais ou como base para seus próprios projetos.
