# Home blog

To run preview locally, run:
```shell
docker run --rm \
  --volume="$PWD:/srv/jekyll:Z" \
  --publish 4000:4000 \
  jekyll/jekyll:4.2.0 \
  jekyll serve
```
and go to [http://localhost:4000](http://localhost:4000)