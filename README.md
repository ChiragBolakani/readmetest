# Measure Visual Acuity API
## Team SecureVision

**'Smart Vision'** is a human intrusion detection based system which detects unknown/uninvited person in the owner's house and notify the user via Call and SMS. 

## Description
To develop a solution that can be used to conduct eye tests in regions with a lack of space and ambience issues, especially rural areas. 

## Requirements
All the necessary python modules and libraries are mentioned in **requirements.txt** file. Make sure you have them installed(or install them if not present) before running the project.

- Install all libraries mentioned in requirements.txt
 ```python
pip install -r requirements.txt
```
- For twilio setup, please make a free account [here](https://www.twilio.com/try-twilio) and paste the obtained the account id and auth_token in mva_api.py file.
- Mongo-URI has to be provided for database connectivity

## Usage
- The api takes in the following parameters such as 'position', 'distance', 'dpi', 'chart_type'.
- Based on the parameters the image of the chart will be returned, that is to be displayed in the display app.
 ```python
mva_api.py
```

## Screenshots
![Screenshot (237)](https://user-images.githubusercontent.com/62014238/116792635-86be9d00-aadf-11eb-964b-d432fabd1563.png)
![Screenshot (238)](https://user-images.githubusercontent.com/62014238/116792638-8c1be780-aadf-11eb-9107-060de5c41dbc.png)


