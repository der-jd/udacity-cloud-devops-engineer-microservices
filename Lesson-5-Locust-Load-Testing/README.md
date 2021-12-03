Activate virtual environment via:
source ~/.locust-test/bin/activate

Deactivate via:
deactivate

If necessary open following ports for AWS EC2 instance:
- 8080 (flask app)
- 8089 (locust)

Start app via:
"python app.py" --> access on port 8080

Start locust in another terminal via:
"locust" --> access on port 8089