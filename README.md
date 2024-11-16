Star Wars API

This project is a RESTful API that provides detailed information about the Star Wars universe, including characters, planets, and starships.

Features

	•	Character Information: Retrieve data on various characters, such as names, species, and affiliations.
	•	Planet Details: Access information about planets, including climate, population, and terrain.
	•	Starship Data: Obtain specifications of starships, like model, manufacturer, and hyperdrive rating.

Installation

To set up the project locally:
	1.	Clone the repository:

git clone https://github.com/cesarcm5/Star-Wars-API.git


	2.	Navigate to the project directory:

cd Star-Wars-API


	3.	Install the required dependencies:

pipenv install


	4.	Activate the virtual environment:

pipenv shell


	5.	Set up the database:

pipenv run init
pipenv run migrate
pipenv run upgrade


	6.	Run the application:

pipenv run start

The API will be accessible at http://localhost:5000.

Usage

Once the application is running, you can access various endpoints to retrieve information:
	•	Characters:

GET /characters


	•	Planets:

GET /planets


	•	Starships:

GET /starships



Contributing

Contributions are welcome! To contribute:
	1.	Fork the repository.
	2.	Create a new branch:

git checkout -b feature/YourFeatureName


	3.	Make your changes and commit them:

git commit -m 'Add some feature'


	4.	Push to the branch:

git push origin feature/YourFeatureName


	5.	Open a pull request.

License

This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments

This project is a fork of the 4GeeksAcademy/flask-rest-hello repository.

