
# Teste - Brain Agriculture

O teste tem como objetivo acurar as habilidades do candidato em resolver alguns problemas relacionados à lógica de programação, regra de negócio e orientação à objetos.

O mesmo consiste em um cadastro de produtor rural com os seguintes dados: 

 1. CPF ou CNPJ
 2. Nome
 3. Nome da Fazenda
 4. Cidade
 5. Estado
 6. Área total em hectares da fazenda
 7. Área de Uso Consolidado em hectares
 8. Área de Reserva Legal em hectares
 7. Culturas plantadas (Soja, Milho, Algodão, Café, Cana de Açucar) 


# Requisitos de negócio

 - O usuário deverá ter a possibilidade de cadastrar, editar, e excluir produtores rurais.
 - O sistema deverá validar CPF e CNPJ digitados incorretamente.
 - A soma de Área de Uso Consolidado e Reserva Legal, não deverá ser maior que a Área Total da Fazenda
 - Cada produtor pode plantar mais de uma cultura em sua Fazenda.
 - A plataforma deverá ter um Dashboard que exiba:
	 - Média de fazendas por Estado e Cultura. 
	 - Média de Hectares por Estado e Cultura.
	 - Total de Área Consolidada em hectares.
	 - Total de Reserva legal em hectares.
     
# Mockups

![Dashboard da ferramenta](https://brain.agr.br/assets/docs/Dashboard.png)

![Tela de cadastro](https://brain.agr.br/assets/docs/Registro.png)

![Tabela para edição e remoção](https://brain.agr.br/assets/docs/Datatable.png)

# Requisitos técnicos

 - O front-end deverá ser escrito em [ReactJS](http://reactjs.org) usando o [Redux](https://redux.js.org/) para controlar o estado da aplicação.
 - Os dados inputados pelo usuário deverão ser salvos em um banco de dados Postgres usando o NodeJS como layer de Backend.
 - Não envie a solução como anexo, suba os fontes para seu Github (ou outro repositório) e envie o link para *guilherme@brain.agr.br*. 

