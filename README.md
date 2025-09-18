<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Saloum Travel</title>
  <meta name="description" content="Saloum Travel - Conseil, orientation et accompagnement pour études, démarches administratives et voyages internationaux.">
  <meta name="keywords" content="Saloum Travel, études à l’étranger, Campus France, Parcoursup, orientation, visas, voyages">
  <meta name="author" content="Saloum Travel">
  <style>
    * { box-sizing: border-box; }
    body { margin: 0; font-family: Arial, sans-serif; line-height: 1.6; background: #f5f7fa; color: #333; }
    header { width: 100%; background: #003366; color: #fff; padding: 1rem; position: sticky; top: 0; z-index: 1000; display: flex; flex-wrap: wrap; justify-content: space-between; align-items: center; }
    .header-left { display: flex; align-items: center; gap: 10px; }
    .logo { height: 50px; width: auto; }
    header h1 { margin: 0; font-size: 1.5rem; }
    nav { display: flex; flex-wrap: wrap; gap: 10px; }
    nav a { color: #fff; text-decoration: none; font-weight: bold; }
    nav a:hover { text-decoration: underline; }
    .lang-switch { background: #ffcc00; border: none; padding: 5px 10px; cursor: pointer; border-radius: 5px; font-weight: bold; }
    main section { padding: 2rem; max-width: 1000px; margin: auto; }
    main section:nth-child(even) { background: #fff; }
    h2, h3 { color: #003366; }
    h3 { margin-top: 2rem; }
    .team { display: grid; grid-template-columns: repeat(auto-fit, minmax(180px, 1fr)); gap: 20px; text-align: center; }
    .team div { background: #e6ecf2; padding: 15px; border-radius: 10px; }
    form { display: grid; gap: 10px; max-width: 500px; }
    label { font-weight: bold; }
    input, textarea, button { padding: 10px; border-radius: 5px; border: 1px solid #ccc; font-family: inherit; }
    button { background: #003366; color: white; font-weight: bold; cursor: pointer; border: none; }
    button:hover { background: #002244; }
    footer { text-align: center; padding: 1rem; background: #003366; color: white; margin-top: 2rem; }
    @media (max-width: 600px) {
      header { flex-direction: column; align-items: flex-start; gap: 10px; }
      .header-left { flex-direction: row; align-items: center; }
      nav { flex-direction: column; gap: 5px; }
      .lang-switch { margin-top: 10px; }
    }
  </style>
</head>
<body>
  <header>
    <div class="header-left">
      <img src="logo.png" alt="Logo Saloum Travel" class="logo">
      <h1>Saloum Travel</h1>
    </div>
    <nav>
      <a href="#accueil" data-fr="Accueil" data-en="Home">Accueil</a>
      <a href="#services" data-fr="Services" data-en="Services">Services</a>
      <a href="#equipe" data-fr="Équipe" data-en="Team">Équipe</a>
      <a href="#contact" data-fr="Contact" data-en="Contact">Contact</a>
    </nav>
    <button class="lang-switch" onclick="switchLang()" aria-label="Changer la langue">EN</button>
  </header>

  <main>
    <section id="accueil">
      <h2 data-fr="Bienvenue chez Saloum Travel" data-en="Welcome to Saloum Travel">Bienvenue chez Saloum Travel</h2>
      <p data-fr="Cabinet de conseil, d'orientation et d'accompagnement de démarches administratives et voyages internationaux." 
         data-en="We support students in their study choices, administrative procedures, and international travel.">Cabinet de conseil, d'orientation et d'accompagnement de démarches administratives et voyages internationaux.</p>
    </section>

      <section id="services">
      <h2 data-fr="Nos Services" data-en="Our Services">Nos Services</h2>
      <p data-fr="Nous guidons les étudiants dans le choix de leur formation, les démarches administratives et l’aventure internationale. Orientation, visas, hébergement et voyages : nous accompagnons chaque année les étudiants pour transformer leurs projets en réussites concrètes, en France via les préinscriptions Campus France et Parcoursup. De l’inscription à l’installation, nous prenons en charge toutes les étapes pour que votre expérience internationale soit sereine et enrichissante. Nous organisons vos voyages et séjours à l’étranger, réservons vos billets et hôtels, et assistons votre installation. Tous nos services sont pensés pour simplifier la vie des étudiants et leur permettre de profiter pleinement de leur expérience internationale, en toute sécurité et avec sérénité." 
         data-en="We guide students through their choice of program, administrative procedures, and international adventure. Orientation, visas, accommodation, and travel: every year, we support students to transform their projects into concrete successes in France via Campus France and Parcoursup pre-registrations. From registration to settling in, we take care of every step to ensure your international experience is smooth and enriching. We organize your trips and stays abroad, book your tickets and hotels, and assist with your settling in. All our services are designed to simplify students' lives and allow them to fully enjoy their international experience, safely and with peace of mind.">
        Nous guidons les étudiants dans le choix de leur formation, les démarches administratives et l’aventure internationale. Orientation, visas, hébergement et voyages : nous accompagnons chaque année les étudiants pour transformer leurs projets en réussites concrètes, en France via les préinscriptions Campus France et Parcoursup. De l’inscription à l’installation, nous prenons en charge toutes les étapes pour que votre expérience internationale soit sereine et enrichissante. Nous organisons vos voyages et séjours à l’étranger, réservons vos billets et hôtels, et assistons votre installation. Tous nos services sont pensés pour simplifier la vie des étudiants et leur permettre de profiter pleinement de leur expérience internationale, en toute sécurité et avec sérénité.
      </p>
      <h3 data-fr="Nos Slogans" data-en="Our Slogans">Nos Slogans</h3>
      <ul>
        <li data-fr="« Étudiez, voyagez, réussissez ! »" data-en="“Study, travel, succeed!”">« Étudiez, voyagez, réussissez ! »</li>
        <li data-fr="« Étudier à l’étranger n’a jamais été aussi simple »" data-en="“Studying abroad has never been easier”">« Étudier à l’étranger n’a jamais été aussi simple »</li>
        <li data-fr="« Étudier partout, réussir toujours »" data-en="“Study everywhere, succeed always”">« Étudier partout, réussir toujours »</li>
        <li data-fr="« Le monde vous attend, nous vous guidons »" data-en="“The world awaits you, we guide you”">« Le monde vous attend, nous vous guidons »</li>
        <li data-fr="« De l’inscription au départ, on s’occupe de tout »" data-en="“From registration to departure, we take care of everything”">« De l’inscription au départ, on s’occupe de tout »</li>
        <li data-fr="« Formations, visas, voyages… simplifiés ! »" data-en="“Training, visas, travel… simplified!”">« Formations, visas, voyages… simplifiés ! »</li>
        <li data-fr="« Votre aventure internationale commence ici »" data-en="“Your international adventure starts here”">« Votre aventure internationale commence ici »</li>
      </ul>
    </section>
   
    <section id="equipe">
      <h2 data-fr="Notre Équipe" data-en="Our Team">Notre Équipe</h2>
      <div class="team">
        <div><strong>Khalifa Ababacar Cisse</strong><br><span data-fr="Président Directeur Général et Représentant en France" data-en="CEO and Representative in France">Président Directeur Général et Représentant en France</span></div>
        <div><strong>Bada Bèye</strong><br><span data-fr="Conseil et orientation sur le parcours d'études" data-en="Advice and guidance on the study path">Conseil et orientation sur le parcours d'études</span></div>
        <div><strong>Abdoulaye Seck</strong><br><span data-fr="Chargés Relations Clients" data-en="Clients Relations">Chargés Relations Clients</span></div>
      </div>
    </section>

    <section id="contact">
      <h2 data-fr="Contactez-nous" data-en="Contact Us">Contactez-nous</h2>
      <p><strong>Adresse France :</strong> 7 rue du Lin, 35510 Cesson-Sévigné - France<br>
      <strong>Adresse Sénégal :</strong> Keur Mbaye Fall Cité Poste Dakar - Sénégal<br>
      <strong>Email :</strong> saloumtravel.sn@gmail.com<br>
      <strong>Tél. France :</strong> +33 (0)6 51 45 98 71<br>
      <strong>Tél. Sénégal :</strong> +221 70 467 40 01</p>




      <form id="contactForm" action="https://formspree.io/f/xxxxxxx" method="POST">
        <label for="name" data-fr="Nom" data-en="Name">Nom</label>
        <input type="text" id="name" name="name" placeholder="Votre nom / Your name" required data-fr="Votre nom" data-en="Your name">

        <label for="email" data-fr="Email" data-en="Email">Email</label>
        <input type="email" id="email" name="email" placeholder="Votre email / Your email" data-fr="Votre email" data-en="Your email">
        <!-- ✅ Email facultatif -->

        <label for="numero" data-fr="Numéro" data-en="Number">Numéro</label>
        <input type="tel" id="numero" name="numero" placeholder="Votre numéro / Your number" data-fr="Votre numéro" data-en="Your number">
        <!-- ✅ Numéro facultatif, mais contrôlé par JS -->

        <label for="message" data-fr="Message" data-en="Message">Message</label>
        <textarea id="message" name="message" rows="5" placeholder="Votre message / Your message" required data-fr="Votre message" data-en="Your message"></textarea>

        <button type="submit" data-fr="Envoyer" data-en="Send">Envoyer</button>
      </form>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Saloum Travel - Tous droits réservés</p>
  </footer>

  <script>
    let currentLang = "fr";
    function switchLang() {
      currentLang = currentLang === "fr" ? "en" : "fr";
      document.querySelectorAll("[data-fr][data-en]").forEach(el => {
        if (el.tagName === "INPUT" || el.tagName === "TEXTAREA") {
          el.placeholder = el.getAttribute("data-" + currentLang);
        } else {
          el.textContent = el.getAttribute("data-" + currentLang);
        }
      });
      document.querySelector(".lang-switch").textContent = currentLang === "fr" ? "EN" : "FR";
    }

    document.getElementById("contactForm").addEventListener("submit", function(event) {
      const email = document.getElementById("email").value.trim();
      const numero = document.getElementById("numero").value.trim();
      if (!email && !numero) {
        alert("Veuillez saisir au moins un email ou un numéro de téléphone.");
        event.preventDefault();
      }
    });
  </script>
</body>
</html>
