### Como executar:
O código foi feito na linguagem de programação python, é necessário o uso da biblioteca pandas.
É essencial que você rode o arquivo ipynb com algum editor que suporte notebooks para executar esse código.

### Screencast:
[link no google drive](https://drive.google.com/file/d/1caVE8CHLrXofSCjumX4TjZ4jgco-oIOy/view?usp=share_link)

### Proposta:

Executar um sistema de compras de reservas e assentos em voos, podendo obter informações sobre o voo e assentos disponíveis.

### Conclusões:

Mesmo que o trabalho não tenha seguido a proposta original que combinamos, eu escolhi fazer o trabalho em python e não me arrependi dessa escolha. Eu estou vendo python em deep learning nesse semestre e esse trabalho me ajudou a realmente colocar as coisas na prática, entender melhor a linguagem e a me familiarizar com ela. No começo eu tinha bastante preconceito com python porque já escutei que *"meninas só sabem programar usando isso porque é mais fácil"*, mas finalmente entendi o apelo da linguagem e porque ela é tão procurada.

Eu escolhi trabalhar com a biblioteca pandas porquê: primeiro, o nome parecia interessante, mas, não tem nada a ver com o animalzinho, segundo, descobri que trabalha com dataframes e possui um monte de bibliotecas auxiliares então daria para fazer um trabalho legal com ela.

A biblioteca permite fazer a leitura e escrita com vários tipos de arquivos, e nesse trabalho tentei explorar o XML e o csv. 

O XML começou a ficar extremamente maçante e eu não consegui fazer muita coisa com ele, então, parti para o csv, que foi bem mais fácil de trabalhar. 

Depois que aprendi a manusear um pouco arquivos csv, comecei a pesquisar possíveis funções que eu poderia chamar para resolver questões no código.

Os métodos loc, iloc e isdigit foram os principais métodos que eu utilizei para resolver as questões do trabalho.
Quando o método loc se tornou familiar, consegui montar as lógicas das funções com mais facilidade pois ajuda a localizar os dados que eu preciso facilmente.

Alguns outros métodos já eram familiares pois já tinha visto versões deles em haskell, como o head, tail, length, etc.
Já outros métodos foram novos para mim, como o isdigit e oS conceitos de nan/none e dicionários, foi assustador no começo, mas de acordo com o que eu ia descobrindo, fui me empolgando em achar metódos novos e jeitos diferentes de criar minhas funções.
 
A função to_csv também foi muito importante, pois foi através dela que consegui fazer o buy_seats funcionar e atualizar a tabela de assentos.

Foi um trabalho bem divertido de fazer, apesar de ter mudado toda a proposta de ultima hora e ter enviado super atrasado, sinto que na verdade fiz um progresso imenso, quando voltei para a faculdade no ínicio desse ano, eu já não sabia se iria dar conta de programar mesmo, entrei em 2018 e fui trancando durante vários semestres até me organizar, tomei gosto de fazer código quando comecei a fazer ED e lab2, isso só se fortaleceu até agora em paradigmas, é extremamente prazeroso conseguir criar algo e fico muito feliz de ter espaço para meninas nessa área também. :)

Espero que java seja tão divertido quanto python, estou ansiosa para aprender mais sobre programaçao orientada a objetos <3 

### Dificuldades:

Acabei tendo alguns travamentos em certas funções:
1. Perdi um tempo por uma besteira na função create_flight(), eu estava enviando 7 argumentos para a função, mas ela só esperava 5, até eu notar que esse era o problema, eu já tinha perdido um tempo considerável.

2. Na função get_filled_flight_seats_dict(), display_seats() e get_flight_full foi aonde eu mais senti dificuldade, tive que procurar ajuda de colegas que já passaram pela disciplina para elaborar elas, apesar de ter conseguido pensar sozinha na lógica de tudo, ocorreu o problema de não saber o que usar para o código fazer o que eu queria, então, tive que pedir ajuda.

3. Na função buy_seats() eu tive que pesquisar bastante para entender como funcionava o método to_csv, pois eu não estava conseguindo fazer a atualização da tabela de assentos, mas depois de pesquisar e entender como funcionava, consegui fazer a função funcionar.

4. A questão da coloração de assentos foi algo totalmente novo para mim, nem sabia por onde começar mas percebi que era muito tranquilo, o trabalho acabou me empurrando para testar coisas novas e divertidas também.


### Referências:
+ [Por quê usar a biblioteca pandas?](https://harve.com.br/blog/programacao-python-blog/pandas-python-vantagens-e-como-comecar/)
+ [Como é e como instalar a biblioteca](https://www.alura.com.br/artigos/pandas-o-que-e-para-que-serve-como-instalar)
+ [Como trabalhar com arquivos csv](https://www.w3schools.com/python/pandas/pandas_csv.asp)
+ [Diferentes formas de fazer a leitura de um arquivo csv com pandas](https://medium.com/@henrique.gelatti/diferentes-formas-de-ler-um-arquivo-csv-utilizando-a-biblioteca-pandas-dbeab96555ba)
+ [Como usar os métodos loc e iloc](https://medium.com/horadecodar/data-science-tips-02-como-usar-loc-e-iloc-no-pandas-fab58e214d87)
+ [loc vs iloc](https://www.delftstack.com/pt/howto/python-pandas/pandas-loc-vs-iloc-python/)
+ [Como usar o método isdigit()](https://acervolima.com/python-pandas-series-str-isdigit/)
+ [O quê é nan/none](https://note.nkmk.me/en/python-pandas-nan-none-na/)
+ [Como funciona um dicionário em python](https://blog.somostera.com/desenvolvimento-web/dicionario-python)
+ [Método to_csv](https://www.aprendadatascience.com/blog/fun%C3%A7%C3%A3o-to_csv)
