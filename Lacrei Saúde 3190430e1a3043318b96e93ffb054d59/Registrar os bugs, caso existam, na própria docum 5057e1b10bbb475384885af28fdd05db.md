# Registrar os bugs, caso existam, na própria documentação;

**Bug:** Usuário realizou a exclusão de sua conta no sistema através do botão "Apagar minha conta”, ao tentar se registrar novamente uma mensagem de "Um usuário já foi registrado com este endereço de e-mail.” foi exibida, não permitindo que o mesmo realiza-se o cadastro.

**Cenário Conta excluída:** Usuário fornece informações válidas de uma pessoa usuária que havia sido excluída.

**Entrada:**

- Nome: Elisete
- Sobrenome: Cercal
- E-mail: elisetecercal@gmail.com
- Senha: Elisete@123

| Caso de Teste Cadastro de pessoa usuária | Passos | Resultado esperado | Resultado Real |
| --- | --- | --- | --- |
| CTCE: Usuário fornece informações válidas. | Acessar a pagina home https://frontend-lacrei-pessoa-usuaria.vercel.app/ | Página home será exibida “Bem vinda à Lacrei” | Página home será exibida “Bem vinda à Lacrei” |
|  | Clicar no botão “Criar  conta” | Formulário de cadastro será exibido | Formulário de cadastro será exibido |
|  | Preencher os campos obrigatórios com informações válidas | Os campos devem receber dados digitados | Os campos devem receber dados digitados |
|  | Marcar o campo de "Li e concordo com termos de uso” | O campo deve ficar marcado de branco para azul | O campo deve ficar marcado de branco para azul |
|  | Marcar o campo de “tenho mais de 18 anos” | O campo deve ficar marcado de branco para azul | O campo deve ficar marcado de branco para azul |
|  | Clicar no botão “cadastrar” | O sistema apresenta uma mensagem para confirmação de e-mail “Para sua segurança,
enviamos um link de verificação para o e-mail cadastrado” | O sistema apresenta uma mensagem para confirmação de e-mail “Para sua segurança,
enviamos um link de verificação para o e-mail cadastrado” |
|  | Após o recebimento do link de verificação na caixa de e-mail da nova pessoa cadastrada, clicar no link para confirmar e-mail | O sistema apresenta uma mensagem para confirmação de e-mail “Para sua segurança,
enviamos um link de verificação para o e-mail cadastrado” | O sistema apresenta uma mensagem “Um usuário já foi registrado com este endereço de e-mail.” Pessoa usuária não foi cadastrada |

![CTCE.gif](Registrar%20os%20bugs,%20caso%20existam,%20na%20pro%CC%81pria%20docum%205057e1b10bbb475384885af28fdd05db/CTCE.gif)