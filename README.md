# 🎓 UNIPENSE AI: Pesquisa Inteligente, Aprendizado Eficiente | Smart Research, Efficient Learning

[![MIT License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Status](https://img.shields.io/badge/status-prototype-blue)]()
[![Powered by FastAPI](https://img.shields.io/badge/backend-FastAPI-green)](https://fastapi.tiangolo.com/)
[![Frontend in React](https://img.shields.io/badge/frontend-React-blue)](https://react.dev/)
[![OpenAI + LangChain](https://img.shields.io/badge/AI-OpenAI%20%2B%20LangChain-ff69b4)](https://www.langchain.com/)

---

## 📘 Sobre | About

🇧🇷 O **UNIPENSE AI** é um sistema inteligente desenvolvido para auxiliar universitários na **busca de conteúdos acadêmicos**, de forma **rápida, confiável e resumida**. Ele integra múltiplas fontes reconhecidas (como Google Scholar, SciELO, Wikipedia etc.) com uso de IA para entregar **respostas relevantes com linguagem acessível**.

🇺🇸 **UNIPENSE AI** is an intelligent system designed to help university students search for **academic content** in a **fast, reliable, and summarized** way. It integrates multiple trusted sources (such as Google Scholar, SciELO, Wikipedia, etc.) and uses AI to provide **relevant and easy-to-understand answers**.

---

## ✨ Funcionalidades | Features

- 🔍 **Busca simultânea** em múltiplas fontes confiáveis.  
  🔍 **Simultaneous search** across multiple trusted sources.

- 🧠 **Resumos automáticos** com IA (OpenAI + LangChain).  
  🧠 **Automated summaries** using AI (OpenAI + LangChain).

- ⚙️ **Interface moderna e responsiva** em React.  
  ⚙️ **Modern and responsive interface** in React.

- ☁️ Integração com **Firebase** e **Heroku/Google Cloud**.  
  ☁️ Integration with **Firebase** and **Heroku/Google Cloud**.

- 🔒 Sem armazenamento de dados sensíveis.  
  🔒 No sensitive user data is stored.

---

# 🚀 Como Executar Localmente | How to Run Locally

## 🔧 Pré-requisitos
Python 3.10+
Node.js + npm
Git (opcional, para clonar o repositório)

## 🧠 Backend (FastAPI + LangChain)
Acesse a pasta do projeto:
bash
cd unipense-ai/backend

Crie um ambiente virtual (opcional, mas recomendado):
bash
python -m venv venv
- No Windows: venv\Scripts\activate
- No Linux/macOS: source venv/bin/activate  

Instale as dependências:
bash
pip install -r ../requirements.txt

Inicie a API:
bash
uvicorn main:app --reload
A API estará disponível em: http://localhost:8000

## 💻 Frontend (React)
Acesse a pasta do frontend:
bash
cd ../frontend

Instale os pacotes:
bash
npm install

Inicie o servidor React:
bash
npm start
A aplicação estará disponível em: http://localhost:3000

## 🔐 Variáveis de Ambiente
Crie um arquivo .env na raiz com base no .env.example.
Exemplo:
env
OPENAI_API_KEY=your_openai_api_key
FASTAPI_PORT=8000


# 📅 Cronograma | Timeline
Confira o cronograma do projeto em [Cronograma](https://github.com/galdino013/TCC/blob/main/cronograma.md)
See project timeline in [Cronograma](https://github.com/galdino013/TCC/blob/main/cronograma.md/main/cronograma.md)

# 👥 Equipe | Team
- Igor Galdino
- Leonardo Marana
- Lukas Andrade Nascimento
- Pedro Henrique de Souza Putinatti
- Erick Patrick

# 📄 Licença | License
Este projeto está sob a licença MIT.
This project is licensed under the MIT License.
Veja o arquivo LICENSE para mais detalhes.
See LICENSE file for more details.
