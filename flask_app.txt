from flask import Flask,render_template
app = Flask(__name__)


@app.route('/')
def index_roue():
    return "Welcome to my Koyeb/GitHub site" #render_template('index.html')
