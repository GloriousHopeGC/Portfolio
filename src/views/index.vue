<template>
  <div class="portfolio">
    <header>
      <nav>
        <ul>
          <li><a href="#home">Home</a></li>
          <li><a href="#about">About</a></li>
          <li><a href="#services">Services</a></li>
          <li><a href="#worksamples">My work</a></li>
          <li><a href="#achievements">Achievements</a></li>
          <li><a href="#contact">Contact Me</a></li>
        </ul>
      </nav>
    </header>

    <main>
      <div class="welcome-section">
        <div class="background-image">
          <img src="/pictures/drum2.jpg" alt="Background Image" class="background-img" />
        </div>
        <div class="overlay-text">
          <h1>Welcome to my portfolio</h1>
          <p>A Programmer, Musician, Follower of Christ</p>
        </div>
      </div>
    </main>

    
    <!-- About Page -->
    <div id="about"class="about-page">
      <h1>About Me</h1> <!-- Title added -->
      <div class="profile-section">
        <div class="profile-image">
          <img src="/pictures/GHGC.png" alt="Your Picture" />
        </div>
        <div class="profile-info">
          <h2>Glorious Hope G. Cuyos</h2> <!-- Changed to h2 for the name -->
          <br>
          <p>Age: 21</p>
          <p>Birthday: 07/25/2002</p> <!-- Birthday moved after Age -->
          <p>Course: Bachelor of Science And Information Technology</p> <!-- Corrected typo -->
          <p>Address: Purok Shooting Star Babag II Lapu-Lapu City</p>
          <p>Hobbies: Playing instruments, Coding, Playing Online Games, Playing Offline</p>
          <div class="motto">
            <p>"Never Give up no matter what the situation is"</p>
            <br>
            <p>"&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Hello My name Is Glorious Hope Guillen Cuyos. 21 years of age. Becoming 22 this 25th day of July 2024. 
              I take the course of BSIT- Bachelor of Science And Information Tchnology. My hobbies are Playing Intruments, 
              Drumset is my favorate to play. I hate coding when it runs error. but i love coding when it found 0 errors and lastly i love to play online and offline games such as Minecraft,
               Nba Basketball and etc."</p>
          </div>
        </div>
      </div>
    </div>
    <!-- End About Page  -->


      <!-- Services Page -->
    <div id="services" class="services-page">
      <h1>Services</h1> <!-- Title added -->
      <div class="services-container">
        <div class="service">
          <div class="card">
            <svg xmlns="http://www.w3.org/2000/svg" width="50" height="50" fill="currentColor" class="bi bi-display" viewBox="0 0 16 16"> <path d="M0 4s0-2 2-2h12s2 0 2 2v6s0 2-2 2h-4q0 1 .25 1.5H11a.5.5 0 0 1 0 1H5a.5.5 0 0 1 0-1h.75Q6 13 6 12H2s-2 0-2-2zm1.398-.855a.76.76 0 0 0-.254.302A1.5 1.5 0 0 0 1 4.01V10c0 .325.078.502.145.602q.105.156.302.254a1.5 1.5 0 0 0 .538.143L2.01 11H14c.325 0 .502-.078.602-.145a.76.76 0 0 0 .254-.302 1.5 1.5 0 0 0 .143-.538L15 9.99V4c0-.325-.078-.502-.145-.602a.76.76 0 0 0-.302-.254A1.5 1.5 0 0 0 13.99 3H2c-.325 0-.502.078-.602.145"/></svg>
            <div class="card-content">
              <h2>Computer System Servicing</h2>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Repudiandae recusandae facere ut quidem praesentium alias fuga repellat obcaecati ad cum provident quisquam doloremque possimus excepturi facilis, incidunt ratione magni voluptas?</p>
            </div>
          </div>
        </div>
        <!-- Service 2 -->
        <div class="service">
          <div class="card">
            <!-- SVG Icon for Service 2 -->
            <svg xmlns="http://www.w3.org/2000/svg" width="50" height="50" fill="currentColor" class="bi bi-music-note-list" viewBox="0 0 16 16">
              <path d="M12 13c0 1.105-1.12 2-2.5 2S7 14.105 7 13s1.12-2 2.5-2 2.5.895 2.5 2"/><path fill-rule="evenodd" d="M12 3v10h-1V3z"/><path d="M11 2.82a1 1 0 0 1 .804-.98l3-.6A1 1 0 0 1 16 2.22V4l-5 1z"/> <path fill-rule="evenodd" d="M0 11.5a.5.5 0 0 1 .5-.5H4a.5.5 0 0 1 0 1H.5a.5.5 0 0 1-.5-.5m0-4A.5.5 0 0 1 .5 7H8a.5.5 0 0 1 0 1H.5a.5.5 0 0 1-.5-.5m0-4A.5.5 0 0 1 .5 3H8a.5.5 0 0 1 0 1H.5a.5.5 0 0 1-.5-.5"/></svg>
            <div class="card-content">
              <h2>Gigs</h2>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Repudiandae recusandae facere ut quidem praesentium alias fuga repellat obcaecati ad cum provident quisquam doloremque possimus excepturi facilis, incidunt ratione magni voluptas?</p>
            </div>
          </div>
        </div>
        <!-- Service 3 -->
        <div class="service">
          <div class="card">
            <!-- SVG Icon for Service 3 -->
            <svg xmlns="http://www.w3.org/2000/svg" width="50" height="50" fill="currentColor" class="bi bi-globe" viewBox="0 0 16 16">
              <path d="M0 8a8 8 0 1 1 16 0A8 8 0 0 1 0 8m7.5-6.923c-.67.204-1.335.82-1.887 1.855A8 8 0 0 0 5.145 4H7.5zM4.09 4a9.3 9.3 0 0 1 .64-1.539 7 7 0 0 1 .597-.933A7.03 7.03 0 0 0 2.255 4zm-.582 3.5c.03-.877.138-1.718.312-2.5H1.674a7 7 0 0 0-.656 2.5zM4.847 5a12.5 12.5 0 0 0-.338 2.5H7.5V5zM8.5 5v2.5h2.99a12.5 12.5 0 0 0-.337-2.5zM4.51 8.5a12.5 12.5 0 0 0 .337 2.5H7.5V8.5zm3.99 0V11h2.653c.187-.765.306-1.608.338-2.5zM5.145 12q.208.58.468 1.068c.552 1.035 1.218 1.65 1.887 1.855V12zm.182 2.472a7 7 0 0 1-.597-.933A9.3 9.3 0 0 1 4.09 12H2.255a7 7 0 0 0 3.072 2.472M3.82 11a13.7 13.7 0 0 1-.312-2.5h-2.49c.062.89.291 1.733.656 2.5zm6.853 3.472A7 7 0 0 0 13.745 12H11.91a9.3 9.3 0 0 1-.64 1.539 7 7 0 0 1-.597.933M8.5 12v2.923c.67-.204 1.335-.82 1.887-1.855q.26-.487.468-1.068zm3.68-1h2.146c.365-.767.594-1.61.656-2.5h-2.49a13.7 13.7 0 0 1-.312 2.5m2.802-3.5a7 7 0 0 0-.656-2.5H12.18c.174.782.282 1.623.312 2.5zM11.27 2.461c.247.464.462.98.64 1.539h1.835a7 7 0 0 0-3.072-2.472c.218.284.418.598.597.933M10.855 4a8 8 0 0 0-.468-1.068C9.835 1.897 9.17 1.282 8.5 1.077V4z"/></svg>
            <div class="card-content">
              <h2>Web Development</h2>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Repudiandae recusandae facere ut quidem praesentium alias fuga repellat obcaecati ad cum provident quisquam doloremque possimus excepturi facilis, incidunt ratione magni voluptas?</p>
            </div>
          </div>
        </div>
      </div>
    </div>
      <div id="services" class="services-page">
      <div class="services-container">
        <div class="service">
          <div class="card">
            <svg xmlns="http://www.w3.org/2000/svg" width="50" height="50" fill="currentColor" class="bi bi-check-circle" viewBox="0 0 16 16"><path d="M8 15A7 7 0 1 1 8 1a7 7 0 0 1 0 14m0 1A8 8 0 1 0 8 0a8 8 0 0 0 0 16"/><path d="m10.97 4.97-.02.022-3.473 4.425-2.093-2.094a.75.75 0 0 0-1.06 1.06L6.97 11.03a.75.75 0 0 0 1.079-.02l3.992-4.99a.75.75 0 0 0-1.071-1.05"/></svg>
            <div class="card-content">
              <h2>100% Legitimate</h2>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Repudiandae recusandae facere ut quidem praesentium alias fuga repellat obcaecati ad cum provident quisquam doloremque possimus excepturi facilis, incidunt ratione magni voluptas?</p>
            </div>
          </div>
        </div>
        <!-- Service 2 -->
        <div class="service">
          <div class="card">
            <!-- SVG Icon for Service 2 -->
            <svg xmlns="http://www.w3.org/2000/svg" width="50" height="50" fill="currentColor" class="bi bi-clock" viewBox="0 0 16 16"><path d="M8 3.5a.5.5 0 0 0-1 0V9a.5.5 0 0 0 .252.434l3.5 2a.5.5 0 0 0 .496-.868L8 8.71z"/><path d="M8 16A8 8 0 1 0 8 0a8 8 0 0 0 0 16m7-8A7 7 0 1 1 1 8a7 7 0 0 1 14 0"/></svg>
            <div class="card-content">
              <h2>Time Management</h2>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Repudiandae recusandae facere ut quidem praesentium alias fuga repellat obcaecati ad cum provident quisquam doloremque possimus excepturi facilis, incidunt ratione magni voluptas?</p>
            </div>
          </div>
        </div>
        <!-- Service 3 -->
        <div class="service">
          <div class="card">
            <!-- SVG Icon for Service 3 -->
            <svg xmlns="http://www.w3.org/2000/svg" width="50" height="50" fill="currentColor" class="bi bi-calendar-check" viewBox="0 0 16 16"><path d="M10.854 7.146a.5.5 0 0 1 0 .708l-3 3a.5.5 0 0 1-.708 0l-1.5-1.5a.5.5 0 1 1 .708-.708L7.5 9.793l2.646-2.647a.5.5 0 0 1 .708 0"/><path d="M3.5 0a.5.5 0 0 1 .5.5V1h8V.5a.5.5 0 0 1 1 0V1h1a2 2 0 0 1 2 2v11a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2V3a2 2 0 0 1 2-2h1V.5a.5.5 0 0 1 .5-.5M1 4v10a1 1 0 0 0 1 1h12a1 1 0 0 0 1-1V4z"/></svg>
            <div class="card-content">
              <h2>On Time</h2>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Repudiandae recusandae facere ut quidem praesentium alias fuga repellat obcaecati ad cum provident quisquam doloremque possimus excepturi facilis, incidunt ratione magni voluptas?</p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- End Services Section -->
    
      <!-- My work -->
      <div id="worksamples" class="services-page">
      <h1>My work</h1> <!-- Title added -->
      <div class="services-container">
        <div class="service">
          <div class="card">
            <img src="/pictures/AGCOWC CIRCULAR.png" alt="Work Sample 1" class="work-sample-img" />
            <div class="card-content">
              <h2>AGCOWC CHURCH WEBSITE</h2>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Repudiandae recusandae facere ut quidem praesentium alias fuga repellat obcaecati ad cum provident quisquam doloremque possimus excepturi facilis, incidunt ratione magni voluptas?</p>
              <a href="https://github.com/GloriousHopeGC/AGCOWC-PROJECT-v1" target="_blank" class="btn">View Work</a>
            </div>
          </div>
        </div>
        <!-- Service 2 -->
        <div class="service">
          <div class="card">
            <!-- SVG Icon for Service 2 -->
            <img src="/pictures/fcfs.png" alt="Work Sample 1" class="work-sample-img" />
            <div class="card-content">
              <h2>FCFS program JS language</h2>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Repudiandae recusandae facere ut quidem praesentium alias fuga repellat obcaecati ad cum provident quisquam doloremque possimus excepturi facilis, incidunt ratione magni voluptas?</p>
              <a href="https://github.com/GloriousHopeGC/PROJECTS/blob/main/FCFC.html" target="_blank" class="btn">View Work</a>
            </div>
          </div>
        </div>
        <!-- Service 3 -->
        <div class="service">
          <div class="card">
            <img src="/pictures/api.png" alt="Work Sample 1" class="work-sample-img" />
            <div class="card-content">
              <h2>Log-in Api</h2>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Repudiandae recusandae facere ut quidem praesentium alias fuga repellat obcaecati ad cum provident quisquam doloremque possimus excepturi facilis, incidunt ratione magni voluptas?</p>
              <a href="https://github.com/GloriousHopeGC/3rd-Yr-2nd-Sem/tree/main/HCI2-API%20LOGIN" target="_blank" class="btn">View Work</a>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- End My work Section -->

    <!-- My Achievements -->
    <div id="achievements" class="services-page">
      <h1>Achievements</h1> <!-- Title added -->
      <div class="services-container">
        <div class="service">
          <div class="card">
            <img src="/pictures/mq1.webp" alt="Work Sample 1" class="work-sample-img" />
            <div class="card-content">
              <h2>BATTLE OF THE BAND CHAMPION In Intramurals</h2>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Repudiandae recusandae facere ut quidem praesentium alias fuga repellat obcaecati ad cum provident quisquam doloremque possimus excepturi facilis, incidunt ratione magni voluptas?</p>
            </div>
          </div>
        </div>
        <!-- Service 2 -->
        <div class="service">
          <div class="card">
            <!-- SVG Icon for Service 2 -->
            <img src="/pictures/mq1.webp" alt="Work Sample 1" class="work-sample-img" />
            <div class="card-content">
              <h2>Battle Of The Band Champion in ACLC week</h2>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Repudiandae recusandae facere ut quidem praesentium alias fuga repellat obcaecati ad cum provident quisquam doloremque possimus excepturi facilis, incidunt ratione magni voluptas?</p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- End My work Section -->
    <!-- Contact Us Section -->
