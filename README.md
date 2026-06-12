<h1 align="center">
    <i>
        <strong>Login Page</strong>
    </i>
</h1>

<h2>
    <i>
        <strong>Dependencies and Prerequisites:</strong>
    </i>
</h2>

<ul>
    <li>
        <strong>Docker installed</strong>
    </li>
</ul>

<h2>
   <i>
     <strong>What is it?</strong>
    </i>
</h2>

<p align="center">
    <i>
        <strong>Login Page</strong> is a static and responsive web application, that represents a login page with
        field to sign in or sign up made with <strong>HTML</strong>, <strong>CSS</strong> and <strong>Docker</strong> 
    </i>
</p>


<h2>
    <i>
        <strong>Preview:</strong>
    </i>
</h2>

<div align="center">
    <img src="assets/login_preview.png"></img>
</div>

<h2>
   <i>
     <strong>How to use it?</strong>
    </i>
</h2>

<p align="center">
    <i>
        This web page project contains a <strong>Dockerfile</strong>
        and a <strong>docker-compose.yaml</strong> files that together builds a <strong>nginx</strong> server that hosts the static page, allowing other devices in the local network to connect to the server. 
    </i>
</p>

<p align="center">
    <i>
        Make sure to be on the same directory as: <strong>Dockerfile</strong> and <strong>docker-compose.yaml</strong>
    </i>
</p>

<pre>
    <code class="language-bash">
        .
        ├── assets
        │   ├── login_preview.png
        │   └── user_auth.png
        ├── docker-compose.yaml
        ├── Dockerfile
        ├── index.html
        ├── README.md
        └── style.css
    </code>
</pre>

<p align="center">
    <i>
        Run the following commands to build and manager the container:
    </i>
</p>

<pre>
    <code class="language-bash">docker compose up</code>
</pre>

<p align="center">
    <i>
        (Build and run on foreground the application)
    </i>
</p>

<pre>
    <code class="language-bash">docker compose up -d</code>
</pre>

<p align="center">
    <i>
        (Build and run on background the application)
    </i>
</p>

<pre>
    <code class="language-bash">docker compose stop</code>
</pre>

<p align="center">
    <i>
        (Stop the application from running)
    </i>
</p>

<pre>
    <code class="language-bash">docker compose down</code>
</pre>

<p align="center">
    <i>
        (Remove container)
    </i>
</p>

<img src="assets/html.png"></img> <img src="assets/css.png"></img> <img src="assets/docker.png" length="100" height="100"></img>

<hr>


<p>
    <i>
        Made with 💙 by Igor Ruiz, Cyber Security Student from Federal University of Itajuba.
    </i>
</p>