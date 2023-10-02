# Project Name: Pizza-Restaurant RESTful API

**Project Description:** 
This project is a RESTful API for managing superheroes, their powers, and relationships. It allows users to view information about various superheroes, their powers, and their associations with various powers.

## Table of Contents

- [Project Name: Pizza-Restaurant RESTful API](#project-name-pizza-restaurant-restful-api)
  - [Project Description](#project-description)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Features](#features)
  - [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
  - [Usage](#usage)
  - [Contributing](#contributing)
  - [License](#license)
  

## Features

- **List of Heroes**: View a list of all superheroes.
- **Hero Details**: Get detailed information about each superhero including their powers.
- **List of Powers**: View a list of all superhero powers.
- **Power Details**: Get detailed information about each power.

## Getting Started

### Prerequisites

Ensure you have the following software installed:

- Python 3.8+
- Flask
- SQLAlchemy


### Installation

1. Clone the repository:

```bash
        git clone https://github.com/Abogeerick/superheroes-api.git

 ```
2. Move into the repository
```bash
        cd superheroes-api
```
## Usage

1. Start the server by running python3 app.py.
2. Open a web browser and go to http://localhost:5555.


## Working with Routes

Here are the details of the available routes in the HeroesPower API:

1. **View Home**:
   - **Endpoint**: `/`
   - **Method**: `GET`
   - **Description**: Returns a list of all heroes and their powers.
   - **Example Request**: 
     ```bash
     curl http://localhost:5555/
     ```

2. **View All Heroes**:
   - **Endpoint**: `/heroes`
   - **Method**: `GET`
   - **Description**: Returns a list of all heroes.
   - **Example Request**: 
     ```bash
     curl http://localhost:5555/heroes
     ```

3. **View Hero by ID**:
   - **Endpoint**: `/heroes/<int:id>`
   - **Method**: `GET`
   - **Description**: Returns details of a specific hero based on ID.
   - **Example Request**: 
     ```bash
     curl http://localhost:5555/heroes/1
     ```

4. **View All Powers**:
   - **Endpoint**: `/powers`
   - **Method**: `GET`
   - **Description**: Returns a list of all powers.
   - **Example Request**: 
     ```bash
     curl http://localhost:5555/powers
     ```

5. **View Power by ID**:
   - **Endpoint**: `/powers/<int:id>`
   - **Method**: `GET`
   - **Description**: Returns details of a specific power based on ID.
   - **Example Request**: 
     ```bash
     curl http://localhost:5555/powers/1
     ```

This will help users understand how to interact with the HeroesPower API and utilize the different endpoints available to them.



## Contributing
We welcome contributions from the community. 
Please follow our contributing guidelines for more details.

## License
This project is licensed under the MIT License.
