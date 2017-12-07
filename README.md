

* PiZza-BiteS! is a web application which provides the Pizza ordering system through online. 
 Nowadays there are lots of online food ordering websites but this application will only can 
 be used to order pizza through online. Pizza-Bites is a web application through which a customer 
 can view available pizzas their prices & size. Customer can order pizza anytime by providing their
 required information. There is also a admin page by which a admin can delete a order, add new pizzas,
 delete pizzas, updates prices etc.


**How to set up the code**

1. Install [Node.js](https://nodejs.org/en/download/) and [MongoDB](https://www.mongodb.com/download-center?jmp=nav) on your computer

2. Download this code, and from command prompt run:

   `npm install`


   `bower install`


3. To run the code, run:

    `node server.js`

    
4. In the browser open http://localhost:3000/, and you should see the index page

**Exposed APIs**:

GET **/api/articles** (returns list of articles)

POST **/api/articles** (create new article)

GET **/api/articles/:articleId** (returns an article with matching id)

DELETE **/api/articles/:articleId** (deletes the matching article)

GET **/api/articles/edit/:articleId** (returns an article with matching id)

PUT **/api/articles/edit/:articleId** (updates the matching article)
