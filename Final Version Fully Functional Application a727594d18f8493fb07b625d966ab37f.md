# Final Version: Fully Functional Application

---

### Discentes

### Docente

André Gustavo Jucovski

Kamila Rios H. Rodrigues

Armando Akio Morey Filho

### Disciplina

### Instituição

SCC-0219 Introdução ao Desenvolvimento Web

Instituto de Ciências Matemáticas e de Computação - USP

---

## **Introdução**

Este projeto visa aplicar os conhecimentos obtidos durante a realização da disciplina de Introdução ao Desenvolvimento Web, a partir da implementação de um *E-commerce*, tanto na elaboração do *front-end*  quanto do *back-end.*

Partiu-se do conceito de uma empresa fictícia ligada a produtos orgânicos, mercado o qual cresce continuamente em nosso país, em razão da alta divulgação dos efeitos adversos dos agrotóxicos em nossa saúde e ao meio ambiente, consequentemente a denominamos de *YBY*, que no Tupi-Guarani significa terra. 

A YBY consiste em conectar a agriculta familiar diretamente com o consumidor final, sem a necessidade de mercados ou outros mediadores. Desta forma assegurando uma alta qualidade dos produtos, aumentando a renda dos produtores sem que este fator influencie no preço para nossos clientes.

O *front-end* foi desenvolvido com *Vue.js* associado ao *Bootstrap 4,* já no *back-end* foi utilizado C# e noSQL.

## Execução da aplicação

Clone ou realize o download do repositório presente no seguinte link [https://github.com/gicutieri/trab_web](https://github.com/gicutieri/trab_web)

```bash
git clone git@github.com:gicutieri/trab_web.git
```

Instale o Node.js

```bash
npm install
```

Compile e rode o server

```bash
npm run serve
```

Em relação ao back-end, a chave de acesso ao banco de dados é

```bash

```

## Identidade visual

Toda a identidade visual foi concebida no *software Figma,* utilizando a paleta de cores presente na Figura 1.

É válido ressaltar, que utilizou-se a extensão *Colorblindy* do navegador *Google Chrome* para averiguar se o contraste da informação estava visível para todas as derivações de daltonismo.

Além disso a ferramenta *Color Tool* do website *Material Design* foi amplamente utilizada para assegurar a legibilidade do texto em relação a cor do *backgroud.* 

![Final%20Version%20Fully%20Functional%20Application%20a727594d18f8493fb07b625d966ab37f/Paleta_YBY.png](Final%20Version%20Fully%20Functional%20Application%20a727594d18f8493fb07b625d966ab37f/Paleta_YBY.png)

Figura 1: Paleta de cores utilizada no website

## Telas do E-commerce

### HOME

A home se baseia num *Carousel* exibindo informações importantes, produtos em destaque que podem ser escolhidos através das configurações de administrador. Apresenta também um diagrama do ciclo do produto, além de um texto sobre a empresa.

![Final%20Version%20Fully%20Functional%20Application%20a727594d18f8493fb07b625d966ab37f/Untitled.png](Final%20Version%20Fully%20Functional%20Application%20a727594d18f8493fb07b625d966ab37f/Untitled.png)

Figura 2 - Home

### LOJA

Apresenta todos os produtos catalogados, além de apresentar um sistema de buscas *single page,* que está completamente funcional.

![Final%20Version%20Fully%20Functional%20Application%20a727594d18f8493fb07b625d966ab37f/Untitled%201.png](Final%20Version%20Fully%20Functional%20Application%20a727594d18f8493fb07b625d966ab37f/Untitled%201.png)

Figura 3: Loja

![Final%20Version%20Fully%20Functional%20Application%20a727594d18f8493fb07b625d966ab37f/Untitled%202.png](Final%20Version%20Fully%20Functional%20Application%20a727594d18f8493fb07b625d966ab37f/Untitled%202.png)

Figura 4: Loja após procura por "Ce"

### SOBRE

É composta por informações e objetivos da empresa.

![Final%20Version%20Fully%20Functional%20Application%20a727594d18f8493fb07b625d966ab37f/Untitled%203.png](Final%20Version%20Fully%20Functional%20Application%20a727594d18f8493fb07b625d966ab37f/Untitled%203.png)

### CARRINHO

É composto por cards dos produtos que foram adicionados na loja, é possível alterar a quantidade desses produtos escolhidos anteriormente, além da opção de excluí-los. É exibido o valor total da compra, junto com o adicional de frete para a cidade presente no cadastro. Tem algumas falhas que necessitam correção, como por exemplo o valor total que só altera quando recarregamos a página.

![Final%20Version%20Fully%20Functional%20Application%20a727594d18f8493fb07b625d966ab37f/Untitled%204.png](Final%20Version%20Fully%20Functional%20Application%20a727594d18f8493fb07b625d966ab37f/Untitled%204.png)

### PAGAMENTO

Finalização do pagamento, confirmando o endereço de entrega e a forma de pagamento.

![Final%20Version%20Fully%20Functional%20Application%20a727594d18f8493fb07b625d966ab37f/Untitled%205.png](Final%20Version%20Fully%20Functional%20Application%20a727594d18f8493fb07b625d966ab37f/Untitled%205.png)

### LOGIN

Tela simples para login. Administrador pode ser acessado por:

Usuário: admin

Senha: admin

![Final%20Version%20Fully%20Functional%20Application%20a727594d18f8493fb07b625d966ab37f/Untitled%206.png](Final%20Version%20Fully%20Functional%20Application%20a727594d18f8493fb07b625d966ab37f/Untitled%206.png)

### CADASTRO

Caso seja sua primeira vez utilizando o website, temos a opção de cadastro

![Final%20Version%20Fully%20Functional%20Application%20a727594d18f8493fb07b625d966ab37f/Untitled%207.png](Final%20Version%20Fully%20Functional%20Application%20a727594d18f8493fb07b625d966ab37f/Untitled%207.png)