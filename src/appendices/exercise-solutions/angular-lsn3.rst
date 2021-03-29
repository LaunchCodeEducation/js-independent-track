.. _angular-lsn3-exercise-solutions:

Exercise Solutions: Angular, Lesson 3
=====================================

Add Attribute Directives and Template Variables
-----------------------------------------------

Update the HTML
^^^^^^^^^^^^^^^

.. _angular-lsn3-exercise-solutionsA1:

#. Pass in the ``message`` variable to the app html:
   
   ``app.component.html``:

   .. sourcecode:: html+ng2
      :lineno-start: 5

      <p>{{message}}</p>

.. _angular-lsn3-exercise-solutionsA3:

3. Use the ``height`` property to determine the displayed height:

   ``app.component.html``:

   .. sourcecode:: html+ng2
      :lineno-start: 31

      <p>{{height}} km</p>


:ref:`Back to the exercises <exercises-angular-lsn3A>`

Add Events to Modify Directives
-------------------------------

Control Buttons
^^^^^^^^^^^^^^^

.. _angular-lsn3-exercise-solutionsB1:

#. Add an event listener to the *Take Off* button.

   ``app.component.html``:

   .. sourcecode:: html+ng2
      :lineno-start: 38
   
      <button (click) = "handleTakeOff()">Take Off</button>

:ref:`Back to the exercises <exercises-angular-lsn3B>`


Movement Buttons
^^^^^^^^^^^^^^^^
.. _angular-lsn3-exercise-solutionsC1:

#. Label the ``img`` element so we can reference it:

   ``app.component.html``

   .. sourcecode:: html+ng2
      :linenoe-start: 20

      <img #rocketImage src="assets/images/LaunchCode_rocketline_white.png" height = "75" width = "75" [style.left]="0" [style.bottom]="0"/>

:ref:`Back to the exercises <exercises-angular-lsn3C>`
