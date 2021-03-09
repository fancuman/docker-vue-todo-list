### How to run it
Navigate to the root directory.

```
$ cd nginx-serve-todo-list

```
update frontend/dist folder if source code changes

```
$ docker-compose -f docker-compose-generate-web.yaml up -d 
```

Start the `frontend-web`, `backend` and `db` containers using docker-compose

```
$ docker-compose up -d 
```
Access the app from your browser at `http://localhost:80`
