<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>AFX Global - Transforming Ideas into Digital Success</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  <style>
    html { scroll-behavior: smooth; }
    /* Floating WhatsApp Button */
    .whatsapp-float {
      position: fixed;
      bottom: 20px;
      right: 20px;
      z-index: 100;
    }
    .whatsapp-float a {
      display: flex;
      align-items: center;
      justify-content: center;
      width: 55px;
      height: 55px;
      border-radius: 50%;
      background: #25D366;
      color: white;
      font-size: 28px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.3);
      margin-bottom: 10px;
      transition: transform 0.2s ease-in-out;
    }
    .whatsapp-float a:hover {
      transform: scale(1.1);
      background: #20b954;
    }
  </style>
</head>
<body class="font-sans text-gray-800">

  <!-- Navbar -->
  <header class="fixed w-full bg-white shadow z-50">
    <div class="container mx-auto flex justify-between items-center py-4 px-6">
      <h1 class="text-2xl font-bold text-blue-600">🌐 AFX Global</h1>
      <nav class="hidden md:flex">
        <ul class="flex space-x-6 font-medium">
          <li><a href="#services" class="hover:text-blue-600">Services</a></li>
          <li><a href="#industries" class="hover:text-blue-600">Industries</a></li>
          <li><a href="#process" class="hover:text-blue-600">Process</a></li>
          <li><a href="#aftersales" class="hover:text-blue-600">After-Sales</a></li>
          <li><a href="#leadership" class="hover:text-blue-600">Leadership</a></li>
          <li><a href="#contact" class="hover:text-blue-600">Contact</a></li>
        </ul>
      </nav>
      <button id="menu-btn" class="md:hidden text-2xl text-blue-600">
        <i class="fa-solid fa-bars"></i>
      </button>
    </div>

    <!-- Mobile Dropdown -->
    <nav id="mobile-menu" class="hidden md:hidden bg-white shadow px-6 py-4">
      <ul class="flex flex-col space-y-4 font-medium">
        <li><a href="#services" class="hover:text-blue-600">Services</a></li>
        <li><a href="#industries" class="hover:text-blue-600">Industries</a></li>
        <li><a href="#process" class="hover:text-blue-600">Process</a></li>
        <li><a href="#aftersales" class="hover:text-blue-600">After-Sales</a></li>
        <li><a href="#leadership" class="hover:text-blue-600">Leadership</a></li>
        <li><a href="#contact" class="hover:text-blue-600">Contact</a></li>
      </ul>
    </nav>
  </header>

  <!-- Hero Section -->
  <section class="relative bg-gradient-to-r from-blue-600 to-indigo-700 text-white text-center h-screen flex flex-col justify-center items-center px-6">
    <div class="absolute inset-0 bg-black bg-opacity-30"></div>
    <div class="relative z-10">
      <h2 class="text-4xl md:text-6xl font-bold mb-4">Smart Strategies. Powerful Results.</h2>
      <p class="text-lg md:text-2xl italic mb-8">Transforming Ideas into Digital Success.</p>
      <a href="#contact" class="bg-yellow-400 text-black px-6 py-3 rounded-lg font-semibold hover:bg-yellow-300 transition">Get Started</a>
    </div>
  </section>

  <!-- Executive Summary -->
  <section class="py-20 container mx-auto px-6 text-center">
    <h2 class="text-3xl font-bold mb-6">💡 Executive Summary</h2>
    <p class="max-w-3xl mx-auto leading-relaxed">
      AFX Global is a forward-thinking digital solutions agency combining <strong>innovation and technology</strong> with business expertise. 
      Whether you are starting a company in the <strong>USA, UK, UAE, or Pakistan</strong>, building your digital brand, 
      or scaling your online presence — we provide everything under one roof.
    </p>
  </section>

  <!-- Services -->
  <section id="services" class="bg-gray-50 py-20">
    <h2 class="text-3xl font-bold text-center mb-12">🚀 Our Core Services</h2>
    <div class="grid md:grid-cols-3 gap-8 container mx-auto px-6">
      <div class="bg-white p-6 rounded-xl shadow hover:shadow-xl transform hover:-translate-y-1 transition">
        <i class="fa-solid fa-laptop-code text-3xl text-blue-600 mb-4"></i>
        <h3 class="font-semibold text-xl mb-2">Website Design & Development</h3>
        <p>Responsive websites, secure hosting, e-commerce solutions.</p>
      </div>
      <div class="bg-white p-6 rounded-xl shadow hover:shadow-xl transform hover:-translate-y-1 transition">
        <i class="fa-solid fa-building text-3xl text-blue-600 mb-4"></i>
        <h3 class="font-semibold text-xl mb-2">Business Formation</h3>
        <p>Company registration in USA, UK, UAE, Pakistan with compliance support.</p>
      </div>
      <div class="bg-white p-6 rounded-xl shadow hover:shadow-xl transform hover:-translate-y-1 transition text-center">
        <div class="flex space-x-3 text-3xl text-blue-600 mb-4 justify-center">
          <i class="fa-brands fa-facebook"></i>
          <i class="fa-brands fa-instagram"></i>
          <i class="fa-brands fa-youtube"></i>
          <i class="fa-brands fa-tiktok"></i>
          <i class="fa-brands fa-x-twitter"></i>
          <i class="fa-brands fa-linkedin"></i>
        </div>
        <h3 class="font-semibold text-xl mb-2">Social Media Management</h3>
        <p>Content creation, ad campaigns, and growth across top platforms.</p>
      </div>
      <div class="bg-white p-6 rounded-xl shadow hover:shadow-xl transform hover:-translate-y-1 transition">
        <i class="fa-solid fa-store text-3xl text-blue-600 mb-4"></i>
        <h3 class="font-semibold text-xl mb-2">E-Commerce Setup</h3>
        <p>Shopify, WooCommerce, Amazon & Daraz integration.</p>
      </div>
      <div class="bg-white p-6 rounded-xl shadow hover:shadow-xl transform hover:-translate-y-1 transition">
        <i class="fa-solid fa-chart-line text-3xl text-blue-600 mb-4"></i>
        <h3 class="font-semibold text-xl mb-2">SEO & Digital Marketing</h3>
        <p>SEO optimization, Google Ads, Meta Ads, lead generation.</p>
      </div>
      <div class="bg-white p-6 rounded-xl shadow hover:shadow-xl transform hover:-translate-y-1 transition">
        <i class="fa-solid fa-paintbrush text-3xl text-blue-600 mb-4"></i>
        <h3 class="font-semibold text-xl mb-2">Branding & Design</h3>
        <p>Logos, brand identity, and marketing collaterals.</p>
      </div>
    </div>
  </section>

  <!-- Industries -->
  <section id="industries" class="py-20 container mx-auto px-6 text-center">
    <h2 class="text-3xl font-bold mb-12">🎯 Industries We Serve</h2>
    <div class="grid md:grid-cols-4 gap-6">
      <div class="bg-blue-50 p-6 rounded-xl shadow hover:shadow-md">🏠 Real Estate</div>
      <div class="bg-blue-50 p-6 rounded-xl shadow hover:shadow-md">🛒 Retail & E-Commerce</div>
      <div class="bg-blue-50 p-6 rounded-xl shadow hover:shadow-md">🚀 Startups</div>
      <div class="bg-blue-50 p-6 rounded-xl shadow hover:shadow-md">💻 Tech & SaaS</div>
    </div>
  </section>

  <!-- Process -->
  <section id="process" class="bg-gray-50 py-20">
    <div class="container mx-auto text-center">
      <h2 class="text-3xl font-bold mb-12">🛠️ Our Process</h2>
      <div class="relative max-w-5xl mx-auto">
        <div class="border-l-4 border-blue-600 ml-4">
          <div class="mb-10 ml-6">
            <h3 class="text-xl font-bold text-blue-600">1️⃣ Discovery</h3>
            <p class="text-gray-700">We listen to your needs, goals, and challenges. Our team gathers insights and conducts market research to lay the foundation of your digital journey.</p>
          </div>
          <div class="mb-10 ml-6">
            <h3 class="text-xl font-bold text-blue-600">2️⃣ Strategy</h3>
            <p class="text-gray-700">We craft a clear roadmap with KPIs, timelines, and growth tactics to ensure every step aligns with your business objectives.</p>
          </div>
          <div class="mb-10 ml-6">
            <h3 class="text-xl font-bold text-blue-600">3️⃣ Design & Development</h3>
            <p class="text-gray-700">Our creative team designs modern, user-friendly solutions, while developers bring them to life with cutting-edge technology.</p>
          </div>
          <div class="mb-10 ml-6">
            <h3 class="text-xl font-bold text-blue-600">4️⃣ Launch</h3>
            <p class="text-gray-700">We test rigorously, deploy with confidence, and launch your project for maximum impact across digital platforms.</p>
          </div>
          <div class="mb-10 ml-6">
            <h3 class="text-xl font-bold text-blue-600">5️⃣ Growth & Support</h3>
            <p class="text-gray-700">We don’t just deliver — we partner with you long-term. From analytics to optimizations and after-sales support, we help you grow continuously.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- After-Sales -->
  <section id="aftersales" class="py-20 container mx-auto px-6 text-center">
    <h2 class="text-3xl font-bold mb-12">🤝 After-Sales Support</h2>
    <p class="max-w-3xl mx-auto leading-relaxed mb-10">
      At AFX Global, our relationship doesn’t end at project delivery. We provide <strong>dedicated after-sales support</strong> 
      including troubleshooting, updates, training, and long-term guidance to ensure your digital journey continues to thrive.
    </p>
    <div class="grid md:grid-cols-3 gap-8">
      <div class="bg-white p-6 rounded-xl shadow hover:shadow-xl transition">
        <i class="fa-solid fa-headset text-3xl text-blue-600 mb-4"></i>
        <h3 class="font-semibold text-xl mb-2">24/7 Customer Care</h3>
        <p>Always available to resolve your issues and queries instantly.</p>
      </div>
      <div class="bg-white p-6 rounded-xl shadow hover:shadow-xl transition">
        <i class="fa-solid fa-arrows-rotate text-3xl text-blue-600 mb-4"></i>
        <h3 class="font-semibold text-xl mb-2">Free Updates</h3>
        <p>We ensure your platforms stay updated with the latest tools and trends.</p>
      </div>
      <div class="bg-white p-6 rounded-xl shadow hover:shadow-xl transition">
        <i class="fa-solid fa-handshake text-3xl text-blue-600 mb-4"></i>
        <h3 class="font-semibold text-xl mb-2">Long-Term Partnership</h3>
        <p>We work with you beyond launch to achieve ongoing growth and success.</p>
      </div>
    </div>
  </section>

  <!-- Leadership -->
  <section id="leadership" class="bg-gray-50 py-20">
    <div class="container mx-auto px-6 text-center">
      <h2 class="text-3xl font-bold mb-12">🌟 Leadership Team</h2>
      <p class="max-w-2xl mx-auto text-gray-600 mb-12">
        Meet the visionaries driving AFX Global forward with innovation, expertise, and a passion for empowering businesses worldwide.
      </p>
      <div class="grid md:grid-cols-2 gap-8 max-w-6xl mx-auto">
        <!-- Founder -->
        <div class="bg-white p-6 rounded-xl shadow hover:shadow-xl transition text-center">
          <img src="images/farhan.jpg" alt="Farhan Abbas" class="w-32 h-32 rounded-full mx-auto mb-4">
          <h3 class="text-xl font-semibold text-blue-600">Founder & CEO</h3>
          <h4 class="mt-2 text-2xl font-bold text-gray-900">Farhan Abbas</h4>
          <p class="mt-3 text-gray-600 text-sm">
            Visionary entrepreneur with 5+ years in digital solutions, startups, and business innovation. Leads AFX Global’s mission to transform ideas into digital success.
          </p>
        </div>
        <!-- Co-Founder -->
        <div class="bg-white p-6 rounded-xl shadow hover:shadow-xl transition text-center">
          <img src="images/arooj.jpg" alt="Arooj Ilyas" class="w-32 h-32 rounded-full mx-auto mb-4">
          <h3 class="text-xl font-semibold text-blue-600">Co-Founder</h3>
          <h4 class="mt-2 text-2xl font-bold text-gray-900">Arooj Ilyas</h4>
          <p class="mt-3 text-gray-600 text-sm">
            Business strategist with expertise in operations, branding & international markets. Passionate about helping startups and SMEs grow globally.
          </p>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="bg-gradient-to-r from-blue-600 to-indigo-700 text-white py-20">
    <div class="container mx-auto text-center">
      <h2 class="text-3xl font-bold mb-6">📞 Contact AFX Global</h2>
      
      <form action="https://formspree.io/f/yourFormID" method="POST" class="max-w-xl mx-auto bg-white text-black p-6 rounded-xl shadow">
        <input type="text" name="name" placeholder="Your Name" class="w-full border p-3 rounded mb-4" required>
        <input type="email" name="email" placeholder="Your Email" class="w-full border p-3 rounded mb-4" required>
        <textarea name="message" placeholder="Your Message" class="w-full border p-3 rounded mb-4" rows="4" required></textarea>
        <button type="submit" class="bg-blue-600 text-white px-6 py-3 rounded-lg font-semibold hover:bg-blue-500 w-full">Send Message</button>
      </form>

      <div class="mt-6 space-y-2">
        <p>🌐 Website: <a href="https://www.afxglobal.com" class="underline">www.afxglobal.com</a></p>
        <p>📧 Email: <a href="mailto:info@afxglobal.com" class="underline">info@afxglobal.com</a></p>
        <p>📱 WhatsApp (Pakistan): <a href="https://wa.me/923134535930" class="underline">+92 313 4535930</a></p>
        <p>📱 WhatsApp (UK): <a href="https://wa.me/447510758242" class="underline">+44 7510 758242</a></p>
        <p>📍 Location: 66 Link Road, Sanda Kalan, Lahore</p>
      </div>
    </div>
  </section>

  <!-- Floating WhatsApp Buttons -->
  <div class="whatsapp-float">
    <a href="https://wa.me/923134535930" title="Chat on WhatsApp Pakistan" target="_blank">
      <i class="fa-brands fa-whatsapp"></i>
    </a>
    <a href="https://wa.me/447510758242" title="Chat on WhatsApp UK" target="_blank">
      <i class="fa-brands fa-whatsapp"></i>
    </a>
  </div>

  <!-- Footer -->
  <footer class="bg-gray-900 text-gray-400 text-center p-6">
    <p>© 2025 AFX Global. All rights reserved.</p>
  </footer>

  <!-- Mobile Menu Script -->
  <script>
    const menuBtn = document.getElementById('menu-btn');
    const mobileMenu = document.getElementById('mobile-menu');
    menuBtn.addEventListener('click', () => {
      mobileMenu.classList.toggle('hidden');
    });
  </script>

</body>
</html>
