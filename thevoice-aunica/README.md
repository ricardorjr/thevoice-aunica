# thevoice-aunica

Uma fábrica de conteúdo de autoridade no LinkedIn.

O problema que ele resolve não é audiência. É autoria: quando a maior parte do que um grupo de
líderes publica é repost, a rede somada deles não vira autoridade de ninguém.

## Como funciona

Cada líder instala na própria máquina e abre na segunda-feira. O plugin identifica quem é, lê o
que a direção editorial planejou, pergunta o que aconteceu na semana dele, e entrega o texto
pronto para copiar e colar.

**Quinze minutos por semana, uma vez só.**

## As skills

| Skill | Para quê |
|---|---|
| `segunda` | **A porta de entrada.** A abertura da semana de um líder, de ponta a ponta |
| `voz` | As regras da casa. Carregada automaticamente antes de qualquer conteúdo |
| `conteudo-post` | Um post de LinkedIn, até 1.300 caracteres |
| `conteudo-artigo` | Artigo de blog, matéria ou newsletter |
| `comentario` | Comentário com tese em post de colega, cliente ou mercado |
| `repost` | Decide se vale compartilhar e escreve as linhas próprias antes |
| `pauta` | Monta ou troca pautas |
| `perfil` | Headline, seção Sobre e diagnóstico de perfil |
| `semana` | A visão do editor: dirigir antes, revisar depois, fechar os números |

## As três fontes de um tema

Nesta ordem, porque é a ordem que os números justificam:

1. **A cena que a pessoa traz.** Vence tudo. É a única que ninguém produz no lugar dela
2. **O que a direção editorial direcionou** em `_Operacao/Planejamento_geral.md`
3. **O que o plugin sugere**, do repertório da pessoa, do banco de reserva ou do mercado

Quando as duas primeiras colidem, a cena ganha a semana e o tema direcionado volta na segunda
seguinte, com o adiamento registrado para quem pediu.

## O que ele não faz

Não publica, não agenda, não entra na conta de ninguém. O texto sai pronto e quem publica é a
pessoa, no perfil dela. Isso não é limitação técnica: é o que faz a autoria ser real.

## A pasta da operação

O plugin não carrega dado de pessoa nenhuma dentro dele. Nome, território, cadência, voz e
planejamento ficam numa pasta privada que ele lê em tempo de execução. Sem ela, o plugin não
opera, de propósito.

O formato dessa pasta está em `skills/voz/references/estrutura.md`.

Nada é apagado. O que sai da estrutura vai para `_deletar` na raiz.
