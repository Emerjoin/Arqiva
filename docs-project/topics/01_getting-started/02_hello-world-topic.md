# __Creating the hello-world topic__

1. Create a new file under the following path:
```js
    docs-project/topics/02-hello-world.md
```

You just created a markdown file. 
If you don't know what is markdown, then, you definitely 
need to read [__this__](../../topics/reference/markdown/the-concept.html) before we can continue.

2. Now, please open the file we just created and past the following content:
```md
    # Say hello __world__ to *arqiva*
```


3. Access a command line interface __pointing to the directory__ containing your project and __run the arqiva project__ using the following command:
```bash
    mvn arqiva:run
```
The command above tells arqiva to start it's web-server on the __9610__ port (configurable).
Arqiva will be serving your docs from that port in the __/arqiva__ context path.


4. __Display your new topic in a web-browser__
```bash
    http://localhost:9610/arqiva/topics/hello-world.html
```


## __What to do next?__

Let us show you a few more markdown syntax tricks.