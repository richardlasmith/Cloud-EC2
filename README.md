<p align="center">
<img src="https://i.imgur.com/uvRMTfL.png" alt="Amazon EC2 Instance"/>
</p>

<h1>Create and Launch a Amazon EC2 Instance</h1>
This tutorial outlines the creation and launching of an Amazon EC2 instance.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Amazon Cloud Quest Lab Account
- Desktop Computer 


<h2>Operating Systems Used </h2>

- Amazon Web Services</b> 

<h2>Create and Launching Configuration Objectives</h2>

- Create an Amazon EC2 Instance 
- Configure a user data script to display the instance details.
- Launch a second Amazon EC2 instance in a different Availability Zone.


<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/dC9FYDu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
On the search bar, Type EC2 
</p>
<br />
At the EC2 Dashboard, Launch Instance. 
<p>
<img src="https://i.imgur.com/42EXpnY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

</p>
<br />

<p>
<img src="https://i.imgur.com/hknoErQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Name the EC2 Instance (Webserver01), under application, and OS images (AMI). Click on Amazon Linux, then scroll down.
</p>
<br />

<p>
<img src="https://i.imgur.com/KPObPZo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
On the drop-down arrow, select Amazon Linux 2AMI (HVM)- Kernel 5.10, SSD Volume Type - Free tier eligible, on Instance Type select t2.micro, Then on Key pair (Login), use proceed without a key pair (Not recommended). Scroll Down
</p>
<br />

<p>
<img src="https://i.imgur.com/PdGDTnH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Under Network settings, use the (Lab) VPC and subnet Availability Zone 1a. Then, for Firewall (Security groups), click Create Security Group.
</p>
<br />

<p>
<img src="https://i.imgur.com/5AH7Uvw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Change the security group name to (Security-Group-Lab), in the description section type (HTTP Security Group), change the rule to HTTP, then click Advanced network config.
</p>
<br />

<p>
<img src="https://i.imgur.com/tkPNhwF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Under the advanced network config section, scroll down and paste the downloaded code into the user data box.
</p>
<br />

<p>
<img src="https://i.imgur.com/Akqd2x2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Paste the code.
</p>
<br />

<p>
<img src="https://i.imgur.com/vmku2ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Review the EC2 instance before launching.
</p>
<br />

<p>
<img src="https://i.imgur.com/mPvX1xq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
You should get a successful launch if all information was correctly entered.
</p>
<br />

<p>
<img src="https://i.imgur.com/EKE4fYN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now the EC2 instance is running, you can copy the public IPv4 address for testing.
</p>
<br />

<p>
<img src="https://i.imgur.com/9bsy7Fi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Congrats on creating and launching the Amazon EC2 Instance!.
</p>
<br />
