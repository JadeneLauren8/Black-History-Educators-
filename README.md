<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" href="style.css">
</head>
<body>
<script>
  const facts = [
    "Garrett Morgan invented the traffic light in 1923.",
    "Harriet Tubman helped around 70 enslaved people escape using the Underground Railroad.",
    "Dr. Mae Jemison was the first Black woman to travel in space.",
    "Barack Obama became the first Black U.S. President in 2008.",
    "Mary McLeod Bethune opened a school with only $1.50 and 5 students.",
    "George Washington Carver created over 300 products from peanuts!"
  ];

  function showFact() {
    const randomIndex = Math.floor(Math.random() * facts.length);
    document.getElementById("factBox").textContent = facts[randomIndex];
  }
</script>
<div id="app">
<header>
<h1>Black History</h1>
</header>
<main>
<section>
<h2>About Black History</h2>
<p>Black history is the history of people of African descent. It is a rich and diverse history that spans centuries and continents.</p>
<p>This website celebrates Black history by providing information about important Black figures, events, and achievements.</p>
</section>
<section>
  <h2>Family Fun Activities</h2>
  <ul>
    <li>🧩 <strong>Quiz Time!</strong> – <button onclick="showFact()">Click to reveal a fun Black History fact!</button></li>
    <li id="factBox" style="margin-top: 10px; font-style: italic; color: #4e342e;"></li>
    <li>🎨 <strong>Art Corner</strong> – Draw your favorite hero or make a family Black History poster</li>
    <li>📚 <strong>Story Hour</strong> – Read a bedtime story featuring real Black heroes</li>
    <li>👪 <strong>Talk Together</strong> – Share what fairness and bravery mean in your family</li>
  </ul>
</section>
<section>
<h2>Black Figures</h2>
<ul>
<li>Harriet Tubman</li>
<li>Martin Luther King Jr.</li>
<li>Marcus Garvey</li>
<li>Rita Pierson</li>
<li>Mary McLeod</li>
<li>Booker T. Washington</li>
<li>W.E.B. Du Bois</li>
<li>Septima Clark</li>
</ul>
</section>
<section>
<h2>Black Events</h2>
<ul>
<li>The Emancipation Proclamation</li>
<li>The Civil Rights Movement</li>
<li>The Black Power Movement</li>
<li>The Million Man March</li>
<li>The Black Lives Matter Movement</li>
</ul>
</section>
<section>
<h2>Black Achievements</h2>
<ul>
<li>The invention of the traffic light</li>
<li>The development of the X-ray machine</li>
<li>The creation of the first heart transplant</li>
<li>The first Black president of the United States</li>
</ul>
</section>
</main>
<footer>
<p>Copyright &copy; 2023, Black History Interactive Website.</p>
</footer>
</div>
