# sonicpi-jupyter-notebook
Using [sonicpi](http://sonic-pi.net/) inside [jupyter notebooks](http://jupyter.org/).

![Example](sonicpi-jupyter.gif)

This is quite useful for educational purposes. For example you can teach sonic pi  using an interactive notebook or as exported Reveal.js slideshow.

To see a real example check the repo for a Sonic Pi crash-course I'm preparing for the technology divulgation event [gitech.cat](http://gitech.cat/): 

https://github.com/victormartingarcia/2018-gitech-introsonicpi (work in progress) 

You can see the material as [Jupyter notebook](http://nbviewer.ipython.org/github/victormartingarcia/2018-sonicpi-intropandas/blob/master/sonicpi_introduction.ipynb) or as [Reveal.js slides](http://nbviewer.ipython.org/format/slides/github/victormartingarcia/2018-gitech-introsonicpi/blob/master/sonicpi_introduction.ipynb#/) 

# Installation

You need to have python and ruby installed on your machine. Please refer to your platform instructions. 

## Install python requirements

```bash
$ pip install -r requirements.txt
```
## Install Jupyter Ruby Kernel iRuby

Follow instructions for your OS: https://github.com/SciRuby/iruby

## Install ruby gems

```bash
$ gem install bundler
$ bundle install
```


# Usage

## Executing sonic-pi

You can go ahead and open __Sonic Pi__ application with the GUI, or just open the Sonic Pi Server from a terminal:

```bash
$ ruby app/server/ruby/bin/sonic-pi-server.rb
```

## Launch Jupyter notebook

```bash
$ jupyter notebook
```

## Play with samples

Load the [sonicpi-notebook-sample notebook](sonicpi-notebook-sample.ipynb) and start having some fun 😆

http://localhost:8888/notebooks/sonicpi-notebook-sample.ipynb