<div id="contact" class="contact-page">
  <div class="contact-container">
    <!-- Contact Form -->
     <!-- Map -->
     <div class="map-container">
      <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3925.8498251957058!2d123.93809117495036!3d10.273681589846143!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x33a99a37eef5d297%3A0x50c0883edca262d9!2sAlmighty%20God%20Center%20Of%20Worship%20Church!5e0!3m2!1sen!2sph!4v1711446241950!5m2!1sen!2sph" width="400" height="300" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
    </div>
    <div class="contact-form">
      <h1>Contact Us</h1> <!-- Title for the contact form -->
      <form>
        <div class="form-group">
          <label for="name">Name:</label>
          <input type="text" id="name" name="name" placeholder="Enter your name" required>
        </div>
        <div class="form-group">
          <label for="address">Address:</label>
          <input type="text" id="address" name="address" placeholder="Enter your address" required>
        </div>
        <div class="form-group">
          <label for="email">Email:</label>
          <input type="email" id="email" name="email" placeholder="Enter your email" required>
        </div>
        <div class="form-group">
          <label for="mobile">Mobile No.:</label>
          <input type="tel" id="mobile" name="mobile" placeholder="Enter your mobile number" required>
        </div>
        <button type="submit" class="btn">Submit</button>
      </form>
    </div>

   
  </div>
