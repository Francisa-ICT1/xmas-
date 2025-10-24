
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Grade 11 - Numbers | Christmas Party 2025</title>
  <style>
    :root {
      --bg:#0f1723; --accent:#c0392b; --accent2:#f7c948; --muted:#cbd5e1;
      --glass:rgba(255,255,255,0.03); --radius:14px;
      font-family:"Segoe UI",Roboto,system-ui;
    }
    html,body {margin:0; background:linear-gradient(180deg,#07102a 0%,#0b1b2b 60%); color:var(--muted);}
    .wrap {max-width:900px; margin:auto; padding:20px;}
    header {display:flex; align-items:center; gap:15px; background:var(--glass); border-radius:var(--radius); padding:15px;}
    header img {width:80px; height:80px; border-radius:10px; object-fit:cover;}
    h1 {margin:0; color:white;}
    nav a {color:var(--muted); margin-right:8px; text-decoration:none; font-weight:600;}
    main {display:grid; grid-template-columns:1fr 280px; gap:18px; margin-top:18px;}
    figure img {width:100%; border-radius:12px; height:260px; object-fit:cover;}
    figcaption {font-size:0.9rem; color:var(--muted);}
    section.details, article, aside {background:var(--glass); border-radius:var(--radius); padding:14px;}
    h2,h3 {color:var(--accent2);}
    footer {margin-top:18px; text-align:center; font-size:0.9rem; color:#aaa;}
    audio {margin-top:10px; width:80%;}
    @media(max-width:800px){main{grid-template-columns:1fr;}}
  </style>
</head>
<body>
  <div class="wrap">
    <!-- HEADER -->
    <header>
      <img src="https://images.unsplash.com/photo-1543852786-1cf6624b9987?q=80&w=800" alt="Christmas decor">
      <div>
        <h1>Grade 11 — Section A Christmas Bash 🎄</h1>
        <p>Celebrate with joy, laughter, and memories this December!</p>
        <nav>
          <a href="#details">Details</a>
          <a href="#schedule">Schedule</a>
          <a href="#contact">Contact</a>
        </nav>
      </div>
    </header>
    <main>
      <section>
        <figure>
          <img src="https://images.unsplash.com/photo-1519681393784-d120267933ba?q=80&w=1600" alt="Classroom Christmas party">
          <figcaption>🎅 Grade 11 - Section A Christmas Party • December 18, 2025</figcaption>
        </figure>
        <section id="details" class="details">
          <h2>Party Details</h2>
          <p><strong>Date:</strong> December 18, 2025 • 4:00 PM - 8:30 PM</p>
          <p><strong>Venue:</strong> Ramos Building, Room 101, Unida Christian Colleges, Mambog 3, Bacoor</p>
          <p><strong>Theme:</strong> “Cozy Holiday” — Wear Christmas colors or your favorite sweater!</p>
        </section>
        <article id="schedule">
          <h2>Program Schedule</h2>
          <ul>
            <li>4:00 PM — Arrival & Photo Booth</li>
            <li>4:30 PM — Welcome Remarks</li>
            <li>5:00 PM — Games & Potluck Dinner</li>
            <li>6:15 PM — Secret Santa Gift Exchange</li>
            <li>7:00 PM — Karaoke & Talent Show</li>
            <li>8:00 PM — Closing & Awards</li>
          </ul>
        </article>
      </section>
      <aside id="contact">
        <h3>What to Bring</h3>
        <ul>
          <li>₱150 Secret Santa gift 🎁</li>
          <li>Dish for potluck 🍴</li>
          <li>Ugly sweater 👕</li>
        </ul>
        <h3>RSVP & Contact</h3>
        <p>Email: <a href="mailto:classA.rsvp@example.com">classA.rsvp@example.com</a></p>
        <p>Contact: Ms. Sharmaine Gonzales — <a href="tel:+639171234567">+63 917 123 4567</a></p>
      </aside>
    </main>
    <footer>
      <p>Designed by Grade 11 — Section A | Unida Christian Colleges</p>
      <audio id="xmasSong" loop>
        <source src="https://files.freemusicarchive.org/storage-freemusicarchive-org/music/no_curator/Scott_Holmes_Music/Christmas_Background_Music/Scott_Holmes_Music_-_12_-_Its_Christmas_Time.mp3" type="audio/mpeg">
      </audio>
    </footer>
  </div>

  <script>
    const audio = document.getElementById('xmasSong');
    let played = false;
    window.addEventListener('scroll', () => {
      if (!played) {
        audio.volume = 0.3; // soft background
        audio.play().catch(()=>{}); // try to play
        played = true;
      }
    });
  </script>
</body>
</html>
