# **Ferramentas de Manipulação de Texto**

**Awk**

Awk é uma linguagem de script de propósito geral usada para manipular dados ou texto e gerar relatórios no mundo Linux. É usado principalmente para digitalização e processamento de padrões. Ele pesquisa um ou mais arquivos para ver se eles contêm linhas que correspondem aos padrões especificados e, em seguida, executa as ações associadas.

Possui a seguinte sintaxe:

awk options 'selection_criteria {action}' input-file > output-file e.g. $ awk '{print}' file.txt

**Sed**

O comando sed(Stream Editor) no UNIX pode executar muitas funções no arquivo, como pesquisar, localizar e substituir, inserir ou excluir. Ao usar o SED, você pode editar arquivos mesmo sem abri-los em editores como o VI Editor.

Possui a seguinte sintaxe:

$ sed [options].. [script] [input-file] e.g. $ sed 's/search-regex/replacement-txt/g' file.txt

**Grep**

O comando grep (pesquisa global por expressão regular e impressão) pesquisa arquivo(s) para um determinado padrão de caracteres e exibe todas as linhas que contêm esse padrão. Pode ser usado com outros comandos como ps tornando-o mais útil.

Possui a seguinte sintaxe:

$ grep [options] pattern [files] e.g. $ grep "search-regex" file-1.txt

**Sort**

O comando sort é usado para classificar o conteúdo de um arquivo em uma ordem específica. Por padrão, ele classifica um arquivo assumindo que o conteúdo está em ASCII. Mas também pode ser usado para classificar numericamente usando opções apropriadas.

Tem a seguinte sintaxe:

$ sort [options].. input-file e.g. $ sort file.txt

**Cut**

O utilitário cut corta partes selecionadas de cada linha (conforme especificado pela lista) de cada arquivo e as grava na saída padrão.

**Uniq**

O utilitário uniq lê o input_file especificado comparando linhas adjacentes e grava uma cópia de cada linha de entrada exclusiva no output_file.

**Cat**

O comando cat (concatenar) é muito usado no Linux. Ele lê os dados do arquivo e fornece seu conteúdo como saída. Ele nos ajuda a criar, visualizar e concatenar arquivos.

Possui a seguinte sintaxe:

View : $ cat [option] [input-file]

Create : $ cat [content] > [new-file]

Append : $ cat [append_content] >> [existing-file]
e.g. $ cat file.txt

**Echo**

Echo é um comando embutido no Linux usado para exibir linhas de texto/string que são passadas como um argumento. É usado principalmente em scripts de shell e arquivos em lote para enviar texto de status ou variáveis ​​ENV para a tela ou um arquivo.

Possui a seguinte sintaxe:

$ echo [options] [string] e.g. $ echo "Hello World!"

**Fmt**

O comando fmt serve para formatar e otimizar o conteúdo em arquivos de texto. Será realmente útil quando se trata de embelezar arquivos de texto grandes, definindo largura e espaços de coluna uniformes.

Possui a seguinte sintaxe:

$ fmt [-width] [option] [file] e.g. $ fmt file.txt

**Tr**

O utilitário tr copia a entrada padrão para a saída padrão com substituição ou exclusão de caracteres selecionados.

**Nl**

O utilitário nl lê linhas do arquivo nomeado ou da entrada padrão se o argumento do arquivo for omitido, aplica uma operação de filtro de numeração de linha configurável e grava o resultado na saída padrão.

**Wc**

O utilitário wc exibe o número de linhas, palavras e bytes contidos em cada arquivo de entrada ou entrada padrão (se nenhum arquivo for especificado) para a saída padrão.


# **Outros** 

**Strace**

Strace é uma ferramenta útil de diagnóstico e depuração para sistemas operacionais baseados em unix. Ele rastreia as chamadas do sistema e sinaliza que um processo usa durante seu tempo de vida. E geralmente retorna o nome de cada chamada do sistema, seus argumentos e o que retornou.

**DTrace**

O DTrace é uma estrutura abrangente de rastreamento dinâmico portada do Solaris. O DTrace fornece uma infra-estrutura poderosa que permite aos administradores, desenvolvedores e pessoal de serviço responder de forma concisa a perguntas arbitrárias sobre o comportamento do sistema operacional e dos programas do usuário.

**SystemTap**

SystemTap é uma linguagem de script e uma ferramenta para instrumentar dinamicamente sistemas operacionais baseados em Linux de produção em execução. Os administradores do sistema podem usar o SystemTap para extrair, filtrar e resumir dados para permitir o diagnóstico de desempenho complexo ou problemas funcionais.

**Uname**

Uname é uma forma abreviada do nome Unix e ajuda a imprimir as informações do sistema para hardware e software no sistema atual em execução.

**Df**

Df é um comando padrão do Unix usado para exibir a quantidade de espaço em disco disponível para sistemas de arquivos nos quais o usuário chamador tem acesso de leitura apropriado. df normalmente é implementado usando as chamadas de sistema statfs ou statvfs.

**History**

O comando history é usado para visualizar o comando executado anteriormente. Cada comando executado é tratado como o evento e está associado a um número de evento com o qual eles podem ser recuperados e alterados, se necessário. Esses comandos são salvos em um arquivo de histórico.

Possui a seguinte sintaxe:

- $ history

**Du**

O utilitário du, abreviação de uso do disco, exibe o uso do bloco do sistema de arquivos para cada argumento de arquivo e para cada diretório na hierarquia de arquivos com raiz em cada argumento de diretório. Se nenhum arquivo for especificado, o uso do bloco da hierarquia enraizada no diretório atual será exibido.

[Inicio](../../README.md)