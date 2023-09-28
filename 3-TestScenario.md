##  3 - Validação de uma criação de conta com endereço de email com uma conta previamente vinculada

<br>

|     | Elementos             | Descrição                                |
| :-- | :------------------- | :---------------------------------------------------------------------------------------- |
| 1   | **ID:**              | _3-SC_                                                                                  |
| 2   | **Título:**           | _Validação da criação de uma conta com email já usado_                                                |
| 3   | **Dado Que:**   | _A aplicação **automationpractice.pl** está disponível e funcionando corretamente_             |
| 4   | **Quando:**           | _1. Ir até http://www.automationpractice.pl <br> 2. Clicar no botão `Sign in` <br> 3. Colocar um email já vinculado a uma conta no campo <br> 4. Clicar no botão `Create an account`_ |
| 5   | **Então:** | _Depois de seguir os passos descritos, a mensagem [![Valid](https://img.shields.io/badge/An%20account%20using%20this%20email%20address%20has%20already%20been%20registered.%20Please%20enter%20a%20valid%20password%20or%20request%20a%20new%20one.-f3515c)](#) é mostrada_ |
| 6   | **Explicação:** | _Não é possível criar um email com uma conta que já está vinculada a outra conta no site_                      |