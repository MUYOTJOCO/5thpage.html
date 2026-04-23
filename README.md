<html>  
<head>  
    <title>Home Workout Hub</title>  
  
    <style>  
        body {  
            font-family: Arial, sans-serif;  
            margin: 0;  
            padding: 0 20px;  
            background-color: #0f172a;
            color: #e2e8f0;
        }  
  
        header {
            background-color: #1e293b;
            padding: 15px;
            border-radius: 10px;
        }

        nav button {  
            margin: 5px;  
            padding: 10px 15px;  
            cursor: pointer;  
            background-color: #334155;
            border: none;
            color: white;
            border-radius: 6px;
            transition: 0.2s;
        }  

        nav button:hover {
            background-color: #38bdf8;
            color: black;
        }
  
        section {  
            display: none;  
        }  
  
        section.active {  
            display: block;  
        }  
  
        h1, h2, h3 {  
            margin-top: 20px;  
        }  
  
        ul {  
            margin-left: 20px;  
        }  
  
        img {  
            border-radius: 10px;  
            margin-top: 10px;
            box-shadow: 0 4px 10px #000000;
        }  
  
        footer {  
            margin-top: 30px;  
            text-align: center;  
            font-size: 14px;  
            color: #94a3b8;  
        }  
  
        /* Workout Cards */
        .card {
            background-color: #1e293b;
            padding: 15px;
            border-radius: 10px;
            margin-bottom: 20px;
        }

        /* Contact Form Styling */  
        form input[type="text"],  
        form input[type="email"],  
        form textarea {  
            padding: 10px;  
            width: 100%;  
            max-width: 400px;  
            margin-bottom: 10px;  
            border: 1px solid #334155;  
            border-radius: 5px;  
            background-color: #020617;
            color: white;
        }  
  
        form input[type="submit"] {  
            padding: 10px 20px;  
            border: none;  
            background-color: #22c55e;  
            color: white;  
            cursor: pointer;  
            border-radius: 5px;  
            font-size: 16px;  
        }  
  
        form input[type="submit"]:hover {  
            background-color: #16a34a;  
        }  
    </style>  
  
    <script>  
        function showSection(id) {  
            var sections = document.querySelectorAll("section");  
            sections.forEach(function(s) {  
                s.classList.remove("active");  
            });  
            document.getElementById(id).classList.add("active");  
        }  
  
        window.onload = function() {  
            showSection("home");  
        }  
    </script>  
</head>  
  
<body>  
  
<header>  
    <h2>Home Workout Hub</h2>  
  
    <nav>  
        <button onclick="showSection('home')">Home</button>  
        <button onclick="showSection('workouts')">Workouts</button>  
        <button onclick="showSection('tips')">Tips & Guides</button>  
        <button onclick="showSection('about')">About</button>  
        <button onclick="showSection('progress')">Progress</button>
    </nav>  
  
    <hr>  
</header>  
  
<section id="home">  
    <h1>Welcome to Home Workout Hub</h1>  
    <p>Your journey to a stronger and healthier body starts at home!</p>  
  
    <h2>READ ME</h2>  
    <img src="https://images.unsplash.com/photo-1554284126-aa88f22d8b74" width="300">  
    <p><strong>"one day or day one?"</strong></p>  
  
    <br>  
    <img src="https://images.unsplash.com/photo-1583454110551-21f2fa2afe61" width="300">  
    <p><strong>"If you don't sacrifice for what you want, what you want becomes the sacrifice."</strong></p>  
  
    <br>  
    <img src="https://images.unsplash.com/photo-1517960413843-0aee8e2b3285" width="300">  
    <p><strong>"Not every lion that chased the deer caught it. But every lion that caught a deer chased it."</strong></p>  
  
    <br>  
</section>  
  
<section id="workouts">  
    <h1>Workout Programs</h1>  

    <h2>🟢 Easy Level</h2>  

    <div class="card">
        <h3>Jumping Jacks</h3>  
        <img src="https://images.unsplash.com/photo-1599058917212-d750089bc07e" width="250">
        <p><strong>Duration:</strong> 3 sets of 20 reps</p>  
    </div>

    <div class="card">
        <h3>Wall Sit</h3>  
        <img src="https://images.unsplash.com/photo-1594737625785-c45e68e1c9f5" width="250">
        <p><strong>Duration:</strong> 3 sets of 30 seconds</p>  
    </div>
  
    <h2>🟡 Intermediate Level</h2>  

    <div class="card">
        <h3>Push-ups</h3>  
        <img src="https://images.unsplash.com/photo-1598971639058-a4d0b4b4b3f0" width="250">
    </div>

    <div class="card">
        <h3>Squats</h3>  
        <img src="https://images.unsplash.com/photo-1571019613454-1cb2f99b2d8b" width="250">
    </div>
  
    <h2>🔴 Hard Level</h2>  

    <div class="card">
        <h3>Burpees</h3>  
        <img src="https://images.unsplash.com/photo-1599058918144-1ffabb6ab9a0" width="250">
    </div>

    <div class="card">
        <h3>Plank</h3>  
        <img src="https://images.unsplash.com/photo-1605296867304-46d5465a13f1" width="250">
    </div>

</section>  
  
<section id="tips">  
    <h1>Tips & Guides</h1>  
    <ul>  
        <li>Stay consistent</li>  
        <li>Focus on proper form</li>  
        <li>Stay hydrated</li>  
        <li>Get enough rest</li>  
    </ul>  
</section>  
  
<section id="about">  
    <h1>About</h1>  
    <p>Helping you get fit at home.</p>  
</section>  

<section id="progress">
    <h1>Progress Tracker</h1>
    <p>Track your improvement every week.</p>

    <ul>
        <li>Week 1: Starting point</li>
        <li>Week 2: Improved endurance</li>
        <li>Week 3: Stronger and consistent</li>
        <li>Week 4: Visible progress 💪</li>
    </ul>
</section>
  
<footer>  
    <p>© 2026 Home Workout Hub</p>  
</footer>  
  
</body>  
</html>
