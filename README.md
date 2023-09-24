# Documentation_my_four_cents
Looking at how to document, possibly structure a git-repo, using Quarto?

## Based upon: 

+ At Fontys ICT we are mainlly ICT persons, so documentation should be in version control.
+ At this moment the de facto standard for version control is git.
+ 
+ Canvas is our LMS, so we are looking for a maintainable way to get the lesson materials in canvas.

### Canvas for structure vs documents for content

+ Canvas tells us about the week structure, deadlines, where to upload what (and when).
+ The course content is in documents (that are uploaded in canvas).
+ From canvas module only some 3 clicks needed, preferably, to reach the info you are looking for. 
+ Standard document types are
  + pdf  - text, theory, assignments, looks similar in different viewers. 
  + pptx - for slides. 
  + zip  - containing programming material,  or projects created by students.
  + url  - to a git repo. If it contains student made work they uploaded, for the 'toetsdossier' this (also) has to be uploaded in a zip at the end of the semester. 

### self-contained

The content in a document should be more or less self-contained, which means: 
+ If the document contains an assignment or challenge, *all* info about the content of that assignment/challenge should ideally be ín the document.
+ To put documentation in version control, markdown is used a lot nowadays, and
    easy to learn. ms-Word is not very practical with version control, LaTeX
    is too big a hurdle for people that did not already get acquanted. 
+ Quarto looks promising to create documents by including content from markdown
    and other formats. The resulting documents can be several types: mainly pdf
    and/or a website seem relevant for us. 


