<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>YourUsername | Profile</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@500&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Orbitron', sans-serif;
      background: black; /* Plain black background */
      color: white;
      height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      overflow: hidden;
    }

    .overlay {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: rgba(0, 0, 0, 0.8);
      z-index: 0;
    }

    .container {
      z-index: 1;
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 15px;
      border-radius: 15px;
      backdrop-filter: blur(6px);
      border: 2px solid rgba(255, 0, 0, 0.8);
      box-shadow: 0 0 15px rgba(255, 0, 0, 0.5);
      width: 300px;
      transition: transform 0.3s ease;
    }

    .container:hover {
      transform: scale(1.03);
    }

    .pfp {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      border: 4px solid rgba(255, 0, 0, 1);
      object-fit: cover;
      box-shadow: 0 0 20px rgba(255, 0, 0, 0.5);
    }

    .username {
      font-size: 24px; /* Reduced font size */
      color: red; /* Color */
      font-weight: normal; /* Normal font weight */
      margin: 8px 0; /* Adjusted margin */
    }

    .status {
      font-size: 16px; /* Reduced font size */
      color: #ff5555;
      text-shadow: 0 0 2px rgba(255, 0, 0, 1), 0 0 4px rgba(255, 0, 0, 0.5); /* Reduced text-shadow */
      font-style: italic;
      margin-bottom: 10px; /* Adjusted margin */
    }

    .links {
      display: flex;
      justify-content: space-between;
      width: 100%;
      position: relative;
    }

    .link-button {
      padding: 10px 20px; /* Adjusted padding */
      border-radius: 30px;
      border: 2px solid rgba(255, 0, 0, 1);
      color: white;
      text-decoration: none;
      background: rgba(255, 255, 255, 0.1);
      backdrop-filter: blur(4px);
      font-size: 12px; /* Adjusted font size */
      animation: glow 1s infinite alternate;
      transition: all 0.3s ease;
      box-shadow: 0 0 10px rgba(255, 0, 0, 0.5); /* Reduced box-shadow */
      text-align: center;
      flex: 1;
      margin: 0 2px; /* Adjusted space between buttons */
    }

    .link-button:hover {
      transform: translateY(-2px);
      background: rgba(255, 0, 0, 0.3);
      box-shadow: 0 0 15px rgba(255, 0, 0, 1); /* Reduced box-shadow on hover */
    }

    @keyframes glow {
      0% { box-shadow: 0 0 10px rgba(255, 0, 0, 1); } /* Reduced glow */
      100% { box-shadow: 0 0 15px rgba(255, 0, 0, 0.5); } /* Reduced glow */
    }

    @media (max-width: 600px) {
      .container {
        width: 90%;
      }

      .username {
        font-size: 20px; /* Further reduce for smaller screens */
      }

      .status {
        font-size: 14px; /* Further reduce for smaller screens */
      }

      .link-button {
        padding: 8px 15px; /* Adjusted padding for smaller screens */
        font-size: 10px; /* Adjusted font size for smaller screens */
      }
    }
  </style>
</head>
<body>
  <div class="overlay"></div>
  <div class="container">
    <img src="https://i.pinimg.com/originals/e8/0d/b4/e80db497b9e40ed513f6bc3ba8be3e9c.gif" alt="Profile Picture" class="pfp">
    <div class="username">laspez</div>
    <div class="status">Coding</div>
    <div class="links">
      <a href="https://discord.gg/TjTWu8CJ" class="link-button" target="_blank">Discord</a>
    </div>
  </div>
</body>
</html>ing jesus.html…]()
