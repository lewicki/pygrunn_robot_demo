Initial viewport
----------------

Below we can see the screenshot taken from current pyGrunn.org site.

.. figure:: _screenshots/homepage.png
.. code:: robotframework

   Site homepage viewport
      Go to  ${BASE_URL}
      Capture viewport screenshot  _screenshots/homepage.png
