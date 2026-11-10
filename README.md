
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Découvrez nos solutions de financement et de prêt. Contactez notre équipe pour obtenir des informations transparentes.">
  <title>Financement Plus | Solutions de Prêt</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      background: #f5f7fa;
      color: #263445;
      line-height: 1.6;
    }

    header {
      background: #092b50;
      color: white;
      padding: 20px 8%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
    }

    .logo {
      font-size: 25px;
      font-weight: bold;
      color: #f2c14e;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin-left: 20px;
      font-size: 14px;
    }

    .hero {
      background: linear-gradient(120deg, #092b50, #17629a);
      color: white;
      text-align: center;
      padding: 100px 20px;
    }

    .hero h1 {
      font-size: 42px;
      margin-bottom: 20px;
    }

    .hero p {
      max-width: 650px;
      margin: auto;
      font-size: 18px;
    }

    .btn {
      display: inline-block;
      margin-top: 25px;
      padding: 14px 28px;
      background: #f2c14e;
      color: #092b50;
      text-decoration: none;
      font-weight: bold;
      border-radius: 6px;
    }

    section {
      padding: 65px 8%;
      text-align: center;
    }

    section h2 {
      color: #092b50;
      margin-bottom: 20px;
      font-size: 30px;
    }

    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 25px;
      margin-top: 35px;
    }

    .card {
      background: white;
      padding: 30px;
      border-radius: 12px;
      box-shadow: 0 4px 15px rgba(0,0,0,.06);
    }

    .card h3 {
      color: #17629a;
      margin-bottom: 12px;
    }

    .steps {
      background: #eaf0f6;
    }

    .contact {
      background: white;
    }

    .contact form {
      max-width: 500px;
      margin: 25px auto 0;
      display: grid;
      gap: 15px;
    }

    input, textarea {
      width: 100%;
      padding: 14px;
      border: 1px solid #ccd5df;
      border-radius: 6px;
      font-size: 15px;
    }

    button {
      background: #092b50;
      color: white;
      border: none;
      padding: 15px;
      border-radius: 6px;
      cursor: pointer;
      font-size: 16px;
    }

    footer {
      background: #092b50;
      color: white;
      text-align: center;
      padding: 30px 15px;
    }

    footer a {
      color: #f2c14e;
    }

    .disclaimer {
      font-size: 12px;
      color: #d5deea;
      max-width: 750px;
      margin: 15px auto 0;
    }

    @media(max-width: 600px) {
      header {
        justify-content: center;
        gap: 15px;
      }

      nav a {
        margin: 5px;
      }

      .hero h1 {
        font-size: 30px;
      }
    }
  </style>
</head>

<body>

<header>
  <div class="logo">FINANCEMENT PLUS</div>
  <nav>
    <a href="#accueil">Accueil</a>
    <a href="#services">Nos services</a>
    <a href="#etapes">Comment ça marche</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section class="hero" id="accueil">
  <h1>Construisons vos projets financiers</h1>
  <p>
    Découvrez des solutions de financement adaptées à vos besoins.
    Notre équipe vous accompagne avec transparence et professionnalisme.
  </p>
  <a href="#contact" class="btn">Nous contacter</a>
</section>

<section id="services">
  <h2>Nos solutions de financement</h2>
  <p>Des solutions à étudier selon votre situation et votre capacité de remboursement.</p>

  <div class="services">
    <div class="card">
      <h3>Prêt personnel</h3>
      <p>Une solution de financement pour vos projets personnels.</p>
    </div>

    <div class="card">
      <h3>Prêt professionnel</h3>
      <p>Un accompagnement financier pour vos projets professionnels.</p>
    </div>

    <div class="card">
      <h3>Financement de projets</h3>
      <p>Étudiez les possibilités de financement de vos projets.</p>
    </div>
  </div>
</section>

<section class="steps" id="etapes">
  <h2>Comment ça marche ?</h2>

  <div class="services">
    <div class="card">
      <h3>01. Contact</h3>
      <p>Présentez votre projet et vos besoins.</p>
    </div>

    <div class="card">
      <h3>02. Étude</h3>
      <p>Votre demande est examinée selon les critères applicables.</p>
    </div>

    <div class="card">
      <h3>03. Décision</h3>
      <p>Vous recevez une réponse claire concernant votre demande.</p>
    </div>
  </div>
</section>

<section class="contact" id="contact">
  <h2>Contactez notre équipe</h2>
  <p>Pour toute question concernant nos solutions de financement.</p>

  <form action="mailto:contact@votreentreprise.com"
        method="post" enctype="text/plain">

    <input type="text" name="Nom"
           placeholder="Votre nom" required>

    <input type="email" name="Email"
           placeholder="Votre adresse e-mail" required>

    <textarea name="Message" rows="5"
              placeholder="Votre message" required></textarea>

    <button type="submit">Envoyer le message</button>
  </form>
</section>

<footer>
  <p><strong>FINANCEMENT PLUS</strong></p>
  <p>Solutions de financement et accompagnement.</p>
  <p>© 2026 - Tous droits réservés.</p>

  <p class="disclaimer">
    Les informations présentées sur ce site ne constituent pas une offre
    ferme de crédit. Tout financement est soumis à l'étude du dossier,
    aux conditions contractuelles et aux autorisations réglementaires
    applicables. Les coordonnées et mentions légales de l'entreprise
    doivent être complétées avant publication.
  </p>
</footer>

</body>
</html>
