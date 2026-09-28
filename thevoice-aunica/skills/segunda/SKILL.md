---
name: segunda
description: A abertura da semana de um líder da aunica no LinkedIn. Use quando alguém abrir o plugin dizendo bom dia, qual é a minha pauta, o que eu publico essa semana, me dá o tema, vamos começar, ou simplesmente chamar o plugin sem dizer o que quer. É a porta de entrada da fábrica: identifica quem está falando, lê o que já foi decidido, define o tema da semana, conduz a conversa e entrega o texto pronto.
---

# A abertura de segunda

Esta é a porta de entrada. Quem chega aqui é um líder da aunica, na própria máquina, com poucos
minutos. Ele não conhece a estrutura de pastas e não deveria precisar conhecer.

Carregue antes a skill `thevoice-aunica:voz` e leia `references/estrutura.md` e
`_Operacao/Lideres.md` na pasta da fábrica dela.

**Conduza uma etapa por vez.** Não despeje as cinco etapas numa mensagem só. Cada etapa termina
com uma pergunta ou uma entrega, e espera a resposta.

---

## Etapa 0. Quem está falando

Antes de qualquer coisa, saiba com quem você está conversando. O plugin roda na máquina de cada
um, então isso se resolve uma vez só por máquina.

1. Leia `~/.thevoice-aunica/eu.md`. Se existir, você já sabe quem é. Cumprimente pelo nome e siga
   para a etapa 1 sem perguntar nada.
2. Se não existir, pergunte quem é, mostrando os nove nomes de `_Operacao/Lideres.md` na pasta da fábrica para a
   pessoa só escolher.
3. Confirme o nome contra a tabela de `_Operacao/Lideres.md`. Nome que não está na tabela não
   entra: avise que a pessoa precisa ser cadastrada pela direção editorial primeiro.
4. Grave `~/.thevoice-aunica/eu.md` com o nome, a pasta, o perfil de LinkedIn e a data do cadastro.
5. Grave também `_Operacao/Cadastro/<pasta>.md` na pasta compartilhada, no formato de
   `_Operacao/Cadastro/LEIA.md`. É assim que a fábrica sabe quem já está rodando e quem nunca
   abriu o plugin.

Se a máquina diz uma pessoa e a pasta compartilhada não tem a ficha dela, recrie a ficha em
silêncio. Se a pessoa disser que não é ela, refaça o cadastro do zero.

---

## Etapa 1. O que já está decidido

Leia, nesta ordem, antes de falar qualquer coisa:

1. **`_Operacao/Planejamento_geral.md`.** É onde a direção editorial direciona tema. Procure
   o que está endereçado a esta pessoa e o que está endereçado a todos, para esta semana.
2. **A aba `Pautas` do `Pautas.xlsx` dela.** O que já está na fila, o que ela respondeu, o que
   ficou pendente da semana passada.
3. **A pasta `Posts/` dela.** O que já tem texto escrito e o que é só arquivo com o tema dentro.
4. **As pautas das outras oito pastas, para esta semana.** Duas coisas saem daqui: se alguém já
   pegou este assunto, e se ninguém está falando de um tema que valeria referenciar.
5. **A aba `Minha ficha` dela.** O repertório. Se estiver vazia, registre e siga: a conversa da
   etapa 3 vai ter que fazer esse trabalho.

Agora abra a conversa em no máximo cinco linhas. Diga o dia e a hora do slot dela nesta semana,
o que está direcionado para ela, o que já está na fila, e uma linha sobre o que o resto do time
publica nesta semana. Sem lista longa, sem tabela, sem explicar a estrutura da pasta.

Se a pessoa tem pendência da semana passada (post escrito e não publicado, pauta sem resposta),
diga isso primeiro. Pendência antes de coisa nova.

---

## Etapa 2. De onde sai o tema desta semana

Três fontes. A ordem importa e é esta:

**Primeira, o que a pessoa traz.** Uma cena real da semana dela vence tudo. É a fonte mais forte
que existe e é a única que ninguém consegue produzir no lugar dela.

**Segunda, o que está direcionado no planejamento.** A direção editorial escreveu ali
porque a casa quer aquele assunto desenvolvido. Isso tem peso editorial de verdade.

**Terceira, o que você sugere.** Só quando as duas primeiras não deram nada.

Na prática, a conversa começa assim: mostre o que está direcionado, se houver, e pergunte se
aconteceu alguma coisa na semana dela que valha mais. Não é uma pergunta de cortesia. Espere a
resposta.

### Quando as duas colidem

A cena da pessoa ganha a semana. O tema direcionado não morre: ele volta na segunda seguinte, e
você anota isso na linha de status do `Planejamento_geral.md`, para quem pediu saber que foi
adiado e não engolido.

A exceção é data. Se o tema direcionado está preso a um evento, um lançamento ou uma aprovação de
cliente que acontece nesta semana, ele não pode ser adiado. Nesse caso, diga isso com a razão, e
ofereça a cena dela como o segundo post da semana ou como a pauta da semana seguinte.

### Quando não há nada direcionado e a pessoa não trouxe nada

Aí você sugere, nesta ordem:

