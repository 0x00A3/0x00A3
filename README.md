<!DOCTYPE html>
<html lang="en" >
<head>
  
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <title>Birdlinux</title>
  <meta itemprop="name" content="Birdlinux">
  <meta itemprop="description" content="Black Hat / Cyber Terrorist">
  <meta property="og:url" content="index.html">
  <meta property="og:type" content="website">
  <meta property="og:title" content="Birdlinux">
  <meta property="og:description" content="Black Hat / Cyber Terrorist">
  <meta property="twitter:image" content="https://cdn.discordapp.com/attachments/773966287915188294/777295604916420659/bird_security.png" />
  <meta name="twitter:card" content="summary">
  <meta name="twitter:title" content="Birdlinuxx">
  <meta name="twitter:description" content="Black Hat / Cyber Terrorist">
  <meta name="twitter:creator" content="@Birdlinuxx">
  <meta name="theme-color" content="#f0f0f0"
  <script src="7cf1aca7fb.js" crossorigin="anonymous"></script><link rel="stylesheet" href="style.css">


<style>   


@import url("https://fonts.googleapis.com/css?family=Roboto");
* {
  font-family: "Roboto", sans-serif;
}

body {
  transition: 3s ease;
  background-color: #131415;
  margin: 0;
  padding: 0;
}
body.big::-webkit-scrollbar {
  display: none;
}

.main {
  width: 100%;
}

.transition {
  transition: 0.75s ease;
}

.nav {
  position: fixed;
  z-index: 14;
  background: #131415;
  width: 100%;
  max-height: 72px;
}
.nav .more {
  transition: none;
  display: none;
  opacity: 0%;
}
.nav.big {
  max-height: initial;
  margin: 8px;
  height: calc(100% - 16px);
  width: calc(100% - 16px);
  border-radius: 5px;
}
.nav.big .more {
  transition: ease 0.7s;
  animation: fadeIn 1s ease 1;
  width: 100%;
  color: rgba(225, 225, 225, 0.6);
  position: fixed;
  z-index: 100;
  bottom: 10px;
  display: flex;
  flex-direction: column;
  align-items: center;
}
.nav.big .more .text,
.nav.big .more .icon {
  cursor: pointer;
}
.nav.big .more:hover {
  color: white;
}

.header {
  line-height: 36px;
  display: flex;
  color: #e1e1e1;
  align-items: center;
  justify-content: space-between;
}
.header .extra {
  display: none;
}
.header .name {
  animation: rightToLeft 0.75s ease 1;
  border-radius: 20px;
  font-size: 32px;
  margin: 0px 10px;
  padding: 10px 15px;
  font-weight: bold;
  display: flex;
  align-items: baseline;
}
.header .name .tag-line {
  padding-left: 20px;
  font-size: 0.6em;
  color: rgba(225, 225, 225, 0.6);
}
.header .menu {
  line-height: 1.5em;
  animation: leftToRight 0.75s ease 1;
  padding: 10px 20px;
  list-style-type: none;
  display: flex;
}
.header .menu li > a {
  transition: 0.75s ease;
  text-align: center;
  color: #e1e1e1;
  width: 100%;
  padding: 10px 12px;
  margin: 0px;
  margin-left: 5px;
  border-radius: 40px;
  text-decoration: none;
}
.header .menu li > a:hover, .header .menu li > a:focus {
  outline: none;
  background-color: #e1e1e1;
  color: rgba(19, 20, 21, 0.75);
}
@media (max-width: 800px) {
  .header .name {
    width: 100%;
    font-size: 28px;
  }
  .header .name .tag-line {
    display: none;
  }
}
.header.big {
  border-bottom: none;
  transition: 0.75s ease;
  z-index: 15;
  height: 100%;
  padding: 0 10vw;
  margin: 1vh;
  box-sizing: border-box;
}
@media (min-width: 2000px) {
  .header.big {
    padding: 0 25vw;
  }
}
.header.big .extra {
  display: inline;
}
.header.big .name {
  animation: none;
  flex-direction: column;
  font-size: 32px;
}
.header.big .name .tag-line {
  padding: 0;
}
.header.big .menu {
  animation: none;
  flex-direction: column;
  padding-right: 4rem;
  font-size: 16px;
}
.header.big .menu li {
  margin: 4px;
}
.header.big .menu li a {
  padding: 4px 10px;
}
.header.big .menu li a span {
  padding-left: 20px;
}
.header.big .menu li a:hover, .header.big .menu li a:focus {
  margin: 1px 0px;
}
@media (max-width: 800px) {
  .header.big {
    flex-direction: column;
    justify-content: center;
    align-items: center;
    padding: 0;
  }
  .header.big .name {
    width: initial;
    padding: 0;
  }
  .header.big .name .tag-line {
    display: initial;
  }
  .header.big .menu {
    flex-direction: row;
    padding: 0;
  }
  .header.big .extra {
    display: none;
  }
}

.full {
  position: fixed;
  left: 0;
  right: 0;
  top: 0;
  bottom: 0;
  z-index: 13;
}

