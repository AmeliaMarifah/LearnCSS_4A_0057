<img width="1894" height="877" alt="1" src="https://github.com/user-attachments/assets/65216257-20ea-4488-8265-2688a0f6a152" />
<img width="1894" height="873" alt="2" src="https://github.com/user-attachments/assets/3ec2a089-2fdd-4034-a40c-987855746faf" />
<img width="1893" height="862" alt="3" src="https://github.com/user-attachments/assets/58312d40-ef99-4ec5-a14c-c3672073faad" />
<img width="1888" height="660" alt="4" src="https://github.com/user-attachments/assets/bf59605b-154a-4aff-9432-1eea215e9cd4" />
<img width="1889" height="857" alt="5" src="https://github.com/user-attachments/assets/411b9705-400c-4cd0-a476-194576598738" />
<img width="1894" height="852" alt="6" src="https://github.com/user-attachments/assets/cabad606-149e-4731-9351-715822332d5c" />
<img width="1890" height="846" alt="7" src="https://github.com/user-attachments/assets/99257622-0563-47ab-9856-db41a4b38aaa" />

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="style.css" rel="stylesheet" />
    <title>Belajar HTML</title>
</head>

<body id="body">
    <!-- Header -->
    <header>
        <h1>Minggg<span class="accent">.</span></h1>
        <nav>
            <a href="#about">About</a>
            <a href="#skill">Skill</a>
            <a href="#project">Project</a>
            <a href="#education">Education</a>
            <a href="#experience">Experiensce</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <!-- Main -->
    <main>

        <!-- Section About -->
        <section id="about">
            <div class="hero-kiri">
                <h2>About Me</h2>
                <p>My Name Amelia Ma'rifah</p>
                <p>I'm Web Developer.</p>
                <p>i'm from Informatic UISI</p>
            </div>
            
            <div class="hero-kanan">
                <img src="uisi.png" width="512px" height="256px">
            </div>
        </section>

        <!-- Section Skill -->
        <section id="skill">
            <h2>My Skill</h2>
            <div class="skill-hero">
          <ul>
            <li>
              <img src="https://www.freepnglogos.com/uploads/javascript-png/png-javascript-badge-picture-8.png"
                alt="javascript"/>
              <p>JavaScript</p>
            </li>

            <li>
              <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/61/HTML5_logo_and_wordmark.svg/1280px-HTML5_logo_and_wordmark.svg.png?_=20170517184425"
                alt="html"/>
              <p>HTML</p>
            </li>

            <li>
              <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d5/CSS3_logo_and_wordmark.svg/960px-CSS3_logo_and_wordmark.svg.png?_=20160530175649"
                alt="css"/>
              <p>CSS</p>
            </li>

            <li>
              <img src="https://cdn-icons-png.flaticon.com/512/5968/5968282.png"
                alt="java"/>
              <p>Java</p>
            </li>

            <li>
              <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Python-logo-notext.svg/250px-Python-logo-notext.svg.png?_=20250701090410"
                alt="javascript"/>
              <p>Python</p>
            </li>

            <li>
              <img src="https://upload.wikimedia.org/wikipedia/commons/3/33/Figma-logo.svg"
                alt="Figma"/>
              <p>Figma</p>
            </li>
          </ul>
        </div>
        </section>

        <!-- Section Project -->
        <section id="project">
            <h2>My Project</h2>

            <div class="project-hero">
                <div>
                <div>
                    <h4>POS Project</h4>
                    <p>proyek aplikasi Point of Sale berbasis website.</p>
                    <a href="https://github.com/" target="_blank">See project</a>
                </div>

                <div>
                    <h4>Company Profile</h4>
                    <p>Company Profile menggunakan css dan html.</p>
                    <a href="https://github.com/" target="_blank">See project</a>
                </div>

                <div>
                    <h4>Inventory</h4>
                    <p>proyek aplikasi Inventory berbasis website.</p>
                    <a href="https://github.com/" target="_blank">See project</a>
                </div>

                <div>
                    <h4>E-Commerce</h4>
                    <p>proyek E-Commerce berbasis website.</p>
                    <a href="https://github.com/" target="_blank">See project</a>
                </div>
            </div>
            </div>
            
        </section>

        <!-- Section Education -->
      <section id="education">
        <h2>Education</h2>

        <div class="education-card">
          <div class="box-card">
            <img
              src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQFtuzTeRB5M42YUVvD_pCuQD440Aw2Ino_cg&s"
            />
            <div>
              <h3>Universitas Internasional Semen Indonesia</h3>
              <p><em>2024-Now</em></p>
              <p>Bachelor of Informatics Engineering.</p>
            </div>
          </div>
        </section>

        <!-- Section Experience -->
      <section id="experience">
        <h2>Experience</h2>

        <div class="experience-hero">
          <div>
            <h4>2025-Sekarang</h4>
            <p>Staff Ahli HMIF Divisi Kewirausahaan</p>
            <p><em>Responsible for identifying and developing business opportunities</em></p>
          </div>

          <div>
            <h4>2025-Sekarang</h4>
            <p>Staff Ahli LDK Divisi PSDM</p>
            <p><em>Responsible for identifying members' potential and placing them in the right roles</em></p>
          </div>
        </div>
      </section>

        <!-- Section Contact -->
        <section id="contact">
            <h2>Send me message</h2>
            <form action="" class="form">
                <div>
                    <label for="">Nama:</label>
                    <input name="nama" type="text" placeholder="Masukkan Nama">
                </div>
                 <div>
                    <label for="">Pesan:</label>
                    <input name="pesan" type="text" placeholder="Masukkan Pesan">
                </div>
                <button>Kirim Pesan</button>
            </form>
        </section>
    </main>

    <!-- Footer -->
    <footer id="footer">
            <p>&copy; 2023 My Website. Made by Love.</p>
        </footer> 
    </body>
