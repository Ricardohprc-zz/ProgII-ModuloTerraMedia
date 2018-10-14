MODULO TERRAMEDIA

- Ricardo Henrique P. R. Castro - Ricardohcastro@hotmail.com

#Descrição do Trabalho
##	 Construção de Mapas
Este módulo irá criar os mapas que serão futuramente escolhidos pelos construtores das missões dos jogos. 
Criar uma interface visual para construção do Mapa entrando com as informações básicas do Mapa e além disso:
-	Possibilitar inserir os vários tipos de locais no mapa criando objetos das classes de LocalMapa da lista abaixo.  
-	OBS: Futuramente (por outra equipe de projeto) o botão que insere um tipo de local, abrirá um outro painel para criação do local com detalhes.
-	Criar e Inserir objetos trajetos – Completar essa classe, se necessário e prover a criação de trajetos.
-	Completar os detalhes da classe de MapaJogo
-	Preencha os métodos de escrita e leitura dos dados em arquivo, ou banco de dados criando os métodos apropriados, porem sendo arquivo, assumindo que todas as informações serão escritas em uma só linha separada por vírgulas e vá chamando todos os métodos de escrita e leitura dos objetos do mapa (Veja nota geral a parte)

## Classes utilizadas:
  **NÃO MODIFICÁVEIS:**
  ```java
  public abstract class LocalJogo {
  public abstract class LocalMapa extends LocalJogo{
  //Criar opções no mapa para inserção de todos os tipos de locais abaixo
  public class CavernaMapa extends LocalMapa{
  public class CidadeMapa extends LocalMapa{
  public class LagoMapa extends LocalMapa{
  public class RioMapa extends LocalMapa{
  public class TavernaMapa extends LocalMapa{
  ```
 
 **MODIFICAÇÕES ADITIVAS (Somente adicionar atributos, métodos ou código):**
  ```java
  public class MapaJogo {
  public class Trajeto {
  ```
___

##	Construção de Locais de Mapas – CidadeMapa
Este módulo irá somente criar os locais de mapa que serão futuramente escolhidos pelos construtores de mapas. 
Criar uma interface visual para construção do local entrando com as informações básicas do local assim como as informações extras referentes a este tipo de local e eventualmente ao tipo de classe de um local especifico como “Taverna do Bilbo”, por exemplo, teria um atributo nome do dono.
-	Completar os detalhes das classes de local 
-	Novos atributos específicos que pertençam a todos os objetos dessa categoria podem e devem ser acrescentados na classe abstrata LocalMapa
-	Preencha os métodos de escrita e leitura dos dados em arquivo, ou banco de dados criando os métodos apropriados, porem sendo arquivo, assumindo que todas as informações serão escritas em uma só linha separada por vírgulas.
Classes utilizadas:

**NÃO MODIFICÁVEIS:**
```java
public abstract class LocalJogo {
public abstract class LocalMapa extends LocalJogo{
```

**MODIFICAÇÕES ADITIVAS (Somente adicionar atributos, métodos ou código):**
```java
public class CidadeMapa extends LocalMapa{
```

___

##	Construção de Locais de Mapas –CavernaMapa
Este módulo irá somente criar os locais de mapa que serão futuramente escolhidos pelos construtores de mapas. 
Criar uma interface visual para construção do local entrando com as informações básicas do local assim como as informações extras referentes a este tipo de local e eventualmente ao tipo de classe de um local especifico como “Caverna de Smaug”, por exemplo, teria um atributo nome do monstro.
-	Completar os detalhes das classes de local 
-	Novos atributos específicos que pertençam a todos os objetos dessa categoria podem e devem ser acrescentados na classe abstrata LocalMapa
-	Preencha os métodos de escrita e leitura dos dados em arquivo, ou banco de dados criando os métodos apropriados, porem sendo arquivo, assumindo que todas as informações serão escritas em uma só linha separada por vírgulas.
Classes utilizadas:

**NÃO MODIFICÁVEIS:**
```java
public abstract class LocalJogo {
public abstract class LocalMapa extends LocalJogo{
```
**MODIFICAÇÕES ADITIVAS (Somente adicionar atributos, métodos ou código):**
```java
public class CavernaMapa extends LocalMapa{ 
```

___

## Construção de Locais de Mapas – LagoMapa
Este módulo irá somente criar os locais de mapa que serão futuramente escolhidos pelos construtores de mapas. 
Criar uma interface visual para construção do local entrando com as informações básicas do local assim como as informações extras referentes a este tipo de local e eventualmente ao tipo de classe de um local especifico.
-	Completar os detalhes das classes de local 
-	Novos atributos específicos que pertençam a todos os objetos dessa categoria podem e devem ser acrescentados na classe abstrata LocalMapa
-	Preencha os métodos de escrita e leitura dos dados em arquivo, ou banco de dados criando os métodos apropriados, porem sendo arquivo, assumindo que todas as informações serão escritas em uma só linha separada por vírgulas.
Classes utilizadas:

**NÃO MODIFICÁVEIS:**
```java
public abstract class LocalJogo {
public abstract class LocalMapa extends LocalJogo{
```

**MODIFICAÇÕES ADITIVAS (Somente adicionar atributos, métodos ou código):**
```java
public class LagoMapa extends LocalMapa{
```

___

##	Construção de Locais de Mapas –  RioMapa
Este módulo irá somente criar os locais de mapa que serão futuramente escolhidos pelos construtores de mapas. 
Criar uma interface visual para construção do local entrando com as informações básicas do local assim como as informações extras referentes a este tipo de local e eventualmente ao tipo de classe de um local especifico como “Rio de Rivendel”, por exemplo, teria um atributo povo que vive lá.
-	Completar os detalhes das classes de local 
-	Novos atributos específicos que pertençam a todos os objetos dessa categoria podem e devem ser acrescentados na classe abstrata LocalMapa
-	Preencha os métodos de escrita e leitura dos dados em arquivo, ou banco de dados criando os métodos apropriados, porem sendo arquivo, assumindo que todas as informações serão escritas em uma só linha separada por vírgulas.
Classes utilizadas:

**NÃO MODIFICÁVEIS:**
```java
public abstract class LocalJogo {
public abstract class LocalMapa extends LocalJogo{
```

**MODIFICAÇÕES ADITIVAS (Somente adicionar atributos, métodos ou código):**
```java
public class RioMapa extends LocalMapa{
```
 
 ___
 
##	Construção de Locais de Mapas – TavernaMapa
Este módulo irá somente criar os locais de mapa que serão futuramente escolhidos pelos construtores de mapas. 
Criar uma interface visual para construção do local entrando com as informações básicas do local assim como as informações extras referentes a este tipo de local e eventualmente ao tipo de classe de um local especifico como “Taverna do Bilbo”, por exemplo, teria um atributo nome do dono.
-	Completar os detalhes das classes de local 
-	Novos atributos específicos que pertençam a todos os objetos dessa categoria podem e devem ser acrescentados na classe abstrata LocalMapa
-	Preencha os métodos de escrita e leitura dos dados em arquivo, ou banco de dados criando os métodos apropriados, porem sendo arquivo, assumindo que todas as informações serão escritas em uma só linha separada por vírgulas.
Classes utilizadas:

**NÃO MODIFICÁVEIS:**
```java
public abstract class LocalJogo {
public abstract class LocalMapa extends LocalJogo{
```

**MODIFICAÇÕES ADITIVAS (Somente adicionar atributos, métodos ou código):**
```java
public class TavernaMapa extends LocalMapa{
```

