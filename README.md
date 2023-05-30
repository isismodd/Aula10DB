# Aula10DB
//Exercício proposto em uma aula do curso de informática do IFSP.

Aplicação (Aula10DB) para criar, popular e exibir, informações de tabelas de Clientes e Pedidos.
A aplicação deverá considerar somente as funcionalidades “Inserir” e “Listar”
para as duas tabelas, sendo que tais funcionalidades deverão ser informadas via
parâmetros de execução, conforme segue:
dotnet run -- Cliente Inserir
dotnet run -- Cliente Listar
dotnet run -- Pedido Inserir
dotnet run -- Pedido Listar

Para a funcionalidade “Inserir”, as informações das tabelas deverão ser
digitadas, considerando-se os seguintes atributos:

TABELA DE CLIENTES
public int ClienteId { get; set; }
public string Endereco { get; set; }
public string Cidade { get; set; }
public string Regiao { get; set; }
public string CodigoPostal { get; set; }
public string Pais { get; set; }
public string Telefone { get; set; }

TABELA DE PEDIDOS
public int PedidoId { get; set; }
public int EmpregadoId { get; set; }
public string DataPedido { get; set; }
public string Peso { get; set; }
public int CodTransportadora { get; set; }
public int PedidoClienteId { get; set; } ****
