# Programação Orientado a Objeto - POO

# Table of Contents

1. [CLASSE](https://github.com/AntonioCarioca/Programa-o-Orientada-Objetos---POO/edit/main/README.md#classe)

2. [OBJETO](https://github.com/AntonioCarioca/Programa-o-Orientada-Objetos---POO/edit/main/README.md#objeto)

3. [ATRIBUTO](https://github.com/AntonioCarioca/Programa-o-Orientada-Objetos---POO/edit/main/README.md#atributo)

4. [MÉTODO](https://github.com/AntonioCarioca/Programa-o-Orientada-Objetos---POO/edit/main/README.md#m%C3%A9todo)

5. [Pilares da POO](https://github.com/AntonioCarioca/Programa-o-Orientada-Objetos---POO/edit/main/README.md#pilares-da-poo)

	1. [ABSTRAÇÃO](https://github.com/AntonioCarioca/Programa-o-Orientada-Objetos---POO/edit/main/README.md#abstra%C3%A7%C3%A3o)

	2. [ENCAPSULAMENTO](https://github.com/AntonioCarioca/Programa-o-Orientada-Objetos---POO/edit/main/README.md#encapsulamento)
	
		1. [NÍVEIS DE ACESSO](https://github.com/AntonioCarioca/Programa-o-Orientada-Objetos---POO/edit/main/README.md#n%C3%ADveis-de-acesso)
	
		2. [GETTER/SETTER](https://github.com/AntonioCarioca/Programa-o-Orientada-Objetos---POO/edit/main/README.md#gettersetter)

	3. [HERANÇA](https://github.com/AntonioCarioca/Programa-o-Orientada-Objetos---POO/edit/main/README.md#heran%C3%A7a)
		
		1. [CLASSE/MÉTODO ABSTRATOS](https://github.com/AntonioCarioca/Programa-o-Orientada-Objetos---POO/edit/main/README.md#classem%C3%A9todo-abstratoa)

	4. [POLIMORFISMO](https://github.com/AntonioCarioca/Programa-o-Orientada-Objetos---POO/edit/main/README.md#polimorfismo)
	
		1. [INTERFACE](https://github.com/AntonioCarioca/Programa-o-Orientada-Objetos---POO/edit/main/README.md#interface)

6. [STATIC](https://github.com/AntonioCarioca/Programa-o-Orientada-Objetos---POO/edit/main/README.md#static)

7. [CONSTRUTOR](https://github.com/AntonioCarioca/Programa-o-Orientada-Objetos---POO/edit/main/README.md#construtor)

## CLASSE

>*A classe é a forma mais básica de definir apenas uma única vez como devem ser todos os objetos criados a partir dela em vez de definir cada objeto separadamente.*

>*Assim, uma classe também pode ser definida como uma abstração de uma entidade, seja física(pessoa,carro,ect) ou conceitual(venda,estoque,etc) do mundo real.*

## OBJETO

>*Um objeto é a representação de um conceito/entidade do mundo real, que pode ser físico ou conceitual e possui um significado bem definido para um determinado software.*

>*Imagine um software de Fluxo de Caixa, logo um conceito que ele teria de manipular seria uma* ***conta.*** *Então deveríamos criar uma classe chamada* ***Conta*** *e, a partir dela, objetos que representariam uma* ***Conta de Água,*** ***Conta de Energia,*** ***Conta de Telefone.***

## ATRIBUTO

>*Atributo é o elemento de uma classe, responsável por definir sua estrutura de dados. O conjunto destes será responsável por representar suas características e farão dos objetos criados a partir da classe.*

## MÉTODO

>*Método é uma porção de código(sub-rotina) que é disponibilizada pela classe. Este é executado quando é feita uma requisição a ele. Um método serve para identificar quais serviços,ações,que a classe oferece. Eles são responsáveis por definir e realizar um determinado comportamento.*

>*Para facilitar o processo de identificação dos métodos de uma classe, podemos pensar em verbos.*

## Pilares da POO

### ABSTRAÇÃO

>*Consiste em extrair entidades do mundo real para dentro do código seguindo a fio suas responsabilidades. Um objeto deve ter uma identidade única dentro de um sistema, não podendo haver repetições.*

>*Ao criar um estoque de itens em uma loja virtual, um produto teria como “qualidade” ou “características” um “nome”, “categoria”, “quantidade”, etc.*

### ENCAPSULAMENTO

>*Encapsular os dados de uma aplicação significa evitar que estes sofram acessos indevidos. Para isso, é criada uma estrutura que contém métodos que podem ser utilizados por qualquer outra classe, sem causar inconsistências no desenvolvimento de um código.*

>Na prática, isso é feito por meio de dois métodos: os getters e os setters.

####	NÍVEIS DE ACESSO

>*Propriedade e métodos podem ter modificadores de acesso que controlam onde podem ser acessados.*
> 
>*Existem três modificadores de acesso:*
>
>1.	*Public: a propriedade ou método pode ser acessado de qualquer lugar. Este é o padrão.*
>
>2. *Protected: a propriedade ou método pode ser acessado dentro da classe e por classes derivadas dessa classe.*
>
>3. *Private: a propriedade ou método pode SOMENTE ser acessado dentro da propria classe.*

#### GETTER/SETTER

>*Os métodos getter e setter são utilizadas quando precisamos restringir o acesso direto às variáveis pelos usuários finais. Getters e setters são métodos usados para definir ou recuperar os valores das variáveis, normalmente privadas.*
>
>*Assim como o nome sugere, um método getter é uma técnica que obtém ou recupera o valor de um objeto. Além disso, um método de setter é uma técnica que define o valor de um objeto.*

### HERANÇA

> *É o relacionamento entre classes em que uma classe chamada de subclasse (classe filha,classe derivada) é uma extensão, de outra classe chamada de superclasse (classe pai, classe mãe). Devido a isto, a subclasse consegue reaproveitar os atributos e métodos dela. Além dos que venham a ser herdados, a subclasse pode definir seus próprios membros.*

#### CLASSE/MÉTODO ABSTRATO(A)

> *São classes que representam conceitos tão genéricos que não vale a pena trabalhar com elas diretamente. Por não valer a pena trabalhar diretamente com elas, não podem ser instânciadas.*
> 
> *Ao herdar de uma classe abstrata, o método da classe filha deve ser definido com o mesmo nome e o mesmo ou um modificador de acesso menos restrito. Portanto, se o método abstrato for definido como protegido, o método da classe filha deverá ser definido como protegido ou público, mas não como privado.*
> 
> *Além disso, o tipo e o número de argumentos obrigatórios devem ser os mesmos. No entanto, as classes filhas podem ter argumentos opcionais adicionais.*

### POLIMORFISMO

>*Polimorfismo significa "muitas formas" e ocorre quando temos muitas classes relacionadas entre si por herança. Como explicado anterior; Herança nos deixa herdar atributos e métodos de outra classe. Polimorfismo usa esses métodos para executar tarefas diferentes. Isso nos permite executar um único ação de maneiras diferentes.*
>
>*Por exemplo, pense em uma superclasse chamada Animal que tem um método chamado animalSound(). Subclasses de animais podem ser porcos, gatos, cães, pássaros - e eles também têm sua própria implementação de um som animal (, o porco oinks e o gato mia, etc. ).*

#### INTERFACE

>*As interfaces são padrões definidos através de contratos ou especificações. Um contrato define um determinado conjunto de métodos que serão implementados nas classes que assinarem esse contrato. Uma interface é 100% abstrata, ou seja, os seus métodos são definidos como abstract, e as variáveis por padrão são sempre constantes (static final).*
>
>*A interface é semelhante às classes abstratas. A diferença entre interfaces e classes abstratas é:*
>
>* *As interfaces não podem ter propriedades, enquanto as classes abstratas podem,*
>
>* *Todos os métodos de interface devem ser públicos, enquanto os métodos de classe abstrata são públicos ou protegido,*
>
>* *Todos os métodos em uma interface são abstratos, portanto não podem ser implementados no código e a palavra-chave abstract não é necessária*
>
>* *As classes podem implementar uma interface enquanto herdam de outra classe ao mesmo Tempo.*

## STATIC

> *É usado para definir que um método ou atributo em uma classe é estático. Isso significa que aquele método/atributo pertence à classe e não à uma instância dela e, por isso, pode ser acessado sem instânciar um novo objeto.*
> 
> *É importante deixar claro que um valor estático pertence à classe e não às instâncias, mas podem ser usados dentro da classe via self.*
> 
> *Isso é muito interessante para valores que você queira disponíveis para toda a aplicação, por exemplo. Se eles mudarem na classe uma única vez toda a aplicação tem acesso aos mesmos valores.*

## CONSTRUTOR

> *Construtor em linguagens de programação orientadas a objeto é um método chamado assim que uma nova instância do objeto for criada. Tal método geralmente é responsável pela alocação de recursos necessários ao funcionamento do objeto além da definição inicial das variáveis de estado (atributos).*
