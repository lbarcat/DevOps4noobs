# **Multiplexadores de Terminais**

 São programas que nos permitem multiplexar um terminal em vários subprocessos ou terminais dentro de uma única sessão de terminal, isso significa que podemos ter várias sessões abertas usando uma única sessão de login para uma máquina local ou remota.

**Screen:**

Screen é um gerenciador de janelas em tela cheia que multiplexa um terminal físico entre vários processos (tipicamente shells interativos). Cada terminal virtual fornece as funções de um terminal DEC VT100 e, além disso, várias funções de controle dos padrões ISO 6429 (ECMA 48, ANSI X3.64) e ISO 2022 (por exemplo, inserir/excluir linha e suporte para vários conjuntos de caracteres). Há um buffer de histórico de rolagem para cada terminal virtual e um mecanismo de copiar e colar que permite mover regiões de texto entre as janelas.

**Tmux:**

O Tmux é um multiplexador de terminal: ele permite que vários terminais sejam criados, acessados ​​e controlados a partir de uma única tela. O Tmux pode ser desconectado de uma tela e continuar sendo executado em segundo plano e, posteriormente, reanexado.

Quando o Tmux é iniciado, ele cria uma nova sessão com uma única janela e a exibe na tela. Uma linha de status na parte inferior da tela mostra informações sobre a sessão atual e é usada para inserir comandos interativos.

[Inicio](../../README.md)