# Random Memer

Flask API to return random programming meme images scrapped from [Memedroid](https://www.memedroid.com/memes/tag/programming).

### Usage Notes:

Just add `img` tag in your website / README file and it will display a random meme everytime the website is loaded

```html
<img
    src="URL"
    title="Meme"
    alt="Please refresh the page if the meme doesn't show up."
/>
```

## How to deploy

### Using Docker

Build docker image:

```
docker build --tag python-docker .
```

Run docker container:

```
docker run -it -d -p 127.0.0.1:8000:8000 python-docker
```

Run container within a docker network:
```
docker run --network {network_name} --name python-docker -d python-docker -p 127.0.0.1:8000:8000
```