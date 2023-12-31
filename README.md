# Desafio PicPay-Simplificado

Esse projeto é uma implementação de um dos desafios do PicPay para uma vaga de backend, o objetivo do desafio é implementar um serviço semelhante ao próprio PicPay, mas com uma API Restful simplificada, optei por desenvolver um frontend para praticar outras skills utilizando o mesmo projeto.

### 🕵️‍♂️ Link para o desafio:
[Desafio backend PicPay](https://github.com/PicPay/picpay-desafio-backend)

### 🧾 Diagrama de sequência do fluxo de transação:

[Fluxo de transação](./api/docs/Diagrama%20fluxo%20de%20transação.pdf)

### Funcionalides:

- Cadastro de novos usuários "lojistas" e "usuários comuns";
- Usuários podem fazer login na aplicação;
- Usuários comuns podem realizar transferências;
- O sistema deve exibir o histórico de transações e o saldo atual do usuário;

### 🛠 Tecnologias utilizadas:

###  Frontend:
- [Next JS](https://nextjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Redux Toolkit](https://redux-toolkit.js.org/)
- [React-i18next](https://react.i18next.com/)

### Backend:
 - [Go](https://go.dev/)
 - [Gin](https://gin-gonic.com)
 - [Bcrypt](https://pkg.go.dev/golang.org/x/crypto/bcrypt)
 - [JWT-Go](https://github.com/dgrijalva/jwt-go)