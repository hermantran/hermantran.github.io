---
layout: post
title: Thoughts on Backbone and Angular
description: I recently started rebuilding a Backbone-based project into using Angular with some expectations of eventually siding with one framework, but I ended up finishing the rebuilding process with an appreciation for what both have to offer.
comments: true
---

<p>I recently started rebuilding a <a href="http://ec2-54-200-181-70.us-west-2.compute.amazonaws.com" target="_blank">Backbone-based project</a> into <a href="http://ng-racesurfer.aws.af.cm" target="_blank">using Angular</a> with some expectations of eventually siding with one framework, but I ended up finishing the rebuilding process with an appreciation for what both have to offer.</p>

<p>The project in question is a geolocation app that plots running race events near the user and lists associated event details. I first built the project with plain old jQuery for my <a target="_blank" href="http://web-app.usc.edu/soc/syllabus/20123/31835.pdf">ITP 404 class (Developing Web Services and APIs)</a>, and given that the project is a single page app, it made sense to rebuild it with Backbone and then Angular when I started learning each framework. The project is small enough in scope to rebuild but still non-trivial, with support for the following features:</p>

<ul>
    <li>Geolocation, Google Maps, and Active API integration</li>
    <li>Term search to filter results</li>
    <li>Paginated results with infinite scrolling</li>
    <li>Event bindings between DOM elements and Google Map markers
    <li>Routing for deep links to search results</li>
</ul>

<p>Now having used both Backbone and Angular for this project, I can say there are parts of both frameworks that I like for making the project easier to implement.</p>

<h3>Data binding</h3>
<p>This is definitely the first thing I noticed about Angular coming from Backbone; it is so ridiculously easy to do two-way data binding in Angular. I guess this feature might be less impressive if I came from Knockout or Ember instead, but at least this is where Angular clearly shines in comparison to Backbone, which feels more roundabout with the need to wire up event listeners on the model. Angular's two-way data binding helped just slightly because I only needed the data-binding on a single search input, but I could imagine how useful this feature would quickly become with lots of different models that constantly update and need their changes reflected in the views.</p>

<h3>Views</h3>
<p>Again, Angular makes it easy to render views by changing the way that HTML is written so that we can avoid messy DOM manipulation inside the controllers. I didn't need to target elements or add CSS classes to the search results from outside the view. There is a bit of a learning curve but for the most part, it only involves adding <code>ng-</code> attributes to regular HTML elements.</p>

<p>In Backbone, by nature of the Backbone "View" also acting as a controller of sorts, there is a tighter coupling where the controller has to specifically target the element selectors in the templated views, making it harder to swap out views. In addition, I always found it a little awkward how Backbone either makes you tie a rendered view with an element already declared in HTML through the <code>el</code> property, or it makes you manually append the view to the DOM after rendering the view. This is where having built-in support for Backbone Marionette's Layout Manager would come in handy.</p> 

<h3>Models</h3>
<p>I was looking for the equivalent of Backbone Models and Collections in Angular and I couldn't find them. It seems like the convention is to wrap <code>$http</code> or <code>$resource</code> in a Service as the equivalent to Backbone's <code>fetch</code> and <code>sync</code> methods, and then simply represent the models as plain old JavaScript objects in the controller's <code>$scope</code>. This doesn't allow much reusability when creating custom properties on models, but I suppose the additional functions could be stuffed into the Services. I just thought Angular could be a little more opionionated about how to represent models, given the amount of structure it enforces on all the other components.</p>

<p>There's also the added functionality built into Backbone Models and Collections that I found really useful. In particular, the <code>add</code> and <code>set</code> methods made it easier to work with paginated results and specify when to overwrrite or simply append results. I just had to bind the appropriate event listener to the model's methods from the Backbone Views to re-render correctly. In Angular, this wasn't as simple as letting <code>ng-repeat</code> do its magic because that can't be used with Google Map markers, which exist outside the context of Angular.</p> 

<h3>Dependency Management</h3>
<p>Declaring dependencies in each Angular component is definitely much better in terms of modularity and testability. I guess it would also be nice if Angular took on the responsibility of loading those dependencies as well. I have gotten used to including RequireJS in all my projects, and pairing it with Angular proved quite redundant but I still needed it for automatic script ordering and lazy loading.</p>   

<p>&nbsp;</p>
<p>Next time, I'll probably try integrating React as the view component in Backbone, or perhaps I'll just use a Backbone Model plugin for Angular. Either way, I think both frameworks have their merits, and I will continue using both for future projects.</p>