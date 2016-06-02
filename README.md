# psd2api
PSD2 API CLient

Sample SpringBoot with MongoDb

    Install Eclipse Mars
    Install Mongo
    Pull the code from this repository
    Start Mongo

    Mongo commands for setting up text index use mcabuddy db.users.createIndex({fname:"text",lname:"text","aoe":"text",email:"text", "roles" : "text"}, {name:"userTextIndex"})

    Run the Application.java class from eclipse (set an environment variables: MONGO_SVC_URL=mongodb://[user]:[port]@[domain]:[port])

    Install Postman (Chrome App)
