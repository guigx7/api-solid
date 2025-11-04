#APP

Gympass style app.

##RFs

- Deve ser possível se cadastrar
- Deve ser possível se autenticar
- Deve ser possível obter o perfil de um usuário
- Deve ser possível obter o perfil de um usuário logado
- Deve ser possível obter o número de check-ins realizados pelo usuário logado
- Deve ser possível o usuário obter o histórico de check-ins
- Deve ser possível o usuário buscar academias próximas
- Deve ser possível o usuário buscar academias próximas
- Deve ser possível o usuário realizar check-in em uma academia
- Deve ser possível validar o check-in do usuário
- Deve ser possível cadastrar uma academia

#RNs

- O usuário não deve poder se cadastrar com um e-mail duplicado
- O usuário não pode fazer mais de um check-in no mesmo dia
- O usuário não pode fazer check-in se estiver a mais de 100 metros da academia
- O check-in só pode ser validado em até 20 minutos após solicitado
- O check-in só pode ser validado por administradores
- A academia só pode ser cadastrada por administradores

#RNFs

- A senha do usuário deve estar criptografada
- Os dados da aplicação precisam estar persistidos em um banco PostgreSQL
- Todas as listas de dados devem estar paginadas com 20 itens por página
- O usuário deve ser identificado por um JWT
