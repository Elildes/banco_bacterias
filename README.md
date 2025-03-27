# Relatório do Projeto de Sistemas de Banco de Dados

## Universidade Federal do Rio Garnde do Norte
**Curso:** Bacharelado em Tecnologia da Informação e Bacharelado em Engenharia de Software  
**Alunos:**  
   DOUGLAS FELIPE DE LIMA SILVA  
   ELILDES FORTALEZA SANTOS  
   FELIPE MARLEY DE OLIVEIRA GOMES    
**Matrícula:s** 20220054131, 20240078023 e 20210053408    
**Professor:** MARCEL VINICIUS MEDEIROS OLIVEIRA   
**Data:** 01/04/2025

---

## Sumário

1. [Concepção e Definição dos Projetos](#1-concepção-e-definição-dos-projetos)
2. [Descrição da Entrega Inicial do Projeto](#2-descrição-da-entrega-inicial-do-projeto)  
   2.1 [Descrição da Visão do Produto](#21-descrição-da-visão-do-produto)  
   2.2 [Descrição dos Atores Envolvidos e dos Usuários Finais](#22-descrição-dos-atores-envolvidos-e-dos-usuários-finais)  
   2.3 [Descrição do Ambiente do Usuário](#23-descrição-do-ambiente-do-usuário)  
   2.4 [Principais Necessidades dos Usuários e Envolvidos](#24-principais-necessidades-dos-usuários-e-envolvidos)  
   2.5 [Alternativas e Concorrência](#25-alternativas-e-concorrência)  
   2.6 [Visão Geral do Produto](#26-visão-geral-do-produto)  
   2.7 [Recursos do Produto](#27-recursos-do-produto)  
   2.8 [Outros Requisitos do Sistema](#28-outros-requisitos-do-sistema)  
   2.9 [Cronograma do Projeto](#29-cronograma-do-projeto)
3. [Descrição da Entrega Final do Projeto](#3-descrição-da-entrega-final-do-projeto)

---

## 1. Concepção e Definição dos Projetos

A proposta deste projeto é direcionar o aprendizado dos participantes na concepção e implementação de um sistema de banco de dados para o **Catálogo de Isolados do Laboratório de Biologia Molecular e Genômica**. O objetivo é desenvolver uma solução inovadora que permita armazenar, consultar e gerenciar informações sobre bactérias coletadas, facilitando a pesquisa e análise dos dados.

> Inovação é definida na Lei brasileira como introdução de novidade ou aperfeiçoamento no ambiente produtivo e social que resulte em novos produtos, serviços ou processos ou que compreenda a agregação de novas funcionalidades ou características a produto, serviço ou processo já existente que possa resultar em melhorias e em efetivo ganho de qualidade ou desempenho. (Lei nº 13.243, de 2016)

### 1.1 Problemas da situação atual (as-is)

Com base na planilha e no contexto do projeto do banco de dados para o Catálogo de Isolados do Laboratório de Biologia Molecular e Genômica, os principais problemas identificados na situação atual incluem:

- Armazenamento descentralizado e desorganizado: Os dados dos isolados bacterianos estão dispersos em planilhas e documentos não estruturados, dificultando a recuperação eficiente de informações.

- Falta de padronização: Os registros possuem diferentes formatos e nomenclaturas, podendo causar inconsistências nos dados.

- Dificuldade de acesso e compartilhamento: O acesso às informações é manual e pouco eficiente, dificultando a colaboração entre pesquisadores.

- Baixa rastreabilidade das amostras: Não há um sistema que acompanhe automaticamente a atualização dos dados, tornando difícil manter um histórico confiável das informações.

- Limitações em análises e consultas avançadas: Devido à estrutura não relacional dos dados, realizar análises cruzadas e buscas detalhadas é um processo demorado e manual.

- Risco de perda de dados: O armazenamento em planilhas sem backup ou controle adequado pode levar à perda de informações essenciais para a pesquisa.

### 1.2 Soluções inovadoras para a situação futura (to-be)

Para resolver os problemas identificados, o projeto propõe as seguintes soluções inovadoras:

- Desenvolvimento de um banco de dados relacional (PostgreSQL) para centralizar e estruturar os dados, garantindo consistência e segurança.

- Padronização dos registros de isolados bacterianos, garantindo nomenclatura única e formatos compatíveis com padrões científicos.

- Criação de uma interface web (PWA) para facilitar o cadastro, consulta e gerenciamento das amostras, acessível a partir de diferentes dispositivos.

- Implementação de controle de acesso com níveis de permissão, garantindo que apenas usuários autorizados possam inserir, editar e visualizar determinadas informações.

- Adoção de rastreamento e versionamento de dados, permitindo que todas as modificações fiquem registradas, garantindo maior confiabilidade na pesquisa.

- Integração com ferramentas de análise genômica para permitir a importação e cruzamento de dados diretamente no sistema.

- Automatização de processos como a geração de relatórios personalizados e alertas sobre novas amostras ou atualizações críticas.

- Implementação de um sistema de backup automático para evitar perdas de dados e garantir a continuidade das pesquisas.

Essas soluções permitirão maior eficiência, segurança e acessibilidade no gerenciamento do Catálogo de Isolados, melhorando significativamente a experiência dos pesquisadores e a qualidade das informações armazenadas.


---

## 2. Descrição da Entrega Inicial do Projeto

### 2.1 Descrição da Visão do Produto

Descrever os objetivos do projeto, indicando o propósito, principais benefícios e a motivação para sua realização. Detalhar:
- Necessidades
- Estado atual
- Melhorias esperadas
- Modelagem de Processo de Negócio (usando notação BPM)

### 2.2 Descrição dos Atores Envolvidos e dos Usuários Finais

**Envolvidos (não usuários finais):**
- Nome:
- Descrição:
- Responsabilidade:

**Usuários Finais:**
- Nome:
- Descrição:
- Responsabilidade:
- Envolvido representante:

### 2.3 Descrição do Ambiente do Usuário

- Número de pessoas envolvidas nas tarefas
- Duração do ciclo de tarefas
- Restrições existentes
- Plataformas utilizadas atualmente e futuras
- Integração com outros aplicativos existentes

### 2.4 Principais Necessidades dos Usuários e Envolvidos

Para cada problema identificado:
- Quais são as causas?
- Como está sendo resolvido agora?
- Qual a solução desejada?

E para cada necessidade:
- Prioridade
- Preocupações
- Solução Atual
- Solução Proposta

### 2.5 Alternativas e Concorrência

Listar as opções disponíveis:
- Produtos concorrentes
- Soluções locais
- Manutenção do status quo

Analisar pontos fortes e fracos de cada alternativa conforme a visão dos envolvidos.

### 2.6 Visão Geral do Produto

**Perspectiva do Produto:**
- Independência ou integração com outros sistemas
- Diagrama de blocos (se aplicável)

**Suposições e Dependências:**
- Fatores que podem alterar os requisitos
- Exemplo: disponibilidade de sistema operacional ou infraestrutura

### 2.7 Recursos do Produto

Listar funcionalidades (requisitos funcionais):
- Descrição geral das funcionalidades
- Prioridade, estabilidade, esforço, risco
- Questões de usabilidade

### 2.8 Outros Requisitos do Sistema

Listar requisitos não funcionais:
- Padrões aplicáveis
- Hardware/plataforma
- Desempenho
- Tolerância a erros
- Usabilidade
- Documentação
- Restrições externas

### 2.9 Cronograma do Projeto

- Estrutura Analítica do Projeto (EAP)
- Entregáveis intermediários
- Previsão de conclusão

Incluir lista de documentos mencionados com:
- Título
- Número (se houver)
- Data
- Organização

---

## 3. Descrição da Entrega Final do Projeto

Ao final do semestre, os grupos devem apresentar:

- Documento de Visão de Produto
- Modelo Entidade-Relacionamento (ER)
- Modelo Relacional
- Normalização
- Código-fonte do sistema implementado

> Entregas intermediárias ocorrerão conforme cronograma definido pelo professor.

---

