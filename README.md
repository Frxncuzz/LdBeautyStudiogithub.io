<!DOCTYPE html>
<html lang="en">
<head>
     <meta charset="UTF-8"> 
     <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
     <title>LD Studio</title>
     <link rel="stylesheet" href="style.css">
</head>
<body>
     <header> 
         <h1>Dobrodosli u LD Studio</h1>
         <p>Vase kreativno vreme, online</p>
         <button id="magicBtn">Klikni ovde!</button>
</header>

<main> 
    <section>
      <h2>About Us</h2>
      <p> reservisite termin preko instagrama/email-a.</p>
  </section>
</main>

<footer>
    <p>© 2025 LD Studio</p>
</footer>
<script src="script.js">
  
</script>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Online Booking</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>Book Your Appointment</h1>
  </header>

  <main>
    <form id="booking-form">
      <label for="name">Name</label>
      <input type="text" id="name" required />

      <label for="email">Email</label>
      <input type="email" id="email" required />

      <label for="service">Service</label>
      <select id="service" required>
        <option value="">Choose a service</option>
        <option value="consultation">Consultation</option>
        <option value="follow-up">Follow-up</option>
        <option value="custom">Custom Service</option>
      </select>

      <label for="date">Date</label>
      <input type="date" id="date" required />

      <label for="time">Time</label>
      <input type="time" id="time" required />

      <button type="submit">Book Now</button>
    </form>
    <p id="confirmation" style="display: none;">Thank you! Your booking has been submitted.</p>
  </main>

  <footer>
    <p>&copy; 2025 Online Booking Service</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
