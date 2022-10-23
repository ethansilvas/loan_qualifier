# Module 2 Challenge - Loan Qualifier 

This program is an automated loan qualifier that has an interactive CLI which allows users to test which banks their loan would qualify at.<br>
There is dynamic functionality that allows the user to provide bank data and opt to save the qualifying loan data to an external file. 

---

## Technologies

This is a Python 3.7 project

The following dependencies are used: 

[Python Fire](https://github.com/google/python-fire) - for intuitive and easy creation of the project's CLI <br>
[Questionary](https://github.com/tmbo/questionary) - to create CLI prompts/interactions to handle user input 

---

## Installation Guide

To install each of the required dependencies, run the following commands: 

```
pip install fire
pip install questionary
```

---

## Usage

To begin using this program, start the app by running app.py in your terminal like so: 

```python
python app.py
```

You will then be prompted to enter all the information needed to calculate loan worthiness. Type your response to each one and press enter to move on to the next prompt.

Here is an example of a successful run of the program resulting in loans being saved to a provided file: 
![Terminal output of loan information prompts and successful save to file](images/loan_qualifier_usage.png)

---

## Contributors

[Ethan Silvas](https://github.com/ethansilvas)

---

## License

This project uses the [GNU General Public License](https://choosealicense.com/licenses/gpl-3.0/)
