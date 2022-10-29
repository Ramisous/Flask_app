The purpose of this Flask application is to predict whether a basketball player is good or not based on its statistics.

To launch this application, clone the repository :

```
git clone https://github.com/Ramisous/Flask_app.git
```
In the new folder, create a python environment and activate it:
```
cd Flask_app
python -m venv env
source env/scripts/activate
```
install the libraries:
```
pip install -r requirements.txt
```
import flask and run the application:
```
python -c "import flask"
export FLASK_APP=app
export FLASK_ENV=development
flask run
```

This command shows you the localhost port that launchs the application ('http://127.0.0.1:5000/' in general)
