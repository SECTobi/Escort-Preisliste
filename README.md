<!DOCTYPE html>

<html lang="de">
<head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Escort Service Preisrechner - Augenfreundlich</title>
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
    color: #000;
    /* SCHWARZE SCHRIFT */
    line-height: 1.7;
    /* Bessere Lesbarkeit */
    position: relative;
    overflow-x: hidden;
    /* Sanfter, augenfreundlicher Hintergrund */
    background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 50%, #f8f9fa 100%);
    font-size: 16px;
    /* Größere Grundschrift */
    margin: 0 24px 0 24px;
    padding: 0;
    max-width: None;
    }
.header {
    background: #fff;
    padding: 50px;
    border-radius: 20px;
    text-align: center;
    margin-bottom: 40px;
    box-shadow: 0 4px 20px rgba(0, 0, 0, 0.08);
    border: 2px solid #e9ecef;
    }
.logo-section {
    display: flex;
    align-items: center;
    justify-content: center;
    margin-bottom: 30px;
    gap: 40px;
    }
.logo {
    width: 120px;
    height: 120px;
    display: flex;
    align-items: center;
    justify-content: center;
    border-radius: 50%;
    background: #fff;
    box-shadow: 0 8px 25px rgba(0, 0, 0, 0.15);
    overflow: hidden;
    border: 3px solid #dee2e6;
    }
.logo img {
    width: 110px;
    height: 110px;
    object-fit: cover;
    border-radius: 50%;
    }
.title-section {
    text-align: left;
    }
.main-title {
    font-size: 3.5em;
    color: #000;
    font-weight: 700;
    margin-bottom: 20px;
    letter-spacing: -1px;
    }
.subtitle {
    font-size: 1.6em;
    color: #495057;
    margin-bottom: 30px;
    font-weight: 400;
    }
.intro-text {
    background: #f8f9fa;
    padding: 30px;
    border-radius: 15px;
    border: 2px solid #dee2e6;
    font-size: 1.2em;
    color: #000;
    line-height: 1.8;
    }
.calculator-section {
    background: #fff;
    padding: 50px;
    border-radius: 20px;
    box-shadow: 0 4px 20px rgba(0, 0, 0, 0.08);
    border: 2px solid #e9ecef;
    }
.section-title {
    color: #000;
    font-size: 2.2em;
    margin-bottom: 40px;
    text-align: center;
    position: relative;
    font-weight: 600;
    }
.section-title::after {
    content: "";
    position: absolute;
    bottom: -15px;
    left: 50%;
    transform: translatex(-50%);
    width: 120px;
    height: 4px;
    background: #007bff;
    border-radius: 2px;
    }
.service-info-section {
    background: #fff;
    padding: 40px;
    border-radius: 15px;
    margin-bottom: 40px;
    border: 2px solid #e9ecef;
    }
.service-info-section h3 {
    color: #000;
    font-size: 1.8em;
    margin-bottom: 30px;
    text-align: center;
    font-weight: 600;
    }
.service-info-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(380px, 1fr));
    gap: 30px;
    margin-top: 30px;
    }
.service-info-card {
    background: #f8f9fa;
    padding: 35px;
    border-radius: 15px;
    border: 2px solid #dee2e6;
    transition: all 0.3s ease;
    color: #000;
    }
.service-info-card:hover {
    transform: translatey(-5px);
    box-shadow: 0 8px 25px rgba(0, 0, 0, 0.12);
    border-color: #007bff;
    }
.service-info-card h4 {
    color: #000;
    font-size: 1.5em;
    margin-bottom: 20px;
    display: flex;
    align-items: center;
    gap: 15px;
    font-weight: 600;
    }
.service-icon {
    width: 50px;
    height: 50px;
    background: #007bff;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    color: white;
    font-size: 1.4em;
    }
.service-description {
    color: #000;
    margin-bottom: 20px;
    line-height: 1.8;
    font-size: 1.1em;
    }
.service-features {
    background: #fff;
    padding: 20px;
    border-radius: 10px;
    margin-bottom: 20px;
    border: 1px solid #dee2e6;
    }
.service-features strong {
    color: #000;
    font-size: 1.1em;
    }
.service-features ul {
    list-style: none;
    padding: 0;
    margin-top: 15px;
    }
.service-features li {
    padding: 8px 0;
    color: #000;
    font-size: 1.05em;
    }
