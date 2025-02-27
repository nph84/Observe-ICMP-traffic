
<p align="center">
<img src="https://github.com/user-attachments/assets/9f7aa60e-9932-448e-9873-0d06600b8f8a" height="250" width="350"
</p>

<h1>Observe ICMP traffic</h1>
This tutorial outlines the steps to observe ICMP traffic.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Wireshark
- PowerShell
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)


<h2>Installation Steps</h2>

<p>
<img src="https://github.com/user-attachments/assets/a9c3a6e6-3c12-4542-9d0a-797f814db6bb" height="200%" width="200%"
  </p>
<p>  
<img src="https://github.com/user-attachments/assets/e7b132e6-7482-4f6c-b2bb-7e1fef70928c" height="50%" width="50%"
</p>
<p>Find Windows 10 public IP and connect to Windows 10 VM using remote desktop</p>
<br />


<p>  
<img src="https://github.com/user-attachments/assets/62f8cbd7-5160-4b98-8309-74d4b07b4cd7" 
</p>
<p>Install WireShark from within Windows 10 VM</p>
<br />


<p>  
<img src="https://github.com/user-attachments/assets/693ade1b-70c3-4508-a759-628400d668a5" 
</p>
<p>Retrieve the private IP address of the Ubuntu VM</p>
<br />



<p>  
<img src="https://github.com/user-attachments/assets/5a022431-a06a-4e58-b538-0ff3cf90f01c" </p>
<p>Open Wireshark and filter for icmp traffic only and ping from within Windows 10 VM</p>
<br />


<p>  
<img src="https://github.com/user-attachments/assets/c2aa1ef8-b1a8-4d07-9630-30c774d93020" </p>
<p>Initiate a non-stop ping from Windows 10 VM to Ubuntu VM</p>
<br />


<p>  
<img src="https://github.com/user-attachments/assets/d5ce1f08-e03a-49a9-8600-ece342d80c4c" </p>
<p>Open network security group on Ubuntu VM and disable incoming ICMP traffic</p>
<br />


<p>  
<img src="https://github.com/user-attachments/assets/404bd6f6-fa38-4e39-b5f8-1c4c8a9d0cff" </p>
<p>Observe halted ping traffic</p>
<br />































