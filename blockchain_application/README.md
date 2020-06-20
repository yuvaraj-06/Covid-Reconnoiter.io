
## Instructions to run

Clone the project,

Install the dependencies,

```sh
$ cd blockchain_app
$ pip install -r requirements.txt
```

Start a blockchain node server,

```sh

### set FLASK_APP=node_server.py
$ flask run --port 8000
```

One instance of our blockchain node is now up and running at port 8000.


Run the application on a different terminal session,

```sh
$ python run_app.py
```

The application should be up and running at [http://localhost:5000](http://localhost:5000).

