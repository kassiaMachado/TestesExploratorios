# TestesExploratórios

--Testes Login Magazine Luiza--

Dado que estou na tela de login 

E tento acessar a conta sem preencher as informações pedidas

Então o site não me permite acessar ![login senha em branco](https://user-images.githubusercontent.com/60439279/125211479-0e155300-e27d-11eb-94b1-3ecc6283b3c0.png)

Dado que estou na tela de login,

Quando tento criar uma conta ele informa que já existe uma conta cadastrada com o email inserido, ele não me redireciona para acessar a conta já existente e não limpa o campo de criar a nova conta.

Então depois de inserir um email válido e uma senha inválida, o site pede para verificar o login e senha.
![email valido senha invalida](https://user-images.githubusercontent.com/60439279/125211712-bbd53180-e27e-11eb-97be-f7264436d7e7.png)

Dado que estou na tela de login,

E tento inserir um CPF/CNPJ ele não delimita a quantidade de números inseridos para o padrão Brasileiro, o CPF tem 11 dígitos decimais e o CNPJ 14 dígitos decimais.
![campo sem delimitar](https://user-images.githubusercontent.com/60439279/125211824-98f74d00-e27f-11eb-8c6d-f0dfb81ebd65.png)



