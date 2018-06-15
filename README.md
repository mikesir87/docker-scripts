# Docker Scripts

Since I'm lazy (or efficient?), I don't want to install lots of stuff on every machine I get. This repo provides some of my utility scripts, which are based on containers. That way, only Docker is needed. First invocation will pull the image and then use it from then on!

## Installation

```
git clone https://github.com/mikesir87/docker-scripts.git ~/.docker-scripts
sudo sh -c "echo '$(echo $HOME)/.docker-scripts' >> /etc/paths"
```

The reason I update `/etc/paths` is it ensures it's in my path regardless of which shell I'm using (I use zsh personally).

## Usage

Just run the command (like `aws`)!

## License

The MIT License (MIT)

Copyright (c) 2018 Michael Irwin

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
