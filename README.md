# Projeto: Criando Artigos Técnicos com ChatGPT e Lexica

### Assunto:
Programação Orientada a Objetos

### Título:
Back-end Developer - Conhecendo o POO

### Capa
Feito com Canva

### Prompt para criação do artigo 
Comporte-se como um escritor de artigos tech back-end e escreva o Artigo atendendo as regras abaixo

{REGRAS}
> No máximo 5 linhas por blocos de explicação
> Me explique de maneira informal, como se eu fosse uma criança de 10 anos

> Os blocos que serão criandos estão abaixo:

- Introdução à Programação Orientada a Objetos em Python
- Classes e Objetos: Os Blocos de Construção do Python
- Encapsulamento: Protegendo Seus Dados em Python
- Herança: Reaproveitando Código com Python
- Polimorfismo: Flexibilidade na Programação com Python
- Cite exemplos com código de Programação Orientada a Objetos
- Faça um call to action para as minhas redes sociais
- Coloque 3 hashtags que façam sentido


### Apresentação
Olá, pessoal! Se você é novo no mundo da programação ou está buscando simplificar seus projetos, este artigo vai te ajudar a entender os fundamentos da POO em Python de uma maneira leve e divertida. Vamos explorar de maneira simples e descomplicada como você pode usar classes e objetos para construir programas mais organizados e poderosos, comparando a POO com blocos de LEGO.



### Conteúdo
Você aprenderá sobre encapsulamento, que é como proteger seus dados para manter tudo em ordem, e herança, que permite reaproveitar código e criar novos objetos com facilidade. Por fim, vamos explorar o polimorfismo, que traz flexibilidade e versatilidade para o seu código, mostrando exemplos práticos para tornar tudo mais claro.

Boa leitura! 🚀✨


## Introdução à Programação Orientada a Objetos em Python
Imagine que você está montando um castelo com blocos de LEGO. Em vez de construir tudo do zero, você usa diferentes tipos de blocos para criar partes do castelo. A Programação Orientada a Objetos em Python funciona assim: você usa "blocos" chamados objetos para criar programas de maneira mais organizada e divertida!


## Classes e Objetos: Os Blocos de Construção do Python
Classes são como moldes para fazer objetos. Pense em uma classe como o molde para um bloco de LEGO específico. Se a classe é um molde para carros, cada carro que você cria com esse molde é um objeto. Assim, você pode construir vários carros com a mesma classe!

### Exemplo de código (Classe e Objeto):
class Cachorro:
  def __init__(self, nome):
    self.nome = nome

meu_cachorro = Cachorro("Rex")
print(meu_cachorro.nome) # Output: Rex

## Encapsulamento: Protegendo Seus Dados em Python
Encapsulamento é como guardar seus brinquedos favoritos em uma caixa segura. Dentro da caixa, você pode manter seus brinquedos (dados) organizados e protegidos. Só algumas partes do seu programa podem brincar com esses brinquedos, garantindo que tudo fique em ordem e seguro.

### Exemplo de código (Encapsulado):
self.__saldo = saldo_inicial # atributo privado

## Herança: Reaproveitando Código com Python
Herança é como passar uma receita de bolo e adicionar seus próprios toques. Se você já tem uma receita básica, pode criar uma nova receita que usa a básica, mas com novos ingredientes. Em Python, você pode criar novas classes que "herdam" funcionalidades de classes existentes, economizando tempo e esforço!

### Exemplo de código (Herança):
class Animal:
  def fazer_som(self):
    return "Som genérico"

class Cachorro(Animal):
  def fazer_som(self):
    return "Au Au"

print(Cachorro().fazer_som()) # Output: Au Au

## Polimorfismo: Flexibilidade na Programação com Python
Polimorfismo é como usar a mesma peça de LEGO para construir coisas diferentes. Por exemplo, a mesma peça pode ser uma parte de um carro ou de um avião, dependendo de como você usa. Em Python, isso significa que você pode usar o mesmo código para fazer coisas diferentes.

### Exemplo de código (Poliformismo):
class Cachorro:
  def fazer_som(self):
    return "Au Au"

class Gato:
  def fazer_som(self):
    return "Miau"

def ouvir_som(animal):
  print(animal.fazer_som())

ouvir_som(Cachorro()) # Output: Au Au
ouvir_som(Gato())   # Output: Miau


### Usando o mesmo código para diferentes animais:
ouvir_som(Cachorro())  # Imprime: Au Au
ouvir_som(Gato())      # Imprime: Miau


## Conclusão
Este artigo foi gerado por inteligência artificial, revisão 100% Humana. Se você gostou desse artigo e quer saber mais sobre programação e Python, não deixe de se conectar comigo no LinkedIn.

Fontes de produção:
Ilustrações de capa: Gerada por Lexica.art e Canva
Conteúdo gerado por: ChatGPT e revisões humanas

#python #backend #poo
