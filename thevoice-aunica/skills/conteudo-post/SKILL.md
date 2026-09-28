---
name: conteudo-post
description: Escreve um post de LinkedIn na voz de um líder da aunica, pronto para copiar e colar. Use quando alguém pedir para escrever, redigir ou revisar um post, quando uma pauta precisar virar texto, ou quando um líder mandar a cena da semana para o slot recorrente de bastidor ou radar. Entrega o texto puro, sem travessão e sem emoji, dentro de 1.300 caracteres.
---

# Escrever o post

Carregue antes a skill `thevoice-aunica:voz` e leia `_Operacao/Lideres.md` na pasta da fábrica para a voz da pessoa.

## Antes de escrever a primeira palavra

1. Leia a linha da pauta na aba `Pautas`: tema, ângulo, primeira linha, formato, imagem.
2. Leia a aba `Minha ficha` da pessoa: voz, cenas, opiniões, números liberados e travas.
3. Verifique as travas. Cliente que não pode ser citado, assunto que a pessoa não quer tocar e
   palavra que ela nunca usaria são condições, não sugestões.

**Se a ficha estiver vazia e a pauta depender dela, pare.** Não invente cena, não invente número e
não invente cliente. Escreva na coluna `Notas da fábrica` o que falta e avise a direção. Um post
inventado é o único erro que a fábrica não consegue desfazer.

## A estrutura

**Primeira linha, sozinha em um parágrafo.** É a única coisa que aparece antes do "ver mais". Ela
carrega a tese ou a tensão. Não é contexto, não é saudação, não é "compartilho com minha rede".

**Segunda linha entrega a cena ou o número.** Onde, quando, com quem, quanto.

**Miolo em parágrafos curtos**, de uma a três linhas, com linha em branco entre eles. No celular o
espaçamento é metade da legibilidade.

**Fecho.** Uma frase que resume a tese, e quando fizer sentido uma pergunta real. Pergunta real é
a que a pessoa quer mesmo ver respondida, não "e você, o que acha?".

## Esqueleto por formato

- **Bastidor:** a cena, o que estava em jogo, o que mudou de rumo, o que ficou. Nome próprio.
- **Eu testei:** o que rodou, o que funcionou, o que quebrou, quanto custou, faria de novo ou não.
- **Contra-tese:** a crença dominante, a evidência que a derruba, o que fazer com isso.
- **O número:** o número, o contexto que o torna significativo, a decisão que ele muda.
- **Erro caro:** o padrão de falha, três vezes que ele apareceu, o sinal antecedente, o antídoto.
- **Presença:** o que é, quando, onde, sobre o quê, e um convite específico.

## Limites e conferências

- **Máximo 1.300 caracteres**, contando espaços. Conte de verdade antes de entregar.
- **Rode uma busca literal por `—`, `–` e emoji.** Sempre, mesmo quando tem certeza.
- Nenhum link no corpo. Se o post tem link, escreva o primeiro comentário separado.
- No máximo três hashtags, só de busca real.
- Sem "impressionante", "incrível", "gamechanger", "veio para ficar", "não veio para substituir".

## Imagem

A regra padrão é **sem imagem**: texto puro performa melhor na maioria destes formatos. Quando
tiver imagem:

- **Card com o número:** tipografia grande, fundo liso, nada de gráfico complexo.
- **Foto real** da cena ou das pessoas, com autorização. **Nunca banco de imagens.**
- **Print da tela** com dados sensíveis borrados.
- **Evento:** foto do palco ou arte oficial.

## Onde salvar

Um arquivo `.txt` em `Posts/`, com o nome que está na coluna `Arquivo do conteúdo`. Só o texto do
post, sem cabeçalho, sem contagem de caracteres, sem nota. O arquivo é para copiar e colar.

Se o post tiver primeiro comentário, coloque-o depois do texto, separado por uma linha com
`--- primeiro comentário ---`.

Depois de salvar, atualize a coluna `Notas da fábrica` daquela linha para "Post escrito. Abra o
link ao lado, leia e responda na coluna SUA RESPOSTA." e acrescente ao conjunto `PRONTOS` se
estiver regerando os arquivos por script.
