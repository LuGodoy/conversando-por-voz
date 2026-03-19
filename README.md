# 🎙️ Conversando por Voz

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?logo=python&logoColor=white)
![Google Colab](https://img.shields.io/badge/Colab-IDE-F9AB00?logo=googlecolab&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-AI-4285F4?logo=google&logoColor=white)<br>
![Whisper](https://img.shields.io/badge/Whisper-STT-000000?logo=openai&logoColor=white)
![gTTS](https://img.shields.io/badge/gTTS-TTS-FF6F00)

Projeto de interação por voz com IA generativa utilizando **Whisper**, **Google Gemini** e **gTTS**.  
Permite enviar áudio, interpretar a fala e receber uma resposta também em áudio.

---

## ✨ Visão Geral

Este notebook executa um fluxo completo de conversa por voz:

1. 🎤 Grava o áudio do usuário  
2. 🧠 Transcreve com Whisper  
3. 🤖 Gera resposta com Google Gemini  
4. 🔊 Converte a resposta em áudio  

---

## 🚀 Como Executar no Google Colab

### 1. Baixar o notebook

1. No GitHub, abra o arquivo `conversando_por_voz.ipynb`  
2. Clique em **Download raw file** (ícone de download)  
3. Salve o arquivo no seu computador  

---

### 2. Abrir no Colab

- Acesse o Google Colab  
- Vá em **Arquivo > Fazer upload de notebook**  
- Selecione o arquivo `.ipynb`

---

### 3. Configurar sua API Key (Gemini)
> **Obs.:** Se ainda não tem a `GOOGLE_API_KEY`, crie a sua gratuitamente no [Google AI Studio](https://aistudio.google.com/).

Para utilizar o modelo de IA:

1. No menu lateral esquerdo, clique no ícone de **🔑 Secrets**  
2. Crie uma variável chamada: `GOOGLE_API_KEY`
3. Cole sua chave da API  
4. Ative a chave para o notebook  

---

### 4. Executar o projeto

- Execute as células na ordem  
- Autorize o uso do microfone (quando solicitado)  
- Grave sua pergunta  e execute as celulas seguintes
- Ouça a resposta gerada pela IA 🎧  

---

## 🧠 Tecnologias Utilizadas

- **Whisper (OpenAI)** — transcrição de áudio  
- **Google Gemini** — geração de respostas  
- **gTTS** — conversão de texto em voz  
- **Python** — linguagem principal  

---

## 🛠️ Funcionalidades

- 🎤 Entrada de voz diretamente no navegador  
- 🧠 Transcrição automática  
- 🤖 Respostas inteligentes com IA  
- 🔊 Resposta em áudio  
- 🧹 Limpeza de texto para melhor leitura  

---

## ⚠️ Observações
- Este projeto faz parte de um desafio DIO/Banco Bradesco 
[Aqui](https://web.dio.me/project/conversando-por-voz-com-o-chatgpt-utilizando-whisper-openai-e-python/learning/91e3c941-0742-411a-aaef-0cf115cead00?back=/track/bradesco-genai-dados&tab=undefined&moduleId=undefined)

- O projeto foi desenvolvido para rodar no Google Colab  
- A gravação de áudio utiliza JavaScript integrado ao notebook  
- É necessário permitir acesso ao microfone no navegador  

---

## 👩‍💻 Autora

**Luciene**  
AI Agents • Data Science • Software Engineering • Matemática  



