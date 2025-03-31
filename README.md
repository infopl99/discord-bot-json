# Bot Discord avec Configuration JSON

Un bot Discord basique utilisant des configurations JSON pour gérer facilement les commandes, les réponses et les paramètres.

## Fonctionnalités

- Structure organisée avec fichiers de configuration JSON
- Commandes de base : ping, help, clear
- Messages de bienvenue et d'adieu automatiques
- Système d'erreurs et de réponses personnalisables

## Installation

1. Clonez ce dépôt
   ```
   git clone https://github.com/infopl99/discord-bot-json.git
   cd discord-bot-json
   ```

2. Installez les dépendances
   ```
   npm install
   ```

3. Configurez votre bot
   - Copiez `config/config.example.json` vers `config/config.json`
   - Ajoutez votre token Discord et autres informations requises
   - Ou utilisez les variables d'environnement en copiant `.env.example` vers `.env`

4. Démarrez le bot
   ```
   npm start
   ```