# thevoice-aunica

Plugin de Claude para uma fábrica de conteúdo de autoridade no LinkedIn.

Foi construído na [aunica](https://www.aunica.com.br) para resolver um problema específico: um
grupo de líderes com rede somada bem maior que a da página da empresa, publicando quase só
repost. Rede grande e autoria nenhuma.

## A tese

Um post autoral entrega várias vezes mais que um repost, no mesmo perfil, com a mesma rede. E o
melhor post de um grupo costuma sair da menor rede dele, não da maior. O que separa os posts que
rendem dos que não rendem não é alcance, é uma cena real que só aquela pessoa poderia ter contado.

Todo o plugin sai daí. Se um texto poderia ter sido escrito por qualquer outra pessoa do LinkedIn,
ele já falhou, por melhor que esteja.

## Como funciona

Cada pessoa instala na própria máquina e abre na segunda-feira. O plugin identifica quem é, lê o
que a direção editorial planejou, pergunta o que aconteceu na semana dela, e devolve o texto
pronto.

Quinze minutos por semana, uma conversa só.

As três fontes de um tema, nesta ordem:

1. **A cena que a pessoa traz.** Vence tudo. É a única que ninguém produz no lugar dela
2. **O que a direção editorial direcionou** no planejamento da semana
3. **O que o plugin sugere**, do repertório da pessoa, do banco de reserva ou do mercado

Quando as duas primeiras colidem, a cena ganha a semana e o tema direcionado volta na segunda
seguinte, com o adiamento registrado para quem pediu.

## As skills

| Skill | Para quê |
|---|---|
| `segunda` | A porta de entrada. A abertura da semana, de ponta a ponta |
| `voz` | As regras da casa. Carregada antes de qualquer conteúdo |
| `conteudo-post` | Um post de LinkedIn, até 1.300 caracteres |
| `conteudo-artigo` | Artigo de blog, matéria ou newsletter |
| `comentario` | Comentário com tese em post de colega, cliente ou mercado |
| `repost` | Decide se vale compartilhar e escreve as linhas próprias antes |
| `pauta` | Monta ou troca pautas |
| `perfil` | Headline, seção Sobre e diagnóstico de perfil |
| `semana` | A visão do editor: dirigir antes, revisar depois, fechar os números |

## Instalar

```
/plugin marketplace add <owner>/<repo>
/plugin install thevoice-aunica@aunica
```

## O que o plugin não carrega dentro dele

Nada sobre pessoas. Nem nome, nem rede, nem cliente, nem número de post de ninguém.

O plugin é o método. Os dados de quem produz ficam numa pasta privada da operação, que ele lê em
tempo de execução. Sem essa pasta ele não opera, e é assim de propósito: a primeira versão desta
fábrica errou feio ao inferir o território de uma pessoa a partir do currículo dela em vez de
perguntar, e a correção virou regra dura na skill `perfil`.

Se você for usar isto na sua empresa, é essa pasta que você precisa montar. O
`references/estrutura.md` da skill `voz` descreve o formato.

## Regras duras

Valem para post, artigo, repost e comentário:

- Sem travessão e sem emoji, em nenhuma posição
- Nada de repost puro. Se vale repostar, vale escrever cinco linhas próprias antes
- Link no primeiro comentário, nunca no corpo do post
- No máximo 1.300 caracteres e três hashtags
- A primeira linha decide o post. Nunca "compartilho com minha rede" nem "reflexão do dia"

## Licença

MIT.
