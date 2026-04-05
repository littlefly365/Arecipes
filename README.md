# Arecipes
Arecipes (or Aqua Recipes) are build instructions to build each package for a musl system form scratch.

# What is a Cakefile?
- A cakefile is our Makefile contrapart, we use it to configure and build. They are interpreted by cake.

# What language is used?
At the begging we used a Custom language for our recipes (similar to YAML) and cake in C, but the process was a little bit dificult for some decisions, so we rewrite everything in Lua.

# Can i use it for my own distribution?
of courses, but you should say where recipes from