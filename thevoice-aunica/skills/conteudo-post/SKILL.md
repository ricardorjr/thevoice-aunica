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

**Fecho.** Uma frase que resume a tese. **A pergunta ao leitor é uma das opções de fecho, não o
fecho padrão.** Use no máximo em um post a cada três, e só quando a pessoa quiser mesmo ver a
resposta. Nunca "e você, o que acha?".

Os outros fechos, que quase nunca são usados e rendem igual ou mais:

- **A frase seca.** Afirma e para. "O custo de adiar nunca é zero, ele só muda de lugar."
- **A consequência.** O que acontece com quem não fizer nada.
- **O que a pessoa vai fazer.** "Na próxima renovação eu vou pedir isso por escrito."
- **A admissão.** O que ela ainda não resolveu. É o fecho mais raro e o que mais gera comentário.
- **O convite específico.** Só quando existe uma coisa concreta para responder.

## O teste de fôrma

Antes de entregar, abra os três últimos posts dessa pessoa e os posts dos outros na mesma semana.

**Se dois deles tiverem o mesmo esqueleto, reescreva o seu.** Esqueleto é a sequência de blocos:
abertura com número, lista de três situações, bloco de três perguntas, fecho interrogativo. Dois
textos com conteúdo diferente e esqueleto igual soam como o mesmo texto.

Os vícios que já apareceram nesta fábrica e precisam ser vigiados:

| Vício | Limite |
|---|---|
| Fecho em pergunta reflexa ao leitor | No máximo um a cada três posts, e nunca dois na mesma semana entre pessoas diferentes |
| Bloco de "três perguntas que eu faço" | No máximo um a cada quatro posts do grupo inteiro |
| Lista de três situações que se repetem | Não duas semanas seguidas na mesma pessoa |
| Abrir com número grande | Alterne com abrir por cena, por frase seca ou por pergunta |

**Cuidado para não ler esta tabela ao contrário.** O limite é sobre a **pergunta reflexa**, a que
aparece no fim porque o texto acabou e alguém precisa perguntar alguma coisa. Não é sobre o
registro de conversa, que a casa quer em todos os posts. Um texto pode ser inteiro convidativo,
admitir o que não sabe e deixar o leitor com o que dizer, sem terminar em interrogação nenhuma.
Pergunta de verdade, feita porque a pessoa quer mesmo a resposta, nunca foi o problema.

Variar o esqueleto é tão importante quanto variar o formato. O rodízio dos seis formatos não
resolve isso sozinho: dá para escrever um Bastidor e uma Contra-tese com exatamente a mesma
arquitetura, e foi o que aconteceu na primeira semana.

## Esqueleto por formato

- **Bastidor:** a cena, o que estava em jogo, o que mudou de rumo, o que ficou. Nome próprio.
- **Eu testei:** o que rodou, o que funcionou, o que quebrou, quanto custou, faria de novo ou não.
- **Contra-tese:** a crença dominante, a evidência que a derruba, o que fazer com isso.
- **O número:** o número, o contexto que o torna significativo, a decisão que ele muda.
- **Erro caro:** o padrão de falha, três vezes que ele apareceu, o sinal antecedente, o antídoto.
- **Presença:** o que é, quando, onde, sobre o quê, e um convite específico.

## Limites e conferências

- **Faixa de casa: 1.800 a 2.200 caracteres**, contando espaços. Conte de verdade antes de
  entregar. Texto longo entrega mais que texto curto, então na dúvida entre cortar e deixar,
  deixe. Abaixo de 1.500, releia: quase sempre falta a cena ou falta a conclusão. Nunca corte
  uma cena para caber num número, e nunca encha linguiça para chegar nele. **Carrossel é a
  exceção:** legenda de 0 a 100 caracteres, porque quem fala são os slides.
- **Linha em branco entre todo parágrafo**, sem exceção.
- **Rode uma busca literal por `—`, `–` e emoji.** Sempre, mesmo quando tem certeza.
- Nenhum link no corpo. Se o post tem link, escreva o primeiro comentário separado.
- No máximo três hashtags, só de busca real.
- Sem "impressionante", "incrível", "gamechanger", "veio para ficar", "não veio para substituir".

## Formato

**Carrossel, um a cada quatro ou cinco posts da pessoa.** É o formato que entrega mais e conversa
mais ao mesmo tempo, e é onde vale gastar trabalho. Quatro a seis páginas, uma ideia por página,
tipografia grande, a tese na primeira. A legenda é curta.

**Imagem solta** quando ela acrescenta: um número que merece card, uma foto real de cena ou evento
com autorização, um print com dado sensível borrado. **Nunca banco de imagens.**

**Texto puro** é o padrão e continua funcionando. Não é inferior a imagem solta.

**Enquete quase nunca**, e nunca para buscar alcance. Ela entrega muito e conversa pouco. O único
uso que a casa aceita é como pesquisa: pergunte o que você não sabe, espere fechar, e escreva o
post em cima do resultado. Uma a cada dois meses por pessoa, no máximo.

Os números por formato estão em `voz/references/linkedin.md`.

## Onde salvar

Um arquivo `.txt` em `Posts/`, com o nome que está na coluna `Arquivo do conteúdo`. Só o texto do
post, sem cabeçalho, sem contagem de caracteres, sem nota. O arquivo é para copiar e colar.

Se o post tiver primeiro comentário, coloque-o depois do texto, separado por uma linha com
`--- primeiro comentário ---`.

Depois de salvar, atualize a coluna `Notas da fábrica` daquela linha para "Post escrito. Abra o
link ao lado, leia e responda na coluna SUA RESPOSTA." e acrescente ao conjunto `PRONTOS` se
estiver regerando os arquivos por script.
