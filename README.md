# A Simple Flask Webapp project with Dockerization

Dockerize a simple Webapp Flask application .

## GitBash check

1 . In Gitbash

```bash
docker run -p 8000:5000 -it ubuntu bash
apt-get update
apt-get install -y python3
apt-get install -y python3-pip
```

2 . Install dependencies

```bash
pip3 install flask
```

3 . Other commands :

```bash
cd opt
apt-get install vim
```

4 . Write a flask webapp file : `app.py`

```bash
vi app.py
    i
    <copy paste app.py code>

esc
:wq!
```

5 . Install curl :

```bash
app install curl
```

6 . Run the application : 

```bash
python3 app.py
```

## Docker Desktop

1 . Goto Docker Desktop -> Containers

2 . You can see the container -> CLI

3 . execute below command :

```bash
curl --location --request GET 'http://127.0.0.1:5000/'
curl --location --request GET 'http://127.0.0.1:5000/container'
```

## Testing

If the messages are coming correctly , you are assured your Dockerize application is working perfectly .