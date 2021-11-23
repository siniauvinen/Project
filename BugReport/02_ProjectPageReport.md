
## Summary

The title for creating a new project includes a typo. The word "black" should be "blank".

## Steps to reproduce
1. Navigate to https://gitlab.com/projects/new
2. See the title of "creating a black project", located in the upper-left corner of the grid.


## Example Project


## What is the current bug behavior?

The title for creating a new blank project states "Create black project"    

## What is the expected correct behavior?

The title for creating a new project should state "Create blank project"
     
## Relevant logs and/or screenshots

Screenshot of bug and the code causing the bug can be found from Project > Image > Bug_Code.png 

## Possible fixes

Code now with the bug
"<h3 class="gl-font-size-h2 gl-reset-color"> Create black project </h3>"

Code should be
"<h3 class="gl-font-size-h2 gl-reset-color"> Create blank project </h3>"

      