.service-features li::before {
    content: "✓";
    color: #28a745;
    font-weight: bold;
    margin-right: 12px;
    font-size: 1.2em;
    }
.price-range {
    background: #007bff;
    color: white;
    padding: 15px 20px;
    border-radius: 10px;
    font-weight: 600;
    text-align: center;
    font-size: 1.1em;
    }
.form-section {
    background: #fff;
    padding: 40px;
    border-radius: 15px;
    margin-bottom: 40px;
    border: 2px solid #e9ecef;
    }
.form-section h3 {
    color: #000;
    font-size: 1.6em;
    margin-bottom: 30px;
    display: flex;
    align-items: center;
    gap: 15px;
    font-weight: 600;
    }
.guards-selection {
    background: #fff;
    padding: 40px;
    border-radius: 15px;
    margin: 40px 0;
    border: 2px solid #e9ecef;
    text-align: center;
    }
.guards-selection h3 {
    color: #000;
    font-size: 1.6em;
    margin-bottom: 20px;
    font-weight: 600;
    }
.guards-selection p {
    color: #495057;
    margin-bottom: 30px;
    font-size: 1.1em;
    line-height: 1.6;
    }
.guards-options {
    display: flex;
    justify-content: center;
    gap: 50px;
    margin-top: 30px;
    }
.guard-option {
    background: #f8f9fa;
    padding: 30px 50px;
    border-radius: 15px;
    border: 3px solid #dee2e6;
    cursor: pointer;
    transition: all 0.3s ease;
    min-width: 180px;
    position: relative;
    color: #000;
    }
.guard-option:hover, .guard-option.selected {
    border-color: #007bff;
    background: #e3f2fd;
    transform: translatey(-3px);
    box-shadow: 0 8px 25px rgba(0, 123, 255, 0.2);
    }
.guard-option input[type="radio"] {
    position: absolute;
    top: 15px;
    right: 15px;
    transform: scale(1.5);
    accent-color: #007bff;
    }
.guard-option strong {
    color: #000;
    font-size: 1.3em;
    display: block;
    margin-bottom: 8px;
    }
.guard-option .description {
    font-size: 1em;
    color: #6c757d;
    }
.countries-section {
    background: #fff;
    padding: 40px;
    border-radius: 15px;
    margin: 40px 0;
    border: 2px solid #e9ecef;
    }
.countries-section h3 {
    color: #000;
    font-size: 1.6em;
    margin-bottom: 20px;
    display: flex;
    align-items: center;
    gap: 15px;
    font-weight: 600;
    }
.route-description {
    margin-bottom: 30px;
    color: #495057;
    text-align: center;
    font-style: italic;
    font-size: 1.1em;
    line-height: 1.6;
    }
.country-row {
    background: #f8f9fa;
    padding: 30px;
    border-radius: 15px;
    margin-bottom: 25px;
    border: 2px solid #dee2e6;
    transition: all 0.3s ease;
    }
.country-row:hover {
    background: #fff;
    box-shadow: 0 6px 20px rgba(0, 0, 0, 0.1);
    border-color: #007bff;
    }
.country-header {
    display: grid;
    grid-template-columns: 2fr 1fr 80px;
    gap: 25px;
    align-items: center;
    margin-bottom: 25px;
    }
.country-select, .hours-input {
    padding: 18px 20px;
    border: 2px solid #ced4da;
    border-radius: 10px;
    font-size: 16px;
    background: white;
    transition: all 0.3s ease;
    color: #000;
    font-weight: 500;
    }
.country-select:focus, .hours-input:focus {
    outline: none;
    border-color: #007bff;
    box-shadow: 0 0 0 3px rgba(0, 123, 255, 0.1);
    }
.remove-btn {
    background: #dc3545;
    color: white;
    border: none;
    border-radius: 10px;
    padding: 18px;
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
    border-top: 2px solid #dee2e6;
    padding-top: 25px;
    }
.services-for-country h5 {
    color: #000;
    margin-bottom: 20px;
    font-size: 1.2em;
    font-weight: 600;
    }
.service-checkboxes {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 20px;
    }
.service-checkbox {
    display: flex;
    align-items: center;
    gap: 15px;
    padding: 20px;
    background: #fff;
    border-radius: 10px;
    border: 2px solid #dee2e6;
    transition: all 0.3s ease;
    cursor: pointer;
    color: #000;
    }
