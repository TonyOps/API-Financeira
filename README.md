### API Financeira
<P>Construí uma API financeira completa, utilizando o Node.js, que oferece uma gama de recursos essenciais para gerenciamento de contas bancárias. Desde o cadastro de contas até a validação de CPF, cada aspecto foi desenvolvido para garantir eficiência e segurança.

Resumo da aplicação:

   <ul>
     <li>Utilizei os métodos HTTP GET, PUT, POST e DELETE para criar usuários, buscar extratos, realizar alterações e apagar contas.</li>
     <li>Implementei middlewares personalizados para melhor comunicação com outras aplicações.</li>
     <li>Preocupei-me em seguir os padrões do Clean Code ao aplicar os princípios SOLID no projeto.</li>
   </ul>    
</P>

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
