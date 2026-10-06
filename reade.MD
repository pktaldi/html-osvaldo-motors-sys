carro (placa, modelo, FK(id_cliente)
\|/
 |
 |
cliente (id_cliente, nome, cpf, email)
 |
 |
 |
cadastro_servico (id_servico, valor total, descrição, FK(id_cliente), FK(placa))
