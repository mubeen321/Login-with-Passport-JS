<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Login with Passport.js App</title>
  <style>
    /* Reset some default styles */
    body, h1, h2, h3, p, ul, li, a {
      margin: 0;
      padding: 0;
    }

    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      color: #333;
    }

    header {
      background-color: #007BFF;
      padding: 1rem;
      text-align: center;
    }

    .title {
      color: #FFF;
    }

    .navbar {
      list-style: none;
      padding: 0;
    }

    .navbar-item {
      display: inline-block;
      margin-right: 1rem;
    }

    .navbar-item a {
      color: #FFF;
      text-decoration: none;
    }

    main {
      padding: 2rem;
    }

    .container {
      max-width: 800px;
      margin: 0 auto;
    }

    footer {
      background-color: #007BFF;
      color: #FFF;
      padding: 1rem;
      text-align: center;
    }

  </style>
</head>

<body>
  <header>
    <h1 class="title">Login with Passport.js App</h1>
    <nav>
      <ul class="navbar">
        <li class="navbar-item"><a href="/">Home</a></li>
        <li class="navbar-item"><a href="/login">Login</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <div class="container">
      <h2>Description</h2>
      <p>
        This is a login with Passport.js app built with Express on the backend and React on the frontend. It allows users to log in using their Google, GitHub, or Facebook accounts using OAuth authentication. The user's session is managed using cookie-session, and the app utilizes Passport.js for authentication and authorization.
      </p>

      <h2>Requirements</h2>
      <ul>
        <li>Node.js and npm installed on your machine</li>
        <li>MongoDB database</li>
      </ul>

      <h2>Installation</h2>
      <ol>
        <li>Clone the repository to your local machine:</li>
      </ol>
      <pre><code>git clone &lt;repository_url&gt;</code></pre>

      <ol start="2">
        <li>Navigate to the project directory:</li>
      </ol>
      <pre><code>cd &lt;project_directory&gt;</code></pre>

      <ol start="3">
        <li>Install the required dependencies:</li>
      </ol>
      <pre><code>npm install</code></pre>

      <h2>Running the Application</h2>
      <p>
        To start the backend server, run the following command:
      </p>
      <pre><code>npm start</code></pre>

      <p>
        The backend server will be running on <a href="http://localhost:5000">http://localhost:5000</a>.
      </p>

      <p>
        To start the frontend, navigate to the "client" folder and run the following command:
      </p>
      <pre><code>npm start</code></pre>

      <p>
        The frontend will be running on <a href="http://localhost:3000">http://localhost:3000</a>.
      </p>

      <h2>Endpoints</h2>
      <ul>
        <li><strong>GET /auth/login/success:</strong> Returns the user information if the user is logged in.</li>
        <li><strong>GET /auth/login/failed:</strong> Returns an error message if the login process fails.</li>
        <li><strong>GET /auth/logout:</strong> Logs out the user and redirects to the home page.</li>
        <li><strong>GET /auth/google:</strong> Initiates Google OAuth authentication.</li>
        <li><strong>GET /auth/google/callback:</strong> Callback route for Google OAuth authentication</li>
        <li><strong>GET /auth/github:</strong> Initiates GitHub OAuth authentication.</li>
        <li><strong>GET /auth/github/callback:</strong> Callback route for GitHub OAuth authentication.</li>
        <li><strong>GET /auth/facebook:</strong> Initiates Facebook OAuth authentication.</li>
        <li><strong>GET /auth/facebook/callback:</strong> Callback route for Facebook OAuth authentication.</li>
      </ul>

    </div>

  </main>

  <footer>
    <p>© 2023 Your Company. All rights reserved.</p>
  </footer>
</body>

</html>
