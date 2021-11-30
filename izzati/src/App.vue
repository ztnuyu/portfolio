<template>
<div>
 <nav id="navbarExample" class="navbar navbar-expand-lg fixed-top navbar-light" aria-label="Main navigation">
  <div class="container">

    
    
       <a class="navbar-brand logo-text" href="#">Izzati Suhaimi</a> 

      <button class="navbar-toggler p-0 border-0" type="button" id="navbarSideCollapse" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
      </button>

      <div class="navbar-collapse offcanvas-collapse" id="navbarsExampleDefault">
          <ul class="navbar-nav ms-auto navbar-nav-scroll">
              <li class="nav-item">
                  <a class="nav-link active" aria-current="page" href="#header">Home</a>
              </li>
              <li class="nav-item">
                  <a class="nav-link" href="#about">About</a>
              </li>
              <li class="nav-item">
                  <a class="nav-link" href="#skills">Skills</a>
              </li>
              <li class="nav-item">
                  <a class="nav-link" href="#projects">Projects</a>
              </li>
              <li class="nav-item">
                  <a class="nav-link" href="#contact">Contact</a>
              </li>
          </ul>
      </div> 
  </div> 
</nav>

<header id="header" class="header">
  <div class="container">
      <div class="row">
          <div class="col-lg-6 col-xl-5">
              <div class="text-container">
                  <h1 class="h1-large">Hello, Im Izzati Suhaimi</h1>
                  <p class="p-large">A passionate learner who is currently enrolled at UTeM and majoring in Software Engineering. </p>
                  <a class="btn-solid-lg" href="https://www.linkedin.com/in/nurul-izzati-suhaimi-80b538209/" target="_black">Click here to view my resume</a>
              </div>
          </div> 
          <div class="col-lg-6 col-xl-7">
              <div class="image-container">
                  <img class="img-fluid" src="assets/images/creativity.png" alt="alternative" />
              </div> 
          </div> 
      </div> 
  </div> 
</header> 

<div id="about" class="basic-1">
  <div class="container">
      <div class="row">
          <div class="col-lg-6 col-xl-7">
              <div class="image-container">
                  <img class="img-fluid" src="assets/images/learning.png" alt="alternative" />
              </div> 
          </div> 
          <div class="col-lg-6 col-xl-5">
              <div class="text-container">
                  <h2>About Me</h2>
                  <p class="p-large">This year, I'll be 22 years old, and I'm hoping to enhance my skills in system analyst and software testing to further my career. I'm looking for a fun way to learn more about project management, app development, and other software development topics at your company. I am a dynamic team player eager to contribute to the domains of system and networking, apps, and online development, as well as actively supporting a forward-thinking firm's success.</p>
              </div> 
          </div> 
      </div>
  </div> 
</div>




<div id="skills" class="basic-2">
  <div class="container">
      <div class="row">
          <div class="col-lg-6 col-xl-5">
              <div class="text-container">
                  <h2>Skills</h2>
                  <div class="section-title">C++/C#</div>
                 <div class="progress">
                    <div class="progress-bar progress-bar-striped" role="progressbar" style="width: 80%" aria-valuenow="10" aria-valuemin="0" aria-valuemax="100"></div>
                    </div>
                    <div class="section-title">Java</div>
                    <div class="progress">
                    <div class="progress-bar progress-bar-striped bg-success" role="progressbar" style="width: 65%" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
                    </div>
                    <div class="section-title">MySQL</div>
                    <div class="progress">
                    <div class="progress-bar progress-bar-striped bg-info" role="progressbar" style="width: 70%" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100"></div>
                    </div>
                    <div class="section-title">PHP, JavaScript</div>
                    <div class="progress">
                    <div class="progress-bar progress-bar-striped bg-warning" role="progressbar" style="width: 75%" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100"></div>
                    </div>
                    <div class="section-title">Android</div>
                    <div class="progress">
                    <div class="progress-bar progress-bar-striped bg-danger" role="progressbar" style="width: 90%" aria-valuenow="100" aria-valuemin="0" aria-valuemax="100"></div>
                    </div>
              </div> 
          </div> 
          <div class="col-lg-6 col-xl-7">
              <div class="image-container">
                  <img class="img-fluid" src="assets/images/books.png" alt="alternative" />
              </div> 
          </div> 
      </div>
  </div> 
</div> 


