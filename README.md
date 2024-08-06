# Flask-basica
# Aplicação Flask Básica

Este é um exemplo de uma aplicação web básica usando o Flask.

## Como Executar

1. Clone o repositório:
    ```bash
    git clone https://github.com/seu-usuario/seu-repositorio.git
    ```

2. Navegue até o diretório do projeto:
    ```bash
    cd seu-repositorio
    ```

3. Crie um ambiente virtual e ative-o:
    ```bash
    python -m venv venv
    source venv/bin/activate  # No Windows, use: venv\Scripts\activate
    ```

4. Instale as dependências:
    ```bash
    pip install -r requirements.txt
    ```

5. Execute a aplicação Flask:
    ```bash
    python app.py
    ```

6. Abra o navegador e vá para `http://127.0.0.1:5000/`.

## Adicionando um Nome

Para testar o endpoint `/greet`, envie um POST request para `http://127.0.0.1:5000/greet` com um formulário que inclui um campo `name`.
