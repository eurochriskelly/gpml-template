# About 

 *** DRAFT VERSION ***

`gpml-template` is a (G)ithub (Package) (M)ark(L)ogic Template.

This is a template that can be checked out to create a MarkLogic package for used
in both gradle and nodejs.

# Publishing your package

1. Create a github PAT with `read:packages`, `write:packages`, and (optionally) `delete:packages` scope scopes
2. The log in using:
   `npm login --registry=https://npm.pkg.github.com --scope=@your-username`

   For password, please provide the PAT.

# Accessing packages

Update your .npmrc to look in repositories where ml packages can be found.

e.g. To download from this repostiory, add the line:

`@eurochriskelly:registry=https://npm.pkg.github.com`

Then in a new git repository, run something like:

`npm install @eurochriskelly/gpml-template`

