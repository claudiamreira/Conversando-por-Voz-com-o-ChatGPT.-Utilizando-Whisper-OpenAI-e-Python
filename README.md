# 🎙️ Conversando por Voz com o ChatGPT utilizando Whisper, OpenAI e Python

## 📌 Descrição

Este projeto tem como objetivo criar uma interação por voz com o ChatGPT, utilizando **Python**, **Whisper** para reconhecimento de fala e a **API da OpenAI** para geração de respostas inteligentes.

A proposta é permitir que o usuário grave um áudio, converta a fala em texto e envie esse conteúdo para o ChatGPT, recebendo uma resposta de forma automatizada.

---

## 🚀 Tecnologias utilizadas

- Python  
- JavaScript  
- Google Colab  
- Whisper (OpenAI)  
- OpenAI API  
- IPython Display  

---

## ⚙️ Funcionalidades

- Gravação de áudio pelo navegador  
- Conversão de fala em texto utilizando Whisper  
- Envio do texto transcrito para a API da OpenAI  
- Geração automática de respostas utilizando o ChatGPT  
- Execução simples em ambiente Google Colab  

---

## 📂 Estrutura do projeto

```bash
Conversando-por-Voz-com-o-ChatGPT/
│
├── README.md
├── projeto.ipynb
├── requirements.txt
└── assets/
```

---

## 🧠 Como funciona

1. O usuário grava um áudio diretamente no navegador.
2. O áudio é capturado e convertido em arquivo.
3. O modelo **Whisper** realiza a transcrição da fala para texto.
4. O texto transcrito é enviado para a **API da OpenAI**.
5. O ChatGPT gera uma resposta baseada na mensagem recebida.

---

## ▶️ Como executar o projeto

### 1️⃣ Clone este repositório

```bash
git clone https://github.com/seu-usuario/Conversando-por-Voz-com-o-ChatGPT.-Utilizando-Whisper-OpenAI-e-Python.git
```

### 2️⃣ Acesse a pasta do projeto

```bash
cd Conversando-por-Voz-com-o-ChatGPT.-Utilizando-Whisper-OpenAI-e-Python
```

### 3️⃣ Instale as dependências

```bash
pip install -r requirements.txt
```

### 4️⃣ Configure sua chave da API da OpenAI

Defina sua chave em uma variável de ambiente ou diretamente no código.

Exemplo:

```python
import os
os.environ["OPENAI_API_KEY"] = "sua-chave-aqui"
```

### 5️⃣ Execute o notebook ou script

O projeto pode ser executado no **Google Colab** ou em ambiente local utilizando **Jupyter Notebook**.

---

## 📋 Pré-requisitos

Antes de executar o projeto, você precisa ter:

- Python 3.10+ instalado  
- Conta na OpenAI  
- Chave de API válida  
- Ambiente Jupyter ou Google Colab  

---

## 💡 Aprendizados

Durante o desenvolvimento deste projeto foi possível praticar:

- Integração com APIs
- Manipulação de áudio com Python
- Reconhecimento de fala com Whisper
- Uso do ChatGPT em aplicações reais
- Automação de fluxo entre voz e texto

---

## 🔮 Melhorias futuras

- Converter a resposta do ChatGPT em **áudio (Text-to-Speech)**  
- Criar uma **interface gráfica** para interação  
- Implementar **histórico de conversas**  
- Melhorar tratamento de erros  
- Transformar em uma **aplicação web**

---

## 👩‍💻 Autor

Projeto desenvolvido por **Clau** como parte dos estudos em **Python, Inteligência Artificial e integração de APIs**.

---

## 📄 Licença

Este projeto foi desenvolvido para fins **educacionais e de aprendizado**.