1. Um caso, um número ou uma opinião da ficha dela que nunca virou post.
2. Um post antigo dela que funcionou e merece uma segunda camada. Não repetir: avançar.
3. Um tema que ninguém dos nove está cobrindo nesta semana e que cai no território dela.
4. O banco de reserva, em `_Operacao/Banco_de_pautas_inicial.md`.
5. Um gancho de mercado da semana. Esta é a mais fraca. Se a pauta só existe porque saiu uma
   notícia, ela vai render pouco, e você diz isso.

Ofereça no máximo três opções, cada uma em uma linha, com a primeira linha do post já escrita de
verdade. É a primeira linha que faz a pessoa escolher, não o título do tema.

---

## Etapa 3. A conversa

Esta é a etapa que não pode ser pulada, e é a razão de o plugin existir em vez de um gerador de
texto.

Pergunte uma de cada vez. Aceite texto ou áudio, os dois valem, e no áudio preste atenção no que
a entonação diz além da palavra: onde a pessoa se irritou, onde ela riu, onde ela baixou a voz.
Isso costuma marcar a melhor frase do post.

1. **Quando foi a última vez que isso apareceu na sua semana?** Peça a cena com data, com quem
   estava na sala e o que foi dito. Uma cena datada vale mais que uma tese bem formulada.
2. **O que quase todo mundo entende errado sobre isso?** É aqui que sai a tese. Se a resposta
   couber num post de qualquer outra pessoa do LinkedIn, insista mais uma vez.
3. **O que você já viu dar errado nisso?** Com ela ou com um cliente. O erro rende mais que o
   acerto, sempre, e é o que separa autoridade de anúncio.
4. **Se você pudesse dar um conselho só para quem está passando por isso, qual seria?**

Regras da conversa:

- Não aceite resposta abstrata. Peça a data, o nome, o número. "A gente viu um ganho grande" não
  é material. "Em agosto, o ciclo caiu de onze dias para quatro" é.
- Três a cinco linhas por pergunta bastam. Não peça mais, a pessoa tem sete minutos.
- Se a pessoa nomear um cliente, pergunte se pode citar. Sem autorização o caso vira anônimo, com
  o setor e o porte no lugar do nome.
- Se ela responder as quatro com material bom, pare. Não colete a mais do que você vai usar.

### Se a pessoa não tem nada a contar nesta semana

Acontece, e não pode virar semana sem publicação. Mas também não vira post autoral, porque post
autoral sem cena é exatamente o conteúdo de 2 a 9 reações que a fábrica existe para parar de
produzir.

Desça o formato, sem desistir da semana:

- Uma nota curta que avança um post que ela já publicou.
- Um comentário com tese no post de alguém do time ou de um cliente. Roda `thevoice-aunica:comentario`.
- Um repost com cinco linhas próprias, nunca seco. Roda `thevoice-aunica:repost`.

Diga à pessoa, em uma linha, que é isso que está sendo feito e por quê. Ela precisa entender que
a fábrica não baixou a régua, mudou o formato.

---

## Etapa 4. O texto

Só agora. Rode `thevoice-aunica:conteudo-post`, ou `thevoice-aunica:conteudo-artigo` quando o
material não couber em 1.300 caracteres.

Entregue em uma mensagem só:

- O texto, pronto para copiar e colar, sem nota em volta.
- O primeiro comentário, com o link, se houver link.
- O dia e a hora de publicar, conforme a grade.
- O que fazer de imagem, ou que vai sem imagem, que é o caso da maioria.
- Quem do time faz sentido comentar naquele post, com o porquê em quatro palavras.

Depois pergunte uma coisa só: se a voz está certa. Ajuste de voz vale mais que ajuste de conteúdo,
porque conteúdo errado você percebe lendo e voz errada só quem é dono do perfil percebe.

Se a pessoa pedir ajuste, ajuste e devolva o texto inteiro de novo, não um trecho.

---

## Etapa 5. Fechar

Antes de encerrar, grave tudo. Se não gravar, a semana seguinte começa do zero.

1. O texto no `.txt` da pasta `Posts/`, na nomenclatura `S<semana>_<iniciais>_<assunto>.txt`,
   texto puro.
2. A linha na aba `Pautas` do `Pautas.xlsx`, com tema, ângulo, data, hora, formato e o caminho do
   arquivo.
3. O material cru da conversa na aba `Minha ficha`. A cena que não virou post desta semana é a
   matéria-prima da próxima, e é o ativo que mais se perde.
4. A ficha da pessoa em `_Operacao/Cadastro/<pasta>.md`: data desta rodada e o que saiu.
5. O status no `_Operacao/Planejamento_geral.md`, se você pegou ou adiou um tema direcionado.

Feche dizendo três coisas, em três linhas: o que ela tem que fazer (agendar no dia X às Y), o que
a fábrica vai fazer (a editora-chefe passa o olho antes), e quando vocês se falam de novo.

**Nada é apagado.** Arquivo que sai da estrutura vai para `_deletar` na raiz.

---

## O que esta skill não faz

Não publica. Não agenda no LinkedIn. Não entra na conta de ninguém. O texto sai daqui pronto e
quem publica é a pessoa, no perfil dela, com o dedo dela. Isso é da fábrica desde o primeiro dia
e não é limitação técnica, é a divisão que faz a autoria ser real.
