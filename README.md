# Django Test


Note - For tasks 3 through 40, commit your code changes with a message “Task <number>”. If the task involves no code changes, create a text file for the same and commit it with the above message.

Tasks -
    
```    
    1. Clone the git repository - git@github.com:vishalapte/python-jobs.git and create a branch where you’ll be committing the code changes/answers. 
    2. Create a virtual environment and activate it.
    3. Install all the requirements from requirements.txt file in the project and solve for any errors that you might face while doing so.
    4. Identify and solve any problem that you might face while trying to run the server.
    5. Navigate to the admin panel and fix any problem that might make the admin site inaccessible.
    6. Change the background colour of ‘2’ to brown. On the ‘Senior Developer Role’ page of the project.
    7. Add a new app to the project, name : cars.
    8. Implement basic authentication in the app and make sure only authenticated users access the HomePage of the project.
    9. Create the following models 
          Car model. 
              1. maker : String field : Foreign Key
              2. car_name : String field
              3. hpp : Int field
              4. launch_date : Date field
          Maker Model.
              1. name : String field
              2. number_of_cars : Int field
    10. Add a simple function based view, to return “My First Function !@#”.
    11. Create a route to the new app(‘cars/test/’) which displays the welcome info :
          1. Welcome To 1E9 Task.
    12. Create a view to display the list of Cars on the “cars/list/” route of your app.
    13. Using Curl, get the result of the above api, paste the curl request and the output to a curl_output.txt file. Under the test_data folder create a folder with your name and place the curl_output.txt file under it.
    14. In the  “cars/list/” route, only display the cars with launch date in future and Car names that start with ‘F’.
    15. Pass a suffix_string parameter to  “cars/list/” route and it must be appended to every car name that is listed.
    16. On the  “cars/list/” route make every alternate line blue. And centre the Heading.
          ![image](https://github.com/abiradar-enine/python-jobs/assets/141114004/add0ced8-0edf-40bf-bdd6-5da9ae18545b)
          1. ![Alt jhah](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")
    17. Create a basic form to accept fields for the Maker Model and update the database with the input data.
    18. Redirect the page to google.com after the form is submitted.
    19. Add an updated_at field to the maker model which has the latest time that the instance was created or updated.
    20. Create dummy data for the Car Model with about 100 unique rows.
    21. Using the django shell perform basic crud operations on any one of the models.
    22. Access the admin page in django. Make changes needed to access the admin page.
    23. Add a Car and Maker Object to the respective models from the django admin panel.

    24. On the django admin panel implement the following.
        1. Add a list view for the Car model on the django admin panel. 
        2. Filter the list on the date launched 
        3. Give a search functionality on the name of the car.
    25. Create a simple Class Based View for your custom model to display the list of all cars.
    26. Create a simple Template to show the list of your model objects.
    27. Add new routes and display the content using the class based view and template that you have just created. Route: ‘cars/carlist/’ .
    28. Add a detailed view which shows all the fields of your model for the specific instance as provided with the API as follows - /cars/<name_of_the_car>. Here, the name of the car will tell you which object to generate the detailed view of.
    29. Display a default form for /cars/create/ route using the built in Django Class.
    30. Edit the form to be displayed in the following style, edit the labels and fields will be as per your Car Model
    31. Implement Serializers for Car Model with the following fields:
        1. Maker
        2. Name
        3. Launch Date
        4. Mileage 
        and make necessary changes to the model if required for the above step.
    32. Implement Serializers in GET/POST API for the Car model.
    33. Implement PATCH API for the maker model (be able to update selective fields for the model instance)
    34. Serialise the Maker API to return the Makers and their cars such that both the Maker and Cars are serialised.
    35. Implement a django builtin request signal in your code and print/log information of an event using the signal handler.
    36. Create a custom model signal and use it on the Car model. If the form data is valid and the Maker is present in our database then increase the count of the cars of that maker by 1.
    37. Create a tagging mixin that allows you to put a tag on each model instance and use it for Maker and Car models.

    38. Perform the following steps in the project,record all the steps in fixture_operation.sh file and then commit. Under the test_data folder create a folder with your name and place the fixture_operation.sh file under it. (Same folder which was created for 13 Question. )
        1. Take a dump of all models related to the new project created as fixtures. clear the tables for that project
        2.  Reload the fixtures for that project with the dump using django cli .
    39. On the django admin panel display the list of Makers along with the cars they made such that if cars’ count is less than 2 then display car Name and horsepower, if cars’ count is between 2 and 5 then display only car names and anything above that display all the cars in a dropdown.
    40. Run flake8 on the project directory and fix issues displayed.

```

