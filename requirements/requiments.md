# Requisitos Funcionais

## Requisito Funcional 1: Cadastro de Usuário

**Descrição**: O sistema deve permitir que o usuário se cadastre fornecendo um e-mail e uma senha.

### Requisitos:
- O sistema deve validar se o e-mail fornecido é único.
- O sistema deve validar se o formato do e-mail está correto.
- A senha deve ser armazenada de forma segura, utilizando hashing.
- O sistema deve enviar um e-mail de confirmação para o endereço informado.
- O sistema deve garantir que o e-mail de confirmação tenha um link válido por no máximo 24 horas.

### Fluxo de Funcionamento:
1. O usuário acessa a página de cadastro.
2. O usuário insere o e-mail e senha nos campos correspondentes.
3. O sistema valida o e-mail e a senha.
4. Se os dados forem válidos, o sistema envia um e-mail de confirmação para o endereço informado.
5. O usuário deve confirmar o e-mail clicando no link recebido.
6. O sistema ativa a conta e permite o login.

---
