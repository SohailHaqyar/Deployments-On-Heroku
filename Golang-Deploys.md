## How to Deploy REST APIs made with GO-LANG to heroku

Note: when defining the port make sure you get the environemnt variable from os package
```
port := os.Getenv("PORT")
app.Listen(":" + port)
```

Also make a binary on /bin/{name of project}

Good Luck!
