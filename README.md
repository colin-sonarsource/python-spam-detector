# Spam Detector App
This is a simple Flask web application that detects spam messages based on predefined spam words. The application uses SQLite as the database to store spam messages and spam words.

## Installation
### Prerequisites

- Python 3.x
- pip (Python package installer)

### Steps
1. Clone the repository:

```
git clone https://github.com/fiveshotsofespresso/spam-detector-app.git
cd spam-detector-app
```

2. Create a virtual environment (optional but recommended):

```
python3 -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

3. Install the required packages:

```
pip install -r requirements.txt
```

4. Run the application:

```
python3 app.py
```

5. Open your web browser and navigate to:

```
http://127.0.0.1:5000/
```

## Usage
- Enter a message in the input field and click "Check" to see if the message might be spam.
- The application will display all spam messages and related spam messages based on the input. 
