---

layout: page
title: Install on Windows
permalink: /instalOnWindows/
---

<article>
    <div> 
        <h3> Preparing Windows 10 for ubuntu</h3>
        <p>The simplest way is to take advantage of the free available ubuntu distribution on Windows 10. (An alternate solution is to install directly in Windows a C++ compiler and MPI library). </p>
        <p>In the control panel or in the Microsoft Store, search for ubuntu.</p> 
        <img src="{{ "/assets/images/W10_microsoftStore.jpg" | prepend: site.baseurl }}"  alt="">
        <p>You can chose a specific Ubuntu distribution (e.g.: 18.04 LTS) while Ubuntu App select the last available distro. Before downloading the App, read the system requirements.      <img src="{{ "/assets/images/W10_checkAppRequirements.jpg" | prepend: site.baseurl }}"  alt=""></p>
        <p>Check the system requirements. For Ubuntu 18.04 release: Windows 10 version 1615.0 or higher, x64 architecture. (To find the OS version, open the <em class="surligne">Setting>System>About</em> panel: </p>
        <img src="{{ "/assets/images/W10_SystemRequirements.jpg" | prepend: site.baseurl }}"  alt="">
        <p>In the <em class="surligne">Settings>Update & Security>For developpers</em> panel enable <em class="surligne">Developer mode</em>  </p>
        <img src="{{ "/assets/images/W10_DevelopperMode.jpg" | prepend: site.baseurl }}"  alt="">
        <p>In the control panel, type and chose<em class="surligne">Turn Windows features on or off</em>. Tick the box <em class="surligne">Windows System for Linux</em></p>
        <img src="{{ "/assets/images/W10_WindowsSubSystem4Linux.jpg" | prepend: site.baseurl }}"  style="width:75%;" alt="">
        <h3> Install ubuntu</h3>
        <p> From the Microsoft store click on the <em  class="surligne">Install</em> button of the Ubuntu App. Before using this app, restart the system. <br>  
        Then, in the <em class="surligne">start</em> menu, click on the Ubuntu on windows 10 button to open a terminal. </p>
        <img src="{{ "/assets/images/W10_Ubuntu_button.jpg" | prepend: site.baseurl }}"  style="width:50%;" alt="">
        <p>For the first time, an username and and a password may be required.<br>
        <img src="{{ "/assets/images/ubuntu_term.jpg" | prepend: site.baseurl }}"  alt=""> </p>
        <p>ECOGEN environment can be now completed in the companion section  <a href="{{ "/prerequisitesUbuntu" | prepend: site.baseurl }}">Ubuntu prerequisities</a>.</p>
    </div>
</article>

