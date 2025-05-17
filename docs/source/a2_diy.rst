DIY
===========

.. admonition:: Info

  After completing the lab, the player does **DIY**

1. Select **DIY** to make.

.. image:: pictures/imagec1.png
   :align: center
   :width: 7000px

2. In the **Plan** interface.

- Read **DIY ACTIVITIES**
- Read **SOLUTION VALIDATION METHOD**
- Select **Open AWS Console**

.. image:: pictures/imagec2.png
   :align: center
   :width: 7000px


3. In **AWS Console**, find and select **EC2**.

.. image:: pictures/imagec3.png
   :align: center
   :width: 7000px

4. Select **Launch instance**.

.. image:: pictures/imagec4.png
   :align: center
   :width: 7000px

5. In **Choose an Amazon Machine Image (AMI)**.

- Select **Amazon Linux 2 AMI (HVM) - Kernel 5.10, SSD Volume Type**
- Select **Select**

.. image:: pictures/imagec5.png
   :align: center
   :width: 7000px


6. In **Choose an Instance Type**.

- Select **t2.micro**
- Then select **Next: Configure Instance Details**

.. image:: pictures/imagec6.png
   :align: center
   :width: 7000px


7. In **Configure Instance Details**.

- Select **VPC**
- Choose **Subnet different from the subnet of Practice**

.. image:: pictures/imagec7.png
   :align: center
   :width: 7000px


8. In **Advanced Details**.

- Select **As file**
- Select **Select file** and download the file **user-data**
- Select **Next: Add Storage**

.. image:: pictures/imagec8.png
   :align: center
   :width: 7000px


9. In **Add Storage**, select **Next: Add Tags**.

.. image:: pictures/imagec9.png
   :align: center
   :width: 7000px

10. In **Add Tags**, select **Next: Configure Security Group**.

.. image:: pictures/imagec10.png
   :align: center
   :width: 7000px

11. In **Configure Security Group**, create a security group.

- **Security group name**, enter ``Security-Group-Lab-2``
- **Description**, enter ``HTTP Group Lab 2``
- **Rule**, select **HTTP**
- Select **Review and Launch**

.. image:: pictures/imagec11.png
   :align: center
   :width: 7000px


12. In **Review Instance Launch**, double check and select **Launch**.

.. image:: pictures/imagec12.png
   :align: center
   :width: 7000px

13. In **Select an existing key pair or create a new key pair**.

- Select **Proceed without a key pair**
- Select **I acknowledge…**
- Select **Launch Instances**

.. image:: pictures/imagec13.png
   :align: center
   :width: 7000px


14. Select **View Instances**.

.. image:: pictures/imagec14.png
   :align: center
   :width: 7000px

15. Result of creating 2 **Amazon EC2 Instance**.

.. image:: pictures/imagec15.png
   :align: center
   :width: 7000px

16. After creating 2 **Amazon EC2 Instance**, copy both **Instance ID**.

- Paste in **Instance ID in AZ1**
- Paste in **Instance ID in AZ2**
- Select **VALIDATE**

.. image:: pictures/imagec16.png
   :align: center
   :width: 7000px


17. After selecting **VALIDATE**, if **VALIDATION MESSAGE** contains **Success!** … is complete.

.. image:: pictures/imagec17.png
   :align: center
   :width: 7000px

18. Select **EXIT**.

.. image:: pictures/imagec18.png
   :align: center
   :width: 7000px

19. In **ASSIGNMENT** select **COLLECT**.
  
.. image:: pictures/imagec19.png
   :align: center
   :width: 7000px

20. Select **NEXT**.

.. image:: pictures/imagec20.png
   :align: center
   :width: 7000px

21. Select **COLLECT**.

.. image:: pictures/imagec21.png
   :align: center
   :width: 7000px

22. Get **rewarded**.

.. image:: pictures/imagec22.png
   :align: center
   :width: 7000px










