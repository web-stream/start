# [start.webstream.dev](https://start.webstream.dev/)

## Czym jest Webstream?

+ [about.webstream.dev](https://about.webstream.dev/#/)
+ [www.webstream.dev](https://about.webstream.dev/#/)
+ [docs.webstream.dev](https://docs.webstream.dev/#/)
+ [roadmap.webstream.dev](https://roadmap.webstream.dev/#/)


## Nasz -> Twój zespół
+ [team.webstream.dev](https://team.webstream.dev/)


## Inne projekty do których możesz dołączyć i współtworzyć
+ [projects.wapka.pl](https://projects.wapka.pl/)


## Jak wesprzeć projekt?
+ [partnership.webstream.dev](https://partnership.webstream.dev/#/)


## Jakie mamy plany?
+ [roadmap.webstream.dev](https://roadmap.webstream.dev/#/)


# Start

+ Wyslij username pod którym działasz na github
+ po dodaniu i nadaniu praw do pracy z projektem zapoznaj się z listą zadań

## Zadania do wykonania

+ [task.webstream.dev](https://task.webstream.dev/#/)



### prepare environment:

   node js

### prepare projects

fork the source of webstream:

    github.com/web-stream/src


fork a examples:

    github.com/web-stream/examples


create your own repo on your username:

    webstream-examples


### testing

start to use the project

### coding

start to change the source code to find the bugs or implement the features

### unittesting

every time you changed the code or you produced somthing new, check the unittest


### get the next task

every time you are starting the next task, please create the new folder as task number

    [webstream main project folder]/[task number]/[webstream sourcode]

put to the file:

    github.txt 


the branch url in content


### load the sourcode over apicup commmands:

    sh github clone


### check if work

    sh test



### create sourceode changes and 

    sh test


### if everything is OK, push on server

    sh push
  

### After you finish , please make a MR

    sh github mr




# codereview

After you finish I will check your code
If everything will be correct I will merge

if not I will write you some info



## Kod źródłowy

Biblioteki/Funkcje podstawowe:

    https://github.com/apifunc/js/tree/master/src

Kod źródłowy Webstream:

    https://github.com/web-stream/src

Biblioteki Funkcje zewnętrzne potrzebne do renderowania, np MARKDOWN

    https://revealjs.com/installation/#full-setup

### kompilowanie pojedynczej funkcji


### przygotowanie paczka webstream.min.js
    
    clone https://github.com/web-stream/build

win

    build-all.bat

lx (todo)

    build-all.sh
    
File [build-all.bat](https://github.com/web-stream/build/blob/main/build-all.bat)

    type ".\src\meta\*.js" > .\jloads.js
    type ".\src\core\*.js" >> .\jloads.js
    type "..\apifunc-js\src\*.js" >> .\jloads.js
    type ".\src\event\*.js" >> .\jloads.js
    type ".\src\include\*.js" >> .\jloads.js
    type ".\src\load\*.js" >> .\jloads.js
    type ".\src\*.js" >> .\jloads.js
    type ".\src\form\*.js" >> .\jloads.js
    type ".\src\url\*.js" >> .\jloads.js
    type ".\src\jloads\*.js" >> .\jloads.js
    type ".\src\all\*.js" >> .\jloads.js
    uglifyjs jloads.js -o jloads.min.js -c -m




---
+ [edit](https://github.com/web-stream/start/edit/main/README.md)

```
https://github.com/web-stream/start.git
```


