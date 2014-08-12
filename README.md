#nitpick - A visualisation library for NuPIC

All notebooks can be viewed using IPython's nb viewer website here:  http://nbviewer.ipython.org/github/rhuairahrighairidh/nitpick/tree/master/

Demo of use: [demo notebook](http://nbviewer.ipython.org/github/rhuairahrighairidh/nitpick/blob/master/nitpick/documentation/demo.ipynb)


##Installation Instructions

This library can be fully installed using the standard python package manager ```pip```

To install run the following:

    pip install https://github.com/rhuairahrighairidh/nitpick/archive/master.zip

To uninstall run:

    pip uninstall  nitpick

This library is designed to be used with IPython. It doesn't require IPython to be installed but if you want to install ipython run:

    pip install ipython[all]
    
This installs ipython and makes sure all its dependencies are installed. (just running ```pip install ipython``` will not allow you to run the ipython notebook)

###Additional guidlines:

The above works fine but using virtualenv is generally a better method.
For an introduction see [A non-magical introduction to Pip and Virtualenv for Python beginners](http://www.dabapps.com/blog/introduction-to-pip-and-virtualenv-python/)

If you install this in a virtualenv then it will install numpy and matplotlib as well. This takes a while. You can get round the wait if you have these two installed on your system. In this case tell virtualenv to use the system packages by adding on the option "--system-site-packages" when creating your virtualenv. Like this

    virtualenv myNewEnv --system-site-packages

Now when a package is not found in the virtualenv, python will look in the system wide location as well.


