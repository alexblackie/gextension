# gextension

I enjoy using GNOME as my desktop environment, but installing the few extensions
I rely upon requires opening Firefox, going to some website, and clicking
buttons. There is no CLI to do this, which means [I can't automate it][1]. So I
wrote some horrible Ruby script to install extensions for me.

## Installation

Just clone and run `./gextension`. There are no dependencies outside of Ruby and
its standard library.

## Usage

```
gextension - install GNOME extensions from the command-line.

Available commands:

    search $QUERY      Given $QUERY, query the GNOME extensions API and return
                       a list of extension names and UUIDs.

    install $UUID      Given $UUID; download, extract, and enable the extension
                       that matches $UUID.
```

## License

See [LICENSE](./LICENSE).

[1]: https://github.com/alexblackie/bootstart
