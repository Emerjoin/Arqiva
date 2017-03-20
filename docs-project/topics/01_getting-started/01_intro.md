# __Getting started__

## What is arqiva?

Arqiva is an extensible java based tool that allows you to write awesome API documentations without much effort using Markdown and HTML together.


## Requirements to get started

  ![Git](../../assets/img/joined.png)
    
  <small><b>Java 8 + Git + Maven 3.3.x</b></small>  
    
## Clone the start-project
The start-project is a __maven-project__ configured with the __arqiva-maven-plugin__ which starts an
embedded web-server to display our docs in a browser as we write them. It also allows to build our project into
static html writing only 3 words.
```bash
    git clone https://github.com/Emerjoin/Arqiva-start-project.git
```


## Run the project
```bash
    mvn arqiva:run
```

### Wait for the following log to appear on your command line:
```bash
    INFO: Starting ProtocolHandler ["http-nio-9610"]
```


## Display the index page on your favorite web-browser
```bash
    http://localhost:9610/arqiva/index.html
```
