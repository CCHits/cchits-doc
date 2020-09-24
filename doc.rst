The documentation
=================

This documentation is hosted on github. Each time a pull request is made, the documentation is built, but not published.
Once the mainteners are happy with the result, the pull request is merged, and the documentation is rebuilt automatically,
and becomes the new current version.

How to contribute
-----------------

This is the prefered way to contribute to this documentation.

If you are familliar with another workflow, then feel free to use that instead of what is documented here.

Obviously, you will still need to install Sphinx to preview the doc before you send a pull request.

First, you need to have `python3` and `pip` installed on your machine. 
How you do that is beyond the scope of this document.

Once you have those two pieces of software installed, fork the `documentation repositoy <https://github.com/CCHits/cchits-doc>`_.

Then, clone your own repo : 

.. code-block:: shell

    git clone git@github.com:username/cchits-doc.git

Change to that directory : 

.. code-block:: shell

    cd cchits-doc

Add upstream reference :

.. code-block:: shell

    git remote add upstream https://github.com/CCHits/cchits-doc.git

Create a new branch to work from :

.. code-block:: shell

    git checkout -b myfeature

Install required python modules :

.. code-block:: shell

    pip install -r requirements.txt

Add, remove, edit files.

Build the documentation locally : 

.. code-block:: shell

    make html

Point your browser to `_build/html/index.html`

If everything looks good, commit and push your changes : 

.. code-block:: shell

    git add .
    git commit -m 'A message describing the changes'
    git push -u origin myfeature

Send a pull request via the GitHub interface.

**Do not commit on this branch until the pull request is merged**

Once the pull request is merged, you can delete your local and remote branches :

.. code-block:: shell

    git checkout main
    git branch -d myfeature
    git push origin --delete myfeature

Synchronize your local main branch with upstream's main branch :

.. code-block:: shell

    git fetch --all
    git merge upstream/main
    git push -u origin main

Your local and remote repositories are now in synch with upstream's main branch.

You can now create a new branch to begin working on another feature.
