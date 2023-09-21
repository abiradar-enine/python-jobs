<h1 align="center">Django Test</h1>

> The Following test duration is 45 minutes, you can take help of the internet. In case you're taking this test online, it is mandatory to share your screen and record the test.

> Note - For tasks 3 through 40, commit your code changes with a message **Task (number)**. If the task involves no code changes, create a text file for the same and commit it with the above message.

## Tasks
1. Clone the git repository - https://github.com/vishalapte/python-jobs.git and create a branch where you’ll be committing the code changes/answers.
2. Create a virtual environment in your project and activate it, henceforth use this virtual environment for subsequent tasks.
3. Install all the requirements from requirements.txt file in the project and solve for any errors that you might face while doing so. Under the test_data folder (Create if not present) place the command.txt file, record the steps you used to install the requirements in this command.txt file.
4. Identify and solve any problem that you might face while trying to run the server.
5. Navigate to the admin panel and implement steps if required to access the admin panel. (No need to commit for this question. )
6. Change the background colour of ‘2’ to brown. On the ‘Senior Developer Role’ page of the project.
7. Add a new app to the project, name : cars.
8. Create the following models
  	<br>Car model.
      	<br>1. maker : String field : Foreign Key
      	<br>2. car_name : String field
      	<br>3. hpp : Int field
      	<br>4. launch_date : Date field
  	<br>Maker Model.
      	<br>1. name : String field
      	<br>2. number_of_cars : Int field
9. Add a simple function based view in the new app, to return “My First Function !@#”.
10. Create a route for the above step (‘cars/test/’) which displays the  info returned from the function.
11. Create dummy data for the Car Model with about 100 unique rows.
12. Create a view to display the list of Cars on the “cars/list/” route of your app.
13. Using Curl, get the result of the above api, paste the curl request and the output to a curl_output.txt file. Under the test_data folder (Create if not present) place the curl_output.txt file under it.
14. In the  “cars/list/” route, only display the cars with launch date in future and Car names that start with ‘F’.
15. Pass a suffix_string parameter to  “cars/list/” route and it must be appended to every car name that is listed.
16. On the  “cars/list/” route make every alternate line blue. And center the Heading.
<br><img src="https://github.com/abiradar-enine/python-jobs/blob/dev_ab/common/logo/p1.png?raw=True" alt="Contact 1E9" height=200 widht=200>

17. Create a basic form to accept fields for the Maker Model and update the database with the input data.
18. Edit the form to be displayed in the following style, edit the labels and fields as per your Maker Model
<br><img src="https://github.com/abiradar-enine/python-jobs/blob/dev_ab/common/logo/p2.png?raw=True" alt="Contact 1E9" height=200 widht=200>

19. Redirect the page to google.com after the form is submitted.
20. Add an updated_at field to the maker model which has the latest time that the instance was created or updated.
21. Using the django shell perform basic crud operations on any one of the models.
22. Implement basic authentication in the app and make sure only authenticated users access the HomePage of the project.
23. Add a Car and Maker Object to the respective models from the django admin panel.

24. On the django admin panel implement the following.
    <br>1. Add a list view for the Car model on the django admin panel.
    <br>2. Filter the list on the date launched
    <br>3. Give a search functionality on the name of the car.
25. Create a simple Class Based View for your custom model to display the list of all cars.
26. Create a simple Template to show the list of your model objects.
27. Add new routes and display the content using the class based view and template that you have just created. Route: ‘cars/carlist/’ .
28. Add a detailed view which shows all the fields of your model for the specific instance as provided with the API as follows - /cars/<name_of_the_car>. Here, the name of the car will tell you which object to generate the detailed view of.
29. Implement Serializers for Car Model with the following fields:
    <br>1. Maker
    <br>2. Name
    <br>3. Launch Date
    <br>4. Mileage
and make necessary changes to the model if required for the above step.
30. Implement Serializers in GET/POST API for the Car model.
31. Implement PATCH API for the maker model (be able to update selective fields for the model instance)
32. Serialise the Maker API to return the Makers and their cars such that both the Maker and Cars are serialised.
33. Implement a django builtin request signal in your code and print/log information of an event using the signal handler.
34. Create a custom model signal and use it on the Car model. If the form data is valid and the Maker is present in our database then increase the count of the cars of that maker by 1.
35. Create a tagging mixin that allows you to put a tag on each model instance and use it for Maker and Car models.

36. Perform the following steps in the project,record all the steps in fixture_operation.sh file and then commit.  Under the test_data folder (Create if not present) place the fixture_operation.sh file under it.
    <br>1. Take a dump of all models related to the new project created as fixtures. clear the tables for that project
    <br>2.  Reload the fixtures for that project with the dump using django cli .
37. On the django admin panel display the list of Makers along with the cars they made such that if cars’ count is less than 2 then display car Name and horsepower, if cars’ count is between 2 and 5 then display only car names and anything above that display all the cars in a dropdown.
38. Run flake8 on the project directory and fix issues displayed.

> After you complete the test, schedule the interview using the following link:
<br>https://calendly.com/eninehr
