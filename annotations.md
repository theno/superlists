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


## P.166 Meaning of tags

Why two tags? What is the difference between 'LIVE' and 'DEPLOYED-...'?

thinking... Ok i got it :-)
* 'LIVE' is the tag of the productive version currently running
* 'DEPLOYED-...' means: This version had been deployed on ... 

After several deployments the 'DEPLOYED-...' tags tell you a deployments history.

## P. 175 Don't understand paragraph 'Using Model-Layer Validation'

What are forms level tests?

## P. 183

Extra hint of the newly inserted slash after '{{ input.id }}'. It's too easy to oversee.

## P. 196

No linebreak on the verbatim word 'textarea'.

## P. 202

    grep -Ir item_text lists
catches "0002_item_text" in lists/migrations/0003_list.py

## Ambiguous class where to add the test

## P. 235 For the protocol

Add hint to make a final commit at the end of this chapter.
