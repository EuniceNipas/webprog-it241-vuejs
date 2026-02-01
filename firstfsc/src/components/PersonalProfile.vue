<template>
  <div class="container">
    <header class="header">
      <h1>Personal Profile Web Page</h1>
      <p class="subtitle">Get to know me 💖</p>
    </header>

    <main class="content">
      <section class="main-content">

        <div class="card">
          <h2>About Me</h2>
          <p>
            Hi, my name is <strong>Eunice B. Nipas</strong>, although most people just call me <strong>Nissy</strong>.
            Fun fact: I came up with that name as an internet alias during the epidemic, but I eventually came to love it
            and adopted it as my actual nickname.
          </p>
          <p>
            The best year for me was <strong>2006</strong> because that was the year I was born.
            I dislike most vegetables, but I do enjoy a good Caesar salad!
          </p>
          <p>
            I <strong>LOVE STYLING</strong> — you’ll always see me with different hair colors and clothing styles.
            If I could be an animal, I’d choose a <strong>cat</strong>: eat, sleep, litter, repeat 🐱
          </p>
        </div>

        <div class="card">
          <h2>Education / Achievements</h2>
          <ul>
            <li><strong>Kinder:</strong> St. Gabriel Academy of Parañaque (SGAP)</li>
            <li><strong>Elementary:</strong> Baclaran Elementary School Central</li>
            <li><strong>Junior High:</strong> Brainshire Science School</li>
            <li><strong>Senior High:</strong> National University – MOA (STEM)</li>
            <li><strong>College:</strong> Asia Pacific College (Ongoing)</li>
          </ul>
        </div>

        <div class="card">
          <h2>Course</h2>
          <p>Bachelor of Science in Information Technology</p>
        </div>

        <div class="card">
          <h2>IT Experience</h2>
          <div class="tags">
            <span>Python</span>
            <span>Java</span>
            <span>HTML</span>
            <span>CSS</span>
          </div>
        </div>

        <div class="card">
          <h2>Hobbies & Interests</h2>
          <p>
            Listening to music, drawing, playing badminton, running sometimes,
            and playing first-person shooter games 🎮
          </p>
        </div>

        <div class="card">
          <h2>Goals In Life / Dream</h2>
          <p><strong>Goals:</strong> Finish my BSIT degree and enjoy life to the fullest.</p>
          <p>
            <strong>Dreams:</strong> I want to be rich—not in a luxury sense,
            but rich in experiences and time with loved ones.
            I’d also love to work or perform in the entertainment industry if given the chance.
          </p>
        </div>

        <div class="card">
          <h2>Picture Gallery</h2>
          <div class="gallery">
            <div class="gallery-box">Image 1</div>
            <div class="gallery-box">Image 2</div>
            <div class="gallery-box">Image 3</div>
          </div>
        </div>

      </section>

      <aside class="sidebar">
        <h3>Quick Info</h3>
        <p><strong>Name:</strong> Eunice “Nissy” Nipas</p>
        <p><strong>Course:</strong> BSIT</p>
        <p><strong>School:</strong> Asia Pacific College</p>
      </aside>
    </main>

    <footer class="footer">
      Asia Pacific College
    </footer>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
/* GENERAL */
body {
  margin: 0;
  font-family: 'Poppins', sans-serif;
}

.container {
  background: #0d0b14;
  color: #f5f5f5;
  min-height: 100vh;
}

/* HEADER */
.header {
  text-align: center;
  padding: 2rem;
  background: linear-gradient(135deg, #ff5fa2, #a855f7);
  color: #fff;
}

.subtitle {
  opacity: 0.9;
}

/* MAIN LAYOUT */
.content {
  display: grid;
  grid-template-columns: 3fr 1fr;
  gap: 1.5rem;
  padding: 2rem;
}

/* CARDS */
.card {
  background: #1a1628;
  border-radius: 16px;
  padding: 1.5rem;
  box-shadow: 0 0 20px rgba(255, 95, 162, 0.15);
  border: 1px solid rgba(255, 95, 162, 0.2);
}

.card h2 {
  color: #ff5fa2;
  margin-bottom: 0.8rem;
}

/* TAGS */
.tags span {
  display: inline-block;
  background: #ff5fa2;
  color: #000;
  padding: 0.3rem 0.8rem;
  border-radius: 999px;
  margin: 0.2rem;
  font-size: 0.85rem;
  font-weight: bold;
}

/* GALLERY */
.gallery {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 1rem;
}

.gallery-box {
  background: linear-gradient(135deg, #ff5fa2, #a855f7);
  height: 120px;
  border-radius: 12px;
  display: grid;
  place-items: center;
  font-weight: bold;
}

/* SIDEBAR */
.sidebar {
  background: #1f1b30;
  border-radius: 16px;
  padding: 1.5rem;
  height: fit-content;
  box-shadow: 0 0 15px rgba(168, 85, 247, 0.2);
}

.sidebar h3 {
  color: #a855f7;
}

/* FOOTER */
.footer {
  text-align: center;
  padding: 1rem;
  background: #120f1f;
  color: #aaa;
}
</style>
