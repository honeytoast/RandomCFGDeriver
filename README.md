# RandomCFGDerivator
A project for Theory of Computability class that takes a context free grammar file and derives a random correct string.

Included files:

Filename | Description
---------|-------------
grammar.py | python3 source containing the grammar class
variable.py | python3 source containing the variable class
variable_reference.py | python3 source containing the variable reference class
random_cfg_derivator.py | the main python3 source that algorithmically determines a random correct string from a given cfg file
teatime.cfg | a file containing a context free grammar I made up.
sampleout | a text file containing a sample output

**How to run:**

python3 random_cfg_derivator.py {cfg filename}

About the project:

The random_cfg_derivator program derives strings randomly from a context free grammar.

A context free grammar is made of a set of rules that describe how a variable can be replaced with a string comprising of symbols and/or more variables.
