---
name: pauta
description: Monta ou revisa a lista de pautas da semana da fábrica de autoridade da aunica. Use quando alguém pedir pautas, temas, ideias de post, o calendário editorial da semana, ou quiser trocar uma pauta que um líder recusou. Aceita o nome de um líder, um período, ou nada (monta a semana inteira dos nove).
---

# Montar pautas

Carregue antes a skill `thevoice-aunica:voz` e leia `_Operacao/Lideres.md` na pasta da fábrica.

## O que descobrir antes de escrever qualquer pauta

1. **Para quem e para quando.** Se o pedido não disser, pergunte. Sem dono, pauta não existe.
2. **O que a pessoa já tem na fila.** Abra a aba `Pautas` do `Pautas.xlsx` dela. Nenhum formato
   repete duas semanas seguidas e nenhuma tese repete no mês.
3. **O que entrou de matéria-prima.** Leia `_Operacao/Caixa_de_entrada.md` e a aba `Minha ficha`
   da pessoa. Uma cena real da caixa de entrada vale mais que qualquer tema de mercado.
4. **O que o mercado está discutindo esta semana.** Só depois disso, e só se sobrar espaço.

## A ordem de prioridade das fontes

Sempre nesta ordem, porque é a ordem que os números do grupo justificam:

1. Cena da semana que alguém contou (caixa de entrada, áudio, conversa)
2. Repertório da ficha da pessoa: um caso antigo, um número que ela pode citar, uma opinião dela
3. Banco de pautas de reserva, em `_Operacao/Banco_de_pautas_inicial.md`
4. Gancho de mercado da semana

Se uma pauta só existe porque saiu uma notícia, ela é a mais fraca da lista. Marque isso na nota.

## O formato de uma pauta

Uma linha na aba `Pautas`, com todas as colunas da fábrica preenchidas. O mínimo viável:

- **ID** iniciais e número sequencial (RJ17, AA09)
- **Semana, data, dia, hora** conforme a cadência da pessoa. Feriado empurra o slot, não cancela
- **Onde publicar** e **amplificação** (`Página aunica, D+2` ou `Nenhuma`)
- **Formato** um dos seis
- **Tema do post** uma frase, não um assunto. "Escalar orçamento é fácil", não "sobre orçamento"
- **Ângulo** o que este post defende, em duas linhas, e de onde sai o material
- **Primeira linha** escrita de verdade, não descrita. É a peça que decide o post
- **Palavras-chave** e no máximo três hashtags de busca real
- **Imagem** o que usar ou, no mais das vezes, que não use nenhuma
- **Arquivo do conteúdo** `S<semana>_<iniciais>_<assunto>.txt`
- **Notas da fábrica** o que ainda falta: uma decisão do líder, um dado, a ficha preenchida

## Checagens antes de entregar a lista

- **Colisão de território.** Duas pessoas na mesma tese na mesma semana é erro de editor, não
  coincidência. Consulte as fronteiras entre territórios vizinhos em `_Operacao/Lideres.md` na pasta da fábrica.
- **Colisão de dia.** Nenhum dia com dois posts, exceto quando os dois autores têm rede
  estabelecida. Quem está construindo rede nunca divide o dia.
- **Rodízio de formato** por pessoa.
- **Cada pauta tem dono, data e primeira linha.** Sem os três, não vai para a planilha.

## Como entregar

Escreva as linhas direto na aba `Pautas` da planilha de cada pessoa e crie o `.txt` correspondente
em `Posts/`, mesmo que ainda não escrito, com tema, ângulo, primeira linha prevista e orientação de
imagem dentro. Nunca deixe um link apontando para arquivo que não existe.

Depois, entregue no chat a lista em texto corrido, uma linha por pauta, com dono e título, para o
a direção editorial revisar de uma olhada só.
