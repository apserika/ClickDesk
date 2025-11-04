<h1> 📑 DoR e DoD </h1>
  
## 🧾 Definições Gerais

- **DoR (Definition of Ready):** Critérios mínimos para iniciar uma sprint.
  As tarefas devem estar compreendidas, estimadas e com recursos necessários disponíveis.  
- **DoD (Definition of Done):** Critérios mínimos para considerar uma sprint concluída com sucesso.  
  As entregas devem atender aos requisitos funcionais e não funcionais definidos, estar revisadas e versionadas no GitHub.

---
## 🎯 Sprint 1 — Estruturação do GitHub e Diagrama de Caso de Uso

**Período:** 21/08/2025 - 28/08/2025  

### ✅ DoR

- Repositório GitHub criado com a estrutura inicial de pastas organizada.

- Equipe alinhada quanto ao padrão de versionamento e boas práticas de commits.

- Ferramentas de modelagem definidas e disponíveis para todos os membros.

- Escopo do diagrama de caso de uso claramente definido e compreendido pela equipe.

### 🏁 DoD

- Repositório estruturado e acessível a todos os membros da equipe.

- README.md criado, contendo objetivo, escopo e organização do projeto.

- Diagrama de Caso de Uso revisado, exportado e versionado corretamente no repositório.


## 🎯 Sprint 2 — Diagrama de Classe de Implementação

**Período:** 28/08/2025 - 04/09/2025

### 🚀 DoR
- O Diagrama de Caso de Uso (Sprint 1) foi formalmente aprovado.
- Um rascunho inicial das principais entidades (classes) do sistema foi discutido.
- A equipe tem clareza sobre os requisitos funcionais que o diagrama de classes deve suportar.

### 🏁 DoD
- O diagrama identifica corretamente as classes, seus atributos (com tipos) e métodos principais.
- Os relacionamentos (herança, associação, agregação, composição) e suas respectivas multiplicidades foram definidos e revisados.
- O diagrama foi exportado e os arquivos (fonte e imagem) estão versionados na pasta correta no GitHub.

---

## 🎯 Sprint 3 — Diagrama de Objetos

**Período:** 04/09/2025 - 11/09/2025

### 🚀 DoR
- O Diagrama de Classe (Sprint 2) é considerado estável e validado.
- Pelo menos um cenário de uso específico (ex: "Usuário realiza login") foi selecionado para ser instanciado.
- Os dados de exemplo que serão usados para "preencher" os objetos foram definidos.

### 🏁 DoD
- O diagrama representa uma "fotografia" válida do sistema em um determinado momento, mostrando instâncias concretas das classes.
- Os valores dos atributos dos objetos são consistentes com o Diagrama de Classe (tipos, regras).
- O arquivo foi salvo na pasta da Sprint 3 e passou por uma revisão de pares (peer review).

---

## 🎯 Sprint 4 — Diagrama de Sequência

**Período:** 11/09/2025 - 18/09/2025

### 🚀 DoR
- Os cenários (Casos de Uso) que serão detalhados nesta sprint foram priorizados.
- Os objetos e classes envolvidos na interação (atores, controladores, entidades) são conhecidos.
- A ordem básica das mensagens (o "fluxo feliz") foi rascunhada pela equipe.

### 🏁 DoD
- O diagrama demonstra claramente a ordem temporal (linhas de vida) das mensagens trocadas entre os objetos.
- A sintaxe UML (setas síncronas/assíncronas, loops, fragmentos `alt`/`opt`) foi usada corretamente.
- O diagrama foi validado contra o Caso de Uso e o Diagrama de Classe para garantir consistência.
- O arquivo final foi enviado ao repositório.

---

## 🎯 Sprint 5 — Diagrama de Colaboração (Comunicação)

**Período:** 18/09/2025 - 25/09/2025

### 🚀 DoR
- O Diagrama de Sequência (Sprint 4) está completo e aprovado.
- A equipe entende que este diagrama é uma visão estrutural (foco nos links) do mesmo cenário visto no Diagrama de Sequência (foco no tempo).

### 🏁 DoD
- O diagrama foca na organização espacial dos objetos e como eles estão conectados (links).
- A numeração das mensagens está correta e é 100% consistente com a ordem definida no Diagrama de Sequência.
- O arquivo foi exportado e commitado na pasta da Sprint 5.

---

## 🎯 Sprint 6 — Diagrama de Pacote

**Período:** 25/09/2025 - 02/10/2025

### 🚀 DoR
- As principais classes e componentes do sistema (Sprints 2-5) estão identificados.
- A arquitetura do sistema (ex: arquitetura em camadas, microsserviços) foi discutida e definida pela equipe.
- As regras de dependência (o que "pode ver" o quê) foram estabelecidas.

### 🏁 DoD
- O diagrama agrupa logicamente as classes em pacotes (namespaces/módulos).
- As dependências (ex: `<<import>>` ou `<<access>>`) entre os pacotes estão claramente visíveis e seguem as regras de arquitetura.
- O diagrama foi validado pela equipe e o arquivo-fonte/imagem está no GitHub.

---

## 🎯 Sprint 7 — Diagrama de Implantação

**Período:** 02/10/2025 - 09/10/2025

### 🚀 DoR
- Os requisitos não-funcionais de infraestrutura (hardware, rede, SGBD, servidor de aplicação) foram levantados.
- Os artefatos de software que serão implantados (ex: `.jar`, `.war`, scripts de banco de dados) são conhecidos.

### 🏁 DoD
- O diagrama modela a arquitetura física (hardware, nós, servidores) e como os artefatos de software são distribuídos por ela.
- Os protocolos de comunicação (ex: HTTP, TCP/IP, JDBC) entre os nós estão identificados.
- O arquivo final foi revisado, exportado para um formato acessível (PDF/PNG) e enviado ao repositório.

---

## 🎯 Sprint 8 — Diagrama de Estrutura

**Período:** 09/10/2025 - 16/10/2025
### 🚀 DoR
- Os principais componentes lógicos do software foram identificados (baseado no Diagrama de Pacotes).
- As interfaces (APIs, pontos de conexão) entre os componentes foram rascunhadas.
- Todos os diagramas anteriores estão disponíveis para consulta.

### 🏁 DoD
- O Diagrama de Componentes (ou Estrutura Composta) mostra as partes modulares do sistema e suas interações.
- As interfaces (portas `provided` e `required`) estão claramente definidas, mostrando o "contrato" de cada componente.
- O diagrama final é consistente com o Diagrama de Pacotes e foi versionado no GitHub.