</div>

<!-- Footer -->
<footer class="footer">
  <div class="footer-icons">
    <a href="https://www.facebook.com/tokiwa.sougo.94617" target="_blank" class="icon-facebook"><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-facebook" viewBox="0 0 16 16"><path d="M16 8.049c0-4.446-3.582-8.05-8-8.05C3.58 0-.002 3.603-.002 8.05c0 4.017 2.926 7.347 6.75 7.951v-5.625h-2.03V8.05H6.75V6.275c0-2.017 1.195-3.131 3.022-3.131.876 0 1.791.157 1.791.157v1.98h-1.009c-.993 0-1.303.621-1.303 1.258v1.51h2.218l-.354 2.326H9.25V16c3.824-.604 6.75-3.934 6.75-7.951"/></svg></a>
    <a href="https://www.instagram.com/jberg_restaurant/?hl=en" target="_blank" class="icon-instagram"><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-instagram" viewBox="0 0 16 16"><path d="M8 0C5.829 0 5.556.01 4.703.048 3.85.088 3.269.222 2.76.42a3.9 3.9 0 0 0-1.417.923A3.9 3.9 0 0 0 .42 2.76C.222 3.268.087 3.85.048 4.7.01 5.555 0 5.827 0 8.001c0 2.172.01 2.444.048 3.297.04.852.174 1.433.372 1.942.205.526.478.972.923 1.417.444.445.89.719 1.416.923.51.198 1.09.333 1.942.372C5.555 15.99 5.827 16 8 16s2.444-.01 3.298-.048c.851-.04 1.434-.174 1.943-.372a3.9 3.9 0 0 0 1.416-.923c.445-.445.718-.891.923-1.417.197-.509.332-1.09.372-1.942C15.99 10.445 16 10.173 16 8s-.01-2.445-.048-3.299c-.04-.851-.175-1.433-.372-1.941a3.9 3.9 0 0 0-.923-1.417A3.9 3.9 0 0 0 13.24.42c-.51-.198-1.092-.333-1.943-.372C10.443.01 10.172 0 7.998 0zm-.717 1.442h.718c2.136 0 2.389.007 3.232.046.78.035 1.204.166 1.486.275.373.145.64.319.92.599s.453.546.598.92c.11.281.24.705.275 1.485.039.843.047 1.096.047 3.231s-.008 2.389-.047 3.232c-.035.78-.166 1.203-.275 1.485a2.5 2.5 0 0 1-.599.919c-.28.28-.546.453-.92.598-.28.11-.704.24-1.485.276-.843.038-1.096.047-3.232.047s-2.39-.009-3.233-.047c-.78-.036-1.203-.166-1.485-.276a2.5 2.5 0 0 1-.92-.598 2.5 2.5 0 0 1-.6-.92c-.109-.281-.24-.705-.275-1.485-.038-.843-.046-1.096-.046-3.233s.008-2.388.046-3.231c.036-.78.166-1.204.276-1.486.145-.373.319-.64.599-.92s.546-.453.92-.598c.282-.11.705-.24 1.485-.276.738-.034 1.024-.044 2.515-.045zm4.988 1.328a.96.96 0 1 0 0 1.92.96.96 0 0 0 0-1.92m-4.27 1.122a4.109 4.109 0 1 0 0 8.217 4.109 4.109 0 0 0 0-8.217m0 1.441a2.667 2.667 0 1 1 0 5.334 2.667 2.667 0 0 1 0-5.334"/></svg></a>
    <a href="https://mail.google.com/mail/u/0/#inbox" class="icon-google"><svg xmlns="http://www.w3.org/2000/svg" target="_blank" width="16" height="16" fill="currentColor" class="bi bi-google" viewBox="0 0 16 16"><path d="M15.545 6.558a9.4 9.4 0 0 1 .139 1.626c0 2.434-.87 4.492-2.384 5.885h.002C11.978 15.292 10.158 16 8 16A8 8 0 1 1 8 0a7.7 7.7 0 0 1 5.352 2.082l-2.284 2.284A4.35 4.35 0 0 0 8 3.166c-2.087 0-3.86 1.408-4.492 3.304a4.8 4.8 0 0 0 0 3.063h.003c.635 1.893 2.405 3.301 4.492 3.301 1.078 0 2.004-.276 2.722-.764h-.003a3.7 3.7 0 0 0 1.599-2.431H8v-3.08z"/></svg></a>
  </div>
