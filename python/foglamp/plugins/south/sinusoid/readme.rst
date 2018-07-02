***********************
FogLAMP South Sinusoid
***********************

This directory contains a South plugin that implements sine wave with data points.
It generates one data point each second. Over the course of 60 seconds, it returns the following values, one after the another.
The 61st data point begins again at the beginning.

**Example**

.. code-block:: console

   data_points=[
	0.0,
	0.104528463,
	0.207911691,
	0.309016994,
	0.406736643,
	0.5,
	0.587785252,
	0.669130606,
	0.743144825,
	0.809016994,
	0.866025404,
	0.913545458,
	0.951056516,
	0.978147601,
	0.994521895,
	1.0,
	0.994521895,
	0.978147601,
	0.951056516,
	0.913545458,
	0.866025404,
	0.809016994,
	0.743144825,
	0.669130606,
	0.587785252,
	0.5,
	0.406736643,
	0.309016994,
	0.207911691,
	0.104528463,
	1.22515E-16,
	-0.104528463,
	-0.207911691,
	-0.309016994,
	-0.406736643,
	-0.5,
	-0.587785252,
	-0.669130606,
	-0.743144825,
	-0.809016994,
	-0.866025404,
	-0.913545458,
	-0.951056516,
	-0.978147601,
	-0.994521895,
	-1.0,
	-0.994521895,
	-0.978147601,
	-0.951056516,
	-0.913545458,
	-0.866025404,
	-0.809016994,
	-0.743144825,
	-0.669130606,
	-0.587785252,
	-0.5,
	-0.406736643,
	-0.309016994,
	-0.207911691,
	-0.104528463
	]



**Known issues:**

- For now this debian works with default configuration, it does not work if the Admin API config gets:

      1. host, port, https scheme changes

      2. authentication as mandatory

      3. authentication as mandatory & allowPing as false
