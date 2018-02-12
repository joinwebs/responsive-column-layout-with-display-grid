# responsive 12 column layout with css display grid
==========================

We are using latest display grid for responsive 12 columns layout. And we add all available css related to display:grid. 

It will work like your bootstrap columns work and it will be completely reponsive.

These Are classes

# How to Start
Just add grid.css in your project

Firs you have to create a div with grid class like this

<pre>
  <div class="grid grid-columns"></div> 
</pre>

So inside grid you have to use column classes

# column classes
width-1/12, width-2/12, width-3/12, width-4/12, width-5/12, width-6/12, width-7/12, width-8/12, width-9/12, width-10/12, width-11/12, width-12/12

# Responsive Media Queries

//Mobile version
@media screen and (max-width: 576px){}

# For mobile versions Classes

width-1/12@xs, width-2/12@xs, width-3/12@xs, width-4/12@xs, width-5/12@xs, width-6/12@xs, width-7/12@xs, width-8/12@xs, width-9/12@xs, width-10/12@xs, width-11/12@xs, width-12/12@xs

//small devices
@media screen and (min-width: 577px) and (max-width: 767px){}

# small screen classes
width-1/12@sm, width-2/12@sm, width-3/12@sm, width-4/12@sm, width-5/12@sm, width-6/12@sm, width-7/12@sm, width-8/12@sm, width-9/12@sm, width-10/12@sm, width-11/12@sm, width-12/12@sm

//Tablet
@media (min-width: 768px) and (max-width: 991.99px){}

# Tablet screen classes
width-1/12@md, width-2/12@md, width-3/12@md, width-4/12@md, width-5/12@md, width-6/12@md, width-7/12@md, width-8/12@md, width-9/12@md, width-10/12@md, width-11/12@md, width-12/12@md

//desktop
@media (min-width: 992px) and (max-width: 1199.99px){}

# Desktop Screen classes
width-1/12@lg, width-2/12@lg, width-3/12@lg, width-4/12@lg, width-5/12@lg, width-6/12@lg, width-7/12@lg, width-8/12@lg, width-9/12@lg, width-10/12@lg, width-11/12@lg, width-12/12@lg
