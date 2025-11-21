# <p align="center">StreamAll</p>

<p align="center">
  <img src="imgs/logo png.png" alt="StreamAll Logo" width="200"/>
</p>

<p align="center">
  <strong>Uma plataforma multimídia unificada para Filmes, Séries, Livros e Músicas.</strong>
</p>

---

## 🚀 Sobre

O **StreamAll** é uma aplicação web Full-Stack que simula uma plataforma de streaming moderna. O diferencial do projeto é a unificação de diferentes tipos de mídia em uma única interface fluida e responsiva.

O objetivo deste projeto é demonstrar competências em desenvolvimento web, arquitetura de software, consumo de múltiplas APIs externas e persistência de dados segura.

---

## ✨ Funcionalidades

- **Autenticação Segura:** Sistema de Cadastro e Login com hash de senhas e gerenciamento de sessão.
- **Catálogo Unificado:** Busca e exibição de Filmes, Séries, Livros e Músicas.
- **Live Search:** Barra de pesquisa global que filtra resultados em tempo real.
- **Minha Lista:** Funcionalidade para salvar itens favoritos (vinculado ao usuário).
- **Edição de Perfil:** Gerenciamento de dados do usuário.
- **Integração via API:**
  - Filmes e Séries via **TMDB API**.
  - Livros via **Google Books API**.
  - Músicas via **Spotify Web API**.

---

## 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

### Frontend
- **HTML5** (Estrutura Semântica)
- **CSS3** (Estilização Responsiva e Animações)
- **JavaScript (ES6+)** (Lógica de interface e requisições assíncronas)

### Backend
- **Python 3** (Linguagem Base)
- **Flask** (Framework Web / API REST)
- **SQLAlchemy** (ORM para Banco de Dados)
- **Werkzeug Security** (Segurança e Criptografia)

### Banco de Dados
- **SQLite** (Banco de dados relacional leve e embutido)

---

## 🎲 Como Executar

Siga os passos abaixo para rodar o projeto na sua máquina local.

### Pré-requisitos
Antes de começar, você vai precisar ter instalado em sua máquina o [Python](https://www.python.org/) e o [Git](https://git-scm.com).

### 1. Clone o repositório
```bash
# Clone este repositório (substitua SEU-USUARIO pelo seu nome de usuário real do GitHub)
$ git clone [https://github.com/SEU-USUARIO/StreamAll.git](https://github.com/SEU-USUARIO/StreamAll.git)

# Acesse a pasta do projeto no terminal/cmd
$ cd StreamAll

# No Windows
$ python -m venv venv
$ venv\Scripts\activate

# No Linux/Mac
$ python3 -m venv venv
$ source venv/bin/activate

# Instala todas as bibliotecas listadas no arquivo requirements.txt
$ pip install -r requirements.txt

FLASK_APP=app.py
FLASK_ENV=development
SECRET_KEY=sua_chave_secreta_flask

# Chaves de API Externas
TMDB_API_KEY=sua_chave_tmdb
SPOTIFY_CLIENT_ID=seu_client_id
SPOTIFY_CLIENT_SECRET=seu_client_secret

# Comando para criar as tabelas no banco de dados
$ python -c 'from app import db, app; app.app_context().push(); db.create_all()'

# Rodar a aplicação
$ flask run
````
O servidor iniciará na porta: http://127.0.0.1:5000

🎨 Layout
O layout foi desenvolvido com foco em experiência do usuário (UX), utilizando uma paleta de cores moderna:

🎨 Cores do gradiente

Início do gradiente (rosa-pêssego):

HEX: #F7A7A6

RGB: 247, 167, 166

Meio do gradiente (rosa-lavanda suave):

HEX: #D7A6E8

RGB: 215, 166, 232

Fim do gradiente (lilás/roxo claro):

HEX: #9E8BFF

RGB: 158, 139, 255

<br>
<p align="left">
  <img src="Documentação/paleta_streamall.png" alt="Paleta de Cores do Projeto" width="300px">
</p>
<br>

📝 Licença
Este projeto está sob a licença MIT.

🦸 Autor
Feito com ❤️ por Emanuelly de Oliveira.
