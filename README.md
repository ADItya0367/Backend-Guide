<h1 align="center">
 Backend Guide 
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

<br/>

## 🌟  Installation Process 

#📑  There are two ways through which we can Setup our System . Let's seee

<details>
 <summary><b>Installation Process includes</b></summary>
 <br>
<p>
- Download Nodejs (Make sure version should be > 17 )
 
*  open cmd and run this coommand by going to desktop (cd Desktop) command:npx create-react-native-app project_name 

* now run this command to start your metro cmd prompt (from where your app will be initialised) command: npx expo start
*   Here you can get some errors toh brothers Acche se step follow karna
 *   Now here before running previous command make sure to start an emulator (i will recommend Android Studio)
 *   Download Android Studio and Install it (settings same rehne dena)....install completely
 *   After installing go to SDK Manager 
</p>
</details>

<details>
<summary><b>Installation Through CLI(Command Line Argument)</b></summary>

<p>
<pre><code>git clone https://github.com/plandex-ai/plandex.git
git clone https://github.com/plandex-ai/survey.git
cd plandex/app/cli
go build -ldflags "-X plandex/version.Version=$(cat version.txt)"
mv plandex /usr/local/bin # adapt as needed for your system
</code></pre>
</p>
</details>
