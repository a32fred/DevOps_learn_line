<h1 aling="center">DevOps RoadMap</h1>

![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge)

## Início: 
- `O que precisa saber` :<br/>

  explicação boa: [Click aqui](https://www.youtube.com/watch?v=IQ8-_khQATQ)<br/>
  o que faz: [Click aqui](https://www.redhat.com/pt-br/topics/devops/devops-engineer)<br/>
  explicação de Container, Docker, Kubernetes: [Click Aqui](https://www.youtube.com/watch?v=wxLvvMxzc1Q)<br/>
  
## Conceitos de Desenvolvimento
  
- `Conceitos de Desenvolvimento` : <br/>
  Como os Devs trabalham e colaboram (Agile, Jira workflows)
  
   * Agile: [O que é e para q serve!](https://www.youtube.com/watch?v=3jFhJXgURJw)
   * Jira WorkFlows: [O que é!](https://www.youtube.com/watch?v=aTjZxZX99Hw)<br/>
  
  Qual GitWorkFlow eles usam:
  
   * git flow: [Explicação](https://www.youtube.com/watch?v=oweffeS8TRc)<br/>
  
  Como as aplicação são configuradas:
  
   * Build 
   * packaging Tools<br/>
  
  Testes automatizados e escopo de teste:
  
   * Entendendo Testes de Software Automatizados: [aqui](https://www.youtube.com/watch?v=o_N1mmQnHSI)
   * Testes automatizados no React: [aqui](https://www.youtube.com/watch?v=uSp873d43_E)
   * Aprenda testes automatizados em DevOps: [aqui](https://www.youtube.com/watch?v=Zy8fJJdmQxA)<br/>
  
  Entender Como Funciona Ciclo de Vida de um Desenvolvimento 

## OS & Linux Basics

- `OS & Linux Basics` : <br/>
  Conceitos básicos de operação de sistema:
   
   * Shell commands => [curso](https://t.me/+Cex-JJeFdhNjYzhh)
   * Linux File System & Permissions => [curso 1](https://t.me/+_zefSqfIDgM0OTI5); [curso 2](https://t.me/+Faocjb1dLlNkYTdh)
   * SSH Key Management => [entender o que é](https://www.youtube.com/watch?v=GxRu35fy-oY)
   > importante ver a descrição do link do video acima
   * Virtualization => [play list de videos](https://www.youtube.com/watch?v=3VJsPxwaaG4&list=PLQ2gZvoWCA74QtyUUB2zDAKcrW9o_jzRI)<br/>
 
  Básico de NetWorking e Segurança como:
  
   * Configurar FireWalls para acesso de segurança
   * Entender o que é endereço de IP, Portas e DNS works
   * Load Balancers
   * Proxies
   * HTTP/HTTPS<br/>
   
## Conteinerização - Docker
> [Curso completo no telegram](https://t.me/+wvL3wFjw0t05ZTVh)
- `Conteinerização - Docker` : <br/>
  Você vai presisar saber:
  
   * Conceitos de Virtualização
   * Conceitos de Conteinerização
   * Como configurar conteiners em um servidor<br/>
  
  Mais algumas coisas que você deve saber:
  
   * Rodar Containers
   * Inspessionar containers ativos
   * Docker Networking
   * Persist data with Docker Volumes
   * Dockerizar aplicações usando Docker Files
   * Rodar múltiplos containers usando Docker Compose
   * Trabalhar com Docker Repository
   
## CI/CD Pipelines
> **Material de base forte:** [redirect](https://www.youtube.com/watch?v=h9K1NnqwUvE)


- `CI/CD Pipelines`: <br/>
  No DevOps, todas alteração no código, como novas
  features ou bug resolvido, precisa ser
  integrada na existente aplicação e
  implantada para o usuário final continuamente
  e de forma automatizada 

  Daí o termo:
  
   Integração Contínua e Contínua
   Implantação (CI/CD)
  
  Quando o recurso ou correção de bug estiver concluído, um
  pipeline em execução em um servidor CI (por exemplo,
  Jenkins) deve ser acionado
  automaticamente, que:
   
   * executa os testes
   * empacota o aplicativo
   * cria uma imagem de contêiner
   * envia o contêiner Image para um
   * repositório de imagens
   * implanta a nova versão em um servidor
  
  Habilidades que você precisa aprender:
   
   * Setting up the CI/CD server
   * Integrar repositório de código para acionar pipeline automaticamente
   * Ferramentas de compilação e ferramentas do gerenciador de pacotes para executar os testes e empacotar a aplicação
   * Configurar repositórios de artefatos (como Nexus) e integrar com pipeline

## Learn one Cloud Provider (exemple AWS)
> **curso no telegram do básico:** [Telegram](https://t.me/+_rWPR45H8BRhZTdh)

> **curso focado em aplicação serveless (nodejs):** [Telegram](https://t.me/+OGR8xRTVt0YzNDJh)

  - `Learn one Cloud Provider`: <br/>
  Hoje em dia muitas empresas utilizam
  infraestrutura na nuvem, em vez de
  gerenciando sua própria infraestrutura. Esses
  são Infraestrutura como Serviço (IaaS)
  plataformas, que oferecem uma gama de
  serviços adicionais, como backup, segurança,
  balanceamento de carga etc.

  Esses serviços são específicos da plataforma. Então
  você precisa aprender os serviços desse
  plataforma específica e saiba como
  gerenciar toda a implantação
  infraestrutura nele.
  
  Por exemplo. para AWS você deve saber o
  fundamentos de:
   
   * Serviço IAM - gerenciamento de usuários e
permissões
   * Serviço VPC - sua rede privada
   * cria uma imagem de contêiner
   * Serviço EC2 - servidores virtuais 
 
## ![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge)

> orquestração de container
  * Full couse for beginners: [youtube](https://www.youtube.com/watch?v=X48VuDVv0do)
> Monitoramento e obeservação

> infraestrutura como código

> Linguagem script || programção

> Controtole de versionamento - GIT
 
##

> **Note**: Material não é autoral, mas a estrutura sim. [arquivo de referência usado aqui](https://drive.google.com/file/d/1OKHOp6y8xXlpXBc6RBisimcEgLUZ6aQj/view?usp=share_link)

> **Note**: Material de apoio para aprendizado, outro roadmap. [site referido](https://roadmap.sh/devops)

- cursos completos de devops em um unico video:
  - [DevOps Tools Full Course | Ansible, Jenkins, Nagios, Chef, Puppet, Selenium tutorial | Simplilearn](https://www.youtube.com/watch?v=FyNvwI02Nhg&pp=ugMICgJlbhABGAE%3D)
  
  - [DevOps Full Course | Learn DevOps In 10 Hours | DevOps Tutorial For Beginners | DevOps | Simplilearn](https://www.youtube.com/watch?v=5KtRF4NuUWE) 