</footer>

  


  </div>
  
</template>

<script>
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function (e) {
        e.preventDefault();

        document.querySelector(this.getAttribute('href')).scrollIntoView({
            behavior: 'smooth'
        });
    });
});

export default {
  name: 'Portfolio',
  data() {
    return {
      isMobileMenuOpen: false
    };
  },
  methods: {
    toggleMobileMenu() {
      this.isMobileMenuOpen = !this.isMobileMenuOpen;
    }
  }
};
</script>

<style scoped>
/* Your scoped CSS styles go here */
.portfolio {
  /* Portfolio container styles */
}

header {
  background-color: #000; /* Black background color */
  padding: 20px; /* Increase padding for spacing */
}

nav ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  display: flex;
  justify-content: center;
}
.background-img {
  width: 612px;
  height: 700px;
}

nav ul li {
  display: inline;
  margin-right: 30px; /* Increase margin for spacing */
}

nav ul li a {
  text-decoration: none;
  color: #fff; /* Text color */
  font-weight: bold; /* Make text bold */
}

nav ul li a:hover {
  color: #ccc; /* Hover color */
}

main {
  /* Main content styles */
}

.welcome-section {
  position: relative;
}

.background-image {
  position: relative;
}

.background-img {
  width: 100%;
}

.smaller-img {
  position: absolute;
  right: 20px; /* Adjust to position on the right */
  top: 20px; /* Adjust as needed */
  width: 100px; /* Adjust width */
}

