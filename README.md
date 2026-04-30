[full page.html](https://github.com/user-attachments/files/27238640/full.page.html)
<!DOCTYPE html>
<html lang="bn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>StudyNet</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f0f2f5;
        }
        /* Header */
        .header {
            position: fixed;
            top: 0;
            width: 100%;
            height: 60px;
            background-color: #219b3b;
            color: rgb(14, 226, 145);
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 0 20px;
            z-index: 1000;
            box-shadow: 0 2px 5px rgba(169, 204, 13, 0.1);
        }
        .header .logo {
            font-size: 24px;
            font-weight: bold;
        }
        .header input[type="text"] {
            width: 300px;
            padding: 5px 10px;
            border-radius: 20px;
            border: none;
        }
        /* Main layout */
        .main {
            display: flex;
            margin-top: 60px;
            padding: 20px;
        }
        /* Left sidebar */
        .left-sidebar {
            width: 250px;
            margin-right: 20px;
        }
        .left-sidebar h3 {
            margin-bottom: 10px;
            color: #1877f2;
        }
        .left-sidebar ul {
            list-style: none;
            padding: 0;
        }
        .left-sidebar ul li {
            margin: 10px 0;
            padding: 8px;
            background-color: white;
            border-radius: 6px;
            cursor: pointer;
        }
        /* Center feed */
        .feed {
            flex: 1;
            max-width: 600px;
        }
        .status-box {
            background-color: white;
            padding: 15px;
            border-radius: 8px;
            margin-bottom: 20px;
        }
        .status-box textarea {
            width: 100%;
            border-radius: 8px;
            border: 1px solid #ccc;
            padding: 10px;
            resize: none;
        }
        .post {
            background-color: white;
            padding: 15px;
            border-radius: 8px;
            margin-bottom: 20px;
        }
        .post h4 {
            margin: 0 0 5px 0;
        }
        .post p {
            margin: 5px 0 0 0;
        }
        /* Right sidebar */
        .right-sidebar {
            width: 250px;
            margin-left: 20px;
        }
        .right-sidebar h3 {
            margin-bottom: 10px;
            color: #1877f2;
        }
        .friend-suggestion, .ad {
            background-color: white;
            padding: 10px;
            border-radius: 8px;
            margin-bottom: 50px;
        }
        /* Scrollbars */
        .feed, .left-sidebar, .right-sidebar {
            max-height: calc(100vh - 80px);
            overflow-y: auto;
        }
    </style>
</head>
<body>

    <!-- Header -->
    <div class="header">
        <div class="logo">StudyNet</div>
        <input type="text" placeholder="Search StudyNet">
    </div>

    <!-- Main content -->
    <div class="main">
        <!-- Left sidebar -->
        <div class="left-sidebar">
            <h3>Menu</h3>
            <ul>
                <li>Home</li>
                <li>Profile</li>
                <li>Groups</li>
                <li>Events</li>
                <li>Marketplace</li>
                <li>Settings</li>
                <li>Sharif</li>
                <button><a href="fbUI.html"></a></button>
        </ul>
        </div>

        <!-- Center feed -->
        <div class="feed">
            <div class="status-box">
                <textarea rows="3" placeholder="What's on your mind?"></textarea>
                <button style="margin-top:10px; padding:8px 12px; background-color:#1877f2; color:white; border:none; border-radius:6px;">Post</button>
            </div>

            <div class="post">
                <h4>Arafatullah Sharif</h4>
                <p>Hello friends! Welcome to StudyNet.</p>
            </div>

            <div class="post">
                <h4>Jane Doe</h4>
                <p>Learning HTML & CSS is fun!</p>
            </div>
        </div>

        <!-- Right sidebar -->
        <div class="right-sidebar">
            <h3>Friends Suggestions</h3>
            <div class="friend-suggestion">
                <p>John Smith</p>
                <button style="padding:5px 10px; background-color:#42b72a; color:white; border:none; border-radius:6px;">Add Friend</button>
            </div>
            <div class="friend-suggestion">
                <p>Mary Johnson</p>
                <button style="padding:5px 10px; background-color:#42b72a; color:white; border:none; border-radius:6px;">Add Friend</button>
            </div>

            <h3>Sponsored</h3>
            <div class="ad">
                <p>Check out new StudyNet features!</p>
            </div>
        </div>
    </div>

</body>
</html>
