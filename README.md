GOAL: list with examples for different readme markdowns

### Instructions to start the project
#### **Start the network**
- [x] go to `/network` folder
- [x] run `sudo ./env_start.sh`, after it is finished check if all containers are running `sudo docker ps -a`
- [x] run `cordite https://localhost:8081` in the same folder adn establish connection

#### **Start the angular app**
- [x] go to `/dasl` folder after all steps for the network are completed
- [x] make sure npm packages are installed, if not `npm install` in the main folder
- [x] run `ng serve -o` and the app will open on port `:4200`

#### **Front end Dependencies**
    angular-cli 8+
    node 10.16
    npm 6.9

#### Notes
  * comments for unfinished business are ` //TODO: ` 
  * if you are runnig VS Code, install `TODO Highlight` for better reading
  * currently for dev purposes, you need to have an account with the name **industria** on the network

#### Network commands in use
  * check all notaries `network.notaryIdentities()`
  * create account `ledger.createAccount(<account-name>, <notary>)`
  * get all accounts `ledger.listAccounts()`
  * get single account `ledger.getAccount(<accound-id>)`
