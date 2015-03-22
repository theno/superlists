Suggestions for the Autor and Notes for Myself
==============================================

## P.154

Replace SITENAME, with, eg., superlists-staging.theno.eu

## P.425

typo (slash instead of dot), correct:

    template: src=./gunicorn.upstart.conf.j2"
    
Inconsistent user name. 'harry' instead of 'elspeth'
(likewise it is been used in the rest of this book)

## P.426

typo ('ansible' before 'inventory'), correct:

    ansible-playbook -i inventory.ansible  ...


## P. Meaning of tags

Why two tags? What is the difference between 'LIVE' and 'DEPLOYED-...'?

thinking... Ok i got it :-)
* 'LIVE' is the tag of the productive version currently running
* 'DEPLOYED-...' means: This version had been deployed on ... 

After several deployments the 'DEPLOYED-...' tags tell you a deployments history.

## P. 175 Don't understand paragraph 'Using Model-Layer Validation'

What are forms level tests?

## P. 183

Extra hint of the newly inserted slash after '{{ input.id }}'
