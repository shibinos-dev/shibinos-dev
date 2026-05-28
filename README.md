<html>
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Git Repository Profile</title>

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family: Arial, sans-serif;
    }

    body{
      background:#0d1117;
      color:#ffffff;
      display:flex;
      justify-content:center;
      align-items:center;
      min-height:100vh;
      padding:20px;
    }

    .profile-card{
      background:#161b22;
      width:350px;
      border-radius:15px;
      padding:25px;
      box-shadow:0 0 20px rgba(0,0,0,0.5);
      text-align:center;
    }

    .profile-card img{
      width:120px;
      height:120px;
      border-radius:50%;
      border:4px solid #58a6ff;
      margin-bottom:15px;
    }

    .profile-card h1{
      font-size:28px;
      margin-bottom:5px;
    }

    .username{
      color:#58a6ff;
      margin-bottom:15px;
    }

    .bio{
      font-size:14px;
      color:#c9d1d9;
      margin-bottom:20px;
      line-height:1.5;
    }

    .stats{
      display:flex;
      justify-content:space-between;
      margin-bottom:20px;
    }

    .stat-box{
      background:#21262d;
      padding:12px;
      border-radius:10px;
      width:30%;
    }

    .stat-box h2{
      color:#58a6ff;
      font-size:20px;
    }

    .stat-box p{
      font-size:12px;
      color:#c9d1d9;
    }

    .btn{
      display:inline-block;
      text-decoration:none;
      background:#238636;
      color:white;
      padding:12px 20px;
      border-radius:8px;
      transition:0.3s;
      font-weight:bold;
    }

    .btn:hover{
      background:#2ea043;
    }
  </style>
</head>
<body>

  <div class="profile-card">
    
    <img src="https://avatars.githubusercontent.com/u/9919?s=200&v=4" alt="Profile Image">

    <h1>John Doe</h1>
    <p class="username">@johndoe</p>

    <p class="bio">
      Full Stack Developer | Open Source Contributor | Passionate about Web Development and GitHub Projects.
    </p>

    <div class="stats">
      <div class="stat-box">
        <h2>120</h2>
        <p>Repos</p>
      </div>

      <div class="stat-box">
        <h2>450</h2>
        <p>Followers</p>
      </div>

      <div class="stat-box">
        <h2>180</h2>
        <p>Following</p>
      </div>
    </div>

    <a href="https://github.com/" class="btn" target="_blank">
      Visit GitHub
    </a>

  </div>

</body>
</html>
