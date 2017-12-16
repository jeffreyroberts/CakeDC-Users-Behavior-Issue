To reproduce the error, execute the following commands

    git clone https://github.com/jeffreyroberts/CakeDC-Users-Behavior-Issue.git
    cd CakeDC-Users-Behavior-Issue
    composer install

** Edit the app.php with your DB Details **

    bin/cake migrations migrate --plugin CakeDC/Users
    bin/cake server -p 9000
    
** Navigate to following URL and Complete the Form **

    http://localhost:9000/register