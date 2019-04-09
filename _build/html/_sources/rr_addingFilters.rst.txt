Adding Filters
===================

Scrutinizer offers an extremly powerful filtering engine which can also be leveraged by this Datasource. The easiest way to pass filters to the datasource is to first build them within Scrutinizer to get a feel for the format. 

For example if I wanted to see what JSON would be needed to pass a filter for host 10.60.1.240 and application TCP 443 I could build the filters in Scrutinizer and then look at the restAPI JSON. 

.. image:: images/addFilters.png
    :scale: 100%
From there copy from the opening bracket to the closing bracket and paste that filter within Grafana. And select Apply Filter.


.. image:: images/addfiltersGrafana.png
    :scale: 100%

Keep in mind the "sdfDips_0" will be igored. This references the device in Scrutinizer you were looking at when you built the filters. You can leave it in if it's easier to paste that way, or you can remove it. Both will yield the same result. 

.. image:: images/addfiltersnoDevice.png
    :scale: 100%