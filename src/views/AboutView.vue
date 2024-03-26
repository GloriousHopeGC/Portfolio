<!-- AboutPage.vue -->
<template>
  <div class="about-page">
    <div class="left-section">
      <div class="profile-info">
        <h1>Your Name</h1>
        <p>Age: XX</p>
        <p>Birthday: DD/MM/YYYY</p>
        <p>Course: Your Course</p>
        <p>Address: Your Address</p>
      </div>
      <div class="motto">
        <p>Your Motto</p>
      </div>
    </div>
    <div class="right-section">
      <img src="/pictures/GHGC.jpg" alt="Your Picture" class="profile-image" />
    </div>
  </div>
</template>

<script>
export default {
  name: 'AboutPage',
  // Your Vue.js logic here
};
</script>

<style scoped>
.about-page {
  display: flex;
  background-color: #f0f0f0; /* Gray background color */
  padding: 20px;
}

.left-section {
  flex: 1;
  padding: 20px;
}

.right-section {
  flex: 1;
  padding: 20px;
}

.profile-info {
  background-color: #fff;
  padding: 20px;
  border-radius: 10px;
  margin-bottom: 20px;
}

.profile-info p {
  margin: 10px 0;
}

.motto {
  background-color: #fff;
  padding: 20px;
  border-radius: 10px;
}

.profile-image {
  width: 100%;
  border-radius: 10px;
}
</style>
