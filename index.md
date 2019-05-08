
# What is Scratux?
* * *

Scratux is a block-based visual programming language targeted primarily at children. Users can create projects using a block-like interface. With Scratux, you can program your own interactive stories, games, and animations — and share your creations with others in the online community.

Basically Scratux is a simple project that aims to provide Free/Libre Open Source Linux binaries of [Scratch Desktop](https://scratch.mit.edu/download) (previously called the Scratch Offline editor). So consider it as the unofficial Scratch for Linux ;)

Since the official Scratch project does not provide binaries for Linux distributions, we created this project so you do not have to download + build from source. Just click and install it.

Scratux is built-in different languages and is always based on the latest stable Scratch release. (Currently Scratch 3.0)


## Build your own
* * *

First, download this project and run the `fetch.sh` script. This will donwload our latest `scratch-desktop` and `scratch-gui` custom repositories and will initialize them. Then run `npm` or `yarn` to build.

```sh
$ git clone https://github.com/scratux/scratux.git
$ cd scratux
$ git checkout master
$ chmod +x fetch.sh
$ ./fetch.sh
$ cd src
$ yarn run dist // or npm run dist
```

## Support or Contact
* * *
Drop me some lines at <a href = "mailto: joancipria@gmail.com">joancipria@gmail.com</a>
