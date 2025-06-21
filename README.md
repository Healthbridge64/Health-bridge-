<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>HealthBridge | Virtual Medical Assistant</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Inter', sans-serif;
      margin: 0;
      padding: 0;
      background: #f9f9f9;
      color: #333;
    }

    header {
      background-color: #0077cc;
      color: white;
      padding: 3rem 1rem;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }

    header p {
      font-size: 1.2rem;
    }

    section {
      padding: 2rem 1rem;
      max-width: 900px;
      margin: auto;
    }

    .features, .audience {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
    }

    .card {
      background: white;
      border-radius: 8px;
      padding: 1.5rem;
      box-shadow: 0 2px 8px rgba(0,0,0,0.05);
    }

    .chatbox {
      background: white;
      padding: 1rem;
      border: 1px solid #ccc;
      border-radius: 6px;
      max-width: 600px;
      margin: 2rem auto;
    }

    .chatbox p {
      margin: 0.5rem 0;
    }

    form {
      background: white;
      padding: 2rem;
      border-radius: 8px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    }

    input, textarea {
      width: 100%;
      padding: 0.8rem;
      margin: 0.5rem 0 1rem;
      border: 1px solid #ccc;
      border-radius: 5px;
    }

    button {
      background: #0077cc;
      color: white;
      padding: 0.8rem 1.5rem;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      font-weight: bold;
    }

    footer {
      background: #eee;
      padding: 1rem;
      text-align: center;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>

<header>
  <h1>HealthBridge</h1>
  <p>Your AI-powered assistant for patient care, appointments, and Q&A</p>
</header>

<section>
  <h2>Key Features</h2>
  <div class="features">
    <div class="card">
      <h3>🗓 Appointment Scheduling</h3>
      <p>Patients can book, reschedule, and get reminders easily 24/7.</p>
    </div>
    <div class="card">
      <h3>💬 Health Q&A Assistant</h3>
      <p>Instant responses to common patient questions using safe AI models.</p>
    </div>
    <div class="card">
      <h3>👩‍⚕️ Patient Follow-ups</h3>
      <p>Send reminders, post-visit care instructions, and alerts to patients automatically.</p>
    </div>
    <div class="card">
      <h3>🏥 Made for Healthcare Providers</h3>
      <p>Simple, secure, and customizable — built to support real clinics and teams.</p>
    </div>
  </div>
</section>

<section>
  <h2>How It Works</h2>
  <ol>
    <li>Embed the assistant on your clinic’s site or patient portal.</li>
    <li>Patients interact through chat to ask questions or book appointments.</li>
    <li>HealthBridge AI handles routine tasks and sends updates to your team.</li>
  </ol>
</section>

<section>
  <h2>Chat Assistant Demo (Preview)</h2>
  <div class="chatbox">
    <p><strong>Patient:</strong> I need to schedule a check-up for next week.</p>
    <p><strong>HealthBridge:</strong> Sure! What day works best for you?</p>
    <p><strong>Patient:</strong> Wednesday morning.</p>
    <p><strong>HealthBridge:</strong> Got it. Booking you for Wednesday at 10 AM. ✅</p>
  </div>
</section>

<section>
  <h2>Contact Us</h2>
  <p>Want to try HealthBridge for your clinic or team? Fill out the form below and we’ll reach out.</p>
  <form action="https://formsubmit.co/hareemabdullah6464@gmail.com" method="POST">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name" required>

  <label for="email">Email:</label>
  <input type="email" id="email" name="email" required>

  <label for="message">Message:</label>
  <textarea id="message" name="message" required></textarea>

  <button type="submit">Send Message</button>
</form>


<footer>
  &copy; 2025 HealthBridge. All rights reserved.
</footer>

</body>
</html>
