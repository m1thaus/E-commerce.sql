# E-commerce.sql

Descrição

Este banco de dados foi criado para gerenciar um sistema de e-commerce simples, incluindo usuários, produtos, pedidos e itens de pedido.

Estrutura do Banco de Dados


O banco de dados contém as seguintes tabelas:


usuarios - Armazena informações sobre os usuários cadastrados.

produtos - Contém os detalhes dos produtos disponíveis para compra.

pedidos - Registra os pedidos feitos pelos usuários.

itens_pedido - Relaciona os produtos incluídos em cada pedido.


Requisitos


MySQL ou MariaDB instalado.

Um cliente SQL para executar os comandos.


Como Usar


Crie o banco de dados executando o script SQL fornecido no arquivo banco_dados.sql.

Para inserir dados, utilize comandos INSERT INTO conforme necessário.

Para consultar informações, utilize consultas SELECT nas tabelas desejadas.


Exemplo de Consulta


SELECT pedidos.id, usuarios.nome, pedidos.total, pedidos.status
FROM pedidos
JOIN usuarios ON pedidos.usuario_id = usuarios.id;

Licença

Este projeto está sob a licença MIT.