.overlay-text {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  color: #fff;
  text-align: center;
}

.overlay-text h1 {
  font-size: 36px;
}

/* Media query for mobile responsiveness */
@media (max-width: 768px) {
  nav ul {
    flex-direction: column;
    align-items: center;
  }

  nav ul li {
    margin: 10px 0;
  }
}

/* About Page Styles */
.about-page {
  display: flex;
  flex-direction: column; /* Added to make the sections stack vertically */
  background-color: #f0f0f0; /* Gray background color */
  padding: 20px;
}

.about-page h1 {
  margin-top: 20px;
  margin-bottom: 20px; /* Added margin for spacing */
  text-align: center; /* Center the text horizontally */
  align-self: center; 
  /* Added margin for spacing */
}
.about-page h2 {
  margin-top: 20px;
  margin-bottom: 20px; /* Added margin for spacing */
  text-align: center; /* Center the text horizontally */
  align-self: center; 
  /* Added margin for spacing */
}
.profile-section {
  display: flex;
}

.profile-image {
  flex: 1;
  padding: 20px;
}

.profile-image img {
  width: 100%;
  border-radius: 10px;
  background-color: #000;
}

.profile-info {
  flex: 2;
  padding: 20px;
}

.profile-info h2 {
  margin-bottom: 10px; /* Added margin below the name */
}

