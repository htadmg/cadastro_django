# Cadastro de Usuario com django

## Descrição do Projeto
Este projeto é uma aplicação simples em Django que permite o cadastro e listagem de usuários. A aplicação conta com uma interface para adicionar novos usuários e visualizar a lista de todos os usuários cadastrados.

## Funcionalidades
- Cadastro de usuários com nome e idade.
- Exibição da lista de usuários cadastrados com ID, nome e idade.
- 
## Tecnologias Usadas
- **Python**: Linguagem de programação usada para construir o backend.
- **Django**: Framework web usado para construir o servidor e o gerenciamento de dados.
- **Bootstrap**: Framework de front-end usado para criar uma interface de usuário responsiva e estilizada.
- **HTML/CSS**: Linguagens de marcação e estilo usadas para construir e estilizar a interface do usuário.

  ## Como Configurar o Projeto

Para executar este projeto localmente, siga os passos abaixo:

1. **Clone o Repositório**
- Usando HTTPS:
```bash
git clone https://github.com/htadmg/cadastro_django.git
```
- Usando SSH:
```bash
git clone git@github.com:htadmg/cadastro_django.git
```
- Navegue até o diretório do projeto:
```bash
cd .\cadastro_django
```
   
3. **Crie e Ative um Ambiente Virtual (opcional, mas recomendado)**
- **Para Linux/MacOS:**
```bash
python -m venv venv
source venv/bin/activate
```

- **Para Windows:**
```powershell
python -m venv venv
.\venv\Scripts\Activate.ps1
```   
3. **Instale as dependências**
```bash
pip install -r requirements.txt
```
## Configuração do Banco de Dados

Aplique as migrações para configurar o banco de dados:

```bash
python manage.py migrate
```

### Criação de Superusuário

Para acessar o painel administrativo, crie um superusuário:
```bash
python manage.py createsuperuser
```

### Iniciar o Servidor de Desenvolvimento

Inicie o servidor de desenvolvimento com o comando:

```bash
python manage.py runserver
```
### Acessar o Projeto
Abra um navegador e vá para http://127.0.0.1:8000/ para ver o aplicativo em funcionamento. Você pode acessar o painel administrativo em http://127.0.0.1:8000/admin/ usando as credenciais do superusuário que você criou.
