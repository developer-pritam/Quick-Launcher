# Quick-Launcher
<img src="https://imgur.com/kSqIkim.jpg">
<!DOCTYPE html>
<html>
  <head>
    <title>Quick Launcher</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://fonts.googleapis.com/css?family=Open+Sans" rel="stylesheet" type="text/css"/>
    <link href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet" integrity="sha384-wvfXpqpZZVQGK6TAh5PVlGOfQNHSoD2xbE+QkPxCAFlNEevoEH3Sl0sibVcOQVnN" crossorigin="anonymous"/>

    <style>
        .header p{
          font-size:12px;
          margin:0px;
          padding:5px 0px 0 0;
        }

      	h1{
      		font-size:20px;
      		font-family:monospace;
      		padding:5px;
      	}

      .modal-icons {
        border: 0.5px solid #dadada;
        border-radius:5px;
        padding:10px;
        margin:5px;
      }

      a:link,
      a:visited {
        color: #000000;
        outline: 0;
        text-decoration: none;
      }
      .logo {
        padding: 10px; 
      }

      .logo-icon {
        vertical-align: text-bottom;
        height:50px; 
        width:50px;
        padding-top:10px;
      }

      .flex-container {
        display: flex;
        justify-content: space-between;
        padding: 5px 0px;
      }

      .flex {
        transition: transform 0.3s ease-out;
        padding:0px 10px;
      }

      .flex div:hover{
      	transform: translateY(5px);
      }

      .flex .fa:hover {
        transform:scale(0.7) translateY(8px);
      }

      .flex .fa {
        font-size: 40px;
        color: #3c797b;
      }
      .flex a div{
        visibility: hidden;
      }
      .flex:hover{
        cursor: pointer;
      }
      .flex:hover div{
        visibility: visible;
      }
      button{
        margin:0px 20px;
      }
      .btn{
        color: black;
        border-radius: .25rem;
        padding: .375rem .75rem;
        line-height: 1rem;
        font-size: 1rem; 
        text-align: center;
        vertical-align: middle;
        background-color: white;
        border: 1px solid 007bff;
        margin-top: .25rem;
        margin-bottom: .25rem;
        box-shadow: 1px 1px 1px 1px rgba(0,0,0,0.3);
        transition: background-color 0.3s ease-in-out;
      }
      .btn:hover{
        color: white;
        background-color: black;
        border-color: #0062cc;
      }

    </style>
    
	</head>

	<body>

		<div class="header">
			<center>
			<img src="extension-icon.png" alt="Launcher" class="logo-icon">
      <p>User Name</p>
			<h1 class="logo">
				Social Media Profile launcher
			</h1>
			</center>
		</div>


	<div class="modal-icons">
      <div class="flex-container">
        <div class="flex">
          <a id="website_link" href="#!" target="_blank">
            <center>
            <i class="fa fa-globe" style="color:black "></i>
            <div>Website</div>
            </center>
          </a>
        </div>
         <div class="flex">
          <a id="linkedin_link" href="#!" target="_blank">
            <center>
            <i class="fa fa-linkedin" style="color:black"></i>
            <div>LinkedIn</div>
            </center>
          </a>
        </div>
        <div class="flex">
          <a id="medium_link" href="#!" target="_blank">
            <center>
            <i class="fa fa-medium" style="color:black "></i>
            <div>Medium</div>
            </center>
          </a>
        </div>
        <div class="flex">
          <a id="twitter_link" href="#!" target="_blank">
            <center>
            <i class="fa fa-twitter" style="color:black "></i>
            <div>Twitter</div>
            </center>
          </a>
        </div>
      </div>
    </div>

	<div class="modal-icons">
      <div class="flex-container">
        <div class="flex">
          <a id="github_link" href="https://github.com/" target="_blank">
            <center>
            <i class="fa fa-github" style="color:black"></i>
            <div>GitHub</div>
            </center>
          </a>
        </div>
        <div class="flex">
          <a id="whatsapp_link" href="https://web.whatsapp.com/" target="_blank">
            <center>
            <i class="fa fa-whatsapp" style="color:black"></i>
            <div>Whatsapp</div>
            </center>
          </a>
        </div>
        <div class="flex">
          <a id="facebook_link" href="#!" target="_blank">
            <center>
            <i class="fa fa-facebook-square" style="color:black"></i>
            <div>Facebook</div>
            </center>
          </a>
        </div>
        <div class="flex">
          <a id="youtube_link" href="https://www.youtube.com/" target="_blank">
            <center>
            <i class="fa fa-youtube" style="color:black"></i>
            <div>You Tube</div>
            </center>
          </a>
        </div>
      </div>
    </div>


   		<div class="header">
			<center>
			<h1 class="logo">
				Online Meeting Platforms
			</h1>
			</center>
		</div>


	<div class="modal-icons">
      <div class="flex-container">
        <div class="flex">
          <a id="meet_link" href="https://apps.google.com/meet/" target="_blank">
            <center>
            <img src="https://imgur.com/y8Ii3WW.jpg" class="fa" height="50px" width="50px">
            <div>Google Meet</div>
            </center>
          </a>
        </div>
         <div class="flex">
          <a id="teams_link" href="https://www.microsoft.com/en-in/microsoft-365/microsoft-teams/group-chat-software" target="_blank">
            <center>
            <img src="https://imgur.com/e1y2nxD.jpg" class="fa" height="50px" width="50px">
            <div>Teams</div>
            </center>
          </a>
        </div>
        <div class="flex">
          <a id="zoom_link" href="https://zoom.us/meetings" target="_blank">
            <center>
            <img src="https://imgur.com/qIGpLyD.jpg" class="fa" height="50px" width="50px">
            <div>Zoom</div>
            </center>
          </a>
        </div>
        <div class="flex">
          <a id="webex_link" href="https://cart.webex.com/sign-up" target="_blank">
            <center>
            <img src="https://imgur.com/xLVks5N.jpg" class="fa" height="50px" width="50px">
            <div>Cisco Webex</div>
            </center>
          </a>
        </div>
      </div>
    </div>

    <center>
      <a href="edit.html"><button class="btn"><i class="fa fa-pencil"></i> Edit</button></a>
      <a href="https://github.com/Aayushi-Mittal/Quick-Launcher" target="_blank"><button class="btn"><i class="fa fa-star"></i> Star </button></a>
    </center>

	</body>

</html>
