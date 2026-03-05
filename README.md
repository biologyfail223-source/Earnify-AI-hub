<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Earnify AI Hub - Best AI Tools, Online Earning Guides & Student Resources for Pakistan. Learn how to earn money online and access free study materials.">
    <meta name="keywords" content="AI Tools, Online Earning Pakistan, Student Resources, Freelancing, MDCAT Preparation, Earn Money Online">
    <meta name="author" content="Earnify AI Hub">
    <meta name="robots" content="index, follow">
    
    <!-- Open Graph / Social Media -->
    <meta property="og:title" content="Earnify AI Hub - AI Tools & Online Earning Pakistan">
    <meta property="og:description" content="Discover top AI tools, online earning methods, and student resources tailored for Pakistan.">
    <meta property="og:type" content="website">
    
    <title>Earnify AI Hub - AI Tools & Online Earning Pakistan</title>
    
    <!-- Google AdSense Script (Replace ca-pub-XXXXXXXXXXXXXXXX with your actual ID) -->
    <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-XXXXXXXXXXXXXXXX" crossorigin="anonymous"></script>
    
    <style>
        :root {
            --primary: #6366f1;
            --primary-dark: #4f46e5;
            --secondary: #ec4899;
            --accent: #8b5cf6;
            --dark: #0f172a;
            --darker: #020617;
            --glass: rgba(15, 23, 42, 0.7);
            --glass-border: rgba(255, 255, 255, 0.1);
            --text: #f8fafc;
            --text-muted: #94a3b8;
            --gradient-1: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            --gradient-2: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
            --gradient-3: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            font-family: 'Segoe UI', system-ui, -apple-system, sans-serif;
            background: var(--darker);
            color: var(--text);
            line-height: 1.6;
            overflow-x: hidden;
        }

        /* Custom Scrollbar */
        ::-webkit-scrollbar {
            width: 10px;
        }
        ::-webkit-scrollbar-track {
            background: var(--dark);
        }
        ::-webkit-scrollbar-thumb {
            background: var(--primary);
            border-radius: 5px;
        }

        /* Background Animation */
        .bg-animation {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
            background: 
                radial-gradient(circle at 20% 50%, rgba(120, 119, 198, 0.3) 0%, transparent 50%),
                radial-gradient(circle at 80% 80%, rgba(255, 119, 198, 0.3) 0%, transparent 50%),
                radial-gradient(circle at 40% 20%, rgba(120, 219, 255, 0.3) 0%, transparent 50%);
            filter: blur(80px);
            animation: bgMove 20s ease-in-out infinite;
        }

        @keyframes bgMove {
            0%, 100% { transform: translate(0, 0) scale(1); }
            33% { transform: translate(30px, -30px) scale(1.1); }
            66% { transform: translate(-20px, 20px) scale(0.9); }
        }

        /* Glassmorphism Utilities */
        .glass {
            background: var(--glass);
            backdrop-filter: blur(12px);
            -webkit-backdrop-filter: blur(12px);
            border: 1px solid var(--glass-border);
        }

        .glass-card {
            background: rgba(255, 255, 255, 0.05);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.1);
            border-radius: 16px;
            transition: all 0.3s ease;
        }

        .glass-card:hover {
            transform: translateY(-5px);
            background: rgba(255, 255, 255, 0.08);
            border-color: rgba(255, 255, 255, 0.2);
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.3);
        }

        /* Navigation */
        .navbar {
            position: sticky;
            top: 0;
            z-index: 1000;
            padding: 1rem 0;
            transition: all 0.3s ease;
        }

        .navbar.scrolled {
            background: rgba(15, 23, 42, 0.95);
            backdrop-filter: blur(20px);
            box-shadow: 0 4px 30px rgba(0, 0, 0, 0.3);
        }

        .nav-container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 2rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            font-size: 1.8rem;
            font-weight: 800;
            background: var(--gradient-1);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            text-decoration: none;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }

        .nav-links {
            display: flex;
            gap: 2rem;
            list-style: none;
        }

        .nav-links a {
            color: var(--text);
            text-decoration: none;
            font-weight: 500;
            position: relative;
            padding: 0.5rem 0;
            transition: color 0.3s;
        }

        .nav-links a::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            width: 0;
            height: 2px;
            background: var(--gradient-2);
            transition: width 0.3s;
        }

        .nav-links a:hover::after {
            width: 100%;
        }

        .mobile-menu {
            display: none;
            flex-direction: column;
            gap: 4px;
            cursor: pointer;
            z-index: 1001;
        }

        .mobile-menu span {
            width: 25px;
            height: 3px;
            background: var(--text);
            transition: 0.3s;
            border-radius: 3px;
        }

        /* Buttons */
        .btn {
            display: inline-flex;
            align-items: center;
            gap: 0.5rem;
            padding: 0.875rem 2rem;
            border-radius: 50px;
            font-weight: 600;
            text-decoration: none;
            border: none;
            cursor: pointer;
            transition: all 0.3s ease;
            position: relative;
            overflow: hidden;
        }

        .btn-primary {
            background: var(--gradient-1);
            color: white;
            box-shadow: 0 4px 15px rgba(102, 126, 234, 0.4);
        }

        .btn-primary:hover {
            transform: translateY(-2px);
            box-shadow: 0 8px 25px rgba(102, 126, 234, 0.6);
        }

        .btn-secondary {
            background: transparent;
            color: var(--text);
            border: 2px solid rgba(255, 255, 255, 0.2);
        }

        .btn-secondary:hover {
            background: rgba(255, 255, 255, 0.1);
            border-color: rgba(255, 255, 255, 0.4);
        }

        /* Container */
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 2rem;
        }

        /* Sections */
        .section {
            padding: 5rem 0;
            display: none;
        }

        .section.active {
            display: block;
            animation: fadeIn 0.5s ease;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .section-title {
            font-size: 2.5rem;
            margin-bottom: 1rem;
            text-align: center;
            background: linear-gradient(to right, #fff, #a5b4fc);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .section-subtitle {
            text-align: center;
            color: var(--text-muted);
            margin-bottom: 3rem;
            font-size: 1.1rem;
        }

        /* Hero Section */
        .hero {
            min-height: 90vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            padding: 2rem;
            position: relative;
            overflow: hidden;
        }

        .hero-content {
            max-width: 800px;
            z-index: 1;
        }

        .hero-badge {
            display: inline-block;
            padding: 0.5rem 1.5rem;
            background: rgba(99, 102, 241, 0.2);
            border: 1px solid rgba(99, 102, 241, 0.3);
            border-radius: 50px;
            color: #a5b4fc;
            font-size: 0.9rem;
            margin-bottom: 1.5rem;
            animation: pulse 2s infinite;
        }

        @keyframes pulse {
            0%, 100% { opacity: 1; }
            50% { opacity: 0.7; }
        }

        .hero h1 {
            font-size: clamp(2.5rem, 5vw, 4rem);
            font-weight: 800;
            line-height: 1.1;
            margin-bottom: 1.5rem;
            background: linear-gradient(135deg, #fff 0%, #c7d2fe 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .hero p {
            font-size: 1.25rem;
            color: var(--text-muted);
            margin-bottom: 2rem;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
        }

        .hero-buttons {
            display: flex;
            gap: 1rem;
            justify-content: center;
            flex-wrap: wrap;
        }

        /* Stats Counter */
        .stats {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 2rem;
            margin-top: 4rem;
        }

        .stat-card {
            text-align: center;
            padding: 2rem;
        }

        .stat-number {
            font-size: 2.5rem;
            font-weight: 800;
            background: var(--gradient-3);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            display: block;
        }

        .stat-label {
            color: var(--text-muted);
            font-size: 0.9rem;
            margin-top: 0.5rem;
        }

        /* Ad Placeholders */
        .ad-container {
            background: rgba(255, 255, 255, 0.03);
            border: 2px dashed rgba(255, 255, 255, 0.1);
            border-radius: 12px;
            padding: 2rem;
            text-align: center;
            margin: 2rem 0;
            color: var(--text-muted);
            font-size: 0.9rem;
        }

        .ad-label {
            display: block;
            font-size: 0.75rem;
            text-transform: uppercase;
            letter-spacing: 1px;
            margin-bottom: 0.5rem;
            color: #64748b;
        }

        /* Cards Grid */
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 2rem;
        }

        .card {
            padding: 2rem;
            position: relative;
            overflow: hidden;
        }

        .card-icon {
            width: 60px;
            height: 60px;
            border-radius: 12px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.5rem;
            margin-bottom: 1.5rem;
            background: var(--gradient-1);
        }

        .card h3 {
            font-size: 1.25rem;
            margin-bottom: 0.75rem;
            color: #fff;
        }

        .card p {
            color: var(--text-muted);
            font-size: 0.95rem;
            line-height: 1.6;
        }

        .card-tag {
            display: inline-block;
            padding: 0.25rem 0.75rem;
            background: rgba(99, 102, 241, 0.2);
            border-radius: 50px;
            font-size: 0.75rem;
            color: #a5b4fc;
            margin-top: 1rem;
            margin-right: 0.5rem;
        }

        .card-link {
            display: inline-flex;
            align-items: center;
            gap: 0.5rem;
            margin-top: 1.5rem;
            color: var(--primary);
            text-decoration: none;
            font-weight: 600;
            transition: gap 0.3s;
        }

        .card-link:hover {
            gap: 0.75rem;
        }

        /* Tools Page Specific */
        .tool-card {
            display: flex;
            flex-direction: column;
            height: 100%;
        }

        .tool-header {
            display: flex;
            align-items: center;
            gap: 1rem;
            margin-bottom: 1rem;
        }

        .tool-icon {
            width: 50px;
            height: 50px;
            border-radius: 12px;
            background: var(--gradient-2);
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.5rem;
        }

        .tool-category {
            font-size: 0.75rem;
            text-transform: uppercase;
            letter-spacing: 1px;
            color: var(--secondary);
            font-weight: 600;
        }

        /* Articles */
        .article-card {
            text-align: left;
        }

        .article-meta {
            display: flex;
            gap: 1rem;
            font-size: 0.85rem;
            color: var(--text-muted);
            margin-top: 1rem;
        }

        /* Resources */
        .resource-list {
            list-style: none;
        }

        .resource-item {
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 1.5rem;
            margin-bottom: 1rem;
            border-radius: 12px;
            transition: all 0.3s;
        }

        .resource-item:hover {
            background: rgba(255, 255, 255, 0.05);
            transform: translateX(10px);
        }

        .resource-info h4 {
            margin-bottom: 0.25rem;
            color: #fff;
        }

        .resource-info p {
            font-size: 0.9rem;
            color: var(--text-muted);
        }

        /* Contact Form */
        .contact-form {
            max-width: 600px;
            margin: 0 auto;
            padding: 3rem;
        }

        .form-group {
            margin-bottom: 1.5rem;
        }

        .form-group label {
            display: block;
            margin-bottom: 0.5rem;
            color: #cbd5e1;
            font-weight: 500;
        }

        .form-group input,
        .form-group textarea,
        .form-group select {
            width: 100%;
            padding: 1rem;
            background: rgba(255, 255, 255, 0.05);
            border: 1px solid rgba(255, 255, 255, 0.1);
            border-radius: 8px;
            color: #fff;
            font-size: 1rem;
            transition: all 0.3s;
        }

        .form-group input:focus,
        .form-group textarea:focus,
        .form-group select:focus {
            outline: none;
            border-color: var(--primary);
            background: rgba(255, 255, 255, 0.08);
        }

        .form-group textarea {
            resize: vertical;
            min-height: 150px;
        }

        .error-message {
            color: #ef4444;
            font-size: 0.85rem;
            margin-top: 0.25rem;
            display: none;
        }

        .error-message.show {
            display: block;
        }

        /* About Page */
        .about-hero {
            text-align: center;
            padding: 4rem 0;
        }

        .team-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            margin-top: 3rem;
        }

        .team-card {
            text-align: center;
            padding: 2rem;
        }

        .team-avatar {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            background: var(--gradient-1);
            margin: 0 auto 1rem;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 2rem;
        }

        /* Privacy Policy */
        .privacy-content {
            max-width: 800px;
            margin: 0 auto;
            line-height: 1.8;
        }

        .privacy-content h3 {
            color: #fff;
            margin-top: 2rem;
            margin-bottom: 1rem;
        }

        .privacy-content p {
            color: var(--text-muted);
            margin-bottom: 1rem;
        }

        /* Footer */
        .footer {
            background: rgba(2, 6, 23, 0.9);
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            padding: 4rem 0 2rem;
            margin-top: 4rem;
        }

        .footer-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 3rem;
            margin-bottom: 3rem;
        }

        .footer-brand h3 {
            font-size: 1.5rem;
            margin-bottom: 1rem;
            background: var(--gradient-1);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .footer-brand p {
            color: var(--text-muted);
            line-height: 1.6;
        }

        .footer-links h4 {
            color: #fff;
            margin-bottom: 1rem;
        }

        .footer-links ul {
            list-style: none;
        }

        .footer-links li {
            margin-bottom: 0.5rem;
        }

        .footer-links a {
            color: var(--text-muted);
            text-decoration: none;
            transition: color 0.3s;
        }

        .footer-links a:hover {
            color: var(--primary);
        }

        .social-links {
            display: flex;
            gap: 1rem;
            margin-top: 1.5rem;
        }

        .social-links a {
            width: 40px;
            height: 40px;
            border-radius: 50%;
            background: rgba(255, 255, 255, 0.05);
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--text);
            text-decoration: none;
            transition: all 0.3s;
            border: 1px solid rgba(255, 255, 255, 0.1);
        }

        .social-links a:hover {
            background: var(--primary);
            transform: translateY(-3px);
        }

        .footer-bottom {
            text-align: center;
            padding-top: 2rem;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            color: var(--text-muted);
            font-size: 0.9rem;
        }

        /* Scroll to Top */
        .scroll-top {
            position: fixed;
            bottom: 2rem;
            right: 2rem;
            width: 50px;
            height: 50px;
            border-radius: 50%;
            background: var(--gradient-1);
            color: white;
            border: none;
            cursor: pointer;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.2rem;
            opacity: 0;
            visibility: hidden;
            transition: all 0.3s;
            z-index: 999;
            box-shadow: 0 4px 15px rgba(102, 126, 234, 0.4);
        }

        .scroll-top.visible {
            opacity: 1;
            visibility: visible;
        }

        .scroll-top:hover {
            transform: translateY(-3px);
            box-shadow: 0 8px 25px rgba(102, 126, 234, 0.6);
        }

        /* Responsive */
        @media (max-width: 768px) {
            .nav-links {
                position: fixed;
                top: 0;
                right: -100%;
                width: 70%;
                height: 100vh;
                background: rgba(15, 23, 42, 0.98);
                flex-direction: column;
                padding: 5rem 2rem;
                transition: right 0.3s ease;
                backdrop-filter: blur(20px);
            }

            .nav-links.active {
                right: 0;
            }

            .mobile-menu {
                display: flex;
            }

            .hero h1 {
                font-size: 2.5rem;
            }

            .grid {
                grid-template-columns: 1fr;
            }

            .section {
                padding: 3rem 0;
            }
        }

        /* Loading Animation */
        .loader {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: var(--darker);
            display: flex;
            align-items: center;
            justify-content: center;
            z-index: 9999;
            transition: opacity 0.5s;
        }

        .loader.hidden {
            opacity: 0;
            pointer-events: none;
        }

        .loader-spinner {
            width: 50px;
            height: 50px;
            border: 3px solid rgba(255, 255, 255, 0.1);
            border-top-color: var(--primary);
            border-radius: 50%;
            animation: spin 1s linear infinite;
        }

        @keyframes spin {
            to { transform: rotate(360deg); }
        }
    </style>
