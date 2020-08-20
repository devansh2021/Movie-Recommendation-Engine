## Movies Recommendation Engine

Built a Movie Recommendation Engine in the form of a web-app which recommends movies using user-user collaborative ﬁltering.

### Tech Stack

Built API using web2py (Python based framework) and Front-end using JavaScript
with VueJS

## Installation Instructions

Clone the repository and run:

    python web2py.py

That's it!!!

## Directory structure

    project/
        README
        LICENSE
        VERSION                    > this web2py version
        web2py.py                  > the startup script
        anyserver.py               > to run with third party servers
        ...                        > other handlers and example files
        gluon/                     > the core libraries
            packages/              > web2py submodules
              dal/
            contrib/               > third party libraries
            tests/                 > unittests
        applications/              > are the apps
            admin/                 > web based IDE
                ...
            examples/              > examples, docs, links
                ...
            welcome/               > the scaffolding app (they all copy it)
                ABOUT
                LICENSE
                models/
                views/
                controllers/
                sessions/
                errors/
                cache/
                static/
                uploads/
                modules/
                cron/
                tests/
            ...                    > your own apps
        examples/                  > example config files, mv .. and customize
        extras/                    > other files which are required for building web2py
        scripts/                   > utility and installation scripts
        handlers/
            wsgihandler.py         > handler to connect to WSGI
            ...                    > handlers for Fast-CGI, SCGI, Gevent, etc
        site-packages/             > additional optional modules
        logs/                      > log files will go in there
        deposit/                   > a place where web2py stores apps temporarily

### Recommendations Model File:

    item_similarity_df.csv

Posters for each movie is from MovieLens dataset.
Filename corresponds to the ‘movieId’.
It is open-sourced at: https://github.com/babu-thomas/movielens-poster
![Screenshot](ss-1)
