
<h1>Setting up and hosting a website using Apache</h1>


<h2>Description</h2>
Project consists of a utilizing Vagrant and git bash to setup and host a website in a vm using Apache.


<br />


<h2>Languages and Utilities Used</h2>

- <b>Git Bash</b> 
- <b>Oracle VM Virtualbox 6.1 </b>
- <b>Vagrant boxes</b>
- <b>https://app.vagrantup.com/boxes/search</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)
- <b>Ubuntu 18 server
- <b>CentOS7

<h2>Program walk-through:</h2>

<p align="left">
- VM started using Vagrant and editing the config using VIM to add the network address and increase ram <br/>


<img width="464" alt="vim editing network" src="https://user-images.githubusercontent.com/85902399/204062068-df66db2f-0aba-44d4-8ec3-1308c6e40da1.png">


<br />
<br />
Installing the httpd service  <br/>
  
<img width="943" alt="installing httpd" src="https://user-images.githubusercontent.com/85902399/204062104-947b1d23-80d8-42b0-b287-000a99f9bedd.png">

adding httpd service to startup

<img width="743" alt="systemctl start httpd" src="https://user-images.githubusercontent.com/85902399/204062130-b104d1b5-e48e-40da-b37d-faff541eabd6.png">



<br />
<br />
testing that the website address is working <br/>

<img width="881" alt="test page" src="https://user-images.githubusercontent.com/85902399/204062149-0e2cd58d-1708-4bf1-9674-4df4f7c869c6.png">


<br />
<br />


<br />

Copying website zip file from a free template website and adding to my local vm 

<img width="922" alt="downloading website template into tmp" src="https://user-images.githubusercontent.com/85902399/204062203-4d3b90f0-7bcb-4283-8e0a-3632e993fdec.png">


<br/>
<br/>
<img width="823" alt="unziping website" src="https://user-images.githubusercontent.com/85902399/204062214-8f177944-8ef0-482f-a2d5-0222b4ef2e35.png">


<br />
Vrestarting httpd service and testing that the website is loaded.
  

<img width="924" alt="website template loaded" src="https://user-images.githubusercontent.com/85902399/204062231-aa68da03-b881-4f97-b154-ffc814064e03.png">

 
</p>