.service-checkbox:hover {
    border-color: #007bff;
    background: #e3f2fd;
    }
.service-checkbox.selected {
    border-color: #007bff;
    background: #e3f2fd;
    box-shadow: 0 4px 15px rgba(0, 123, 255, 0.2);
    }
.service-checkbox input[type="checkbox"] {
    transform: scale(1.4);
    accent-color: #007bff;
    }
.service-checkbox label {
    cursor: pointer;
    font-weight: 500;
    color: #000;
    font-size: 1.1em;
    }
.add-country-btn {
    background: linear-gradient(135deg, #28a745, #20c997);
    color: white;
    border: none;
    border-radius: 12px;
    padding: 20px 40px;
    font-size: 16px;
    font-weight: bold;
    cursor: pointer;
    transition: all 0.3s ease;
    margin: 30px 0;
    box-shadow: 0 6px 20px rgba(40, 167, 69, 0.3);
    }
.add-country-btn:hover {
    transform: translatey(-3px);
    box-shadow: 0 10px 25px rgba(40, 167, 69, 0.4);
    }
.fixprice-section {
    background: #fff8e1;
    padding: 40px;
    border-radius: 15px;
    margin: 40px 0;
    border: 3px solid #ffc107;
    }
.fixprice-section h3 {
    color: #000;
    font-size: 1.8em;
    margin-bottom: 25px;
    display: flex;
    align-items: center;
    gap: 15px;
    font-weight: 600;
    }
.fixprice-description {
    margin-bottom: 25px;
    color: #000;
    font-style: italic;
    font-size: 1.1em;
    line-height: 1.6;
    }
.fixprice-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(380px, 1fr));
    gap: 25px;
    margin-top: 30px;
    }
.fixprice-item {
    background: #fff;
    padding: 25px;
    border-radius: 12px;
    border: 2px solid #ffc107;
    transition: all 0.3s ease;
    cursor: pointer;
    }
.fixprice-item:hover {
    border-color: #ff9800;
    transform: translatey(-2px);
    box-shadow: 0 8px 20px rgba(255, 193, 7, 0.3);
    }
.fixprice-item.selected {
    border-color: #ff9800;
    background: #fff8e1;
    }
.fixprice-header {
    display: flex;
    align-items: center;
    gap: 20px;
    margin-bottom: 15px;
    }
.fixprice-header input[type="checkbox"] {
    transform: scale(1.5);
    accent-color: #ffc107;
    }
.fixprice-title {
    font-weight: 600;
    color: #000;
    font-size: 1.2em;
    flex: 1;
    }
.fixprice-price {
    font-weight: bold;
    color: #000;
    background: #ffc107;
    padding: 10px 15px;
    border-radius: 8px;
    font-size: 1.2em;
    }
.fixprice-description-text {
    color: #000;
    font-size: 1em;
    margin-top: 10px;
    line-height: 1.6;
    }
