<p align="center">
    <img src="logo.png" alt="screenshot">
</p>


<h1 align="center">
  <br>
  DevCollab
  <br>
</h1>


<h4 align="center">This is a simple guide on how to run DevCollab on your local machine. A more detailed guide was provided at the end of this document </h4>

<p align="center">
  <a href="#overview">Overview</a> •
  <a href="#getting-started">Getting Started</a> •
  <a href="#database-setup">Database Setup</a> •
  <a href="#running-the-server">Running The Server</a> •

</p>



## Overview

DevCollab is a Django-based web application designed for collaborative development. The application features user authentication, project management tools, and supports media and static content, making it suitable for managing collaborative projects and tasks.

## Getting Started
* Prerequisites : 
    * Python 3.6 or newer installed from their [website](https://www.python.org/downloads/) or relevant store on your system.
    * Django 3.1 or newer installed
    * Additional Python/Django packages as specified in requirements.txt

* Installation
    1. Clone the repository or download the files to your local machine.
    2. Navigate to the project directory where manage.py is located.
    3. Install Python from from their [website](https://www.python.org/downloads/) or relevant store on your system.
    4. Install the required Python/Django packages:

        ```pip install -r requirements.txt```


## Database Setup

``` python manage.py migrate ```

## Running The Server

``` python manage.py runserver ```


## Full Guide on how to run (Ignore if you followed the above)
 1. Use the recommended IDE : [Visual Studio Code](https://code.visualstudio.com/download)

2. Open the downloaded folder the installed from QMPlus (Supporting Materials Submission) 
    * The directory should somewhat look like this (if you extracted on the desktop): ` C:\Users\NAME\Desktop\DevCollabN`
3. In VSC run the following in the **terminal**:
    ```bash
    # Make Sure Python is first installed to your system
    # Then in the VSC terminal do as follows:

    #This is assuming that you are still in the SupportingMaterials_STUDENTID directory.
    $cd DevCollab

    #Commands here should be run in the same directory as the manage.py file.
    # Install dependencies
    $ pip install -r requirements.txt

    # Setup Database
    $ python manage.py migrate

    # Runserver
    $ python manage.py runserver
    ```

4. Visit http://127.0.0.1:8000/ in your web browser to view the application.


## END OF DOCUMENT
