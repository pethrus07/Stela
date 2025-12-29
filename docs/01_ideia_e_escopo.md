# Stela 4.0 — Ideia, Escopo e Funcionalidades

## 1. Contexto do Projeto

A Stela é um projeto pessoal que acompanha minha evolução técnica ao longo do tempo.  
As versões anteriores surgiram como experimentos simples de interação e automação, sem uma arquitetura bem definida. Com o amadurecimento dos estudos e maior contato com projetos reais, tornou-se necessário refatorar completamente a ideia, tanto em termos técnicos quanto conceituais.

A versão 4.0 nasce, portanto, como uma reestruturação total do projeto, com foco em organização, clareza de responsabilidades, versionamento e integração com outros sistemas do meu portfólio.

---

## 2. O que é a Stela 4.0

A Stela 4.0 é um chatbot backend-first, desenvolvido em Python, com persistência de dados em SQLite, pensado para operar inicialmente sem interface gráfica.

Seu papel principal não é “simular conversa humana”, mas atuar como um **assistente funcional**, capaz de:
- responder a consultas estruturadas,
- acessar dados previamente armazenados,
- consumir APIs externas simples,
- servir como camada de interação para outros projetos.

A interface visual será adicionada posteriormente, por meio de integração com o site de portfólio desenvolvido em Wix.

---

## 3. Motivação e Objetivos

O projeto possui três objetivos centrais:

1. **Técnico**  
   Consolidar conhecimentos em:
   - arquitetura de projetos em Python,
   - separação de responsabilidades,
   - integração com banco de dados,
   - consumo de APIs externas,
   - versionamento contínuo com Git.

2. **Portfólio**  
   Servir como projeto demonstrável, onde seja possível avaliar:
   - organização do código,
   - clareza de documentação,
   - capacidade de planejar e evoluir um sistema ao longo do tempo.

3. **Integração futura**  
   A Stela foi pensada para dialogar, conceitualmente, com um projeto futuro de organizador pessoal, funcionando como uma camada de consulta e acesso a informações armazenadas.

---

## 4. Relação com o Portfólio

No contexto do portfólio pessoal, a Stela não será apresentada como um produto final para uso amplo, mas como um **projeto técnico explicável**.

O foco está em:
- decisões de arquitetura,
- escolhas de tecnologias,
- limitações assumidas,
- e possibilidades de expansão.

A interface visual, quando integrada ao site, terá caráter demonstrativo, enquanto o núcleo do projeto permanece no backend.

---

## 5. Funcionalidades Previstas (Escopo Inicial)

### 5.1 Funcionalidades Básicas
- Processamento de entradas textuais simples.
- Roteamento de comandos e intenções.
- Respostas baseadas em dados internos.

### 5.2 Persistência de Dados
- Banco de dados SQLite.
- Estrutura de tabelas voltadas para:
  - informações do portfólio,
  - dados estáticos do usuário,
  - registros simples de interação.

### 5.3 Consumo de APIs Externas
- Integração com APIs públicas e simples (ex.: clima, horário, informações gerais).
- Uso dessas integrações como demonstração prática de consumo de serviços externos.

### 5.4 Interface Inicial
- Interface via linha de comando (CLI), apenas para validação funcional.
- Sem foco em experiência do usuário neste estágio.

---

## 6. Limites do Projeto (Escopo Delimitado)

A Stela 4.0 **não tem como objetivo**:
- substituir assistentes comerciais,
- realizar processamento avançado de linguagem natural,
- operar de forma autônoma,
- armazenar dados sensíveis,
- ou escalar para múltiplos usuários.

Essas decisões são conscientes e fazem parte da proposta do projeto.

---

## 7. Evolução e Versionamento

A Stela já passou por versões anteriores, desenvolvidas de forma menos estruturada.  
A versão 4.0 marca:
- a adoção de uma arquitetura clara,
- versionamento contínuo desde o primeiro commit,
- documentação desde a fase inicial,
- e separação explícita entre ideia, implementação e interface.

A evolução do projeto será registrada por commits incrementais e documentação associada.

---

## 8. Considerações Finais

A Stela 4.0 é, acima de tudo, um projeto de consolidação técnica.  
Ela existe menos para impressionar visualmente e mais para demonstrar capacidade de planejamento, organização e execução de um sistema coerente, mesmo em escala reduzida.
