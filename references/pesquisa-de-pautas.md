# Pesquisa de pautas

Objetivo: achar fatos recentes (últimos 30 dias) que provem que a fome da mulher está ligada, e transformar em conteúdo.

## Fontes

1. **WebSearch em português (principal).** Notícias do Brasil. Busque com o mês e o ano atuais. Consultas sugeridas:
   - "Mounjaro" OR "caneta emagrecedora" reganho de peso [mês ano]
   - Anvisa canetas emagrecedoras [mês ano]
   - compulsão alimentar estudo [mês ano]
   - comer à noite estudo ansiedade [mês ano]
   - efeito sanfona pesquisa [mês ano]
   - menopausa peso fome estudo [mês ano]
   - dieta da moda viral [mês ano]
2. **/last30days (tendências e conversa da internet).** Antes, rode `bash scripts/garantir-last30days.sh` (na pasta da skill bellas-magras-conteudo): ele instala o last30days se faltar e atualiza para a última versão do GitHub (mvanhorn/last30days-skill), guardando a versão antiga em `~/.claude/skills-backup/`. Depois use a skill `last30days` quando quiser saber o que as pessoas estão FALANDO (Reddit, YouTube, TikTok, X). As fontes são mais em inglês. Bons temas: "GLP-1 food noise after stopping", "weight regain after Ozempic", "emotional eating at night". Traduza o achado para a realidade brasileira.
3. **Instagram dos concorrentes (opcional).** Com a chave `APIFY_INSTAGRAM_SCRAPER` (no `.env` do projeto, puxada do cofre), o ator `apify/instagram-scraper` traz os posts recentes de @vanessabaadnutri, @leteponto e @zanonmacedo para ver o que está viralizando. Dados antigos ficam em `pesquisa/instagram/`.

## Filtro: a pauta serve?

Uma pauta só entra se responder SIM a pelo menos uma pergunta:

- Mostra que a dieta ou a caneta **liga ou abafa** a Fome do Corpo?
- Mostra a **Fome da Ferida** (emoção, estresse, sono, noite, culpa)?
- Mostra que o problema **não é força de vontade**?

Descarte notícia que só fala de estética, celebridade sem gancho de fome, ou receita sem ligação com o mecanismo.

## Ponte notícia → mecanismo

```
FATO: (o que aconteceu, com fonte)
O QUE ELA SENTE: (como isso aparece na vida da mulher)
QUAL FOME: do Corpo | da Ferida | as 2
VIRADA: "isso prova que…"
O MÉTODO: qual pilar desliga
GANCHO: (0-3s)
```

Exemplo:

```
FATO: estudos mostram que quem para a semaglutida recupera cerca de 2/3 do peso em um ano (STEP 1).
O QUE ELA SENTE: "parei a caneta e a fome voltou com tudo".
QUAL FOME: as 2. A caneta abafava; nada foi desligado.
VIRADA: "a caneta abafa a fome. Ela não desliga."
O MÉTODO: Corpo (fome física) + Alma (a ferida que a caneta só silenciou).
GANCHO: "Parou a caneta e o peso voltou? Não foi você que falhou."
(+ "decisão sobre medicação é sempre com o seu médico")
```

## Entrega da pesquisa

Lista de 3 a 5 pautas, cada uma com: título, fonte (link), fome, gancho e formato sugerido. Depois escreva as peças que a pessoa escolher, ou a semana inteira se pedirem.
