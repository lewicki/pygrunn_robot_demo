Tablet (768x)
=======================

.. code:: robotframework

    *** Settings ***

    Resource  ../robot.rst
    Suite Setup  Suite Setup
    Suite Teardown  Suite Teardown
    
    *** Keywords ***

    Suite Setup
        Open Browser  ${BASE_URL}
        Set window size  768  900

    *** Test Cases ***

.. include:: ../_frontpage.rst
.. include:: ../_topmenu.rst
