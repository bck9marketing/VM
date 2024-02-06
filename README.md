<p align="center">
<img src="https://i.imgur.com/sarJhrf.png" alt="osTicket logo"/>
</p>

<h1>Microsoft Azure Virtual Machine- Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of virtual machines through Microsoft Azure<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To create a Virtual Machine with Microsoft Azure](https://www.youtube.com/watch?v=fr6GFM0ARFg)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Microsoft Account
- Windows 10 ( What I use in this tutorial)

<h2>Installation Steps</h2>

<p>
<img src="https://github.com/bck9marketing/VM/assets/159003800/d38dbf29-c4df-4758-88c4-2013b5d51242" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
We're going to start off by going to azure.microsoft.com/en-us/free and clicking "Start free".
</p>
<br />

<p>
<img src="https://github.com/bck9marketing/VM/assets/159003800/78c3d35c-5fc2-46e6-8ac3-0350156e1d79" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
On this screen we're going to put in our info and attach our credit/debit card when prompted. For new users, you will receive a free $200 in credit for 30 days. This will more than suffice for our tutorial.
</p>
<br />

<p>
<img src="https://github.com/bck9marketing/VM/assets/159003800/886af1ec-ec84-4e31-83c0-4c3e56cb0253" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
At the top search bar type in "vm" and click on the Virtual machines tab that will populate below.
</p>
<br />

<p>
<img src="https://github.com/bck9marketing/VM/assets/159003800/849e493e-0d7d-4dfc-b4a8-92d0a1f1e227" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once that takes to the next page, click the blue button towards the bottom that says "Create" and then click "Azure virtual machine"
</p>
<br />

<p>
<img src="https://github.com/bck9marketing/VM/assets/159003800/6e2e1332-cb63-4a27-afa5-e65037dad8d2" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://github.com/bck9marketing/VM/assets/159003800/4720df13-afb3-4481-98af-2cf5d3cb5de6" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now we can configure our virtual machine.<br>
  - For "Resource group" we'll click "Create new" and name it RG-Test.<br>
  - For "Virtual machine" we'll name it VM-1<br>
  - For "Image" we're going to be using "Windows 10 Pro, version 22H2"<br>
  - For "Size" will depend on the options available, for now we'll do Standard_B4ms 4vcpus, 16 GiB memory<br>
  - For "Username" we'll use "testaccount" and for "Password" we'll use "Testpassword1" for the sake of this tutorial.<br>
  - Check the box under "Licensing"<br>
  - Everything else you can leave as is, just take note of your "Region" and always try to use the same one within groups<br>
Finally click the blue "Review + create" button.
</p>
<br />

<p>
<img src="https://github.com/bck9marketing/VM/assets/159003800/402fa1ae-2f22-42cc-b9fd-26201b12a5ac" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Might take a few seconds but once you notice a green "Validation passed" box up top, simply click the blue "Create" button at the bottom again.
</p>
<br />

<p>
<img src="https://github.com/bck9marketing/VM/assets/159003800/e5630431-21a5-4466-a753-00cce142679d" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Again, on this screen simply be patient and wait until you see "Your deployment is complete" at the top. This will take a few minutes as the virtual machine is created. Once thats done, click the blue "Go to resource" button.
</p>
<br />

<p>
<img src="https://github.com/bck9marketing/VM/assets/159003800/bfce174f-f56a-4f15-8578-151512a9eece" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Your virtual machine is now ready to be used! On this screen you will see all sorts of information regarding your vm. All we need now to access it is the "Public IP address" in the top right. Copy this number to clipboard.
</p>
<br />

<p>
<img src="https://github.com/bck9marketing/VM/assets/159003800/de4b6ebe-7ae7-4a21-abe9-4eeb7a608da2" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
With your vm's IP now copied, go to your windows search bar in the buttom left of your screen and type in "Remote Desktop Connection". Click open the App that will populate towards the top.
</p>
<br />

<p>
<img src="https://github.com/bck9marketing/VM/assets/159003800/0264c67f-f6a9-46a8-9cc1-9b28a0c8e3ae" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://github.com/bck9marketing/VM/assets/159003800/a394ea16-7313-4c58-837f-3a5386a11874" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://github.com/bck9marketing/VM/assets/159003800/53c6c298-2592-4a0a-bced-d8c078249132" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once open, go ahead and paste in the previously copied IP address. Click connect.<br>
When prompted insert the credentials we made during the virtual machines creation and click ok.<br>
- User name: testaccount<br>
- Password: Testpassword1<br>
Lastly click yes on the certificate prompt that pops up.
</p>
<br />

<p>
<img src="https://github.com/bck9marketing/VM/assets/159003800/daada320-1453-496c-9181-80d9c85c9006" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Congratulations! You should now be inside your virtual machine.
</p>
<br />
