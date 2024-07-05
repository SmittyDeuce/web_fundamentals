# API Fundamentals

## Project Introduction

This project demonstrates how to interact with public APIs using Python. It includes scripts for fetching and processing data from the Pokémon API and the Solar System OpenData API.

## Setup Instructions

### Python Environment Setup:

1. Ensure Python 3.x is installed.
2. Create a virtual environment:

   ```bash
   python -m venv myenv

   # Windows
   .\myenv\Scripts\activate

   # macOS/Linux
   source myenv/bin/activate


## Scripts Overview

### get_pokemon.py

#### Purpose:
This script interacts with the Pokémon API to fetch and display data about specific Pokémon.

#### Functionalities:
- `fetch_pokemon_data(pokemon_names)`: Fetches data (names and abilities) for specified Pokémon.
- `fetch_pokemon_weight(pokemon_names)`: Calculates the average weight of specified Pokémon.

#### Usage:
Execute `get_pokemon.py` to fetch and display Pokémon data.

### digital_cosmos.py

#### Purpose:
This script interacts with the Solar System OpenData API to fetch and display planet data.

#### Functionalities:
- `fetch_planet_data()`: Fetches and displays planet names, masses, and orbit periods.
- `heaviest_planet()`: Identifies and prints the heaviest planet.

#### Usage:
Execute `digital_cosmos.py` to fetch and display planet data.

### Dependencies

- Python 3.x
- requests library
