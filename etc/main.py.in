import sys
sys.path.insert(0, "./libs")

from google.appengine.ext.webapp.util import run_wsgi_app
from flask import Flask

app = Flask(__name__)

@app.route('/')
def index():
    return 'Hello Flask on Google App Engine!'

run_wsgi_app(app)
