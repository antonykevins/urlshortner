# urlshortner

Simple Url shortner service

Use postman or soap UI to invoke apis

To create entry:

http method : POST  
url : http://localhost:8081/urlshortner/create
Body : <your-longURL>
Response : <7 digit Alphanumeric code>
  
To get long URL:

http method : GET  
url : http://localhost:8081/urlshortner/<7 digit Code>
Response : <7 digit Alphanumeric code> and its corresponding long URL
