

https://github.com/user-attachments/assets/8c5b0440-01b9-448f-a545-ecfbe000a950

# ⚽ Simulador Tático Dinâmico: Rastreamento de Dados de Jogo (22 Jogadores + Bola)

Este projeto apresenta o desenvolvimento de um simulador tático interativo de futebol capaz de reproduzir frame a frame as coordenadas espaciais (X, Y) de 22 jogadores e da bola. O foco principal é demonstrar como dados estruturados de rastreamento (tracking data) podem ser transformados em visualizações dinâmicas de alto valor para comissões técnicas e analistas de desempenho.

---

## 🚀 Sobre Mim & Transição de Carreira

Com uma trajetória consolidada de 16 anos de experiência profissional em análise, estou atualmente em transição de carreira, direcionando meu foco para o ecossistema de Análise de Dados. 

Este projeto faz parte do meu aprendizado prático e do meu portfólio em desenvolvimento. Ele une a minha bagagem analítica prévia à capacidade técnica de manipular grandes matrizes de dados, aplicar lógica matemática para geometria de campo e construir visualizações interativas em Python.

---

## 🛠️ Tecnologias, Ferramentas e Bibliotecas Utilizadas

O ambiente de desenvolvimento utilizado foi o Google Colab, permitindo a criação de um pipeline em nuvem de fácil reprodução.

* Python (Core): Utilizado para estruturar a lógica de iteração dos frames e construção das funções.
* NumPy: Manipulação avançada de matrizes multidimensionais para gerenciar as coordenadas dos 22 jogadores e da bola simultaneamente ao longo do tempo.
* mplsoccer: Biblioteca padrão-ouro de visualização de dados esportivos, utilizada para renderizar o campo de futebol nos padrões exatos da StatsBomb (120x80 metros).
* Matplotlib (FuncAnimation): Engine responsável por calcular a interpolação dos pontos frame a frame, gerando a dinâmica de movimento.
* FFmpeg: Ferramenta de codificação utilizada para compilar os gráficos renderizados e exportar a animação diretamente no formato físico `.mp4`.

---

## 🧠 Análise Tática do Lance

O modelo reproduz uma Transição Ofensiva Apoiada estruturada no sistema tático 4-3-3 (Time Azul) contra um bloco médio defensivo estruturado em 4-4-2 (Time Vermelho).



### Comportamentos Críticos Detectados pelo Modelo:

1. A Atração do Bloco (Frames 0 a 2): O portador da bola (Meia Azul) retém a posse no corredor central intermediário, forçando o balanço da linha de meio-campo do Time Vermelho e criando um espaço livre nas costas dos volantes adversários.
2. A Janela de Ruptura (Frames 3 a 5): O Atacante Azul inicia o movimento de desmarcação em diagonal "dentro para fora" atacando o ponto cego do zagueiro central e do lateral-esquerdo vermelho. A bola é lançada no Frame 3, quebrando a última linha de oposição.
3. Tomada de Decisão do Goleiro (Frames 6 a 7): A velocidade do passe obriga o goleiro adversário a quebrar sua base e sair da meta para tentar o abafamento (Prostíbase Tardia), resultando em uma clara oportunidade de finalização na área penal.

Marco Aurélio Moreira 
URL: www.linkedin.com/in/marco-aurélio-moreira
