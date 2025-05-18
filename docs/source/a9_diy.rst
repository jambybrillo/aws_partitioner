DIY
========

.. admonition:: Info

 After completing the lab, the player does DIY


1. In the AWS Console interface

- Find EC2
- Select EC2


.. image:: pictures/0001-diy9.png
   :align: center
   :width: 7000px


2. In the EC2 interface

- Select Instances
- View the instance


.. image:: pictures/0002-diy9.png
   :align: center
   :width: 7000px


3. In EC2 interface

- Select Security Groups
- View Security Groups
- Select Create security group


.. image:: pictures/0003-diy9.png
   :align: center
   :width: 7000px


4. In the Create security group interface

- Security group name, enter PetModels-EFS-1-SG
- Description, enter Restric access to webservers only
- Select PetModels VPC


.. image:: pictures/0004-diy9.png
   :align: center
   :width: 7000px


5. In the Create security group interface

- Select Add rule
- In Inbound rules, select NFS
- Select webserver Security group


.. image:: pictures/0005-diy9.png
   :align: center
   :width: 7000px


6. In the Create security group interface

- Select Create security group


.. image:: pictures/0006-diy9.png
   :align: center
   :width: 7000px


7. In the Security groups interface

- View Security group name
- View the Inbound rules


.. image:: pictures/0007-diy9.png
   :align: center
   :width: 7000px


8. In the AWS Console interface

- Find EFS
- Select EFS


.. image:: pictures/0008-diy9.png
   :align: center
   :width: 7000px


9. In the EFS interface

- Select Create file system


.. image:: pictures/0009-diy9.png
   :align: center
   :width: 7000px


10. In the Create file system interface

- Name, enter PetModels-EFS-1
- VPC, select PetModels
- Select Regional
- Select Customize


.. image:: pictures/00010-diy9.png
   :align: center
   :width: 7000px


11. In the File Systems interface

- In Automatic backups, uncheck Enable automatic backups
- In Transition into A, select None


.. image:: pictures/00011-diy9.png
   :align: center
   :width: 7000px


12. In the File systems interface

- Select Next


.. image:: pictures/00012-diy9.png
   :align: center
   :width: 7000px


13. In the Network access interface

- Uncheck security group of us-east-1a
- Select Remove the remaining AZs


.. image:: pictures/00013-diy9.png
   :align: center
   :width: 7000px


14. In the Network access interface

- Select us-east-1a
- select Subnet ID
- Select Security group
- Select Next


.. image:: pictures/00014-diy9.png
   :align: center
   :width: 7000px


15. In the File system policy interface

- Select Next


.. image:: pictures/00015-diy9.png
   :align: center
   :width: 7000px


16. In the Create file system interface

- Select Create


.. image:: pictures/00016-diy9.png
   :align: center
   :width: 7000px


17. In the File System interface

- See the successful file system initialization
- Select PetModels-EFS-1


.. image:: pictures/00017-diy9.png
   :align: center
   :width: 7000px


18. In the PetModels-EFS-1 interface

- Select Attach


.. image:: pictures/00018-diy9.png
   :align: center
   :width: 7000px


19. In the Attach interface

- Copy EFS mount helper
- Select Close


.. image:: pictures/00019-diy9.png
   :align: center
   :width: 7000px


20. In the AWS Console interface

- Find EC2
- Select EC2


.. image:: pictures/00020-diy9.png
   :align: center
   :width: 7000px































