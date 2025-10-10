<!-- Оны GitHub README.md ішіне де қоюға болады -->
<style>
  .profile {
    display: flex;
    flex-direction: column; /* баған бойынша: аватар -> мәтін -> иконкалар */
    align-items: center;    /* горизонталь бойынша центрлейді */
    gap: 12px;              /* элементтер арасындағы ара қашықтық */
    max-width: 760px;
    margin: 0 auto;         /* бетте ортасына қою */
    padding: 16px;
  }

  .profile-header {
    display: flex;
    align-items: center;
    gap: 12px;
    flex-wrap: wrap;        /* шағын экранда аватар пен мәтін қатарға сыяды */
    justify-content: center;
    text-align: center;
  }

  .profile-header img.avatar {
    width: 48px;
    height: 48px;
    border-radius: 8px;
    object-fit: cover;
  }

  .profile h3 {
    margin: 0;
    font-size: 1.1rem;
  }

  .profile p {
    margin: 0;
    color: #444;
  }

  .icons {
    display: flex;
    gap: 10px;
    flex-wrap: wrap;        /* егер орын жетпесе жолға оралады */
    justify-content: center;
    margin-top: 8px;
  }

  .icons img {
    width: 50px;
    height: 50px;
    object-fit: contain;
  }

  /* Қосымша: кішкене экранда иконкалар ұсақтау */
  @media (max-width: 420px) {
    .icons img { width: 36px; height: 36px; }
    .profile-header img.avatar { width: 40px; height: 40px; }
  }
</style>

<div class="profile">
  <div class="profile-header">
    <h3>Hi, I'm Diyor Mahmudov
      <img class="avatar" src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" alt="wave">
    </h3>
    <p>I work remotely and like to travel a lot.</p>
  </div>

  <div>
    <strong>Languages and tools I work with:</strong>
  </div>

  <div class="icons">
    <img src="https://cdn.freebiesupply.com/logos/large/2x/html5-2-logo-png-transparent.png" alt="HTML5">
    <img src="https://cdn.freebiesupply.com/logos/large/2x/css3-3-logo-png-transparent.png" alt="CSS3">
    <img src="https://cdn.freebiesupply.com/logos/large/2x/javascript-logo-png-transparent.png" alt="JS">
    <img src="https://cdn.freebiesupply.com/logos/large/2x/react-2-logo-png-transparent.png" alt="React">
    <img src="https://cdn.freebiesupply.com/logos/large/2x/nodejs-icon.png" alt="Node.js">
  </div>
</div>


