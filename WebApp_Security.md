# Web App Security  
  
## sanitized Input  
we can have many injections to our code by HTML and sql.  

* We must user Cleaning Content  
Not all HTML tags or attributes are dangerous,so it might make sense for you to allow some HTML, as long as you don’t allow the dangerous stuff. For example you might want to allow <p tag> , <th:text tag> and <ul tag> tags, but not <script tag>, <th:utext tag> or <iframe tag> tags.  
* SQL query  
**Unsafe Query**    
![unsafe](./WebSec_Image/unsafe.PNG)  
**Safe Query**    
![safe](./WebSec_Image/safe.PNG)  
  
## Many-To-Many  
**What is the realationship**    
![many](./WebSec_Image/many.PNG)  
**How do it in the Model classes**    
![model](./WebSec_Image/model.PNG)  

  
 Resources : [Mant-to-Many](https://www.baeldung.com/hibernate-many-to-many) 