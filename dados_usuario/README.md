# Cadastro de Usuário - Projeto de Formulário com Bootstrap

Este projeto é um formulário de cadastro de usuário simples desenvolvido em HTML e estilizado com Bootstrap. O objetivo é coletar dados do usuário por meio de campos de entrada, montar um objeto a partir desses dados e exibi-lo no console. Futuramente, esse projeto pode ser expandido para enviar os dados a uma API.

## Tecnologias Utilizadas

-   **HTML**: para a estrutura do formulário.
-   **Bootstrap**: para a estilização e responsividade.
-   **JavaScript**: para coletar os dados e realizar operações com eles.

## Estrutura do Projeto

O formulário é composto por quatro campos de entrada:

1. **Nome**: um campo de texto para o nome do usuário.
2. **Email**: um campo de email para o endereço de email do usuário.
3. **Data de Nascimento**: um campo de data para a data de nascimento do usuário.
4. **Senha**: um campo de senha para o usuário criar uma senha.

Além disso, há um botão de enviar que, quando clicado, deverá acionar um script JavaScript que coleta os dados inseridos, monta um objeto e exibe esse objeto no console.

## Como Usar

1. Abra o arquivo `index.html` em um navegador.
2. Preencha os campos de entrada com os dados desejados.
3. Clique no botão de enviar.
4. Abra o console do navegador (geralmente pressionando F12) para ver o objeto contendo os dados inseridos.

## Futuras Melhorias

Esse projeto pode ser expandido para enviar os dados a uma API. Isso pode ser feito da seguinte forma:

1. **Integração com uma API**:

    - Pode-se usar `fetch` ou uma biblioteca como `axios` para enviar os dados para um endpoint.
    - Esse endpoint pode então processar ou armazenar os dados.

2. **Validação**:

    - Adicionar validação nos campos de entrada para garantir que os dados sejam inseridos corretamente.

3. **Estilização**:
    - Personalizar ainda mais o estilo do formulário, talvez adicionando temas personalizados ou melhorando a usabilidade.

## Conclusão

Este é um exemplo básico de um formulário de cadastro de usuário. Ele pode ser usado como ponto de partida para projetos mais complexos que envolvem coleta de dados do usuário e integração com APIs.
