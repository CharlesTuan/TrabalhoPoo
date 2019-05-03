## Problema 01

Um objeto é uma instância de uma classe.

## Problema 02

Caracteristicas: Cor, Modelo, força de motor.
Metódos: Ligar, ligar o limpador e freiar.

## Problema 03

Caracteristicas são os Atríbutos e Comportamento são os Métodos.

## Prolema 04

Útil no caso da definição e criação da interface gráfica de programas e programação orientada a objetos torna possível definir objetos de software e estabelecer seus métodos de interação e relações interdependentes entre si.

## Problema 05

Abstração , em computação, é a aplicação do método lógico de abstração na estruturação da descrição dos sistemas informáticos complexos, a fim de facilitar a concepção e manutenção ou o mesmo entendimento.

## Problema 06



Na programação orientada a objetos, uma classe é uma construção de uma linguagem de programação usada como modelo para criar objetos. O modelo inclui atributos e métodos que serão compartilhados por todos os objetos criados a partir da classe.

## Problema 07

Utilizar uma palavra, começando sempre com uma letra maiúscula, sempre que houver outra palavra, deve iniciar com letra maiúscula também, não usando espaço, nem iniciando a variável com número, no singular. 
Padrão camelCase. Ex: Carro, CarroEletrico. 

## Problema 08

CarroEletrico.

## Problema 09

Utilizar uma palavra, começando sempre com uma letra minúscula, sempre que houver outra palavra, deve iniciar com letra maiúscula, exemplo “nomeAluno”.

Padrão camelCase.

## Problema 10

corDeFundo.

## Problema 11

Utilizar uma palavra, começando sempre com uma letra minusculo, sempre que houver outra palavra, deve iniciar com letra maiúscula também, não usando espaço, comumente sendo um verbo. 
Padrão camelCase. Ex: nomeAlunoSala.

## Problema 12

public  Pessoa(){}

## Problema 13

Objeto é uma referência de memória para a instância de uma classe. Ela passa a existir a partir do momento que é instanciado na memória. Deixando de existir quando o programa é encerrado.

## Problema 14

 Objetivo do operador new é criar uma instância na memória para aquela classe.
 
## Problema 15

Um construtor é um "método" utilizado para inicializar os atríbutos da classe. Seu nome deve ser o mesmo da classe. Ex:

public  class  Aluno{

public  Aluno(){}

}

...

Pessoa p =  new Aluno();

## Problema 16

Para esses casos o Java possui um construtor padrão. 
Ex:
public Pessoa{}

## Problema 17

Pessoa p =  new Pessoa();

## Problema 18

O termo **encapsulamento** pode ser usado para se referir a dois conceitos, conectados entre si, mas distintos ou, às vezes, à combinação dos dois:

Um mecanismo de linguagem de programação projetado para limitar o acesso direto aos elementos do objeto .

Uma construção da linguagem de programação que favorece a integração dos métodos (ou outras funções da classe dentro da própria classe.

## Problema 19

 Fazer com que o método ou atributo seja acessado por qualquer outro objeto ou de forma direta.
 
## Problema 20

Fazer com que o método ou atributo seja acessado somente pela própria classe.

## Problema 21

O encapsulamento em uma classe irá definir de que forma será possível acessar um atributo. Se um atributo for privado, só será possível acessar utilizando os métodos da própria classe, caso seja público poderá ser acessada de forma direta.

public  class  Aluno{

private String matricula;

public String getMatricula(){

return  this.matricula;

}

public  void  setMatricula(String matricula){

this.matricula = matricula;

}
}

## Problema 22

Quando o encapsulamento torna um atributo da classe privado, para acessar o valor deste atributo utilizamos um método getter.

public  class  Aluno{

private String matricula;

public String getMatricula(){

return  this.matricula;

}

...

}

## Problema 23

Quando o encapsulamento torna um atributo da classe privado, para definir o valor deste atributo utilizamos um método setter.

public  class  Aluno{

private String matricula;

public  void  setMatricula(String matricula){

this.matricula = matricula;

}

...

}

## Problema 24

1 - Classe, 2- Atributos, 3 - Métodos

## Problema 25

Definir o modificador, sendo +(public), -(private), #(protect), ~(default). O nome do atributo (seguindo o padrão da linguagem) : e o tipo. Ex: - nome: String.

## Problema 26

Modificador nomeDoMetodo(parametro: TipoParametro): TipoRetorno Ex: +getSaldo(): double

## Problema 27

Utilizando o termo << create >> antes do metodo que leva o mesmo nome da clas. Ex: << create >>+Aluno(marca:String, modelo: String, ano: int).

## Problema 28

**Modificador**

"+"

"-"

"#"

"~"

**Cliente**

-nome: String

-email: String

-telefone: int

+getNome(): String

+setNome(nome: String)

+getEmail(): String

+setEmail(email: String)

+getTelefone(): int

+setTelefone(telefone: int)

## Problema 30

public  class  Cliente{

private String nome;

private String email;

private  int telefone;

public String getNome(){

return  this.nome;

}

public  void  setNome(String nome){

this.nome = nome;

}

public String getEmail(){

return  this.email;

}

public  void  setEmail(String email){

this.email = email;

}

public String getTelefone(){

return  this.telefone;

}

public  void  setTelefone(String telefone){

this.telefone = telefone;

}

}

## Problema 31

public  class  Aluno{

private String nome;

public String getNome(){

<![if !supportLists]>a. <![endif]>return  this.nome;

}

public  void  setNome(String nome){

<![if !supportLists]>b. <![endif]>this.nome = nome;

}

}

public  class  Password{

private String value;

public  void  Password(String value){

}

public  boolean  isEqual(Password p){

}

}

public  class  Animal{

private  boolean alive;

public  boolean  isAlive(){

}

private  void  die(){

}

}

