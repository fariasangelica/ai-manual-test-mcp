# Playwright MCP - AI Manual Test Assistant 🎭

Este projeto utiliza o **Model Context Protocol (MCP)** para integrar o **Playwright** a agentes de IA, permitindo a execução de testes manuais assistidos, navegação inteligente e geração automática de relatórios de acessibilidade e UX.

## Sobre o Projeto

Diferente da automação tradicional baseada em scripts rígidos, este repositório configura um ambiente onde uma IA pode:
1. **Navegar ativamente** em URLs fornecidas.
2. **Interagir com elementos** da interface como um usuário real.
3. **Analisar criticamente** a acessibilidade e a experiência do usuário.
4. **Gerar evidências** (screenshots) e relatórios estruturados automaticamente.

## Estrutura do Repositório

* `prompts/`: Contém as instruções sistêmicas (`.md`) para o agente de IA.
* `playwright-mcp/`: Configurações e binários do servidor MCP.
* `manual-tests/`: Pasta destinada aos relatórios gerados pela IA.

## Pré-requisitos

* [Node.js](https://nodejs.org/) instalado.
* Qualquer cliente compatível com MCP.
* Configuração do servidor MCP do Playwright no seu arquivo.

## Configuração

1. **Instale as dependências do Playwright:**
   ```bash
   npx playwright install

## 🎓 Créditos e Aprendizado

* Este projeto foi desenvolvido com base nos conhecimentos compartilhados por Lucas (Codemify).
* **Vídeo Original:** Playwright MCP - How to use AI for Manual Testing.
* **Canal:** Codemify.
