# Read 06: Duckett: JavaScript & jQuery

    var today = new Date();
    var hourNow = today.getHours();
    var greeting;
    
    if (hourNow > 18) {
        greeting = 'Good evening!';
    } else if (hourNow > 12) {
        greeting = 'Good afternoon!';
    } else if (hourNow > 0) {
        greeting = 'Good morning!';
    } else {
        greeting = 'Welcome!';
    }
    
    document.write('<h3>' + greeting + '</h3>');
 
 ## Here's what I learned from implementing the above code:
 
 - Initialize new variables like this: `var` + `variable-name` + `=` + `however you want to define your variable`
 - You can put stuff that you want the program to return inside curly braces.
 - sintax for if, else if, else then stuff is like this:  
     if (*condition*) {
     *"whatever you want it to do"*
     }
     
![coffee](https://www.incimages.com/uploaded_files/image/970x450/getty_938993594_398960.jpg)
