# ca2

* [Axios](https://www.npmjs.com/package/axios)
* https://medium.freecodecamp.org/quick-guide-to-understanding-and-creating-reactjs-apps-8457ee8f7123
* [React-bootstrap](https://react-bootstrap.github.io/getting-started/introduction/)
* freeformater.com
* https://restfulapi.net/security-essentials/
* [Introduction to Distributed Systems](https://hackernoon.com/a-thorough-introduction-to-distributed-systems-3b91562c9b3c)
* [Dweb: Building Cooperation and Trust into the Web with IPFS](https://hacks.mozilla.org/2018/08/dweb-building-cooperation-and-trust-into-the-web-with-ipfs/?utm_source=dev-newsletter&utm_medium=email&utm_campaign=aug30-2018&utm_content=dweb)
* [Material Kit React](https://demos.creative-tim.com/material-kit-react/#/)
* [Swaggerhub](https://app.swaggerhub.com/apis/CrowdArt/ca2/1.0.0)
* [Datum](https://app.swaggerhub.com/apis/CrowdArt/ca2/1.0.0)
* [Cosmos Network](https://cosmos.network/docs/getting-started/installation.html)

### Ethereum Application Architecture
* Browser => Web3 => Metamask (public/private keys) => Ethereum network
* Application interacts with Web3, Web3 interacts with Metamask, Metamask creates a transaction and signs it with users private key and sends teh transaction to the ethereum network.
* Anytime the user changes data, they have to send the transaction to the network.  That costs some amount of money.
* The public and private keys only exist on user's machine.
* Client is responsible for modifying any data inside the app.
* Contract ABI - Application Binary Interface = communication layer => translation layer from the blockchain world to the javascript world.
* We feed the ABI to Web3 instance.  This creates a local copy of the contract.
* Anytime we deploy a contract to the blockchain it gets a distinct address assigned to it.

### MyEthereumWallet
* [MyEthereumWallet](https://www.myetherwallet.com/)
* Marina0624!@#$#@!

#### Material UI
* npm install @material-ui/core
* npm install @material-ui/icons
* npm install typeface-roboto --save
* npm install enzyme@^3.0.0
#### React Router
* npm install --save react-router react-router-dom react-router-config

### Create Build
* npm run dev:build:server
* npm run dev:server

## Firebase
* [Firebase Console](https://console.firebase.google.com/u/0/project/coinart-b825c/database/coinart-b825c/data)

Open a terminal window and navigate to or create a directory for your site

Sign in to Google:

$ firebase login
Initiate your project:

$ firebase init
Add your static files to your deploy directory (the default is public)

Deploy your website:

$ firebase deploy

```service cloud.firestore {
  match /databases/{database}/documents {
    match /{document=**} {
      allow read, write;
    }
  }
}
```
```
service cloud.firestore {
  match /databases/{database}/documents {
    match /{document=**} {
      allow read, write;
    }
  }
}
```
## Axios
* [Axios](https://www.npmjs.com/package/axios)
* npm install axios --save
