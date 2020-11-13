[Alignment subject](https://developer.mozilla.org/pt-BR/docs/Glossary/Alignment_Subject)
# Alignment subject
In CSS Box Alignment the alignment subject is the thing (or things) being aligned by the property.

For justify-self and align-self, the alignment subject is the margin box of the box the property is set on, using the writing mode of that box.

For justify-content and align-content, the writing mode of the box is also used. The definition of the alignment subject depends on the layout mode being used.

### Block containers (including table cells)
The entire content of the block as a single unit.
### Multicol containers
The column boxes, with any spacing inserted between column boxes added to the relevant column gaps.
### Flex containers
For justify-content, the flex items in each flex line.
For align-content, the flex lines. Note, this only has an effect on multi-line flex containers.
### Grid containers
The grid tracks in the appropriate axis, with any spacing inserted between tracks added to the relevant gutters. Collapsed gutters are treated as a single opportunity for space insertion.
***
# Tópico de alinhamento

No Alinhamento de Box do CSS, o tópico (assunto) de alinhamento é a coisa (ou coisas) que está sendo alinhada pelas propriedade.

Para o justify-self e aligj-self, o tópico de alinhamento é a caixa de margem da caixa em que a propriedade está definida, usando o modo de escrita dessa caixa.

Para o justify-content e align-content, o modo de escrita da caixa também é usado. A definição do tópico de alinhamento depende do modo de layout que está sendo usado.

### Contêineres de bloco (incluindo células de tabela)
Todo o conteúdo do bloco como uma única unidade.

### Contêineres de colunas múltiplas (multicol)
As caixas de colunas, com qualquer espaçamento inserido entre as caixas de colunas adicionado às lacunas de coluna relevantes.

## Contêiner flexíveis

Para justify-content, os items flexíveis em cada linha flexível.
Para align-content, as linhas flexíveis. Perceba que, isso só tem efeito em Contêineres flexíveis de múltiplas linhas.

## Contêineres grid
As trilhas do grid nos eixos apropriados, com qualquer espaçamento inserido entre traçados adicionado à gutters relevantes. Gutters colapsados são tratados como uma oportunidade única para inserção no espaço.