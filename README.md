You should:
1. write in the console:
-> npm install --save pug

2. create config.js and create:
GOOGLE_CLIENT_ID and CALLBACK_URL use
->https://console.developers.google.com/projectselector/apis/credentials
(select: OAuth client ID, write  Product name, select:Web application and write: http://localhost:3000 (authorized JS origins) and http://localhost:3000/auth/google/callback (authorizes redirect URls) and create client ID and client secret) next you open:
->https://console.developers.google.com/apis/library/plus.googleapis.com?project=project-gertruda&folder&organizationId and push button enable

3. write in the console:
-> npm install express passport passport-google-oauth
