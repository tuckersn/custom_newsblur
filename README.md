# custom_newsblur
newsblur.com has support for custom JS and CSS to be uploaded for a user to customize the application, these are my customizations.


## How to install
1. Run `npm install`
2. Run `npm run build`
3. Goto Newsblur -> Settings Icon -> ACcount -> Custom CSS/JavaScript
4. Copy and paste the contents of ./build/style.css into the Custom CSS field
5. Copy and paste the contents of ./build/code.js into the Custom JavaScript field
6. Hit save and reload the page.


## Misc
cat ./build/newsblur.css | clip