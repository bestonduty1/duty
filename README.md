<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>A & A Painting and Drywall Repairs</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header>
    <h1>A & A Painting and Drywall Repairs</h1>
    <p>Your Local Experts in Painting & Drywall Services</p>
  </header>

  <nav>
    <a href="#services">Services</a>
    <a href="#booking">Book Now</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="services">
    <h2>Our Services</h2>
    <ul>
      <li>Interior & Exterior Painting</li>
      <li>Drywall Installation & Repairs</li>
      <li>Texturing & Finishing</li>
      <li>Residential & Commercial Projects</li>
    </ul>
  </section>

  <section id="booking">
    <h2>Book an Appointment</h2>
    <form action="https://formspree.io/f/your-form-id" method="POST">
      <label for="name">Full Name:</label>
      <input type="text" id="name" name="name" required>

      <label for="email">Email Address:</label>
      <input type="email" id="email" name="email" required>

      <label for="phone">Phone Number:</label>
      <input type="tel" id="phone" name="phone" required>

      <label for="date">Preferred Date:</label>
      <input type="date" id="date" name="date" required>

      <label for="message">Tell us about your project:</label>
      <textarea id="message" name="message" rows="5" required></textarea>

      <button type="submit">Submit</button>
    </form>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>📞 Phone: <a href="tel:4794010010">(479) 401-0010</a></p>
    <p>📧 Email: <a href="mailto:apaintinganddrywall@gmail.com">apaintinganddrywall@gmail.com</a></p>
  </section>

  <footer>
    <p>&copy; 2025 A & A Painting and Drywall Repairs. All rights reserved.</p>
  </footer>
</body>
</html>
body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  margin: 0;
  padding: 0;
  background: #f4f4f4;
  color: #333;
}

header {
  background: #003366;
  color: white;
  padding: 2rem;
  text-align: center;
}

nav {
  background: #005599;
  display: flex;
  justify-content: center;
  gap: 2rem;
  padding: 1rem;
}

nav a {
  color: white;
  text-decoration: none;
  font-weight: bold;
}

section {
  padding: 2rem;
  background: white;
  margin: 1rem auto;
  max-width: 800px;
  border-radius: 8px;
  box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

form {
  display: flex;
  flex-direction: column;
}

form label {
  margin-top: 1rem;
}

form input,
form textarea {
  padding: 0.5rem;
  font-size: 1rem;
  margin-top: 0.3rem;
  border: 1px solid #ccc;
  border-radius: 4px;
}

form button {
  margin-top: 1.5rem;
  padding: 0.8rem;
  background-color: #003366;
  color: white;
  border: none;
  cursor: pointer;
  border-radius: 4px;
  font-size: 1rem;
}

form button:hover {
  background-color: #005599;
}

footer {
  background: #003366;
  color: white;
  text-align: center;
  padding: 1rem;
  margin-top: 2rem;
}
