# Matrix-hardware.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Matrix Hardware - Premium Building Materials & Tools</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #1a2a3a, #2c3e50, #34495e);
            color: #ecf0f1;
            line-height: 1.6;
            min-height: 100vh;
            background-attachment: fixed;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        
        header {
            text-align: center;
            padding: 40px 0;
            border-bottom: 2px solid #3498db;
            margin-bottom: 40px;
            background: rgba(0, 0, 0, 0.3);
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.5);
        }
        
        h1 {
            font-size: 3.5rem;
            margin-bottom: 15px;
            color: #3498db;
            text-shadow: 0 0 10px rgba(52, 152, 219, 0.7);
            letter-spacing: 2px;
        }
        
        .subtitle {
            font-size: 1.4rem;
            color: #bdc3c7;
            margin-bottom: 20px;
        }
        
        .contact-info {
            display: flex;
            justify-content: center;
            gap: 30px;
            margin-top: 20px;
            flex-wrap: wrap;
        }
        
        .contact-item {
            display: flex;
            align-items: center;
            gap: 10px;
            font-size: 1.1rem;
            background: rgba(52, 152, 219, 0.1);
            padding: 10px 20px;
            border-radius: 25px;
            border: 1px solid #3498db;
        }
        
        .contact-icon {
            color: #3498db;
            font-size: 1.3rem;
        }
        
        .products {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 30px;
            margin-bottom: 50px;
        }
        
        .product-card {
            background: rgba(0, 0, 0, 0.4);
            border-radius: 15px;
            overflow: hidden;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            box-shadow: 0 8px 25px rgba(0, 0, 0, 0.4);
            border: 1px solid rgba(52, 152, 219, 0.3);
        }
        
        .product-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.6);
        }
        
        .product-image {
            width: 100%;
            height: 220px;
            object-fit: cover;
            border-bottom: 3px solid #3498db;
        }
        
        .product-info {
            padding: 20px;
        }
        
        .product-name {
            font-size: 1.4rem;
            margin-bottom: 10px;
            color: #ecf0f1;
            font-weight: 600;
        }
        
        .product-price {
            font-size: 1.3rem;
            color: #2ecc71;
            font-weight: 700;
            margin-bottom: 15px;
        }
        
        .product-description {
            color: #bdc3c7;
            font-size: 0.95rem;
            line-height: 1.5;
        }
        
        .category-title {
            font-size: 2.2rem;
            color: #3498db;
            margin: 50px 0 30px 0;
            padding-bottom: 15px;
            border-bottom: 3px solid #3498db;
            text-align: center;
            position: relative;
        }
        
        .category-title::after {
            content: '';
            position: absolute;
            bottom: -3px;
            left: 50%;
            transform: translateX(-50%);
            width: 100px;
            height: 3px;
            background: #2ecc71;
        }
        
        .about-section {
            background: rgba(0, 0, 0, 0.4);
            padding: 40px;
            border-radius: 15px;
            margin: 60px 0;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.5);
            border: 1px solid rgba(52, 152, 219, 0.3);
        }
        
        .about-title {
            font-size: 2.5rem;
            color: #3498db;
            margin-bottom: 25px;
            text-align: center;
        }
        
        .about-content {
            font-size: 1.1rem;
            line-height: 1.8;
            color: #ecf0f1;
            text-align: justify;
        }
        
        .features {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }
        
        .feature {
            background: rgba(52, 152, 219, 0.1);
            padding: 20px;
            border-radius: 10px;
            border: 1px solid rgba(52, 152, 219, 0.3);
            text-align: center;
        }
        
        .feature-icon {
            font-size: 2.5rem;
            color: #3498db;
            margin-bottom: 15px;
        }
        
        .feature-title {
            font-size: 1.3rem;
            color: #ecf0f1;
            margin-bottom: 10px;
        }
        
        .feature-desc {
            font-size: 0.95rem;
            color: #bdc3c7;
        }
        
        footer {
            text-align: center;
            padding: 40px 0;
            margin-top: 60px;
            background: rgba(0, 0, 0, 0.5);
            border-top: 3px solid #3498db;
            border-radius: 15px;
            box-shadow: 0 -10px 30px rgba(0, 0, 0, 0.5);
        }
        
        .footer-title {
            font-size: 2rem;
            color: #3498db;
            margin-bottom: 20px;
        }
        
        .footer-contact {
            display: flex;
            justify-content: center;
            gap: 30px;
            margin: 20px 0;
            flex-wrap: wrap;
        }
        
        .footer-contact-item {
            display: flex;
            align-items: center;
            gap: 10px;
            font-size: 1.1rem;
        }
        
        .footer-contact-icon {
            color: #3498db;
            font-size: 1.3rem;
        }
        
        .copyright {
            margin-top: 30px;
            color: #bdc3c7;
            font-size: 0.9rem;
        }
        
        @media (max-width: 768px) {
            h1 {
                font-size: 2.5rem;
            }
            
            .subtitle {
                font-size: 1.1rem;
            }
            
            .products {
                grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            }
            
            .contact-info, .footer-contact {
                flex-direction: column;
                gap: 15px;
            }
            
            .about-section {
                padding: 25px;
            }
        }
        
        @media (max-width: 480px) {
            h1 {
                font-size: 2rem;
            }
            
            .container {
                padding: 15px;
            }
            
            .products {
                grid-template-columns: 1fr;
            }
        }
        
        /* Animation for the header */
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        
        header {
            animation: fadeIn 1s ease-out;
        }
        
        .product-card {
            animation: fadeIn 1s ease-out;
            animation-delay: 0.2s;
            opacity: 0;
            animation-fill-mode: forwards;
        }
        
        .product-card:nth-child(2) { animation-delay: 0.3s; }
        .product-card:nth-child(3) { animation-delay: 0.4s; }
        .product-card:nth-child(4) { animation-delay: 0.5s; }
        .product-card:nth-child(5) { animation-delay: 0.6s; }
        .product-card:nth-child(6) { animation-delay: 0.7s; }
        .product-card:nth-child(7) { animation-delay: 0.8s; }
        .product-card:nth-child(8) { animation-delay: 0.9s; }
        .product-card:nth-child(9) { animation-delay: 1s; }
        .product-card:nth-child(10) { animation-delay: 1.1s; }
        .product-card:nth-child(11) { animation-delay: 1.2s; }
        .product-card:nth-child(12) { animation-delay: 1.3s; }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>MATRIX HARDWARE</h1>
            <p class="subtitle">Your Trusted Partner for Quality Building Materials & Tools</p>
            <div class="contact-info">
                <div class="contact-item">
                    <span class="contact-icon">📧</span>
                    <span>ajoamko@yahoo.com</span>
                </div>
                <div class="contact-item">
                    <span class="contact-icon">📱</span>
                    <span>0652717647</span>
                </div>
            </div>
        </header>

        <h2 class="category-title">CONSTRUCTION MATERIALS</h2>
        <div class="products">
            <div class="product-card">
                <img src="https://placehold.co/300x220/3498db/ffffff?text=Cement+50kg" alt="Cement 50kg" class="product-image">
                <div class="product-info">
                    <h3 class="product-name">Premium Cement (50kg)</h3>
                    <p class="product-price">Tsh 15,000/-</p>
                    <p class="product-description">High-quality Portland cement perfect for all construction needs. Durable and reliable for foundations, walls, and concrete work.</p>
                </div>
            </div>
            
            <div class="product-card">
                <img src="https://placehold.co/300x220/e74c3c/ffffff?text=Steel+Bars" alt="Steel Bars" class="product-image">
                <div class="product-info">
                    <h3 class="product-name">Reinforcement Steel Bars</h3>
                    <p class="product-price">Tsh 18,000/m</p>
                    <p class="product-description">High-tensile steel bars for reinforced concrete structures. Available in various diameters for different construction requirements.</p>
                </div>
            </div>
            
            <div class="product-card">
                <img src="https://placehold.co/300x220/2ecc71/ffffff?text=Sand" alt="Construction Sand" class="product-image">
                <div class="product-info">
                    <h3 class="product-name">Washed River Sand</h3>
                    <p class="product-price">Tsh 80,000/truck</p>
                    <p class="product-description">Clean, washed river sand ideal for concrete mixing, plastering, and masonry work. Delivered in bulk quantities.</p>
                </div>
            </div>
            
            <div class="product-card">
                <img src="https://placehold.co/300x220/f39c12/ffffff?text=Aggregates" alt="Construction Aggregates" class="product-image">
                <div class="product-info">
                    <h3 class="product-name">Crushed Stone Aggregates</h3>
                    <p class="product-price">Tsh 95,000/truck</p>
                    <p class="product-description">Quality crushed stone for concrete production, road base, and drainage applications. Various sizes available.</p>
                </div>
            </div>
            
            <div class="product-card">
                <img src="https://placehold.co/300x220/9b59b6/ffffff?text=Bricks" alt="Bricks" class="product-image">
                <div class="product-info">
                    <h3 class="product-name">Burnt Clay Bricks</h3>
                    <p class="product-price">Tsh 600/each</p>
                    <p class="product-description">Durable burnt clay bricks for wall construction. Consistent quality with excellent compressive strength.</p>
                </div>
            </div>
            
            <div class="product-card">
                <img src="https://placehold.co/300x220/16a085/ffffff?text=Roof+Tiles" alt="Roof Tiles" class="product-image">
                <div class="product-info">
                    <h3 class="product-name">Concrete Roof Tiles</h3>
                    <p class="product-price">Tsh 3,500/each</p>
                    <p class="product-description">Weather-resistant concrete roof tiles with excellent durability. Available in various colors and styles.</p>
                </div>
            </div>
        </div>

        <h2 class="category-title">TOOLS & EQUIPMENT</h2>
        <div class="products">
            <div class="product-card">
                <img src="https://placehold.co/300x220/34495e/ffffff?text=Power+Drill" alt="Power Drill" class="product-image">
                <div class="product-info">
                    <h3 class="product-name">Heavy Duty Power Drill</h3>
                    <p class="product-price">Tsh 180,000/-</p>
                    <p class="product-description">Professional-grade power drill with variable speed and hammer function. Perfect for concrete, wood, and metal drilling.</p>
                </div>
            </div>
            
            <div class="product-card">
                <img src="https://placehold.co/300x220/2c3e50/ffffff?text=Angle+Grinder" alt="Angle Grinder" class="product-image">
                <div class="product-info">
                    <h3 class="product-name">Angle Grinder 4.5"</h3>
                    <p class="product-price">Tsh 165,000/-</p>
                    <p class="product-description">High-performance angle grinder for cutting, grinding, and polishing metal and masonry surfaces.</p>
                </div>
            </div>
            
            <div class="product-card">
                <img src="https://placehold.co/300x220/7f8c8d/ffffff?text=Hammer" alt="Construction Hammer" class="product-image">
                <div class="product-info">
                    <h3 class="product-name">Framing Hammer 20oz</h3>
                    <p class="product-price">Tsh 28,000/-</p>
                    <p class="product-description">Professional framing hammer with fiberglass handle and magnetic nail starter. Ideal for carpentry and general construction.</p>
                </div>
            </div>
            
            <div class="product-card">
                <img src="https://placehold.co/300x220/c0392b/ffffff?text=Levels" alt="Spirit Levels" class="product-image">
                <div class="product-info">
                    <h3 class="product-name">Laser Level Set</h3>
                    <p class="product-price">Tsh 220,000/-</p>
                    <p class="product-description">Precision laser level with tripod for accurate horizontal and vertical alignment in construction projects.</p>
                </div>
            </div>
            
            <div class="product-card">
                <img src="https://placehold.co/300x220/d35400/ffffff?text=Tool+Kit" alt="Tool Kit" class="product-image">
                <div class="product-info">
                    <h3 class="product-name">Complete Tool Kit</h3>
                    <p class="product-price">Tsh 350,000/-</p>
                    <p class="product-description">Comprehensive tool kit including wrenches, screwdrivers, pliers, and other essential tools for construction work.</p>
                </div>
            </div>
            
            <div class="product-card">
                <img src="https://placehold.co/300x220/27ae60/ffffff?text=Generator" alt="Portable Generator" class="product-image">
                <div class="product-info">
                    <h3 class="product-name">Portable Generator 5kVA</h3>
                    <p class="product-price">Tsh 1,200,000/-</p>
                    <p class="product-description">Reliable portable generator for construction sites, providing consistent power for tools and equipment.</p>
                </div>
            </div>
        </div>

        <h2 class="category-title">PLUMBING & ELECTRICAL</h2>
        <div class="products">
            <div class="product-card">
                <img src="https://placehold.co/300x220/8e44ad/ffffff?text=PVC+Pipes" alt="PVC Pipes" class="product-image">
                <div class="product-info">
                    <h3 class="product-name">PVC Pipes & Fittings</h3>
                    <p class="product-price">Tsh 12,000/m</p>
                    <p class="product-description">High-quality PVC pipes and fittings for plumbing systems. Resistant to corrosion and suitable for water supply.</p>
                </div>
            </div>
            
            <div class="product-card">
                <img src="https://placehold.co/300x220/16a085/ffffff?text=Copper+Wire" alt="Electrical Wire" class="product-image">
                <div class="product-info">
                    <h3 class="product-name">Copper Electrical Wire</h3>
                    <p class="product-price">Tsh 8,500/m</p>
                    <p class="product-description">High-conductivity copper wire for electrical installations. Available in various gauges for different applications.</p>
                </div>
            </div>
            
            <div class="product-card">
                <img src="https://placehold.co/300x220/f1c40f/ffffff?text=Switches" alt="Electrical Switches" class="product-image">
                <div class="product-info">
                    <h3 class="product-name">Electrical Switches & Sockets</h3>
                    <p class="product-price">Tsh 15,000/-</p>
                    <p class="product-description">Premium switches and sockets with safety features. Modern design for residential and commercial installations.</p>
                </div>
            </div>
            
            <div class="product-card">
                <img src="https://placehold.co/300x220/e67e22/ffffff?text=Water+Tanks" alt="Water Tanks" class="product-image">
                <div class="product-info">
                    <h3 class="product-name">Plastic Water Tanks</h3>
                    <p class="product-price">Tsh 320,000/1000L</p>
                    <p class="product-description">UV-resistant plastic water tanks in various capacities. Ideal for rainwater harvesting and water storage.</p>
                </div>
            </div>
        </div>

        <div class="about-section">
            <h2 class="about-title">ABOUT MATRIX HARDWARE</h2>
            <p class="about-content">Matrix Hardware is a leading supplier of premium building materials, tools, and equipment in Tanzania. With over 15 years of experience in the construction industry, we have built a reputation for providing high-quality products at competitive prices. Our commitment to excellence and customer satisfaction has made us the preferred choice for contractors, builders, and DIY enthusiasts across the region.</p>
            
            <p class="about-content" style="margin-top: 15px;">We source our products from trusted manufacturers and subject them to rigorous quality control to ensure they meet the highest industry standards. Our knowledgeable staff is always available to provide expert advice and help you find the right solutions for your construction needs.</p>
            
            <p class="about-content" style="margin-top: 15px;">At Matrix Hardware, we believe in building strong relationships with our customers. Whether you're working on a small home improvement project or a large-scale construction development, we have the products and expertise to support your success. We offer delivery services, bulk discounts, and personalized customer service to make your experience with us seamless and satisfying.</p>
            
            <div class="features">
                <div class="feature">
                    <div class="feature-icon">🏆</div>
                    <h3 class="feature-title">Quality Assurance</h3>
                    <p class="feature-desc">All our products undergo strict quality control to ensure durability and performance.</p>
                </div>
                
                <div class="feature">
                    <div class="feature-icon">🚚</div>
                    <h3 class="feature-title">Fast Delivery</h3>
                    <p class="feature-desc">We offer reliable delivery services to ensure your materials arrive on time.</p>
                </div>
                
                <div class="feature">
                    <div class="feature-icon">💰</div>
                    <h3 class="feature-title">Competitive Prices</h3>
                    <p class="feature-desc">Our bulk purchasing power allows us to offer the best prices in the market.</p>
                </div>
                
                <div class="feature">
                    <div class="feature-icon">👨‍🔧</div>
                    <h3 class="feature-title">Expert Advice</h3>
                    <p class="feature-desc">Our experienced staff provides professional guidance for all your construction needs.</p>
                </div>
            </div>
        </div>

        <footer>
            <h2 class="footer-title">MATRIX HARDWARE</h2>
            <p>Your Partner in Building Excellence</p>
            
            <div class="footer-contact">
                <div class="footer-contact-item">
                    <span class="footer-contact-icon">📧</span>
                    <span>ajoamko@yahoo.com</span>
                </div>
                <div class="footer-contact-item">
                    <span class="footer-contact-icon">📱</span>
                    <span>0652717647</span>
                </div>
            </div>
            
            <p class="copyright">© 2023 Matrix Hardware. All rights reserved. Premium Building Materials & Tools Supplier.</p>
        </footer>
    </div>
</body>
</html>
