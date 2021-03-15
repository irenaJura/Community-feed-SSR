Community feed project is a PWA with declarative routing using react-router that supports SSR and therefore is loaded from the server rather than the browser.

 Also, the application is optimized for search engines using React Helmet.

 This project uses the publicly available Stack Overflow API to fill the application with data. This is done by fetching questions that are posted to Stack Overflow. More information about this API can be found at: https:/​/api.​stackexchange.​com/​docs/​questions#order=​desc​sort=​hot​tagged=​reactjs​filter=default​site=​stackoverflow​run=​true.

 The app consists of a simple header and a list of cards - these cards have a title and meta information such as view count, answer count, and information about the user who asked this question.
 
 Each title is a link that takes the user to that single question.