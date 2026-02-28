<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aura | Strategy-Led Digital Growth Agency</title>
    <meta name="description" content="We combine data-driven strategy with premium design and engineering to accelerate your digital growth.">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@300;400;600;800&family=Inter:wght@400;500&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="cursor-glow"></div>
    <header class="header">
        <div class="logo">AURA<span>.</span></div>
        <nav class="nav">
            <a href="#services">Services</a>
            <a href="#work">Case Studies</a>
            <a href="#about">Philosophy</a>
        </nav>
        <a href="#contact" class="btn btn-primary">Start a Project</a>
    </header>

    <main>
        <section class="hero">
            <div class="hero-content">
                <div class="badge">Strategy-Led Agency</div>
                <h1 class="hero-title">We engineer <span class="gradient-text">digital growth</span>.</h1>
                <p class="hero-subtitle">We don't just build beautiful digital experiences. We orchestrate data-driven strategies that scale your business, elevate your brand, and dominate the market.</p>
                <div class="hero-cta">
                    <a href="#services" class="btn btn-primary btn-large">Explore Capabilities</a>
                    <a href="#work" class="btn btn-secondary btn-large">View Case Studies</a>
                </div>
            </div>
            <div class="hero-visual">
                <div class="orb orb-1"></div>
                <div class="orb orb-2"></div>
                <div class="glass-panel">
                    <div class="metric">
                        <span class="metric-value">+240%</span>
                        <span class="metric-label">Average ROI</span>
                    </div>
                    <div class="metric">
                        <span class="metric-value">120+</span>
                        <span class="metric-label">Projects Delivered</span>
                    </div>
                </div>
            </div>
        </section>

        <section class="ticker">
            <div class="ticker-wrapper">
                <div class="ticker-content">
                    <span>STRATEGY</span> • <span>ECOMMERCE</span> • <span>PRODUCT DESIGN</span> • <span>WEB DEVELOPMENT</span> • <span>GROWTH MARKETING</span> • <span>BRAND IDENTITY</span> • 
                </div>
                <div class="ticker-content">
                    <span>STRATEGY</span> • <span>ECOMMERCE</span> • <span>PRODUCT DESIGN</span> • <span>WEB DEVELOPMENT</span> • <span>GROWTH MARKETING</span> • <span>BRAND IDENTITY</span> • 
                </div>
            </div>
        </section>

        <section id="services" class="services">
            <div class="section-header">
                <h2>Our Ecosystem</h2>
                <p>An integrated approach to digital dominance.</p>
            </div>
            <div class="service-grid">
                <div class="service-card">
                    <div class="card-icon">🎯</div>
                    <h3>Growth Strategy</h3>
                    <p>Data-backed roadmaps designed to capture market share and maximize your digital ROI.</p>
                </div>
                <div class="service-card">
                    <div class="card-icon">✨</div>
                    <h3>Experience Design</h3>
                    <p>Premium, user-centric interfaces that engage users and elevate your brand perception.</p>
                </div>
                <div class="service-card">
                    <div class="card-icon">⚡</div>
                    <h3>Performance Engineering</h3>
                    <p>Robust, scalable architectures built for speed, security, and seamless integration.</p>
                </div>
                <div class="service-card">
                    <div class="card-icon">📈</div>
                    <h3>Activation & Scaling</h3>
                    <p>Targeted campaigns and conversion rate optimization to turn traffic into revenue.</p>
                </div>
            </div>
        </section>
        
        <section class="cta-section">
            <div class="cta-container glass-panel">
                <h2>Ready to accelerate?</h2>
                <p>Partner with a team that treats your growth like their own.</p>
                <a href="#contact" class="btn btn-primary btn-large cta-btn">Schedule a Discovery Call</a>
            </div>
        </section>
    </main>

    <footer class="footer">
        <div class="footer-top">
            <div class="footer-brand">
                <div class="logo">AURA<span>.</span></div>
                <p>Strategy-first digital product & growth agency.</p>
            </div>
            <div class="footer-links">
                <div class="link-group">
                    <h4>Company</h4>
                    <a href="#">About</a>
                    <a href="#">Careers</a>
                    <a href="#">Contact</a>
                </div>
                <div class="link-group">
                    <h4>Social</h4>
                    <a href="#">Twitter</a>
                    <a href="#">LinkedIn</a>
                    <a href="#">Instagram</a>
                export const config = {
  runtime: 'edge',
};

export default function handler(request) {
  return new Response(
    JSON.stringify({
      message: 'Hello from the Edge!',
      timestamp: new Date().toISOString()
    }),
    {
      status: 200,
      headers: {
        'content-type': 'application/json',
        'Cache-Control': 's-maxage=86400'
      },
    }
  );
}


                </div>
            </div>
        </div>
        <div class="footer-bottom">
            <p>&copy; 2026 Aura Digital. All rights reserved.</p>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>

