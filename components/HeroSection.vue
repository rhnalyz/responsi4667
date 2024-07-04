<template>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Raleway:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet">
  <link rel='stylesheet' href='https://cdn.jsdelivr.net/npm/bootstrap@4.4.1/dist/css/bootstrap.min.css'>
  <link rel="stylesheet" href="assets/main.css">
  <section class="hero">
    <div class="container">
      <div class="main-body">
        <div class="navbar">
          <nav class="navbar navbar-expand-lg navbar-light bg-light">
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"  aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
              <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
              <ul class="navbar-nav mr-auto">
                <li class="nav-item active">
                  <a class="nav-link" href="#">Beranda</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">Profil</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">Pengalaman</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">Project</a>
                </li>
              </ul>
            </div>
          </nav>
        </div>
        <div class="row gutters-sm">
          <div class="col-md-4 mb-3">
            <div class="card">
              <div class="card-body">
                <div class="d-flex flex-column align-items-center text-center">
                  <img src="assets/FOTO.png" alt="Admin" class="foto" width="150">
                  <div class="mt-3">
                    <h4>Raihan Aly Zaky</h4>
                    <p class="text-profil">Hai, saya Raihan Aly Zaky, mahasiswa program studi Teknik Informatika di UNIVERSITAS AMIKOM YOGYAKARTA, saya memiliki ketertarikan yang kuat pada bidang desain grafis, desain UI/UX, dan frontend web dev. Saya memiliki dedikasi yang tinggi untuk terus belajar dan berkembang di bidang ini, dan siap untuk berkontribusi secara positif di lingkungan akademis dan profesional.</p>
                    <p class="text-muted font-size-sm">Daerah Istimewa Yogyakarta</p>
                    <button class="btn btn-outline-primary">Follow</button>
                    <button class="btn btn-outline-primary">Message</button>
                  </div>
                </div>
              </div>
            </div>
            <div class="card mt-3">
              <ul class="list-group list-group-flush">
                <li class="list-group-item d-flex justify-content-between align-items-center flex-wrap">
                  <h6 class="mb-0"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-github mr-2 icon-inline"><path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"></path></svg>Github</h6>
                  <span class="text-secondary">@rhnalyz</span>
                </li>
                <li class="list-group-item d-flex justify-content-between align-items-center flex-wrap">
                  <h6 class="mb-0"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-twitter mr-2 icon-inline text-info"><path d="M23 3a10.9 10.9 0 0 1-3.14 1.53 4.48 4.48 0 0 0-7.86 3v1A10.66 10.66 0 0 1 3 4s-4 9 5 13a11.64 11.64 0 0 1-7 2c9 5 20 0 20-11.5a4.5 4.5 0 0 0-.08-.83A7.72 7.72 0 0 0 23 3z"></path></svg>Twitter</h6>
                  <span class="text-secondary">@rhnalyz</span>
                </li>
                <li class="list-group-item d-flex justify-content-between align-items-center flex-wrap">
                  <h6 class="mb-0"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-instagram mr-2 icon-inline text-danger"><rect x="2" y="2" width="20" height="20" rx="5" ry="5"></rect><path d="M16 11.37A4 4 0 1 1 12.63 8 4 4 0 0 1 16 11.37z"></path><line x1="17.5" y1="6.5" x2="17.51" y2="6.5"></line></svg>Instagram</h6>
                  <span class="text-secondary">@rhnaly</span>
                </li>
              </ul>
            </div>
          </div>
          <div class="col-md-8">
            <div class="card mb-3">
              <div class="card-body">
                <h4 class="atas">Profil</h4>
                <div class="row">
                  <div class="col-sm-3">
                    <h6 class="mb-0">Nama Lengkap</h6>
                  </div>
                  <div class="data-profil">
                    Raihan Aly Zaky
                  </div>
                </div>
                <hr>
                <div class="row">
                  <div class="col-sm-3">
                    <h6 class="mb-0">Universitas</h6>
                  </div>
                  <div class="data-profil">
                    Amikom Yogyakarta
                  </div>
                </div>
                <hr>
                <div class="row">
                  <div class="col-sm-3">
                    <h6 class="mb-0">Fakultas</h6>
                  </div>
                  <div class="data-profil">
                    Ilmu Komputer
                  </div>
                </div>
                <hr>
                <div class="row">
                  <div class="col-sm-3">
                    <h6 class="mb-0">Jurusan</h6>
                  </div>
                  <div class="data-profil">
                    S1 Informatika
                  </div>
                </div>
                <hr>
                <div class="row">
                  <div class="col-sm-3">
                    <h6 class="mb-0">Alamat</h6>
                  </div>
                  <div class="data-profil">
                    Yogyakarta
                  </div>
                </div>
                <hr>
              </div>
            </div>
            <div class="card mb-3">
              <div class="card-body">
                <h4 class="title">Pengalaman</h4>
                <div class="experience">
                  <h5>Computer Graphic</h5>
                  <h6>Forum Asisten · Paruh Waktu</h6>
                  <p>Feb 2024 - Saat ini · 6 bln</p>
                  <p>Sleman, Daerah Istimewa Yogyakarta, Indonesia · Di lokasi</p>
                  <ul>
                    <li>Menyiapkan dan menguasai materi praktikum</li>
                    <li>Membantu tugas dosen selama praktikum berlangsung</li>
                    <li>Mengkondisikan berjalannya praktikum</li>
                  </ul>
                  <p><strong>Keahlian:</strong> Adobe Illustrator, Adobe Photoshop, Figma</p>
                </div>
                <hr>
                <div class="experience">
                  <h5>Designer, Tim Kreatif</h5>
                  <h6>BerDigital · Magang</h6>
                  <p>Jan 2021 - Mei 2021 · 5 bln</p>
                  <p>Daerah Istimewa Yogyakarta, Indonesia · Gabungan</p>
                  <ul>
                    <li>Berkolaborasi dengan tim kreatif untuk mengembangkan dan menyempurnakan desain UI/UX</li>
                    <li>Membantu membuat poster sesuai arahan dan memastikan hasil akhir sesuai dengan kebutuhan</li>
                    <li>Membuat infografis yang informatif dan menarik untuk digunakan dalam kampanye media sosial</li>
                    <li>Mengembangkan konten kreatif untuk media sosial, dengan tujuan meningkatkan engagement</li>
                  </ul>
                  <p><strong>Keahlian:</strong> Canva, Adobe Premiere Pro</p>
                </div>
              </div>
            </div>
            <div class="card mb-3">
              <div class="card-body">
                <h4 class="title">Project</h4>
                <div class="row">
                  <div class="col-md-4">
                    <img src="assets/Neckdeep 1.png" alt="Project 1" class="img-fluid project-image">
                  </div>
                  <div class="col-md-4">
                    <img src="assets/Neckdeep 2.png" alt="Project 2" class="img-fluid project-image">
                  </div>
                  <div class="col-md-4">
                    <img src="assets/Neckdeep 3.png" alt="Project 3" class="img-fluid project-image">
                  </div>
                </div>
                <div class="row mt-3">
                  <div class="col-md-4">
                    <img src="assets/Stars.png" alt="Project 4" class="img-fluid project-image">
                  </div>
                  <div class="col-md-4">
                    <img src="assets/Viva.png" alt="Project 5" class="img-fluid project-image">
                  </div>
                  <div class="col-md-4">
                    <img src="assets/Yellow.png" alt="Project 6" class="img-fluid project-image">
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'HeroSection'
}
</script>

