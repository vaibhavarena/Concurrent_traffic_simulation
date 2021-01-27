# Concurrent_traffic_simulation

<p>The implementation of Concurrent traffic simulation, the fourth project in Udacity C++ Nanodegree. In this project, the vehicles
are run as different tasks, and they have access to the same thread queue and message queue, which are protected 
by resource locking mechanism in C++. The vehicles wait in thread queue when they reach an intersection and 
are released in First in First out order.</p>

<h2>Dependencies for Running Locally</h2>



<li><b>cmake >= 2.8</b>
        <ul>
            <li>All OSes: click here for installation instructions</li>
        </ul>
</li>

<li>
    <b>make >= 4.1 (Linux, Mac), 3.81 (Windows)</b>
        <ul>
            <li>Linux: make is installed by default on most Linux distros</li>
        
<li>Mac: install Xcode command line tools to get make</li>
</li>
            <li>Windows: Click here for installation instructions</li>
</ul>
    </li>

<li><b>OpenCV >= 4.1 </b>
        <ul>
            <li>The OpenCV 4.1.0 source code can be found here</li>
</ul>
<li><b>gcc/g++ >= 5.4</b>
        <ul>
            <li>Linux: gcc / g++ is installed by default on most Linux distros</li>
</ul>
        

<h2>Basic Build Instructions</h2>
<ul>
    <li>Clone this repo.</li>
    <li>Make a build directory in the top level directory: mkdir build && cd build</li>
    <li>Compile: cmake .. && make</li>
    <li>Run it: ./membot.</li>
</ul>

