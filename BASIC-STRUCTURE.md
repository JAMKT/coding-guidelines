# App Structure

## Basic folder structure

    .
    ├── /client           # React or Vue app
    ├── /routes           # Handles routing
        ├── auth.js
        ├── chat.js
        ├── ...
    ├── /models           # Contains database models
        ├── User.js
        ├── Chat.js
        └── ...
    ├── /config           # Stores config files and keys
        ├── passport.js
        ├── dbKeys.js
        ├── devDbKeys.js
        ├── prodDbKeys.js
        └── config.js
    ├── /middleware       # Contains Node.js middleware files
        ├── ...
        └── ...
    ├── app.js            # Main
    └── README.md

## Naming conventions:
* Folders: Lowercase, with dashes `-` as spaces
* JS files (general): Camel-case
* Models and classes: Capitalized. If the name of a model (or class) is composed by more than one word, each word has to be capitalized and there should be no spaces between them
* .md files: Uppercase

### Work In Process
    
