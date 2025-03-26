# Projeto de QA com llmaIndex e Gradio 🚀

Este repositório contém duas aplicações que demonstram a integração entre **llmaIndex** e **Gradio** para a interação com modelos de IA via API do **groq**. Utilizamos o modelo **llma3.3-70b** para realizar tarefas de **Question Answering (QA)** de forma interativa e eficiente.

---

## Visão Geral 📚

### Ferramentas Utilizadas

- **llmaIndex**: Ferramenta para indexação e consulta de dados, facilitando a criação de sistemas de QA.
- **Gradio**: Framework para criação de interfaces interativas que permitem a interação com os modelos de IA via web.
- **groq API**: API que possibilita a integração e o uso de modelos de IA avançados.
- **SQLAlchemy**: Utilizado no Projeto 2 para manipulação e consulta de dados armazenados em um arquivo `.db`.

---

## Projetos

### Projeto 1: QA a partir de arquivo CSV 📊

Esta aplicação permite:
- **Upload de arquivo CSV**: O usuário pode enviar um arquivo `.csv`.
- **Interação via prompt**: A aplicação utiliza prompts fornecidos pelo usuário para extrair informações e responder perguntas sobre o conteúdo do arquivo.
- **Uso do llmaIndex e Gradio**: A integração dessas ferramentas possibilita uma experiência interativa, onde o modelo **llma3.3-70b** processa os dados e responde às consultas.

### Projeto 2: QA a partir de arquivo DB de Vendas 💰

Nesta aplicação, a abordagem é similar, porém com um diferencial:
- **Fonte de dados em SQLite (`.db`)**: A aplicação trabalha com um banco de dados contendo informações de vendas.
- **Integração com SQLAlchemy**: Facilita a manipulação dos dados, permitindo consultas SQL eficientes e dinâmicas.
- **Interface interativa com Gradio**: Os usuários podem enviar prompts e obter respostas detalhadas sobre os dados de vendas.
- **Uso do llmaIndex**: Auxilia na indexação dos dados do banco para uma consulta rápida e precisa.

---



