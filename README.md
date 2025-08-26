<style>
  .cv-container { display:flex; flex-wrap:wrap; gap:2rem; font-family:Arial,sans-serif; color:#333; }
  .cv-left { flex:1; min-width:250px; background:#f5f5f5; padding:20px; border-radius:8px; }
  .cv-right { flex:2; min-width:400px; padding:20px; border-left:3px solid #007acc; }
  
  h1 { margin-bottom:0.2rem; color:#007acc; }
  h2 { margin-top:0; font-weight:normal; color:#555; }
  h3 { border-bottom:2px solid #007acc; padding-bottom:4px; margin-top:20px; color:#007acc; }
  
  .skills span { display:inline-block; background:#007acc; color:white; padding:4px 8px; margin:3px 3px 3px 0; border-radius:4px; font-size:0.85rem; }
  
  .job h4 { margin:0; color:#007acc; }
  .duration { font-size:0.85rem; color:#555; }
  .job ul { margin-top:5px; margin-bottom:15px; }
  a { color:#007acc; text-decoration:none; }
  a:hover { text-decoration:underline; }
  
  @media (max-width:800px) {
  .cv-container { flex-direction:column; }
  .cv-right { border-left:none; border-top:3px solid #007acc; }
  }
</style>

# Mon CV test

<div class="cv-container">
  
  <!-- Colonne gauche -->
  <div class="cv-left">
    <h1>GNAVIT</h1>
    <h2>test</h2>
    
    <div class="contact">
      <p>📧 <a href="">gnvt17@gmail.com</a></p>
      <p>🌐 <a href="https://agnavit.github.io">Portfolio ?</a></p>
      <p>💼 <a href="https://linkedin.com/in/tonprofil">LinkedIn (à mettre)</a></p>
      <img 
        width="100" 
        height="100" 
        alt="image" 
        src="https://github.com/user-attachments/assets/3dfa6409-f031-4ef8-8708-5a05f9ad5641" />
      <p><a href="https://github.com/agnavit">GitHub</a></p>
    </div>

    
    <h3>Profil</h3>
    <p>Motivation ?</p>
    
    <h3>Compétences</h3>
    <div class="skills">
      <span>Liste</span>
      <span>des</span>
      <span>Compé</span>
    </div>
  </div>
  
  <!-- Colonne droite -->
  <div class="cv-right">
  
  <h3>Expériences professionnelles</h3>
  
  <div class="job">
    <h4>à mettre</h4>
    <span class="duration">Jan 2022 – Présent</span>
    <ul>
      <li>Développement d’interfaces web réactives avec React</li>
      <li>Collaboration avec l’équipe backend pour intégrer les APIs</li>
      <li>Optimisation des performances et accessibilité</li>
    </ul>
  </div>
  
  <div class="job">
    <h4>à mettre</h4>
    <span class="duration">Juin 2021 – Déc 2021</span>
    <ul>
      <li>Création d’une application interne pour la gestion des stocks</li>
      <li>Mise en place d’une base de données PostgreSQL</li>
      <li>Implémentation de tests unitaires et documentation technique</li>
    </ul>
  </div>
  
  <h3>Formation</h3>
  <p><strong>Licence Economie et Gestion</strong> – <a href="https://unc.nc/formations/licence-economie-et-gestion/">UNC</a>, Nouville (2025 – Aujourd'hui)</p>
  <p><strong>Licence Informatique</strong> – <a href="https://unc.nc/formations/licence-informatique/">UNC</a>, Nouville (2020 – 2022)</p>
  <p><strong>Baccalauréat Scientifique</strong> – Université de Exemple (2018 – 2021)</p>
  
  <h3>Langues</h3>
  <ul>
    <li>Français (natif)</li>
    <li>Anglais</li>
  </ul>
  
  </div>
</div>
