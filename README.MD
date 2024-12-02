Passo 1:
Acesse o site oficial do Python.
Baixe e instale a versão mais recente do Python. Durante a instalação, marque a opção "Add Python to PATH".
Verifique se o Python foi instalado corretamente abrindo o terminal (Prompt de Comando) e digitando:

python --version

Passo 2: Instalar o Visual Studio Code
Acesse o site oficial do Visual Studio Code.
Baixe e instale o VS Code para o seu sistema operacional.
Abra o VS Code após a instalação.

Passo 3: Instalar a extensão Python no VS Code
Abra o VS Code.
Vá até a aba de Extensões (ícone de quadrado no lado esquerdo ou Ctrl+Shift+X).
Procure por Python e instale a extensão oficial do Python (desenvolvida pela Microsoft).
Isso vai habilitar várias funcionalidades úteis, como execução de código Python e suporte a ambientes virtuais.

Passo 4: Criar um Ambiente Virtual
Abrir o terminal integrado no VS Code:

No VS Code, abra o terminal pressionando Ctrl+` ou vá em Terminal > Novo Terminal.
Criar o ambiente virtual: No terminal, navegue até o diretório do projeto e execute o seguinte comando:

python -m venv venv

Isso criará uma pasta chamada venv dentro do seu diretório de projeto, que irá conter o ambiente virtual.

Ativar o ambiente virtual:

Windows: No terminal, digite:
.\venv\Scripts\activate

macOS/Linux: No terminal, digite:
source venv/bin/activate

Passo 5: Instalar as dependências
No terminal do VS Code (com o ambiente virtual ativado), execute o seguinte comando para instalar as bibliotecas necessárias para o projeto:

pip install -r requirements.txt

Passo 6: Rodar a aplicação
Agora que você instalou as dependências necessárias, pode rodar a aplicação.

No terminal, com o ambiente virtual ativado, execute:

python app.py

Você pode rodar diretamente também o comando:

flask run
Isso iniciará o servidor Flask, e você verá algo como:

 * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)

Passo 7: Abrir o link no seu navegador e pronto.