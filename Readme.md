<h1>IamGui Base Template</h1>

<p>This contains the base boiler of iamgui for graphics using Modern OpenGL (with/for):
<ul>
<li>GLFW, GLAD</li>
<li>For Windows and Mac platform</li>
</ul>

<h2>How to use it : </h2>
<li>clone the repo <code>git clone https://github.com/Thaparoshan143/iamgui_base</code></li>
<li>Entry point is from main.mm for mac and main.cpp for window (dir - src>win and src>mac)</li>
<li>Use make file to compile the all the cpp file (change dir to the makefile) </li>
<li>command : <code>make all</code> (to make final executable) || to remove the obj and exe, command : <code>make clean </code> </li>
</p>

<hr>
<h3>NOTES</h3>
<ul>
  <li>glfw3.dll is required for exe for windows.</li>
  <li>Makefile dependes upon includes>lib for libs..</li>
  <li>Update the directory or the directory path in makefile as per the change in the structure.</li>
</ul>
