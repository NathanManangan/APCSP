---
keywords: fastai
description: The project-based learning objective is to create a purposeful backend, something that can't be done in frontend via JavaScript.  A database and storing persistent data is a primary focus of most backend systems.  An SQLite Database using the Python SQLAlchemy framework will be the outcome of this lesson.  As students learn databases using SQLAlchemy, they will also learn about Object-oriented programming in Python.
title: Database/Model, Python, Backend, OOP
toc: true
categories: []
image: /images/python.png
type: pbl
week: 17
nb_path: _notebooks/2023-01-06-PBL-database.ipynb
layout: notebook
---

<!--
#################################################
### THIS FILE WAS AUTOGENERATED! DO NOT EDIT! ###
#################################################
# file to edit: _notebooks/2023-01-06-PBL-database.ipynb
-->

<div class="container" id="notebook-container">
        
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Database-and-Table-Terms">Database and Table Terms<a class="anchor-link" href="#Database-and-Table-Terms"> </a></h2><blockquote><p>The foundations of database is defining one or more <strong><em>Tables</em></strong>.  In Python, a database can be constructed using the foundations we learned in modeling a Class.</p>
<ul>
<li>A "Table" is a Model/Schema within a Database.  </li>
<li>A "Table" definition in Python/SQLAlchemy is manifested by defining a "<strong><em>Class</em></strong>" and "<strong><em>Attributes</em></strong>" in Python.  </li>
<li>A Python <strong><em>Class can inherit database functionality</em></strong> from SQLAlchemy.  This is a method Python developers use to turn a Class into a Table within a <strong><em>SQL Database</em></strong>.</li>
<li>Writing methods in the Class for Create, Read, Update, Delete (<strong><em>CRUD</em></strong>) is how a developer initiates database operations.</li>
</ul>
</blockquote>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Reference">Reference<a class="anchor-link" href="#Reference"> </a></h2><ul>
<li><a href="https://www.sqlalchemy.org/">SQLAlchemy</a></li>
<li><a href="https://www.ffnext.io/blog/python-backend-with-flask-for-beginners#:~:text=You%20can%20create%20an%20HTTP,command%3A%20python%20app.py.">Python Backend with Flask, SQLite</a></li>
<li><a href="https://www.ffnext.io/blog/python-backend-with-flask-for-beginners#:~:text=You%20can%20create%20an%20HTTP,command%3A%20python%20app.py.">Backend API and Flask</a></li>
</ul>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Working-outline-for-blog">Working outline for blog<a class="anchor-link" href="#Working-outline-for-blog"> </a></h2><p>Review this code to understand concepts so far...</p>
<ol>
<li>Model Defining the <a href="https://github.com/nighthawkcoders/nighthawk_csp/blob/master/crud/model.py#L25">Table</a> Class</li>
<li>Model <a href="https://github.com/nighthawkcoders/nighthawk_csp/blob/master/crud/model.py#L84">Testing and Initial Setup</a></li>
<li>Model Defining function to support <a href="https://github.com/nighthawkcoders/nighthawk_csp/blob/master/crud/model.py#L40-L81">CRUD operations</a> </li>
<li>Control Methods for <a href="https://github.com/nighthawkcoders/nighthawk_csp/blob/master/crud/app_crud.py#L63-L113">Create</a>, <a href="https://github.com/nighthawkcoders/nighthawk_csp/blob/master/crud/app_crud.py#L63-L113">Read</a>, <a href="https://github.com/nighthawkcoders/nighthawk_csp/blob/master/crud/app_crud.py#L63-L113">Update</a>, <a href="https://github.com/nighthawkcoders/nighthawk_csp/blob/master/crud/app_crud.py#L63-L113">Delete</a> or Alternative <a href="https://github.com/nighthawkcoders/nighthawk_csp/blob/master/crud/app_crud.py#L138-L189">CRUD API definitions </a></li>
<li>View Here is a <a href="https://csp.nighthawkcodingsociety.com/crud/">runtime</a> showing off some CRUD. All the MVC code is show at the bottom of this page.</li>
</ol>
<p>To get started with databases, perhaps you can simply try to get some Database Code running in your project.  Then you could try to define a new Table in you database.  After pulling code, you will need to Init your database and table by running the <a href="https://github.com/nighthawkcoders/nighthawk_csp/blob/master/crud/model.py#L121">Tester Method</a>.</p>

</div>
</div>
</div>
</div>
 
