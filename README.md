# phpstan-practice

# command
vendor/bin/phpstan analyse <options> <paths>
# example 
cd C:\Apache24\htdocs\phpstan-practice
# and then  -l = --level and src is the folder you want to analyse
vendor/bin/phpstan analyse -l 2 src


# to ignore php stan error
/** @phpstan-ignore-next-line */
# OR
/** @phpstan-ignore-line */