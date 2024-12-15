<script setup>
</script>

<template>
  <section id="home-signup">
    <div class="description">
      <h1>Start Learning with AI</h1>
      <p>The world is evolving, and so should your learning. Ditch outdated methods and embrace AI-powered education. Master new skills, explore passions, and advance your career with smarter, faster, and more effective learning.</p>
    </div>

    <div class="signup-form">
      <form>
        <label for="fullname">Full Name</label>
        <input type="text" id="fullname" placeholder="your name here" />

        <label for="email">Email</label>
        <input type="email" id="email" placeholder="username@gmail.com" />

        <label for="password">Password</label>
        <input type="password" id="password" placeholder="password" />

        <label for="confirm-password">Confirm Password</label>
        <input type="password" id="confirm-password" placeholder="confirm password" />

        <button type="submit">Sign Up</button>
      </form>
      <p>Already have an account? <a href="#login">Login here!!!</a></p>
    </div>
  </section>
</template>

<style scoped>
/* Glavni raspored stranice s centriranjem */
#home-signup {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh; /* Postavlja visinu stranice na cijeli prozor */
  padding-left: 98px; /* Udaljenost sa lijeve strane */
  padding-right: 98px; /* Udaljenost s desne strane */
  gap: 20px; /* Razmak između lijevog i desnog dijela */

}

/* Lijevi dio s opisom */
.description {
  flex: 1;
  max-width: 500px; /* Maksimalna širina za lijevi dio */
}

.description h1 {
  color: #333333;
}

.description p {
  font-size: 1.1rem;
  line-height: 1.6;
  color: #8CA2C0;
}

/* Desni dio sa formom za prijavu */
.signup-form {
  flex: 1;
  max-width: 400px; /* Maksimalna širina za formu */
  background-color: #FFFFFF;
  padding: 2rem;
  border-radius: 10%; /* Zakrivljeni kut od 10% */
  box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2); /* Dodana tamnija sjena */
}


.signup-form label {
  font-weight: bold;
  display: block;
  margin-bottom: 0.5rem;
  color: #333333;
}

.signup-form input {
  width: 93%;
  padding: 0.8rem;
  margin-bottom: 1rem;
  border: 1px solid #A8B9D0;
}

.signup-form button {
  width: 100%;
  padding: 1rem;
  background-color: #624F82;
  color: #FDFEFF;
  border: #FDFEFF;

}

.signup-form button:hover {
  background-color: #8367C7; /* Svjetlija ljubičasta pri hoveru */
}

.signup-form p {
  text-align: center;
  margin-top: 1rem;
  color: #333333;
}

.signup-form a {
  color: #F77B7B;
  font-weight: bold;
}

</style>
