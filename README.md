# [start.webstream.dev](https://start.webstream.dev/)

## Czym jest Webstream?

+ [about.webstream.dev](https://about.webstream.dev/#/)
+ [www.webstream.dev](https://about.webstream.dev/#/)
+ [docs.webstream.dev](https://docs.webstream.dev/#/)


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


# Environment


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



# DevOps

# First Steps with .apicra

## on linux

### install
    sh .apicra/install

install promagen

    sh .apicra/promagen

### start
    sh .apicra/start

### open in browser
    sh .apicra/browser

## on windows

### install
    .apicra\install.bat

### start
    .apicra\start.bat


### open in browser
    .apicra\browser.bat




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


# Suggestions


## FLOW of creation with webstream
focus on small defined problem in some context and make the context smaller by the iteration

**Create just one function**

+ Don’t create all in one class.
+ Think about your problem and solve it by many functions, but make it more generic to extend with another functions

**Deliver in small pieces*+

+ Do not bury your work on the long-living branch.
+ There is a high risk that you will never finish that.
+ Break it up into smaller pieces and deliver on each piece, one by one.
  + extend the functionality by modularisation

**Take care of the documentation*+

+ without documentation, no one will use your code.
+ Make a README one file documentation


**Create a CI / CD flow*+

+ Many tools allow you to configure a free CI process for Open Source projects expressly:
  + DevOps, Github Actions, Travis, etc.
+ User should started the code-base without failure.
  + The repository should be builded and tested.
+ This is crucial for potential contributors.


**Join the community*+

**communication channel**
Every popular library has its communication channel, be it Slack, Gitter, Discourse or a mailing list.

Join it, check how people communicate with each other and how they help on issues.
Verify if this is the place you want to be.

From such a channel, you can also assess whether the community is alive.
If there are active discussions, there is a greater chance that the library is maintained.


**Help others**

Open Source, as the name suggests, is about being OPEN.

Even if you do not consider yourself an expert, your advice may be valuable to someone.
Don’t be afraid that someone will tell that: you’re wrong.
Even if someone criticizes your work, you will at least learn something new.
You will confront your thinking.



## About Webstream

+  Website about Webstreaming on github - [web-stream/www](https://github.com/web-stream/www)

## About Tom Sapletta

+ [Contact on linkedin](https://www.linkedin.com/in/tom-sapletta-com/)
+ [Tom Sapletta Blog - Embedded System Software & Hardware Developer](https://tom.sapletta.com/)
+ [Softreck Company - Leadership Through Software Development](https://softreck.com/)


## Devops supported by [Api Foundation](https://www.apifoundation.com)

+ [.apicra](https://www.apicra.com) - bash scripts to prepare environment
+ [.apifunc](https://www.apifunc.com) - funkcje, implementacja apiunit
+ [.apiunit](https://www.apiunit.com) - metadane potrzebne do stworzenia aplikacji
+ [.apibuild](https://www.apibuild.com) - budowanie plaikacji, deployment
+ [.apiterminal](https://www.apiterminal.com) - devops terminal by web


## Substantively supported by: 

+ [SaaS is King .com](https://www.saasisking.com/)
+ [hyper Modularity .com](https://www.hypermodularity.com/)


## Sponsored by:

+ [Softreck - Leadership Through Software Development](https://softreck.com/)




---
+ [edit](https://github.com/web-stream/start/edit/main/README.md)

```
https://github.com/web-stream/start.git
```


