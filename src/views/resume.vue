<template>
     <header>
      <nav>
        <ul>
          <li><router-link to="/">Return Home</router-link></li>
           <li><a href="#resume">Resume</a></li>
        </ul>
      </nav>
    </header>
    <div class="resume">
      <div class="header">
        <img class="profile-picture" src="/pictures/GHGC.png" alt="Profile Picture">
        <div class="info">
         
          <h1>{{ fullName }}</h1>
        </div>
      </div>
      <div class="contact">
        <h2>Contact Information</h2>
        <p>Email: {{ email }}</p>
        <p>Phone: {{ phone }}</p>
        <p>Address: {{ address }}</p>
        <p>Course: {{ profession }}</p>

      </div>
      <div class="education">
        <h2>Education</h2>
        <div v-for="(edu, index) in primaryeducation" :key="index">
          <h3>{{ edu.Primary }}</h3>
          <p>{{ edu.school }}</p>
          <p>{{ edu.year }}</p>
        </div>
      </div>

      <div class="education">
        <div v-for="(edu, index) in secondaryeducation" :key="index">
          <h3>{{ edu.Secondary }}</h3>
          <p>{{ edu.school }}</p>
          <p>{{ edu.year }}</p>
        </div>
      </div>
      <div class="education">
        <div v-for="(edu, index) in territiaryeducation" :key="index">
          <h3>{{ edu.Tertiary}}</h3>
          <p>{{ edu.school }}</p>
          <p>{{ edu.year }}</p>
        </div>
      </div>
      <div class="skills">
        <h2>Skills</h2>
        <p></p>
        <ul>
          <li v-for="(skills, index) in skills" :key="index">{{ skills }}</li>
        </ul>
      </div>
      <div class="achievements">
        <h2>Achievements</h2>
        <p></p>
        <ul>
          <li v-for="(achievement, index) in achievements" :key="index">{{ achievement }}</li>
        </ul>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        fullName: "Glorious Hope Cuyos",
        profession: "Bachelor of Science and Information Technology",
        email: "cuyosglorious@gmail.com",
        phone: "09662379503",
        address: "Purok Shooting star Babag II Lapu-Lapu City",
        primaryeducation: [
          {Primary: "Primary", school: "Babag I Elementary School", year: "2014-2015"}
        ],
        secondaryeducation:[
          {Secondary: "Secondary", school: "Babag I Elementary School", year: "2018-2019"}
        ],
        territiaryeducation:[
          {Tertiary: "Tertiary", school: "Cordova Public College", year: "2020-present"}
        ],
        achievements: [
          "2x Champion in Battle of the Band Competition in ACLC WEEK AND INTRAMURALS",
          "Won first place in BATTLE OF THE BAND ACLC INTRAMURALS",
          "Won first place in BATTLE OF THE BAND ACLC WEEK"
        ],
        skills:[
            "Good at Web Designing",
            "Good At Listening skills",
            "Good In making web-design using Html & bootstrap",
            "Better in Music Industry",
            "Hardworking man",
            "Time management"
        ],
      };
    }
  };
  </script>
  
  <style scoped>
  .resume {
    max-width: 800px;
    margin: 0 auto;
    padding: 20px;
    background-color: #fff; /* Bond paper color */
    border: 1px solid #ccc; /* Border for realistic effect */
  }
  
  .header {
    text-align: center;
  }
  
  .info {
    display: flex;
    align-items: center;
    justify-content: center;
  }
  
  .profile-picture {

    width: 150px;
    height: 150px;
    border-radius: 50%;
    background-color: black;
  }
  
  .contact,
  .education,
  .experience,
  .achievements {
    margin-top: 30px;
  }
  
  h2 {
    margin-top: 10px;
  }
  
  h3 {
    margin-top: 15px;
  }
  
  ul {
    list-style-type: disc;
    padding-left: 20px;
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
  </style>
  
