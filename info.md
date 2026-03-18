# 1. Inicializa o repositório Git na pasta
git init

# 2. Adiciona os arquivos (respeitando o .gitignore)
git add .

# 3. Cria o primeiro commit
git commit -m "Initial commit: Integração Gemini com gTTS e suporte local"

# 4. Conecta ao seu GitHub (Crie um repo vazio chamado 'conversando-por-voz' no GitHub antes)
git remote add origin https://github.com/LuGodoy/conversando-por-voz.git

# 5. Define a branch principal e envia
git branch -M main
git push -u origin main