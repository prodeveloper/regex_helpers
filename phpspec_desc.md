Quickly generate command for phpspec description file

##Input data sample

/var/www/src/Chencha/Conveyor.php

##Regex

\*([\s\S]*?)src(\/([\s\S]*?)\/)([\s\S]*?)(.php)\*

##Substitution

phpspec desc $3/$4

##Sample output

phpspec desc Chencha/Conveyor
