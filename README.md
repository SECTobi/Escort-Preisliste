<!DOCTYPE html>

<html lang="de">
<head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>SECompanion - Escort Service Preisrechner</title>
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
    /* GEÄNDERT: Hintergrundbild aus den hochgeladenen Dateien */
    background-image: url('uploaded:image_29733f.jpg-65cff0ba-b357-415e-935f-f0697f0baf3b');
    background-size: cover;
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-color: #1e3c72; /* Fallback-Farbe */
    min-height: 100vh;
    color: #333;
    line-height: 1.6;
    font-size: 16px;
    margin: 0 24px 0 24px;
    padding: 0;
    max-width: None;
    }
.header {
    background: rgba(255, 255, 255, 0.98);
    padding: 40px;
    border-radius: 20px;
    text-align: center;
    margin-bottom: 30px;
    box-shadow: 0 15px 35px rgba(0, 0, 0, 0.1);
    border: 3px solid #2a5298;
    }
.logo-section {
    display: flex;
    align-items: center;
    justify-content: center;
    margin-bottom: 20px;
    gap: 20px;
    }
.logo {
    width: 80px;
    height: 80px;
    background: linear-gradient(135deg, #2a5298, #1e3c72);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    color: white;
    font-size: 2em;
    font-weight: bold;
    box-shadow: 0 8px 20px rgba(42, 82, 152, 0.3);
    overflow: hidden; 
    }
.company-name {
    font-size: 2.5em;
    color: #1e3c72;
    font-weight: bold;
    margin: 0;
    }
.tagline {
    font-size: 1.2em;
    color: #2a5298;
    margin: 10px 0;
    font-weight: 500;
    }
.company-info {
    background: linear-gradient(135deg, #f8f9ff, #e8f0ff);
    padding: 25px;
    border-radius: 15px;
    margin: 20px 0;
    border-left: 5px solid #2a5298;
    }
.company-info h3 {
    color: #1e3c72;
    margin-bottom: 15px;
    font-size: 1.3em;
    }
.info-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 15px;
    margin-top: 15px;
    }
.info-item {
    display: flex;
    align-items: center;
    gap: 10px;
    }
.info-icon {
    width: 30px;
    height: 30px;
    background: #2a5298;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    color: white;
    font-size: 0.9em;
    }
.calculator-section {
    background: rgba(255, 255, 255, 0.98);
    padding: 40px;
    border-radius: 20px;
    box-shadow: 0 15px 35px rgba(0, 0, 0, 0.1);
    border: 3px solid #2a5298;
    }
.calculator-section h2 {
    color: #1e3c72;
    font-size: 2.2em;
    margin-bottom: 30px;
    text-align: center;
    position: relative;
    }
.calculator-section h2::after {
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
.service-info {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
    gap: 25px;
    margin: 30px 0;
    }
.service-card {
    background: linear-gradient(135deg, #f8f9ff, #e8f0ff);
    padding: 30px;
    border-radius: 15px;
    border-left: 5px solid #2a5298;
    transition: transform 0.3s, box-shadow 0.3s;
    }
.service-card:hover {
    transform: translatey(-5px);
    box-shadow: 0 10px 25px rgba(42, 82, 152, 0.2);
    }
.service-card h4 {
    color: #1e3c72;
    font-size: 1.3em;
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
.price-range {
    background: rgba(42, 82, 152, 0.1);
    padding: 10px 15px;
    border-radius: 8px;
    margin-top: 10px;
    font-weight: bold;
    color: #1e3c72;
    }
.form-container {
    background: #f8f9ff;
    padding: 35px;
    border-radius: 15px;
    margin: 30px 0;
    }
.form-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 25px;
    margin-bottom: 30px;
    }
.form-group {
    display: flex;
    flex-direction: column;
    }
.form-group label {
    font-weight: bold;
    margin-bottom: 8px;
    color: #1e3c72;
    font-size: 1.1em;
    }
.form-group select, .form-group input {
    padding: 15px;
    border: 2px solid #ddd;
    border-radius: 10px;
    font-size: 16px;
    transition: border-color 0.3s, box-shadow 0.3s;
    background: white;
    }
.form-group select:focus, .form-group input:focus {
    outline: none;
    border-color: #2a5298;
    box-shadow: 0 0 0 3px rgba(42, 82, 152, 0.1);
    }
.additional-services {
    background: white;
    padding: 25px;
    border-radius: 15px;
    margin: 25px 0;
    border: 2px solid #e8f0ff;
    }
.additional-services h3 {
    color: #1e3c72;
    margin-bottom: 20px;
    font-size: 1.3em;
    }
.services-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 20px;
    }
.service-option {
    display: flex;
    align-items: center;
    gap: 15px;
    padding: 15px;
    background: #f8f9ff;
    border-radius: 10px;
    border: 2px solid transparent;
    transition: all 0.3s;
    }
.service-option:hover {
    border-color: #2a5298;
    }
.service-option input[type="checkbox"] {
    width: 20px;
    height: 20px;
    accent-color: #2a5298;
    }
.calculate-btn {
    background: linear-gradient(135deg, #2a5298, #1e3c72);
    color: white;
    padding: 18px 50px;
    border: none;
    border-radius: 12px;
    font-size: 18px;
    font-weight: bold;
    cursor: pointer;
    transition: all 0.3s;
    display: block;
    margin: 30px auto;
    box-shadow: 0 8px 20px rgba(42, 82, 152, 0.3);
    }
.calculate-btn:hover {
    transform: translatey(-3px);
    box-shadow: 0 12px 25px rgba(42, 82, 152, 0.4);
    }
.price-display {
    background: linear-gradient(135deg, #4CAF50, #45a049);
    color: white;
    padding: 40px;
    border-radius: 20px;
    text-align: center;
    margin-top: 30px;
    box-shadow: 0 15px 35px rgba(76, 175, 80, 0.3);
    display: none;
    }
.price-display h3 {
    font-size: 1.8em;
    margin-bottom: 15px;
    }
.price-display .price {
    font-size: 3.5em;
    font-weight: bold;
    margin: 20px 0;
    }
.price-breakdown {
    background: rgba(255, 255, 255, 0.2);
    padding: 20px;
    border-radius: 15px;
    margin-top: 20px;
    text-align: left;
    }
.breakdown-item {
    display: flex;
    justify-content: space-between;
    margin: 10px 0;
    padding: 8px 0;
    border-bottom: 1px solid rgba(255, 255, 255, 0.3);
    }
.contact-section {
    background: rgba(255, 255, 255, 0.98);
    padding: 40px;
    border-radius: 20px;
    margin-top: 30px;
    text-align: center;
    border: 3px solid #2a5298;
    }
.contact-section h3 {
    color: #1e3c72;
    font-size: 1.8em;
    margin-bottom: 25px;
    }
.contact-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 25px;
    margin-top: 25px;
    }
.contact-item {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 15px;
    padding: 20px;
    background: #f8f9ff;
    border-radius: 12px;
    }
.contact-icon {
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
@media (max-width: 768px) {
    .container {
        padding: 10px;
        }
    .header {
        padding: 25px;
        }
    .logo-section {
        flex-direction: column;
        gap: 15px;
        }
    .company-name {
        font-size: 2em;
        }
    .form-grid, .service-info, .services-grid {
        grid-template-columns: 1fr;
        }
    .calculator-section {
        padding: 25px;
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
                font-size: 1em; 
                font-weight: 400;
                margin-bottom: 1.2em;
                line-height: 1.8;
            }

            p {
                font-size: 1em;
                line-height: 1.8; 
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
            font-size: 0.8em; 
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
<div class="header">
<div class="logo-section">
<div class="logo">
    <img src="uploaded:image_1c53e3.png-380f4565-0f39-43e3-941b-3669b71d78dd" alt="SECompanion Logo" style="width: 100%; height: 100%; border-radius: 50%; object-fit: cover;"/>
</div>
<div>
<h1 class="company-name">SECompanion GmbH</h1>
<p class="tagline">Ihr professioneller Sicherheitspartner</p>
</div>
</div>
<div class="company-info">
<h3>🛡️ Über SECompanion</h3>
<p>Seit April 2020 Ihr zuverlässiger Partner für Sicherheitsdienste in ganz Europa. Mit unserem erfahrenen Team von 60+ Mitarbeitern gewährleisten wir 24/7 Verfügbarkeit und professionelle Abwicklung aller Sicherheitsdienstleistungen.</p>
<div class="info-grid">
<div class="info-item">
<div class="info-icon">📍</div>
<span>Sitz in Bayern, Deutschland</span>
</div>
<div class="info-item">
<div class="info-icon">🕒</div>
<span>24/7 Verfügbarkeit</span>
</div>
<div class="info-item">
<div class="info-icon">👥</div>
<span>60+ qualifizierte Mitarbeiter</span>
</div>
<div class="info-item">
<div class="info-icon">⚡</div>
<span>&lt; 3 Min. Reaktionszeit</span>
</div>
</div>
</div>
</div>
<div class="calculator-section">
<h2>🚗 Escort Service Preisrechner</h2>
<div class="service-info">
<div class="service-card">
<h4>
<div class="service-icon">🗣️</div>
                        Language Services
                    </h4>
<p>Professionelle Dolmetscher und Übersetzungsleistungen für internationale Einsätze und mehrsprachige Kommunikation.</p>
<div class="price-range">120,00 € pro Stunde (alle Regionen)</div>
</div>
<div class="service-card">
<h4>
<div class="service-icon">🏢</div>
                        Static Guard
                    </h4>
<p>Objektschutz an festen Standorten mit qualifizierten Sicherheitskräften. Minimum 4 Stunden Einsatzzeit.</p>
<div class="price-range">120,00 - 150,00 € pro Stunde</div>
</div>
<div class="service-card">
<h4>
<div class="service-icon">🚗</div>
                        Escort Services
                    </h4>
<p>Professioneller Begleitschutz für Transporte und Fahrten mit 1 oder 2 Guards für maximale Sicherheit.</p>
<div class="price-range">135,00 - 160,00 € (1. Guard) + 70,00 - 90,00 € (2. Guard)</div>
</div>
</div>
<div class="form-container">
<form id="priceCalculator">
<div class="form-grid">
<div class="form-group">
<label for="country">🌍 Land auswählen:</label>
<select id="country" required="">
<option value="">Bitte wählen Sie ein Land...</option>
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
</div>
<div class="form-group">
<label for="hours">⏱️ Fahrtzeit (Stunden):</label>
<input id="hours" min="0.5" placeholder="z.B. 3.5" required="" step="0.5" type="number"/>
</div>
<div class="form-group">
<label for="guards">👥 Anzahl Guards:</label>
<select id="guards" required="">
<option value="">Bitte wählen...</option>
<option value="1">1 Guard</option>
<option value="2">2 Guards</option>
</select>
</div>
<div class="form-group">
<label for="service">🛡️ Hauptservice:</label>
<select id="service" required="">
<option value="">Bitte wählen...</option>
<option value="language">Language Services</option>
<option value="static">Static Guard</option>
<option value="escort">Escort Services</option>
</select>
</div>
</div>
<div class="additional-services">
<h3>➕ Zusätzliche Services</h3>
<div class="services-grid">
<div class="service-option">
<input id="additionalLanguage" type="checkbox" value="120"/>
<label for="additionalLanguage">
<strong>Zusätzliche Sprachdienste</strong><br/>
<small>120,00 € pro Stunde</small>
</label>
</div>
<div class="service-option">
<input id="additionalStatic" type="checkbox" value="varies"/>
<label for="additionalStatic">
<strong>Zusätzliche statische Bewachung</strong><br/>
<small>120,00 - 150,00 € pro Stunde</small>
</label>
</div>
</div>
</div>
<button class="calculate-btn" onclick="calculatePrice()" type="button">
                        💰 Preis berechnen
                    </button>
</form>
<div class="price-display" id="priceResult">
<h3>Ihr individueller Preis:</h3>
<div class="price" id="finalPrice">0,00 €</div>
<div class="price-breakdown" id="breakdown">
</div>
<p><strong>Alle Preise verstehen sich zzgl. MwSt.</strong></p>
<p>Gültig für das Jahr 2025 | Änderungen vorbehalten</p>
</div>
</div>
</div>
<div class="contact-section">
<h3>📞 Kontaktieren Sie uns für ein individuelles Angebot</h3>
<p>Unser erfahrenes Team steht Ihnen 24/7 zur Verfügung und erstellt gerne ein maßgeschneidertes Sicherheitskonzept für Ihre Anforderungen.</p>
<div class="contact-grid">
<div class="contact-item">
<div class="contact-icon">📧</div>
<div>
<strong>E-Mail</strong><br/>
                        info@secompanion.de
                    </div>
</div>
<div class="contact-item">
<div class="contact-icon">📱</div>
<div>
<strong>24/7 Hotline</strong><br/>
                        +49 (0) XXX XXXXXXX
                    </div>
</div>
<div class="contact-item">
<div class="contact-icon">🌐</div>
<div>
<strong>Website</strong><br/>
                        www.secompanion.de
                    </div>
</div>
<div class="contact-item">
<div class="contact-icon">📍</div>
<div>
<strong>Standort</strong><br/>
                        Bayern, Deutschland
                    </div>
</div>
</div>
</div>
</div>
<script>
        // Preistabelle basierend auf Ihrer Excel-Datei
        const prices = {
            language: [120, 120, 120],  // Region 1, 2, 3
            static: [120, 138, 150],
            escort1: [135, 150, 160],
            escort2: [70, 80, 90]
        };
        
        function calculatePrice() {
            const country = document.getElementById('country').value;
            const hours = parseFloat(document.getElementById('hours').value);
            const guards = parseInt(document.getElementById('guards').value);
            const service = document.getElementById('service').value;
            const additionalLanguage = document.getElementById('additionalLanguage').checked;
            const additionalStatic = document.getElementById('additionalStatic').checked;
            
            if (!country || !hours || !guards || !service) {
                alert('Bitte füllen Sie alle Pflichtfelder aus.');
                return;
            }
            
            const region = parseInt(country) - 1; // 0-basiert für Array
            let totalPrice = 0;
            let breakdown = [];
            
            // Hauptservice berechnen
            if (service === 'language') {
                const price = hours * prices.language[region];
                totalPrice += price;
                breakdown.push({
                    service: 'Language Services',
                    calculation: `${hours}h × ${prices.language[region]}€`,
                    price: price
                });
            } else if (service === 'static') {
                const price = Math.max(hours, 4) * prices.static[region]; // Minimum 4h
                totalPrice += price;
                breakdown.push({
                    service: 'Static Guard',
                    calculation: `${Math.max(hours, 4)}h × ${prices.static[region]}€`,
                    price: price
                });
            } else if (service === 'escort') {
                const price1 = hours * prices.escort1[region];
                totalPrice += price1;
                breakdown.push({
                    service: 'Escort 1. Guard',
                    calculation: `${hours}h × ${prices.escort1[region]}€`,
                    price: price1
                });
                
                if (guards === 2) {
                    const price2 = hours * prices.escort2[region];
                    totalPrice += price2;
                    breakdown.push({
                        service: 'Escort 2. Guard',
                        calculation: `${hours}h × ${prices.escort2[region]}€`,
                        price: price2
                    });
                }
            }
            
            // Zusätzliche Services
            if (additionalLanguage) {
                const price = hours * prices.language[region];
                totalPrice += price;
                breakdown.push({
                    service: 'Zusätzliche Sprachdienste',
                    calculation: `${hours}h × ${prices.language[region]}€`,
                    price: price
                });
            }
            
            if (additionalStatic) {
                const price = hours * prices.static[region];
                totalPrice += price;
                breakdown.push({
                    service: 'Zusätzliche statische Bewachung',
                    calculation: `${hours}h × ${prices.static[region]}€`,
                    price: price
                });
            }
            
            // Ergebnis anzeigen
            document.getElementById('finalPrice').textContent = 
                totalPrice.toLocaleString('de-DE', {minimumFractionDigits: 2}) + ' €';
            
            // Breakdown erstellen
            let breakdownHTML = '<h4>Preisaufschlüsselung:</h4>';
            breakdown.forEach(item => {
                breakdownHTML += `
                    <div class="breakdown-item">
                        <span>${item.service}</span>
                        <span>${item.calculation} = ${item.price.toLocaleString('de-DE', {minimumFractionDigits: 2})} €</span>
                    </div>
                `;
            });
            
            document.getElementById('breakdown').innerHTML = breakdownHTML;
            document.getElementById('priceResult').style.display = 'block';
            
            // Smooth scroll zum Ergebnis
            document.getElementById('priceResult').scrollIntoView({ 
                behavior: 'smooth',
                block: 'center'
            });
        }
        
        // Form Reset bei Service-Änderung
        document.getElementById('service').addEventListener('change', function() {
            document.getElementById('priceResult').style.display = 'none';
        });
    </script>
</body>
</html>
