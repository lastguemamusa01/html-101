# html-101

install pljugins
- presentation assistant
- live edit (for debug and open in browser the html page)
- prettier

Live template -> with h1 and tab -> generate the automatically the tag
Live template support Emmet -> create a syntax with keystroke html editing fast

div.jumbotron>div.container>h1{hellow, emmet}+p{this is a sample application}      ,  hit tab
ul>li*5


package json you can run and customize your runs


.editorconfig file - you can customize you rules
of indent size, syntax, spaces , etc

https://editorconfig.org/
EditorConfig helps maintain consistent coding styles for multiple developers working on the same project across various editors and IDEs.
ctlr+alt+l  -> reformat code

prettier -> reformatter

preference -> search code style -> (there is html , css and various languages)

go to plugins and install prettier
also install depencies with npm

npm install --save-dev --save-exact prettier

preference -> prettier  -> see node interpreter have project and prettier package is the actual project path

also check in the package.json, that have prettier dev dependencies

"devDependencies": {
  "parcel-bundler": "^1.12.4",
  "prettier": "2.4.1"
}

we need to add comfiguration file
create file named .prettierrc

add json

{
"trailingComma": "es5",
"tabWidth": 4,
"semi": false,
"singleQuote": true
}

open javascript file
right click -> reformat with prettier to apply

intellij hint you about prettier syntax also

http client

single page application -
option is postman

intellij idea menu tools 0> http client -> test restful web service

you can scretae scrateches -> create http request file
rest-api.http

database

- in the right tab
databases
  + button click
  data source -> choose your databases

add name of data base
host , user and password, credentials

after connect you can see the tables in the right tab
get contents
edit content
add new row

lite database editor sql developer etc.

you can run your sql query in sql console
intellij idea give hint about sql language

also you can download data in different document format the query result, tsv, csv , etc.
different kind of export format


- migration

keymap

intellij idea support eclipse, netbenas, visual studio, sublime text, vs code, vim

configurations -> keymap 0<> you see keymap

plugins -> you can down load vs code keymap

you can use shortcut and key combinations of the original another ides


