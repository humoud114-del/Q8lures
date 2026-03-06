# Q8lures
Q8 Lures is a Kuwait-based fishing store offering high-quality lures, rods, reels, and fishing accessories. The store provides reliable gear for saltwater fishing in the Arabian Gulf, helping anglers get the best performance on every trip. 🎣
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Q8 LURES | Professional Fishing Gear</title>
    <style>
        :root {
            --primary-orange: #ff4500;
            --dark-bg: #121212;
            --card-bg: #1e1e1e;
            --text-light: #f4f4f4;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: var(--dark-bg);
            color: var(--text-light);
            margin: 0;
            padding: 0;
        }

        /* Navigation */
        nav {
            background: rgba(0,0,0,0.9);
            padding: 1rem 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky;
            top: 0;
            z-index: 1000;
            border-bottom: 2px solid var(--primary-orange);
        }

        .logo {
            font-size: 1.5rem;
            font-weight: bold;
            color: var(--primary-orange);
            text-transform: uppercase;
        }

        .nav-links a {
            color: white;
            text-decoration: none;
            margin-left: 20px;
            font-weight: 500;
        }

        /* Hero Section */
        .hero {
            height: 60vh;
            background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('https://images.unsplash.com/photo-1544551763-46a013bb70d5?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80');
            background-size: cover;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
        }

        .hero h1 { font-size: 3.5rem; margin-bottom: 10px; }
        .hero p { font-size: 1.2rem; color: #ccc; }

        /* Product Grid */
        .container {
            max-width: 1200px;
            margin: 50px auto;
            padding: 0 20px;
        }

        .section-title {
            text-align: center;
            margin-bottom: 40px;
            font-size: 2rem;
            border-bottom: 2px solid var(--primary-orange);
            display: inline-block;
            padding-bottom: 10px;
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }

        .product-card {
            background: var(--card-bg);
            border-radius: 10px;
            overflow: hidden;
            transition: transform 0.3s;
            border: 1px solid #333;
        }

        .product-card:hover {
            transform: translateY(-10px);
            border-color: var(--primary-orange);
        }

        .product-img {
            width: 100%;
            height: 250px;
            object-fit: cover;
            background: white; /* Contrast for equipment photos */
        }

        .product-info {
            padding: 20px;
        }

        .product-info h3 { margin: 0 0 10px 0; color: var(--primary-orange); }
        .product-info p { font-size: 0.9rem; color: #aaa; line-height: 1.4; }

        /* Contact Section */
        .contact {
            background: #000;
            padding: 60px 20px;
            text-align: center;
        }

        .insta-btn {
            background: linear-gradient(45deg, #f09433 0%, #e6683c 25%, #dc2743 50%, #cc2366 75%, #bc1888 100%);
            color: white;
            padding: 15px 30px;
            text-decoration: none;
            border-radius: 30px;
            font-weight: bold;
            display: inline-block;
            margin-top: 20px;
        }

        footer {
            text-align: center;
            padding: 20px;
            font-size: 0.8rem;
            color: #666;
        }
    </style>
</head>
<body>

    <nav>
        <div class="logo">Q8 Lures</div>
        <div class="nav-links">
            <a href="#">Home</a>
            <a href="#shop">Equipment</a>
            <a href="#contact">Contact</a>
        </div>
    </nav>

    <header class="hero">
        <h1>MASTER THE DEEP</h1>
        <p>Premium Offshore Jigging & Casting Gear</p>
    </header>

    <div class="container" id="shop">
        <center><h2 class="section-title">Featured Collections</h2></center>
        
        <div class="grid">
            <div class="product-card">
                <div class="product-info">
                    <h3>Q8 Professional Racks</h3>
                    <p>Modular, high-durability storage systems for the serious angler's collection.</p>
                </div>
            </div>

            <div class="product-card">
                <div class="product-info">
                    <h3>Asuka Samurai Series</h3>
                    <p>Extremely reliable offshore jigging rods. Featuring Fuji guides and Toray Carbon blanks.</p>
                </div>
            </div>

            <div class="product-card">
                <div class="product-info">
                    <h3>AVET LX 6.0 G2</h3>
                    <p>Precision engineered in the USA. The gold standard for lever drag performance.</p>
                </div>
            </div>

            <div class="product-card">
                <div class="product-info">
                    <h3>Zerek Origin - Pink Glow</h3>
                    <p>Innovative deep-water lures designed for maximum visibility and strike response.</p>
                </div>
            </div>

            <div class="product-card">
                <div class="product-info">
                    <h3>Italcanna Maracaibo</h3>
                    <p>Made in Italy. 50lb - 80lb powerhouse rods for the ultimate offshore battle.</p>
                </div>
            </div>

            <div class="product-card">
                <div class="product-info">
                    <h3>CNC Pole Handles</h3>
                    <p>Custom aircraft-grade aluminum handles for superior grip and torque.</p>
                </div>
            </div>
        </div>
    </div>

    <section class="contact" id="contact">
        <h2>Follow Our Journey</h2>
        <p>For orders and custom inquiries, reach out via Instagram</p>
        <a href="https://instagram.com/q8lures" class="insta-btn">@Q8LURES ON INSTAGRAM</a>
    </section>

    <footer>
        &copy; 2026 Q8 LURES. Designed for the Elite Angler.
    </footer>

</body>
</html>
