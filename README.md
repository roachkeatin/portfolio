<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Engineering Portfolio | Mechanical & Physics</title>
    <style>
        :root {
            --bg-color: #f8f9fa;
            --card-bg: #ffffff;
            --text-color: #212529;
            --accent-color: #0056b3;
            --border-color: #e9ecef;
        }
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            line-height: 1.6;
            color: var(--text-color);
            background-color: var(--bg-color);
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
        }
        header {
            text-align: center;
            padding: 40px 0;
            border-bottom: 2px solid var(--border-color);
            background-color: var(--card-bg);
            margin-bottom: 30px;
        }
        h1 { margin: 0; font-size: 2.2rem; }
        p.subtitle { color: #6c757d; margin-top: 5px; font-weight: 500; }
        
        .project-card {
            background: var(--card-bg);
            border: 1px solid var(--border-color);
            border-radius: 8px;
            padding: 25px;
            margin-bottom: 25px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.05);
        }
        .project-title { margin-top: 0; color: var(--accent-color); }
        .tag {
            display: inline-block;
            background: #e9ecef;
            padding: 2px 8px;
            border-radius: 4px;
            font-size: 0.85rem;
            margin-right: 5px;
            margin-bottom: 10px;
            font-weight: 600;
        }
        .grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 15px;
            margin-top: 15px;
        }
        .img-placeholder {
            background-color: #dee2e6;
            border-radius: 6px;
            height: 180px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #6c757d;
            font-size: 0.9rem;
        }
        @media (max-width: 600px) {
            .grid { grid-template-columns: 1fr; }
        }
    </style>
</head>
<body>

    <header>
        <div class="container">
            <h1>Engineering Portfolio</h1>
            <p class="subtitle">B.S. Engineering Physics — Mechanical Engineering Track</p>
        </div>
    </header>

    <div class="container">

        <!-- Project 1 -->
        <div class="project-card">
            <h2 class="project-title">Closed-Loop Thermal Regulation System</h2>
            <span class="tag">Arduino</span><span class="tag">PWM Control</span><span class="tag">Circuit Design</span>
            <p>Designed and built an automated cooling system using an Arduino Uno, thermistor sensor, and transistor-driven DC motor[cite: 1]. Programmed dynamic PWM speed control and integrated an LCD display for real-time telemetry[cite: 1].</p>
            <div class="grid">
                <div class="img-placeholder">[ Replace with Schematic / Circuit Photo ]</div>
                <div class="img-placeholder">[ Replace with Motor / LCD GIF ]</div>
            </div>
        </div>

        <!-- Project 2 -->
        <div class="project-card">
            <h2 class="project-title">Two-Person Recycled Lake Vessel</h2>
            <span class="tag">Fluid Dynamics</span><span class="tag">Structural Design</span><span class="tag">Prototyping</span>
            <p>Calculated buoyancy force and water displacement to design a functional two-person watercraft made from recycled materials[cite: 1]. Executed structural assembly and successfully navigated open water under dynamic loads[cite: 1].</p>
            <div class="grid">
                <div class="img-placeholder">[ Replace with Buoyancy Calculation Sheet ]</div>
                <div class="img-placeholder">[ Replace with Water Test Photo ]</div>
            </div>
        </div>

        <!-- Project 3 -->
        <div class="project-card">
            <h2 class="project-title">Calibrated Target Washer Launcher</h2>
            <span class="tag">SOLIDWORKS</span><span class="tag">Mechanical Testing</span><span class="tag">Data Analysis</span>
            <p>Engineered a free-standing launcher within rigid material constraints[cite: 1]. Executed iterative build-and-test trials to map spring tension against target distances ranging from 10 to 50 feet[cite: 1].</p>
            <div class="grid">
                <div class="img-placeholder">[ Replace with Excel Tension vs Distance Plot ]</div>
                <div class="img-placeholder">[ Replace with Launcher Assembly Photo ]</div>
            </div>
        </div>

    </div>

</body>
</html>
