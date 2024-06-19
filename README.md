# Automotive Manufacturing Plant

## Introduction

This project is an interactive console-based application that simulates the process of manufacturing cars in an automotive plant. The program allows users to register, choose car models, and customize various features of the car. It also maintains a record of registered users and their manufactured cars, providing functionalities to search, fetch, and remove user details.

## Functionalities

### User Registration and Management
- **Add User**: Allows new users to register with a unique registration ID.
- **Fetch All Users**: Displays a list of all registered users and their IDs.
- **Search User by ID**: Fetches detailed information about a user and their car based on the registration ID.
- **Remove User by ID**: Removes a user and their car details from the records.

### Car Manufacturing
- **Choose Model**: Users can choose from four different car models.
- **Customize Features**: Users can customize the car color, type, number of doors, maximum speed, safety features, and sound system.
- **Generate Car Details**: Displays a table with the complete details of the manufactured car.

## Setup Instructions

### Prerequisites
- Python 3.7 or higher
- PrettyTable module

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/automotive-manufacturing-plant.git
   cd automotive-manufacturing-plant
2. **Install the required package:**:
   ```bash
   pip install prettytable

### Usage

1. **Run the main application:**:
   ```bash
   python main.py

2. **Follow the on-screen prompts:**:
- Register a new user.
- Choose a car model and customize its features.
- Fetch user details, list all users, or remove a user from the records.

## Example
+-----------------+-------------------+
| Features        | Value             |
+-----------------+-------------------+
| Username        | John Doe          |
| Registration ID | ABC123            |
| Model Code      | M01               |
| Model Type      | Manual            |
| Engine Type     | Gasoline          |
| Car Type        | Sedan             |
| Car Color       | Red               |
| Engine Capacity | 1500 CC           |
| Tank Capacity   | 40.0 Ltr.         |
| Battery Capacity| None              |
| Number of Doors | 4                 |
| Maximum Speed   | 220 km/h          |
| Safety Features | Included          |
| Sound System    | Included          |
+-----------------+-------------------+

## Contributing
- Contributions are welcome! Please feel free to submit a Pull Request.


