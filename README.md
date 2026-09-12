<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Imran Allround Engineering & IT</title>
    <style>
        body { font-family: Arial, sans-serif; line-height: 1.6; margin: 0; padding: 0; color: #333; }
        header { background: #003366; color: #fff; padding: 35px 20px; text-align: center; }
        .container { padding: 20px; max-width: 950px; margin: auto; }
        .about-container { display: flex; flex-direction: column; gap: 20px; background: #f4f7f6; padding: 25px; border-radius: 8px; margin-bottom: 30px; box-shadow: 0 2px 5px rgba(0,0,0,0.05); }
        .profile-header { display: flex; align-items: center; gap: 20px; }
        .about-image { width: 120px; height: 120px; border-radius: 50%; object-fit: cover; border: 3px solid #003366; background: #eee; }
        .languages-flex { display: flex; flex-direction: row; gap: 20px; margin-top: 15px; }
        .lang-block { flex: 1; background: #fff; padding: 15px; border-radius: 6px; border: 1px solid #e0e0e0; }
        .services { display: flex; flex-direction: column; gap: 15px; margin-top: 20px; }
        .service-box { border-left: 5px solid #003366; padding: 15px; background: #f9f9f9; border-radius: 0 6px 6px 0; }
        
        /* Portfolio Grid */
        .portfolio-grid { display: flex; gap: 20px; margin-top: 20px; }
        .portfolio-item { flex: 1; border: 1px solid #ddd; border-radius: 8px; overflow: hidden; background: #fff; box-shadow: 0 2px 4px rgba(0,0,0,0.05); }
        .portfolio-item img { width: 100%; height: 180px; object-fit: cover; background: #eee; }
        .portfolio-item-desc { padding: 15px; }
        .portfolio-item-desc h4 { margin: 0 0 10px 0; color: #003366; }
        
        footer { background: #333; color: #fff; text-align: center; padding: 30px 20px; margin-top: 40px; font-size: 0.9em; line-height: 1.8; }
        footer a { color: #fff; text-decoration: none; }
        h1, h2, h3 { color: #003366; }
        header h1 { color: #fff; margin: 0 0 10px 0; }
        header p { margin: 0; font-size: 1.1em; }
        
        @media (max-width: 768px) {
            .languages-flex, .portfolio-grid { flex-direction: column; }
        }
    </style>
</head>
<body>

<header>
    <h1>Imran Allround Engineering & IT</h1>
    <p>Ihr zuverlässiger Partner für digitale Konstruktion, Elektrotechnik & IT-Lösungen</p>
</header>

<div class="container">
    
    <!-- Über uns / About Us -->
    <div class="about-container">
        <div class="profile-header">
            <img src="mein-bild.jpg" alt="Imran" class="about-image">
            <h2>Über uns / About Us</h2>
        </div>
        
        <div class="languages-flex">
            <!-- Deutsch -->
            <div class="lang-block">
                <h3>🇩🇪 Deutsch</h3>
                <p><strong>Über mich & Unser Service:</strong><br>Mein Name ist Imran. Ich bin Ihr zentraler Ansprechpartner und Projektkoordinator hier in Deutschland. Gemeinsam mit meinem hochqualifizierten Remote-Team aus erfahrenen Ingenieuren und IT-Spezialisten bieten wir erstklassige, flexible und kosteneffiziente digitale Lösungen an.</p>
                <p>Wir unterstützen Unternehmen, Architektur- und Ingenieursbüros genau dort, wo Engpässe entstehen – absolut zuverlässig, termingerecht und exakt nach den deutschen Qualitätsstandards sowie Ihren individuellen Vorgaben.</p>
            </div>
            
            <!-- English -->
            <div class="lang-block">
                <h3>🇬🇧 English</h3>
                <p><strong>About Me & Our Services:</strong><br>My Name is Imran. I am your central point of contact and project coordinator here in Germany. Together with my highly qualified remote team of experienced engineers and IT specialists, we deliver premium, flexible, and cost-effective digital solutions.</p>
                <p>We support businesses, architectural firms, and engineering offices exactly where project bottlenecks occur – with absolute reliability, on-time delivery, and strict adherence to German quality standards and your individual requirements.</p>
            </div>
        </div>
    </div>

    <!-- Core Competences -->
    <h2>Unsere Kompetenzen / Core Competences</h2>
    <div class="services">
        <div class="service-box">
            <h3>1. Bauingenieurwesen & CAD-Drafting (Civil Engineering)</h3>
            <p>Erstellung von präzisen 2D/3D-CAD-Zeichnungen (AutoCAD, Revit), Planaufbereitung, BIM-Modellierung und Schalungspläne exakt nach Ihren Vorgaben und Skizzen.</p>
        </div>
        <div class="service-box">
            <h3>2. Elektrotechnik & Schaltplanerstellung (Electrical Engineering)</h3>
            <p>Professionelles PCB-Design (Altium Designer, KiCad), Schaltplanentwicklung, elektrotechnische CAD-Konstruktionen und technische Dokumentation.</p>
        </div>
        <div class="service-box">
            <h3>3. IT-Dienstleistungen & Softwareentwicklung (Information Technology)</h3>
            <p>Webentwicklung (Frontend/Backend), App-Entwicklung, WordPress-Lösungen, Datenbankmanagement und lösungsorientierter IT-Support.</p>
        </div>
    </div>

    <!-- Portfolio Samples -->
    <h2>Unsere Projektreferenzen / Portfolio Samples</h2>
    <p>Hier finden Sie einige visuelle Beispiele unserer technischen Ausführungen:</p>
    
    <div class="portfolio-grid">
        <div class="portfolio-item">
            <img src="projekt-bau.jpg" alt="CAD-Zeichnung Muster">
            <div class="portfolio-item-desc">
                <h4>Bauingenieurwesen</h4>
                <p>Präzise 2D-CAD-Grundrisse und Schnitte, erstellt nach Kundenzeichnungen.</p>
            </div>
        </div>
        
        <div class="portfolio-item">
            <img src="projekt-elektro.jpg" alt="PCB Design Muster">
            <div class="portfolio-item-desc">
                <h4>Elektrotechnik</h4>
                <p>Professionelles mehrlagiges PCB-Design und Schaltplanerstellung.</p>
            </div>
        </div>
        
        <div class="portfolio-item">
            <img src="projekt-it.jpg" alt="Webentwicklung Muster">
            <div class="portfolio-item-desc">
                <h4>IT & Webentwicklung</h4>
                <p>Modernes, responsives Webdesign und kundenspezifische Programmierungen.</p>
            </div>
        </div>
    </div>

    <!-- Contact -->
    <h2>Kontakt / Contact</h2>
    <p>Haben Sie ein konkretes Projekt oder benötigen Sie temporäre Unterstützung zur Entlastung Ihres Teams? Wir freuen uns auf Ihre Anfrage.</p>
    <p>Bitte kontaktieren Sie uns direkt per E-Mail für ein unverbindliches Angebot.</p>
</div>

<!-- Impressum -->
<footer>
    <p><strong>Impressum (Rechtliche Angaben)</strong></p>
    <p>
        Imran Allround Engineering & IT<br>
        Inhaber: Imran<br>
        Deutschland
    </p>
    <p>
        <strong>Kontakt:</strong><br>
        Anfragen per E-Mail: Kontaktaufnahme über das Projektportal / auf Anfrage.
    </p>
    <p>&copy; 2026 Imran Allround Engineering & IT. Alle Rechte vorbehalten.</p>
</footer>

</body>
</html>
