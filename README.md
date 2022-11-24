
## References

  + https://book.d2l.ai/user/create.html

## Setup


```sh
brew install texlive
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

## Building

https://book.d2l.ai/user/build.html

```sh
cd book
rm -rf _build/ && d2lbook build all

```
### Building HTML

```sh
# cd book && d2lbook build html
#
# cd book
# rm -rf _build
# d2lbook build html

rm -rf _build/html && d2lbook build html
```

### Building PDF

```sh
# cd book && d2lbook build pdf

rm -rf _build/pdf && d2lbook build pdf
```

This doesn't work? But it does generate a file "_build/pdf/book.tex" which you can convert to PDF manually via a website like this one https://cloudconvert.com/tex-to-pdf. JK, JK.




## Deploying

https://book.d2l.ai/user/deploy.html
