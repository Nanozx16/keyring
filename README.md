# keyring
This repository contains a simple example of a keyring snap.
 This repository contains a simple example of an account abstraction keyring snap.
 
 Keyring snaps enable developers to enhance MetaMask by adding new account
 types. These accounts are natively supported within the extension, appearing in
 @@ -23,7 +23,17 @@ template](https://github.com/MetaMask/template-snap-monorepo/generate) and
 setup the development environment:
 
 ```shell
 yarn install && yarn start
 yarn install
 ```
 
 compile types
 ```shell
 cd packages/snap && yarn compile
 ```
 
 start the application (cd back into root of repository)
 ```shell
 yarn start
 ```
 
 ## Cloning
