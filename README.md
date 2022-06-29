
# Election - DAPP 

## Dependencies
Install these prerequisites to follow along with the tutorial. See free video tutorial or a full explanation of each prerequisite.
- NPM: https://nodejs.org
- Truffle: https://github.com/trufflesuite/truffle
- Ganache: http://truffleframework.com/ganache/
- Metamask: https://metamask.io/


## Step 1. Install dependencies
```
$ npm install
```
## Step 2. Start Ganache
Open the Ganache GUI client that you downloaded and installed. This will start your local blockchain instance. See free video tutorial for full explanation.
![Screenshot from 2022-06-30 00-08-01](https://user-images.githubusercontent.com/73174196/176512096-6463efb5-e798-4f85-b53c-d97dea4780aa.png)



## Step 3. Compile,test & Deploy Election Smart Contract
`$ truffle migrate --reset`
You must migrate the election smart contract each time your restart ganache.
![Screenshot from 2022-06-30 00-13-54](https://user-images.githubusercontent.com/73174196/176512347-2313ba4e-096e-44b2-9541-45509f8ed297.png)
`$ truffle test`
![Screenshot from 2022-06-30 00-07-04](https://user-images.githubusercontent.com/73174196/176512497-7c89060e-a36c-471e-abe2-37df6fe65fa8.png)


## Step 4. Configure Metamask
- Unlock Metamask
- Connect metamask to your local Etherum blockchain provided by Ganache.
- Import an account provided by ganache by pasting the private key of one of ganache account in metamask.
![Screenshot from 2022-06-30 00-19-31](https://user-images.githubusercontent.com/73174196/176513537-3ffd282c-c527-4468-a835-f7b40ca0cc27.png)



## Step 5. Run the Front End Application
`$ npm run dev`
![Screenshot from 2022-06-30 00-06-51](https://user-images.githubusercontent.com/73174196/176512608-84960fc8-86f6-4683-b574-17f6f0f2c04b.png)
Visit this URL in your browser: http://localhost:3000
![Screenshot from 2022-06-30 00-10-36](https://user-images.githubusercontent.com/73174196/176512960-263138ef-115b-4b12-bc83-c610c4a6badc.png)


## If we were to build our voting application on the web, we’d run into a few problems:

-The data on the database could be changed: it could be counted more than once, or removed entirely.

-The source code on the web server could also be changed at any time.
