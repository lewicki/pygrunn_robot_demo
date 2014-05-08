Cropping and annotations
------------------------

Topmenu
.......

Below we may see cropped and annotated page element.

.. figure:: _screenshots/topmenu.png
.. code:: robotframework

   Capture annotated top menu 
      ${note1} =  Add pointy note
      ...    css=.headerbar
      ...    This Robot Framework stuff is very very cool!
      ...    width=200  position=bottom
      Capture and crop page screenshot  _screenshots/topmenu.png
      ...    css=.headerbar  ${note1}
