# Install the tyronzil client

> Getting ready:  
> - Recommended to use [nvm](https://github.com/nvm-sh/nvm) to install node.js ```nvm use 12```
> - Make sure to have the latest version of npm: ```npm install -g npm```  
> - Also, install [node-gyp](https://github.com/nodejs/node-gyp): ```npm install -g node-gyp```  
On macOS ```xcode-select --install``` as well

1. ```git clone https://github.com/tralcanx/tyronzil```

2. ```cd tyronzil```

3. ```git status```
> To start contributing, create your topic branch: ```git checkout -b yourTyron```

4. ```npm install```

5. ```npm run build```

6. To get the CLI ready:
```npm install -g .```

## tyronzil command-line interface

### DID-Create

Create your brand new tyronzil DID and save it on the Zilliqa blockchain platform, forever.

```tyronzil did create``` and follow the instructions :zap:

> More info [here](https://www.tyronzil.com/operations/CRUD/did-create/)  
> For your convenience, you could use [these testing-accounts](./testing-accounts.md) 

### DID-Resolve

Resolve any DID into its corresponding DID-document or DID-resolution-result with:

```tyronzil resolve```

> More info [here](https://www.tyronzil.com/operations/CRUD/did-resolve/)

### DID-Recover

In case you want to reset your DID-state while keeping the same identifier, you need your recovery private key.

```tyronzil did recover``` and follow the instructions

> More info [here](https://www.tyronzil.com/operations/CRUD/did-recover/)

### DID-Update

To update your tyronzil DID you need your update private key:

```tyronzil did update``` and follow the instructions

> More info [here](https://www.tyronzil.com/operations/CRUD/did-update/)

### DID-Deactivate

To fully deactivate your DID:

```tyronzil did deactivate``` and follow the instructions

> After deactivation, the DID will not be useful anymore, and trying to resolve it must throw a 'DidDeactivated' error.

> More info [here](https://www.tyronzil.com/operations/CRUD/did-deactivate/)

## Documentation

Build the project documentation with:

```npm run typedoc```