.profile-info p {
  margin: 7px 0; /* Adjusted margin for other profile info */
}

.motto {
  padding: 20px;
  border-radius: 10px;
}
html {
  scroll-behavior: smooth;
}
.services-container {
  display: flex;
  justify-content: space-between; /* Aligns the cards with equal space between them */
}
/* CSS to make the cards responsive */
@media (max-width: 768px) {
  .services-container {
    flex-direction: column; /* Stack cards vertically on small screens */
  }

  .service {
    width: 100%; /* Set the width of each card to 100% on small screens */
    margin: 0 0 20px; /* Adjust margin for spacing */
  }
}


/* CSS to center the icons within the cards */
.card {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  margin-top: 5%;
  margin-right: 5%;
  margin-left: 5%;
}
/* CSS to center the text within the cards */
.card-content {
  text-align: center;
  margin: 30px 30px;
}
/* CSS to center the icons within the cards */
/* CSS to center the icons within the cards and add hover effect */
.card svg {
  margin: 10% 30%; /* Add margin to the top and bottom of the SVG icon */
  transition: fill 0.3s ease; /* Smooth transition effect */
}

.card svg:hover {
  fill: red; /* Change the fill color to red on hover */
}

.services-page h1 {
  margin-top: 20px;
  margin-bottom: 20px; /* Added margin for spacing */
  text-align: center; /* Center the text horizontally */
  align-self: center; 
  /* Added margin for spacing */
}
.services-page h2 {
  font-size: 25px;
  margin-top: 20px;
  margin-bottom: 20px; /* Added margin for spacing */
  text-align: center; /* Center the text horizontally */
  align-self: center; 
  /* Added margin for spacing */
}
.services-page p {
  font-size: 17px;
}
/* CSS to adjust the image size in the services section */
.work-sample-img {
  width: 100%; /* Make the image width 100% of its container */
  height: auto; /* Allow the height to adjust proportionally */
  border-radius: 10px; /* Add border radius for rounded corners */
}
/* CSS to style the button */
.btn {
  color: #fff; /* Set the default color of the button text */
  background-color: #000; /* Set the background color of the button */
  padding: 10px 20px; /* Adjust padding as needed */
  text-decoration: none; /* Remove underline */
  border: none; /* Remove border */
  cursor: pointer; /* Change cursor to pointer on hover */
  transition: color 0.3s ease; /* Smooth transition effect for color change */
}

