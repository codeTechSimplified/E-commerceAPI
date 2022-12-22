# Creating a RESTful API with Node.js
This repository allows you to start a boilerPlate code to begin building more features on RESTful API: https://github.com/codeTechSimplified/E-commerceAPI/

## Usage
1)  git clone
2)  npm install
3)  npm update
4)  npm start

On App.js file replace 
your mongoDB atlas url to existing url in mongoose.connect.


Make sure to also add your Mongo Atlas Admin Username to a nodemon.json file (which you have to create).

```
{
    "env": {
        "MONGO_ATLAS_PW": "YOUR_MONGO_USER_PW"
    }
}
```
