<h1 align="center">
 Backend Guide (Node+Express)
</h1>
<br />
<p align="center"><strong>🔮 Understanding the Backend Concept's and to Respond efficiently to the client Requests </strong></p>


![Black Minimal Business Personal Profile Linkedin Banner (1)](https://github.com/ADItya0367/Backend-Guide/assets/113133103/79fb63b7-2257-4273-b102-fad533073e27)





<p align="center">
<a href="https://github.com/plandex-ai/plandex/pulls"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs Welcome" /></a> 
<a href="https://github.com/plandex-ai/plandex/releases?q=cli"><img src="https://img.shields.io/github/v/release/plandex-ai/plandex?filter=cli*" alt="Release" /></a>
<a href="https://github.com/plandex-ai/plandex/releases?q=server"><img src="https://img.shields.io/github/v/release/plandex-ai/plandex?filter=server*" alt="Release" /></a>

</p>

<p align="center">
  <a href="#install">
    <b>Install</b>
  </a>
  .
    <a href="./guides/USAGE.md">
    <b>Usage</b>
  </a>
  ·
  <a href="./guides/HOSTING.md">
    <b>Self-Hosting</b>
  </a>
  ·
    <a href="./guides/DEVELOPMENT.md">
    <b>Development</b>
  </a>
  ·
  <a href="https://discord.gg/plandex-ai">
    <b>Discord</b>
  </a>  
</p>

<br/>

<p align="center">This Repository is only made to Understand the concepts of Node and Express js In Depth , With Mongo DB Database , Proper Notes and Practice Projects =(aao)=>Let's Start </p>


<br/>

## Definition Of Node js
<p>
Mainly defined as a Javascript framework that is mainly used for creating servers . It only uses javascript language. But You Know that node js alone cannot make server , it may but it becomes very complex and lenthy , so in order to ease this task Express comes into existance . Express js is a node js framework only. Express is just like react js which is also a framework that helps building faster development process. 
</p>


<br/>


<PHASE-1>
 
<br>

## Installation Process

*  We have a lot of node js Version but better to go with LTS (Long Term Support) Version which is 16.16.0 as a msi installer
*  To confirm installation move to cmd and write (npm -v)
*  Now if we will be intsalling any library in node js then it will be coming from npmjs.com which is a website containing all of the libraries there
*  Check if npm is available or not - by default it comes with node but if not available install it by (npm intall)

  
  <br>

  
<details>
<summary><b>Starting Our Basic Project</b></summary>

-  Now create a folder anywhere on device a
  -  Open it on VS Code  for opening professionally type (code .)
  -  Initialize git using (git init)  -  <pre><code>git init</code></pre>
  - make a repository on github 
  -  copy repo link and link withv this project (git remote add origin repo_link)  <pre><code>git init</code></pre>
- you can do (git add .)(git commit -m "")(git push origin master) once finishing the Project  <pre><code>git add .</code></pre><pre><code>git commit -m ""</code></pre><pre><code>git push origin master</code></pre>
- Starting with VS Code 
 - open terminal (ctrl+shift+`)  <pre><code>ctrl+shift+backtics</code></pre>
 - write command (npm init ) , by doing so a package.json file will be made which will contain all of our dependencies 
 - now write command (npm install express) , we are installing express js here this will create three files  <pre><code>npm install express</code></pre>
   - package-lock.json
   - node_modules-containg library files
 - After creating everything you might asked to select your package name , description and other things as well so in that case select anything you want but make sure that the name of entry file should mathch with the actual file made (entry file declared in package.json === actually made)
 - Now create a file suppose (server.js)
 - We will now start writing our code from here


</details>
