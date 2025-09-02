# Sistema-de-Gerenciamento-de-Conteudo-Digital
Sistema de Gerenciamento de Conteúdo Digital
 Este sistema permite que o usuário cadastre, visualize, pesquise e remova diferentes tipos de
 conteúdo digital, como Filmes, Livros e Músicas. A aplicação possui uma interface gráfica amigável
 utilizando a biblioteca Tkinter, e aplica os princípios da Programação Orientada a Objetos para
 organizar e estruturar o código de forma modular e extensível.
 Pilares da Programação Orientada a Objetos aplicados:
 1. Abstração:
 Foi criada uma classe abstrata chamada ConteudoDigital que define uma estrutura base para
 qualquer conteúdo digital, exigindo que todas as subclasses implementem o método exibir_info.
 2. Encapsulamento:
 As propriedades e métodos relacionados a cada tipo de conteúdo (como Filme, Livro e Música) são
 encapsulados dentro de suas respectivas classes. Isso isola a lógica de cada tipo de conteúdo,
 facilitando a manutenção.
 3. Herança:
 As classes Filme, Livro e Música herdam da classe base ConteudoDigital. Isso permite compartilhar
 atributos comuns (como título e ano) e também garantir que todas implementem a mesma interface
 (exibir_info).
 4. Polimorfismo:
 O método exibir_info é implementado de maneira diferente em cada subclasse (Filme, Livro e
 Música), permitindo que objetos dessas classes sejam tratados de forma uniforme, mas
apresentem comportamentos distintos quando esse método é chamado.
 Com esses pilares aplicados, o sistema é facilmente expansível, reutilizável e organizado,
 permitindo a adição de novos tipos de conteúdo digital com mínima alteração no código existente.
