# Desafio_Modelo_Conceitual_Oficina_Mecânica
Desafio DIO construindo do zero um esquema conceitual para execução de ordens de serviço em uma Oficina mecânica.

### Premissas do Modelo

1 - Cliente leva o(s) veículo(s) à oficina para serem consertados ou para revisões periódicas.
2 - Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma OS (Odem de Serviço) com data de entrega.
3 - A partir da OS, calcula-se o valor de cada serviço, consultando uma tabela de referência de mão de obra.
4 - O valor de cada peça também irá compor OS.
5 - O cliente autoriza a execução dos serviços.
6 - A mesma equipe que avalia, executa os serviços.
7 - Os mecânicos possuem: código, nome, endereço e especialidade.
8 - Cada OS possui: número, data de emissão, valor, status e uma data para conclusão dos trabalhos.
9 - Uma OS pode ser composta por vários serviços e um serviço pode estar contido em mais de uma OS.
10 - Uma OS pode ter vários tipos de peça e uma peça pode estar presente em mais de uma OS.

#### Descrição

O modelo foi desenvolvido baseado nas premissas acima.
Onde um cliente pode ter mais de um veiculo que gera uma OS e a equipe que analisa, executa a OS do veículo.
