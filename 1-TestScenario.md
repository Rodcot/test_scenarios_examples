##  1 - Validação de uma criação de conta sem endereço de email inserido no campo de entrada

<br>

|     | Elementos             | Descrição                                |
| :-- | :------------------- | :---------------------------------------------------------------------------------------- |
| 1   | **ID:**              | _1-SC_                                                                                  |
| 2   | **Título:**           | _Validação de criação de conta sem email_                                                |
| 3   | **Dado Que:**   | _A aplicação **automationpractice.pl** está disponível e funcionando corretamente_             |
| 4   | **Quando:**           | _1. Ir até http://www.automationpractice.pl <br> 2. Clicar no botão `Sign in` <br> 3. Clicar no botão `Create an account`_ |
| 5   | **Então:** | _Depois de seguir os passos descritos, a mensagem [![Valid](https://img.shields.io/badge/Invalid%20email%20address.-f3515c)](#) é mostrada._ |
| 6   | **Explicação:** | _Não é possível criar uma conta nova sem especificar um email_                      |