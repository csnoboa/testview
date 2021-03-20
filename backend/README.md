# TestView-Backend

# 0- Install Python3:
Install python 3.7: https://www.python.org/ftp/python/3.7.7/python-3.7.7.exe

All the steps aboves must be executed in this folder! ('backend')

# 1- Optional - Create a Virtual Environment
Create a virtual env (this step is not mandatore, but is advisable):
        python -m venv env

then: (You will need to do this every new terminal)
    
        source env/bin/activate     (Linux/MacOS)
        
or
        
        env\Scripts\activate        (Windows)


# 2- Install project's dependencie
Install project's dependencies: 

        pip install -r requirements.txt

# 3- Change the MongoDB parameters  
Change the variable MongoDBConnect in config.py:

    The default is "localhost:27017", but you can change the url and add username and password if needed.
    
# 4- Now the project is ready!
Now the project is ready, you can run:

        python app.py

# 5- Test the API alone
If you would like to do simples tests with the API without the interface, 
you can install the software Insomnia: https://insomnia.rest/download 

There are a configuration alread done: "Insomnia_config.json" you can import that file in Insominia.




