# Ashok-Enterprises-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Ashok Enterprises</title>
  <link rel="stylesheet" href="style.css"/>
</head>
<body>
  <header>
    <h1>Ashok Enterprises</h1>
    <p>Digital Web | Digital Seva Kendra</p>
  </header>

  <section class="services">
    <h2>Our Services</h2>
    <div class="service-grid">

      <div class="service">
        <h3>PAN Card Apply</h3>
        <a href="https://forms.gle/YOUR_PAN_FORM" target="_blank">Apply Now</a>
      </div>

      <div class="service">
        <h3>Recharge & Bill Payment</h3>
        <a href="https://forms.gle/YOUR_RECHARGE_FORM" target="_blank">Start Now</a>
      </div>

      <div class="service">
        <h3>AEPS (Aadhaar Enabled Payment System)</h3>
        <p>Fingerprint-based cash withdrawal & balance check.</p>
        <a href="https://forms.gle/YOUR_AEPS_FORM" target="_blank">Submit Details</a>
      </div>

    </div>
  </section>

  <section class="contact">
    <h2>Contact Us</h2>
    <a href="https://wa.me/919761294444" class="whatsapp" target="_blank">Chat on WhatsApp</a>
  </section>

  <footer>
    <p>Contact: 9761294444 | Email: ashokkumaryadav1289@gmail.com / ashishyaduvanshi109@gmail.com</p>
    <p>&copy; 2025 Ashok Enterprises</p>
  </footer>
</body>
</html>
body {
  margin: 0;
  font-family: sans-serif;
  background: #fff;
  color: #111;
}

header {
  background-color: #b30000;
  color: white;
  padding: 20px;
  text-align: center;
}

.services {
  padding: 20px;
}

.service-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 20px;
}

.service {
  border: 1px solid #ccc;
  border-radius: 12px;
  padding: 15px;
  background-color: #f9f9f9;
  text-align: center;
}

.service a {
  display: inline-block;
  margin-top: 10px;
  background: #b30000;
  color: white;
  padding: 10px;
  border-radius: 6px;
  text-decoration: none;
}

.service a:hover {
  background: #800000;
}

.contact {
  background: #f2f2f2;
  padding: 20px;
  text-align: center;
}

.whatsapp {
  background: #25D366;
  color: white;
  padding: 10px 20px;
  border-radius: 6px;
  text-decoration: none;
}

footer {
  background-color: #111;
  color: white;
  text-align: center;
  padding: 10px;
}