<style scoped>
.hero {
  padding: 100px 0;
  display: flex;
  align-items: center;
  background-image: url('/assets/BG.jpg');
  background-repeat: no-repeat;
  background-size: cover;
  background-attachment: fixed;
  position: relative;
  z-index: 1;
}

.main-body {
  background: #4e89ac;
  font-family: "Raleway", sans-serif;
  font-optical-sizing: auto;
  border-radius: 20px; 
  padding: 20px;
}

.foto {
  width: 150px; 
  height: 150px; 
  border-radius: 80%; 
  border: 2px solid #050C9C; 
  box-shadow: 0 0 10px #000000; 
  overflow: hidden; 
}

.navbar {
  margin-bottom: 20px;
  display: flex;
  text-align: center;
  align-items: center;
  justify-content: space-between;
  padding: 1rem 5%;
  position: fixed;
  background-color: #ffffff;
  border-bottom: 1px solid #10439f;
  top: 0%;
  left: 0;
  right: 0;
  z-index: 9999;
}

.navbar-brand {
  font-size: 1.5rem;
}

.navbar-nav .nav-item {
  margin-right: 10px;
  align-items: center;
}

.navbar-nav .nav-link {
  color: #333;
  align-items: center;
}

.data-profil {
  margin-left: 9rem;
}

.mb-0{
  margin-left: 1.5rem;
}

.atas {
  margin-bottom: 3rem;
  text-align: center;
}

.text-profil {
  text-align: justify;
  color: #000000;
}

.title {
  font-size: 24px;
  margin-bottom: 20px;
  text-align: center;
}

.experience {
  margin-bottom: 20px;
}

.experience h5 {
  font-size: 20px;
  margin-bottom: 5px;
}

.experience h6 {
  font-size: 16px;
  color: #6c757d;
  margin-bottom: 5px;
}

.experience p {
  margin-bottom: 5px;
}

.experience ul {
  list-style-type: disc;
  padding-left: 20px;
  margin-top: 5px;
  margin-bottom: 10px;
}

.experience ul li {
  margin-bottom: 5px;
}

strong {
  font-weight: bold;
}

.card {
  background: #f9f9f9; 
  border: 20px;
  border-radius: 8px; 
  box-shadow: #000000; 
}

.card-body {
  padding: 20px;
}

.btn-primary, .btn-outline-primary {
  color: #000000; 
  border-color: #4e89ac; 
}

.btn-outline-primary {
  margin-left: 1rem;
}

.btn-outline-primary {
  background-color: transparent; 
}

.project-image {
  border-radius: 8px;
  margin-bottom: 10px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}
</style>
