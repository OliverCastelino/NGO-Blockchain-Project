## Running it locally
  1. Install nodejs.
  2. For building local blockchain network install ganache.
  
  3. clone the repository ( Let download in folder name "final1")
  ```
   https://github.com/OliverCastelino/NGO-Blockchain-Project
  ```
  4. Install truffle globally and install all node dependencies
  ```
    npm install
    npm install -g truffle
  ```
  5. Compile and migrate to local blockchain network
  ```
   truffle compile
   truffle migrate
  ```
  6. Set path of  Mongo DB(USERNAME = username of your root(OS-X))
  ```
   /Users/"USERNAME"/Downloads/mongod/bin/mongod --dbpath=/Users/"USERNAME"/Downloads/mongodb-path
   mongo
  ```
  7. Connect to MongoDB 
  ```
   cd final1 
   npm run dev
  ```
  8. Run the server on localhost
  ```
   npm start
  ```

