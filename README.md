<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>World Shelter — Rescue. Rehabilitate. Rehome.</title>
  <meta name="description" content="World Shelter is a dog rescue shelter in Colorado Springs dedicated to saving, rehabilitating, and rehoming dogs. Donate, adopt, foster, or volunteer to help save lives." />
  <link rel="icon" href="data:;base64,iVBORw0KGgo=" />
  <style>
    :root{
      --accent:#4a7c59;
      --accent-2:#7aba6f;
      --muted:#6b6b6b;
      --bg:#fbfdf9;
      --card:#ffffff;
      --maxw:1100px;
      font-family: Inter, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;
    }
    *{box-sizing:border-box}
    body{margin:0;background:var(--bg);color:#222}
    header{background:linear-gradient(180deg,var(--accent),var(--accent-2));color:white;padding:28px 16px}
    .wrap{max-width:var(--maxw);margin:0 auto;padding:18px}
    .brand{display:flex;align-items:center;gap:12px}
    .brand h1{margin:0;font-size:24px;letter-spacing:0.4px}
    nav{margin-top:12px}
    nav a{color:white;text-decoration:none;margin-right:14px;font-weight:600}
    .hero{display:flex;flex-wrap:wrap;gap:18px;align-items:center;padding:28px 0}
    .hero .left{flex:1;min-width:260px}
    .hero .right{flex:1;min-width:260px}
    .cta{display:inline-block;padding:12px 18px;background:white;color:var(--accent);border-radius:8px;text-decoration:none;font-weight:700;margin-right:10px}
    .card{background:var(--card);border-radius:12px;box-shadow:0 6px 20px rgba(18,18,18,0.06);padding:16px}
    .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:16px}
    h2{margin-top:0}
    .dog{display:flex;gap:12px;align-items:flex-start}
    .dog img{width:120px;height:100px;object-fit:cover;border-radius:8px}
    footer{padding:18px;text-align:center;color:var(--muted);font-size:14px}
    .pill{display:inline-block;padding:6px 10px;background:#f3f6f2;border-radius:999px;font-weight:600}
    .donate-btn{display:inline-block;padding:12px 18px;background:var(--accent);color:white;border-radius:8px;text-decoration:none;font-weight:700}
    .small{font-size:13px;color:var(--muted)}
    form input,form textarea{width:100%;padding:10px;margin:8px 0;border:1px solid #e6e6e6;border-radius:8px}
    form button{padding:10px 14px;background:var(--accent);color:white;border:0;border-radius:8px;cursor:pointer}
    .stats{display:flex;gap:16px;flex-wrap:wrap;margin-top:12px}
    .stats .stat{background:#f3f6f2;padding:12px 18px;border-radius:8px;text-align:center;flex:1;min-width:120px}
    .dog-of-week{border:2px solid var(--accent);padding:12px;border-radius:12px;margin-top:12px}
    @media(max-width:720px){
      .hero{flex-direction:column}
    }
  </style>
</head>
<body>
  <header>
    <div class="wrap">
      <div class="brand">
        <div style="width:56px;height:56px;border-radius:10px;background:white;display:flex;align-items:center;justify-content:center;color:var(--accent);font-weight:800">WS</div>
        <div>
          <h1>World Shelter</h1>
          <div class="small">Rescue • Rehabilitate • Rehome — Colorado Springs, USA</div>
        </div>
      </div>
      <nav>
        <a href="#about">About</a>
        <a href="#dogs">Our Dogs</a>
        <a href="#donate">Donate</a>
        <a href="#contact">Contact</a>
      </nav>
    </div>
  </header>

  <main class="wrap" style="padding-top:22px;">
    <section class="hero">
      <div class="left">
        <div class="card">
          <h2>Welcome to World Shelter</h2>
          <p>World Shelter is a non‑profit dog rescue in Colorado Springs dedicated to saving dogs from the streets, neglect, and abandonment. We provide medical care, behavioral rehabilitation, and loving foster homes until permanent families are found.</p>
          <p class="small">Want to help? You can adopt, foster, volunteer, or donate. Every action saves lives.</p>
          <div style="margin-top:12px">
            <a class="cta" href="#dogs">View Dogs for Adoption</a>
            <a class="donate-btn" href="#donate">Donate Now</a>
          </div>
        </div>
      </div>
      <div class="right">
        <div class="card" style="text-align:center">
          <img src="assets/images/hero-dog.jpg" alt="happy dog" style="width:100%;height:220px;object-fit:cover;border-radius:8px;margin-bottom:12px" />
          <p style="margin:0;font-weight:700">Open Hearts. Wagging Tails.</p>
          <p class="small">We care for dogs of all ages and sizes. See who’s waiting for a home.</p>
        </div>
      </div>
    </section>

    <section id="about" style="margin-top:18px">
      <div class="card">
        <h2>About World Shelter</h2>
        <p><strong>Our mission:</strong> Rescue dogs in need, give them medical treatment and behavioral support, and place them into loving, permanent homes. We believe in transparency, compassion, and the power of community.</p>
        <div class="grid" style="margin-top:12px">
          <div class="card">
            <h3>What We Do</h3>
            <ul>
              <li>Rescue and intake</li>
              <li>Medical care (vaccinations, spay/neuter, treatment)</li>
              <li>Training and socialization</li>
              <li>Adoption and foster programs</li>
            </ul>
          </div>
          <div class="card">
            <h3>How You Can Help</h3>
            <ul>
              <li>Adopt a dog</li>
              <li>Become a foster</li>
              <li>Volunteer at the shelter</li>
              <li>Donate to support care</li>
            </ul>
          </div>
        </div>

        <div class="stats">
          <div class="stat"><strong>120+</strong><br>Dogs Rescued</div>
          <div class="stat"><strong>85+</strong><br>Successful Adoptions</div>
          <div class="stat"><strong>40+</strong><br>Active Volunteers</div>
          <div class="stat"><strong>2000+</strong><br>Pounds of Food Donated</div>
        </div>
      </div>
    </section>

    <section id="dogs" style="margin-top:18px">
      <h2>Available Dogs</h2>
      <div class="grid">
        <div class="card">
          <div class="dog">
            <img src="assets/images/dog1.jpg" alt="Buddy" />
            <div>
              <h3>Buddy — 3 years</h3>
              <p class="small">Mixed breed • Friendly & playful • Good with children</p>
              <p class="small">Story: Rescued from a busy roadside, now recovering and ready to meet a family.</p>
              <a class="pill" href="#contact">Enquire about Buddy</a>
            </div>
          </div>
        </div>

        <div class="card">
          <div class="dog">
            <img src="assets/images/dog2.jpg" alt="Luna" />
            <div>
              <h3>Luna — 2 years</h3>
              <p class="small">Small mixed breed • Calm & affectionate • House-trained</p>
              <p class="small">Story: Found near a marketplace — vaccinated and spayed.</p>
              <a class="pill" href="#contact">Enquire about Luna</a>
            </div>
          </div>
        </div>

      </div>

      <div class="dog-of-week card">
        <h3>Dog of the Week: Max</h3>
        <img src="assets/images/dog3.jpg" alt="Max" style="width:100%;height:200px;object-fit:cover;border-radius:8px;margin-bottom:8px"/>
        <p class="small">Max was rescued after being abandoned near a highway. After care and training, he’s playful, affectionate, and ready for adoption. Be the one to give him a forever home!</p>
        <a class="pill" href="#contact">Adopt Max</a>
      </div>
    </section>

    <section id="donate" style="margin-top:18px">
      <div class="card">
        <h2>Support World Shelter</h2>
        <p>Your donation provides food, medical care, shelter, and rehabilitation for dogs in our care. Every contribution makes a real difference.</p>
        <p class="small">We currently accept donations via PayPal. Use the button below to support our work.</p>

        <p style="margin-top:12px"><a class="donate-btn" href="https://linktr.ee/Wildsherltercom" target="_blank" rel="noopener">Donate via PayPal</a></p>

        <h3>Donation Tiers</h3>
        <ul>
          <li>$10 = Vaccination for 1 dog</li>
          <li>$25 = Food for 1 dog for a month</li>
          <li>$50 = Medical care</li>
        </ul>

        <p class="small" style="margin-top:12px">Notes:
          <ul>
            <li>100% of donations go to dog care, medical bills, and shelter operations.</li>
            <li>You can make a one-time or recurring donation via the PayPal page linked above.</li>
          </ul>
        </p>
      </div>
    </section>

    <section id="contact" style="margin-top:18px; margin-bottom:32px">
      <div class="card">
        <h2>Contact Us</h2>
        <p class="small">Have questions, want to adopt or volunteer? Get in touch.</p>
        <div style="display:grid;grid-template-columns:1fr;gap:12px;max-width:700px">
          <p>Email: <a href="mailto:nickyherbz2@gmail.com">nickyherbz2@gmail.com</a></p>
          <p>Location: Colorado Springs, USA</p>

          <form action="mailto:nickyherbz2@gmail.com" method="post" enctype="text/plain">
            <input type="text" name="name" placeholder="Your name" required />
            <input type="email" name="email" placeholder="Your email" required />
            <textarea name="message" rows="5" placeholder="Your message" required></textarea>
            <button type="submit">Send Message</button>
          </form>
        </div>
      </div>
    </section>
  </main>

  <footer>
    <div class="wrap">
      <div style="display:flex;justify-content:space-between;align-items:center;gap:12px;flex-wrap:wrap">
        <div>© 2025 World Shelter — Colorado Springs, USA</div>
        <div class="small">Follow us: <a href="https://linktr.ee/Wildsherltercom" target="_blank">Linktree</a></div>
      </div>
    </div>
  </footer>
</body>
</html>
