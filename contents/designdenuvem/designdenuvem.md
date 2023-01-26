# **Design de Nuvem**

**Disponibilidade:**

Disponibilidade é a porcentagem de tempo em que um sistema está funcional e funcionando como pretendido, geralmente referido como tempo de atividade. A disponibilidade pode ser afetada por erros de hardware ou software, problemas de infraestrutura, ataques maliciosos e carga do sistema. Muitos provedores de nuvem normalmente oferecem a seus usuários um acordo de nível de serviço (SLA) que especifica as porcentagens exatas de tempo de atividade/tempo de inatividade prometido. A disponibilidade está relacionada à confiabilidade nesse sentido. 

Por exemplo, uma empresa pode prometer 99,99% de tempo de atividade para seus serviços. Para atingir altos níveis de tempo de atividade, é importante eliminar pontos únicos de falha para que uma única falha de dispositivo não interrompa todo o serviço. A alta disponibilidade na nuvem geralmente é alcançada por meio da criação de clusters. Clusters são grupos de dispositivos (como servidores) em que todos têm acesso ao mesmo armazenamento compartilhado e funcionam como um único servidor para fornecer disponibilidade ininterrupta. Dessa forma, se um servidor cair, os outros poderão retomar a carga até que ele volte a ficar online. Os clusters podem variar de dois servidores até mesmo vários edifícios de servidores.

**Gestão de dados:**

O gerenciamento de dados é o elemento-chave dos aplicativos em nuvem e influencia a maioria dos atributos de qualidade. Os dados geralmente são hospedados em locais diferentes e em vários servidores por motivos como desempenho, escalabilidade ou disponibilidade, e isso pode apresentar uma série de desafios. Por exemplo, a consistência dos dados deve ser mantida e os dados geralmente precisam ser sincronizados em diferentes locais. Além disso, os dados devem ser protegidos em repouso, em trânsito e por meio de mecanismos de acesso autorizado para manter as garantias de segurança de confidencialidade, integridade e disponibilidade. Consulte o Controle de proteção de dados de benchmark de segurança do Azure para obter mais informações.

**Design e Implementação:**

Um bom design abrange fatores como consistência e coerência no design e implantação de componentes, capacidade de manutenção para simplificar a administração e o desenvolvimento e capacidade de reutilização para permitir que componentes e subsistemas sejam usados em outros aplicativos e em outros cenários. As decisões tomadas durante a fase de design e implementação têm um grande impacto na qualidade e no custo total de propriedade de aplicativos e serviços hospedados na nuvem.

**Gerenciamento e Monitoramento:**

O gerenciamento e o monitoramento do DevOps envolvem a supervisão de todo o processo de desenvolvimento, desde o planejamento, desenvolvimento, integração e teste, implantação e operações. Envolve uma visão completa e em tempo real do status de aplicativos, serviços e infraestrutura no ambiente de produção. Recursos como streaming em tempo real, reprodução histórica e visualizações são componentes críticos do monitoramento de aplicativos e serviços.

[Inicio](../../README.md)