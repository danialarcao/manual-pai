# Manual do sistema PAI

## Preparando o ambiente
    1) Crie um repositório no github marcando a opção publico, adicionando README.md, gitignore para Python e a licença GPL v3

    2) Clone o repositorio na maquina e abra o repositorio no Powershell

    3) prepare o ambiente no powershell com os comandos:
	$ python -m venv venv
	$ cd .\venv\Scripts\
	$ .\activate
	$ python.exe -m pip install --upgrade pip
	$ cd..
	$ cd..
	$ pip install mkdocs-material
	$ code . #para abrir no vscode

    4) Dentro do vscode, abrir o terminal e rodar:
	$ mkdocs new
	$ mkdocs serve

O ambiente estará operacional localmente