</head>
<body>
    <!-- Background Animation -->
    <div class="bg-animation"></div>

    <!-- Loader -->
    <div class="loader" id="loader">
        <div class="loader-spinner"></div>
    </div>

    <!-- Navigation -->
    <nav class="navbar" id="navbar">
        <div class="nav-container">
            <a href="#" class="logo" onclick="showSection('home')">
                <span>⚡</span> Earnify AI Hub
            </a>
            <ul class="nav-links" id="navLinks">
                <li><a href="#" onclick="showSection('home')">Home</a></li>
                <li><a href="#" onclick="showSection('tools')">AI Tools</a></li>
                <li><a href="#" onclick="showSection('earning')">Earning Guide</a></li>
                <li><a href="#" onclick="showSection('resources')">Student Resources</a></li>
                <li><a href="#" onclick="showSection('about')">About</a></li>
                <li><a href="#" onclick="showSection('contact')">Contact</a></li>
            </ul>
            <div class="mobile-menu" id="mobileMenu" onclick="toggleMenu()">
                <span></span>
                <span></span>
                <span></span>
            </div>
        </div>
    </nav>

    <!-- AdSense Header Ad Placeholder -->
    <div class="container">
        <div class="ad-container">
            <span class="ad-label">Advertisement</span>
            <!-- AdSense Header Ad Code -->
            <!-- <ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-XXXXXXXXXXXXXXXX" data-ad-slot="XXXXXXXXXX" data-ad-format="auto" data-full-width-responsive="true"></ins> -->
            <p>Header Ad Space (728x90 or Responsive)</p>
        </div>
    </div>

    <!-- HOME PAGE -->
    <section id="home" class="section active">
        <div class="hero">
            <div class="hero-content">
                <div class="hero-badge">🚀 #1 Resource Hub for Pakistan Students</div>
                <h1>Master AI Tools & Start Earning Online Today</h1>
                <p>Discover the best AI tools, proven online earning strategies, and premium student resources tailored for Pakistan. Turn your skills into income.</p>
                <div class="hero-buttons">
                    <a href="#" class="btn btn-primary" onclick="showSection('tools')">
                        Explore AI Tools →
                    </a>
                    <a href="#" class="btn btn-secondary" onclick="showSection('earning')">
                        Start Earning Now
                    </a>
                </div>
                
                <div class="stats">
                    <div class="stat-card glass-card">
                        <span class="stat-number" data-target="50">0</span>
                        <div class="stat-label">AI Tools Listed</div>
                    </div>
                    <div class="stat-card glass-card">
                        <span class="stat-number" data-target="10000">0</span>
                        <div class="stat-label">Students Helped</div>
                    </div>
                    <div class="stat-card glass-card">
                        <span class="stat-number" data-target="500">0</span>
                        <div class="stat-label">Earning Guides</div>
                    </div>
                    <div class="stat-card glass-card">
                        <span class="stat-number" data-target="98">0</span>
                        <div class="stat-label">% Satisfaction</div>
                    </div>
                </div>
            </div>
        </div>

        <div class="container">
            <!-- Featured AI Tools -->
            <h2 class="section-title">Featured AI Tools</h2>
            <p class="section-subtitle">Boost your productivity with these cutting-edge AI tools</p>
            
            <div class="grid" id="featuredTools">
                <!-- Populated by JS -->
            </div>

            <!-- Sidebar Ad -->
            <div class="ad-container" style="margin: 4rem auto; max-width: 600px;">
                <span class="ad-label">Advertisement</span>
                <!-- <ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-XXXXXXXXXXXXXXXX" data-ad-slot="XXXXXXXXXX" data-ad-format="auto"></ins> -->
                <p>In-Article Ad Space (300x250 or Responsive)</p>
            </div>

            <!-- Trending Articles -->
            <h2 class="section-title" style="margin-top: 4rem;">Trending Earning Methods</h2>
            <p class="section-subtitle">Latest strategies to earn money online in Pakistan</p>
            
            <div class="grid" id="trendingArticles">
                <!-- Populated by JS -->
            </div>
        </div>
    </section>

    <!-- AI TOOLS PAGE -->
    <section id="tools" class="section">
        <div class="container" style="padding-top: 2rem;">
            <h1 class="section-title">AI Tools Directory</h1>
            <p class="section-subtitle">20+ Essential AI tools to supercharge your workflow</p>
            
            <div class="ad-container">
                <span class="ad-label">Advertisement</span>
                <p>Top Banner Ad Space</p>
            </div>

            <div class="grid" id="toolsGrid">
                <!-- Populated by JS -->
            </div>
        </div>
    </section>

    <!-- EARNING GUIDE PAGE -->
    <section id="earning" class="section">
        <div class="container" style="padding-top: 2rem;">
            <h1 class="section-title">Online Earning Guide</h1>
            <p class="section-subtitle">10 Proven ways to earn money online in Pakistan (2024-2025)</p>

            <div class="grid" id="earningGrid">
                <!-- Populated by JS -->
            </div>

            <!-- In-Article Ad -->
            <div class="ad-container" style="margin: 4rem auto;">
                <span class="ad-label">Advertisement</span>
                <p>Mid-Content Ad Space</p>
            </div>
        </div>
    </section>

    <!-- STUDENT RESOURCES PAGE -->
    <section id="resources" class="section">
        <div class="container" style="padding-top: 2rem;">
            <h1 class="section-title">Student Resources</h1>
            <p class="section-subtitle">Free notes, PDFs, and MCQs for Pakistani students</p>

            <div class="glass-card" style="padding: 2rem; margin-bottom: 3rem;">
                <h2 style="margin-bottom: 1.5rem; color: #fff;">📚 Study Materials</h2>
                <ul class="resource-list" id="resourceList">
                    <!-- Populated by JS -->
                </ul>
            </div>

            <div class="glass-card" style="padding: 2rem;">
                <h2 style="margin-bottom: 1.5rem; color: #fff;">📝 Entry Test Preparation (MDCAT/ECAT)</h2>
                <div class="grid" id="mcqGrid">
                    <!-- Populated by JS -->
                </div>
            </div>
        </div>
    </section>

    <!-- ABOUT PAGE -->
    <section id="about" class="section">
        <div class="container" style="padding-top: 2rem;">
            <div class="about-hero">
                <h1 class="section-title">About Earnify AI Hub</h1>
                <p class="section-subtitle" style="max-width: 700px; margin: 0 auto 3rem;">
                    Empowering Pakistani students with AI knowledge and online earning opportunities since 2024.
                </p>
            </div>

            <div class="glass-card" style="padding: 3rem; margin-bottom: 3rem;">
                <h3 style="color: #fff; margin-bottom: 1rem;">Our Mission</h3>
                <p style="color: var(--text-muted); line-height: 1.8;">
                    Earnify AI Hub is dedicated to bridging the gap between technology and income generation for students in Pakistan. 
                    We curate the best AI tools, provide actionable earning strategies, and offer free educational resources to help 
                    students become financially independent while pursuing their education.
                </p>
            </div>

            <h2 style="text-align: center; margin-bottom: 2rem; color: #fff;">Why Choose Us?</h2>
            <div class="grid">
                <div class="card glass-card">
                    <div class="card-icon">🎯</div>
                    <h3>Pakistan Focused</h3>
                    <p>All resources tailored specifically for Pakistani students and local market conditions.</p>
                </div>
                <div class="card glass-card">
                    <div class="card-icon">⚡</div>
                    <h3>Updated Daily</h3>
                    <p>We constantly update our AI tools list and earning methods to keep you ahead.</p>
                </div>
                <div class="card glass-card">
                    <div class="card-icon">🆓</div>
                    <h3>100% Free Resources</h3>
                    <p>All student resources and basic guides are completely free to access.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- CONTACT PAGE -->
    <section id="contact" class="section">
        <div class="container" style="padding-top: 2rem;">
            <h1 class="section-title">Contact Us</h1>
            <p class="section-subtitle">Have questions? We'd love to hear from you.</p>

            <form class="contact-form glass-card" id="contactForm" onsubmit="handleSubmit(event)">
                <div class="form-group">
                    <label for="name">Full Name *</label>
                    <input type="text" id="name" name="name" required>
                    <span class="error-message" id="nameError">Please enter your name</span>
                </div>

                <div class="form-group">
                    <label for="email">Email Address *</label>
                    <input type="email" id="email" name="email" required>
                    <span class="error-message" id="emailError">Please enter a valid email</span>
                </div>

                <div class="form-group">
                    <label for="subject">Subject *</label>
                    <select id="subject" name="subject" required>
                        <option value="">Select a subject</option>
                        <option value="general">General Inquiry</option>
                        <option value="tools">AI Tools Question</option>
                        <option value="earning">Earning Guide Help</option>
                        <option value="resources">Resource Request</option>
                        <option value="advertising">Advertising</option>
                    </select>
                    <span class="error-message" id="subjectError">Please select a subject</span>
                </div>

                <div class="form-group">
                    <label for="message">Message *</label>
                    <textarea id="message" name="message" required></textarea>
                    <span class="error-message" id="messageError">Please enter your message (min 10 characters)</span>
                </div>

                <button type="submit" class="btn btn-primary" style="width: 100%; justify-content: center;">
                    Send Message →
                </button>

                <div id="formSuccess" style="display: none; margin-top: 1rem; padding: 1rem; background: rgba(34, 197, 94, 0.2); border: 1px solid rgba(34, 197, 94, 0.3); border-radius: 8px; color: #86efac; text-align: center;">
                    ✅ Message sent successfully! We'll get back to you soon.
                </div>
            </form>
        </div>
    </section>

    <!-- PRIVACY POLICY PAGE -->
    <section id="privacy" class="section">
        <div class="container" style="padding-top: 2rem;">
            <h1 class="section-title">Privacy Policy</h1>
            <p style="text-align: center; color: var(--text-muted); margin-bottom: 3rem;">Last updated: March 2025</p>

            <div class="privacy-content glass-card" style="padding: 3rem;">
                <p>At Earnify AI Hub, we take your privacy seriously. This Privacy Policy describes how we collect, use, and protect your personal information when you use our website.</p>

                <h3>1. Information We Collect</h3>
                <p>We collect information you provide directly to us, such as when you fill out our contact form or subscribe to our newsletter. This may include your name, email address, and any messages you send us.</p>
                <p>We also automatically collect certain information about your device and how you interact with our website, including IP address, browser type, and pages visited.</p>

                <h3>2. Use of Google AdSense</h3>
                <p>We use Google AdSense to display advertisements on our website. Google may use cookies and web beacons to collect information about your visits to this and other websites to provide relevant advertisements.</p>
                <p>You can opt out of personalized advertising by visiting <a href="https://www.google.com/settings/ads" style="color: var(--primary);">Google Ads Settings</a>.</p>

                <h3>3. Cookies</h3>
                <p>We use cookies to enhance your browsing experience and analyze website traffic. You can control cookies through your browser settings.</p>

                <h3>4. Data Security</h3>
                <p>We implement appropriate security measures to protect your personal information. However, no method of transmission over the internet is 100% secure.</p>

                <h3>5. Third-Party Links</h3>
                <p>Our website may contain links to third-party websites. We are not responsible for the privacy practices of these external sites.</p>

                <h3>6. Contact Us</h3>
                <p>If you have any questions about this Privacy Policy, please contact us through our <a href="#" onclick="showSection('contact')" style="color: var(--primary);">Contact Page</a>.</p>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="container">
            <div class="footer-grid">
                <div class="footer-brand">
                    <h3>Earnify AI Hub</h3>
                    <p>Your trusted resource for AI tools, online earning guides, and student materials in Pakistan.</p>
                    <div class="social-links">
                        <a href="#" aria-label="Facebook">📘</a>
                        <a href="#" aria-label="Twitter">🐦</a>
                        <a href="#" aria-label="Instagram">📷</a>
                        <a href="#" aria-label="YouTube">▶️</a>
                        <a href="#" aria-label="LinkedIn">💼</a>
                    </div>
                </div>
                <div class="footer-links">
                    <h4>Quick Links</h4>
                    <ul>
                        <li><a href="#" onclick="showSection('home')">Home</a></li>
                        <li><a href="#" onclick="showSection('tools')">AI Tools</a></li>
                        <li><a href="#" onclick="showSection('earning')">Earning Guide</a></li>
                        <li><a href="#" onclick="showSection('resources')">Resources</a></li>
                    </ul>
                </div>
                <div class="footer-links">
                    <h4>Legal</h4>
                    <ul>
                        <li><a href="#" onclick="showSection('privacy')">Privacy Policy</a></li>
                        <li><a href="#" onclick="showSection('about')">About Us</a></li>
                        <li><a href="#" onclick="showSection('contact')">Contact</a></li>
                    </ul>
                </div>
                <div class="footer-links">
                    <h4>Contact Info</h4>
                    <ul>
                        <li>📧 info@earnifyaihub.com</li>
                        <li>📍 Karachi, Pakistan</li>
                        <li>🌐 www.earnifyaihub.com</li>
                    </ul>
                </div>
            </div>
            <div class="footer-bottom">
                <p>&copy; 2025 Earnify AI Hub. All rights reserved. | Designed for Pakistani Students 🇵🇰</p>
            </div>
        </div>
    </footer>

    <!-- Scroll to Top Button -->
    <button class="scroll-top" id="scrollTop" onclick="scrollToTop()">↑</button>

    <script>
        // Data Objects
        const aiTools = [
            { name: "ChatGPT", category: "Writing & Chat", icon: "💬", desc: "OpenAI's powerful conversational AI for writing, coding, and research.", color: "#10a37f" },
            { name: "Claude", category: "Writing & Analysis", icon: "🧠", desc: "Anthropic's AI assistant with superior reasoning and long-context capabilities.", color: "#cc785c" },
            { name: "Midjourney", category: "Image Generation", icon: "🎨", desc: "Create stunning AI-generated artwork and images from text prompts.", color: "#1a1a2e" },
            { name: "Grammarly", category: "Writing Assistant", icon: "✍️", desc: "AI-powered writing assistant for grammar, tone, and clarity improvements.", color: "#15c39a" },
            { name: "Canva AI", category: "Design", icon: "🖼️", desc: "Magic Studio features for AI-powered design, writing, and image editing.", color: "#00c4cc" },
            { name: "Jasper AI", category: "Marketing", icon: "📢", desc: "AI copywriting tool for marketing content, ads, and blog posts.", color: "#6366f1" },
            { name: "Copy.ai", category: "Copywriting", icon: "📝", desc: "Generate marketing copy, emails, and social media content instantly.", color: "#2563eb" },
            { name: "Synthesia", category: "Video Creation", icon: "🎥", desc: "Create AI videos with virtual avatars for training and marketing.", color: "#4f46e5" },
            { name: "Notion AI", category: "Productivity", icon: "📋", desc: "AI-powered notes, summaries, and workflow automation in Notion.", color: "#000000" },
            { name: "Perplexity", category: "Research", icon: "🔍", desc: "AI search engine providing cited answers to complex questions.", color: "#1e3a8a" },
            { name: "DALL-E 3", category: "Image Generation", icon: "🖌️", desc: "OpenAI's advanced image generation model integrated with ChatGPT.", color: "#10a37f" },
            { name: "GitHub Copilot", category: "Coding", icon: "💻", desc: "AI pair programmer that suggests code completions in real-time.", color: "#2d333b" },
            { name: "Runway ML", category: "Video Editing", icon: "🎬", desc: "AI-powered video editing and generation tools for creators.", color: "#ff6b6b" },
            { name: "Otter.ai", category: "Transcription", icon: "🎤", desc: "AI meeting assistant for transcription and note-taking.", color: "#f97316" },
            { name: "Zapier AI", category: "Automation", icon: "⚡", desc: "Automate workflows between apps using AI-powered integrations.", color: "#ff4a00" },
            { name: "Beautiful.ai", category: "Presentations", icon: "📊", desc: "AI-powered presentation software that designs slides automatically.", color: "#6366f1" },
            { name: "Lumen5", category: "Video Marketing", icon: "📹", desc: "Turn blog posts into engaging videos using AI.", color: "#3b82f6" },
            { name: "Surfer SEO", category: "SEO", icon: "📈", desc: "AI-driven SEO optimization tool for content ranking analysis.", color: "#059669" },
            { name: "Replit Ghostwriter", category: "Coding", icon: "👻", desc: "AI coding assistant built into the Replit online IDE.", color: "#f26207" },
            { name: "Fireflies", category: "Meetings", icon: "🔥", desc: "AI meeting recorder and conversation intelligence platform.", color: "#ef4444" }
        ];

        const earningArticles = [
            { 
                title: "Freelancing in Pakistan: Complete Beginner's Guide 2025", 
                category: "Freelancing", 
                desc: "Learn how to start freelancing on Fiverr, Upwork, and local platforms. Step-by-step guide to your first $1000.",
                readTime: "15 min read",
                date: "Mar 1, 2025"
            },
            { 
                title: "YouTube Automation Without Showing Your Face", 
                category: "Content Creation", 
                desc: "AI-powered faceless YouTube channels earning $5000+/month. Tools, niches, and monetization strategies.",
                readTime: "12 min read",
                date: "Feb 28, 2025"
            },
            { 
                title: "Print on Demand in Pakistan: T-Shirt Business Guide", 
                category: "E-commerce", 
                desc: "Start a print-on-demand business with zero investment using Canva and local suppliers.",
                readTime: "10 min read",
                date: "Feb 25, 2025"
            },
            { 
                title: "AI Prompt Engineering: High-Income Skill for Students", 
                category: "AI Skills", 
                desc: "Master the art of prompt engineering. Earn $50-100/hour working with international clients.",
                readTime: "8 min read",
                date: "Feb 20, 2025"
            },
            { 
                title: "Blogging for Pakistani Audience: AdSense & Beyond", 
                category: "Blogging", 
                desc: "How to start a blog in Urdu/English, get AdSense approval, and earn through affiliate marketing.",
                readTime: "20 min read",
                date: "Feb 15, 2025"
            },
            { 
                title: "Online Tutoring: Teach Pakistan Students Globally", 
                category: "Teaching", 
                desc: "Platforms like Preply, Udemy, and local tutoring sites. Subject selection and pricing strategies.",
                readTime: "11 min read",
                date: "Feb 10, 2025"
            },
            { 
                title: "Digital Marketing Agency for Local Businesses", 
                category: "Agency", 
                desc: "Start a social media marketing agency serving Pakistani SMEs. Low investment, high returns.",
                readTime: "14 min read",
                date: "Feb 5, 2025"
            },
            { 
                title: "Stock Trading & Crypto: Student Investment Guide", 
                category: "Investment", 
                desc: "Safe investment strategies for students. PSX, cryptocurrencies, and halal investment options.",
                readTime: "18 min read",
                date: "Jan 28, 2025"
            },
            { 
                title: "Transcription & Data Entry: Quick Start Earning", 
                category: "Micro Jobs", 
                desc: "Immediate income opportunities for students. Rev, TranscribeMe, and local data entry jobs.",
                readTime: "6 min read",
                date: "Jan 20, 2025"
            },
            { 
                title: "Mobile App Development with AI Tools", 
                category: "Tech", 
                desc: "Use no-code and AI coding tools to build apps. Monetization through ads and in-app purchases.",
                readTime: "16 min read",
                date: "Jan 15, 2025"
            }
        ];

        const resources = [
            { title: "FSC Pre-Medical Notes (Complete)", type: "PDF", size: "45 MB", subject: "Biology, Chemistry, Physics" },
            { title: "FSC Pre-Engineering Notes", type: "PDF", size: "38 MB", subject: "Math, Physics, Chemistry" },
            { title: "MDCAT Past Papers (2015-2024)", type: "PDF", size: "25 MB", subject: "Entry Test Prep" },
            { title: "ECAT Past Papers Collection", type: "PDF", size: "22 MB", subject: "Engineering Test" },
            { title: "SAT Preparation Material", type: "PDF", size: "30 MB", subject: "SAT I & II" },
            { title: "NTS Test Preparation Book", type: "PDF", size: "15 MB", subject: "General Aptitude" },
            { title: "CSS/PMS Past Papers", type: "PDF", size: "50 MB", subject: "Competitive Exams" },
            { title: "Cambridge O/A Level Notes", type: "PDF", size: "60 MB", subject: "Multiple Subjects" }
        ];

        const mcqSets = [
            { title: "MDCAT Biology MCQs (1000+)", questions: 1200, time: "Unlimited", difficulty: "Hard" },
            { title: "MDCAT Chemistry MCQs", questions: 800, time: "Unlimited", difficulty: "Medium" },
            { title: "MDCAT Physics MCQs", questions: 600, time: "Unlimited", difficulty: "Hard" },
            { title: "MDCAT English Practice", questions: 400, time: "Unlimited", difficulty: "Easy" },
            { title: "ECAT Mathematics MCQs", questions: 1000, time: "Unlimited", difficulty: "Hard" },
            { title: "NTS General Knowledge", questions: 500, time: "30 min", difficulty: "Medium" }
        ];

        // Initialization
        document.addEventListener('DOMContentLoaded', function() {
            // Hide loader
            setTimeout(() => {
                document.getElementById('loader').classList.add('hidden');
            }, 500);

            // Populate Featured Tools (Home)
            const featuredContainer = document.getElementById('featuredTools');
            aiTools.slice(0, 6).forEach(tool => {
                featuredContainer.innerHTML += createToolCard(tool);
            });

            // Populate All Tools
            const toolsContainer = document.getElementById('toolsGrid');
            aiTools.forEach(tool => {
                toolsContainer.innerHTML += createToolCard(tool, true);
            });

            // Populate Earning Articles
            const earningContainer = document.getElementById('earningGrid');
            earningArticles.forEach(article => {
                earningContainer.innerHTML += createArticleCard(article);
            });

            // Populate Trending Articles (Home)
            const trendingContainer = document.getElementById('trendingArticles');
            earningArticles.slice(0, 3).forEach(article => {
                trendingContainer.innerHTML += createArticleCard(article);
            });

            // Populate Resources
            const resourceContainer = document.getElementById('resourceList');
            resources.forEach(res => {
                resourceContainer.innerHTML += createResourceItem(res);
            });

            // Populate MCQs
            const mcqContainer = document.getElementById('mcqGrid');
            mcqSets.forEach(mcq => {
                mcqContainer.innerHTML += createMCQCard(mcq);
            });

            // Initialize counters
            animateCounters();

            // Scroll listener
            window.addEventListener('scroll', handleScroll);
        });

        // Helper Functions
        function createToolCard(tool, detailed = false) {
            return `
                <div class="card glass-card tool-card">
                    <div class="tool-header">
                        <div class="tool-icon" style="background: ${tool.color}20; color: ${tool.color}; border: 2px solid ${tool.color}40;">
                            ${tool.icon}
                        </div>
                        <div>
                            <div class="tool-category">${tool.category}</div>
                            <h3>${tool.name}</h3>
                        </div>
                    </div>
                    <p>${tool.desc}</p>
                    ${detailed ? `<a href="#" class="card-link" style="margin-top: auto;">Visit Tool →</a>` : `<span class="card-tag">Popular</span>`}
                </div>
            `;
        }

        function createArticleCard(article) {
            return `
                <div class="card glass-card article-card">
                    <span class="card-tag">${article.category}</span>
                    <h3 style="margin-top: 1rem; margin-bottom: 0.75rem;">${article.title}</h3>
                    <p>${article.desc}</p>
                    <div class="article-meta">
                        <span>📅 ${article.date}</span>
                        <span>⏱️ ${article.readTime}</span>
                    </div>
                    <a href="#" class="card-link">Read Article →</a>
                </div>
            `;
        }

        function createResourceItem(res) {
            return `
                <li class="resource-item glass-card">
                    <div class="resource-info">
                        <h4>${res.title}</h4>
                        <p>${res.subject} • ${res.size}</p>
                    </div>
                    <a href="#" class="btn btn-primary" style="padding: 0.5rem 1rem; font-size: 0.9rem;">Download ${res.type}</a>
                </li>
            `;
        }

        function createMCQCard(mcq) {
            return `
                <div class="card glass-card" style="text-align: center;">
                    <div style="font-size: 2rem; margin-bottom: 1rem;">📝</div>
                    <h3>${mcq.title}</h3>
                    <p style="margin: 1rem 0;">
                        <span class="card-tag">${mcq.questions} Questions</span>
                        <span class="card-tag">${mcq.time}</span>
                        <span class="card-tag">${mcq.difficulty}</span>
                    </p>
                    <a href="#" class="btn btn-secondary" style="width: 100%; margin-top: 1rem;">Start Practice</a>
                </div>
            `;
        }

        // Navigation
        function showSection(sectionId) {
            // Hide all sections
            document.querySelectorAll('.section').forEach(section => {
                section.classList.remove('active');
            });
            
            // Show target section
            document.getElementById(sectionId).classList.add('active');
            
            // Close mobile menu
            document.getElementById('navLinks').classList.remove('active');
            
            // Scroll to top
            window.scrollTo(0, 0);
            
            // Update URL hash
            window.location.hash = sectionId;
        }

        function toggleMenu() {
            document.getElementById('navLinks').classList.toggle('active');
        }

        // Handle initial hash
        if (window.location.hash) {
            const section = window.location.hash.substring(1);
            if (document.getElementById(section)) {
                setTimeout(() => showSection(section), 100);
            }
        }

        // Scroll Effects
        function handleScroll() {
            const navbar = document.getElementById('navbar');
            const scrollTop = document.getElementById('scrollTop');
            
            if (window.scrollY > 50) {
                navbar.classList.add('scrolled');
            } else {
                navbar.classList.remove('scrolled');
            }
            
            if (window.scrollY > 500) {
                scrollTop.classList.add('visible');
            } else {
                scrollTop.classList.remove('visible');
            }
        }

        function scrollToTop() {
            window.scrollTo({ top: 0, behavior: 'smooth' });
        }

        // Counter Animation
        function animateCounters() {
            const counters = document.querySelectorAll('.stat-number');
            
            const observer = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        const target = parseInt(entry.target.getAttribute('data-target'));
                        animateValue(entry.target, 0, target, 2000);
                        observer.unobserve(entry.target);
                    }
                });
            });
            
            counters.forEach(counter => observer.observe(counter));
        }

        function animateValue(obj, start, end, duration) {
            let startTimestamp = null;
            const step = (timestamp) => {
                if (!startTimestamp) startTimestamp = timestamp;
                const progress = Math.min((timestamp - startTimestamp) / duration, 1);
                obj.innerHTML = Math.floor(progress * (end - start) + start);
                if (progress < 1) {
                    window.requestAnimationFrame(step);
                } else {
                    obj.innerHTML = end + (end === 98 ? '%' : '+');
                }
            };
            window.requestAnimationFrame(step);
        }

        // Form Validation
        function handleSubmit(e) {
            e.preventDefault();
            
            const name = document.getElementById('name');
            const email = document.getElementById('email');
            const subject = document.getElementById('subject');
            const message = document.getElementById('message');
            let valid = true;
            
            // Reset errors
            document.querySelectorAll('.error-message').forEach(err => err.classList.remove('show'));
            
            // Validate name
            if (name.value.trim().length < 2) {
                document.getElementById('nameError').classList.add('show');
                valid = false;
            }
            
            // Validate email
            const emailRegex = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
            if (!emailRegex.test(email.value)) {
                document.getElementById('emailError').classList.add('show');
                valid = false;
            }
            
            // Validate subject
            if (!subject.value) {
                document.getElementById('subjectError').classList.add('show');
                valid = false;
            }
            
            // Validate message
            if (message.value.trim().length < 10) {
                document.getElementById('messageError').classList.add('show');
                valid = false;
            }
            
            if (valid) {
                // Simulate form submission
                const btn = e.target.querySelector('button[type="submit"]');
                const originalText = btn.innerHTML;
                btn.innerHTML = 'Sending...';
                btn.disabled = true;
                
                setTimeout(() => {
                    document.getElementById('formSuccess').style.display = 'block';
                    e.target.reset();
                    btn.innerHTML = originalText;
                    btn.disabled = false;
                    
                    setTimeout(() => {
                        document.getElementById('formSuccess').style.display = 'none';
                    }, 5000);
                }, 1500);
            }
        }

        // Close mobile menu when clicking outside
        document.addEventListener('click', function(e) {
            const navLinks = document.getElementById('navLinks');
            const mobileMenu = document.getElementById('mobileMenu');
            
            if (!navLinks.contains(e.target) && !mobileMenu.contains(e.target)) {
                navLinks.classList.remove('active');
            }
        });
    </script>
</body>
</html>
