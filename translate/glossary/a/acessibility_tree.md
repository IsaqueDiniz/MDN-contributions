[Accessibility tree](https://developer.mozilla.org/en-US/docs/Glossary/Accessibility_tree)
# Accessibility tree

The accessibility tree contains accessibility-related information for most HTML elements.

Browsers convert markup into an internal representation called the DOM tree. The DOM tree contains objects representing all the markup’s elements, attributes, and text nodes. Browsers then create an accessibility tree based on the DOM tree, which is used by platform-specific Accessibility APIs to provide a representation that can be understood by assistive technologies, such as screen readers.

There are four things in an accessibility tree object:

## name
How can we refer to this thing? For instance, a link with the text "Read more" will have "Read more" as its name (find more on how names are computed in the Accessible Name and Description Computation spec).
##description
How do we describe this thing, if we want to provide more desciption beyond the name? The description of a table could explain what kind of information the table contains.
## role
What kind of thing is it? For example, is it a button, a nav bar, or a list of items?
## state
Does it have a state? Examples include checked or unchecked for checkboxes, and collapsed or expanded for the <summary> element.
Additionally, the accessibility tree often contains information on what can be done with an element: a link can be followed, a text input can be typed into, etc.

While still in draft form within the Web Incubator Community Group, the Accessibility Object Model (AOM) intends to incubate APIs that make it easier to express accessibility semantics and potentially allow read access to the computed accessibility tree.

***
# Árvore de acessibilidade

A **árvore de acessibilidade** contém informação relacionada à acessibildade para a maioria dos elementos HTML.

Navegadores convertem a marcação em uma representação interna chamada *árvore do DOM*. A árvore do DOM contém objetos representando todas as marcações de elementos, atributos e nós de texto. Os navegadores, então, criam uma árvore de acessibilidade baseada na árvore do DOM, a qual é usada por APIs específicas de plataforma para fornecer uma representação que possa ser entendida por tecnologias assistivas, como leitores de tela.

Há quatro coisas em um objeto da árvore de acessibilidade:

## nome
Como podemos nos referir a esse objeto? Por exemplo, um link com o texto "Leia mais" terá "Leia mais" como seu atriuto name (saiba mais como os nomes são computados em "Nomes acessíveis e descrição de especificações de computação")

## description
Como podemos descrever esse objeto se quisermos fornecer mais descrição além do nome? A descrição de uma tabela pode explicar que tipo de informação ela contém.

## função
Que tipo de objeto é esse? Por exemplo, se é um botão, uma barra de navegação ou uma lista de items?

## estado
Tem um estado? Os exemplos incluem *checked* ou *unchecked* para *checkboxes*, e *collapsed* ou *expanded* para o elemento `<summary>`·

Adicionalmente, a árvore de acessibilidade frequentemente contém informação sobre o que pode ser feito com um elemento: um link pode ser seguido, uma entrada de texto pode ser digitada, entre outras coisas.

Enquanto continua em forma de rascunho na *Web Incubator Community Group*, o Modelo de Objeto de Acessibilidade( Accessibility Object Model, AOM, em inglês), tem a intenção de incubar APIs que facilitam expressar a semântica de acessibilidade e potencialmente permitir acesso de leitura à árvore de acessibilidade computada.