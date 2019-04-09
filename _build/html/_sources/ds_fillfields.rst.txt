Setting up Scrutinizer Datasource
===================================

Fill out the required fields. 

.. image:: images/fillFields.png

You can generate an authentication token within Scrutinizer by heading to the Admin Tab - > Security - > Authentication Token 

.. image:: images/createAuth.png

If you are getting an error, one common problem can be your https certificate in Scrutinizer is selfsigned. 

.. image:: images/notSecure.png

If this is the case make sure you check off the ability to skip tls verify. 

.. image:: images/skipVerify.png