/* CSS to change button text color on hover */
.btn:hover {
  color: #ad1e1e; /* Change the color of the button text on hover */
}
.achievements-container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.achievement {
  width: 30%; /* Adjust width as needed */
  display: inline-block;
  margin: 0;
  padding: 0;
  text-align: center;
}
/* CSS for Contact Us Section */
.contact-page {
  background-color: #f0f0f0; /* Gray background color */
  padding: 20px;
}

.contact-form form {
  max-width: 500px; /* Set maximum width for the form */
  margin: 0 auto; /* Center the form horizontally */
}

.form-group {
  margin-bottom: 20px; /* Add space between form fields */
}

label {
  display: block; /* Display labels as block elements */
  margin-bottom: 5px; /* Add space below labels */
}

input[type="text"],
input[type="email"],
input[type="tel"] {
  width: 100%; /* Set input fields to fill their container */
  padding: 10px; /* Add padding to input fields */
  border: 1px solid #ccc; /* Add border to input fields */
  border-radius: 5px; /* Add border radius to input fields */
}

button[type="submit"] {
  background-color: #000; /* Button background color */
  color: #fff; /* Button text color */
  padding: 10px 20px; /* Button padding */
  border: none; /* Remove button border */
  border-radius: 5px; /* Button border radius */
  cursor: pointer; /* Set cursor to pointer on hover */
  transition: background-color 0.3s ease; /* Smooth transition for background color */
}

button[type="submit"]:hover {
  background-color: #333; /* Darken button background color on hover */
}
.contact-page h1 {
  margin-top: 20px; /* Adjust top margin */
  margin-bottom: 20px; /* Adjust bottom margin */
  text-align: center; /* Center align text */
}
.contact-page {
  padding: 20px;
}

.contact-container {
  display: flex;
  flex-wrap: wrap;
}

.map-container {
  flex: 1;
  margin-right: 20px; /* Adjust as needed */
}

.map-container iframe {
  width: 100%;
  height: 100%;
}

.contact-form {
  flex: 1;
  max-width: 500px; /* Adjust as needed */
}
.footer {
  background-color: #333;
  color: #fff;
  padding: 20px;
  text-align: center;
}

.footer-icons a {
  color: #fff;
  margin: 0 10px;
  font-size: 24px;
  text-decoration: none;
}

.footer-icons a:hover {
  color: #ccc;
}
/* CSS for hiding navbar items on smaller screens */
@media screen and (max-width: 768px) {
  nav ul li {
    display: none; /* Hide the list items */
  }
}

</style>
