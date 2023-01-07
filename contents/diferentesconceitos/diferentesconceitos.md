# **Conceitos de Sistema Operacional**

Um sistema operacional é um programa que gerencia os recursos de um computador, especialmente a alocação desses recursos entre outros programas. Os recursos típicos incluem a unidade central de processamento (CPU), memória do computador, armazenamento de arquivos, dispositivos de entrada/saída (E/S) e conexões de rede.

## **Rede**

Rede de computadores refere-se a dispositivos de computação interconectados que podem trocar dados e compartilhar recursos uns com os outros. Esses dispositivos em rede usam um sistema de regras, chamado protocolos de comunicação, para transmitir informações por meio de tecnologias físicas ou sem fio.

Comece estudando o Modelo OSI. Este modelo ajudará na construção de uma compreensão dos tópicos vinculados e ajudará você a contextualizar os itens vinculados ao nó Rede, Segurança e Protocolos. Os conceitos de rede de nível superior podem ser implementados e nomeados de forma diferente entre os provedores de nuvem. Não deixe que isso o confunda - os fundamentos do TCP/IP são úteis e usados da mesma forma em todas as implementações.

## **POSIX**

POSIX (Portable Operating System Interface) é uma família de padrões para manter a compatibilidade entre sistemas operacionais. Ele descreve utilitários, APIs e serviços que um sistema operacional compatível deve fornecer ao software, facilitando assim a portabilidade de programas de um sistema para outro.

Um exemplo prático: em um sistema operacional do tipo Unix, existem três fluxos padrão, stdin, stdout e stderr - são conexões de E/S que você provavelmente encontrará ao usar um terminal, pois gerenciam o fluxo da entrada padrão (stdin), saída padrão (stdout) e erro padrão (stderr).

Então, nesse caso, quando queremos interagir com qualquer um desses streams (através de um processo, por exemplo), a API do sistema operacional POSIX facilita - por exemplo, no cabeçalho C <unistd.h> onde o stdin, stderr e stdout são definidos como STDIN_FILENO, STDERR_FILENO e STDOUT_FILENO.

O POSIX também adiciona um padrão para códigos de saída, semântica de sistema de arquivos e várias outras convenções de API de utilitário de linha de comando.

## **Sockets**

Socket é um ponto final de um link de comunicação bidirecional entre dois processos diferentes na rede (máquinas iguais ou diferentes). O mecanismo de soquete fornece um meio de comunicação entre processos (IPC) estabelecendo pontos de contato nomeados entre o cliente e o servidor. É a combinação do endereço IP e do número da porta.

## **Processos**

Um processo significa um programa em execução. Geralmente, ele recebe uma entrada, processa-a e nos fornece a saída apropriada. O comando ps pode ser usado no Linux para obter a lista de processos em execução em primeiro plano. Cada processo terá um identificador exclusivo chamado PID, que pode ser usado para rastreá-lo ou eliminá-lo por meio do shell.

Tipos de processos:

Processos de primeiro plano

Processos em segundo plano

## **Gerenciamento de E/S**

Uma das tarefas importantes de um sistema operacional é gerenciar vários dispositivos de E/S, incluindo mouse, teclados, touchpad, unidades de disco, adaptadores de vídeo, dispositivos USB, telas mapeadas de bits, LED, conversor analógico-digital, liga/desliga switch, conexões de rede, E/S de áudio, impressoras, etc.

## **Virtualização**

A virtualização é a criação de uma versão virtual - em vez de real - de algo, como um sistema operacional (SO), um servidor, um dispositivo de armazenamento ou recursos de rede. Ele usa um software que simula a funcionalidade do hardware para criar um sistema virtual. Essa prática permite que as organizações de TI operem vários sistemas operacionais, mais de um sistema virtual e vários aplicativos em um único servidor.

## **Gerenciamento de memória**

O termo Memória pode ser definido como uma coleção de dados em um formato específico. É usado para armazenar instruções e processar dados. A memória compreende uma grande matriz ou grupo de palavras ou bytes, cada um com sua própria localização. O motivo principal de um sistema de computador é executar programas. Esses programas, juntamente com as informações que acessam, devem estar na memória principal durante a execução. A CPU busca instruções na memória de acordo com o valor do contador de programa.

Para atingir um grau de multiprogramação e utilização adequada da memória, o gerenciamento de memória é importante. Existem vários métodos de gerenciamento de memória, refletindo várias abordagens, e a eficácia de cada algoritmo depende da situação.

## **Sistema de arquivo**

Um arquivo é uma coleção nomeada de informações relacionadas gravadas em armazenamento secundário, como discos magnéticos, fitas magnéticas e discos ópticos. Geralmente, um arquivo é uma sequência de bits, bytes, linhas ou registros cujo significado é definido pelo criador e usuário do arquivo.

## **Gerenciamento de inicialização (init.d)**

init.d é um daemon que é o primeiro processo (PID = 1) do sistema Linux. Em seguida, outros processos, serviços, daemons e threads são iniciados pelo init. Pode-se escrever seus próprios scripts na localização '/etc/init.d' para iniciar os serviços automaticamente na inicialização do sistema. Os serviços podem ser iniciados e interrompidos manualmente usando o comando service.

Possui a seguinte sintaxe: $ service [service_name] [action] e.g. $ serviço ssh start

## **Gerenciamento de serviços (systemd)**

systemd é um daemon de gerenciamento do sistema que substitui o processo sysvinit para se tornar o primeiro processo com PID = 1, que é executado no espaço do usuário durante o processo de inicialização do Linux. É um sistema projetado especificamente para o kernel do Linux. Ele agora está sendo usado como um substituto do init.d para superar as deficiências dele. Ele usa o comando systemctl para executar operações relacionadas.

por exemplo. $ systemctl start [nome do serviço], $ systemctl poweroff

## **Thread** 

Thread é uma entidade ativa que executa uma parte de um processo. É um fluxo sequencial de tarefas dentro de um processo. Também é chamado de processo leve, pois compartilham recursos comuns. Um processo pode conter vários threads. Threads são usados para aumentar o desempenho dos aplicativos. Cada thread tem seu próprio contador de programa, pilha e conjunto de registradores. Mas os threads de um único processo podem compartilhar o mesmo código e dados/arquivo.

Principais terminologias:

- proc
- fork
- join

## **Simultaneidade no sistema operacional**

Simultaneidade é a execução de várias sequências de instruções ao mesmo tempo. Isso acontece no sistema operacional quando há vários threads de processo em execução em paralelo. Ele ajuda em técnicas como coordenar a execução de processos, alocação de memória e agendamento de execução para maximizar a taxa de transferência.

Os threads do processo em execução sempre se comunicam entre si por meio de memória compartilhada ou passagem de mensagens. Os resultados da simultaneidade no compartilhamento de recursos resultam em problemas como impasses e escassez de recursos.

Principais terminologias:

- mutex
- critical section
- Deadlock

 [Inicio](../../README.md)