.rainbow {
  transition: 0.75s ease;
  position: absolute;
  z-index: -1;
  width: 100%;
  height: 100%;
  background: linear-gradient(255deg, #b827fc, #2c90fc, #b8fd33, #fec837, #fd1892);
  background-size: 1000% 1000%;
  animation: rainbowRotate 9s ease infinite;
}

.main {
  color: #e1e1e1;
  width: 100%;
  display: flex;
  justify-content: center;
  padding-bottom: 100px;
}
.main .body {
  display: flex;
  flex-direction: column;
  width: 80vw;
  padding-top: 82px;
}

.card {
  background: linear-gradient(255deg, #b827fc, #2c90fc, #b8fd33, #fec837, #fd1892);
  background-size: 1000% 1000%;
  animation: rainbowRotate 9s ease infinite;
  padding: 10px;
  margin-bottom: 15px;
  display: flex;
}
.card .content {
  width: 100%;
  background: black;
  padding: 25px;
  transition: 1s ease;
}
.card .content h3 {
  margin-top: 28px;
}
.card .content a {
  color: #e1e1e1;
}
.card .content a:active {
  color: inherit;
}
.card:hover .content {
  background: rgba(19, 20, 21, 0.75);
}

.hidden {
  display: none;
}

.black {
  background-color: black;
}

@keyframes rainbowRotate {
  0% {
    background-position: 0% 50%;
  }
  50% {
    background-position: 100% 51%;
  }
  100% {
    background-position: 0% 50%;
  }
}
@keyframes rightToLeft {
  from {
    transform: translatex(40%);
  }
  to {
    transform: translatex(0%);
  }
}
@keyframes leftToRight {
  from {
    transform: translatex(-40%);
  }
  to {
    transform: translatex(0%);
  }
}
@keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
.smallname {
  font-size: 0.5em;
  color: rgba(225, 225, 225, 0.6);
}

.btn {
  padding: 5px 20px;
  color: #131415 !important;
  background: #e1e1e1;
  border-radius: 5px;
  text-decoration: none;
  transition: 0.5s ease;
}
.btn:hover {
  color: #e1e1e1 !important;
  background: rgba(19, 20, 21, 0.75);
}



</style>

</head>
<body>
  <div class="full" id="rainbow" class=""><div class="rainbow"></div></div>
  <div class="nav big" id="nav">
    <div class="header big" id="header">
      <div class="name"><span>Birdlinux</span>
        <div class="tag-line">Black Hat / Cyber Terrorist</div>
      </div>
      <ul class="menu">
        <li><a href="https://instagram.com/birdlinux" target="_blank"><i class="fab fa-instagram"></i><span class="extra">Instagram</span></a></li>
        <li><a href="https://twitter.com/birdlinuxx" target="_blank"><i class="fab fa-twitter"></i><span class="extra">Twitter</span></a></li>
        <li><a href="https://github.com/footages" target="_blank"><i class="fab fa-github"></i><span class="extra">GitHub</span></a></li>
        <li><a href="https://discord.gg/F6vs5fyFvF" target="_blank"><i class="fab fa-discord"></i><span class="extra">Discord</span>
        <li><a href="https://mail.google.com/mail/u/0/#inbox?compose=DXDwSWxClxdGLTsdgLKpkzJZdNjMBfpWbdKzNVTfbLpqMJwsFpJDTfShkVRXVfgPwNqzTdDbxztPpFvbZlkDLPTXJGFzRNmPJPWTxkFJXGcMmRshRNJbpwxB" target="_blank"><i class="fas fa-envelope"></i><span class="extra">6@lizard.land</span></a>
          </a></li>
      </ul>
    </div>
    <div class="more" id="more">
      <div class="text">More Information!</div>
      <i class="icon fas fa-angle-down"></i>
    </div>
  </div><br><br>
  <div class="main" id="main">
        <div class="body">
          <div class="card">
            <div class="content">
              <h1>Information</h1>
              <p>I'm George {Birdlinux} im 16 years old and i do Pentesting, Bug Bounty, Hardware Hacking, Website Hacking and Programming. The programming languages i work with are >> <i class="fab fa-python"></i> Python, <i class="fab fa-node-js"></i> JavaScript, Ruby, PHP, C, C-CAML, SWIFT, C# and im currently learning C++<i class="far fa-grin-tongue"></i></p>
            </div>
          </div>
          <div class="card">
            <div class="content">
              <h1>Our Team</h1>
              <div>
                <h3>Bird Security</h3>
                <p>A Hacking Team {Black Hats / Gray Hats}</p>
              <a class="btn" href="https://github.com/footages"><i class="fab fa-github"></i> GitHub</a>
              <a class="btn" href="https://discord.gg/F6vs5fyFvF"><i class="fab fa-discord"></i> Discord</a>
              </div>
              <div>
                <h3>Recruits</h3>
                <p>Recruiting Soon!</p>
                <a class="btn">Coming soon</a>
              </div>
            </div>
          </div>
          <div class="card">
            <div class="content">
              <h1>Contact</h1>
              <p>6@lizard.land</span></a></p>
            </div>
          </div>
        </div>
  </div>
    <script data-cfasync="false" src="cdn-cgi/scripts/5c5dd728/cloudflare-static/email-decode.min.js"></script><script  src="script.js"></script>
  </body>
  </html>
  
