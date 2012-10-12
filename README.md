To build the basebox with veewee, use current git master branch of veewee:

    veewee vbox build wheezy
    vagrant basebox export wheezy

Import the base box with:

    vagrant box add wheezy wheezy.box

And boot it up:

    vagrant up

