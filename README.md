# Conversando por Voz 🎙️

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/LuGodoy/conversando-por-voz/blob/main/conversando_por_voz.ipynb)

Este projeto utiliza o Google Gemini e gTTS para criar uma interface de interação por voz, processando dados e transformando respostas de texto em áudio sintetizado.

---

## 🚀 Como Executar no Google Colab

Siga os passos abaixo para testar o projeto diretamente no seu navegador:

### 1. Clonar o Repositório
Copie e cole o código abaixo em uma célula do Colab para baixar os arquivos necessários:

```python
# Clona o repositório
!git clone https://github.com/LuGodoy/conversando-por-voz.git

# Entra na pasta do projeto
%cd conversando-por-voz

### 3. Instalar Dependências
Execute a célula abaixo para instalar as bibliotecas necessárias (como gTTS e google-generativeai):

```python

!pip install gTTS google-generativeai

```

### 4. Configurar sua API Key
Este projeto requer uma chave do Google Gemini. Para manter a segurança:

- No menu lateral esquerdo do Colab, clique no ícone de Chave (Secrets).

- Adicione uma nova chave com o nome GOOGLE_API_KEY.

- Ative a chave para este notebook.

### 🛠️ Funcionalidades
- Processamento de Linguagem Natural: Integração com modelos Gemini.

- Conversão Texto-Voz: Utilização da biblioteca gTTS para sintetizar respostas em áudio.

- Limpeza de Markdown: Scripts integrados para remover formatações (como asteriscos) antes da leitura por voz.

### 👨‍💻 Autor
Desenvolvido por Luciene (Lu).
### O que foi personalizado:
* **Link do Git:** [aqui](https://github.com/LuGodoy/conversando-por-voz.git)
* **Dependências:** Adicionei as bibliotecas que o seu notebook utiliza (`gTTS` e `google-generativeai`).
* **Destaque para Voz:** Incluí a seção sobre a limpeza de Markdown e síntese de voz, que é o núcleo do seu arquivo `.ipynb`.
