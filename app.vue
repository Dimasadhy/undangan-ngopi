<template>
  <div>
    <div class="container">
      <h1>Undangan Acara Ngopi</h1>
      <p>Hai! Kami mengundang anda sekalian/kabehan ke acara ngopi rumah Dimas</p>

      <div class="event-details">
        <h2>Detail Acara:</h2>
        <p><strong>Tanggal:</strong> 4 Agustus 2024</p>
        <p><strong>Waktu:</strong> Pukul 19.00 WIB</p>
        <p><strong>Tempat:</strong> Jl. Gobang Rumah Dimas</p>
      </div>


    </div>
  </div>
</template>

<script>
export default {
  setup() {


    return {}
  }
}
</script>

<style scoped>
body {
  font-family: Arial, sans-serif;
  background-color: #f2f2f2;
  margin: 0;
  padding: 0;
}

.container {
  max-width: 600px;
  margin: 40px auto;
  background-color: #fff;
  padding: 40px;
  border-radius: 4px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
}

h1 {
  color: #333;
  font-size: 28px;
  margin-bottom: 20px;
}

p {
  color: #555;
  line-height: 1.6;
  margin-bottom: 15px;
}

.event-details {
  margin-top: 30px;
  padding-top: 30px;
  border-top: 1px solid #ddd;
}

.event-details h2 {
  color: #333;
  font-size: 24px;
  margin-bottom: 10px;
}

.event-details p {
  margin-bottom: 15px;
}

.cta-button {
  margin-top: 30px;
}

.cta-button a {
  background-color: #428bca;
  color: #fff;
  text-decoration: none;
  padding: 10px 20px;
  border-radius: 4px;
  transition: background-color 0.3s;
}

.cta-button a:hover {
  background-color: #3071a9;
}

/* Responsiveness for mobile */
@media screen and (max-width: 480px) {
  .container {
    padding: 20px;
  }

  h1 {
    font-size: 24px;
  }

  .event-details h2 {
    font-size: 20px;
  }
}
</style>