# UMP-XM8-BOT2
Bot Discord com sistema de filas
# Clone o repositório vazio
git clone https://github.com/SEU_USERNAME/bot-discord-filas.git
cd bot-discord-filas

# Crie os arquivos (no seu editor ou terminal)
touch index.js package.json README.md
{
  "name": "bot-discord-filas",
  "version": "1.0.0",
  "description": "Bot Discord com sistema de filas completo",
  "main": "index.js",
  "scripts": {
    "start": "node index.js",
    "dev": "nodemon index.js"
  },
  "keywords": [
    "discord",
    "bot",
    "filas",
    "ranked"
  ],
  "author": "UMP XM8",
  "license": "MIT",
  "dependencies": {
    "discord.js": "^14.13.0"
  },
  "devDependencies": {
    "nodemon": "^3.0.1"
  }
}
