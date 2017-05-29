First: npm init

Second install babel: 
  npm install --save babel-cli@6.11.x babel-core@6.13.x  \
  babel-preset-es2015@6.13.x babel-preset-react@6.11.x ejs@2.5.x \
  express@4.14.x react@15.3.x react-dom@15.3.x react-router@2.6.x

Third webpack:
	npm install --save-dev webpack@1.13.x babel-loader@6.2.x http-server@0.9.x


Add src folder
add static folder 
add index.html there and a style.css folder there. Can be designed as per needs. (/src/static/index.html & /src/static/css/style.css)
Add a data folder for the data (small in this case. Fuck with APIs if required.)
Organize the site into components. Add a component folder and keep adding files to it one by one according to file hierarchy and demand.


REFERENCE PATH STRUCT
├── package.json
├── webpack.config.js
├── src
│   ├── app-client.js
│   ├── routes.js
│   ├── server.js
│   ├── components
│   │   ├── AppRoutes.js
│   │   ├── AthletePage.js
│   │   ├── AthletePreview.js
│   │   ├── AthletesMenu.js
│   │   ├── Flag.js
│   │   ├── IndexPage.js
│   │   ├── Layout.js
│   │   ├── Medal.js
│   │   └── NotFoundPage.js
│   ├── data
│   │   └── athletes.js
│   ├── static
│   │   ├── index.html
│   │   ├── css
│   │   ├── favicon.ico
│   │   ├── img
│   │   └── js
│   └── views
 `       └──  index.ejs