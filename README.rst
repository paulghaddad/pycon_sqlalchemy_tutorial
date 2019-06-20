=======================================
Introduction to SQLAlchemy - Pycon 2013
=======================================

This package contains the student prerequisite handout as well
as the in-class software we'll be running.

Tutorial Updates
================

We've been given access to the page at https://us.pycon.org/2013/community/tutorials/16/
to provide updates on tutorial status.   We're hoping to be around at least for the
Wednesday 6:30 setup session.

Preparing for the Tutorial
==========================

Prior to the class, all students should:

* Download this package.   It is available using git as follows::

    git clone https://bitbucket.org/zzzeek/pycon2013_student_package.git

  Loading the package via git is preferred, so that on the day of the
  tutorial students can update the package in-place with the latest
  updates.  For those students not yet familiar with git, it is
  also available as a .zip file from this link via
  https://bitbucket.org/zzzeek/pycon2013_student_package/get/master.zip.

* Read through the handout.   It is included as a PDF file ``handout.pdf``
  as well as an HTML document viewable at ``handout/index.html``.
  The handout includes a "Relational Review" section which discusses
  the basics of SQL, relational algebra, and transactions; the course
  will assume a basic understanding of this material.

* Install and test the software environment.  Full instructions are
  available in the handout in the "Package Setup" chapter.
  As detailed in that section, students should first install
  `virtualenv <http://pypi.python.org/pypi/virtualenv>`_, then
  create a virtual environment, then install the local software
  packages using ``.venv/bin/python install.py``.


Schedule
========

Course Time: Thursday, March 14, 1:20 PM - 4:40 PM

Location: Great America Floor 2B R3

============  ==================================
 Time             Topic
============  ==================================
1:20 - 1:30   Welcome / Setup
1:30 - 1:40   Prerequisite Material Review
1:40 - 1:45   Overview of SQLAlchemy
1:45 - 2:00   Engine, Connection, Transactions
2:00 - 2:20   Table Metadata, Reflection, DDL
2:20 - 2:50   SQL Expressions
2:50 - 3:10   break
3:10 - 4:40   ORM
============  ==================================


