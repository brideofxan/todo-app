Vi ska bygga Student Manager med Express, JavaScript, SQLite, SQL

1. Generera inledande projektfiler:

npx express-generator --view=ejs --git student-manager

https://expressjs.com/en/starter/generator.html

--view=ejs
https://ejs.co/ -> view engine som genererar HTML
	blandar javascript med HTML -> ren HTML

https://expressjs.com/en/guide/using-template-engines.html

--git
Gör att vi får en .gitignore-fil <- ?????


EJS
<p><%= name %>'s Pug source code!</p>

Mustache
<p>{{name}}'s Pug source code!</p>

PUG
p #{name}'s Pug source code!

2. Hoppa nere i katalogen som skapades

cd student-manager

3. Öppna projektet i VS Code

code .

. = nuvarande katalog
.. = förälderkatalogen

CTRL + SHIFT + Ö   / CTRL + J = öppna den integrerade terminalen

4. Installera beroenden

npm install

5. Installera nodemon (ladda ner nodemon)

npm install nodemon --save-dev
 alt
npm install nodemon -D 
 alt
npm i nodemon -D 

6. Uppdatera package.json

"scripts": {
  "start": "nodemon ./bin/www"
},

7. Starta applikationen

npm start

Vi har nu satt upp projektet och är redo att börja utveckla.

Men först!

Skapa README.md (markdown)

8 - Skapa repo

git init

9 - Gör första commit

# lägg till alla filer i "staging area"
git add .

# skapa commit som inkluderar alla filer från "staging area"
git commit -m "Initial commit"

10 - Gör en enkel ändring i README.md

Skapa sen ny commit.

11 - Ladda upp till GitHub  (UTMANING)

