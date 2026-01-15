# **postech-group-fiap-188**
A **postech-group-fiap-188** é formada por alunos da Pós-graduação em Arquitetura de Software da FIAP. Trabalhamos juntos nos projetos ao longo da pós em Software Architecture - FIAP, sempre seguindo boas práticas de arquitetura, testes e versionamento de código. Nosso objetivo é criar soluções eficientes, escaláveis e bem documentadas.

## Projetos
Atualmente, nossos repositórios são privados e exclusivos para os integrantes do grupo, garantindo um ambiente seguro e focado para aprendizagem e desenvolvimento.

## Fase 1 – Fundamentos Arquiteturais

Na primeira fase do projeto foi desenvolvida a versão inicial do **Fastfood System**, um sistema que permite aos clientes realizarem pedidos de forma autônoma, sem a necessidade de interação com atendentes.

O objetivo principal desta etapa foi estabelecer uma base arquitetural sólida, aplicando práticas modernas de engenharia de software e conceitos de arquitetura orientada a domínio.

### Objetivos da Fase
- Compreensão e modelagem do domínio do negócio.
- Definição de uma arquitetura inicial aderente a boas práticas.
- Estruturação do sistema de forma modular e desacoplada.

### Abordagens Arquiteturais
Nesta fase foram adotadas as seguintes técnicas e padrões:

- Domain-Driven Design (DDD) para modelagem do domínio.
- Arquitetura Hexagonal (Ports and Adapters) para isolamento entre domínio e infraestrutura.
- Event Storming como técnica colaborativa para descoberta e refinamento do domínio.
- Definição de Bounded Contexts e separação clara de responsabilidades.
- Implementação de uma aplicação monolítica dockerizada para padronização do ambiente de execução.

### Entregáveis
- Modelagem inicial do domínio.
- Definições arquiteturais e decisões técnicas.
- Implementação da primeira versão funcional do sistema.

### Código-fonte
O código completo da Fase 1 está disponível em:  
https://github.com/postech-group-fiap-188/fastfood-system/tree/phase1



## Fase 2 – Evolução Arquitetural e Orquestração

Nesta etapa avançamos na evolução do **Fastfood System**, realizando a refatoração da aplicação para **Clean Architecture** e preparando o ambiente para execução em **Kubernetes**, com foco em escalabilidade, observabilidade e resiliência.

O objetivo principal desta fase foi aprimorar a organização interna do sistema e introduzir práticas de orquestração de contêineres, simulando um ambiente próximo ao produtivo.

### Objetivos da Fase
- Refatorar a base de código para uma arquitetura mais desacoplada e testável.
- Preparar o sistema para execução em ambiente orquestrado.
- Validar escalabilidade e comportamento sob carga.

### Principais Entregas
- Refatoração da aplicação para **Clean Architecture**, promovendo maior separação de responsabilidades e aumento da testabilidade.
- Criação e configuração de manifests do **Kubernetes**, incluindo:
  - Ingress Controller com **ngrok** para exposição local simulando ambiente produtivo.
  - Service, ConfigMap, Secret e demais recursos nativos do Kubernetes.
- Implementação de escalabilidade automática por meio de **Horizontal Pod Autoscaler (HPA)** com base em CPU e memória.
- Execução de **testes de carga com Locust**, simulando múltiplos acessos simultâneos para validação de resiliência e escalabilidade da aplicação.

### Técnicas e Ferramentas Utilizadas
- Clean Architecture.
- Kubernetes (Ingress, Service, ConfigMap, Secret, HPA).
- Locust para testes de carga.
- Ngrok para exposição do ambiente local.

### Código-fonte
O código completo da Fase 2 está disponível em:  
https://github.com/postech-group-fiap-188/fastfood-system/tree/phase2



## Fase 3 – Cloud, Segurança e Automação

Nesta etapa focamos na preparação e implantação do **Fastfood System** em um ambiente de **Cloud real (AWS)**, aprimorando a performance do banco de dados, adicionando uma camada de segurança com **arquitetura serverless** e automatizando toda a infraestrutura e o processo de deploy.

O objetivo principal desta fase foi tornar a solução pronta para produção, com foco em escalabilidade, segurança, automação e boas práticas de engenharia de software em ambientes de nuvem.

### Objetivos da Fase
- Implantar a solução em um ambiente de nuvem real.
- Melhorar a performance e a eficiência do banco de dados.
- Adicionar uma camada de segurança desacoplada da aplicação.
- Automatizar infraestrutura e processos de build e deploy.

### Principais Entregas
- **Otimização de Banco de Dados**: adição de índices em tabelas críticas para melhoria de performance e eficiência das consultas.
- **Segurança com Arquitetura Serverless**: implementação de um autorizador dedicado utilizando recursos serverless da AWS (por exemplo, Lambda e API Gateway) para controle de acesso e autenticação.
- **Organização do Código**: separação da aplicação em múltiplos repositórios, incluindo repositórios específicos para Infraestrutura como Código (IaC).
- **Infraestrutura na Nuvem (IaC)**: criação e gerenciamento da infraestrutura na AWS utilizando **Terraform**, garantindo ambientes reprodutíveis, versionados e escaláveis.
- **Deployment Contínuo**: implementação de pipelines de **CI/CD** em todos os repositórios para automação de build, testes e deploy.
- **Implantação em Cloud**: deploy final da aplicação em um cluster **Kubernetes (EKS)** na AWS.

### Técnicas e Ferramentas Utilizadas
- Otimização de banco de dados com uso de índices.
- Arquitetura serverless para autorização (por exemplo, AWS Lambda).
- Terraform para Infraestrutura como Código (IaC) na AWS.
- CI/CD (Integração e Entrega Contínua).
- AWS EKS (Elastic Kubernetes Service) para orquestração de contêineres.

### Código-fonte
O código completo da Fase 3 está disponível em:  
https://github.com/postech-group-fiap-188/fastfood-system/tree/phase3






## Membros

| <img src="assets/membro1.jpg" width="200" height="200" alt="Douglas Vinicius"/> | <img src="assets/membro2.jpg" width="200" height="200" alt="Layssa Hillary"/> | <img src="assets/membro3.jpg" width="200" height="200" alt="Thiago Savin"/> |
|:-------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| **Douglas Vinicius**                                                            | **Layssa Hillary**                                                            | **Thiago Savin**                                                            |

| <img src="assets/membro4.jpg" width="200" height="200" alt="Novo Membro 1"/> | <img src="assets/membro5.jpg" width="200" height="200" alt="Novo Membro 2"/> |
|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| **Shayna Bauer**                                                           | **Paulo Cavalcante**                                                           |
## Como participar
A colaboração está restrita aos membros atuais do grupo. Se você faz parte da turma ou tem interesse em saber mais, entre em contato com um dos integrantes.
