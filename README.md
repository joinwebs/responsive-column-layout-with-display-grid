<h1>responsive 12 column layout with css display grid</h1>
==========================

We are using latest display grid for responsive 12 columns layout. And we add all available css related to display:grid. 

It will work like your bootstrap columns work and it will be completely reponsive.

These Are classes

# How to Start
Just add grid.css in your project

Firs you have to create a div with grid class like this
```html


  <div class="grid grid-columns">
    <div class="width-12/12 width-6/12@sm width-10/12@md">
      12 Columns / 6 columns on small devices / 10 columns on medium device
    </div>
  </div> 

```


So inside grid you have to use column classes

# column classes
<ul>
    <li>width-1/12</li>
    <li>width-2/12</li>
    <li>width-3/12</li>
    <li>width-4/12</li>
    <li>width-5/12</li>
    <li>width-6/12</li>
    <li>width-7/12</li>
    <li>width-8/12</li>
    <li>width-9/12</li>
    <li>width-10/12</li>
    <li>width-11/12</li>
    <li>width-12/12</li>
</ul>

# Responsive Media Queries

<strong>Mobile version</strong>
<b>@media screen and (max-width: 576px){}</b>

<h4>For mobile versions Classes</h4>
<ul>
    <li>width-1/12@xs</li>
    <li>width-2/12@xs</li>
    <li>width-3/12@xs</li>
    <li>width-4/12@xs</li>
    <li>width-5/12@xs</li>
    <li>width-6/12@xs</li>
    <li>width-7/12@xs</li>
    <li>width-8/12@xs</li>
    <li>width-9/12@xs</li>
    <li>width-10/12@xs</li>
    <li>width-11/12@xs</li>
    <li>width-12/12@xs</li>
</ul>

<strong>small devices</strong>
<b>@media screen and (min-width: 577px) and (max-width: 767px){}</b>

<h4>small screen classes</h4>
<ul>
    <li>width-1/12@sm</li>
    <li>width-2/12@sm</li>
    <li>width-3/12@sm</li>
    <li>width-4/12@sm</li>
    <li>width-5/12@sm</li>
    <li>width-6/12@sm</li>
    <li>width-7/12@sm</li>
    <li>width-8/12@sm</li>
    <li>width-9/12@sm</li>
    <li>width-10/12@sm</li>
    <li>width-11/12@sm</li>
    <li>width-12/12@sm</li>
</ul>

<strong>Tablet</strong>

<b>media (min-width: 768px) and (max-width: 991.99px){}</b>

<h4>Tablet screen classes</h4>
<ul>
    <li>width-1/12@md</li>
    <li>width-2/12@md</li>
    <li>width-3/12@md</li>
    <li>width-4/12@md</li>
    <li>width-5/12@md</li>
    <li>width-6/12@md</li>
    <li>width-7/12@md</li>
    <li>width-8/12@md</li>
    <li>width-9/12@md</li>
    <li>width-10/12@md</li>
    <li>width-11/12@md</li>
    <li>width-12/12@md</li>
</ul>

<strong>desktop</strong>
<b>@media (min-width: 992px) and (max-width: 1199.99px){}</b>

<h4>Desktop Screen classes</h4>
<ul>
    <li>width-1/12@lg</li>
    <li>width-2/12@lg</li>
    <li>width-3/12@lg</li>
    <li>width-4/12@lg</li>
    <li>width-5/12@lg</li>
    <li>width-6/12@lg</li>
    <li>width-7/12@lg</li>
    <li>width-8/12@lg</li>
    <li>width-9/12@lg</li>
    <li>width-10/12@lg</li>
    <li>width-11/12@lg</li>
    <li>width-12/12@lg</li>
</ul>


<h2>Grid Helper Classes</h2>

<h5>justify content classes</h5>
<ul>
    <li>justify-content-normal</li>
    <li>justify-content-start</li>
    <li>justify-content-end</li>
    <li>justify-content-center</li>
    <li>justify-content-around</li>
    <li>justify-content-between</li>
    <li>justify-content-evenly</li>
    <li>justify-content-baseline</li>
    <li>justify-content-first-baseline</li>
    <li>justify-content-last-baseline</li>
</ul>


<h5>align content</h5>
<ul>
    <li>align-content-normal</li>
    <li>align-content-start</li>
    <li>align-content-start</li>
    <li>align-content-center</li>
    <li>align-content-around</li>
    <li>align-content-between</li>
    <li>align-content-evenly</li>
    <li>align-content-baseline</li>
    <li>align-content-first-baseline</li>
    <li>align-content-last-baseline</li>
</ul>


<h5>justify items</h5>
<ul>
    <li>justify-item-auto</li>
    <li>justify-item-normal</li>
    <li>justify-item-start</li>
    <li>justify-item-center</li>
    <li>justify-item-end</li>
    <li>justify-item-stretch</li>
    <li>justify-item-baseline</li>
    <li>justify-item-first-baseline</li>
    <li>justify-item-last-baseline</li>
</ul>


<h5>align items</h5>
<ul>
    <li>align-items-auto</li>
    <li>align-items-normal</li>
    <li>align-items-start</li>
    <li>align-items-center</li>
    <li>align-items-end</li>
    <li>align-items-stretch</li>
    <li>align-items-baseline</li>
    <li>align-items-first-baseline</li>
    <li>align-items-last-baseline</li>
</ul>

<h5>justify self</h5>
<ul>
    <li>justify-self-auto</li>
    <li>justify-self-normal</li>
    <li>justify-self-start</li>
    <li>justify-self-end</li>
    <li>justify-self-center</li>
    <li>justify-self-stretch</li>
    <li>justify-self-baseline</li>
    <li>justify-self-first-baseline</li>
    <li>justify-self-last-baseline</li>
</ul>


<h5>align self</h5>
<ul>
    <li>align-self-auto</li>
    <li>align-self-normal</li>
    <li>align-self-start</li>
    <li>align-self-center</li>
    <li>align-self-end</li>
    <li>align-self-stretch</li>
    <li>align-self-baseline</li>
    <li>align-self-first-baseline</li>
    <li>align-self-last-baseline</li>
</ul>


