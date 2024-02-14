### API Financeira
<P>Construí uma API financeira que contém recursos como cadastro de conta, validação de CPF, listagem do extrato, validação da conta, e utilizo middlewares para realizar depósitos, saques na conta, listar o extrato bancário por data, atualizar a conta e remover conta. Utilizo também métodos como GET, POST, PUT e DELETE.</P>

### Requisitos

- [X] Deve ser possível criar uma conta
- [X] Deve ser possível buscar o extrato bancário do cliente
- [X] Deve ser possível realizar um depósito
- [X] Deve ser possível realizar um saque
- [X] Deve ser possível buscar o extrato bancário do cleinte por data
- [X] Deve ser possível atualizar dados da conta do cliente
- [X] Deve ser possível obter dados da conta do cleinte
- [X] Deve ser possível deletar uma conta
- [X] Deve ser possível retornar o balace

---

## Regras de negócio

- [X] Não deve ser possível cadastrar uma conta com CPF já existente
- [X] Não deve ser possível fazer depósito em uma conta não existente
- [X] Não deve ser possível buscar o extrato em uma conta não existente
- [X] Não deve ser possível fazer saque em uma conta não existente
- [X] Não deve ser possível excluir uma conta não existente
- [X] Não deve ser possível fazer saque quando o saldo é insuficiente
