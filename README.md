#TECHNOLOGIES
![react-node-express-mongodb-mern-stack-example-architecture](https://user-images.githubusercontent.com/29667186/110526432-73fe9c00-811e-11eb-8fd5-c9199c41b6fb.png)


# JWT-Authentication
Nodejs JWT RestAPIs

We have created an authentication method using a JWT. JSON Web Token (JWT) is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object. 
This information can be verified and trusted because it is digitally signed.
JWTs can be signed using a secret (with the HMAC algorithm) or a public/private key pair using RSA or ECDSA.

We will use mongodb as our database, mongoose to create models and to connect to our express server, bcryptjs to hash passwords and jwt to check for private routes.

#TO GET STARTED
1. Navigate to the root of the project and install node modules,
by running --> npm install
2. Then start server with --> npm start
3. ![Screenshot from 2021-03-09 20-56-48](https://user-images.githubusercontent.com/29667186/110522869-0ea8ac00-811a-11eb-8c73-2655b5d3a384.png)
The server will be running on port 3000

POST requests: 1: http://localhost:3000/api/user/register
               2: http://localhost:3000/api/user/login
               ![Screenshot from 2021-03-09 21-07-55](https://user-images.githubusercontent.com/29667186/110524160-b4a8e600-811b-11eb-8d6f-c030de46450d.png)

