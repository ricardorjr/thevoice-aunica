---
name: semana
description: A visão do editor sobre a semana inteira da fábrica de autoridade da aunica. Use quando a direção editorial pedir para fechar a semana, montar o planejamento da semana seguinte, ver como está a fila dos nove, cobrar quem não rodou, ou fazer o fechamento mensal de números. Não é a skill do líder: quem é líder e vai produzir o próprio conteúdo usa a skill segunda.
---

# A semana, do lado do editor

Esta skill é do time que dirige a fábrica, não dos autores. Quem vem produzir o próprio conteúdo
usa `thevoice-aunica:segunda`.

**Antes de qualquer coisa, saiba quem está falando.** Abra a seção "A direção editorial" de
`_Operacao/Lideres.md`: são três pessoas e cada uma manda numa parte diferente. Quem dirige não é
quem edita, e confundir os dois é como a fábrica perde a voz das pessoas.

| Quem | O que decide | O que não faz |
|---|---|---|
| O dono da fábrica | Quem entra, o plano do trimestre, o que é prioridade | Não mexe no tom do texto dos outros |
| A editora-chefe | A régua de escrita e de PR. O tom de tudo que sai | **Não reescreve o post de ninguém** |
| A direção de growth | O planejamento junto, e a página da empresa | Não decide sozinha o tema de outro autor |

A regra que sustenta as três: **ajuste de tom sim, reescrita não.** Se a editora reescrever o
post, ele deixa de ser da pessoa, e a fábrica volta a ser uma assessoria produzindo conteúdo
correto e sem dono. Foi exatamente isso que ela existe para acabar.

Carregue antes a skill `thevoice-aunica:voz` e leia `references/estrutura.md`.

## Onde a operação vive

A pasta `FabricaConteudos_online`, dentro do OneDrive da pessoa. O caminho exato muda por máquina:
veja a lista em `references/estrutura.md` da skill `voz`. Trabalhe direto nos arquivos dessa pasta.
Nada é apagado: o que sai vai para `_deletar`.

## O modelo mudou

A fábrica não escreve mais para os nove e manda pronto. **Cada líder roda o plugin na segunda, na
própria máquina, e sai da conversa com o texto dele.** O papel do editor virou outro: dirigir antes
e revisar depois.

| Antes | Agora |
|---|---|
| A fábrica escolhia as pautas dos nove | O planejamento direciona, a pessoa traz a cena, o plugin decide |
| A fábrica escrevia os textos | A conversa de segunda escreve, com a pessoa dentro |
| O líder aprovava um draft | O líder é a fonte do draft |

## Sexta anterior: dirigir

1. Abra `_Operacao/Planejamento_geral.md` com a direção editorial inteira. Trinta minutos.
2. Confira os **temas do trimestre**: continuam valendo ou algum já saturou?
3. Preencha a tabela **direcionado por pessoa** para a semana que vem. Uma linha por
   direcionamento, com o tema em forma de tese e o porquê em uma linha. Sem o porquê, o plugin
   trata como sugestão fraca e a pessoa vai preferir a cena dela, com razão.
4. Atualize **datas que travam**, **cases liberados** e **vetos**. O veto é o campo mais
   esquecido e o mais caro quando falta.
5. Limpe `_Operacao/Caixa_de_entrada.md`: o que já virou post desce para a tabela de baixo.

**Não direcione os nove.** Duas ou três linhas por semana bastam. Se tudo está direcionado, a
cena de ninguém cabe, e a cena é o que faz o post render.

## Segunda: acompanhar, não interferir

1. Leia `_Operacao/Cadastro/` e veja quem rodou e quem não abriu o plugin.
2. Quem não rodou até terça de manhã recebe uma mensagem de uma linha. Não duas.
3. Se alguém adiou um tema direcionado, o plugin escreveu isso no status. Leia a razão antes de
   cobrar: cena real vencendo tema direcionado é o sistema funcionando, não falhando.

## Terça e quarta: a passada da editora-chefe

1. Abra os `.txt` novos das nove pastas `Posts/`.
2. Ajuste **tom**, não conteúdo. O conteúdo é da pessoa e ela responde por ele.
3. Marque o que cita cliente sem estar na tabela de cases liberados. Isso não publica.
4. Rode a conferência mecânica: busca literal por `—`, `–` e emoji em todo arquivo escrito, e
   contagem de caracteres abaixo de 1.300.
5. Devolva com o texto inteiro, nunca um trecho solto, e diga o que mudou e por quê.

## Quinta: a grade

1. Confira que os dois posts de cada dia não são do mesmo território nem do mesmo horário.
2. Confira que a página da empresa compartilhou o que era D+2.
3. Confira que os compartilhamentos entre líderes respeitam a regra do dobro de rede e que cada um
   veio com tese própria escrita.

## Última sexta do mês: números

1. Colete as quatro colunas de métrica das nove planilhas.
2. Compare autoral contra repost, e formato contra formato. É a única comparação que muda decisão.
3. Compare também **quem rodou o plugin toda segunda contra quem rodou em algumas**. É a métrica
   que diz se a fábrica está viva.
4. Escreva o resumo em `_Operacao/Baseline_e_metas.md`: o que subiu, o que caiu, que formato
   aposentar e que pauta repetir.
5. **Não relate número de seguidores.** Sobe com repost e não se converte em nada.

## Ao entregar qualquer coisa à direção editorial

Diga o que foi feito, o que ficou pendente e de quem é cada pendência. Uma pendência sem dono é uma
pendência que não vai acontecer.
