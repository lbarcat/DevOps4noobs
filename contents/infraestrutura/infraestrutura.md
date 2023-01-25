# **Iac - Infraestrutura como Código**

- **Terraform:**

    O Terraform é uma ferramenta extremamente popular de infraestrutura como código (IaC) de código aberto que pode ser usada com muitas APIs diferentes de nuvem e provedores de serviços. O Terraform se concentra em uma abordagem imutável para a infraestrutura, com um centro de arquivos de estado do terraform para rastrear o status de sua infraestrutura do mundo real.

    Documentação: https://developer.hashicorp.com/terraform/docs

- **AWS CDK:**

    O AWS Cloud Development Kit (AWS CDK) é uma estrutura de desenvolvimento de software de código aberto usada para provisionar recursos de infraestrutura de nuvem de maneira segura e repetível por meio do AWS CloudFormation. O AWS CDK oferece flexibilidade para escrever infraestrutura como código em linguagens populares como JavaScript, TypeScript, Python, Java, C# e Go.

    Documentação: https://docs.aws.amazon.com/cdk/index.html

- **Cloud Formation:**

    CloudFormation é o serviço da AWS que ajuda a definir coleções de recursos da AWS. O CloudFormation permite modelar, provisionar e gerenciar recursos da AWS e de terceiros tratando a infraestrutura como código.

    Documentação: https://docs.aws.amazon.com/cloudformation/index.html

- **Pulumi:**

    Pulumi é uma ferramenta de infraestrutura como código de código aberto que pode ser escrita em TypeScript, JavaScript, Python, Go, .NET, Java e YAML para modelar a infraestrutura de nuvem.

    Documentação: https://www.pulumi.com/docs/

- **Containers:**

    Docker:

    Docker é uma plataforma de software que permite criar, testar e implantar aplicativos rapidamente. O Docker empacota o software em unidades padronizadas chamadas contêineres que possuem tudo o que o software precisa para executar, incluindo bibliotecas, ferramentas do sistema, código e tempo de execução. Usando o Docker, você pode implantar e dimensionar aplicativos rapidamente em qualquer ambiente e saber que seu código será executado.

    Documentação: https://docs.docker.com/

    LXC: 

    O LXC é um runtime de contêiner Linux bem conhecido que consiste em ferramentas de linguagem e biblioteca, modelos e associações. É de baixo nível, muito flexível e abrange praticamente todos os recursos de contenção suportados pelo kernel upstream.

    Documentação: https://linuxcontainers.org/lxc/documentation/

- **Container Orchestration:**

    Kubernetes:

    O Kubernetes é uma plataforma de gerenciamento de contêineres de código aberto e o produto dominante nesse espaço. Usando o Kubernetes, as equipes podem implantar imagens em vários hosts subjacentes, definindo sua disponibilidade desejada, lógica de implantação e lógica de dimensionamento em YAML. O Kubernetes evoluiu do Borg, uma plataforma interna do Google usada para provisionar e alocar recursos de computação. (semelhante aos sistemas Autopilot e Aquaman do Microsoft Azure).

    A popularidade do Kubernetes tornou-o uma habilidade cada vez mais importante para o DevOps Engineer e desencadeou a criação de equipes de plataforma em todo o setor. Essas equipes de engenharia de plataforma geralmente existem com o único objetivo de tornar o Kubernetes acessível e utilizável para seus colegas de desenvolvimento de produtos.

    Documentação: https://kubernetes.io/docs/home/

- **Configuration Mgmt:**

    Ansible:

    Ansible é uma ferramenta de gerenciamento de configuração, implantação de aplicativos e provisionamento de código aberto que usa sua própria linguagem declarativa em YAML. Ansible é sem agente, o que significa que você só precisa de conexões remotas via SSH ou Windows Remote Management via Powershell para funcionar.

    Documentação: https://docs.ansible.com/

- **GitOps:**

    Argo CD:

    Argo CD é uma ferramenta de entrega contínua para Kubernetes baseada na metodologia GitOps. Ele é usado para automatizar a implantação e o gerenciamento de aplicativos nativos da nuvem, sincronizando continuamente o estado do aplicativo desejado com o estado real do aplicativo no ambiente de produção.

    Em um fluxo de trabalho Argo CD, as alterações no aplicativo são feitas confirmando o código ou as alterações de configuração em um repositório Git. O Argo CD monitora o repositório e implanta automaticamente as alterações no ambiente de produção usando um pipeline de entrega contínua. O pipeline é acionado por alterações no repositório Git e é responsável por criar, testar e implantar as alterações no ambiente de produção.

    O Argo CD foi projetado para ser uma maneira simples e eficiente de gerenciar aplicativos nativos da nuvem, pois permite que os desenvolvedores façam alterações no sistema usando ferramentas e processos familiares e fornece um histórico claro e auditável de todas as alterações no sistema. Geralmente é usado em conjunto com ferramentas como o Helm para automatizar a implantação e o gerenciamento de aplicativos nativos da nuvem.

- **Secret Management:**

    Vault:

    O Vault é uma ferramenta para armazenar e gerenciar segredos com segurança, como senhas, chaves de API e outras informações confidenciais. Ele é desenvolvido e mantido pela Hashicorp e está disponível como software de código aberto.

    O Vault foi projetado para ser altamente escalável e flexível, com uma ampla variedade de recursos para gerenciamento de segredos, incluindo:

    - Criptografia: o Vault usa algoritmos e protocolos de criptografia, como AES e RSA, para armazenar segredos com segurança.
    
    - Controles de acesso: o Vault oferece suporte a controles de acesso baseados em função e autenticação multifator para garantir que apenas usuários ou sistemas autorizados possam acessar segredos.

    - Rotação secreta: o Vault oferece suporte à rotação automática de segredos, permitindo que os segredos sejam alternados regularmente para reduzir o risco de acesso não autorizado.
    
    - Auditoria: o Vault fornece recursos de auditoria, permitindo que os administradores rastreiem e monitorem o acesso aos segredos.
    
    - O Vault é comumente usado em ambientes DevOps para armazenar e gerenciar segredos com segurança, e geralmente é usado em conjunto com outras ferramentas, como Kubernetes e Helm, para automatizar a implantação e o gerenciamento de aplicativos nativos da nuvem.

- **Service Mesh:**

    Istio:

    O Istio é uma plataforma de service mesh de código aberto que fornece uma maneira de controlar como os microsserviços compartilham dados uns com os outros. Ele inclui APIs que permitem que o Istio se integre a qualquer plataforma de registro, telemetria ou sistema de políticas. O Istio foi projetado para ser executado em vários ambientes: no local, hospedado na nuvem, em contêineres Kubernetes, em serviços executados em máquinas virtuais e muito mais.

    Consul:

    Consul é uma solução de malha de serviço que fornece um plano de controle completo com descoberta de serviço, configuração e funcionalidade de segmentação. Cada um desses recursos pode ser usado individualmente conforme necessário ou podem ser usados juntos para criar uma malha de serviço completa. O Consul requer um plano de dados e oferece suporte a um modelo de integração proxy e nativo. O Consul é fornecido com um proxy integrado simples para que tudo funcione imediatamente, mas também oferece suporte a integrações de proxy de terceiros, como o Envoy.

    [Inicio](../../README.md)