### Victor Orlov's presentation at Melbourne Docker Meetup

#### To Run:
```
git clone https://github.com/fforloff/docker-registry-presentation
cd docker-registry-presentation

docker pull danidemi/docker-reveal.js
docker run -d -v $(pwd):/slides/ -p 8000:8000 danidemi/docker-reveal.js:latest
```
