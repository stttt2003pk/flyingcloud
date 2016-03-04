Flask example
=============

* To see what the build is doing, `tail -f build_docker.log`
* docker-machine ssh default -f -N -L localhost:8080:localhost:8080


Install
=======

* `python setup.py install`

Running Tests
=============

* `pip install -r requirements.txt`
* `pytest tests`