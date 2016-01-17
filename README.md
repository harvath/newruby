# newruby
Written for study purposes.
Creates a new ruby script with shebang and run permissions.
Convenient if you're into coding contests and have to write a lot of scripts.
```
nrb A001 
```
Creates A001.rb in the current directory.

Also, when you run
```
nrb test
```
while `test.rb` exists in your directory, `nrb` tries to create `test2.rb`. 
From there on, `nrb` increments the number until it finds a non-used name.
