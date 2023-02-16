# Login no Android Studio

Vamos criar um login com banco de dados para
entender o processo de uso do banco de dados no
Android Studio.

Para isso vamos criar um app chamado login.

E, como sempre, a primeira coisa que fazemos é
criar o design da ou das telas.

Devemos sempre trabalhar com bastante cuidado
nossas telas, para que fiquem agradaveis ao
usuario.

E para criar a tela de login, vamos criar uma
nova activity.

Uma activity é uma classe que tem acoplada a ela
uma tela.

---

Como a tela de login é basicamente um elemento
em baixo do outro, vamos usar o RelativeLayout.
Por padrao ao criarmos uma activity, o Android
cria com o constraintLayout.

Poderiamos desenhar a tela de login nesse tipo
de layout, mas seria um pouco mais trabalhoso,
pois teriamos que criar os constraints.
Escolher as cores do meu projeto:

1 - Cor de fundo

2 - Cor de letra

3 - Cor de fundo de campo

Para isso, vamos criar as cores dentro do
arquivo colos.xml. Esse arquivo está dentro da
pasta values.

# PAMII - Interface

Interface é um contrato que fazemos entre nossa classe e quem quizer usar a classe.

Uma interface tem apenas metodos abstratos.

Metodos abstratos nao tem escopo, logo nao tem as chaves.

E esses metodos abstratos tem que ser inseridos na classe que vai implementar essa interface.

# PAMII - Herança

Imaginem que voces foram contratados para criar um
app para um zoologico.

Entao temos que criar classes para esses animais.
Esses animais terao varios atributos, mas alguns
serao para todos, por exemplo:

nome, um peso, uma comida, uma foto

E todos os animais vao poder comer, dormir, se
movimentar, fazerBarulho.

Alguns desses animais farão coisas diferentes, como
o cachorro enterraOsso, a galinha cisca, botaOvo.
Fazer um DC de um Cachorro, Coruja e Galinha
