---
layout: default
permalink: /Projects/
title: Projects
nav: true
nav_order: 5
---

<div style="text-align: center; font-family: 'Glyphicons Halflings';">
  <h1 style="font-size: 3rem; color: red; margin-bottom: 10px;">Projects</h1>
  <p style="font-size: 1.2rem; color: white;">
A curated list of projects I’ve worked on that have helped me build a solid foundation for learning advanced topics  </p>
</div>

<hr style="border: 0; border-top: 2px solid #ccc; margin: 20px 20px;">

<div style="font-family: 'Glyphicons Halflings'; color: #333;">
  <!-- Project 1 -->
  <div style="margin-bottom: 20px; border: 1px solid #ccc; padding: 15px; border-radius: 5px;">
    <h2 style="color: red;">TCP-IP Stack</h2>
    <p>
      A TCP-IP stack written in C that emulates a multi-node topology of routers and switches. This project implements core networking functionalities across the DataLink (L2) and Network (L3) layers, offering a foundational understanding of networking protocols and architecture.
    </p>
    <ul style="margin: 10px 0; padding-left: 20px;">
      <li>Multi-Node Topology Emulation: Simulates interconnected routers and switches for complex network configurations.</li>
      <li>L2 Routing: Implements key DataLink layer protocols, including ARP for IP-to-MAC address mapping.</li>
      <li>L2 Switching: Features MAC-based learning and forwarding for efficient packet delivery.</li>
      <li>VLAN Support: Enables VLAN-based segmentation and forwarding in the DataLink layer.</li>
      <li>L3 Routing: Provides IP packet routing capabilities across multiple networks.</li>
    </ul>
    <p style="color: grey;">Tech Stack: C</p>
    <p><a href="https://github.com/adityjoshi/tcp-ip-stack" style="color: blue; text-decoration: none;">GitHub Link</a></p>
  </div>

  <!-- Project 2 -->
  <div style="margin-bottom: 20px; border: 1px solid #ccc; padding: 15px; border-radius: 5px;">
    <h2 style="color: red;">TCP Server & Reverse Proxy Client</h2>
    <p>
      A project showcasing a TCP server with a reverse proxy, designed to manage multiple concurrent connections and route client traffic efficiently.
    </p>
    <ul style="margin: 10px 0; padding-left: 20px;">
      <li>Handles multiple simultaneous client connections.</li>
      <li>Implements reverse proxy for efficient routing.</li>
      <li>Uses Go's goroutines for concurrency management.</li>
      <li>Supports real-time communication between clients and servers.</li>
    </ul>
    <p style="color: grey;">Tech Stack: Golang</p>
    <p><a href="https://github.com/adityjoshi/tcp" style="color: blue; text-decoration: none;">GitHub Link</a></p>
  </div>

  <!-- Project 3 -->
  <div style="margin-bottom: 20px; border: 1px solid #ccc; padding: 15px; border-radius: 5px;">
    <h2 style="color: red;">Swaasthya</h2>
    <p>
      Swaasthya is a healthcare management platform designed to enhance hospital efficiency by managing patient flow, real-time bed tracking, inventory updates, and secure authentication. Built on a scalable microservices architecture, it aims to streamline healthcare operations with future expansions for data streaming and analytics.
    </p>
    <ul style="margin: 10px 0; padding-left: 20px;">
      <li>Patient Flow Management: Optimizes appointment scheduling and reduces wait times.</li>
      <li>Real-Time Bed Tracking: Tracks bed availability across departments in real-time.</li>
      <li>Inventory Management: Monitors and updates hospital inventory levels effectively.</li>
      <li>Emergency Dashboard: Provides real-time insights into patient loads and resource allocation.</li>
      <li>2-Factor Authentication: Ensures secure logins with OTP verification.</li>
      <li>Real-Time Notifications: Alerts for critical events, appointments, and bed availability.</li>
      <li>Offline Functionality: Operates seamlessly in low-bandwidth environments.</li>
    </ul>
    <p style="color: grey;">Tech Stack: Golang, Kafka, Redis, PostgreSQL</p>
    <p><a href="https://github.com/adityjoshi/swaasthya" style="color: blue; text-decoration: none;">GitHub Link</a></p>
  </div>

  <!-- Project 4 -->
  <div style="margin-bottom: 20px; border: 1px solid #ccc; padding: 15px; border-radius: 5px;">
    <h2 style="color: red;">Hostel Grievance Redressal</h2>
    <p>
      A Hostel Grievance Redressal System built with Go and PostgreSQL, designed to streamline the process of lodging and addressing complaints in a hostel environment. The system enhances accountability and transparency while ensuring user security through 2FA authentication.
    </p>
    <ul style="margin: 10px 0; padding-left: 20px;">
      <li>Secure Authentication: Implements Two-Factor Authentication (2FA) for enhanced user security.</li>
      <li>Grievance Management: Streamlines the lodging, tracking, and resolution of hostel complaints.</li>
      <li>Go-Powered Backend: High-performance backend built with the simplicity and efficiency of Golang.</li>
      <li>PostgreSQL Integration: Reliable and scalable database for managing user and complaint data.</li>
      <li>Modular and Configurable: Flexible architecture with <code>.env</code> support for environment-specific settings.</li>
    </ul>
    <p style="color: grey;">Tech Stack: Golang, PostgreSQL</p>
    <p><a href="https://github.com/adityjoshi/GoCo" style="color: blue; text-decoration: none;">GitHub Link</a></p>
  </div>

  <!-- Project 5 -->
  <div style="margin-bottom: 20px; border: 1px solid #ccc; padding: 15px; border-radius: 5px;">
    <h2 style="color: red;">A Simple Load Balancer in Golang</h2>
    <p>
      A lightweight load balancer implemented in Go that distributes requests across multiple servers using the round-robin algorithm.
    </p>
    <p style="color: grey;">Tech Stack: Golang</p>
    <p><a href="https://github.com/adityjoshi/GoLB" style="color: blue; text-decoration: none;">GitHub Link</a></p>
  </div>
</div>
<div style="margin-bottom: 20px; border: 1px solid #ccc; padding: 15px; border-radius: 5px;">
  <h2 style="color: red;">GoCo</h2>
  <p>
    A lightweight and efficient bencoding parser implemented in Golang. Bencoding is a simple data serialization format used primarily in BitTorrent applications but can be useful in other contexts as well. This parser allows you to decode bencoded data into native Go data structures for easy manipulation and processing.
  </p>
  <ul style="margin: 10px 0; padding-left: 20px; color: #333;">
    <li>GoCo is designed for speed and efficiency, making it suitable for parsing large bencoded data sets quickly.</li>
    <li>With a straightforward API, GoCo makes it easy to decode bencoded data with just a few lines of code.</li>
    <li>Decoded data is represented using native Go data types, making it easy to work with in your Go applications.</li>
    <li>GoCo provides comprehensive error handling, ensuring robustness in parsing various types of bencoded data.</li>
  </ul>
  <p style="color: grey;">Tech Stack: Golang</p>
  <p>
    <a href="https://github.com/adityjoshi/GoCo" style="color: blue; text-decoration: none;">GitHub Link</a>
  </p>
</div>

