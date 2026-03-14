<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Bhagwan Electricals</title>

<style>
body {
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
  background: #f4f6f9;
}

/* HEADER */
header {
  background: #0f172a;
  color: white;
  padding: 25px;
  text-align: center;
  animation: fadeDown 1s ease;
}

nav {
  background: #1e293b;
  padding: 12px;
  text-align: center;
}

nav a {
  color: white;
  margin: 15px;
  text-decoration: none;
  font-weight: bold;
  transition: 0.3s;
}

nav a:hover {
  color: #38bdf8;
}

/* TOP IMAGE */
.top-photo {
  max-width: 400px;
  width: 90%;
  margin: 20px auto;
  display: block;
  border-radius: 10px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.15);
}

/* HERO */
.hero {
  height: 420px;
  background: url("https://images.unsplash.com/photo-1581092918056-0c4c3acd3789") center/cover;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  color: white;
}

.hero h1 {
  font-size: 48px;
  background: rgba(0, 0, 0, 0.6);
  padding: 20px;
  border-radius: 8px;
  animation: fadeUp 1.5s ease;
}

/* SECTIONS */
section {
  padding: 60px;
  text-align: center;
}

/* SERVICES */
.services {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 25px;
}

.card {
  background: white;
  width: 260px;
  border-radius: 10px;
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
  overflow: hidden;
  transition: 0.4s;
}

.card:hover {
  transform: translateY(-10px) scale(1.03);
}

.card img {
  width: 100%;
  height: 170px;
  object-fit: cover;
}

.card h3 {
  margin: 15px 0 10px;
}

/* FORM */
form {
  max-width: 600px;
  margin: auto;
  background: white;
  padding: 30px;
  border-radius: 10px;
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
}

input,
textarea {
  width: 100%;
  padding: 12px;
  margin: 10px 0;
  border-radius: 6px;
  border: 1px solid #ccc;
}

button {
  background: #2563eb;
  color: white;
  border: none;
  padding: 12px 25px;
  font-size: 16px;
  border-radius: 6px;
  cursor: pointer;
}

button:hover {
  background: #1d4ed8;
}

/* FOOTER */
footer {
  background: #0f172a;
  color: white;
  padding: 20px;
  text-align: center;
}

/* ANIMATIONS */
@keyframes fadeDown {
  from {
    opacity: 0;
    transform: translateY(-30px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

@keyframes fadeUp {
  from {
    opacity: 0;
    transform: translateY(40px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}
</style>
</head>

<body>

<header>
  <h1>Bhagwan Electricals</h1>
  <p>Reliable Home & Commercial Electrical Solutions</p>
</header>

<!-- Your photo added here -->
<img
  src="https://cdn.discordapp.com/attachments/1090871776225155072/1141439224197459984/photo_2026-03-14_19-09-50.jpg"
  alt="Bhagwan Dhuve and partner"
  class="top-photo"
/>

<nav>
  <a href="#">Home</a>
  <a href="#services">Services</a>
  <a href="#appointment">Book Appointment</a>
  <a href="#contact">Contact</a>
</nav>

<div class="hero">
  <h1>Safe & Professional Electrical Work For Your Home</h1>
</div>

<section id="services">
  <h2>Our Electrical Services</h2>

  <div class="services">
    <div class="card">
      <img src="https://images.unsplash.com/photo-1621905251918-48416bd8575a" alt="Home wiring" />
      <h3>Home Electrical Wiring</h3>
      <p>Complete residential electrical wiring and safe installation.</p>
    </div>

    <div class="card">
      <img src="https://images.unsplash.com/photo-1581092335397-9583eb92d232" alt="Electrical repair" />
      <h3>Electrical Repair</h3>
      <p>Fast troubleshooting and repair for electrical faults.</p>
    </div>

    <div class="card">
      <img src="https://images.unsplash.com/photo-1555963966-b7ae5404b6ed" alt="Lighting installation" />
      <h3>Lighting Installation</h3>
      <p>Professional indoor and outdoor lighting installation.</p>
    </div>

    <div class="card">
      <img src="https://images.unsplash.com/photo-1581093588401-16ec1f6c4d6b" alt="Switchboard setup" />
      <h3>Switchboard & Panel Setup</h3>
      <p>Modern distribution boards and electrical panel upgrades.</p>
    </div>
  </div>
</section>

<section id="appointment">
  <h2>Book an Electrical Service Appointment</h2>

  <form>
    <input type="text" placeholder="Customer Full Name" required />

    <input type="tel" placeholder="Phone Number" required />

    <input type="text" placeholder="Home Address" required />

    <textarea
      rows="5"
      placeholder="Describe your electrical problem (e.g., wiring issue, power failure, new fittings)"
    ></textarea>

    <button type="submit">Submit Appointment Request</button>
  </form>
</section>

<section id="contact">
  <h2>Contact Information</h2>

  <p><strong>Electrician:</strong> Bhagwan Dhuve</p>
  <p><strong>Phone:</strong> +91 XXXXX XXXXX</p>
  <p><strong>Service Area:</strong> Local City / Area</p>
</section>

<footer>
  <p>© 2026 Bhagwan Electricals | Safe Electrical Solutions for Homes</p>
</footer>

</body>
</html>
