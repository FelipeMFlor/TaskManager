# TaskManager
Task management system built in C# using Clean Architecture and incremental development.


#### Primeiros Passos

 1- Definir uma classe para fazer um sistema de login no aplicativo de tarefas.
	
	Cadastro de login simples deve conter:

	String Nome
	String Senha
	String E-mail
	int CPF
	Masculino/Feminino Sexo

	Funções:

	ValidarSenha -> Deve validar se o CPF informado condiz com a senha informada. (No momento farei de forma manual, irei fazer uma função
	integrando com banco de dados posteriormente)

	Override -> Deve retornar um texto informando se o login e valido ou não.


2- Definir como irá funcionar o controle de tarefas