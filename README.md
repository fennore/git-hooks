# git-hooks

Useful [Git Hooks](https://git-scm.com/book/gr/v2/Customizing-Git-Git-Hooks) scripts.

Files are named as \<git-hook\>.\<script-name\>

Copy contents of these scripts into your existing git hooks,
or copy the script files into your .git/hooks folder inside your project and remove everything after the .(dot)

Make sure your hook files are executable (chmod +x)



1. pre-commit.php-cs-fixer:
    
    A script to run php code standards fixer before commit and seemless integrate it into your commit.
    - requires [a PHP code standards fixer like this](https://github.com/FriendsOfPHP/PHP-CS-Fixer)
