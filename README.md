
<p align="center">
<img width="3840" height="2160" alt="image" src="https://github.com/user-attachments/assets/d79b82b7-36a1-4066-9b4e-35f0a8c360ae" />

</p>

<h1> How to Create and Access a Virtual Machine Using Microsoft Azure</h1>
This tutorial will demonstrate how to create and access a virtual machine using Microsoft Azure & Remote Desktop on Windows 11. IT support techs can use these Virtual Machines to test and develop software, scale infrastructure, or automate deployments.  <br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure account (Virtual Machines/Compute)


<h2>Operating Systems Used </h2>

- Windows 11</b> (21H2)


<h2>Installation Steps</h2>

<p>
<img width="1599" height="765" alt="image" src="https://github.com/user-attachments/assets/255c21c2-90a4-4562-b5ab-7aee24bad8b0" />
<p>
1. Log into an Azure account at https://portal.azure.com/. Select "Create" and then click Virtual machine.
</p>
<br />

<p>
<img width="1591" height="757" alt="image" src="https://github.com/user-attachments/assets/c9f9335d-d97c-4465-b945-6d0042b33a87" />
</p>
<p>
2. If you do not have a resource group created, create a new one by selecting the option in the resource group selection box.
 
</p>
<br />

<p>
<img width="1599" height="760" alt="image" src="https://github.com/user-attachments/assets/9ecafb46-7281-4abf-810c-1aa4ea067ba5" />
</p>
<p>
3. Name the Virtual Machine anything.  IMPORTANT: For any Virtual Machines or Resource Group, make sure that they are in the same region. Operations will run more smoothly. 
</p>
<br />

<p>
<img width="1594" height="765" alt="image" src="https://github.com/user-attachments/assets/da66f2e2-40ef-4a6b-a1b5-94a1e0221f78" />
</p>
<p>
4. Under the "Image" box, select "Windows 11 Pro Version 25H2 x64". Under the "Size" box, select 2 vCPUs & 4 GiB Memory minimum.
</p>
<br />

<p>
<img width="1595" height="763" alt="image" src="https://github.com/user-attachments/assets/772c49d0-2d37-4f9b-869d-dfb87c7096c4" />
</p>
<p>
5. The next step is to create login credentials for the Virtual machine so that you may access it via Remote Desktop.
</p>
<br />

<p>
<img width="1597" height="722" alt="image" src="https://github.com/user-attachments/assets/5f751a30-abbf-46c0-9931-3002e2a59d56" />
</p>
<p>
6. If you are asked about licensing, simply click the box to continue and finally select "review+create" to finish the Virtual Machine.
</p>
<br />

<p>
<img width="1598" height="724" alt="image" src="https://github.com/user-attachments/assets/e1ac2963-42e1-4e65-a203-4e2440764dfa" />
</p>
<p>
7. Select Create to finalize the Virtual Machine; this process may take a couple of seconds to a few minutes.
</p>
<br />

<p>
<img width="1599" height="763" alt="image" src="https://github.com/user-attachments/assets/11d8b404-4ffe-4f0b-bc95-e1f401931e0c" />
</p>
<p>
8. Once the Virtual Machine is finished deploying, head back to the Azure home tab. The Virtual Machine should be listed; click on the Virtual Machine that you want to access.
</p>
<br />

<p>
<img width="1597" height="761" alt="image" src="https://github.com/user-attachments/assets/093edefb-d4c3-4a05-b170-813ffe485b4a" />
</p>
<p>
9. Scroll down and look for the Public IP address. Copy the IP address to your clipboard so that you can input it to Remote Desktop later. 
</p>
<br />

<p>
<img width="838" height="780" alt="image" src="https://github.com/user-attachments/assets/5a64ad88-d7d6-43d2-becc-68aa086f1d0a" />
</p>
<p>
10.  Click the Start menu on your computer and search for Remote Desktop. Run Remote Desktop.
</p>
<br />

<p>
<img width="475" height="541" alt="image" src="https://github.com/user-attachments/assets/e2e15bc0-9904-47c2-b46b-b575d348138a" />
</p>
<p>
11. Input the Public IP address and the username for the Virtual Machine you just created. Be sure to expand "Show Options" at the bottom of the window.
You will be prompted to also enter the password for your Virtual Machine.
</p>
<br />

<p>
 <img width="434" height="507" alt="image" src="https://github.com/user-attachments/assets/8a44ef0f-ae80-4520-b87c-4ce293d1fc9b" />
</p>
<p>
12. Click yes to gain control of your Virtual Machine 
</p>
<br />

<p>
<img width="1474" height="829" alt="image" src="https://github.com/user-attachments/assets/18d4ca76-8703-4efc-988f-ae8cbae8aac8" />
<p>
13. Make sure none of these options are selected and click Accept.
</p>
<br />

<p>
 <img width="1597" height="841" alt="image" src="https://github.com/user-attachments/assets/59f9a0c3-2dd2-4d82-a945-bb89c19903ab" />
</p>
<p>
 14. Your virtual Machine is now ready to use.
</p>
<br />
