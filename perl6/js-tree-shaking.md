Tree Shaking for the JS backend
==================================

Description
-----------

Implement a way to avoid bundling unused code when compiling a Perl 6 program to JavaScript for browser user.
The tree shaking should determine which parts of the builtin setting a Perl 6 program uses and extract those.
This will likely imply changing the way code is generated by the JavaScript backend so we know which parts of the output are responsible for what. Serialized objects will also need to be examined to determine dependencies.

Expected outcomes
-----------------

Tree shaking should allow our parcel plugin to compile Perl 6 programs of moderate complexity into 
significantly smaller JavaScript bandles then we get with bundling of everything.

Required skills
---------------

JavaScript knowledge, ability to work with a fairly complex code base (with guidance).

Rating
------

hard

Possible mentors
----------------

Paweł Murias 