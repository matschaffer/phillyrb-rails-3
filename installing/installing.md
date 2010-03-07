!SLIDE subsection

# Installing Rails 3 #

!SLIDE

## Step 1. Install Dependencies ##

!SLIDE commandline incremental

    $ gem install rails3b
    ... lots of lines ...
    Successfully installed rails3b-3.0.1
    ... more lines ...
    (this is a wrapper gem for rails beta dependencies)

!SLIDE

## Step 2. Install The Beta ##

!SLIDE commandline incremental

    $ gem install rails --pre
    ... lines of stuff ...
    Successfully installed rails-3.0.0.beta
    ... more lines ...

!SLIDE

## But if you also need rails 2 installed... ##

!SLIDE center

![Train Crash](train_wreck.jpg)

!SLIDE

### Managing versions is a pain in the ass. ###
### Use something to manage gem environments ###

### RVM: http://rvm.beginrescueend.com/ ###
### gemset: http://gist.github.com/307257 ###

!SLIDE

## That's pretty much it. ##

