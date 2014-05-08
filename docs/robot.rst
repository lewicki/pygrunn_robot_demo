.. code:: robotframework

   *** Settings ***

   Resource  Selenium2Screenshots/keywords.robot

   *** Variables ***
   
   ${BASE_URL} =  http://pygrunn.org
   ${PAGE_DOWN} =  121

   *** Keywords ***

   Suite Teardown
       Close All Browsers

