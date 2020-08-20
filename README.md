# Get into project folder

## Install dependencies

 npm install

####  Create  .env file inside root project then put the following examples inside with valid values

- PORT=3001
- MONGO_DB_URL='mongodb+srv://user:password@dbname.cvepz.mongodb.net/<dbname>?retryWrites=true&w=majority'
- JWT_SECRET_KEY=test@1234


## Run local dev server

npm run dev

## Using the GraphQL playground 

First create the User running the mutation query,  then you should login (put your email and password to continue)  to create the tasks you want.
After login you'll receive a token, with this you can : Create Tasks, Update Tasks, Delete Tasks and Change Task Status.

**Remember to write the token inside HTTP Headers :**

Example :

{
	"Authorization": "Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJlbWFpbCI6ImZsb3JhQGZsb3JhLmNvbSIsImlhdCI6MTU5Nzg3NjU3MCwiZXhwIjoxNTk4MTM1NzcwfQ.0ny0ySjezeITjDfFZcIOPJIKTHqB2HhxgESeqZZ8xEs"
	
}
