# Colorizr
Colorizr is a Ruby gem that enables you to implement coloful terminal output by modifying the String class.

### Features

Colorizr has the following color options for terminal output text:
* red
* green
* yellow
* blue
* pink
* light blue
* white
* light grey
* black

### Usage

##### First, require colorizr in your ruby file:
```
require 'colorizr'
```

##### Then, you can colorize your ouput by using any of the following methods:
```
 .red
 .green
 .yellow
 .blue
 .pink
 .light_blue
 .white
 .light_grey
 .black
```

##### Example:
```
puts "Yellow".yellow
```

##### Class methods:
```
String.colors               # returns an array of all the available colors
String.sample_colors        # prints examples of all the available colors
```

### Installation

##### You can download and unzip the zip file, or clone this repo using:
```
$ git clone https://github.com/QilinGu/Survivr1.git
```

##### And then inside the folder, install the gem by running:
```
$ gem install colorizr-0.0.1.gem
```