# Node-RED: Instalação e Fundamentos (CNVI)

Repositório para a entrega do trabalho da aula **CNVI - Instalação e Fundamentos do Node-RED**. Contém a documentação e os fluxos desenvolvidos com base na playlist oficial *Node-RED Essentials*.

---

## 📌 Estrutura do Repositório
- **`README.md`**: Documentação e explicação do projeto.
- **`flows/`**: Pasta contendo os ficheiros `.json` de cada fluxo praticado.

---

## 🚀 Tópicos e Fluxos (`flows/`)

| Ficheiro / Fluxo | Tópico | Descrição |
|---|---|---|
| `01-introduction.json` | Introduction | Apresentação e conceitos de programação baseada em fluxos. |
| `02-editor-components.json` | Editor Components | Visão geral do editor (Palette, Workspace, Header, Sidebar). |
| `03-creating-a-flow.json` | Creating a Flow | Montagem do primeiro fluxo com Inject, Function e Debug. |
| `04-wiring-nodes.json` | Wiring Nodes | Ligações entre nós, atalhos de conexão e remoção de fios. |
| `05-editing-nodes.json` | Editing Nodes | Edição de propriedades, documentação em Markdown e desativação. |
| `06-deploying-flows.json` | Deploying Flows | Tipos de Deploy (Full, Modified Flows, Modified Nodes). |
| `07-information-sidebar.json` | Information Sidebar | Painel de informação, estrutura em árvore e ajuda de nós. |
| `08-debug-sidebar.json` | Debug Sidebar | Leitura de logs, filtragem e inspeção detalhada de mensagens. |
| `09-configuration-nodes-sidebar.json` | Configuration Nodes | Gestão de nós de configuração global e reutilizável. |
| `10-context-sidebar.json` | Context Sidebar | Inspeção de variáveis de contexto (Node, Flow, Global). |
| `11-subflows.json` | Subflows | Criação de subfluxos e blocos de código reutilizáveis. |
| `12-working-with-context.json` | Working with Context | Armazenamento e persistência de dados no contexto. |
| `13-introduction-to-messages.json` | Introduction to Messages | Estrutura do objeto `msg`, `msg.payload` e nó JSON. |
| `14-working-with-messages.json` | Working with Messages | Alteração e conversão de mensagens com Change e JSONata. |
| `15-message-sequences.json` | Message Sequences | Divisão e junção de sequências de dados (Split / Join). |
| `16-routing-messages.json` | Routing Messages | Encaminhamento condicional de mensagens com o nó Switch. |
| `17-managing-message-flow.json` | Managing Message Flow | Controlo de fluxo e temporização com Delay e Trigger. |
| `18-merging-flows.json` | Merging Flows | Combinação de múltiplos fluxos de dados num só. |
| `19-grouping-nodes.json` | Grouping Nodes | Organização visual e documentação de grupos no editor. |

---

## 🛠️ Como Executar o Projeto Localmente

1. **Instalar o Node.js** (versão LTS): [nodejs.org](https://nodejs.org)
2. **Instalar o Node-RED**:
   ```bash
   npm install -g --unsafe-perm node-red