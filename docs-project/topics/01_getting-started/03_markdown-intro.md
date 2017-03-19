# __Introducing markdown__

> Did you know that this documentation was generated using arqiva?
  > This topic you are reading was written using markdown.

We wont be taking too much of your time. We will be showing you some markdown syntax tricks that you will need while writing your topic files.

## __Basic formatting__
###  __Bold__

Markdown code:
```md
    __Example bolded__
```

Html output:
```html
    <b>Example bolded<b/>
```

### __Italic__

Markdown code:
```markdown
    *Example italized*
```
Html output:
```html
    <i>Example italized<i/>
```

## __Heading__

### __Heading levels__

One # represents __h1__, two # represent __h2__, then, you can guess the rest.

Markdown code:
```md
    # I'm a big title
```
Html output:
```html
    <h1>I'm a big title</h1>
```

## __Links__

Markdown code:
```markdown
    [click here](http://google.co.mz)
```
Html output:
```html
    <a href=http://google.co.mz"">click here</a>
```


## __Images__

Markdown code:
```markdown
    ![Java Image](https://java.languages/logo.png "Java Logo")
```
Html output:
```html
    <img src="https://java.languages/logo.png" alt="Java Image" title="Java Logo"/>
```


## __Code syntax highlighting__

This markdown:

``` markdown

         ``` java
             public static void main(String[] args){
                
                  System.out.println("Hello world");
                
             }
         ```
```

Is transformed into the following html:

```html
   
   <pre>
   
        <code class="language-java">
            
            public static void main(String[] args){
                        
                 System.out.println("Hello world");
                        
            }
            
        </code>
        
   </pre>
   
```

The html is then displayed like this:
 ``` java
 
    public static void main(String[] args){
                
        System.out.println("Hello world");
    }
    
```

