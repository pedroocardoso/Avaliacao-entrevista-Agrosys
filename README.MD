# Avaliação Técnica Agrosys
Este foi um desafio proposto pela empresa Agrosys para entrevista e consiste no desenvolvimento de uma mini aplicação Web voltada para o cadastro e gerenciamento de clientes e seus respectivos endereços, com foco em simplicidade, funcionalidade e execução totalmente local, sem dependências de servidor backend.

A aplicação foi implementada com HTML, CSS e JavaScript (Vanilla), sendo obrigatória a utilização do AlaSQL.js para a criação e manipulação de um banco de dados SQL executado diretamente no navegador, sem a necessidade de backend ou instalações adicionais. O sistema foi projetado para ser Mobile Friendly, garantindo sua utilização em dispositivos móveis e desktops. O uso de jQuery e Bootstrap foi permitido de forma opcional para auxiliar no desenvolvimento da interface.

O desafio exigiu a implementação das seguintes funcionalidades:

 - Tela de Login, com autenticação e cadastro de novos usuários, impedindo a duplicação de contas, além de uma opção de Configurações para upload de um banco de dados pré-populado.

 - Tela de cadastro e listagem de clientes, contendo os campos: nome completo, CPF, data de nascimento, telefone e celular, sendo proibido o cadastro de clientes com CPF duplicado.

 - Tela de cadastro e listagem de endereços, vinculada aos clientes, com os campos: CEP, rua, bairro, cidade, estado, país e identificador do cliente, sendo obrigatório que cada cliente possua um endereço principal.

 - Funcionalidade de exportação do banco de dados, permitindo gerar um arquivo no formato JSON.

Como requisito final, o projeto deveria ser estruturado para rodar localmente no navegador do avaliador, sendo entregue com um arquivo INFO.txt com instruções para execução.