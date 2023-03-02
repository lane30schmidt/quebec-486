# quebec-486

const { MongoClient, ServerApiVersion } = require('mongodb');
const uri = "mongodb+srv://lschmidt:<password>@cluster0.8khag9y.mongodb.net/?retryWrites=true&w=majority";
const client = new MongoClient(uri, { useNewUrlParser: true, useUnifiedTopology: true, serverApi: ServerApiVersion.v1 });
