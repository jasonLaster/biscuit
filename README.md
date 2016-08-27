# biscuit
A terminal debugger for remote js processes a.k.a the browser or node duh. 

## Goal

Help you debug JS in all of the cases where JS is not running in your browser. 

## Secondary Goal

Be a hip cli alternative to those pretty GUI debuggers you know and love

## Use Cases

* debugging browsers running in CI 
* debugging embedded / headless browsers
* debugging your node server in a different terminal tab

## How would it work

* run biscuit in the terminal to launch the debugger
* run connect to connect to a browser or node process 
* run tabs to see available tabs to debug
* run debug to attach to a tab
* run commands like sources, breakpoint, etc to do debugy things
