html
Copy code
<!DOCTYPE html>
<html>
<head>
  <title>Travel Recommendation</title>
  <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
  <nav>
    <ul>
      <li><a href="index.html">Home</a></li>
      <li><a href="about.html">About Us</a></li>
      <li><a href="contact.html">Contact Us</a></li>
    </ul>
  </nav>
  <header>
    <h1>Welcome to Our Travel Recommendation Website</h1>
    <p>Discover your ideal destinations based on your preferences.</p>
  </header>
  <!-- Add other sections like beach, temple, country recommendations -->
</body>
</html>
About Us Page (about.html)

html
Copy code
<!DOCTYPE html>
<html>
<head>
  <title>About Us</title>
  <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
  <nav>
    <ul>
      <li><a href="index.html">Home</a></li>
      <li><a href="about.html">About Us</a></li>
      <li><a href="contact.html">Contact Us</a></li>
    </ul>
  </nav>
  <section>
    <h2>About Us</h2>
    <p>Our mission is to help you discover the best travel destinations.</p>
    <p>Meet our team of travel enthusiasts!</p>
    <!-- Add more details about the team -->
  </section>
</body>
</html>
Contact Us Page (contact.html)

html
Copy code
<!DOCTYPE html>
<html>
<head>
  <title>Contact Us</title>
  <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
  <nav>
    <ul>
      <li><a href="index.html">Home</a></li>
      <li><a href="about.html">About Us</a></li>
      <li><a href="contact.html">Contact Us</a></li>
    </ul>
  </nav>
  <section>
    <h2>Contact Us</h2>
    <form>
      <label for="email">Email:</label>
      <input type="email" id="email" name="email">
      <label for="message">Message:</label>
      <textarea id="message" name="message"></textarea>
      <button type="submit">Submit</button>
    </form>
  </section>
</body>
</html>
Stylesheet (styles.css)

css
Copy code
nav ul {
  list-style-type: none;
  padding: 0;
}
nav ul li {
  display: inline;
  margin-right: 10px;
}








