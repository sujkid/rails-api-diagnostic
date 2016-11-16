# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.

What is the purpose of a backend?

```bash
A back end is used to store dataa and in game example, game states and views.
```

Which layer in the MVC pattern is used by the controller to fetch data?

```bash
model
```

Which layer in the MVC pattern communicates with the model?

```bash
controller
```

Why don't we use views in our interpretation of the MVC pattern?

```bash

```

What does C.R.U.D stand for?

```bash
C - create
R - read?
U - Update
D - Delete
```

In which part of the MVC pattern can we find C.R.U.D actions?

```bash
controller
```

List at least 5 standard rails actions that C.R.U.D requests correspond to?

```bash
index
show
create
update
destroy
```

A user action fires a `GET` request for `/people/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```bash
1. A user opens his browser, types in a URL.
2. When the user presses Enter, the browser sends a GET request for that URL.
3. The GET request hits the Rails router. The router maps the URL to the
   correct controller action to handle the request.
4. The action receives the GET request and passes it on to the view.
5. The view renders the page as HTML.
6. The controller sends the HTML back to the browser.
   The page loads and the user sees the page with the form.
```

What is the command to generate a new rails-api app?

```bash
rails-api new blog_app --skip-javascript --skip-sprockets --skip-turbolinks
--skip-test-unit --database=postgresql
```

What is the command to start an instance of a rails server?

```bash
bundle exec rails server
```

What are the commands to drop, create and migrate a database from the command
line? (3 bullet points)

```bash
- bundle exec rake db:drop
- bundle exec rake db:create
- bundle exec rake db:migrate
```

What is the command to scaffold a pet with a name and age attributes (hint:
Also think of the data types for each attribute)?

```bash
rails g scaffold pet name:string age:integer
```
