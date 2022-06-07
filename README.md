# fsrx

📚(**f**)low (**s**)tate (**r**)eading e(**x**)change – flow state
reading in the terminal


[![GitHub CI
Workflow](https://github.com/coloradocolby/fsrx/actions/workflows/ci.yml/badge.svg)](https://github.com/coloradocolby/fsrx/actions/workflows/ci.yml)
[![GitHub Deploy
Workflow](https://github.com/coloradocolby/fsrx/actions/workflows/deploy.yml/badge.svg)](https://github.com/coloradocolby/fsrx/actions/workflows/deploy.yml)
[![License](https://img.shields.io/badge/License-MIT-default.svg)](./LICENSE.md)
[![Crate
Version](https://img.shields.io/crates/v/fsrx)](https://crates.io/crates/fsrx)
[![Github
Stars](https://img.shields.io/github/stars/coloradocolby/fsrx)](https://github.com/coloradocolby/fsrx/stargazers)

![demo](https://github.com/coloradocolby/assets/raw/main/fsrx/demo.gif)

*Inspired by **(but not affiliated with)** Renato Casutt and his
revolutionary work on [Bionic Reading](https://bionic-reading.com).
Please consider supporting his mission to make Bionic Reading available
worldwide ❤️*
## Usage

For detailed usage run `fsrx -h`.

```
fsrx 0.2.0
Colby Thomas <coloradocolby@gmail.com>
📚(f)low (s)tate (r)eading e(x)change
flow state reading in the terminal

USAGE:
    fsrx [OPTIONS] [PATH]

ARGS:
    <PATH>    path to file (or supply input via stdin)

OPTIONS:
    -c, --contrast               high contrast
    -f, --fixation <FIXATION>    fixation intensity [default: m] [possible values: l, m, h]
    -h, --help                   Print help information
    -s, --saccade <SACCADE>      saccade intensity [default: h] [possible values: l, m, h]
    -V, --version                Print version information
```

### Examples

```sh
$ echo "the quick brown fox jumps over the lazy dog" | fsrx
$ fsrx input.txt | less
$ fsrx -c -fh -sl input.txt | less
```

## Installation

### Cargo

```sh
$ cargo install fsrx
```

### Homebrew

incoming @
[homebrew-fsrx](https://github.com/coloradocolby/homebrew-fsrx)

## Contributing

All contributions are greatly appreciated. Please keep in mind this
project is meant to be as lightweight as possible, so not every idea
will be considered.

If you have a suggestion that would make fsrx better, please fork the
repo and create a [pull
request](https://github.com/coloradocolby/fsrx/pulls). You can also
simply open an issue and select `Feature Request`

1. Fork the repo
2. Create your feature branch (`git checkout -b [your_username]/xyz`)
3. Commit your changes (`git commit -m 'add some xyz'`)
4. Rebase off main (`git fetch --all && git rebase origin/main`)
5. Push to your branch (`git push origin [your_username]/xyz`)
6. Fill out pull request template

See the [open issues](https://github.com/coloradocolby/fsrx/issues) for
a full list of proposed features (and known issues).

## License

Distributed under the MIT License. See [LICENSE.md](./LICENSE.md) for
more information.

## Follow

[![github](https://img.shields.io/github/followers/coloradocolby?style=social)](https://github.com/coloradocolby)
[![twitter](https://img.shields.io/twitter/follow/coloradocolby?color=white&style=social)](https://twitter.com/coloradocolby)
[![youtube](https://img.shields.io/youtube/channel/subscribers/UCEDfokz6igeN4bX7Whq49-g?style=social)](https://youtube.com/user/coloradocolby)
