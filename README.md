# mprglobalsolutionsAPI

After cloning the repo, running

## npm install

will install all the dependencies.

## npm run start
will start the env without hot reload.

## npm run dev
will start the env with hot reload.

Following are the list of api's
1) POST http://localhost:5000/auth/signup
2) POST http://localhost:5000/auth/login
3) GET http://localhost:5000/users
4) PUT http://localhost:5000/users/:id
5) DELETE http://localhost:5000/users/:id
6) GET http://localhost:5000/users/:id

In order to sign, I would request having a look at the users model file.
After successful signup, user can login using the credentials provided.

After successful login, users can find the authorization token in the header of the response. "x-auth-token" is key provided.
Users will have to add it to headers of every api except(login & signup) for succesfull response.
