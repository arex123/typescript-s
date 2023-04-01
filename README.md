# Typescript
It is a superset of javascript


<br/>

## Benefits: 
* Static typing
    * examples of statically typed language: C++, C#, Java
    * dynamically types language: Javascript, Python, Ruby
* Code completion
* Refactoring
* Shorthand notations 

<br/>

# Transpilation:

Typescript (.ts) --------> Compiled to -----------> Javascript (.js)



<br/>


## Installation

    npm i -g typescript

    tsc -v   //to check the version of typescript


## Configuration File : To complie ts code to newer version of js syntax

By <b>default</b> typscript on compiling .ts code , it converts <b> older version</b> of javascript,
like <span style="color:yellow;"> when we declare any variable in ts as 'let', on compiling we'll see that variable's type as 'var'</span>
It happens bcauz of typscript , so that that js code could run on even <b>older versions</b> of browsers also without any error, But we can <b> configure</b> it to compile ts code in newer version of javascript

        tsc --init

## Notes
* Every typescript files should have the .ts as a extension
* compile the file using, below cmd will create a new file having sameCode as nameOfFile.ts , but in javascript syntax
    
        tsc nameOfFile.ts

    If above command gives error like, <span style="color:Red; font-size:18px;">"cannot be loaded because running scripts is disabled"</span>
    then use
        
        tsc.cmd nameOfFile.ts