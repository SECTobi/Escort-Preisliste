<!DOCTYPE html>

<html lang="de">
<head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Escort Service Preisrechner - Erweiterte Version</title>
<style>.container {
    max-width: 800px;
    margin: 0 auto;
    padding: 24px 40px;
    background-color: #fff;
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
    border-radius: 8px;
    }
.chart-container {
    position: relative;
    margin: 3em auto;
    max-width: 700px;
    min-height: 200px;
    max-height: 400px;
    width: 100%;
    height: auto;
    overflow: visible;
    }
img {
    display: block;
    overflow: hidden;
    max-width: 100%;
    margin: 1em auto;
    border-radius: 8px;
    }
h1 {
    font-size: 28px;
    margin-top: 24px;
    margin-bottom: 20px;
    }
h2 {
    font-size: 22px;
    }
h3 {
    font-size: 20px;
    }
h4 {
    font-size: 18px;
    }
h5 {
    font-size: 16px;
    }
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    }
body {
    font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
    min-height: 100vh;
    color: #333;
    line-height: 1.6;
    position: relative;
    overflow-x: hidden;
    font-size: 16px;
    margin: 0 24px 0 24px;
    padding: 0;
    max-width: None;
    /* *** HINTERGRUNDPFAD KORRIGIERT *** */
    background-image: url('assets/images/image_29733f.jpg');
    background-size: cover;
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-color: #1e3c72; /* Fallback-Farbe */
    }
.header {
    background: rgba(255, 255, 255, 0.98);
    padding: 50px 40px;
    border-radius: 20px;
    text-align: center;
    margin-bottom: 30px;
    box-shadow: 0 15px 35px rgba(0, 0, 0, 0.15);
    border: 3px solid rgba(42, 82, 152, 0.3);
    backdrop-filter: blur(10px);
    }
.logo-section {
    display: flex;
    align-items: center;
    justify-content: center;
    margin-bottom: 25px;
    gap: 25px;
    }
.logo {
    width: 120px;
    height: 120px;
    display: flex;
    align-items: center;
    justify-content: center;
    border-radius: 50%;
    background: linear-gradient(135deg, #2a5298, #1e3c72);
    box-shadow: 0 10px 25px rgba(42, 82, 152, 0.4);
    animation: logoGlow 3s ease-in-out infinite;
    overflow: hidden;
    }
@keyframes logoGlow {
    0%, 100% {
        box-shadow: 0 10px 25px rgba(42, 82, 152, 0.4);
        } 50% {
        box-shadow: 0 15px 35px rgba(42, 82, 152, 0.6);
        }
    }
.main-title {
    font-size: 3.2em;
    color: #1e3c72;
    font-weight: bold;
    margin-bottom: 15px;
    text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.1);
    }
.subtitle {
    font-size: 1.4em;
    color: #2a5298;
    margin-bottom: 25px;
    font-weight: 500;
    }
