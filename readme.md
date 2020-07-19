## why

minimal web content should be easy.

## what

a tool for rendering a single github markdown file to a single html file.

## install

```bash
python3 -m pip install git+https://github.com/nathants/render
```

## usage

```bash
render readme.md \
    "render" \
    "render github markdown to html" \
    "github.com/nathants/render" \
    "https://github.com/nathants/render" \
    > index.html

python3 -m http.server &

firefox localhost:8000
```

```
>> render -h
usage: render [-h] [-f FOOTER] github-markdown title subtitle header-link-name header-link-href

    render github markdown to html


positional arguments:
  github-markdown       -
  title                 -
  subtitle              -
  header-link-name      -
  header-link-href      -

optional arguments:
  -h, --help            show this help message and exit
  -f FOOTER, --footer FOOTER
```

## examples

all of [nathants.com](https://nathants.com) is created with render.