.calculate-btn {
    background: linear-gradient(135deg, #007bff, #0056b3);
    color: white;
    padding: 25px 80px;
    border: none;
    border-radius: 15px;
    font-size: 24px;
    font-weight: bold;
    cursor: pointer;
    transition: all 0.3s ease;
    display: block;
    margin: 60px auto;
    text-transform: uppercase;
    letter-spacing: 1px;
    box-shadow: 0 8px 25px rgba(0, 123, 255, 0.4);
    }
.calculate-btn:hover {
    transform: translatey(-4px);
    box-shadow: 0 15px 35px rgba(0, 123, 255, 0.5);
    }
.result-section {
    background: #d4edda;
    color: #000;
    padding: 60px;
    border-radius: 20px;
    margin-top: 50px;
    box-shadow: 0 15px 40px rgba(40, 167, 69, 0.3);
    display: none;
    border: 3px solid #28a745;
    }
.result-header {
    text-align: center;
    margin-bottom: 50px;
    }
.result-header h3 {
    font-size: 2.8em;
    margin-bottom: 20px;
    color: #000;
    font-weight: 600;
    }
.total-price {
    font-size: 5em;
    font-weight: bold;
    text-align: center;
    margin: 40px 0;
    color: #000;
    }
.total-summary {
    text-align: center;
    font-size: 1.4em;
    margin-bottom: 50px;
    background: #fff;
    padding: 25px;
    border-radius: 12px;
    border: 2px solid #28a745;
    color: #000;
    line-height: 1.8;
    }
.breakdown-section {
    background: #fff;
    padding: 40px;
    border-radius: 15px;
    margin-top: 40px;
    border: 2px solid #28a745;
    }
.breakdown-title {
    font-size: 1.8em;
    margin-bottom: 30px;
    text-align: center;
    font-weight: 600;
    color: #000;
    }
.country-breakdown {
    background: #f8f9fa;
    padding: 25px;
    border-radius: 12px;
    margin: 20px 0;
    border: 2px solid #dee2e6;
    border-left: 5px solid #007bff;
    }
.country-breakdown h5 {
    margin-bottom: 15px;
    font-size: 1.3em;
    font-weight: 600;
    color: #000;
    }
.service-breakdown {
    margin: 10px 0;
    padding: 10px 0;
    border-bottom: 1px solid #dee2e6;
    display: flex;
    justify-content: space-between;
    color: #000;
    font-size: 1.1em;
    }
.breakdown-item {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px 0;
    border-bottom: 1px solid #dee2e6;
    font-size: 1.1em;
    color: #000;
    }
.breakdown-item:last-child {
    border-bottom: none;
    font-weight: bold;
    font-size: 1.4em;
    margin-top: 25px;
    padding-top: 30px;
    border-top: 3px solid #007bff;
    }
.footer-info {
    text-align: center;
    margin-top: 50px;
    padding: 30px;
    background: #fff;
    border-radius: 12px;
    border: 2px solid #28a745;
    color: #000;
    font-size: 1.1em;
    line-height: 1.8;
    }
/* Responsive Design */
@media (max-width: 768px) {
    .container {
        padding: 20px;
        }
    .header {
        padding: 30px 25px;
        }
    .logo-section {
        flex-direction: column;
        gap: 25px;
        }
    .title-section {
        text-align: center;
        }
    .main-title {
        font-size: 2.8em;
        }
    .country-header {
        grid-template-columns: 1fr;
        gap: 20px;
        }
    .service-info-grid, .fixprice-grid {
        grid-template-columns: 1fr;
        }
    .guards-options {
        flex-direction: column;
        gap: 25px;
        }
    .total-price {
        font-size: 3.8em;
        }
    .calculate-btn {
        padding: 20px 50px;
        font-size: 20px;
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
<img alt="Logo" src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wBDAAYEBQYFBAYGBQYHBwYIChAKCgkJChQODwwQFxQYGBcUFhYaHSUfGhsjHBYWICwgIyYnKSopGR8tMC0oMCUoKSj/2wBDAQcHBwoIChMKChMoGhYaKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCgoKCj/wAARCAABAAEDASIAAhEBAxEB/8QAFQABAQAAAAAAAAAAAAAAAAAAAAv/xAAUEAEAAAAAAAAAAAAAAAAAAAAA/8QAFQEBAQAAAAAAAAAAAAAAAAAAAAX/xAAUEQEAAAAAAAAAAAAAAAAAAAAA/9oADAMBAAIRAxEAPwCdABmX/9k="/>
</div>
<div class="title-section">
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
<!-- Service-Informationen -->
<section class="service-info-section">
<h3>🛡️ Unsere Sicherheitsdienstleistungen im Detail</h3>
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
</div>
</section>
<form id="priceCalculator">
<!-- Guards-Auswahl (global für alle Services) -->
<section class="guards-selection">
<h3>👥 Anzahl Guards (gilt für alle Escort Services)</h3>
<p>
                        Diese Einstellung gilt für alle Escort Services in allen Ländern. 
                        Static Guard und Language Services sind davon nicht betroffen.
                    </p>
<div class="guards-options">
<div class="guard-option">
<input name="guards" required="" type="radio" value="1"/>
<strong>1 Guard</strong>
<div class="description">Standard-Begleitung</div>
</div>
<div class="guard-option">
<input name="guards" required="" type="radio" value="2"/>
<strong>2 Guards</strong>
<div class="description">Erhöhte Sicherheit</div>
</div>
</div>
</section>
<!-- Multi-Länder mit Service-Auswahl pro Land -->
<section class="countries-section">
<h3>🌍 Route planen - Services pro Land</h3>
<p class="route-description">
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
<!-- Fixpreis Services mit korrekten Bezeichnungen -->
<section class="fixprice-section">
<h3>💰 Zusätzliche Fixpreis-Services</h3>
<p class="fixprice-description">
                        Einmalige Zusatzleistungen die unabhängig von Zeit und Ort berechnet werden:
                    </p>
<div class="fixprice-grid">
<div class="fixprice-item">
<div class="fixprice-header">
<input id="cancel_full" type="checkbox" value="250"/>
<div class="fixprice-title">Cancellation Fee (Full)</div>
<div class="fixprice-price">250,00 €</div>
</div>
<div class="fixprice-description-text">
                                Vollständige Stornierungsgebühr bei kurzfristiger Absage (weniger als 24h vor Einsatzbeginn)
                            </div>
</div>
<div class="fixprice-item">
<div class="fixprice-header">
<input id="cancel_pre" type="checkbox" value="100"/>
<div class="fixprice-title">Cancellation Fee (Pre)</div>
<div class="fixprice-price">100,00 €</div>
</div>
<div class="fixprice-description-text">
                                Vorab-Stornierungsgebühr bei Absage zwischen 24-48h vor Einsatzbeginn
                            </div>
</div>
<div class="fixprice-item">
<div class="fixprice-header">
<input id="police" type="checkbox" value="120"/>
<div class="fixprice-title">Police activation (for Alarm verification)</div>
<div class="fixprice-price">120,00 €</div>
</div>
<div class="fixprice-description-text">
                                Aktivierung und Koordination der örtlichen Polizei zur Alarmverifikation
                            </div>
</div>
<div class="fixprice-item">
<div class="fixprice-header">
<input id="lea" type="checkbox" value="120"/>
<div class="fixprice-title">Flat-rate activation/coordination of LEA, ambulance, etc.</div>
<div class="fixprice-price">120,00 €</div>
</div>
<div class="fixprice-description-text">
                                Pauschalgebühr für Aktivierung und Koordination von Behörden, Rettungsdiensten etc.
                            </div>
</div>
<div class="fixprice-item">
<div class="fixprice-header">
<input id="forwarding" type="checkbox" value="20"/>
<div class="fixprice-title">Forwarding of LEA invoices, per forwarded invoice</div>
<div class="fixprice-price">20,00 €</div>
</div>
<div class="fixprice-description-text">
                                Weiterleitung von Behördenrechnungen - Gebühr pro weitergeleiteter Rechnung
                            </div>
</div>
<div class="fixprice-item">
<div class="fixprice-header">
<input id="monitoring_sheet" type="checkbox" value="25"/>
<div class="fixprice-title">Monitorings, Orga per Sheet</div>
<div class="fixprice-price">25,00 €</div>
</div>
<div class="fixprice-description-text">
                                Monitoring und Organisation pro Dokumentationsblatt/Protokoll
                            </div>
</div>
<div class="fixprice-item">
<div class="fixprice-header">
<input id="monitoring_system" type="checkbox" value="8"/>
<div class="fixprice-title">Monitorings, per System Check</div>
<div class="fixprice-price">8,00 €</div>
</div>
<div class="fixprice-description-text">
                                Monitoring-Gebühr pro durchgeführtem Systemcheck/technischer Überprüfung
                            </div>
</div>
<div class="fixprice-item">
<div class="fixprice-header">
<input id="monitoring_call" type="checkbox" value="8"/>
<div class="fixprice-title">Monitorings, per Call Check</div>
<div class="fixprice-price">8,00 €</div>
</div>
<div class="fixprice-description-text">
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
<!-- Zusammenfassung wird hier eingefügt -->
</div>
<div class="breakdown-section">
<div class="breakdown-title">📊 Detaillierte Aufschlüsselung</div>
<div id="breakdown">
<!-- Breakdown wird hier eingefügt -->
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

        function addCountryRow() {
            const container = document.getElementById('countriesContainer');
            const newRow = container.children[0].cloneNode(true);
            
            // Reset values
            newRow.querySelector('.country-select').value = '';
            newRow.querySelector('.hours-input').value = '';
            
            // Reset checkboxes
            newRow.querySelectorAll('input[type="checkbox"]').forEach(cb => {
                cb.checked = false;
                cb.closest('.service-checkbox').classList.remove('selected');
            });
            
            newRow.querySelector('.remove-btn').style.display = 'block';
            
            container.appendChild(newRow);
            updateRemoveButtons();
        }

        function removeCountryRow(button) {
            button.closest('.country-row').remove();
            updateRemoveButtons();
        }

        function updateRemoveButtons() {
            const rows = document.querySelectorAll('.country-row');
            rows.forEach((row, index) => {
                const removeBtn = row.querySelector('.remove-btn');
                removeBtn.style.display = index === 0 && rows.length === 1 ? 'none' : 'block';
            });
        }

        function calculatePrice() {
            const guards = parseInt(document.querySelector('input[name="guards"]:checked')?.value);
            
            if (!guards) {
                showAlert('Bitte wählen Sie die Anzahl Guards aus.');
                return;
            }
            
            const countryRows = document.querySelectorAll('.country-row');
            let countries = [];
            let totalHours = 0;
            let totalServices = 0;
            
            // Länder und Services sammeln
            for (let row of countryRows) {
                const countrySelect = row.querySelector('.country-select');
                const hoursInput = row.querySelector('.hours-input');
                
                if (countrySelect.value && hoursInput.value) {
                    const region = parseInt(countrySelect.value) - 1;
                    const hours = parseFloat(hoursInput.value);
                    const countryName = countrySelect.options[countrySelect.selectedIndex].text;
                    
                    // Services für dieses Land sammeln
                    const services = {
                        escort: row.querySelector('.service-escort').checked,
                        language: row.querySelector('.service-language').checked,
                        static: row.querySelector('.service-static').checked
                    };
                    
                    // Prüfen ob mindestens ein Service gewählt
                    if (!services.escort && !services.language && !services.static) {
                        showAlert(`Bitte wählen Sie mindestens einen Service für ${countryName.split(' ')[1]} aus.`);
                        return;
                    }
                    
                    countries.push({
                        name: countryName,
                        region: region,
                        hours: hours,
                        services: services
                    });
                    
                    totalHours += hours;
                    if (services.escort) totalServices++;
                    if (services.language) totalServices++;
                    if (services.static) totalServices++;
                }
            }
            
            if (countries.length === 0) {
                showAlert('Bitte fügen Sie mindestens ein Land mit Services hinzu.');
                return;
            }
            
            let totalPrice = 0;
            let breakdown = [];
            
            // Preise pro Land berechnen
            countries.forEach(country => {
                let countryPrice = 0;
                let countryServices = [];
                
                if (country.services.language) {
                    const price = country.hours * prices.language[country.region];
                    countryPrice += price;
                    countryServices.push({
                        name: 'Language Services',
                        calculation: `${country.hours}h × ${prices.language[country.region]}€`,
                        price: price
                    });
                }
                
                if (country.services.static) {
                    const hours = Math.max(country.hours, 4); // Minimum 4h
                    const price = hours * prices.static[country.region];
                    countryPrice += price;
                    countryServices.push({
                        name: 'Static Guard',
                        calculation: `${hours}h × ${prices.static[country.region]}€${country.hours < 4 ? ' (min. 4h)' : ''}`,
                        price: price
                    });
                }
                
                if (country.services.escort) {
                    const price1 = country.hours * prices.escort1[country.region];
                    countryPrice += price1;
                    countryServices.push({
                        name: 'Escort 1. Guard',
                        calculation: `${country.hours}h × ${prices.escort1[country.region]}€`,
                        price: price1
                    });
                    
                    if (guards === 2) {
                        const price2 = country.hours * prices.escort2[country.region];
                        countryPrice += price2;
                        countryServices.push({
                            name: 'Escort 2. Guard',
                            calculation: `${country.hours}h × ${prices.escort2[country.region]}€`,
                            price: price2
                        });
                    }
                }
                
                totalPrice += countryPrice;
                breakdown.push({
                    country: country.name,
                    hours: country.hours,
                    price: countryPrice,
                    services: countryServices
                });
            });
            
            // Fixpreis-Services
            let fixpriceTotal = 0;
            let fixpriceItems = [];
            
            document.querySelectorAll('.fixprice-item input[type="checkbox"]:checked').forEach(checkbox => {
                const price = parseFloat(checkbox.value);
                const label = checkbox.closest('.fixprice-item').querySelector('.fixprice-title').textContent;
                fixpriceTotal += price;
                fixpriceItems.push({
                    name: label,
                    price: price
                });
            });
            
            totalPrice += fixpriceTotal;
            
            // Ergebnis anzeigen
            displayResults(totalPrice, totalHours, countries.length, totalServices, breakdown, fixpriceItems, fixpriceTotal);
        }

        function displayResults(totalPrice, totalHours, countryCount, serviceCount, breakdown, fixpriceItems, fixpriceTotal) {
            document.getElementById('finalPrice').textContent = 
                totalPrice.toLocaleString('de-DE', {minimumFractionDigits: 2}) + ' €';
            
            // Zusammenfassung
            document.getElementById('totalSummary').innerHTML = `
                <strong>Zusammenfassung:</strong><br>
                ${totalHours} Stunden durch ${countryCount} ${countryCount === 1 ? 'Land' : 'Länder'}<br>
                ${serviceCount} Service-Einsätze insgesamt<br>
                ${fixpriceItems.length > 0 ? fixpriceItems.length + ' Zusatzleistungen' : 'Keine Zusatzleistungen'}
            `;
            
            // Breakdown erstellen
            let breakdownHTML = '';
            
            // Länder-Breakdown
            breakdown.forEach(item => {
                breakdownHTML += `
                    <div class="country-breakdown">
                        <h5>${item.country} (${item.hours}h)</h5>
                `;
                
                item.services.forEach(service => {
                    breakdownHTML += `
                        <div class="service-breakdown">
                            <span>${service.name}: ${service.calculation}</span>
                            <span>${service.price.toFixed(2)} €</span>
                        </div>
                    `;
                });
                
                breakdownHTML += `
                        <div style="text-align: right; font-weight: bold; margin-top: 15px; padding-top: 10px; border-top: 1px solid #dee2e6;">
                            Subtotal: ${item.price.toFixed(2)} €
                        </div>
                    </div>
                `;
            });
            
            // Fixpreis-Services
            if (fixpriceItems.length > 0) {
                breakdownHTML += '<div style="margin: 25px 0; padding: 20px; background: #f8f9fa; border-radius: 12px; border: 2px solid #dee2e6;">';
                breakdownHTML += '<h5 style="margin-bottom: 15px; color: #000000;">Fixpreis-Services:</h5>';
                fixpriceItems.forEach(item => {
                    breakdownHTML += `<div class="breakdown-item">
                        <span>${item.name}</span>
                        <span>${item.price.toFixed(2)} €</span>
                    </div>`;
                });
                breakdownHTML += `<div style="text-align: right; font-weight: bold; margin-top: 15px; padding-top: 10px; border-top: 1px solid #dee2e6;">
                    Fixpreis-Summe: ${fixpriceTotal.toFixed(2)} €
                </div></div>`;
            }
            
            // Gesamtsumme
            breakdownHTML += `
                <div class="breakdown-item" style="font-size: 1.4em; margin-top: 25px;">
                    <span><strong>GESAMTPREIS</strong></span>
                    <span><strong>${totalPrice.toFixed(2)} €</strong></span>
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

        function showAlert(message) {
            // Moderne Alert-Alternative
            const alertDiv = document.createElement('div');
            alertDiv.style.cssText = `
                position: fixed;
                top: 20px;
                right: 20px;
                background: #dc3545;
                color: white;
                padding: 15px 20px;
                border-radius: 10px;
                box-shadow: 0 8px 25px rgba(220, 53, 69, 0.4);
                z-index: 10000;
                font-weight: bold;
                animation: slideIn 0.3s ease;
                max-width: 300px;
                border: 2px solid #c82333;
            `;
            alertDiv.textContent = message;
            
            // Animation CSS hinzufügen
            if (!document.querySelector('#alertStyles')) {
                const style = document.createElement('style');
                style.id = 'alertStyles';
                style.textContent = `
                    @keyframes slideIn {
                        from { transform: translateX(100%); opacity: 0; }
                        to { transform: translateX(0); opacity: 1; }
                    }
                `;
                document.head.appendChild(style);
            }
            
            document.body.appendChild(alertDiv);
            
            setTimeout(() => {
                alertDiv.style.animation = 'slideIn 0.3s ease reverse';
                setTimeout(() => alertDiv.remove(), 300);
            }, 4000);
        }
    </script>
</body>
</html>
