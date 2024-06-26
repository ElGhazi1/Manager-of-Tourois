# Football Tournament System

This project is a web-based football tournament management system. It allows users to register teams, organize matches, record results, and display the tournament standings. The system is designed to streamline the process of managing a football tournament from start to finish.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [License](#license)

## Features

- User authentication (login and signup)
- Register and manage teams
- Schedule matches
- Record match results
- Display tournament standings and results
- Responsive design for mobile and desktop

## Technologies Used

- HTML, CSS, JavaScript (Frontend)
- PHP (Backend)
- MySQL (Database)
- Bootstrap (CSS Framework)
- jQuery (JavaScript Library)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/ElGhazi1/football-tournament-system.git
    cd football-tournament-system
    ```

2. Set up the database:
    - Create a MySQL database named `football_tournament`.
    - Import the `tables.sql` file to create the necessary tables:
      ```sql
      mysql -u your_username -p football_tournament < tables.sql
      ```

3. Configure the database connection:
    - Edit the `connectToDatabase.php` file with your database credentials:
      ```php
      $servername = "your_servername";
      $username = "your_username";
      $password = "your_password";
      $dbname = "football_tournament";
      ```

4. Start a local server and navigate to `index.php` in your browser:
    - Using XAMPP, MAMP, or any local server setup.

## Usage

1. **User Authentication:**
   - Users can sign up and log in to access the tournament management features.

2. **Dashboard:**
   - After logging in, users are redirected to the dashboard (`dashboard.php`), where they can manage teams and matches.

3. **Register Teams:**
   - Use the `equipeForme.php` page to register new teams.

4. **Schedule Matches:**
   - Schedule matches using the `enregister_tournois.php` page.

5. **Record Match Results:**
   - Record results of matches using the `results_matchs.php` page.

6. **View Results:**
   - View the results and standings on the `display_results.php` page.

## File Structure

.
├── css
│ └── (CSS files)
├── images
│ └── (Image files)
├── js
│ └── (JavaScript files)
├── connectToDatabase.php
├── dashboard.php
├── display_results.php
├── enregister_tournois.php
├── equipeForme.php
├── get_teams.php
├── home.php
├── index.php
├── login.php
├── logout.php
├── matchsToDB.php
├── plan.docx
├── README.md
├── resultats.php
├── results_matchs.php
├── session\ plan.docx
├── session_manager.php
├── signin.php
├── tables.sql
├── tournoiToDB.php
├── traitement_display_results.php
└── traitement_equipe.php


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
