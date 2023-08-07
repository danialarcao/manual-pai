# Manual do sistema PAI

## Pré-requisitos funcionais
1. Crie um repositório no github marcando a opção "público", adicionando README.md, arquivo .gitignore para Python e a licença GPL v3

2. Clone o repositório na máquina local e abra-o no Powershell
    
3. Prepare o ambiente no powershell com as instruções:
    ``` 
    $ python -m venv venv
	$ cd .\venv\Scripts\
	$ .\activate
	$ python.exe -m pip install --upgrade pip
	$ cd..
	$ cd..
	$ pip install mkdocs-material
	$ code . # para abrir no vscode
    ```

4. Dentro do vscode, abrir o terminal e rodar:
    ```
    $ mkdocs new
	$ mkdocs serve
    ```
    O ambiente estará operacional localmente! :-)