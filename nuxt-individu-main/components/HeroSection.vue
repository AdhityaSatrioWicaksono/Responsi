<template>
  <link rel='stylesheet' href='https://cdn.jsdelivr.net/npm/bootstrap@4.4.1/dist/css/bootstrap.min.css'>
  <section class="hero">
   <div class="container">
    <div class="main-body">
      
    <!-- Menambahkan Navbar (in)-->
    <nav>
      <section class="nav-section">
            <a><NuxtLink to="/" class="nav-item">Home</NuxtLink></a>
            <a><NuxtLink to="/about" class="nav-item">About</NuxtLink></a>
            <a><NuxtLink to="/contact" class="nav-item">Contact</NuxtLink></a>
            <a><NuxtLink to="/project" class="nav-item">Project</NuxtLink></a>
      </section>
    </nav>
    <!-- Menambahkan Navbar (end)-->

          <div class="row gutters-sm">
            <div class="col-md-4 mb-3">
              <div class="card">
                <div class="card-body">
                  <div class="d-flex flex-column align-items-center text-center">
                    <img src="https://bootdey.com/img/Content/avatar/avatar7.png" alt="Admin" class="rounded-circle" width="150">
                    <div class="mt-3">
                      <h4>Adhiya Satrio Wicaksono</h4>
                      <p class="text-secondary mb-1">Full Stack Developer, Aamiin</p>
                      <p class="text-muted font-size-sm">Jembrana, Bali</p>
                      <button class="follow_btn">Follow</button>
                      <button class="massage_btn">Message</button>
                    </div>
                  </div>
                </div>
              </div>
              <div class="card mt-3">
                <ul class="list-group list-group-flush">
                  <li class="list-group-item d-flex justify-content-between align-items-center flex-wrap">
                    <h6 class="mb-0"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-globe mr-2 icon-inline"><circle cx="12" cy="12" r="10"></circle><line x1="2" y1="12" x2="22" y2="12"></line><path d="M12 2a15.3 15.3 0 0 1 4 10 15.3 15.3 0 0 1-4 10 15.3 15.3 0 0 1-4-10 15.3 15.3 0 0 1 4-10z"></path></svg>Website</h6>
                    <span class="text-secondary">https://bootdey.com</span>
                  </li>
                  <li class="list-group-item d-flex justify-content-between align-items-center flex-wrap">
                    <h6 class="mb-0"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-github mr-2 icon-inline"><path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"></path></svg>Github</h6>
                    <a href="https://github.com/AdhityaSatrioWicaksono"target="_blank"><i class="text">Jump to Github</i></a>
                  </li>
                  <li class="list-group-item d-flex justify-content-between align-items-center flex-wrap">
                    <h6 class="mb-0"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-instagram mr-2 icon-inline text-danger"><rect x="2" y="2" width="20" height="20" rx="5" ry="5"></rect><path d="M16 11.37A4 4 0 1 1 12.63 8 4 4 0 0 1 16 11.37z"></path><line x1="17.5" y1="6.5" x2="17.51" y2="6.5"></line></svg>Instagram</h6>
                    <a href="https://www.instagram.com/adhi_tyaw?igsh=N3dkZ2t1bmRocWRn"target="_blank"><i class="text">Jump to Instagram</i></a>
                  </li>
                  <li class="list-group-item d-flex justify-content-between align-items-center flex-wrap">
                    <h6 class="mb-0"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-facebook mr-2 icon-inline text-primary"><path d="M18 2h-3a5 5 0 0 0-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 0 1 1-1h3z"></path></svg>Facebook</h6>
                    <a href="https://www.facebook.com/profile.php?id=100093304365607&mibextid=ZbWKwL"target="_blank"><i class="text">Jump to Facebook</i></a>
                  </li>
                </ul>
              </div>
            </div>
            <div class="col-md-8">
              <div class="card mb-3">
                <div class="card-body">
                  <div class="row">
                    <div class="col-sm-3">
                      <h6 class="mb-0">Full Name</h6>
                    </div>
                    <div class="col-sm-9 text-secondary">
                      Adhitya Satrio Wicaksono
                    </div>
                  </div>
                  <hr>
                  <div class="row">
                    <div class="col-sm-3">
                      <h6 class="mb-0">Email</h6>
                    </div>
                    <div class="col-sm-9 text-secondary">
                      adhityasatrio123@students.amikom.ac.id
                    </div>
                  </div>
                  <hr>
                  <div class="row">
                    <div class="col-sm-3">
                      <h6 class="mb-0">NIM</h6>
                    </div>
                    <div class="col-sm-9 text-secondary">
                      22.11.4635
                    </div>
                  </div>
                  <hr>
                  <div class="row">
                    <div class="col-sm-3">
                      <h6 class="mb-0">Phone</h6>
                    </div>
                    <div class="col-sm-9 text-secondary">
                      (+62) 8133884****
                    </div>
                  </div>
                  <hr>
                  <div class="row">
                    <div class="col-sm-3">
                      <h6 class="mb-0">Address</h6>
                    </div>
                    <div class="col-sm-9 text-secondary">
                     Wedomartani, Sleman, Yogyakarta 
                    </div>
                  </div>
                  <hr>
                  <div class="row">
                  </div>
                </div>
              </div>

              <div class="row gutters-sm">
                <div class="col-sm-12 mb-3">
                  <div class="card h-100">
                    <div class="card-body">
                      <h6 class="d-flex align-items-center mb-3">Project Status Persentage</h6>
                      <small>Web Design</small>
                      <div class="progress mb-3" style="height: 5px">
                        <div class="progress-bar bg-primary" role="progressbar" style="width: 80%" aria-valuenow="80" aria-valuemin="0" aria-valuemax="100"></div>
                      </div>
                      <small>Express Suki Sushi (2024)</small>
                      <div class="progress mb-3" style="height: 5px">
                        <div class="progress-bar bg-primary" role="progressbar" style="width: 72%" aria-valuenow="72" aria-valuemin="0" aria-valuemax="100"></div>
                      </div>
                      <small>Cashier Management (2023)</small>
                      <div class="progress mb-3" style="height: 5px">
                        <div class="progress-bar bg-primary" role="progressbar" style="width: 89%" aria-valuenow="89" aria-valuemin="0" aria-valuemax="100"></div>
                      </div>
                      <small>HeartSync Application (2023)</small>
                      <div class="progress mb-3" style="height: 5px">
                        <div class="progress-bar bg-primary" role="progressbar" style="width: 55%" aria-valuenow="55" aria-valuemin="0" aria-valuemax="100"></div>
                      </div>
                      <small>Tentang Rumahku MVC</small>
                      <div class="progress mb-3" style="height: 5px">
                        <div class="progress-bar bg-primary" role="progressbar" style="width: 66%" aria-valuenow="66" aria-valuemin="0" aria-valuemax="100"></div>
                      </div>
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
  text-align: center;
  padding: 100px 0;
  background-image: url(https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS69KBzgab7vfkcvZiPpJ-qONc9FpJvEo_yOg&s);

}

.follow_btn {
    background-color: rgb(186, 11, 11);
    color: white;
    border: none;
    height: 32px;
    width: 105px;
    border-radius: 2px;
    transition: opacity 0.15s;
    
  }
.follow_btn:hover{
  opacity: 0.8;
}
.follow_btn:active{
  opacity: 0.5;

}

.massage_btn {
  background-color: rgb(255, 255, 255);
    color: rgb(57, 88, 199);
    border-color: rgb(57, 88, 199);
    border-style: solid;
    height: 32px;
    width: 105px;
    border-radius: 2px;
    border-width: 1px;
    margin-left: 8px;
    transition: background-color 0.15s, color 0.15s, opacity 0.15s;
    
  }
.massage_btn:hover{
  background-color:rgb(57, 88, 199);
    color: rgb(255, 255, 255);
}
.massage_btn:active{
  opacity: 0.7;
}

</style>
