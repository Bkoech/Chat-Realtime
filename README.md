# Chat-Realtime

This app will always be on (BETA) Because there will continue to be updated and developed. Hence, do not forget at the fork and like ya bro :).

This application is created using:
- PHP
- Bootstrap
- MySQL
- jQuery
- Firebase
- Fontawesome

Faetures:
- Public rooms chat.
- Private chat with user.

Realtime:
- Status user online or offline.
- Push new user login.
- Push new message.
- Push inbox count.

<h3>Use:</h3>
1. Import database <code>db/chat_realtime.sql</code>

2. Setting database <code>lib/config.php</code>
<pre>
&lt;?php
// Replace with: your database account
$username     = "REPLACE";
$password     = "REPLACE";
$host         = "REPLACE";
$name         = "chat_realtime";
</pre>
3. Setting firebase & MySQL API <code>js/config.js</code>
<pre>
// Replace with: your_firebase_name.firebaseio.com
var dbRef = new Firebase("https://REPLACE.firebaseio.com/"),
    apis = 'api.php'; // MySQL API
 &nbsp;
// create firebase child
var messageRef = dbRef.child('message'),
    userRef = dbRef.child('user');
</pre>

<h3>Done :)</h3>
<a href="http://ibacor.com/chat"><h4>Live Demo</h4></a>


<a href="https://github.com/bachors/Chat-Realtime/blob/master/LICENSE"><h4>LICENSE</h4></a>
