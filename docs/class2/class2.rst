Class 2: Deployment with auto-scale
===================================

.. note:: On this page there is no actions to be done here regarding the lab itself

In this class, we will review the auto-scale feature available with BIG-IQ 6.0
called ``Service Scaling Groups`` (SSG)

Below Virtual Servers and Pool Members can be used in the context of the  (`UDF lab`_) for this class.

.. _UDF lab: https://udf.f5.com/d/cf3810ee-4e02-4fd1-a0ec-747ee424920a#components

.. warning:: After starting the blueprint in UDF, connect to the BIG-IP Cluster BOS-vBIGIP01.termmarc.com and BOS-vBIGIP02.termmarc.com, make sure the cluster shows **In Sync**.

- **vLab Test Web Site 26:**

=======================================  =========== ==== ============================
Test Website                             VIP         Port Members
=======================================  =========== ==== ============================
site26.example.com                       10.1.10.126 80   10.1.20.126 and 10.1.20.127
site26.example.com                       10.1.10.126 443  10.1.20.126 and 10.1.20.127
site26.example.com                       10.1.10.126 8081 10.1.20.126 and 10.1.20.127
=======================================  =========== ==== ============================

- **vLab Test Web Site 28:**

=======================================  =========== ==== ============================
Test Website                             VIP         Port Members
=======================================  =========== ==== ============================
site28.example.com                       10.1.10.128 80   10.1.20.128 and 10.1.20.129
site28.example.com                       10.1.10.128 443  10.1.20.128 and 10.1.20.129
site28.example.com                       10.1.10.128 8081 10.1.20.128 and 10.1.20.129
=======================================  =========== ==== ============================

- **vLab Test Web Site 30:**

==========================  =========== ==== ============================
Test Website                VIP         Port Members
==========================  =========== ==== ============================
site30.example.com          10.1.10.130 80   10.1.20.130 and 10.1.20.131
site30.example.com          10.1.10.130 443  10.1.20.130 and 10.1.20.131
site30.example.com          10.1.10.130 8081 10.1.20.130 and 10.1.20.131
==========================  =========== ==== ============================

- **Hackazon Test Web Site 32:**

=======================================  =========== ==== ============================
Test Website                             VIP         Port Members
=======================================  =========== ==== ============================
site42.example.com                       10.1.10.132 80   10.1.20.132
=======================================  =========== ==== ============================

.. toctree::
   :maxdepth: 1
   :glob:

   intro
   module*/module*
