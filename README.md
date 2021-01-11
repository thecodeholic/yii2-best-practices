# Yii2 Best Practices
This repository contains best practices and recommendations about Yii2 framework

## Database

#### Naming database tables
Name your tables always in singular form (Ex: `user`, `article`, `country`). <br>
Naming your tables in plural form (Ex: `users`, `articles`, `countries`) will cause by default models to have name in plural as well (Ex: `Users`, `Articles`, `Countries`) and you will have to manually change the generated model names in relations.
