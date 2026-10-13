# teste

## Agentes do Claude Code

Este repositório define subagentes em `.claude/agents/`.

### `assistente-fiscal`

Especialista em rotinas contábeis, fiscais e trabalhistas brasileiras (folha, eSocial,
apuração de tributos, Reforma Tributária, conferência de planilhas).

**Como usar:** abra o Claude Code neste repositório e peça algo como:

- "Use o assistente-fiscal para conferir a folha de setembro na planilha folha.xlsx"
- "Pergunte ao assistente-fiscal qual o vencimento da DCTFWeb de outubro"

O Claude Code também chama o agente sozinho quando o pedido combina com a descrição dele.
Para ver ou editar os agentes, use o comando `/agents`.

**Como personalizar:** edite `.claude/agents/assistente-fiscal.md`. O bloco entre `---`
define nome, descrição (quando o agente é acionado) e ferramentas permitidas; o texto
abaixo é o prompt de sistema do agente.
