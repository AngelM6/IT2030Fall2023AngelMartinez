For week 5 lab continuing from week 2 lab, I put the two paragraphs on the home page into 2 separate columns, changed the color of the nav bar to dark blue, applied the img-fluid rounded class to the flower.png image and changed the heading on the homepage.
$~$
I added an About Us page link to the nav bar as well as a razor view for the page and added the history, mission, and vison of MGN Clothing co.
I also added a Contact us page link to the nav bar and razor view for the page. Added a model called ContactModel.cs within the models folder to gather the information the user is inputting such as their first name, last name, address, phone number, email, and their message.
<br />
To allow the user to input their information, I added new folder in the views folder called “Contact” and created a razor view.
I then added ContactController.cs within the Controllers folder to have the two index action methods HttpGet attribute and return a View and HttpPost attribute to accept a ContactModel object as input and return a view of the model
<br />
I did have issues with this lab in ContactModel.cs within the Models folder I forgot to add a ? to public string since there were 6 properties I copied and pasted each one to go by quicker without making sure my syntax was fine before doing so and I also had logic errors in Index.cs.html within the Views and Contact folder and in ContactControllers.cs within the Controllers folder where I was not able to be able to submit the inputted data and clear button as I was receiving errors, but found my errors and fixed them.

