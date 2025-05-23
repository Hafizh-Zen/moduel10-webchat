<h1>Module 10</h1>

<p><strong>HAFIZH SURYA MUSTAFA ZEN</strong> - <code>2306256343</code></p>
<hr>

<h2>3.1 Original Code</h2>

<h4>Login Page</h4>

<p>Open <strong>http://localhost:8000</strong> in your browser to access a basic login form:</p>

<p><img src="image\webchatlogin.png" alt="Login screen"></p>

<ol>
  <li>Type in your <strong>Username</strong>.</li>
  <li>Click the <strong>GO CHATTING!</strong> button.</li>
</ol>

<h3>4. What Happens Behind the Scenes</h3>

<ol>
  <li>A <strong>WebSocket connection</strong> is established between the Yew front-end and the Rust back-end (port 8080).</li>
  <li>When the page loads, the client sends your username to the server, which registers it in the active user list.</li>
  <li>Whenever a message is sent by any client, the server rebroadcasts it to all connected users.</li>
  <li>The Yew interface updates live, displaying each message as a chat bubble in real time.</li>
</ol>
