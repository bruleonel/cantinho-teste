# cantinho-teste

Aqui falaremos sobre testes, que é uma maneira de botar à prova e avaliar se uma aplicação funciona ou não, e reduzir o risco de erros e falhas. Eu aposto que você já usou um site ou um sistema e aconteceu algum erro, alguma coisa que você não estava esperando.

Além de ser muito chato, isso pode ocasionar vários problemas, desde perda financeira, perda de reputação daquele site, e até perda de tempo também. Então é bem importante nós testarmos o nosso sistema para que ele seja resiliente e não tenha muitos erros. É sempre importante evitar esses erros. Para fazer esses testes nós vamos usar o sistema AluraPic. Nele vamos trabalhar alguns conceitos.

O processo de teste tem várias atividades. Não é só você chegar e fazer um teste em si. Você tem que planejar esse teste, tem que avaliar, ver as métricas dele. E tudo isso vamos aprender, e vamos gerar uma dessas documentações de teste, que é o plano de teste.

Um plano de teste define, comunica a intenção e o esforço desse teste. Por exemplo, para você ganhar a aceitação de que aqueles testes foram bem feitos e comunicar quais testes você fez; para você justificar o prazo que você planejou de fazer aqueles testes. Esse plano de teste serve para tudo isso.

Eu vou deixar um template e você poderá acompanhar junto comigo esse plano de teste, que é esse documento que eu tenho aqui. Ele é composto por várias seções, e nós falaremos um pouco delas depois.

Mas por onde nós começamos? A primeira coisa que vemos no AluraPic é a tela de login. Então precisamos saber como fazer para testar esse login. Você pode até achar um pouco óbvio, você já fez login várias vezes. Mas mesmo assim é importante olhar no nosso plano de teste como esse login deve funcionar.

Na seção de funcionalidades você acha o login. Tem alguns comportamentos de o que ele deve fazer e como ele deve funcionar que foram escritos pelo time de desenvolvimento, por aquela pessoa que idealizou o sistema.

Por exemplo, temos “Ao digitar seu usuário e senha corretamente o usuário irá logar na plataforma”. Então vamos ver se isso acontece.

Eu vou digitar no AluraPic um login e uma senha. No campo de usuário vou colocar “usuario_teste” e uma senha muito difícil, “12345678”, e clicar em “login”.

Legal, isso funcionou, ele nos levou para uma tela diferente, que é a tela principal do nosso sistema. E segundo o nosso plano de teste, era para realmente isso acontecer.

Agora que vimos que essa funcionalidade funciona, o que mais precisamos testar? No nosso plano de teste temos outras coisas. Então no próximo vídeo veremos melhor como estruturar esses testes e quais todos os outros testes que precisamos fazer.

<b>Exemplo:</b>

Funcionalidade: Cadastro

Comportamento esperado: Ao digitar e-mail, nome completo, usuário e senha e confirmar a senha, o usuário será cadastrado na plataforma.

Quando o cadastro for efetuado corretamente, o usuário deverá ser redirecionado para a tela de login. Em caso de erro, usuário deve receber uma mensagem informando qual é o erro.

Todos os campos são obrigatórios e o sistema deve indicar caso um campo não tenha sido digitado.

A senha deve ter no mínimo 8 caracteres.

![MicrosoftTeams-image](https://github.com/bruleonel/cantinho-teste/assets/104650333/0d790b2d-01fd-45c3-95a0-50439ed10d63)

*Deixei essa imagem do fluxo que eu criei com a correção da minha superior.*


<a href="https://bruleonel.github.io/cantinho-teste/">Veja</a>
