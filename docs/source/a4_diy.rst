DIY
=======

.. admonition:: Info

 After completing the lab, the player does DIY

1. Select DIY.

.. image:: pictures/a456.png
   :align: center
   :width: 7000px
  
2. The DIY interface appears including:

- Lab Files
- DIY Activity
- Networking Concepts
- VALIDATION FORM
- Read SOLUTION VALIDATION METHOD

.. image:: pictures/a457.png
   :align: center
   :width: 7000px

3. In the AWS Console page, find and select EC2.

.. image:: pictures/a458.png
   :align: center
   :width: 7000px
  
4. Select Instances.

- Select Security
- In Security groups, select DbServerSecurityGroup

.. image:: pictures/a459.png
   :align: center
   :width: 7000px

5. In the Security Groups interface.

- Select Edit inbound rules


.. image:: pictures/a460.png
   :align: center
   :width: 7000px

  
6. In the Edit inbound rules interface.

- Type: select MYSQL/Aurora
- Protocol: select TCP
- Prot range: enter ``3306``
- Source: choose Custom
- Then select Save rules

.. image:: pictures/a461.png
   :align: center
   :width: 7000px

7. Interface after creating DbServerSecurityGroup.

.. image:: pictures/a462.png
   :align: center
   :width: 7000px
  
8. In the Security groups view, copy Security group name.


.. image:: pictures/a463.png
   :align: center
   :width: 7000px

  
9. After copying Security group name.

- Paste Security group name into VALIDATION FORM in Database Security Group name field

- Then select VALIDATE

.. image:: pictures/a464.png
   :align: center
   :width: 7000px

10. Results.
  
- On VALIDATION MESSAGE, appears Nice!You have properly configured your security! and done DIY
- Select EXIT to exit

.. image:: pictures/a465.png
   :align: center
   :width: 7000px

11. Select NEXT.

.. image:: pictures/a466.png
   :align: center
   :width: 7000px

12. Select COLLECT.

.. image:: pictures/a467.png
   :align: center
   :width: 7000px


13. Congratulations on completing lab 7.

.. image:: pictures/a468.png
   :align: center
   :width: 7000px


