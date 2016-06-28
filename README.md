# HELLO METEOR
`Meteor project practice | algobet Labs © 2016`

< hope MeteorJS can help development of apps >

## Sample Projects from Meteor Tutorials
> ### Landing - ReactJS - Submodule
`./Landing/`

    $ git submodule add https://github.com/algobet/Landing.git Landing


#### 0-to-1:


> ### Todos - ReactJS - Submodule
`./Todos/`

    $ git submodule add https://github.com/algobet/Todos.git Todos


#### 0-to-1:


#### Testing:
    $ meteor add practicalmeteor:mocha
    $ meteor test --driver-package practicalmeteor:mocha

#### What's next?
    $ meteor create --example todos
    $ meteor create --example localmarket

> ### Whatsapp - AngularJS - Submodule
`./Whatsapp/`

    $ git submodule add https://github.com/algobet/Whatsapp.git Whatsapp


#### 0-to-1:


## Examples - Submodules
> ### landing - blazeJS
`./examples/landing/`

    $ git submodule add https://github.com/DiscoverMeteor/Microscope.git examples/landing

> ### todos - reactJS
`./examples/todos/`

    $ git submodule add https://github.com/meteor/todos.git examples/todos

> ### whatsapp - angularJS
`./examples/whatsapp/`

    $ git submodule add https://github.com/DAB0mB/angular-meteor-whatsapp.git examples/whatsapp

## How to Use?
    $ git clone https://github.com/algobet/hellometeor.git
    $ cd hellometeor
    $ git submodule init

    $ git pull
    $ git submodule update
    or
    $ git submodule update --remote

    $ git add .
    $ git commit . -m "your-commit-description"
    $ git push
