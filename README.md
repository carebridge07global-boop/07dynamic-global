<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CareBridge'07 | Dynamic Global Ltd</title>
    <style>
        /* Premium Reset & Typography */
        * {margin:0;padding:0;box-sizing:border-box;font-family:'Helvetica Neue',Arial,sans-serif;scroll-behavior:smooth;}

        :root {
            --navy: #0A1931;
            --gold: #D4AF37;
            --green: #1B5E20;
            --white: #FFFFFF;
            --light-gray: #F5F5F5;
        }

        body {background-color: var(--white);color: #333;line-height: 1.6;}

        /* Header */
       .header {
            background-color: var(--navy);
            padding: 1.5rem 5%;
            display: flex;
            align-items: center;
            gap: 1.5rem;
            border-bottom: 3px solid var(--gold);
        }

       .logo-img {
            width: 80px;
            height: 80px;
            object-fit: contain;
        }

       .logo-text {
            color: var(--white);
        }

       .logo-text h1 {
            font-size: 2rem;
            font-weight: 700;
            letter-spacing: 1px;
        }

       .logo-text h1 span {
            color: var(--gold);
        }

       .logo-text.tagline {
            font-size: 0.85rem;
            color: var(--gold);
            text-transform: uppercase;
            letter-spacing: 2px;
            margin-top: 0.3rem;
        }

        /* Hero Section */
       .hero {
            background-color: var(--navy);
            color: var(--white);
            padding: 5rem 5%;
            text-align: center;
        }

       .hero-logo {
            width: 200px;
            margin: 0 auto 2rem;
        }

       .hero h2 {
            font-size: 3rem;
            font-weight: 800;
            line-height: 1.1;
            margin-bottom: 1rem;
        }

       .hero.subtitle {
            font-size: 1.8rem;
            font-weight: 300;
            color: var(--light-gray);
            margin-bottom: 2rem;
        }

       .values {
            display: flex;
            justify-content: center;
            gap: 3rem;
            margin: 3rem 0;
            flex-wrap: wrap;
        }

       .value-item {
            text-align: center;
            max-width: 200px;
        }

       .value-item h4 {
            color: var(--gold);
            margin-top: 0.5rem;
            font-size: 0.9rem;
            text-transform: uppercase;
        }

       .btn {
            display: inline-block;
            background-color: var(--gold);
            color: var(--navy);
            padding: 1rem 2.5rem;
            font-weight: 700;
            text-decoration: none;
            border-radius: 4px;
            transition: all 0.3s ease;
            margin-top: 1rem;
        }

       .btn:hover {background-color: var(--green);color: var(--white);}

        /* Hub Section */
       .hub {
            padding: 4rem 5%;
            max-width: 1200px;
            margin: 0 auto;
            text-align: center;
        }

       .hub h3 {
            font-size: 2.5rem;
            color: var(--navy);
            margin-bottom: 1rem;
        }

       .hub p {
            font-size: 1.1rem;
            margin-bottom: 2rem;
            max-width: 700px;
            margin-left: auto;
            margin-right: auto;
        }

        /* Footer */
       .footer {
            background-color: var(--navy);
            color: var(--white);
            text-align: center;
            padding: 2rem 5%;
            margin-top: 4rem;
        }

       .footer.tagline {
            color: var(--gold);
            font-size: 0.9rem;
            margin-bottom: 1rem;
        }

        @media (max-width: 768px) {
           .header {flex-direction: column;text-align: center;}
           .hero h2 {font-size: 2rem;}
           .hero.subtitle {font-size: 1.2rem;}
           .values {gap: 1.5rem;}
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header class="header">
        <img src="logo.png" alt="CareBridge'07 Logo" class="logo-img">
        <div class="logo-text">
            <h1>CAREBRIDGE<span>'07</span></h1>
            <div class="tagline">DYNAMIC GLOBAL LTD.</div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <img src="logo.png" alt="CareBridge'07" class="hero-logo">
        <h2>Transforming Human Dignity into Auditable</h2>
        <div class="subtitle">Care Governance Metrics</div>

        <div class="values">
            <div class="value-item">
                <h4>Dignity in Care</h4>
            </div>
            <div class="value-item">
                <h4>Community Empowerment</h4>
            </div>
            <div class="value-item">
                <h4>Sustainable Impact</h4>
            </div>
            <div class="value-item">
                <h4>Inclusive Futures</h4>
            </div>
        </div>

        <a href="#hub" class="btn">Access The Digital Hub</a>
    </section>

    <!-- Digital Hub Section -->
    <section class="hub" id="hub">
        <h3>The Care Governance Hub</h3>
        <p>
            Download frameworks, audit tools, and metrics from <em>The Care Governance Deficit</em> manuscript.
            Built for health systems, NGOs, and policymakers ready to measure what matters.
        </p>
        <p><strong>Coming Soon:</strong> Paid downloads, member portal, and certification tools.</p>
        <a href="#contact" class="btn">Join Waitlist</a>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="tagline">BRIDGING CARE. RESTORING DIGNITY. TRANSFORMING LIVES.</div>
        <p>&copy; 2026 CareBridge'07 Dynamic Global Ltd. All Rights Reserved.</p>
        <p>GitHub: @07-Dynamic-Global</p>
    </footer>
</body>
</html>
