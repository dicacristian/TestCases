# TestCases

You can find some test cases that I wrote while working on previous projects. 

______________________________________________________________________________________________________________________________________________________________________

 Test cases for Login and functionality on https://admin-demo.nopcommerce.com/

Test ID : 1

Title : Test login with valid data. 

Description : Check if the login works when a person inserts the correct Admin credentials. 

Test steps : 

1. Go to : https://admin-demo.nopcommerce.com/
2. Add a correct username and password
3. Press "Login" Button

 Expected Results : Admin should be able to login and is taken to the Dashbord page.
   
 Test data : username : admin@yourstore.com and password : admin

______________________________________________________________________________________________________________________________________________________________________

  Test ID : 2

  Title : Test login with invalid data. 

  Description : Check if the login works when a person inserts the incorrect Admin credentials. 

  Test steps : 

 1. Go to : https://admin-demo.nopcommerce.com/
 2. Add a incorrect username and password
 3. Press "Login" Button

 Expected Results : Admin should not be able to login and is taken to the Dashbord page.
   
 Test data : username : admin@store.com and password : admin123

______________________________________________________________________________________________________________________________________________________________________

   Test ID : 3

   Title : Add a new customer functionality on Customers section

   Description : Check if the user can add details into the Text 

   Test steps : 

   1. Go to "https://admin-demo.nopcommerce.com/Admin/Customer/List"
   2. Click on "Add New"
   3. Add "example@yahoo.com" into "Email" field
   4. Add "123123123" into "Password" field
   5. Add "Cristian" into "First Name" field
   6. Add "Dica" into "Last Name" field
   7. Click "Male" on "Gender" field
   8. Add "5/4/1998" into "Date of Birth" field
   9. Add "FC Barcelona" into "Company Name" field
   10. Click and choose "Test Store 2" on "Newsletter" field
   11. Click and choose "Guests" on "Customer Roles" field
   12. Click and choose "Vendor 1" on "Manager of vendor" field
   13. Click "✅" on the "Active" field
   14. Add "Lorem Ipsum is simply dummy text of the printing and typesetting industry."
   15. Scroll Up and click the Save button 

   Expected Results : The new customer has been added successfully. 

   Environmnent : Google Chrome  
   ____________________________________________________________________________________________________________________________________________________________________

   Test ID : 4

   
   Title: Check box functionality on Elements page

   Description: Test if the user can check/uncheck the Button

   Test steps : 
   
   1. Go to https://demoqa.com/elements
   2. Click on "Buttons"
   3. Click on "Right Click Me"

   Expected results: A new message: "You have done a right click" 

   Environment : Mozilla Firefox
      
   ____________________________________________________________________________________________________________________________________________________________________


   Test ID : 5
  
   
   Title: Check size and colors functionality on clothes section

   Description: Test if the user can choose the suggested colors and sizes

   Test steps : 

   1. Go to https://magento.softwaretestingboard.com/
   2. Hover the mouse on "Men" section, after at "Tops" and then to the "Jackets"
   3. Click on "Montana Wind Jacket"
   4. Choose the Green color and M size
   5. Click on "Add to Cart"

   Expected result: A new message: "You added Montana Wind Jacket to your shopping cart." : 

   ![image](https://github.com/dicacristian/TestCases/assets/85904271/5cc5579f-3fcc-46bb-9c56-3ba8931c1306)

 
   Environment : Google Chrome 
   

  ____________________________________________________________________________________________________________________________________________________________________

   Test ID : 6

   Title : Test the delete function from a product that we added to cart

   Description : Trying to test the delete function from a product that was added before

   Test steps : 

   1. Go to https://magento.softwaretestingboard.com/
   2. In the right side, click on shopping cart icon
   3. Click on delete icon button

   Expected result: A new message: "You have no items in your shopping cart."
  ____________________________________________________________________________________________________________________________________________________________________

   Test ID : 7

   Title : The existence of a custom 404 error page

   Description : I tried to modify the original page url to see if it shows the 404 error

   Test steps: 

   1. Go to https://magento.softwaretestingboard.com/
   2. Write in the URL something that does not exist on the website


   Expected result: An error page should appear directing the users to what they are looking for.

   Test Data : https://magento.softwaretestingboard.com/123

  ____________________________________________________________________________________________________________________________________________________________________


  Test Cases for search functionality on https://altex.ro/


  Test ID : 8

  Title: Test the search bar with a specific item 

  Description: Test the search bar by searching a specific item from the site https://altex.ro/

  Test steps : 

  1. Go to https://altex.ro/
  2. Search a specific item in the search bar
  3. Click on the search icon
  4. Observe if user receives the correct results of the searching

  Expected result: User should receive correct and valid results of searching a specific item by using the search bar

  ![image](https://github.com/dicacristian/TestCases/assets/85904271/fa23fb59-f2c6-4521-a07a-9a31708292d5)


  Test data: "iphone 14"

  ____________________________________________________________________________________________________________________________________________________________________

  Test ID : 9

  Title : Test the disponibility and price filter 

  Description : Test the disponibility and price filter for a specific phone that we are looking for

  Test steps :  

  1. Go to https://altex.ro/
  2. Hover the mouse on "Products"
  3. Click on "Phones, Tablets", then click on "Telephones" 
  4. In the left side, on availability section click on "News" section and at the price section click on "4000-5000"

  Expected results: The user should see the phones based on the filters they have selected


  ![image](https://github.com/dicacristian/TestCases/assets/85904271/4b3167f0-8e1e-4d00-b65a-29e9945f5b86)


   ____________________________________________________________________________________________________________________________________________________________________


   Test ID : 10

   Title : Test the search bar with a non-existent item

   Description :  Test the search bar by searching an item that does not exist.

   Test steps : 

   1.  Go to https://altex.ro/
   2.  Search a non-existent item in the search bar
   3.  Press the enter button
   4.  Observe if user receives no valid results and / or suggestions to improve searching

   Expected result: User should receive no valid results of searching a non-existent item and / or suggestions to improve the searching.

   Test data : unudoitrei