.intro-text {
    background: linear-gradient(135deg, #f8f9ff, #e8f0ff);
    padding: 25px;
    border-radius: 15px;
    border-left: 5px solid #2a5298;
    font-size: 1.1em;
    color: #555;
    }
.calculator-section {
    background: rgba(255, 255, 255, 0.98);
    padding: 40px;
    border-radius: 20px;
    box-shadow: 0 15px 35px rgba(0, 0, 0, 0.15);
    border: 3px solid rgba(42, 82, 152, 0.3);
    backdrop-filter: blur(10px);
    }
.section-title {
    color: #1e3c72;
    font-size: 2em;
    margin-bottom: 30px;
    text-align: center;
    font-weight: bold;
    position: relative;
    }
.section-title::after {
    content: "";
    position: absolute;
    bottom: -10px;
    left: 50%;
    transform: translatex(-50%);
    width: 100px;
    height: 4px;
    background: linear-gradient(135deg, #2a5298, #1e3c72);
    border-radius: 2px;
    }
.service-info-section {
    background: linear-gradient(135deg, #f8f9ff, #f0f4ff);
    padding: 35px;
    border-radius: 15px;
    margin-bottom: 30px;
    border: 2px solid rgba(232, 240, 255, 0.8);
    }
.service-info-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
    gap: 25px;
    margin-top: 25px;
    }
.service-info-card {
    background: white;
    padding: 30px;
    border-radius: 15px;
    border-left: 5px solid #2a5298;
    box-shadow: 0 5px 15px rgba(42, 82, 152, 0.1);
    transition: transform 0.3s ease;
    }
.service-info-card:hover {
    transform: translatey(-3px);
    box-shadow: 0 10px 25px rgba(42, 82, 152, 0.15);
    }
.service-info-card h4 {
    color: #1e3c72;
    font-size: 1.4em;
    margin-bottom: 15px;
    display: flex;
    align-items: center;
    gap: 10px;
    }
.service-icon {
    width: 40px;
    height: 40px;
    background: #2a5298;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    color: white;
    font-size: 1.2em;
    }
.service-description {
    color: #666;
    margin-bottom: 15px;
    line-height: 1.6;
    }
.service-features {
    background: #f8f9ff;
    padding: 15px;
    border-radius: 10px;
    margin-bottom: 15px;
    }
.service-features ul {
    list-style: none;
    padding: 0;
    }
.service-features li {
    padding: 5px 0;
    color: #555;
    }
.service-features li::before {
    content: "✓";
    color: #4CAF50;
    font-weight: bold;
    margin-right: 8px;
    }
.price-range {
    background: rgba(42, 82, 152, 0.1);
    padding: 12px 15px;
    border-radius: 8px;
    color: #1e3c72;
    font-weight: bold;
    text-align: center;
    }
.guards-selection {
    background: white;
    padding: 35px;
    border-radius: 15px;
    margin: 30px 0;
    border: 2px solid rgba(232, 240, 255, 0.8);
    text-align: center;
    }
.guards-options {
    display: flex;
    justify-content: center;
    gap: 40px;
    margin-top: 20px;
    }
.guard-option {
    background: linear-gradient(135deg, #f8f9ff, #f0f4ff);
    padding: 25px 40px;
    border-radius: 15px;
    border: 3px solid #e8f0ff;
    cursor: pointer;
    transition: all 0.3s ease;
    min-width: 160px;
    position: relative;
    }
.guard-option:hover, .guard-option.selected {
    border-color: #2a5298;
    background: linear-gradient(135deg, #e8f0ff, #d0e4ff);
    transform: translatey(-2px);
    box-shadow: 0 8px 20px rgba(42, 82, 152, 0.2);
    }
.guard-option input[type="radio"] {
    position: absolute;
    top: 10px;
    right: 10px;
    transform: scale(1.3);
    accent-color: #2a5298;
    }
.countries-section {
    background: white;
    padding: 35px;
    border-radius: 15px;
    margin: 30px 0;
    border: 2px solid rgba(232, 240, 255, 0.8);
    }
.country-row {
    background: linear-gradient(135deg, #f8f9ff, #f0f4ff);
    padding: 25px;
    border-radius: 15px;
    margin-bottom: 20px;
    border: 2px solid #e8f0ff;
    transition: all 0.3s ease;
    }
.country-row:hover {
    border-color: #2a5298;
    box-shadow: 0 5px 15px rgba(42, 82, 152, 0.1);
    }
.country-header {
    display: grid;
    grid-template-columns: 2fr 1fr 80px;
    gap: 20px;
    align-items: center;
    margin-bottom: 20px;
    }
.country-select, .hours-input {
    padding: 15px;
    border: 2px solid #ddd;
    border-radius: 10px;
    font-size: 16px;
    background: white;
    transition: all 0.3s ease;
    }
.country-select:focus, .hours-input:focus {
    outline: none;
    border-color: #2a5298;
    box-shadow: 0 0 0 3px rgba(42, 82, 152, 0.1);
    }
.remove-btn {
    background: #dc3545;
    color: white;
    border: none;
    border-radius: 10px;
    padding: 15px;
    cursor: pointer;
    font-size: 16px;
    font-weight: bold;
    transition: all 0.3s ease;
    }
.remove-btn:hover {
    background: #c82333;
    transform: scale(1.05);
    }
.services-for-country {
    border-top: 2px solid #e8f0ff;
    padding-top: 20px;
    }
.services-for-country h5 {
    color: #1e3c72;
    margin-bottom: 15px;
    font-size: 1.1em;
    }
.service-checkboxes {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 15px;
    }
.service-checkbox {
    display: flex;
    align-items: center;
    gap: 12px;
    padding: 15px;
    background: white;
    border-radius: 10px;
    border: 2px solid transparent;
    transition: all 0.3s ease;
    cursor: pointer;
    }
.service-checkbox:hover {
    border-color: #2a5298;
    box-shadow: 0 3px 10px rgba(42, 82, 152, 0.1);
    }
.service-checkbox.selected {
    border-color: #2a5298;
    background: linear-gradient(135deg, #f8f9ff, #e8f0ff);
    }
.service-checkbox input[type="checkbox"] {
    transform: scale(1.3);
    accent-color: #2a5298;
    }
.service-checkbox label {
    cursor: pointer;
    font-weight: 500;
    color: #333;
    }
.add-country-btn {
    background: linear-gradient(135deg, #28a745, #20c997);
    color: white;
    border: none;
    border-radius: 12px;
    padding: 18px 35px;
    font-size: 16px;
    font-weight: bold;
    cursor: pointer;
    transition: all 0.3s ease;
    margin: 25px 0;
    box-shadow: 0 6px 15px rgba(40, 167, 69, 0.3);
    }
.add-country-btn:hover {
    transform: translatey(-3px);
    box-shadow: 0 10px 20px rgba(40, 167, 69, 0.4);
    }
.fixprice-section {
    background: linear-gradient(135deg, #fff8e1, #ffecb3);
    padding: 35px;
    border-radius: 15px;
    margin: 30px 0;
    border: 3px solid #ffc107;
    }
.fixprice-section h3 {
    color: #f57c00;
    font-size: 1.6em;
    margin-bottom: 20px;
    display: flex;
    align-items: center;
    gap: 10px;
    }
.fixprice-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
    gap: 20px;
    margin-top: 25px;
    }
.fixprice-item {
    background: white;
    padding: 20px;
    border-radius: 12px;
    border: 2px solid transparent;
    transition: all 0.3s ease;
    cursor: pointer;
    }
.fixprice-item:hover {
    border-color: #ffc107;
    transform: translatey(-2px);
    box-shadow: 0 6px 15px rgba(255, 193, 7, 0.2);
    }
.fixprice-item.selected {
    border-color: #ffc107;
    background: linear-gradient(135deg, #fff8e1, #ffecb3);
    }
.fixprice-header {
    display: flex;
    align-items: center;
    gap: 15px;
    margin-bottom: 10px;
    }
.fixprice-header input[type="checkbox"] {
    transform: scale(1.4);
    accent-color: #ffc107;
    }
.fixprice-title {
    font-weight: bold;
    color: #333;
    font-size: 1.1em;
    }
.fixprice-price {
    font-weight: bold;
    color: #f57c00;
    background: #fff3e0;
    padding: 5px 10px;
    border-radius: 6px;
    font-size: 1.1em;
    margin-left: auto;
    }
.fixprice-description {
    color: #666;
    font-size: 0.95em;
    margin-top: 8px;
    line-height: 1.4;
    }
.calculate-btn {
    background: linear-gradient(135deg, #2a5298, #1e3c72);
    color: white;
    padding: 22px 70px;
    border: none;
    border-radius: 15px;
    font-size: 22px;
    font-weight: bold;
    cursor: pointer;
    transition: all 0.3s ease;
    display: block;
    margin: 50px auto;
    box-shadow: 0 12px 30px rgba(42, 82, 152, 0.4);
    text-transform: uppercase;
    letter-spacing: 1px;
    }
.calculate-btn:hover {
    transform: translatey(-4px);
    box-shadow: 0 18px 35px rgba(42, 82, 152, 0.5);
    }
.result-section {
    background: linear-gradient(135deg, #4CAF50, #45a049);
    color: white;
    padding: 50px;
    border-radius: 20px;
    margin-top: 40px;
    box-shadow: 0 20px 40px rgba(76, 175, 80, 0.4);
    display: none;
    }
.result-header {
    text-align: center;
    margin-bottom: 40px;
    }
.result-header h3 {
    font-size: 2.5em;
    margin-bottom: 15px;
    text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.2);
    }
.total-price {
    font-size: 4.5em;
    font-weight: bold;
    text-align: center;
    margin: 30px 0;
    text-shadow: 3px 3px 6px rgba(0, 0, 0, 0.3);
    }
.total-summary {
    text-align: center;
    font-size: 1.3em;
    margin-bottom: 40px;
    background: rgba(255, 255, 255, 0.2);
    padding: 20px;
    border-radius: 12px;
    backdrop-filter: blur(10px);
    }
.breakdown-section {
    background: rgba(255, 255, 255, 0.15);
    padding: 30px;
    border-radius: 15px;
    margin-top: 30px;
    backdrop-filter: blur(10px);
    }
.breakdown-title {
    font-size: 1.6em;
    margin-bottom: 25px;
    text-align: center;
    font-weight: bold;
    }
.country-breakdown {
    background: rgba(255, 255, 255, 0.1);
    padding: 20px;
    border-radius: 12px;
    margin: 15px 0;
    border-left: 4px solid rgba(255, 255, 255, 0.5);
    }
.country-breakdown h5 {
    margin-bottom: 12px;
    font-size: 1.2em;
    font-weight: bold;
    }
.service-breakdown {
    margin: 8px 0;
    padding: 8px 0;
    border-bottom: 1px solid rgba(255, 255, 255, 0.2);
    display: flex;
    justify-content: space-between;
    }
.breakdown-item {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 12px 0;
    border-bottom: 1px solid rgba(255, 255, 255, 0.3);
    font-size: 1.05em;
    }
.breakdown-item:last-child {
    border-bottom: none;
    font-weight: bold;
    font-size: 1.3em;
    margin-top: 20px;
    padding-top: 25px;
    border-top: 2px solid rgba(255, 255, 255, 0.5);
    }
.footer-info {
    text-align: center;
    margin-top: 40px;
    padding: 25px;
    background: rgba(255, 255, 255, 0.1);
    border-radius: 12px;
    backdrop-filter: blur(10px);
    }
/* Responsive Design */
@media (max-width: 768px) {
    .container {
        padding: 10px;
        }
    .header {
        padding: 30px 20px;
        }
    .logo-section {
        flex-direction: column;
        gap: 20px;
        }
    .main-title {
        font-size: 2.5em;
        }
    .country-header {
        grid-template-columns: 1fr;
        gap: 15px;
        }
    .service-info-grid, .fixprice-grid {
        grid-template-columns: 1fr;
        }
    .guards-options {
        flex-direction: column;
        gap: 20px;
        }
    .total-price {
        font-size: 3.5em;
        }
    .calculate-btn {
        padding: 18px 40px;
        font-size: 18px;
        }
    }
@media only screen and (max-device-width: 768px) {
            body {
                padding: 0;
                margin: 0;
                font-family: PingFang SC;
                font-size: 15px;
                line-height: 1.5;
            }

            .container {
                padding: 0;
                margin: 16px 20px 30px;
                box-shadow: none;
            }

            h1,
            h2,
            h3,
            h4 {
                font-family: PingFang SC;
            }

            h1 {
                font-size: 1.87em;
                line-height: 1.6;
                margin-bottom: 0.5em;
                text-align: center;
            }

            h2 {
                font-size: 1.6em;
                font-weight: 600;
                margin-top: 1.3em;
                margin-bottom: 0.8em;
                border-bottom: 1px solid #eee;
                padding-bottom: 0.5em;
            }

            h3 {
                font-size: 1.2em;
                font-weight: 600;
                margin-top: 1em;
                margin-bottom: 0.6em;
            }

            h4 {
                font-size: 1.1em;
                font-weight: 500;
                margin-top: 1em;
                margin-bottom: 0.5em;
                font-style: normal;
            }

            h5 {
                font-size: 1em;
                font-weight: 500;
                margin-bottom: 1.2em;
            }

            ul,
            ol {
                font-size: 1em; /* Equivalent to 17.6px if base is 16px */
                font-weight: 400;
                margin-bottom: 1.2em;
                line-height: 1.8;
            }

            p {
                font-size: 1em;
                line-height: 1.8; /* Equivalent to 17.6px if base is 16px */
                font-weight: 400;
                margin-top: 0.8em;
                margin-bottom: 0.8em;
            }

            blockquote {
                padding: 1em 1.2em;

            p {
                margin: 0;
            }
        }

        figcaption {
            margin-top: 0.5em;
            font-size: 0.8em; /* Equivalent to 17.6px if base is 16px */
            font-weight: 400;
            text-align: center;
            font-style: normal;
            color: #7F8896;
        }

        img {
            display: block;
            overflow: hidden;
            max-width: 100%;
            max-height: 335px;
            margin: 1em auto;
            border-radius: 8px;
        }
        }</style>
</head>
<body>
<div class="container">
<header class="header">
<div class="logo-section">
<div class="logo">
<img src="assets/images/image_1c53e3.png" alt="Firmenlogo" style="width: 100%; height: 100%; object-fit: cover; border-radius: 50%;"/>
</div>
<div>
<h1 class="main-title">Escort Service Preisrechner</h1>
<p class="subtitle">Professionelle Sicherheitsdienstleistungen in ganz Europa</p>
</div>
</div>
<div class="intro-text">
<strong>Erweiterte Version:</strong> Wählen Sie für jedes Land individuell die benötigten Services aus. 
                Sie können alle drei Services gleichzeitig nutzen und pro Land unterschiedliche Kombinationen wählen.
            </div>
</header>
<main class="calculator-section">
<h2 class="section-title">Erweiterte Preisberechnung</h2>
<section class="service-info-section">
<h3 style="color: #1e3c72; font-size: 1.6em; margin-bottom: 20px; text-align: center;">
                    🛡️ Unsere Sicherheitsdienstleistungen im Detail
                </h3>
<div class="service-info-grid">
<div class="service-info-card">
<h4>
<div class="service-icon">🗣️</div>
                            Language Services
                        </h4>
<div class="service-description">
                            Professionelle Dolmetscher- und Übersetzungsleistungen für internationale Einsätze. 
                            Unsere zertifizierten Sprachexperten gewährleisten reibungslose Kommunikation in kritischen Situationen.
                        </div>
<div class="service-features">
<strong>Leistungen umfassen:</strong>
<ul>
<li>Simultandolmetschen vor Ort</li>
<li>Dokumentenübersetzung</li>
<li>Kulturelle Beratung</li>
<li>24/7 Sprachunterstützung</li>
<li>Mehrsprachige Kommunikation</li>
</ul>
</div>
<div class="price-range">120,00 € pro Stunde (alle Regionen)</div>
</div>
<div class="service-info-card">
<h4>
<div class="service-icon">🏢</div>
                            Static Guard
                        </h4>
<div class="service-description">
                            Objektschutz an festen Standorten durch qualifizierte Sicherheitskräfte. 
                            Ideal für Gebäude, Veranstaltungen oder temporäre Sicherheitszonen mit mindestens 4 Stunden Einsatzzeit.
                        </div>
<div class="service-features">
<strong>Leistungen umfassen:</strong>
<ul>
<li>Zugangskontrolle</li>
<li>Objektüberwachung</li>
<li>Alarmbearbeitung</li>
<li>Besucherregistrierung</li>
<li>Incident Reporting</li>
</ul>
</div>
<div class="price-range">120,00 - 150,00 € pro Stunde (min. 4h)</div>
</div>
<div class="service-info-card">
<h4>
<div class="service-icon">🚗</div>
                            Escort Services
                        </h4>
<div class="service-description">
                            Professioneller Begleitschutz für Transporte, VIP-Fahrten und Werttransporte. 
                            Flexibel mit 1 oder 2 Guards je nach Sicherheitsanforderung und Risikobewertung.
                        </div>
<div class="service-features">
<strong>Leistungen umfassen:</strong>
<ul>
<li>Personenschutz während Transport</li>
<li>Routenplanung und -sicherung</li>
<li>Fahrzeugbegleitung</li>
<li>Risikobewertung</li>
<li>Notfallmanagement</li>
</ul>
</div>
<div class="price-range">135,00 - 160,00 € (1. Guard) + 70,00 - 90,00 € (2. Guard)</div>
</div>
</div><img src="assets/images/image_e41d5c.jpg" alt="Beschreibung des neuen Bildes" style="max-width: 100%; height: auto; border-radius: 8px;"/>
<form id="priceCalculator">
<section class="guards-selection">
<h3 style="color: #1e3c72; font-size: 1.5em; margin-bottom: 15px;">
                        👥 Anzahl Guards (gilt für alle Escort Services)
                    </h3>
<p style="color: #666; margin-bottom: 20px;">
                        Diese Einstellung gilt für alle Escort Services in allen Ländern. 
                        Static Guard und Language Services sind davon nicht betroffen.
                    </p>
<div class="guards-options">
<div class="guard-option">
<input name="guards" required="" type="radio" value="1"/>
<strong>1 Guard</strong>
<div style="font-size: 0.9em; color: #666; margin-top: 5px;">
                                Standard-Begleitung
                            </div>
</div>
<div class="guard-option">
<input name="guards" required="" type="radio" value="2"/>
<strong>2 Guards</strong>
<div style="font-size: 0.9em; color: #666; margin-top: 5px;">
                                Erhöhte Sicherheit
                            </div>
</div>
</div>
</section>
<section class="countries-section">
<h3 style="color: #1e3c72; font-size: 1.5em; margin-bottom: 15px;">
                        🌍 Route planen - Services pro Land
                    </h3>
<p style="color: #666; margin-bottom: 25px;">
                        Fügen Sie alle Länder Ihrer Route hinzu und wählen Sie für jedes Land die benötigten Services aus. 
                        Sie können alle drei Services gleichzeitig in einem Land nutzen.
                    </p>
<div id="countriesContainer">
<div class="country-row">
<div class="country-header">
<select class="country-select" required="">
<option value="">Land auswählen...</option>
<option value="1">🇩🇪 Deutschland (Region 1)</option>
<option value="1">🇦🇹 Österreich (Region 1)</option>
<option value="1">🇨🇭 Schweiz (Region 1)</option>
<option value="1">🇧🇪 Belgien (Region 1)</option>
<option value="1">🇳🇱 Niederlande (Region 1)</option>
<option value="1">🇫🇷 Frankreich (Region 1)</option>
<option value="1">🇮🇹 Italien (Region 1)</option>
<option value="1">🇪🇸 Spanien (Region 1)</option>
<option value="1">🇵🇹 Portugal (Region 1)</option>
<option value="1">🇱🇺 Luxemburg (Region 1)</option>
<option value="1">🇩🇰 Dänemark (Region 1)</option>
<option value="1">🇸🇪 Schweden (Region 1)</option>
<option value="1">🇳🇴 Norwegen (Region 1)</option>
<option value="1">🇫🇮 Finnland (Region 1)</option>
<option value="2">🇵🇱 Polen (Region 2)</option>
<option value="2">🇨🇿 Tschechien (Region 2)</option>
<option value="2">🇭🇺 Ungarn (Region 2)</option>
<option value="2">🇸🇰 Slowakei (Region 2)</option>
<option value="2">🇸🇮 Slowenien (Region 2)</option>
<option value="2">🇭🇷 Kroatien (Region 2)</option>
<option value="2">🇪🇪 Estland (Region 2)</option>
<option value="2">🇱🇻 Lettland (Region 2)</option>
<option value="2">🇱🇹 Litauen (Region 2)</option>
<option value="2">🇬🇷 Griechenland (Region 2)</option>
<option value="3">🇧🇬 Bulgarien (Region 3)</option>
<option value="3">🇷🇴 Rumänien (Region 3)</option>
<option value="3">🇷🇸 Serbien (Region 3)</option>
<option value="3">🇧🇦 Bosnien und Herzegowina (Region 3)</option>
<option value="3">🇲🇰 Nordmazedonien (Region 3)</option>
<option value="3">🇲🇪 Montenegro (Region 3)</option>
<option value="3">🇦🇱 Albanien (Region 3)</option>
</select>
<input class="hours-input" min="0.5" placeholder="Stunden" required="" step="0.5" type="number"/>
<button class="remove-btn" onclick="removeCountryRow(this)" style="display: none;" type="button">✕</button>
</div>
<div class="services-for-country">
<h5>Benötigte Services in diesem Land:</h5>
<div class="service-checkboxes">
<div class="service-checkbox">
<input class="service-escort" type="checkbox"/>
<label>🚗 Escort Services</label>
</div>
<div class="service-checkbox">
<input class="service-language" type="checkbox"/>
<label>🗣️ Language Services</label>
</div>
<div class="service-checkbox">
<input class="service-static" type="checkbox"/>
<label>🏢 Static Guard</label>
</div>
</div>
</div>
</div>
</div>
<button class="add-country-btn" onclick="addCountryRow()" type="button">
                        ➕ Weiteres Land hinzufügen
                    </button>
</section>
<section class="fixprice-section">
<h3>💰 Zusätzliche Fixpreis-Services</h3>
<p style="color: #666; margin-bottom: 20px;">
                        Einmalige Zusatzleistungen die unabhängig von Zeit und Ort berechnet werden:
                    </p>
<div class="fixprice-grid">
<div class="fixprice-item">
<div class="fixprice-header">
<input id="cancel_full" type="checkbox" value="250"/>
<div class="fixprice-title">Cancellation Fee (Full)</div>
<div class="fixprice-price">250,00 €</div>
</div>
<div class="fixprice-description">
                                Vollständige Stornierungsgebühr bei kurzfristiger Absage (weniger als 24h vor Einsatzbeginn)
                            </div>
</div>
<div class="fixprice-item">
<div class="fixprice-header">
<input id="cancel_pre" type="checkbox" value="100"/>
<div class="fixprice-title">Cancellation Fee (Pre)</div>
<div class="fixprice-price">100,00 €</div>
</div>
<div class="fixprice-description">
                                Vorab-Stornierungsgebühr bei Absage zwischen 24-48h vor Einsatzbeginn
                            </div>
</div>
<div class="fixprice-item">
<div class="fixprice-header">
<input id="police" type="checkbox" value="120"/>
<div class="fixprice-title">Police activation (for Alarm verification)</div>
<div class="fixprice-price">120,00 €</div>
</div>
<div class="fixprice-description">
                                Aktivierung und Koordination der örtlichen Polizei zur Alarmverifikation
                            </div>
</div>
<div class="fixprice-item">
<div class="fixprice-header">
<input id="lea" type="checkbox" value="120"/>
<div class="fixprice-title">Flat-rate activation/coordination of LEA, ambulance, etc.</div>
<div class="fixprice-price">120,00 €</div>
</div>
<div class="fixprice-description">
                                Pauschalgebühr für Aktivierung und Koordination von Behörden, Rettungsdiensten etc.
                            </div>
</div>
<div class="fixprice-item">
<div class="fixprice-header">
<input id="forwarding" type="checkbox" value="20"/>
<div class="fixprice-title">Forwarding of LEA invoices, per forwarded invoice</div>
<div class="fixprice-price">20,00 €</div>
</div>
<div class="fixprice-description">
                                Weiterleitung von Behördenrechnungen - Gebühr pro weitergeleiteter Rechnung
                            </div>
</div>
<div class="fixprice-item">
<div class="fixprice-header">
<input id="monitoring_sheet" type="checkbox" value="25"/>
<div class="fixprice-title">Monitorings, Orga per Sheet</div>
<div class="fixprice-price">25,00 €</div>
</div>
<div class="fixprice-description">
                                Monitoring und Organisation pro Dokumentationsblatt/Protokoll
                            </div>
</div>
<div class="fixprice-item">
<div class="fixprice-header">
<input id="monitoring_system" type="checkbox" value="8"/>
<div class="fixprice-title">Monitorings, per System Check</div>
<div class="fixprice-price">8,00 €</div>
</div>
<div class="fixprice-description">
                                Monitoring-Gebühr pro durchgeführtem Systemcheck/technischer Überprüfung
                            </div>
</div>
<div class="fixprice-item">
<div class="fixprice-header">
<input id="monitoring_call" type="checkbox" value="8"/>
<div class="fixprice-title">Monitorings, per Call Check</div>
<div class="fixprice-price">8,00 €</div>
</div>
<div class="fixprice-description">
                                Monitoring-Gebühr pro durchgeführtem Anruf-Check/Kommunikationstest
                            </div>
</div>
</div>
</section>
<button class="calculate-btn" onclick="calculatePrice()" type="button">
                    💰 Gesamtpreis berechnen
                </button>
</form>
<div class="result-section" id="priceResult">
<div class="result-header">
<h3>Ihr individueller Preis:</h3>
<div class="total-price" id="finalPrice">0,00 €</div>
</div>
<div class="total-summary" id="totalSummary">
</div>
<div class="breakdown-section">
<div class="breakdown-title">📊 Detaillierte Aufschlüsselung</div>
<div id="breakdown">
</div>
</div>
<div class="footer-info">
<p><strong>Alle Preise verstehen sich zzgl. MwSt.</strong></p>
<p>Gültig für das Jahr 2025 | Änderungen vorbehalten</p>
<p>Für individuelle Angebote und weitere Informationen kontaktieren Sie uns gerne.</p>
</div>
</div>
</main>
</div>
<script>
        // Preistabelle basierend auf Excel-Daten
        const prices = {
            language: [120, 120, 120],  // Region 1, 2, 3
            static: [120, 138, 150],
            escort1: [135, 150, 160],
            escort2: [70, 80, 90]
        };
        
        // DOM Content Loaded Event
        document.addEventListener('DOMContentLoaded', function() {
            initializeCalculator();
        });

        function initializeCalculator() {
            // Guard Option Selection
            document.querySelectorAll('.guard-option').forEach(option => {
                option.addEventListener('click', function() {
                    const radio = this.querySelector('input[type="radio"]');
                    radio.checked = true;
                    
                    document.querySelectorAll('.guard-option').forEach(o => o.classList.remove('selected'));
                    this.classList.add('selected');
                });
            });
            
            // Service Checkbox Selection
            document.addEventListener('change', function(e) {
                if (e.target.type === 'checkbox' && e.target.closest('.service-checkbox')) {
                    const checkbox = e.target.closest('.service-checkbox');
                    if (e.target.checked) {
                        checkbox.classList.add('selected');
                    } else {
                        checkbox.classList.remove('selected');
                    }
                }
                
                if (e.target.type === 'checkbox' && e.target.closest('.fixprice-item')) {
                    const item = e.target.closest('.fixprice-item');
                    if (e.target.checked) {
                        item.classList.add('selected');
                    } else {
                        item.classList.remove('selected');
                    }
                }
            });
            
            // Initialize remove buttons
            updateRemoveButtons();
        }

        // Funktion zum Hinzufügen einer neuen Länderzeile
        function addCountryRow() {
            const container = document.getElementById('countriesContainer');
            const rowTemplate = container.children[0];
            const newRow = rowTemplate.cloneNode(true);
            
            // Inputs zurücksetzen
            newRow.querySelector('.country-select').value = "";
            newRow.querySelector('.hours-input').value = "";
            
            // Checkboxes zurücksetzen
            newRow.querySelectorAll('input[type="checkbox"]').forEach(cb => {
                cb.checked = false;
            });
            newRow.querySelectorAll('.service-checkbox').forEach(div => {
                div.classList.remove('selected');
            });

            // Entfernen-Button anzeigen
            newRow.querySelector('.remove-btn').style.display = 'block';
            
            container.appendChild(newRow);
            updateRemoveButtons();
        }

        // Funktion zum Entfernen einer Länderzeile
        function removeCountryRow(button) {
            const row = button.closest('.country-row');
            if (document.getElementById('countriesContainer').children.length > 1) {
                row.remove();
                updateRemoveButtons();
            } else {
                alert('Es muss mindestens eine Länderzeile vorhanden sein.');
            }
        }

        // Steuert, ob der Entfernen-Button angezeigt wird (min. eine Zeile muss bleiben)
        function updateRemoveButtons() {
            const container = document.getElementById('countriesContainer');
            const rows = container.querySelectorAll('.country-row');
            
            rows.forEach((row, index) => {
                const removeBtn = row.querySelector('.remove-btn');
                if (rows.length > 1) {
                    removeBtn.style.display = 'block';
                } else {
                    removeBtn.style.display = 'none';
                }
            });
        }

        // Hauptberechnungsfunktion
        function calculatePrice() {
            const countriesContainer = document.getElementById('countriesContainer');
            const countryRows = countriesContainer.querySelectorAll('.country-row');
            const guardsRadio = document.querySelector('input[name="guards"]:checked');
            
            if (!guardsRadio) {
                alert('Bitte wählen Sie die Anzahl der Guards aus.');
                return;
            }

            let totalTimePrice = 0;
            let totalFixPrice = 0;
            let breakdown = [];
            let totalSummaryText = "";
            const guards = parseInt(guardsRadio.value);
            
            // Berechnung der zeitbasierten Services pro Land
            countryRows.forEach(row => {
                const countrySelect = row.querySelector('.country-select');
                const hoursInput = row.querySelector('.hours-input');
                const serviceEscort = row.querySelector('.service-escort').checked;
                const serviceLanguage = row.querySelector('.service-language').checked;
                const serviceStatic = row.querySelector('.service-static').checked;

                const countryValue = countrySelect.value;
                const hours = parseFloat(hoursInput.value);

                if (!countryValue || isNaN(hours) || hours <= 0) {
                    // Ignoriere unvollständige Zeilen, zeige aber Warnung
                    if (countryValue || !isNaN(hours)) {
                        alert('Bitte füllen Sie alle Land- und Stundenfelder korrekt aus.');
                        // Throwing an error here stops the outer forEach loop
                        return; // Use return instead of throwing to allow other rows to process if needed
                    }
                    return;
                }
                
                const region = parseInt(countryValue) - 1; // 0-basiert
                let countryPrice = 0;
                let countryBreakdown = [];
                const countryName = countrySelect.options[countrySelect.selectedIndex].text;

                if (serviceEscort) {
                    const price1 = hours * prices.escort1[region];
                    countryPrice += price1;
                    countryBreakdown.push({
                        service: 'Escort 1. Guard',
                        calculation: `${hours}h × ${prices.escort1[region]}€`,
                        price: price1
                    });
                    
                    if (guards === 2) {
                        const price2 = hours * prices.escort2[region];
                        countryPrice += price2;
                        countryBreakdown.push({
                            service: 'Escort 2. Guard',
                            calculation: `${hours}h × ${prices.escort2[region]}€`,
                            price: price2
                        });
                    }
                }

                if (serviceLanguage) {
                    const price = hours * prices.language[region];
                    countryPrice += price;
                    countryBreakdown.push({
                        service: 'Language Services',
                        calculation: `${hours}h × ${prices.language[region]}€`,
                        price: price
                    });
                }

                if (serviceStatic) {
                    // Static Guard hat Minimum 4h
                    const effectiveHours = Math.max(hours, 4);
                    const price = effectiveHours * prices.static[region];
                    countryPrice += price;
                    countryBreakdown.push({
                        service: 'Static Guard',
                        calculation: `${effectiveHours}h × ${prices.static[region]}€` + (hours < 4 ? ' (min. 4h)' : ''),
                        price: price
                    });
                }

                if (countryPrice > 0) {
                    totalTimePrice += countryPrice;
                    breakdown.push({
                        country: countryName,
                        totalPrice: countryPrice,
                        details: countryBreakdown
                    });
                }
            });

            // Berechnung der Fixpreis-Services
            let fixPriceBreakdown = [];
            document.querySelectorAll('.fixprice-section input[type="checkbox"]:checked').forEach(checkbox => {
                const price = parseFloat(checkbox.value);
                const title = checkbox.closest('.fixprice-item').querySelector('.fixprice-title').textContent;
                totalFixPrice += price;
                fixPriceBreakdown.push({
                    service: title,
                    price: price
                });
            });

            const grandTotal = totalTimePrice + totalFixPrice;

            // Ergebnis-Display aktualisieren
            document.getElementById('finalPrice').textContent = 
                grandTotal.toLocaleString('de-DE', {minimumFractionDigits: 2}) + ' €';

            // Zusammenfassungstext
            const countriesCount = breakdown.length;
            const servicesCount = countryRows.length > 0 ? (breakdown.reduce((sum, item) => sum + item.details.length, 0)) : 0;
            const fixCount = fixPriceBreakdown.length;

            totalSummaryText = `
                Sie haben **${countriesCount} ${countriesCount === 1 ? 'Land' : 'Länder'}** mit insgesamt **${servicesCount} zeitbasierten Services** und **${fixCount} Fixpreis-Leistungen** ausgewählt. 
                Die Berechnung erfolgte auf Basis von **${guards} Guard${guards === 1 ? '' : 's'}**.
            `;
            document.getElementById('totalSummary').innerHTML = totalSummaryText;

            // Detaillierten Breakdown erstellen
            let breakdownHTML = '';

            // 1. Zeitbasierte Services
            if (breakdown.length > 0) {
                breakdownHTML += '<h3>Zeitbasierte Services</h3>';
                breakdown.forEach(item => {
                    breakdownHTML += `<div class="country-breakdown">`;
                    breakdownHTML += `<h5>${item.country}</h5>`;
                    item.details.forEach(detail => {
                        breakdownHTML += `
                            <div class="service-breakdown">
                                <span>${detail.service}</span>
                                <span>${detail.calculation} = ${detail.price.toLocaleString('de-DE', {minimumFractionDigits: 2})} €</span>
                            </div>
                        `;
                    });
                    breakdownHTML += `
                        <div class="breakdown-item">
                            <span>Summe ${item.country}</span>
                            <span>${item.totalPrice.toLocaleString('de-DE', {minimumFractionDigits: 2})} €</span>
                        </div>
                    `;
                    breakdownHTML += `</div>`;
                });
                breakdownHTML += `
                    <div class="breakdown-item" style="border-top: 3px solid rgba(255, 255, 255, 0.7);">
                        <span>Gesamtsumme Zeitbasiert</span>
                        <span>${totalTimePrice.toLocaleString('de-DE', {minimumFractionDigits: 2})} €</span>
                    </div>
                `;
            }

            // 2. Fixpreis Services
            if (fixPriceBreakdown.length > 0) {
                breakdownHTML += '<h3 style="margin-top: 30px;">Fixpreis-Services</h3>';
                fixPriceBreakdown.forEach(item => {
                    breakdownHTML += `
                        <div class="service-breakdown">
                            <span>${item.service}</span>
                            <span>${item.price.toLocaleString('de-DE', {minimumFractionDigits: 2})} €</span>
                        </div>
                    `;
                });
                breakdownHTML += `
                    <div class="breakdown-item">
                        <span>Gesamtsumme Fixpreis</span>
                        <span>${totalFixPrice.toLocaleString('de-DE', {minimumFractionDigits: 2})} €</span>
                    </div>
                `;
            }

            // Gesamtsumme (Endzeile)
            breakdownHTML += `
                <div class="breakdown-item">
                    <span><strong>GESAMTPREIS (Netto)</strong></span>
                    <span><strong>${grandTotal.toLocaleString('de-DE', {minimumFractionDigits: 2})} €</strong></span>
                </div>
            `;
            
            document.getElementById('breakdown').innerHTML = breakdownHTML;
            document.getElementById('priceResult').style.display = 'block';
            
            // Smooth scroll zum Ergebnis
            document.getElementById('priceResult').scrollIntoView({ 
                behavior: 'smooth',
                block: 'center'
            });
        }
    </script>
</body>
</html>
