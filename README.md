para o backend faça isso:

npm init -y

npm install express cors dotenv jsonwebtoken mongodb passport passport-local

npm install nodemon --save-dev

no package.json:

  "scripts": {
      "dev": "nodemon src/index.js"
  },
  "type": "module",