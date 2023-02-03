# **DevSecOPs**

<img src="https://marvel-b1-cdn.bc0a.com/f00000000236551/dt-cdn.net/images/devsecops-image-2000-6557ba1b00.png" title="jira software" width="300" /></a>


A cultura DevSecOps busca introduzir os conceitos de segurança durante todo o ciclo de desenvolvimento de software e não deixando-o após a finalização do desenvolvimento tal como nos modelos clássicos como o Cascata *(Watterfall)*.

A preocupação com segurança deve vir desde o começo do desenvolvimento, ainda na etapa de projeto, incluindo conceitos como segurança desde os desenhos de arquitetura, considerando assim a segurança por design *(security by design)*.

Sobre esse tema, vamos conhecer um pouco mais afundo alguns conceitos, referências e ferramentas que são comuns nesse meio.

- **Vulnerabilidade e Ameaças**

Antes de falarmos de ferramentas que buscam por vulnerabilidades, precisamos primeiro definir o que é uma vulnerabilidade. **Vulnerabilidades** são condições ou falhas que, quando exploradas por um invasor, pode originar violações na segurança do seu sistema. **Ameaças** por sua vez são qualquer tipo de coisa que possa aproveitar de uma vulnerabilidade para causar dano ao sistema ou a um ativo.

- **Segurança desde o desenvolvimento**

No mercado existem diversas ferramentas para análise de código afim de buscar vulnerabilidades, todavia nenhuma delas é melhor do que um bom engenheiro que conhece as principais falhas e busca sempre utilizar do **desenvolvimento seguro** nos seus projetos. Uma boa fonte de conhecimento para tal é o [OWASP Top 10](https://owasp.org/www-project-top-ten/). OWASP é uma fundação voltada para a melhora da segurança nos softwares e anualmente ela libera um relatório com os 10 tipos de ataques mais frequentes naquele ano. Portanto, esse é um material que todo programador deveria ler antes de se preocupar com ferramentas de análise de código.

- **SAST**

Entrando no mundo das ferramentas para análise de código, podemos dividir as análises em três tipos:  SAST, DAST e IAST. SAST *(Static Application Security Testing)* refere-se a exames do seu código de forma estática, ou seja, apenas olhando o código da forma que está, sem alterá-lo ou tentar burlá-lo, a ferramenta é capaz de verificar se há falta de sanitizações, que são possíveis entradas no seu software para código malicioso, más práticas de segurança e análise da composição das bibliotecas utilizadas no teu programa *(conhecido como análise de SCA - software component analysis)* verificando se alguma delas não possui vulnerabilidades.

Alguns exemplos desse tipo de ferramenta são: Sonarqube, Fortify.

- **DAST**

Diferente da SAST, a DAST *(Dynamic Application Security Testing)* trata-se de análises dinâmicas do seu código, ou seja, com ele em um ambiente controlado, durante execução, busca-se criar um ambiente em que se possa tentar violar o software de diversas formas, aqui também entram os famosos **Pentests**. Pentests, ou testes de penetração, são formas na qual geralmente um terceiro (seja um analista ou outro software) busca ativamente falhas na segurança do seu software visando encontrar as vulnerabilidades presentes e mapeá-las para que possa ser entregue esses achados na forma geralmente de um relatório.

Exemplo de ferramenta DAST: Detectify

- **IAST**

IAST *(Interactive Application Security Testing)* nada mais é que uma combinação entre as duas técnicas de SAST e DAST, os fabricantes ao perceberem que as duas técnicas eram complementares, combinaram-nas criando assim a IAST.

Exemplo de ferramenta: Veracode

- **Quality Gate**

Ao se ter configurado em sua pipeline de CI/CD *thresholds* como porcentagem de cobertura de testes unitários e automatizados da aplicação, somado aos resultados das análises de SAST ou DAST, tem-se uma imagem geral do estado da segurança e qualidade do software. Assim, pode-se estabelecer uma métrica de atingimento mínimo para que o app, ainda durante a etapa de CI, possa ser transformado em artefato e seguir para a etapa de *Continuos Delivery*. Essa é uma excelente prática e geralmente padrão de desenvolvimento para grandes corporações.



[Inicio](../../README.md)
