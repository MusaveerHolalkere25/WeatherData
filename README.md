# Build a Flask API that fetches live weather data from an external API and returns it in JSON format.

**Step 1: Sign Up for an API Key**

```python
Go to OpenWeatherMap Signup

Go to the API Keys page and get a free API key.

NOTE : API key will take few hours to get activated
```

**Step 2: Install Required Packages**

```python
pip install flask requests
```

**Step 3: Create the Flask API (weather_api.py)**

**Step 4: Run the Flask API**

```python
python weather_api.py
```

**Step 5: Test the API**

```python
Using Curl

curl "http://127.0.0.1:5000/weather?city=London"

Using a Browser

Open: http://127.0.0.1:5000/weather?city=London
```