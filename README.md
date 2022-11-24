
## References

  + https://book.d2l.ai/user/create.html

## Setup


```sh
#brew install texlive
```

```sh
conda install pandoc
conda install librsvg
```

```sh
conda create -n book-env python=3.10
conda activate book-env
```

```sh
pip install -r requirements.txt
```

## Building HTML

```sh
# cd book && d2lbook build html
cd book
rm -rf _build
d2lbook build html
```

## Building PDF

```sh
# cd book && d2lbook build pdf
```
