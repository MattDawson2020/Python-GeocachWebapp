## 🐍 Python-Geocoder challenge

- Tenth example project from [Udemy course](https://www.udemy.com/course/the-python-mega-course/)
- Uses Flask and geopy to geocode submitted CSV addresses
- Most of the code is provided by instructor but there were bugs left in there that you needed to find/ figure out yourself


## 📓 Comments

- Bugs relatively simple to work out, incorrectly defined [btn] on index page meant app.py could not inject the download value into it, Nominatim not initialized with a user_agent value so it could not correctly return geocoded values
- Python library documentation is extremely high quality and debugging was extremely easy


## 💻 Running the app

- Clone this repo to your local machine, and then make sure you have access to the libraries in the requirements.txt file, you can either directly install using ``` pip install (libraryname) ``` or you can use a virtualenv, by running ``` python -m venv (env name) ```, and then using the virtualenv to install the libraries local to the project repo
  - Navigate to the project directory and use ``` virtual/scripts/pip install (library name) ```
  - This is a localised install and will not conflict with other installs/ let you set a version
  - Then you need to use ``` source virtual/Scripts/activate ``` to tell python to use this virtualenv as the source
 - Navigate to the directory, and then use ``` python app.py  ``` to run the script, your terminal will confirm the server is running and give you a localhost port to alt-click
- The browser will launch, you can select one of the CSV files from the sample_files directory to upload and be geocached
- From here you can also download the Geocached CSV files





