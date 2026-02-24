# Banco de Dados da Oficina

Este é um pequeno projeto em que decidi colocar em prática meus conhecimentos em Banco de Dados, SQL e MySQL, a partir de um exercício do curso de Banco de Dados Relacionais do professor Felipe Mafra.

Assim, desenvolverei um banco de dados de uma oficina fictícia em que foi me passado uma regra de negócio e deverei segui-la para tal.

## Regra de negócio
> Sr. José quer modernizar sua oficina, e por enquanto, cadastrar os carros que entram para realizar serviços e os seus respectivos donos.
> 
> Ele mencionou que cada cliente possui apenas um carro. Um carro possui uma marca. 
> 
> Ele quer saber também as cores dos carros para ter ideia de qual tinta comprar, e informa que um carro pode ter mais de uma cor.
> 
> Ele necessita armazenar os telefones dos clientes, mas não quer que eles sejam obrigatórios

## Modelagem do banco
Utilizando o software [*BRModelo*](https://brmodelo.com/index.html) construí um **modelo lógico** para o banco especificado pelo Sr. José

### *Modelo Lógico*
![Modelo Lógico](assets/modelo_logico.png)

A partir deste modelo, desenvolvi a modelagem física do banco utilizando o SQL no MySQL. Os arquivos contendo a modelagem estão armazenados na pasta **SQL** do repositório.