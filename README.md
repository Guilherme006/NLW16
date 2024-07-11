# Gerenciador de Viagens

Este é um projeto de Gerenciador de Viagens desenvolvido em Python usando o framework Flask. O projeto permite que os usuários postem viagens, salvem atividades, gerenciem links de viagens e enviem e-mails usando o serviço Ethereal.

## Funcionalidades

- **Postar Viagem:** Permite aos usuários criar e gerenciar suas viagens.
- **Salvar Atividade:** Os usuários podem adicionar e organizar atividades específicas para suas viagens.
- **Gerenciamento de Links de Viagens:** Possibilidade de adicionar e visualizar links relevantes para cada viagem.
- **Envio de E-mails:** Utiliza o serviço Ethereal para enviar e-mails relacionados às viagens e atividades.

## Tecnologias Utilizadas

- **Linguagem:** Python
- **Framework:** Flask
- **Banco de Dados:** SQLite
- **Bibliotecas:**
  - `uuid`: Para geração de identificadores únicos.
  - `requests`: Para fazer chamadas HTTP.
  - `flask`: Para o desenvolvimento do backend.
  - `sqlite3`: Para o gerenciamento do banco de dados SQLite.

## Instalação

1. Clone o repositório:
    ```bash
    git clone [https://github.com/Guilherme006/NLW16.git
    ```

2. Crie um ambiente virtual e ative-o:
    ```bash
    python -m venv venv
    source venv/bin/activate  # No Windows: venv\Scripts\activate
    ```

3. Instale as dependências

4. Configure as variáveis de ambiente para o envio de e-mails com Ethereal:
   ```bash
    from_addr = 'seu_usuario_ethereal'
    login = 'seu_usuario_ethereal'
    password = 'sua_senha_ethereal'
    ```
5. Execute a aplicação:
    ```bash
    python run.py
    ```
