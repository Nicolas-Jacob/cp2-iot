Integrantes:

Vinicius Romaguera Cardozo
RM: 562308

Yuri Fuzinatto garzoli Barreto
RM: 561450

Nicollas de Oliveira Jacob
RM:564205

__________________________________________________

Código da function:

let temperatura = 25;
let luminosidade = 800;
let status = "Temperatura Normal";

msg.topic = `
INSERT INTO sensores
(temperatura, luminosidade, status)
VALUES
(${temperatura}, ${luminosidade}, '${status}')
`;

return msg;

_______________________________________________________

Group: Sensores
