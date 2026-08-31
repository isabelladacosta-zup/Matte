<div align="center">

<img src="docs/matte.png" width="160" alt="Matte">

# Matte

**Uma frase curta dizendo o que o Matte faz.**

[![licença](https://img.shields.io/badge/licença-MIT-7E2A2C?style=for-the-badge&labelColor=3A1214)](LICENSE)
[![versão](https://img.shields.io/badge/versão-0.1.0-7E2A2C?style=for-the-badge&labelColor=3A1214)]()
[![feito com](https://img.shields.io/badge/feito_com-LINGUAGEM-FFD9A8?style=for-the-badge&labelColor=3A1214)]()

<sub>[Instalação](#instalação) · [Uso](#uso) · [Configuração](#configuração) · [Contribuindo](#contribuindo)</sub>

</div>

---

## Oi, eu sou o Matte

Duas ou três linhas na voz dele: qual problema ele resolve e pra quem. Como o
Matte tem cara, vale escrever essa parte em primeira pessoa — funciona
surpreendentemente bem pra fixar o projeto na memória de quem lê.

<img src="docs/demo.gif" width="100%" alt="Matte em ação">

## Instalação

```bash
GERENCIADOR install matte
```

<details>
<summary>Instalar do fonte</summary>

```bash
git clone https://github.com/USUARIO/matte.git
cd matte
COMANDO_DE_BUILD
```

</details>

## Uso

```bash
matte [opções] <argumento>
```

### Exemplos

```bash
matte EXEMPLO_REAL_1
matte --formato json EXEMPLO_REAL_2
cat entrada.txt | matte -
```

### Opções

| Flag | Atalho | Padrão | Descrição |
|------|--------|--------|-----------|
| `--formato` | `-f` | `texto` | Saída: `texto`, `json`, `csv` |
| `--verbose` | `-v` | `false` | Mostra o que está acontecendo |
| `--config` | `-c` | `~/.matterc` | Caminho do arquivo de config |
| `--quiet` | `-q` | `false` | Desliga o banner e os logs |
| `--help` | `-h` | — | Mostra a ajuda |

## Configuração

Se existir um `.matterc` no diretório atual ou no seu home, ele é carregado sozinho:

```yaml
formato: json
verbose: true
```

Precedência: flags > variáveis de ambiente > arquivo de config > padrões.

## Paleta

O Matte tem cor própria. Se você for fazer site, docs ou mais assets, use estas:

| | Cor | Hex | Onde usar |
|---|---|---|---|
| 🟥 | Corpo | `#7E2A2C` | Cor principal, títulos, links |
| 🟫 | Sombra | `#5C1D1F` | Hover, bordas |
| ⬛ | Casca | `#3A1214` | Fundo escuro, base dos badges |
| 🟨 | Olhos | `#FFD9A8` | Acento, destaques, sucesso |
| ⬜ | Brilho | `#FFF1DE` | Texto sobre fundo escuro |
| ⬜ | Fundo | `#EAE4E1` | Fundo claro |

## Contribuindo

PRs bem-vindos. Pra mudanças grandes, abre uma issue antes.

```bash
COMANDO_DE_TESTE
COMANDO_DE_LINT
```

## Licença

[MIT](LICENSE) © SEU_NOME
