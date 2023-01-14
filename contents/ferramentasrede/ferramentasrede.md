# **Ferramentas de Rede**

**Traceroute:**

O comando traceroute é um comando no Linux que imprime a rota que um pacote de rede segue de sua origem (por exemplo, seu computador) até o host de destino (por exemplo, roadmap.sh). É bastante valioso na investigação de conexões de rede lentas, pois pode nos ajudar a identificar a parte lenta da jornada do pacote de rede pela Internet.

**MTR:**

O mtr combina a funcionalidade dos programas traceroute e ping em uma única ferramenta de diagnóstico de rede.

Quando o mtr inicia, ele investiga a conexão de rede entre o host em que o mtr é executado e o HOSTNAME enviando pacotes com TTLs propositadamente baixos. Ele continua enviando pacotes com baixo TTL, observando o tempo de resposta dos roteadores intervenientes. Isso permite que o mtr imprima a porcentagem de resposta da rota da Internet e os tempos de resposta para HOSTNAME. Uma perda repentina de pacotes ou aumento do tempo de resposta geralmente indica um link ruim (ou simplesmente sobrecarregado).

**Ping:**

O comando ping (Packet Internet Groper) é usado para verificar a conectividade de rede entre o host e o servidor/host. Este comando toma como entrada o endereço IP ou a URL e envia um pacote de dados para o endereço especificado com a mensagem “PING” e obtém uma resposta do servidor/host neste momento é registrado o que é chamado de latência.

**NMAP:**

NMAP significa Network Mapper e é uma ferramenta de código aberto usada para explorar e auditar a segurança da rede, como verificar firewalls e escanear portas.

**Netstat:**

Netstat é um utilitário de linha de comando para exibir todas as conexões de rede em um sistema. Ele exibe todas as conexões de soquete tcp, udp e unix. Além dos soquetes conectados, ele também exibe os soquetes de escuta que estão aguardando conexões de entrada.

**UFW:**

UFW, ou firewall descomplicado, é um utilitário baseado em linha de comando para gerenciar regras de firewall no Arch Linux, Debian e Ubuntu. Seu objetivo é tornar a configuração do firewall o mais simples possível. É um frontend para a ferramenta de firewall iptables.

**Tcpdump:**

Tcpdump é uma ferramenta de linha de comando usada para analisar o tráfego de rede que passa pelo seu sistema. Ele pode ser usado para capturar e filtrar pacotes e exibi-los em um formato legível por humanos. As informações capturadas também podem ser analisadas posteriormente.

**Iptables:**

IPtables é um utilitário de firewall de linha de comando que usa cadeias de políticas para permitir ou bloquear o tráfego que será aplicado pela estrutura netfilter do kernel Linux. O mecanismo de filtragem de pacotes do Iptables é organizado em três tipos diferentes de estruturas: tabelas, cadeias e alvos.

**Dig:**

O comando Dig significa Domain Information Groper. Ele é usado para recuperar informações sobre servidores de nomes DNS. Ele é usado principalmente por administradores de rede para verificar e solucionar problemas de DNS e para realizar pesquisas de DNS. Ele substitui ferramentas mais antigas, como nslookup e host.

**SCP:**

SCP é um acrônimo para Secure Copy Protocol. É um utilitário de linha de comando que permite ao usuário copiar com segurança arquivos e diretórios entre dois locais, geralmente entre sistemas unix ou linux. O protocolo garante que a transmissão de arquivos seja criptografada para evitar que alguém com intenções suspeitas de obter informações confidenciais. O SCP usa criptografia em uma conexão SSH (Secure Shell), isso garante que os dados sendo transferidos sejam protegidos contra ataques suspeitos.

 [Inicio](../../README.md)