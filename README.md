# day01
write a blog on difference between HTTP1.1 VS HTTP2

    HTTP1.1 : HTTP1 loads a single request for every TCP connection
              It use works on the textual format.
              It uses requests resource Inlining for use getting multiple pages
  
     HTTP2 : HTTP2 is much faster and more reliable than HTTP1
             It avoids network delay by using multiplexing
             It works on the binary protocol.
             It uses PUSH frame by server that collects all multiple pages 
             
             
write a blog about objects and its internal representation in javascript  

      Objects in JavaScript is  most important data-type and forms the building blocks for modern JavaScript. These objects are quite different from JavaScript’s primitive data-types(Number, String, Boolean, null, undefined and symbol) in the sense that while these primitive data-types all store a single value each (depending on their types). 
      
      To accessing the value inside the object has two types
      1 type: . method (accessing operator)
      Syntax:console.log(objectname.keyname)
      2 type: box method
      Syntax:console.log(objectname["keyname"])
