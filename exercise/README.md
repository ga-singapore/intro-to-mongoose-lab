<h1>
  <span class="headline">Intro to Mongoose Lab</span>
  <span class="subhead">Exercise</span>
</h1>

You will use postman (or any application of your choice) to call the API to get the corret return value. Not user interface is required.

You will also need the following packages to complete this lab:

- mongoose
- dotenv

## Define the model

1. Create a new model file and build the customer schema.

2. The customer model will have the following fields:

   - name: String
   - age: Number

## Make the database connection

Initialize Mongoose and MongoDB Connection:

1. Set up Mongoose in your application.
2. Ensure you have a `.env` file for your MongoDB URI and a `.gitignore` file to avoid pushing sensitive data to GitHub.

## Starting the application

Start your application by running the following command in the terminal:

```bash
npm run dev
```

**NOTE**:
The prompt-sync package, used for user input in the terminal, may not work well with nodemon. To test changes, stop the app using `Ctrl+C` and restart it with `npm run dev`.

### Requirements

1. getting the details of all customers (GET /api/customers)
2. getting the details of 1 customer (GET /api/customers/:id)
3. create a new customer (POST /api/customers)
4. updating a customer (PATCH /api/customers/:id)
5. deleting a customer (DELETE /api/customers/:id)