<div id="projects" class="cards-2 bg-gray">
  <div class="container">
      <div class="row">
          <div class="col-lg-12">
              <h2 class="h2-heading">Recent Projects</h2>
          </div> 
      </div>
      <div class="row">
          <div class="col-lg-12">

              
              <div class="card">
                  <img class="quotes" src="assets/images/quotes.svg" alt="alternative" />
                  <div class="card-body">
                      <p class="testimonial-text">Suspendisse vitae enim arcu. Aliqu convallis risus a felis blandit, at mollis nisi bibendum aliquam noto ricos</p>
                      <div class="testimonial-author">{{ githubData[0].full_name }}</div>
                      <div class="occupation">General Manager, Presentop</div>
                  </div>
                  <div class="gradient-floor red-to-blue"></div>
              </div>
            

              
              <div class="card">
                  <img class="quotes" src="assets/images/quotes.svg" alt="alternative" />
                  <div class="card-body">
                      <p class="testimonial-text">Suspendisse vitae enim arcu. Aliqu convallis risus a felis blandit, at mollis nisi bibendum aliquam noto ricos</p>
                      <div class="testimonial-author">Sam Bloom</div>
                      <div class="occupation">General Manager, Presentop</div>
                  </div>
                  <div class="gradient-floor blue-to-purple"></div>
              </div>
            

              
              <div class="card">
                  <img class="quotes" src="assets/images/quotes.svg" alt="alternative" />
                  <div class="card-body">
                      <p class="testimonial-text">Suspendisse vitae enim arcu. Aliqu convallis risus a felis blandit, at mollis nisi bibendum aliquam noto ricos</p>
                      <div class="testimonial-author">Bill McKenzie</div>
                      <div class="occupation">General Manager, Presentop</div>
                  </div>
                  <div class="gradient-floor purple-to-green"></div>
              </div>
            
              
              
              <div class="card">
                  <img class="quotes" src="assets/images/quotes.svg" alt="alternative" />
                  <div class="card-body">
                      <p class="testimonial-text">Suspendisse vitae enim arcu. Aliqu convallis risus a felis blandit, at mollis nisi bibendum aliquam noto ricos</p>
                      <div class="testimonial-author">Vanya Dropper</div>
                      <div class="occupation">General Manager, Presentop</div>
                  </div>
                  <div class="gradient-floor red-to-blue"></div>
              </div>
            

              
              <div class="card">
                  <img class="quotes" src="assets/images/quotes.svg" alt="alternative" />
                  <div class="card-body">
                      <p class="testimonial-text">Suspendisse vitae enim arcu. Aliqu convallis risus a felis blandit, at mollis nisi bibendum aliquam noto ricos</p>
                      <div class="testimonial-author">Lefty Brown</div>
                      <div class="occupation">General Manager, Presentop</div>
                  </div>
                  <div class="gradient-floor blue-to-purple"></div>
              </div>
            

              
              <div class="card">
                  <img class="quotes" src="assets/images/quotes.svg" alt="alternative" />
                  <div class="card-body">
                      <p class="testimonial-text">Suspendisse vitae enim arcu. Aliqu convallis risus a felis blandit, at mollis nisi bibendum aliquam noto ricos</p>
                      <div class="testimonial-author">Susane Blake</div>
                      <div class="occupation">General Manager, Presentop</div>
                  </div>
                  <div class="gradient-floor purple-to-green"></div>
              </div>          

          </div> 
      </div>
  </div> 
</div> 


<div id="contact" class="form-1">
  <div class="container">
      <div class="row">
          <div class="col-lg-6">
              <div class="text-container">
                  <h2>Contact Me</h2>
                  <p>Get connected to me.</p>
                  <ul class="list-unstyled li-space-lg">
                      <li class="d-flex">
                          <i class="fas fa-square"></i>
                          <div class="flex-grow-1">izzatisuhaimi@icloud.com</div>
                      </li>
                      <li class="d-flex">
                          <i class="fas fa-square"></i>
                          <div class="flex-grow-1">+60 11 2671 0575</div>
                      </li>
                      <li class="d-flex">
                          <i class="fas fa-square"></i>
                          <div class="flex-grow-1">30, Jln SB 7, Taman Seri Bestari, 43900, Sepang, Selangor</div>
                      </li>
                  </ul>
                  
              </div> 
          </div> 
          <div class="col-lg-6">
                  <div class="col-lg-6 col-xl-7">
                    <div class="image-container">
                        <img class="img-fluid" src="assets/images/love-message.png" alt="alternative" />
                </div> 
                </div> 
          </div> 
      </div>
  </div> 
</div>

<div class="footer bg-gray">
  <img class="decoration-circles" src="assets/images/decoration-circles.png" alt="alternative" />
  <div class="container">
      <div class="row">
          <div class="col-lg-12">
              <h4>Get connected to me</h4>
              <div class="social-container">
                  <span class="fa-stack">
                      <a href="#your-link">
                          <i class="fas fa-circle fa-stack-2x"></i>
                          <i class="fab fa-facebook-f fa-stack-1x"></i>
                      </a>
                  </span>
                  <span class="fa-stack">
                      <a href="#your-link">
                          <i class="fas fa-circle fa-stack-2x"></i>
                          <i class="fab fa-twitter fa-stack-1x"></i>
                      </a>
                  </span>
                  <span class="fa-stack">
                      <a href="#your-link">
                          <i class="fas fa-circle fa-stack-2x"></i>
                          <i class="fab fa-pinterest-p fa-stack-1x"></i>
                      </a>
                  </span>
                  <span class="fa-stack">
                      <a href="#your-link">
                          <i class="fas fa-circle fa-stack-2x"></i>
                          <i class="fab fa-instagram fa-stack-1x"></i>
                      </a>
                  </span>
                  <span class="fa-stack">
                      <a href="#your-link">
                          <i class="fas fa-circle fa-stack-2x"></i>
                          <i class="fab fa-youtube fa-stack-1x"></i>
                      </a>
                  </span>
              </div> 
          </div> 
      </div>
  </div> 
</div> 

<button id="myBtn">
  <img src="assets/images/up-arrow.png" alt="alternative" />
</button>
</div>
</template>

<script>
import axios from 'axios'
export default ({
    data() {
        return {
            githubData:[]
        }
    },
    created(){
        this.getGithubData()
    },
    methods:{
        getGithubData(){
            axios.get('https://api.github.com/users/ztnuyu/repos').then(resp => {
            this.githubData = resp.data
            console.log(resp.data);
            });
        }
    }
})
</script>
