# sonicpi-jupyter-notebook
Setup of [sonicpi](http://sonic-pi.net/) into [jupyter notebook](http://jupyter.org/). 

This is quite useful for educational purposes. For example you can teach sonic pi  using an interactive notebook or as exported Reveal.js slideshow.

[comment]: <> (To see a real example, check the material for a Sonic Pi crash-course I'm doing for kids catalan language: LINK A REPO)

# Installation

You need to have python and ruby installed on your machine. Please refer to your platform instructions. 

## create virtualenv!

```bash
$ mkvirtualenv sonicpi
$ workon sonicpi
```

## install python requirements

```bash
$ pip install -r requirements.txt
```
## install Jupyter Ruby Kernel iRuby

Follow instructions for your OS: https://github.com/SciRuby/iruby

## Install ruby gems

```bash
$ gem install bundler
$ bundle install
```


# Usage

## Executing sonic-pi

You can go ahead and open __Sonic Pi__ application with the GUI or just open the Sonic Pi Server from a terminal:

```bash
$ ruby app/server/ruby/bin/sonic-pi-server.rb
```

## Launch Jupyter notebook

```bash
$ jupyter notebook
```

## Play with samples

Load the notebook samples and start having some fun 😆

http://localhost:8888/notebooks/sonicpi-notebook-sample.ipynb

