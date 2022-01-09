# Command list for node-backend-dev

I will deploy on azure, so use command from its doc.
# [Create your Node.js application](https://docs.microsoft.com/en-us/azure/app-service/quickstart-nodejs?pivots=development-environment-azure-portal&tabs=windows)

```powershell
PS E:\p\src\node\danmaku-everywhere\node-backend> npx express-generator danmaku --view pug

   create : danmaku\
   create : danmaku\public\
   create : danmaku\public\javascripts\
   create : danmaku\public\images\
   create : danmaku\public\stylesheets\
   create : danmaku\public\stylesheets\style.css
   create : danmaku\routes\
   create : danmaku\routes\index.js
   create : danmaku\routes\users.js
   create : danmaku\views\
   create : danmaku\views\error.pug
   create : danmaku\views\index.pug
   create : danmaku\views\layout.pug
   create : danmaku\app.js
   create : danmaku\package.json
   create : danmaku\bin\
   create : danmaku\bin\www

   change directory:
     > cd danmaku

   install dependencies:
     > npm install

   run the app:
     > SET DEBUG=danmaku:* & npm start
PS E:\p\src\node\danmaku-everywhere\node-backend> cd .\danmaku\
PS E:\p\src\node\danmaku-everywhere\node-backend\danmaku> npm install
npm WARN deprecated core-js@2.6.12: core-js@<3.4 is no longer maintained and not recommended for usage due to the number of issues. Because of the V8 engine whims, feature detection in old core-js versions could cause a slowdown up to 100x even if nothing is polyfilled. Please, upgrade your dependencies to the actual version of core-js.

added 124 packages, and audited 125 packages in 38s

8 packages are looking for funding
  run `npm fund` for details

4 vulnerabilities (2 low, 2 high)

To address issues that do not require attention, run:
  npm audit fix

To address all issues, run:
  npm audit fix --force

Run `npm audit` for details.
```
