# Bellas Magras: skill de conteúdo

Skill para o [Claude Code](https://claude.com/claude-code) que cria conteúdo de Instagram para a Geicy Maralves ([@geicymaralves](https://www.instagram.com/geicymaralves/)) no posicionamento do **Método Bellas Magras** e do mecanismo das **2 Fomes**: roteiros de Reels, carrosséis, legendas, stories e semanas de conteúdo, na voz dela.

- Conteúdo **atemporal** (banco de temas por fome e pilar) e de **atualidade** (notícias recentes ligadas ao mecanismo)
- Instala e mantém atualizado o [last30days](https://github.com/mvanhorn/last30days-skill) para pesquisa de tendências
- Regras de comunicação embutidas (promessas, suplemento, medicação, testemunho sensível)

## Instalação

**Claude Code (qualquer projeto):**

```bash
npx skills add viniciusfolem/bellas-magras-conteudo -g -a claude-code
```

Ou manualmente:

```bash
git clone https://github.com/viniciusfolem/bellas-magras-conteudo ~/.claude/skills/bellas-magras-conteudo
```

**claude.ai:** baixe o repositório como zip (Code → Download ZIP) e envie em Configurações → Capacidades → Skills.

## Como usar

Peça normalmente, por exemplo:

- "roteiro da Geicy sobre comer à noite"
- "semana de conteúdo Bellas Magras"
- "transforma essa notícia em Reels para a Geicy: [link]"

## Estrutura

```
SKILL.md                         fluxo, núcleo do posicionamento e checklist
references/posicionamento.md     público, Big Idea, 2 Fomes, promessa, ofertas
references/voz-da-geicy.md       como ela fala e o que cortar
references/formatos.md           formatos que viralizaram no nicho + mix da semana
references/banco-de-temas.md     pautas atemporais
references/pesquisa-de-pautas.md notícias e tendências
references/regras.md             o que não pode ser dito
scripts/garantir-last30days.sh   instala/atualiza o last30days
```
