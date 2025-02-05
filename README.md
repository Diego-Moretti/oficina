# Modelo de Banco de Dados para Oficina Mecânica

Este modelo representa um sistema de controle e gerenciamento de ordens de serviço em uma oficina mecânica. Ele foi projetado para gerenciar clientes, veículos, serviços, peças, equipes e mecânicos, garantindo que todas as informações necessárias para a execução e acompanhamento das ordens de serviço sejam armazenadas de forma organizada.

## Funcionalidades Principais
- **Clientes**: Armazena informações dos clientes que levam seus veículos para reparos ou revisões.
- **Veículos**: Registra os veículos associados aos clientes, incluindo detalhes como marca, modelo, ano e cor.
- **Serviços**: Define os serviços que podem ser realizados na oficina, com descrição e valor da mão de obra.
- **Peças**: Gerencia as peças utilizadas nos serviços, com nome e valor unitário.
- **Ordens de Serviço (OS)**: Controla as ordens de serviço, incluindo data de emissão, valor total, status, veículo associado, equipe responsável e data prevista para conclusão.
- **Equipes**: Organiza os mecânicos em equipes para execução dos serviços.
- **Mecânicos**: Armazena informações sobre os mecânicos, incluindo nome, endereço, especialidade e equipe à qual pertencem.

## Relacionamentos
- **Clientes** possuem **Veículos**.
- **Veículos** estão associados a **Ordens de Serviço**.
- **Ordens de Serviço** podem conter vários **Serviços** e **Peças**.
- **Serviços** podem estar associados a várias **Peças**.
- **Equipes** são compostas por **Mecânicos**.
- **Mecânicos** pertencem a uma **Equipe**.
