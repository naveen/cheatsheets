## python ##

install packages from requirements.txt

    pip install -r requirements.txt

setup virtualenvwrapper

    pip install virtualenvwrapper
    export WORKON_HOME=~/.python
    mkdir -p $WORKON_HOME
    source /usr/local/bin/virtualenvwrapper.sh
    mkvirtualenv env1
    # change .bashrc WORKON_HOME default to yours

change to virtualenv

    workon myproject
