# CIPHERLET - Your Crypto Wallet
💳This is a Chrome extension that functions as an Ethereum wallet, allowing users to manage their Ethereum accounts, view balances, and initiate transactions. The extension is built using React and interacts with the Ethereum blockchain using Moralis.io API.

## 🚀Steps to make it a chrome extension:

- [ ] Open Manifest.json in the public folder
- [ ] Set name of the wallet, manifest_version:3, default_popup: index.html
- [ ] Using permissions, we can leverage chrome storage or others for encryption purposes
- [ ] Run ‘npm run build’
- [ ] Open chrome ->Manage extension->Toggle ‘Developer mode’ ON
- [ ] Choose load unpacked option -> Choose the build folder
- [ ] Once done, you can pin the extension and test it
- [ ] Every time ‘npm run build’ is run, the extension gets updated

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.


### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!
