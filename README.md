# ContactManagement
Contact Management micro project
Summary : This project has 2 parts 
a) Web api , which is created using the clean architecture design principles. This api exposes endpoints 
    1) Get all the contacts 
    2) Get single contact 
    3) Create new contact 
    4) Getting random colours
Web api documentation is in swagger , below is the end point to get all the end points details.
https://localhost:5001/swagger/index.html

b) Contact.UI
  1.User interface to add new contact to the data store
  2. Grid to display all the contacts.
  3. While creating the user , application will store contact information in text file and store that locally.


Steps to run Web api
a) Modify appsettings.json to modify the database connection.
b) Run the migrations. 

Steps to run Conatct UI
  a) Install relevent npm packages.
  

Features not complete 
a) Unit testing not complete
b) UI validation is not complete 
c) Design of contact UI is not good , needs to be separated into components and individual , started creating the structure as below , but still pending
      |
      +---● components
      |   |
      |   +--● Contact 
      |      |
      |      |--index.js
      |      |--ContactForm.js
      |      |--ContactList.js
      |      
      +---● layouts (Form, Table)
      |
      +---● hooks ()
      |
      +---● utils ()
      |
      +---● controls (Input, Button, Select)
