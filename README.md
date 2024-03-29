
# IIUM FOOD AND BEVERAGES APPLICATION PROJECT

## GROUP MEMBERS  

**Name**                            | **Matric Number**
----------------------------------- | -------------
BELAL ABDULQAWI ALQADASI            | 1619091
HANAN HAIDAR ALATAS                 | 1624552
HUSSAIN K M TANSIR                  | 1638331
PROMI JARIN TASNIM                  | 1637892
ISLAM MOHAMMAD RAIHANUL             | 1825891


**Group Name :** Group E

**Instructor’s Name :** Dr. MOHD KHAIRUL AZMI BIN HASSAN


## Title 
IIUM FOOD AND BEVERAGES



## INTRODUCTION
International Islamic University Malaysia (IIUM) has a wide variety of food and cuisine choices where students can find a hard time figuring out what meals are the most recommended. Besides, students are hard to know the business hour for every cafeterias as they have different opening and closing time.

IIUM Food Review App is designed to help user in finding meals in IIUM Gombak campus. They can view all cafeterias that are available in IIUM as well as their opening and closing time. It also allows user to give feedback, review and rating for any meal in IIUM. Moreover, they can capture their enjoyable moments with the meal and share it publicly as the memories because it allows users to use their mobile camera to take photo of the meal and write a note about it.

IIUM Food Review App will display all choices that are available in each cafeteria and others' feedbacks and ratings publicly as well as their precious moments with the meal. Our targeted users are students, staff and visitors of IIUM as they can easily get the apps and sign up for free using their e-mail. Anyone that wish to find the most delicious and unique meal might need IIUM Food Review Apps.


## OBJECTIVES
1. User can easily view various meals that are available at cafeterias in IIUM.
2. Allow users to give feedbacks and ratings for any meals that are available at the cafeteria.
3. Allow users to use their mobile camera to take photo of the food and write a note about it.
4. Increase the promotion of cafeterias in IIUM.
5. User can give their suggestion or complain for pricing and others things.




## FEATURES AND FUNCTIONALITIES OF THE MOBILE APPLICATION

### Features

Features | Explanation
------------ | ----------------------------
Sign Up | User need to fill in register form for the first time
Log In | User log in to the app using email and password
Homepage | Display all cafeterias in IIUM, most popular place, well-like food, their business hours and overall customer rating
Recommended canteen | Displays all the canteens registered with the system
Popular Place | Displays the most popular places 
Popular food | Displays the most liked food and beverages among all cafes
Cafe Profile | Each cafe has its own profile that mentions it’s location, descriptions, food menu operation hour and customer ratings.
Food Menu | User can scroll through the menu in horizontal view
Bookmark | Users can bookmark any cafe as their favorite from the description profile
Food Review | Show ratings of others to the meals in specific cafeterias.
Add Review | Take pictures and upload the moments with the meal.
Media Review | User can view pictures of food and ambiance in Horizontal view
Alert | Customer gets alert after they placed a review
Expendable View | Users can control their view of text for cafe description and food review through see more/less 
Edit profile page | Allow user to edit their profile
Firebase | Store users' information



### Functionalities
**Users: The users will be the Students, staff, and visitors of IIUM**
* They can get the apps and sign up for the first time at no cost. Their information will be stored in firebase.
* They can edit their profile and it will be altered in firebase.
* They can view all cafeterias and their business hours at the home page.
* They can check offered cuisines of each cafes and their specility.
* They can choose to view the meals that are available and others feedback in the page of specific cafeteria.
* They can give feedbacks, ratings and share their pictures while having the meals.


**Admin :**

* Admin will store information about new entry of F&B
* Admin will maintain quantity record for food and beverage 
* Keep the record of customer details
* Update and delete a record
* Admin can manage orders produced from the web application and Android application. 

## SCREEEN NAVIGATION

### Sign Up Page:

![sign up](https://user-images.githubusercontent.com/69639669/121815295-4e96a680-cca8-11eb-90f6-0539d45013d7.jpg)

### Sign In Page:

![login](https://user-images.githubusercontent.com/69639669/121815334-8a317080-cca8-11eb-8e4c-6c7d2e8ee1cd.jpg)

### Home Page:

![home](https://user-images.githubusercontent.com/69639669/121815349-9fa69a80-cca8-11eb-97b7-8665009396dd.jpg)

### Cafeteria Page:

![canteen](https://user-images.githubusercontent.com/69639669/121815387-cebd0c00-cca8-11eb-9e9b-a5628e3fd34a.jpg)
![browser](https://user-images.githubusercontent.com/69639669/121815453-36735700-cca9-11eb-832f-5d6f81fbc9d8.jpg)

### Menu Highlighted Page:

![mahallah](https://user-images.githubusercontent.com/69639669/121815495-5f93e780-cca9-11eb-8f6b-93ec0adf437a.jpg)

### Review Box:

![comment](https://user-images.githubusercontent.com/69639669/121815520-7a665c00-cca9-11eb-9ac7-f93b035b7edc.jpg)

![pic](https://user-images.githubusercontent.com/69639669/121815522-7f2b1000-cca9-11eb-95bc-34cd68e7afe6.jpg)

### Alrt Box:

![alert](https://user-images.githubusercontent.com/69639669/121815542-9538d080-cca9-11eb-8819-b5713fca02e1.jpg)

### Profile Page:

![profile](https://user-images.githubusercontent.com/69639669/121815507-6ae71300-cca9-11eb-8dd7-3b2c5398c4c6.jpg)

## PRESENTATIONAL AND CONTAINER COMPONENTS

Presentational Components | Explanation
------------- | ---------------------------------------
TextInput | To key-in user's details in log in/sign up page & the input of user's review and feedback
Text | To name the title of every page for users' view
View | To display the components used
Button | Used to proceed with log in/ sign up & to view specific cafeterias at homepage & submit reviews and feedback
scrollview  | Used to make the products list scrollable, it can scroll both vertically and horizontally
TouchableOpacity  | Used to reduce the opacity of button. It allows background to be seen while the user press down. The opacity of button will be controlled by wrapping the children in an Animation. 


Container Components | Explanation
------------- | ---------------------------------------
onPress |	Click the button and proceed to the next page & click the given options in the category section for adding the items to the database
onChangeText | Use in TextInput components

## PROJECT CONSTAINTS AND CHALLENGES 

1. Time zone difference of the team member
2. System Configuration
3. Poor internet connection within the campus, and the performance of the laptop used for building the system.
4. Screen compilation
5. The difficulty to apply fonts where there is a warning kept showing on because the default font we use
6. The difficulty to change between the classes and functions inside the project. 
7. Setting timer for a long period of time warning 





## SEQUENCE DIAGRAM:<br />
![Sequence Diagram]![photo_2021-06-13_22-12-54](https://user-images.githubusercontent.com/44799410/121813613-6158ad80-cc9f-11eb-8548-8bbf60d0a58f.jpg)




## REFERENCES

* (2017). Difference between component and container in react redux. stackoverflow. https://stackoverflow.com/questions/43414254/difference-between-component-and-container-in-react-redux
* C. (2018). Codebrahma/React-Native-Restaurant-App. GitHub. https://github.com/Codebrahma/React-Native-Restaurant-App
* (2018). Some Assets photos to iium canteens  https://iiumcafernr.wixsite.com/rate-review?lightbox=dataItem-ihlic3np1
* image uploder to internet https://imgbb.com/
