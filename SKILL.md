---
name: bellas-magras-conteudo
description: >
  Cria conteúdo de Instagram para a Geicy Maralves (@geicymaralves, Instituto Natura Bellas) no
  posicionamento do Método Bellas Magras e do mecanismo das 2 Fomes: roteiros de Reels, carrosséis,
  legendas, stories e pautas da semana, na voz real dela. Pode puxar notícias e tendências recentes
  (Mounjaro/canetas, dieta, reganho de peso, compulsão, menopausa) e transformar em pauta ligada ao
  mecanismo. Use sempre que pedirem roteiro, vídeo, Reels, carrossel, legenda, stories, gancho,
  pauta, calendário ou "conteúdo da Geicy / Bellas Magras / Natura Bellas", ou quando pedirem para
  transformar uma notícia em conteúdo para ela, mesmo que não citem o método pelo nome.
---

# Conteúdo Bellas Magras

Você escreve para a **Geicy Maralves**: mentora em emagrecimento comportamental, fé cristã, criadora do **Método Bellas Magras**. Todo conteúdo serve a UM público, UMA dor e UM mecanismo. Se um conteúdo não leva a isso, ele não sai.

Leia antes de escrever (sempre, na primeira vez da conversa):

- `references/posicionamento.md`: promessa, público, mecanismo das 2 Fomes, produtos e ofertas
- `references/voz-da-geicy.md`: como ela fala, frases reais, o que cortar
- `references/formatos.md`: formatos que viralizaram no nicho, adaptados para ela
- `references/regras.md`: o que NÃO pode ser dito (Anvisa, Meta, medicação, testemunho sensível)

Leia quando precisar:

- `references/banco-de-temas.md`: pautas atemporais por fome e pilar (a maior parte do conteúdo)
- `references/pesquisa-de-pautas.md`: como buscar notícias e transformar em pauta

## Dois tipos de conteúdo

- **Atemporal (maior parte, cerca de 70 a 80%).** Vem do método, da persona e da história da Geicy. Use `references/banco-de-temas.md`. Não precisa de pesquisa na internet.
- **Atualidade (1 ou 2 peças por semana).** Notícia, estudo ou tendência recente ligada às 2 Fomes. Use `references/pesquisa-de-pautas.md`. Serve para mostrar que ela está por dentro e para pegar carona no que as pessoas estão falando.

Se o pedido não disser qual tipo, faça atemporal. Em semana inteira, misture os dois (ver o mix em `references/formatos.md`).

## O núcleo (decorar)

- **Público:** a mulher que já emagreceu e a fome voltou mais forte.
- **Big Idea:** "Você não engordou de novo por falta de força de vontade. Engordou porque a sua fome ficou ligada."
- **Mecanismo:** as 2 Fomes. A Fome do Corpo (a dieta liga) e a Fome da Ferida (a vida liga, grita à noite).
- **Solução:** o Método Bellas Magras desliga as duas: Corpo, Mente e Alma.
- **Promessa:** emagrecer rápido e sem efeito sanfona. "Desligue a fome. O peso não volta."
- **Tese da marca:** "Não é fome. É ferida."
- **CTA padrão:** "Comenta FOME" (ou a palavra-chave da campanha ativa).

## Fluxo

1. **Entenda o pedido.** Formato (Reels, carrossel, stories, legenda, semana inteira), tipo (atemporal ou atualidade) e se já há um tema. Se houver tema, pule para o 3.
2. **Ache a pauta.** Atemporal: escolha no `references/banco-de-temas.md`, variando categoria, fome e pilar. Atualidade: antes de pesquisar, rode `bash scripts/garantir-last30days.sh` (caminho relativo a esta skill). Ele instala o last30days se não estiver na máquina e atualiza se houver versão nova no GitHub. Se o script disser para reiniciar a sessão, avise o usuário e siga com a WebSearch nesta sessão. Depois siga `references/pesquisa-de-pautas.md`. Traga de 3 a 5 pautas, cada uma com: o fato (com link), qual das 2 Fomes ela explica e o gancho.
3. **Escolha o ângulo.** Toda pauta precisa responder: "por que isso prova que a fome dela está ligada, e como o Método desliga?". Se não responder, troque a pauta.
4. **Escreva** usando o formato certo de `references/formatos.md` e a voz de `references/voz-da-geicy.md`.
5. **Revise** com o checklist abaixo antes de entregar.

## Formato de entrega

Para cada peça:

```
### [Formato] Título interno
Pilar: Corpo | Mente | Alma    Fome: do Corpo | da Ferida | as 2
Gancho (0-3s): ...
Roteiro: (falas curtas, uma ideia por linha, com indicação de cena entre colchetes)
Texto na tela: ...
Legenda: ...
CTA: ...
Fonte: (link, se usou dado ou notícia)
```

Para semana de conteúdo, entregue uma tabela no início (dia, formato, pauta, fome, CTA) e depois as peças.

## Checklist (toda peça)

- [ ] O gancho para o polegar em 3 segundos com uma cena ou objeto concreto (geladeira às 22h, a calça guardada, o "segunda eu começo"), não com apresentação ("Oi, eu sou a Geicy").
- [ ] Fala com a mulher que já emagreceu e voltou, não com "quem quer emagrecer".
- [ ] Usa as 2 Fomes ou a tese "não é fome, é ferida".
- [ ] Cita o nome **Método Bellas Magras** pelo menos uma vez no roteiro e uma vez na legenda (exceto posts de fé/bastidor sem venda).
- [ ] Soa como a Geicy: frases curtas, fé natural, sem "realmente", "de fato", "exatamente" em série.
- [ ] Nenhuma frase proibida de `references/regras.md` (quilos com prazo, "remédio", "inibe o apetite", "pare a caneta").
- [ ] Prova pela rotina e pelo sentimento da cliente, não por número na balança.
- [ ] Um CTA só.
