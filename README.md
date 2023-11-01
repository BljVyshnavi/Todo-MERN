# Todo_Mini_Project

# In order to make the app work first install the dependencies by running the following command on your terminal:

```
We will install these dependencies through the below npm install command:
"ejs": "^3.1.5",
"express": "^4.18.2",
"mongodb": "^5.5.0",
"mongoose": "^5.10.2"
open command prompt in todominiproject and run the following command:
>> npm install
```
# Create an account in MongoDB atlas in order to store your data in mongoDB database:

```
Create a cluster in your account and copy your MongoDB connection string URI, which looks like below:

mongodb+srv://SupriyaM:<password>@todo-cluster.zlgjipx.mongodb.net/?retryWrites=true&w=majority

and paste your URI in app.js file at mongoose.connect(" ")

To see data in the monogoDB database, Go to your cluster and click on Browse Collections. 
```

# Now start the server by typing the following command:

```
>> node app.js 
```
# To see the output which is todo list application:

```
In Chrome search open, http://localhost:3000