<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MG Motor | Official Showcase</title>
    <style>
        /* Official MG Brand Colors */
        :root {
            --mg-red: #d32f2f;
            --dark-gray: #1a1a1a;
            --light-gray: #f4f4f4;
        }

        body {
            font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: var(--dark-gray);
            line-height: 1.6;
        }

        /* Navigation */
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 5%;
            background: white;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }

        .logo {
            font-size: 28px;
            font-weight: bold;
            color: var(--mg-red);
            letter-spacing: 2px;
        }

        nav ul {
            list-style: none;
            display: flex;
            gap: 25px;
        }

        nav a {
            text-decoration: none;
            color: var(--dark-gray);
            font-weight: 500;
            text-transform: uppercase;
            font-size: 14px;
        }

        /* Hero Section */
        .hero {
            position: relative;
            height: 80vh;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-align: center;
            overflow: hidden;
            background-color: black;
        }

        .hero img {
            position: absolute;
            width: 100%;
            height: 100%;
            object-fit: cover;
            opacity: 0.7;
        }

        .hero-content {
            position: relative;
            z-index: 1;
            max-width: 800px;
        }

        .hero h1 {
            font-size: 3.5rem;
            margin: 0;
            letter-spacing: 4px;
        }

        .btn-main {
            display: inline-block;
            margin-top: 20px;
            padding: 12px 35px;
            background-color: var(--mg-red);
            color: white;
            text-decoration: none;
            font-weight: bold;
            text-transform: uppercase;
            border-radius: 4px;
            transition: 0.3s;
        }

        .btn-main:hover {
            background-color: #b71c1c;
        }

        /* Stats Section */
        .specs {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            padding: 50px 10%;
            background: var(--dark-gray);
            color: white;
            text-align: center;
        }

        .spec-item h2 {
            color: var(--mg-red);
            margin-bottom: 5px;
        }

        .spec-item p {
            font-size: 0.9rem;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        footer {
            text-align: center;
            padding: 20px;
            font-size: 12px;
            color: #888;
        }
    </style>
</head>
<body>

    <nav>
        <div class="logo">MG</div>
        <ul>
            <li><a href="#">Electric</a></li>
            <li><a href="#">SUVs</a></li>
            <li><a href="#">Hatchbacks</a></li>
            <li><a href="#" style="color: var(--mg-red);">Test Drive</a></li>
        </ul>
    </nav>

    <header class="hero">
        <img src="https://images.unsplash.com/photo-1707153673552-3260959449f8?q=80&w=2000&auto=format&fit=crop" alt="MG Cyberster">
        <div class="hero-content">
            <h1>MG CYBERSTER</h1>
            <p>The pure-electric roadster has arrived. Experience the future of performance.</p>
            <a href="#" class="btn-main">Build Your Own</a>
        </div>
    </header>

    <section class="specs">
        <div class="spec-item">
            <h2>3.2s</h2>
            <p>0-100 km/h</p>
        </div>
        <div class="spec-item">
            <h2>580km</h2>
            <p>Range (Est.)</p>
        </div>
        <div class="spec-item">
            <h2>510 PS</h2>
            <p>Max Power</p>
        </div>
        <div class="spec-item">
            <h2>AWD</h2>
            <p>Drivetrain</p>
        </div>
    </section>

    <footer>
        &copy; 2026 MG Motor Clone Project. For educational purposes.
    </footer>

</body>
</html>
