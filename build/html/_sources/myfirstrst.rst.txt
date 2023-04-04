Management Interface
=====================

Object Policy
-------------

**Object policies** are used to determine how to manage objects that go to TS7700 from an external host, such as a DS8000 as part of transparent cloud tiering (TCT).
TS7700 currently allows the capability to set up copy policies for object redundancy across a TS7700 grid.

.. image:: /Images/pic.jpg

To create object policy, complete the following steps:

1. Click **Create Object Policy**.

2. In the **Policy Information** tab, provide the following policy information:

   * Name of the policy in the **Policy Name** field.
   * Description of the policy in the **Description** field.

Object Store
------------
To use DS8000 transparent cloud tiering (TCT), you must create a z/OS DFSMS Cloud Network Connection Construct name (cloud name) in the ISMF cloud panel. A cloud name must be created on TS7700 before DS8000 configuration and zHost transactions for that cloud name. If the cloud name does not exist on TS7700, the DS8000 configuration process or host TCT transactions would fail.

