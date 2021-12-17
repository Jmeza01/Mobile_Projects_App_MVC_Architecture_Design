# CS-360-Mobile-Architect-and-Programming
### Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?
The user needs that the mobile application that was designed was made for keeping a user inform of new, old, and updated product being imported or exported from the Inventory Warehouse. Thanks to this application program, a user is able to keep track at any mobile device and keep records of all old and new inventory that goes into the Corporate Distribution Warehouse.
### What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?
My screens and features implemented in the mobile application supported the user needs and have produce effective work tasks in keeping organized in a table new items or product before they are sent out. Also, the features that were used in each screen were applicable to security and tracking measurments for example, the first screen had a login and registration page to figure if the user is cleared to use the mobile application service and the second screen after login, this is where there is a table view created in grid layout to share all new items in the inventory and have a SMS message go through the user phone number to let him/her know if they are running low in inventory. I kept my user informed by giving SMS permission via text or call depending on what they choose to communicate when inventory needs attention to be restocked again. Thank God, I got to design my UI as professional and intuitive for a user to friendly use the program to their advantage and to easily comply with their essential duty at work.
### How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future?
###### First, I had to go into creating a flow chart on the expectations that my client or user will have in order for the mobile app to be completely functional prior to their expectations. As I plan and analyze these requirements, then I start to work with Android Studios UI design to open a main java file along with the UI View xml file. By looking into OOP model, which has the UML flow chart and designing a UML class diagrams, here I will start to all UML class diagrams in MS Excel for different objects that have its unique aspects from the program along with provided constructive executable java code required in the mobile app. Then, I would consider to create new java and xml files, in order, as it has been planned in the beginning with the flow chart which is my main reference guide to look at the requirements. Finally, I outline my mobile app project to go with the MVC architecture which predominately impact the design approach for this project to be successful for the user to simply enjoy.
###### As I approach to develop my mobile application program, I start to realize that there may be changes in the controller components activities of the MVC architecture that a user needs expectations have currently updated. So, I decide to start researching what providers activities will be used in my project, for example, another website would have the resources that my mobile application will need to accomplish the functionality of a controller component activity. As I develop, I see that I may have to store all created, read, updated or be able to remove data from what the user may want to store into the application which I would consider using an embedded database (SQLite DB) to accommodate with the user requirements when using the application program. Then, I consider logics and functions along the way to keep every part of the app's functionality to be intuitive and simple for a user to friendly use it. It was a pleasure to me to take this course and I wish you the best in your future endeavors.
### How did you test to ensure your code was functional? Why is this process important and what did it reveal?
I had to look at logcat when testing was done in making sure the code was functional at every step of the developing process. This would let me know if a certain snippet of code was created properly with no errors. As I went back and forth with the engineering design from XML and JAVA files, for both that can coordinate together while I coding and design in the MVC architecture. This process is very important because it allows a engineer to look a error syntax rather than waiting until they are done coding and not knowning where the issues were formed in the line of code. 
### Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge?
Where it became challenging to me was working on the model from the MVC architecture process which I had to implenent the API RESTful and SQLite Room embedded Database which will allow the controller to request and respond to the View in the MVC architecture. Here I had to innovate more methods like importing new libraries for the RESTful API to communicate with the Web Servers and had to create a model DOA helper java class to implement the database that will be keeping items in the inventory table from the gridview displayed which will operate in CRUD operations. 
### In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?
The component from the mobile app where I successfully showed knowledge, skills, and experience was in using the Content Provider Element in Manifest Xml file to work with the database which can grant access to the user to modify the user content, products content, or items content from the inventory app. I had created a itemcontent, usercontent, and mycontent (product) to grant access with a URi to find the data from SQLite Room Database of this mobile application. This was a great challenge to first understand the concept of this component and once I learned how it worked then I started to innovate which it worked. Where I found that when a user adds a item content into the database, it will give a URI (Universal Resource ID [Identifier]) and a record number to be added into the database (SQLite Room database). In order for a user to open that item content to read (retrieve) the data, they will need to have granted access from the provider with a Uri which then will display the content into a gridview table as an item where specific details of the item will be exposed. This is when we need to get the content provider component to secure the SQLite Room Databse for us and to help the user to use the CRUD operations while they have access to the data. 
#### CRUD Operations:
###### Create new item
###### Read (retrieve) data from item in Inventory.
###### Update data from item in Inventory.
###### Delete data from item in Inventory.
