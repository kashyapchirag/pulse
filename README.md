<div id="top" class="">

<div align="center" class="text-center">
<h1>PULSE ⚡</h1>
<p><em>Empowering Real-Time Connections for Limitless Innovation</em></p>

<img alt="last-commit" src="https://img.shields.io/github/last-commit/kashyapchirag/pulse?style=flat&amp;logo=git&amp;logoColor=white&amp;color=0080ff">
<img alt="repo-top-language" src="https://img.shields.io/github/languages/top/kashyapchirag/pulse?style=flat&amp;color=0080ff">
<img alt="repo-language-count" src="https://img.shields.io/github/languages/count/kashyapchirag/pulse?style=flat&amp;color=0080ff">

<p><em>Built with the tools and technologies:</em></p>

<img alt="Express" src="https://img.shields.io/badge/Express-000000.svg?style=flat&amp;logo=Express&amp;logoColor=white">
<img alt="Socket.io" src="https://img.shields.io/badge/Socket.io-010101.svg?style=flat&amp;logo=socketdotio&amp;logoColor=white">
<img alt="MongoDB" src="https://img.shields.io/badge/MongoDB-47A248.svg?style=flat&amp;logo=MongoDB&amp;logoColor=white">
<img alt="Mongoose" src="https://img.shields.io/badge/Mongoose-F04D35.svg?style=flat&amp;logo=Mongoose&amp;logoColor=white">
<img alt=".ENV" src="https://img.shields.io/badge/.ENV-ECD53F.svg?style=flat&amp;logo=dotenv&amp;logoColor=black">
<br>
<img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E.svg?style=flat&amp;logo=JavaScript&amp;logoColor=black">
<img alt="React" src="https://img.shields.io/badge/React-61DAFB.svg?style=flat&amp;logo=React&amp;logoColor=black">
<img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6.svg?style=flat&amp;logo=TypeScript&amp;logoColor=white">
<img alt="Vite" src="https://img.shields.io/badge/Vite-646CFF.svg?style=flat&amp;logo=Vite&amp;logoColor=white">
<img alt="Tailwind CSS" src="https://img.shields.io/badge/Tailwind_CSS-38B2AC.svg?style=flat&amp;logo=tailwind-css&amp;logoColor=white">
</div>

<br>
<hr>

<h2>Table of Contents</h2>
<ul>
<li><a href="#overview">Overview</a></li>
<li><a href="#features">Key Features</a></li>
<li><a href="#getting-started">Getting Started</a>
  <ul>
    <li><a href="#prerequisites">Prerequisites</a></li>
    <li><a href="#installation">Installation</a></li>
    <li><a href="#environment">Environment Variables</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#testing">Testing</a></li>
  </ul>
</li>
</ul>

<hr>

<h2 id="overview">Overview</h2>
<p>
Pulse is a real-time, room-based chat application built using <strong>React</strong>,
<strong>Socket.IO</strong>, <strong>Node.js</strong>, and <strong>MongoDB</strong>.
It allows users to join public chat rooms instantly using a nickname,
send and receive messages in real time, view typing indicators,
and create new rooms dynamically — without traditional authentication.
</p>

<p>
The project focuses on real-time communication, scalable socket architecture,
and a modern glassmorphism-based UI.
</p>

<hr>

<h2 id="features">Key Features</h2>
<ul>
<li>⚡ Real-time messaging using Socket.IO</li>
<li>🏠 Public chat rooms</li>
<li>➕ Create rooms instantly</li>
<li>✍️ Live typing indicators</li>
<li>🔔 Join and leave notifications</li>
<li>🧑 Username-based access (no login/signup)</li>
<li>🎨 Glassmorphism UI with Tailwind CSS</li>
<li>📡 Real-time room updates across all connected users</li>
</ul>

<hr>

<h2 id="getting-started">Getting Started</h2>

<h3 id="prerequisites">Prerequisites</h3>
<ul>
<li><strong>Node.js</strong> (v18+ recommended)</li>
<li><strong>npm</strong></li>
<li><strong>MongoDB</strong> (local or cloud)</li>
</ul>

<h3 id="installation">Installation</h3>

<ol>
<li>
<strong>Clone the repository:</strong>
<pre><code>git clone https://github.com/kashyapchirag/pulse</code></pre>
</li>

<li>
<strong>Navigate to the project directory:</strong>
<pre><code>cd pulse</code></pre>
</li>

<li>
<strong>Install backend dependencies:</strong>
<pre><code>cd server
npm install</code></pre>
</li>

<li>
<strong>Install frontend dependencies:</strong>
<pre><code>cd ../client
npm install</code></pre>
</li>
</ol>

<h3 id="environment">Environment Variables</h3>
<p>Create a <code>.env</code> file inside the <code>server</code> directory:</p>

<pre><code>MONGO_URL=your_mongodb_connection_string
PORT=5000</code></pre>

<h3 id="usage">Usage</h3>

<p><strong>Start the backend server:</strong></p>
<pre><code>cd server
npm run dev</code></pre>

<p><strong>Start the frontend development server:</strong></p>
<pre><code>cd client
npm run dev</code></pre>

<p>Open <code>http://localhost:5173</code> in your browser.</p>

<h3 id="testing">Testing</h3>
<p>
Automated tests are not implemented yet.
Manual testing was performed for:
</p>
<ul>
<li>Real-time messaging</li>
<li>Room creation</li>
<li>Socket event handling</li>
<li>Typing indicators</li>
</ul>

<hr>

<div align="left">
<a href="#top">⬆ Return</a>
</div>

<hr>
</div>
