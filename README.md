Simple_Social_network
Description
This is a small project for learning the Django python framework. The idea of the project is a simple "social network" where you can register, see your profile page, visit your friend's posts and leave comments on their page.

Pages:

Register
Login
My Profile
Home
About 

Project setup
Linux user
$ apt-get install python
$ python -m pip install Django

Windows user
first download python
https://www.python.org/downloads/. 
then install it
Setting up a virtual environment
To create a virtual environment for your project, open a new command prompt, navigate to the folder where you want to create your project, and then enter the following:

...\> py -m venv project-name
This will create a folder called ‘project-name’ if it does not already exist and set up the virtual environment. To activate the environment, run:

...\> project-name\Scripts\activate.bat
The virtual environment will be activated and you’ll see “(project-name)” next to the command prompt to designate that. Each time you start a new command prompt, you’ll need to activate the environment again.
Install Django
Django can be installed easily using pip within your virtual environment.

In the command prompt, ensure your virtual environment is active, and execute the following command:

...\> py -m pip install Django
This will download and install the latest Django release.

After the installation has been completed, you can verify your Django installation by executing Django-admin --version in the command prompt.
