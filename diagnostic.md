# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.


What is the purpose of a backend?

```bash
A back end allows you to persist data beyond the current browser session and
also allows multiple users to interact with the same application over the web.
```

Which layer in the MVC pattern is used by the controller to fetch data?

```bash
The Model
```

Which layer in the MVC pattern communicates with the model?

```bash
The Controller
```

Why don't we use views in our interpretation of the MVC pattern?

```bash
We are focusing on SPAs which generate new 'views' from the front end using the
data returned by the model, rather than generating new views from the backend.
```

What does C.R.U.D stand for?

```bash
Create, Read, Update, Destroy
```

In which part of the MVC pattern can we find C.R.U.D actions?

```bash
The Controller
```
List at least 5 standard actions that C.R.U.D corresponds to?

```bash
index, show, update, delete, create
```

A user action fires a `GET` request for `person/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```bash
1. Client sends HTTP request
2. Router directs that request to the proper Controller
3. Controller 'translates' the request & sends to the Model
4. Model handles the request & data according to the logic written
5. Server then returns the response to the Client
```

What is the command to generate a new rails-api app?

```bash
rails-api new <name>
```

What is the command to start an instance of a rails server?

```bash
rails s
```

What are the commands to drop, create and migrate a database? (3 bullet points)

```bash
1. rake db:drop
1. rake db:create
1. rake db:migrate

```

What is the command to scaffold a pet with a name and an age?

```bash
rails-api g scaffold pet name:string age:number
```

List two advantages of using serializers? (2 bullet points)

```bash
1. Serializers create JSON responses which helps with error handling
2. There are a lot of client libraries that can consume these JSON responses
seamlessly
```
