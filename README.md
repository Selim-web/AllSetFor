# Authentification system symfony 

Run the following commands to try the project

    git clone https://github.com/Selim-web/AllSetFor.git
    cd AllSetFor
    compose install
    In the .env file, replace db_user and db_password by your local mysql server credentials and db_name by the desired name
    symfony console doctrine:database:create // Create the db_name database
    symfony console doctrine:database:import AllSetForBase.sql // Import the provided database in order to do the authentication
    symfony serve -d // To launch the server locally
    Open the http link in a browser
    If you have an account, log in, if not, register.

