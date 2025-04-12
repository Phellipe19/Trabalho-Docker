# Google Clone (HTML + CSS + Docker)

Este projeto é uma copia simples da pagina inicial do google, feita com HTML e CSS puros. Ele é servido usando um container Docker com Nginx.

## 📦 Tecnologias usadas

- HTML5
- CSS3
- Docker
- Nginx (como servidor web)

---

## 📁 Estrutura do Projeto
Google-Clone/
├── Dockerfile       # Instruções para construir a imagem Docker
├── nginx.conf       # Configuração personalizada do Nginx
├── index.html       # Página inicial (clone do Google)
├── styles.css       # Estilo da página
└── README.md        # Documentação do projeto

## 🚀 Como rodar o projeto com Docker

### 🔧 Pré-requisitos

- Docker instalado e em execução na máquina  
  (Docker Desktop no Windows/macOS ou Docker Engine no Linux)

---

### 1. Clone o repositório

git clone https://github.com/seu-usuario/google-clone.git
cd google-clone

### 2. Construa a imagem Docker
docker build -t google-clone .

### 3. Execute o container Docker
docker run -d -p 8080:80 google-clone

### 4. Acesse a aplicação no navegador
http://localhost:8080
Você verá a página inicial do Google estilizada com HTML e CSS puros.
