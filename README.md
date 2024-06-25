<!-- PROJECT SHIELDS -->
&nbsp; &nbsp; &nbsp; &nbsp;
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<div align="center">
  <h3 align="center">Network Simulation</h3>

  <p align="center">
     Subnetting, VLAN, Router Protocol(static routing, OSPF, RIP), DHCP, DNS, FTP etc.
    <br/>
    <a href="https://github.com/Arsany-Osama/Network-Simulation/tree/master"><strong>Explore the docs »</strong></a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
      </ul>
    </li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->

## About The Project
</br>
* Building A (212 Host=> Tree Topology) </br>
 &nbsp; &nbsp; Network IP: 193.158.1.0 </br>
 &nbsp; &nbsp; Fist Valid IP: 193.158.1.1  Saved For The Router </br>
 &nbsp; &nbsp; Last Valid IP: 2N+Net-2 = 28+0-2 = 254 = 193.158.1.254 </br>
 &nbsp; &nbsp; Broadcast IP = 193.158.1.255 </br>
 &nbsp; &nbsp; Subnet Mask: 255.255.255.0 </br>
 
![image](https://github.com/Arsany-Osama/Network-Simulation/assets/160052013/9fcd060e-8996-41cb-82b7-8f1aa1affc70)

</br></br>
* Building B with VLAN(36 Host=> Star Topology) </br>
  &nbsp; &nbsp; VLAN 10 (18 Host) </br>
  &nbsp; &nbsp;&nbsp; &nbsp;  Network IP: 193.158.2.0 </br>
  &nbsp; &nbsp;&nbsp; &nbsp;  Fist Valid IP: 193.158.2.1  Saved For The Gatway </br>
  &nbsp; &nbsp;&nbsp; &nbsp;  Last Valid IP: 2N+Net-2 = 25+0-2 = 30 = 193.158.2.30 </br>
  &nbsp; &nbsp;&nbsp; &nbsp;  Broadcast IP = 193.158.2.31 </br>
  &nbsp; &nbsp;&nbsp; &nbsp;  Subnet Mask: 255.255.255.11100000 = 255.255.255.224 </br>
  &nbsp; &nbsp; VLAN 20 (18 Host) </br>
  &nbsp; &nbsp; Network IP: 193.158.2.32 </br>
  &nbsp; &nbsp; Fist Valid IP: 193.158.2.33  Saved For The Gatway </br>
  &nbsp; &nbsp; Last Valid IP: 2N+Net-2 = 25+32-2 = 62 = 193.158.2.62 </br>
  &nbsp; &nbsp; Broadcast IP = 193.158.2.63 </br>
  &nbsp; &nbsp; Subnet Mask: 255.255.255.11100000 = 255.255.255.224 </br>
![image](https://github.com/Arsany-Osama/Network-Simulation/assets/160052013/453d72a2-7958-466e-8904-da269fefc000)


</br></br>
* Building C (47 Host=> Ring Topology) </br>
  &nbsp; &nbsp;  Network IP: 193.158.2.64 </br>
  &nbsp; &nbsp;  Fist Valid IP: 193.158.2.65  Saved For The Gatway </br>
  &nbsp; &nbsp;  Last Valid IP: 2N+Net-2 = 26+64-2 = 126 = 193.158.2.126 </br>
  &nbsp; &nbsp;   Broadcast IP = 193.158.2.127 </br>
  &nbsp; &nbsp;  Subnet Mask: 255.255.255.11000000 = 255.255.255.192 </br>
  ![image](https://github.com/Arsany-Osama/Network-Simulation/assets/160052013/01c6be5a-470a-4a2a-bed2-3d0de8e8cebf)

</br></br>
* Building D (125 Host=> Bus Topology) </br>
 &nbsp; &nbsp; Network IP: 193.158.2.123 </br>
 &nbsp; &nbsp; Fist Valid IP: 193.158.2.124  Saved For The Gatway </br>
 &nbsp; &nbsp; Last Valid IP: 26+128-2 = 126 = 193.158.2.254 </br>
 &nbsp; &nbsp; Broadcast IP = 193.158.2.255 </br>
 &nbsp; &nbsp; Subnet Mask: 255.255.255.10000000 = 255.255.255.128 </br>
![image](https://github.com/Arsany-Osama/Network-Simulation/assets/160052013/fd999938-15de-456d-af3e-2e31cd948cbc)

</br></br>
* Building E (125 Host=> Mesh Topology) </br>
 &nbsp; &nbsp; Network IP: 193.158.3.0 </br>
 &nbsp; &nbsp; Fist Valid IP: 193.158.3.1  </br>
 &nbsp; &nbsp; Last Valid IP: 2N+Net-2 = 28+0-2 = 254 = 193.158.1.254 </br>
 &nbsp; &nbsp; Broadcast IP = 193.158.1.255 </br>
 &nbsp; &nbsp; Subnet Mask: 255.255.255.0 </br>
![image](https://github.com/Arsany-Osama/Network-Simulation/assets/160052013/92002964-e02a-4ab6-9d07-ec89421b966f)



### Features:
- Server Authentication:
  ![image](https://github.com/Arsany-Osama/Network-Simulation/assets/160052013/b219d701-41cd-404e-8786-1b387230d8d3)
  
- PAT + Static NAT:
  ![image](https://github.com/Arsany-Osama/Network-Simulation/assets/160052013/585c27c4-36f5-4e90-a33f-86303818f1ac)

- DNS + HTTP:
  ![image](https://github.com/Arsany-Osama/Network-Simulation/assets/160052013/aa95bf9f-d08b-4c7c-817c-027ce3cc1e9a)

- DHCP :
  ![image](https://github.com/Arsany-Osama/Network-Simulation/assets/160052013/0bcb88c0-95c6-451c-b9a3-614b5be7230d)

- FTP :
![image](https://github.com/Arsany-Osama/Network-Simulation/assets/160052013/306f87b9-114e-41a8-9d31-988c029fa278)


- Telnet :
  ![image](https://github.com/Arsany-Osama/Network-Simulation/assets/160052013/45ce2a41-2bba-4628-81c4-84ad717566dc)


<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* [Packet Tracer](https://www.netacad.com/courses/packet-tracer) - For network simulation and visualization.


<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Prerequisites

Ensure you have the following software installed:
* Xampp and upload DDL file on it to activate the local server data
* VS Code or any editor

  [contributors-shield]: https://img.shields.io/github/contributors/Arsany-Osama/Network-Simulation.svg?style=for-the-badge
[contributors-url]: https://github.com/Arsany-Osama/Network-Simulation/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Arsany-Osama/Network-Simulation.svg?style=for-the-badge
[forks-url]: https://github.com/Arsany-Osama/Network-Simulation/network/members
[stars-shield]: https://img.shields.io/github/stars/Arsany-Osama/Network-Simulation.svg?style=for-the-badge
[stars-url]: https://github.com/Arsany-Osama/Network-Simulation/stargazers
[issues-shield]: https://img.shields.io/github/issues/Arsany-Osama/Network-Simulation.svg?style=for-the-badge
[issues-url]: https://github.com/Arsany-Osama/Network-Simulation/issues
[license-shield]: https://img.shields.io/github/license/Arsany-Osama/Network-Simulation.svg?style=for-the-badge
[license-url]: https://github.com/Arsany-Osama/Network-Simulation/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/arsany-osama-446942264
