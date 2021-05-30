# Blog

## Getting start

### Clone the repository
```
git clone --recurse-submodules -j8 git@github.com:balintkiraly/blog.git
```
or

```
git clone git@github.com:balintkiraly/blog.git
cd blog
git submodule update --init --recursive
```
### Install dependecies
```
sudo apt install hugo
```

## Start the dev server
```
hugo -D serve
```
