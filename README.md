# rkdnio.github.io
Website for RKDN Digital

This is just a simple Jekyll site, but I strongly recommend using a Docker container for performing local development builds:

    docker run --rm --label=jekyll --volume=$(pwd):/srv/jekyll -it -p 127.0.0.1:4000:4000 jekyll/jekyll

That will get you a local instance accessible at `http://localhost:4000` that you can use for testing.
