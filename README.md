# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:

### Step 1:

Open up a terminal in your preffered location, and start a django project using djang-admin startproject Next setup an app inside the project folder using django-admin startapp.

### Step 2:

Once Created ,link your app to the project by adding it in the list of apps in settings.py file located inside the project folder. Add access to your host in allowed host setting and add static folders path to your settings.py file.

### Step 3:

Create a static folder and template folder and add all your required files for the project - Images .etc in your static folder. In the Template folder add your html files required for the pages.

### Step 4:

Head to the views.py in your app folder and create required functions to render a particular page or template when requested by the client. Next go to the urls.py and route the correct view functions to each particular request as needed.

### Step 5:

Next start the server from the projects main directory using python3 manage.py runserver 0:. Now the pages can be accessed from all the routed addresses in urls.py.

## Code:
## Map.html


## Output:
## server output:



## client output:



## Result:
Hence, a website has been developed to display details about the colleges around saveetha university.
