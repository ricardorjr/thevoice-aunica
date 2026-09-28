# A pasta e o ciclo

## Onde achar a pasta

A pasta vem de um SharePoint e cada pessoa adiciona como atalho no próprio OneDrive, então o
caminho muda de máquina para máquina. **Procure nesta ordem e pare no primeiro que existir:**

```
~/Library/CloudStorage/OneDrive-Aunica/FabricaConteudos_online     macOS
~/Library/CloudStorage/OneDrive-*/FabricaConteudos_online          macOS, outro nome de tenant
~/OneDrive - Aunica/FabricaConteudos_online                        Windows
~/OneDrive*/FabricaConteudos_online                                Windows, outro nome
~/FabricaConteudos_online                                          atalho solto na home
```

Se nenhum existir, **não invente e não siga**. Diga à pessoa que a pasta não está na máquina
dela, e mande ela abrir o link do SharePoint no navegador e clicar em "Adicionar atalho a Meus
arquivos". Sem a pasta, o plugin não tem o que ler.

Se a pasta existir mas os arquivos vierem vazios ou não abrirem, eles estão só na nuvem. A pessoa
precisa clicar com o botão direito na pasta e escolher "Sempre manter neste dispositivo".

```
LEIA-ME.html            visão geral da operação
_Operacao/              o cérebro da fábrica
    Planejamento_geral.md      direção editorial. Só a direção escreve
    Caixa_de_entrada.md        matéria-prima crua, qualquer um escreve
    Banco_de_pautas_inicial.md reserva, três teses por pessoa
    Lideres.md                 registro: nome, LinkedIn, cargo, pasta
    Cadastro/                  uma ficha por pessoa, criada pelo plugin
    thevoice-aunica.plugin     o plugin que cada um instala na própria máquina
_deletar/               fila de descarte, nada é apagado direto
<Nome_Sobrenome>/       nove pastas, três objetos cada
    COMECE_AQUI.html
    Pautas.xlsx
    Posts/
```

Os três primeiros arquivos de `_Operacao` são lidos pelo plugin toda segunda, nesta ordem:
planejamento, caixa de entrada, banco. É de lá que sai o tema quando a pessoa não trouxe um.

## Os três objetos de cada líder

**`COMECE_AQUI.html`** é o roteiro. Sete passos numerados: 01 arrumar o perfil, 02 preencher a
ficha, 2b construir rede (só para quem tem rede pequena), 03 validar as pautas, 04 aprovar o post,
05 agendar e publicar, 06 compartilhar e responder, 07 anotar os números. Tem a tabela das pautas
com link relativo para cada texto.

**`Pautas.xlsx`** tem sete abas: Comece por aqui, Pautas, Minha ficha, Ajustar o LinkedIn,
Publicar e agendar, Compartilhar e responder, Regras de escrita.

A aba **Pautas** tem 22 colunas. Só as amarelas são do líder: `SUA RESPOSTA` (dropdown com
Aprovado, Alterar tema, Trocar data, Não publicar, Aguardando), `SEU COMENTÁRIO` e as quatro de
métrica no fim (impressões, reações, comentários, visualizações de perfil). A coluna
`Arquivo do conteúdo` é um hyperlink para o `.txt`. A coluna `Notas da fábrica` é onde o editor
diz o que falta em cada linha.

A aba **Minha ficha** é o combustível: voz observada, dez cenas, cinco opiniões, números que podem
ser usados, travas e jeito de falar. Sem ela a fábrica só produz conteúdo correto e esquecível.

**`Posts/`** tem um `.txt` por pauta, sempre. Nomenclatura `S01_RJ_assunto.txt`: semana, iniciais,
assunto. Texto puro, sem notas em volta, pronto para copiar e colar. Post ainda não escrito existe
como arquivo mesmo assim, trazendo tema, ângulo, primeira linha prevista e orientação de imagem.

## O ciclo da semana

| Quando | Quem | O quê |
|---|---|---|
| Sexta anterior | A direção editorial | Fecha o `Planejamento_geral.md`: o que a casa quer na semana |
| **Segunda** | **Cada líder, sozinho** | **Abre o plugin na própria máquina e roda a skill `segunda`. Sai de lá com o texto pronto** |
| Terça e quarta | A editora-chefe | Passa o olho no que foi produzido, ajusta tom, marca o que precisa de aprovação de cliente |
| Segunda a quinta | Cada líder | Publica no seu slot da grade, dois posts por dia entre todos |
| Todo dia | Todos | Dois ou três comentários por semana nos posts uns dos outros, no mesmo dia da publicação |
| D+2 | Quem cuida da página | A página da empresa compartilha |
| Última sexta do mês | Todos | Trinta minutos de leitura de números |

A skill `segunda` é a porta de entrada. Quem abre o plugin sem dizer o que quer cai nela.

**Quinze minutos por semana por líder**, todos na segunda, numa conversa só. Ninguém do time
escreve o texto. O que o líder dá é a cena, a tese e o aval, e é a parte que ninguém consegue
fazer no lugar dele.

## Regra de exclusão

Nada é apagado direto. Arquivo ou pasta que sai da estrutura vai para `_deletar` na raiz, com o
nome de origem preservado. Quem esvazia é a direção editorial.
