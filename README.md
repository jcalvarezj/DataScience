# DataScience

This corresponds to the Data Science system of the $(PROJECT_NAME) project that serves as a Web Scraping module that retrieves all the jobs of interest from different platforms:

- [Empleos TI](https://empleosti.com.mx/)
- [Get on Board](https://www.getonbrd.com/)  (Using its [public REST API](https://api-doc.getonbrd.com/))


## Requirements

**Python 3.x**, any version of **pip**, and **virtualenv**


## Installation

- Clone into a new directory and navigate inside it

- Create a new virtual environment using **virtualenv**

    For example, `virtualenv venv`

- Activate venv

    For Windows: `.\venv\Scripts\activate.bat`

    For Unix/Linux: `source venv/bin/activate` or `./venv/bin/activate.sh`

    (Run the `deactivate` command when done with this software's execution)

- Install dependencies

    `pip install -r requirements.txt`


## Execution

Use either  `python main.py <label of site>`  or  `python3 main.py <label of site>`

Site labels are **gob** for Get on Board and **empleosti** for EmpleosTI