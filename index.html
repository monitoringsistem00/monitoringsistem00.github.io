<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Login System</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .container {
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            width: 300px;
        }
        .dashboard-container {
            width: 400px;
            text-align: center;
        }
        h2 {
            text-align: center;
            margin-bottom: 20px;
        }
        input[type="text"], input[type="password"] {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 4px;
            box-sizing: border-box;
        }
        button {
            width: 100%;
            padding: 10px;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            margin-top: 10px;
        }
        button:hover {
            background-color: #45a049;
        }
        .error {
            color: red;
            text-align: center;
            margin-bottom: 10px;
        }
        .hidden {
            display: none;
        }
        a {
            color: #4CAF50;
            text-decoration: none;
            cursor: pointer;
        }
        a:hover {
            text-decoration: underline;
        }
        .info {
            background-color: #e7f3fe;
            border-left: 4px solid #2196F3;
            padding: 10px;
            margin-bottom: 15px;
            font-size: 14px;
        }
    </style>
</head>
<body>
    <!-- Login Page (index.php) -->
    <div id="loginPage" class="container">
        <h2>Login</h2>
        <div class="info">
            <strong>Demo Login:</strong><br>
            Username: admin<br>
            Password: password
        </div>
        <p id="errorMessage" class="error hidden">Username atau password salah!</p>
        <form id="loginForm">
            <input type="text" id="username" name="username" placeholder="Username" required>
            <input type="password" id="password" name="password" placeholder="Password" required>
            <button type="submit">Login</button>
        </form>
    </div>

    <!-- Dashboard Page (dashboard.php) -->
    <div id="dashboardPage" class="container dashboard-container hidden">
        <h2>Selamat datang, <span id="usernameDisplay"></span>!</h2>
        <p>Anda telah berhasil login.</p>
        <a id="logoutBtn">Logout</a>
    </div>

    <script>
        // Simulates login.php - Credential validation (hardcoded)
        const validUsername = 'admin';
        const validPassword = 'password';

        // Simulates PHP session
        let session = {
            loggedin: false,
            username: ''
        };

        // DOM Elements
        const loginPage = document.getElementById('loginPage');
        const dashboardPage = document.getElementById('dashboardPage');
        const loginForm = document.getElementById('loginForm');
        const errorMessage = document.getElementById('errorMessage');
        const usernameDisplay = document.getElementById('usernameDisplay');
        const logoutBtn = document.getElementById('logoutBtn');

        // Check session on page load (simulates session_start() check)
        function checkSession() {
            if (session.loggedin) {
                showDashboard();
            } else {
                showLogin();
            }
        }

        // Login form submission (simulates login.php POST handler)
        loginForm.addEventListener('submit', function(e) {
            e.preventDefault();
            
            const username = document.getElementById('username').value;
            const password = document.getElementById('password').value;

            // Validate credentials
            if (username === validUsername && password === validPassword) {
                // Successful login - set session
                session.loggedin = true;
                session.username = username;
                // Redirect to dashboard
                showDashboard();
            } else {
                // Failed login - redirect with error
                errorMessage.classList.remove('hidden');
                document.getElementById('password').value = '';
            }
        });

        // Logout button (simulates logout.php)
        logoutBtn.addEventListener('click', function() {
            // Destroy session
            session.loggedin = false;
            session.username = '';
            // Redirect to login page
            showLogin();
        });

        // Show dashboard page
        function showDashboard() {
            errorMessage.classList.add('hidden');
            loginPage.classList.add('hidden');
            dashboardPage.classList.remove('hidden');
            usernameDisplay.textContent = session.username;
        }

        // Show login page
        function showLogin() {
            dashboardPage.classList.add('hidden');
            loginPage.classList.remove('hidden');
            document.getElementById('username').value = '';
            document.getElementById('password').value = '';
            errorMessage.classList.add('hidden');
        }

        // Initialize - Check session on page load
        checkSession();
    </script>
</body>
</html>
