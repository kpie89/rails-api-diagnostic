# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.


What is the purpose of a backend?

```bash
//The backend is there to store data for the front-end to interact with.
```

Which layer in the MVC pattern is used by the controller to fetch data?

```bash
Model layer
```

Which layer in the MVC pattern communicates with the model?

```bash
Controller
```

Why don't we use views in our interpretation of the MVC pattern?

```bash
We don\'t have to ever since the advent of SPA\'s.  Since thier are not multiples pages to view, the
view layer doesn\'t have to assemble the data into a nice view. The front-end does it for us.
```

What does C.R.U.D stand for?

```bash
Create. Read. Update. Destroy.
```

In which part of the MVC pattern can we find C.R.U.D actions?

```bash
Controller
```

A user action fires a `GET` request for `person/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```bash
- The client (web browser) tells the server that it needs 'person/1' by denoting
the correct route.
- The controller tells the model 'Hey model, I need person/1'
- The model says 'Okay, let me look in MYSQL and get it...oh yeah here it is. Here you go
controller'
- The controller takes the data and gives it back to the client
```

What is the command to generate a new rails-api app?

```bash
rails-api new some_app -T --database=postgresql
```

What is the command to start an instance of a rails server?

```bash
rails s
```

What are the commands to drop, create and migrate a database? (3 bullet points)

```bash
- rake db:create
- rake db:drop
- rake db:migrate

```

What is the command to scaffold a pet with a name and an age?

```bash
// your response here
rails-api g scaffold pet name:string age:integer

List two advantages of using serializers? (2 bullet points)

```bash
- Very human readable
- Makes your api safer
-
```
