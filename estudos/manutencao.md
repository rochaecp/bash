# Informações

- Login via tty1: ctrl alt F1
- Login: mauricio 
- Senha: mesma acessar pc

~~~shell
	#sudo: exec como super usuário, apt-get gerenciador de pacotes
	sudo apt-get install nome_do_programa

	#Remover um programa
	sudo apt-get remove nome_do_programa

	#Verifica se há atualizações
	sudo apt-get update

	#Atualizar
	sudo apt-get upgrade

	#Manutenção no sistema (1 vez/ mês)
	sudo apt-get autoremove    #remove programas obsoletos / desnecessários

	#Manutenção no sistema - limpar cash do apt
	sudo apt-get autoclean

	#Manutenção no sistema - manipular pacotes quebrados
	sudo apt-get install -f
~~~
