# Women-safety-drone-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Women's Safety Drone Project</title>
    <style>
        /* General Styling */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background: linear-gradient(to right, #f4f4f4, #e6e6e6);
            color: #333;
            line-height: 1.6;
            padding: 20px;
            overflow-x: hidden;
        }

        header {
            background: #4CAF50;
            color: #fff;
            text-align: center;
            padding: 40px 20px;
            animation: fadeIn 1s ease-in;
        }

        h1, h2 {
            text-align: center;
        }

        main {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        section {
            background: #fff;
            padding: 40px;
            margin: 20px 0;
            box-shadow: 0 0 20px #ccc;
            transition: transform 0.5s;
        }

        section:hover {
            transform: scale(1.05);
        }

        ul {
            list-style: none;
            padding: 0;
        }

        ul li {
            background: #4CAF50;
            color: #fff;
            margin: 10px 0;
            padding: 15px;
            border-radius: 5px;
            transition: 0.3s;
        }

        ul li:hover {
            background: #45a049;
            transform: translateX(10px);
        }

        footer {
            text-align: center;
            padding: 20px;
            background: #222;
            color: #fff;
        }

        a {
            color: #4CAF50;
            text-decoration: none;
        }

        /* Drone Animation */
        .drone-container {
            position: relative;
            width: 100%;
            height: 300px;
            overflow: hidden;
        }

        .drone {
            width: 120px;
            position: absolute;
            top: 50%;
            left: -150px;
            animation: flyAcross 10s linear infinite;
        }

        @keyframes flyAcross {
            0% {
                left: -150px;
                transform: rotate(0deg);
            }
            50% {
                left: 50%;
                transform: rotate(15deg);
            }
            100% {
                left: 110%;
                transform: rotate(-5deg);
            }
        }

        @keyframes fadeIn {
            0% {
                opacity: 0;
            }
            100% {
                opacity: 1;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Women's Safety Drone Project</h1>
    <p>Empowering women's safety through autonomous protection drones</p>
</header>

<main>

    <!-- Drone Animation -->
    <div class="drone-container">
        <img src="https://img.icons8.com/ios-filled/100/drone.png" alt="Drone" class="drone">
    </div>

    <!-- About the Project -->
    <section>
        <h2>About the Project</h2>
        <p>
            This project aims to develop an autonomous drone system to protect women in dangerous situations.
            Upon triggering an SOS signal, the drone flies to the victim’s location, uses lights and alarms to deter threats,
            and streams live video until help arrives.
        </p>
    </section>

    <!-- How It Works -->
    <section>
        <h2>How It Works</h2>
        <ul>
            <li><strong>Trigger System:</strong> SOS activated via a GPS device or mobile app.</li>
            <li><strong>GPS Navigation:</strong> The drone receives live GPS coordinates.</li>
            <li><strong>Autonomous Flight:</strong> It flies to the woman’s location.</li>
            <li><strong>Protection Mode:</strong> Lights, alarms, and live streaming are activated.</li>
            <li><strong>Support Until Help Arrives:</strong> The drone stays on guard until authorities arrive.</li>
        </ul>
    </section>

    <!-- Features -->
    <section>
        <h2>Key Features</h2>
        <ul>
            <li>Real-time GPS tracking</li>
            <li>Live video streaming to safety teams</li>
            <li>Automatic alarm and lighting deterrents</li>
            <li>Obstacle avoidance using sensors</li>
            <li>Return-to-home mode after rescue</li>
        </ul>
    </section>

    <!-- Impact -->
    <section>
        <h2>Impact and Benefits</h2>
        <p>
            The drone ensures rapid emergency response, deters attackers, and provides visual evidence. 
            <strong>Advantages:</strong>
        </p>
        <ul>
            <li>Faster response times during emergencies.</li>
            <li>Real-time visual evidence for law enforcement.</li>
            <li>Continuous monitoring and protection until help arrives.</li>
        </ul>
    </section>

</main>

<!-- Contact Section -->
<footer>
    <p>Contact us: <a href="mailto:pshruthirani699@gmail.com">pshruthirani699@gmail.com</a></p>
    <p>&copy; 2025 Women's Safety Drone Project. All rights reserved.</p>
</footer>

</body>
</html>
