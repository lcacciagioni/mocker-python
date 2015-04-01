# mocker-python
Docker emulated Cloud Foundry Python Buildpack

# Usage
```bash
$ git clone https://github.com/IBM-Bluemix/python-hello-world-flask.git $HOME/workspace/python-hello-world-flask
$ docker run --rm=true -p 8080:8080 -e RUN_COMMAND="python hello.py" -v $HOME/workspace/python-hello-world-flask:/object cacciald/mocker-python:latest
```