</html>


* {
    box-sizing:content-box;
    margin: 0;
    padding: 0;
}

* h2 {
    font-size: 3rem;
    align-items: center;
}

* p {
    font-size: 1.2rem;
}

body {
    font-family: Georgia;
    background-color: #0d1117;
    color: #c9d1d9;
    line-height: 1.6;
}

.accent {
    color: #3a7ce0;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1rem 4.5rem; 
}

nav{
    display: flex;
    gap: 2rem;
    align-items: center;
}

nav a {
    color: #ffffff;
    font-size: 0.9rem;
    text-decoration: none;
    position: relative;
    padding-bottom: 4px;
    transition: color 0.3s;
}

nav a:hover {
    color: #4d3e3e;
}

/* Section About */
#about {
    background-color: #0d1117;
    padding: 6rem 4.5rem;
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 3rem;
    min-height: 70vh;
}

.hero-kiri {
    max-width: 550px;
}

.hero-kanan h2 {
    font-size: 3.5rem;
    font-weight: 800;
    color: #ffffff;
    margin-bottom: 0rem;
    line-height: 1.1;
}

.hero-kanan img {
    width: 400px;
    height: 400px;
    object-fit: cover;
    border-radius: 50%;
    border: 3px solid #21262d;
    transition: border-color 0.3s;
}

/* Section Skill */
#skill {
    background-color: #0d1117;
    padding: 6rem 6rem;
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 3rem;
}

.skill-hero ul {
    display: flex;
    justify-content: center;
    gap: 2rem;
}

.skill-hero li {
    width: 100px;
    text-align: center;
}

.skill-hero img {
    width: 100px;
    height: 100px;
    object-fit: contain;
    margin-bottom: 0.5rem;
} 

/* Section Project */
#project {
    background-color: #0d1117;
    padding: 6rem 6rem;
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 3rem;
}

.project-hero {
    display: flex;
}

.project-hero div {
    margin: 10px;
    padding: 20px;
    background-color: #3a7ce0;
    border: #3a7ce0 solid 2px;
    border-radius: 5px;
}

.project-hero a {
    color: #ffffff;
    display: inline-block;
    margin-top: 10px;
}

/* Section Education */
#education {
    padding: 6rem 6rem;
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 3rem;
}

.box-card {
    display: flex;
    space-between: 2rem;
    align-items: center;
    padding: 1.5rem;
}

.box-card img {
    width: 180px;
    height: 180px;
    object-fit: cover;
    border-radius: 6px;
    margin-right: 1.5rem;
}

/* Section Experience */
#experience {
    background-color: #0d1117;
    padding: 6rem 6rem;
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 3rem;
}

.experience-hero {
    display: flex;
}

.experience-hero div {
    margin: 10px;
    padding: 20px;
    background-color: #3a7ce0;
    border: #3a7ce0 solid 2px;
    border-radius: 5px;
}

/* Section Contact */
#contact {
    background-color: #0d1117;
    padding: 6rem 6rem;
    align-items: center;
    gap: 3rem;
}

.form input {
    padding: 0.7rem;
    width: 100%;
    margin: 10px 0;
    border: 2px solid rgb(255, 255, 255);
    border-radius: 5px;
}

.form button {
    padding: 0.7rem;
    background-color: #3a7ce0;
    color: #ffffff;
    border: 2px solid #3a7ce0;
    border-radius: 5px;
    cursor: pointer;
    margin: 15px 0;
}

/* Section footer */
#footer {
    background-color: rgba(26, 28, 32, 0.9);
    padding: 1rem 4.5rem;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
}

