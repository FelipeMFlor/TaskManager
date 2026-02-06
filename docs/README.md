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

O controle de tarefas será definido pela classe task que irá conter:

1- Nome da Task
2- Descrição (opcional)
3- Data e hora de validade (Irá durar pelo dia informado, a hora servirá somente para gerenciar avisos futuramente)
4- Tipo (A tarefa poderá ter um tema ou classe para definir sua proveniência)
5- Nível (Cada task terá um nível de dificuldade para ser realizada, futuramente a idéia será implementar um sistema de recompensas 
          definíveis pelo nível).
6- Status de completo ou pendente (boleano com uma checkbox)