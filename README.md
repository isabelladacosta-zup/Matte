<div align="center">

<img src="1787923349117.png" width="160" alt="Matte">

# Matte

**Assistente técnico interno da Zup. Tira dúvidas de infraestrutura e ferramentas — rápido e sem abrir chamado.**

![StackSpot AI](https://img.shields.io/badge/StackSpot_AI-Agent-7E2A2C?style=for-the-badge&labelColor=3A1214)
![tipo](https://img.shields.io/badge/tipo-conversacional-7E2A2C?style=for-the-badge&labelColor=3A1214)
![status](https://img.shields.io/badge/status-ativo-FFD9A8?style=for-the-badge&labelColor=3A1214)

<sub>[O que ele resolve](#o-que-ele-resolve) · [Como usar](#como-usar) · [Bases de conhecimento](#bases-de-conhecimento) · [O que ele não faz](#o-que-ele-não-faz) · [Contribuindo](#contribuindo)</sub>

</div>

---

> **Olá, Zupper!** Eu sou o Matte, seu assistente técnico inteligente.
> Estou aqui para tirar suas dúvidas sobre a infraestrutura e as tecnologias da Zup
> de forma rápida e precisa. O que você deseja configurar ou solucionar hoje? 🚀

## O que ele resolve

| Domínio | Cobre | Exemplo de pergunta |
|---|---|---|
| **VPN & MFA** | Cisco AnyConnect, redefinição de autenticador | *"Como configuro o AnyConnect no macOS?"* |
| **Nuvem & Kubernetes** | Perfis AWS SSO, quotas, namespaces no EKS | *"Como vejo a quota do meu namespace no EKS?"* |
| **Charles CD** | Deploys com círculos | *"Como crio um círculo pra testar com 5% do tráfego?"* |
| **Ritchie CLI** | Criação e uso de fórmulas | *"Como adiciono um repositório de fórmulas no Ritchie?"* |
| **Horusec** | Análise de vulnerabilidades | *"Como ignoro um falso positivo do Horusec?"* |
| **Acessos seguros** | Conexão a bancos privados via Bastion Host | *"Como abro um túnel pro banco via Bastion?"* |
| **ServiceNow** | Categorização de chamados e SLAs | *"Qual a categoria certa pra pedido de acesso à AWS?"* |

## Como usar

**Portal StackSpot AI** — abra o agente pelo catálogo e mande a dúvida no chat.

**Extensão no IDE** — selecione o Matte como agente ativo e pergunte sem sair do editor.

**Spot da squad** — [`ai.stackspot.com/agents/a96a47-matte-seu-agente-de-ti-`]() (peça acesso de leitura pro time responsável).

### Perguntando melhor

O Matte busca por similaridade nas bases de conhecimento, então **use os termos que aparecem na doc**. Comparando:

| ❌ Vago | ✅ Direto |
|---|---|
| "a vpn não funciona" | "AnyConnect dá erro de certificado ao conectar" |
| "não consigo acessar o banco" | "como conectar no RDS privado via Bastion Host" |
| "problema no deploy" | "Charles CD: círculo não recebe tráfego após o deploy" |

Um erro colado na íntegra vale mais que qualquer descrição.



## O que ele não faz

- **Não concede acessos.** Ele explica o caminho; a liberação sai por chamado ou pelo time dono do recurso.
- **Não abre chamado no ServiceNow.** Ele diz a categoria certa — abrir é com você.
- **Não substitui a squad de Infra/SecOps** em incidente. Se está de pé caindo, acione o plantão.
- **Pode estar desatualizado.** A resposta vale o que valem as bases — se a doc mudou e a KS não, ele erra.

> ⚠️ **Nunca cole credenciais, tokens, chaves ou dados de cliente no chat.** Se um passo pede segredo, ele te diz *onde* buscar, não pede pra você mostrar.



## Paleta

| | Cor | Hex | Uso |
|---|---|---|---|
| 🟥 | Corpo | `#7E2A2C` | Principal |
| 🟫 | Sombra | `#5C1D1F` | Hover, bordas |
| ⬛ | Casca | `#3A1214` | Fundo escuro |
| 🟨 | Olhos | `#FFD9A8` | Acento |
| ⬜ | Brilho | `#FFF1DE` | Texto sobre escuro |
| ⬜ | Fundo | `#EAE4E1` | Fundo claro |

## Time

Mantido por **`isa tessarin`** 
