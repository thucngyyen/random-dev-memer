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

To build image:

```
docker build --tag python-docker .
```

To run image:

```
docker run -it -d -p 8000:8000 python-docker
```
