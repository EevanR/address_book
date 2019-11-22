# Address Book Challenge 2019
Address book is a web applitcation that users can use to store contacts in the browsers local storage, and remove these contacts when desired. 

## Dependencies
- Written in javaScript
- Feature test with Cucumber 
- Package Manager: Yarn lockfile v1

## Setup
#### Clone repository
```
git clone https://github.com/raomanasa/address_book.git
cd address_book
```
or
```
git clone https://github.com/EevanR/address_book.git
cd address_book
```

#### Install dependencies

Install Yarn with instruction from their website:
https://yarnpkg.com/en/docs/install

When installed, run initialize in terminal:
```
yarn init
```
For testing, we are using cucumber.js
```
yarn add cucumber chai puppeteer superstatic --dev
```

#### Actions available to the user

Open the web page, in terminal:
```
open index.html
```
Fill in as desired and press Save conact
When relationship has ended, use the necessary delete button.

Run testing, use command terminal
```
yarn run cucumber
```

## Acknowledgements
Thanks to CraftAcademy and its coaches for instructions and support.
Also, a special thanks to Martan and Johan, 6 lines of code influenced from their source: 
- the If statement cycyling through the contact array
- assigining delete button to a ref based on its position in the contacts array, stored in local storage

## Updates/Improvement plans
Further styling using cdnjs semantic ui

## License
Created under the <a href="https://en.wikipedia.org/wiki/MIT_License">MIT License</a>.
