# __Topics-rules__

In Arqiva, markdown files are called __topics__. 
Creating a topic is to create a markdown file. *The topics are placed under the __topics__ directory*. 


Arqiva comes with a naming __convention__ that must be followed while creating topic files and folders:


* The folder and file names __must have two leading digits__ followed by an underscore character: _
* The topic files __must have the .md extension__
* The topic file and folder names __must only have one underscore character__, the underscore after the two leading digits.

## __Valid topic file and folder names examples__
```js
    01_hello-world.md
    02_metting-arqiva.md
    03_Entering-another-galaxy.md
    04_more-topics
    05_example-topics
```

## __Invalid topic file names examples__
```js
    01_hello_world.md //multiple underscores not allowed
    002_metting_arqiva.md //three leading zeros not allowed
    03_Entering-another-galaxy.html //file extension must be .md
```


## __Leading-digits__

The two-leading digits are used to determine the position of each topic in the topics tree. That two digits are used
to determine the topics sequence : next and previous. __Make sure the numbers are showing the correct order__.


## __Web URLS__

This topic file:
```js
    topics/01-examples/01-first-topic.md
```

Will be mapped to:
```js
    topics/examples/first-topic.html
```
