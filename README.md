# Le Wagon - MLOps Optimization : Taxi fare estimator
# Streamlit app

This project is a Streamlit application that estimates taxi fares based on user inputs, including pickup and dropoff locations, date and time, and passenger count.

## Requirements
To run this application, you need to have Python installed on your machine, along with Poetry for dependency management.

## Installing Poetry

If you haven't already installed Poetry, you can do so by following the instructions on the [Poetry website](https://python-poetry.org/docs/#installation). The most common installation command is:

```bash
curl -sSL https://install.python-poetry.org | python3 -
```
Make sure to follow any additional instructions to ensure that the Poetry binary is in your PATH.


## Setting Up the Project
1. Clone the Repository (if applicable):

```bash
git clone <repository-url>
cd <repository-directory>
```

2. Install Dependencies:

Navigate to the project directory and run:

```bash
poetry install
```
This command will create a virtual environment and install all required dependencies specified in the pyproject.toml file.

## Running the Application

1. Activate the Virtual Environment:
Activate the Poetry virtual environment with:
```bash
poetry shell
```
2. Run the Streamlit App:

While in the activated virtual environment, run:

```bash
streamlit run map.py
```

3. Access the App:

After running the command, you will see output in the terminal with a local URL (e.g., http://localhost:8501). Open this URL in your web browser to access the Taxi Fare Estimator application.

## Usage
- Select the date and time for your ride.
- Input the number of passengers (between 0 and 8).
- Click on the map to select the pickup and dropoff locations.
- The estimated fare will be displayed based on the selected parameters.

## Notes

Ensure that your internet connection is active, as the app makes a request to an external API to fetch fare estimates.
If you encounter any issues, check the console for error messages and troubleshoot accordingly.

## License
This project is licensed under the MIT License
