!SLIDE subsection

# Other Cool Features #

!SLIDE

## Pluggable Generators using Thor ##
### http://github.com/indirect/rails3-generators ###

!SLIDE

## UJS (Use prototype / jquery with helpers) ##

!SLIDE

## HTML5-friendly ##

!SLIDE

## Component Agnostic ##

!SLIDE bullets incremental

* ORM (AR, DM)
* Test Framework (T::U, Rspec)
* Fixtures (built in, FactoryGirl)
* Template Framework (ERB, Haml)

!SLIDE

## Auto HTML escaping ##

!SLIDE

    raw('some <strong>html</strong>') 

    safe_helper :fn

    String#html_safe

!SLIDE

## Better Plugin API ##

!SLIDE bullets incremental

* plugin, engine, app distinction
* Public / documentated api
* Hook into arbitrary things
* Namespaced applications

!SLIDE

## named\_scope changes ##

    # not this
    named_scope :sorted, :order => 'name'

    # this
    scope :sorted, order('name')

!SLIDE

## script/rails ##

!SLIDE

## Responders ##

!SLIDE code

    @@@ ruby
    class PeopleController < ApplicationController
      respond_to :html, :xml, :json
      def index
        @people = Person.find(:all)
        respond_with(@people)
      end
    end

!SLIDE

## RAILS\_* is deprecated. ##
## Rails.* is the new hotness. ##


!SLIDE

## http://guides.rails.info/3\_0\_release_notes.html ##

!SLIDE

# Upgrading #

!SLIDE bullets

* Plugin helper: github.com/rails/rails\_upgrade 
* Rails Upgrade Handbook 

!SLIDE center

![Questions?](lolcats-funny-pictures-questionmark.jpg)

!SLIDE

## http://guides.rails.info/3_0_release_notes.html ##
## http://railscasts.com/tags/27 ##
## http://omgbloglol.com ##
## http://docs.heroku.com/rails3 ##
