

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Saman Ramzan | Portfolio</title>

<style>
body {
    margin: 0;
    font-family: 'Poppins', sans-serif;
    background: #0f172a;
    color: white;
}

header {
    text-align: center;
    padding: 50px;
}

header h1 {
    font-size: 3rem;
    color: #38bdf8;
}

header p {
    font-size: 1.2rem;
    color: #cbd5f5;
}

section {
    padding: 50px;
}

.card {
    background: #1e293b;
    padding: 20px;
    margin: 15px;
    border-radius: 15px;
    transition: 0.3s;
}

.card:hover {
    transform: scale(1.05);
    box-shadow: 0px 0px 20px #38bdf8;
}

.grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
}

h2 {
    color: #38bdf8;
}

button {
    padding: 10px 20px;
    background: #38bdf8;
    border: none;
    border-radius: 10px;
    cursor: pointer;
}

button:hover {
    background: #0ea5e9;
}
</style>

</head>

<body>

<header>
    <h1>Saman Ramzan</h1>
    <p>BS Computer Science Student | Graphic Designer | Creative Leader</p>
    <button onclick="scrollToSection()">Explore My Work</button>
</header>

<section id="about">
    <h2>About Me</h2>
    <div class="card">
        <p>
        I am a BSCS student at Fatima Jinnah Women University with strong experience in 
        graphic designing, leadership, and community work. I have worked with multiple 
        organizations and actively contribute to creative and social initiatives.
        </p>
    </div>
</section>

<section>
    <h2>Education</h2>
    <div class="grid">
        <div class="card">BS Computer Science (2024–2028)<br>FJWU</div>
        <div class="card">ICS (A Grade)</div>
        <div class="card">Matric (A+ Grade)</div>
    </div>
</section>

<section>
    <h2>Skills</h2>
    <div class="grid">
        <div class="card">Graphic Designing</div>
        <div class="card">Canva & Figma</div>
        <div class="card">C / C++</div>
        <div class="card">SEO Writing</div>
        <div class="card">Leadership</div>
        <div class="card">Teaching & Mentoring</div>
    </div>
</section>

<section>
    <h2>Experience</h2>
    <div class="grid">
        <div class="card">Chief Graphic Designer - CBS</div>
        <div class="card">Head Designer - PMYDC</div>
        <div class="card">Teacher - Hussain Academy</div>
        <div class="card">Volunteer - Heal Pakistan</div>
    </div>
</section>

<section>
    <h2>Certificates & Achievements</h2>
    <div class="card">
        Multiple certificates in Web Development, SEO Writing, Community Service, 
        Leadership roles, and Graphic Designing.
    </div>
</section>

<section>
    <h2>Contact</h2>
    <div class="card">
        <p>Email: samanramzan473@gmail.com</p>
        <p>Phone: +92 3369948255</p>
    </div>
</section>

<script>
function scrollToSection() {
    document.getElementById("about").scrollIntoView({ behavior: "smooth" });
}
</script>

</body>
</html>
