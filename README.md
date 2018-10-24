# helvetica_reader

helveticascans.com reader went down last month due to an SQL update conducted by the webhost the site runs on. 
The reader used by the site is out of date and no longer being worked on, thus leading to it no longer working with the update. 

I fixed some of the php database errors that were popping up due to this change, but it kept leading to one problem after another all over the place. 
I figured I should just remake a system I was more comfortable with using node for the backend system (the frontend part of the reader would be
rewritten fully in js as well as a bonus). 

That led to the creation of this repo. A day later, I learned that I wouldn't be able to run node.js on the webhost. 
They would only allow PHP to be run. This meant I would unfortunately have to learn more PHP and just fix all the problems being
caused. That was less difficult than expected, so now this repository is kind of sitting here as it's no longer needed. 

Creating a manga reader sounds a bit fun though, so I might work on it again at some point (especially once the site breaks again because it definitely will). 
