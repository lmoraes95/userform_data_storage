# userform_data_storage

create a config.py file and add the following line and update it with your system credentials: 
SQLALCHEMY_DATABASE_URI = 'postgresql://username:password@host:port/database'

This application simply takes any data passed into the fields and stores it into a postgresql database of your choice. 

Before you run app.py, you'll need to create postgresql database. The table will be created by the app.py syntax. However, you can create the table manually as well.

To run the script, simply open a new terminal and type 'python app.py'. It will open your local host live server and any information written in the fields will be ingested into the the postgresql database.