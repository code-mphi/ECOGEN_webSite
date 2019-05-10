---

layout: page
title: Start
permalink: /start/
---

<article>
	<h2> Installation guide </h2>
	<div> 
		<h3> Prerequisites</h3>
		<p>ECOGEN must be compiled with <b>C++</b>. It also requires a functional system implementation of <b>MPI library</b> (not provided in this package). Depending on your operating system, click on the corresponding link below to obtain additional informations: 
		</p>
		<p>Installing prerequisites for <a href="/prerequisitesUbuntu"> Ubuntu system / Windows 10 using bash</a> (<em>Ubuntu on Windows App</em>) </p>
		<p>Installing prerequisites for  <a href="/instalOnWindows"> Windows system </a></p>
	</div>	
	<div> 
		<h3> Download ECOGEN</h3>
		<p>The last ECOGEN version can be downloaded from Git-hub. The source files are available at the following address: 
        <a href="https://github.com/code-mphi/ECOGEN" target="_blank" >https://github.com/code-mphi/ECOGEN</a>
        </p>
	</div>
	<div> 
		<h3>Compilation/Execution on bash (Ubuntu or Windows)</h3>
		<p>Use the Makefile (can be adapted if necessary) to compile ECOGEN sources directly on bash (XX is the number of CPU required for compilation):</p> 
		<div class="cmd">make -j XX</div>
		<p>Executing ECOGEN is really easy on bash (XX is the number of CPU required for execution):</p>
		<div class="cmd">mpirun -np XX ECOGEN</div> 
	</div>
</article>

<article>
	<h2> First use of ECOGEN </h2>
	<p> ECOGEN is including a given number of simple prebuild test cases. Each test can be used as a basis for a new one. Entry files are detailled in the <em>ECOGEN_V1.0_userGuide.pdf</em> file included in the package. </p>
</article>
