
Introdução aos Hooks

Hooks são uma nova adição ao React 16.8. Eles permitem que você use o state e outros recursos do React sem escrever uma classe.

Hooks são retrocompatíveis. Esta página fornece uma visão geral de Hooks para usuários experientes em React. Esta é uma visão geral rápida. Se você se sentir confuso, procure uma caixa amarela com esta:

useState é um Hook (nós vamos falar sobre o que isso significa em instantes). Nós o chamamos dentro de um componente funcional para adicionar alguns states locais a ele. React irá presevar este state entre re-renderizações. useState retorna um par: o valor do state atual e uma função que permite atualizá-lo. Você pode chamar essa função a partir de um manipulador de evento ou de qualquer outro lugar. É parecido com this.setState em uma classe, exceto que não mescla o antigo state com o novo. (Nós iremos mostrar um exemplo comprando useState com this.state em Utilizando o State Hook.)

O Único argumento para useState é o state inicial. No exemplo acima, é 0 porque nosso contador começa do zero. Perceba que diferente de this.state, o state não precisa ser um objeto — apesar de que possa ser se você quiser. O argumento de state inicial é utilizado apenas durante a primeira renderização.

