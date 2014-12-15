Spring MVC Tiles 3 integration
==============================

<p>One of the areas in which Spring MVC has advance compares to other frameworks is in the separation of view technologies. In this post, i will show how to integrate Apache Tiles 3 with Spring MVC. Apache Tiles is a free open-source template engine for java web frameworks. It’s based on Composite pattern and used to simplify the development of user interfaces.</p>

<p>The benefits of using Apache Tiles is we can create a base template which has common UI screens (like Header, Footer, Menus etc) and later have our own customized Screens which can extends tiles base template defination.</p>

<h4>Tiles defination</h4>
<p>Look at the tiles defination below, I have created a base defination (<code>DefaultTemplate</code>) which has Header, Menu, Footer attributes. All other definations extend this base defination and has common attributes available in all extended definations.</p>

<img src="http://www.techzoo.org/wp-content/uploads/2014/07/tiles-diagram.png" />

<p>You can view complete <a href="http://www.techzoo.org/spring-framework/spring-mvc-tiles-3-integration-tutorial.html">Spring MVC Tiles 3 integration</a> post on my blog <a href="http://www.techzoo.org">TechZoo</a>.</p> 
