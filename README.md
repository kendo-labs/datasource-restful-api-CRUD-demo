### Kendo UI `DataSource` RESTful API CRUD demo

This is a demo of the CRUD operations via a Kendo UI DataSource instance. The code contains only enough logic (tried cutting as much out as I could) to showcase the functionality of the DataSource abstraction. The demo does not promote anything else except the grokking of the DataSource configuration values in the context of a restful JSON api.

(Note: prerequisites = [Node.js](https://nodejs.org/download/))

#### Step 1: 

From the cloned directory install npm packages ([json-server](https://github.com/typicode/json-server) and [browsersync](http://www.browsersync.io/))

```
npm install
```

#### Step 2: 

Start Servers (one to server webpage and one to server API) 

From cloned directry run:

```
npm run api
```

(i.e. starts json api at localhost:3000)

and, then in another tab in the same directory:

```
npm run www 
```
(i.e. starts browsersync and serves the index.html at localhost:3002)

#### Step 3: 

Visit [http://localhost:3002](http://localhost:3002) and add users then do some CRUD

#### Step 4: 

Examime the [index.html](index.html) file with the Kendo UI / JS code and see how simple it can be

#### Step 5: 

Examine the [db.json](db.json) file and read up on [json-server](https://github.com/typicode/json-server)
