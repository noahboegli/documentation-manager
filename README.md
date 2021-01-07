# documentation-manager  
`documentation-manager` will be a web-based software to manage your IT documentation the way it is supposed to be managed in the 21st century. 

Services, devices, applications and servers are connected together, but how do you represent these links with a PDF file inside a shared folder? 

The goals of `documentation-manager` are

- A clean, modern user interface
- A software built on open-source
- Keeping all the advantages of a classic KB/EDM software (versionning, expiration dates, etc...)
- Connecting documents together
    - A server is a document
    - An application on the server is a document
    - The interface between the server and the application can be a document


> `documentation-manager` is a project for a "one commit a day" challenge.

## Architecture
The back-end will consist of an API, that will then be called through a separate application that will act as front-end.  
TypeScript will **not** be used.


## Languages & frameworks
### Back-end
- PHP 8+
    - Slim
### Front-end
- VueJS
    - VueX
    - VueRouter
- SaSS
    - Bootstrap
