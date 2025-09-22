# Pooja-Sethu-Single-Page


<!DOCTYPE html>
<html lang="te">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>శ్రీ బాలాత్రిపురసుందరి అవతారం - ప్రత్యేకత</title>
    <style>
        /* Reset and Base Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            background: linear-gradient(135deg, #f9f0ff 0%, #e6f0ff 100%);
            min-height: 100vh;
            padding: 20px;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            background-color: rgba(255, 255, 255, 0.95);
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            position: relative;
        }
        
        /* Header Styles */
        header {
            background: linear-gradient(135deg, #ff66b2 0%, #ff99cc 100%);
            color: white;
            text-align: center;
            padding: 30px 20px;
            position: relative;
            overflow: hidden;
        }
        
        .header-content {
            position: relative;
            z-index: 2;
        }
        
        h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.2);
        }
        
        .subtitle {
            font-size: 1.2rem;
            opacity: 0.9;
        }
        
        .flower-decoration {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            opacity: 0.3;
            background-image: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100"><path fill="white" d="M50,10 C60,10 70,15 75,25 C80,35 80,45 75,55 C70,65 60,70 50,70 C40,70 30,65 25,55 C20,45 20,35 25,25 C30,15 40,10 50,10 Z M50,30 C53,30 56,32 56,35 C56,38 53,40 50,40 C47,40 44,38 44,35 C44,32 47,30 50,30 Z"/></svg>');
            background-size: 80px;
            z-index: 1;
        }
        
        /* Content Sections */
        .content {
            padding: 30px;
        }
        
        section {
            margin-bottom: 40px;
            padding: 25px;
            border-radius: 10px;
            background: #fff;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
            transition: transform 0.3s ease;
        }
        
        section:hover {
            transform: translateY(-5px);
        }
        
        h2 {
            color: #ff66b2;
            margin-bottom: 15px;
            font-size: 1.8rem;
            border-bottom: 2px solid #ffccdd;
            padding-bottom: 8px;
        }
        
        h3 {
            color: #ff66b2;
            margin: 15px 0 10px;
            font-size: 1.4rem;
        }
        
        p {
            margin-bottom: 15px;
            font-size: 1.1rem;
            text-align: justify;
        }
        
        ul {
            margin-left: 20px;
            margin-bottom: 15px;
        }
        
        li {
            margin-bottom: 8px;
            font-size: 1.1rem;
        }
        
        .highlight {
            background-color: #fff0f5;
            padding: 15px;
            border-left: 4px solid #ff66b2;
            margin: 20px 0;
            font-style: italic;
        }
        
        .mantra-box {
            background: linear-gradient(135deg, #ffccdd 0%, #ff99cc 100%);
            padding: 20px;
            border-radius: 10px;
            text-align: center;
            margin: 20px 0;
            font-size: 1.3rem;
            font-weight: bold;
            color: #8b005d;
            box-shadow: 0 5px 15px rgba(255, 102, 178, 0.2);
        }
        
        /* Calendar Section */
        .calendar {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        
        .day-card {
            background: white;
            border-radius: 10px;
            padding: 20px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
            transition: transform 0.3s ease;
            border-top: 4px solid #ff66b2;
        }
        
        .day-card:hover {
            transform: translateY(-5px);
        }
        
        .date {
            font-weight: bold;
            color: #ff66b2;
            margin-bottom: 10px;
            font-size: 1.1rem;
        }
        
        .avatar-name {
            font-weight: bold;
            margin-bottom: 10px;
            color: #333;
        }
        
        .avatar-details {
            margin-top: 10px;
        }
        
        .detail-item {
            margin-bottom: 5px;
            display: flex;
        }
        
        .detail-label {
            font-weight: bold;
            min-width: 120px;
            color: #666;
        }
        
        /* Footer */
        footer {
            text-align: center;
            padding: 20px;
            background: linear-gradient(135deg, #ff66b2 0%, #ff99cc 100%);
            color: white;
            margin-top: 30px;
        }
        
        /* Animation for spiritual effect */
        @keyframes float {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-10px); }
            100% { transform: translateY(0px); }
        }
        
        .floating {
            animation: float 5s ease-in-out infinite;
        }
        
        /* Responsive Design */
        @media (max-width: 768px) {
            h1 {
                font-size: 2rem;
            }
            
            .calendar {
                grid-template-columns: 1fr;
            }
            
            section {
                padding: 15px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <div class="flower-decoration"></div>
            <div class="header-content">
                <h1 class="floating">🌸 శ్రీ బాలాత్రిపురసుందరి అవతారం – ప్రత్యేకత 🌸</h1>
                <p class="subtitle">శ్రీ బాలాత్రిపురసుందరి దేవి, త్రిపురసుందరి అమ్మవారి బాలరూపం</p>
            </div>
        </header>
        
        <div class="content">
            <section id="introduction">
                <h2>శ్రీ బాలాత్రిపురసుందరి అవతారం (శక్తి అవతారం)</h2>
                <h3>పరిచయం</h3>
                <p>శ్రీ బాలాత్రిపురసుందరి దేవి, త్రిపురసుందరి అమ్మవారి బాలరూపం. ఈ అవతారం ద్వారా అమ్మవారు సౌందర్యం, జ్ఞానం, బలం, కరుణ లను ప్రసాదిస్తారు. ఇది దేవి శక్తి యొక్క చిన్న వయస్సులోనూ అపారమైన శక్తి, దివ్య జ్ఞానం, సౌందర్యం ఎలా ఉంటుందో తెలిపే అవతారం.</p>
            </section>
            
            <section id="speciality">
                <h2>అవతార విశేషం</h2>
                <ul>
                    <li>బాల రూపంలో ఉన్నా అపారమైన శక్తిని కలిగిన తల్లి.</li>
                    <li>అజ్ఞానం, దుర్గుణాలను తొలగించి భక్తులకు శాంతి, ఐశ్వర్యం, విద్య, జ్ఞానం ఇస్తుంది.</li>
                    <li>విద్యార్థులు, చిన్నపిల్లలు ఎక్కువగా ఈ అమ్మవారిని పూజిస్తారు.</li>
                    <li>శారీరక, మానసిక శక్తిని పెంచే అవతారం.</li>
                </ul>
            </section>
            
            <section id="importance">
                <h2>ప్రాముఖ్యత</h2>
                <ul>
                    <li>ఈ అవతారం సత్ప్రవర్తన, నిర్దోషత, పావిత్ర్యం కు ప్రతీక.</li>
                    <li>అమ్మవారిని స్మరించినవారికి విద్యాభివృద్ధి, మానసిక ప్రశాంతత కలుగుతుంది.</li>
                    <li>పిల్లల రక్షణకు, వారి ఆరోగ్యం, విద్యలో విజయానికి ప్రత్యేకంగా ప్రార్థిస్తారు.</li>
                </ul>
            </section>
            
            <section id="benefits">
                <h2>పూజా ఫలితాలు</h2>
                <ul>
                    <li>విద్యలో అగ్రగాములు కావడానికి దీవెనలు లభిస్తాయి.</li>
                    <li>భక్తుల గృహంలో సౌఖ్యం, శాంతి, ఐశ్వర్యం పెరుగుతాయి.</li>
                    <li>చిన్నపిల్లలకు రోగాలు దూరమవుతాయి, ఆరోగ్యం కాపాడబడుతుంది.</li>
                    <li>మానసికంగా బలంగా ఉండే శక్తిని ప్రసాదిస్తుంది.</li>
                </ul>
            </section>
            
            <section id="mantra">
                <h2>మంత్రం</h2>
                <div class="mantra-box">
                    "ఓం ఐం హ్రీం శ్రీం బాలాత్రిపురసుందర్యై నమః"
                </div>
                <p>ఈ మంత్రాన్ని భక్తితో జపిస్తే అమ్మవారి అనుగ్రహం లభిస్తుంది.</p>
            </section>
            
            <section id="conclusion">
                <h2>ముగింపు</h2>
                <p>శ్రీ బాలాత్రిపురసుందరి అవతారం చిన్న వయస్సులో ఉన్నా అపార శక్తి, జ్ఞానం, కరుణకు ప్రతీక. పిల్లల విద్య, ఆరోగ్యం, భక్తుల ఐశ్వర్యం కోసం ఈ అమ్మవారిని పూజించడం ద్వారా అనేక అనుగ్రహాలు లభిస్తాయి.</p>
            </section>
            
            <section id="dashara-avatars">
                <h2>✨ దసరా నవరాత్రి అవతారములు – సంక్షిప్త పరిచయం ✨</h2>
                <ol>
                    <li><strong>బాలాత్రిపురసుందరి దేవి</strong> – చిన్న వయస్సులోనూ అపార శక్తిని కలిగిన అమ్మవారు. విద్యార్థులకు జ్ఞానం, పిల్లలకు ఆరోగ్యం, భక్తులకు శాంతి, ఐశ్వర్యం ప్రసాదిస్తుంది.</li>
                    <li><strong>గాయత్రి దేవి</strong> – పంచముఖి రూపిణి, వేదమాత. జ్ఞానం, భక్తి, బుద్ధిని ప్రసాదిస్తుంది.</li>
                    <li><strong>అన్నపూర్ణ దేవి</strong> – అన్నదాత, అక్షయ పాతర కలిగిన అమ్మవారు. భక్తులకు అన్నపూర్ణత, ఐశ్వర్యం, సంతృప్తి ప్రసాదిస్తుంది.</li>
                    <li><strong>త్రిపురమహిషి దేవి</strong> – త్రిపురాల పాలకురాలు, శక్తి స్వరూపిణి. దుష్టశక్తులను నాశనం చేసి భక్తులను రక్షిస్తుంది.</li>
                    <li><strong>మహేశ్వరి దేవి</strong> – శివుని శక్తి, యుద్ధ శక్తికి ప్రతీక. రక్షణ, ధైర్యం, శౌర్యాన్ని ప్రసాదిస్తుంది.</li>
                    <li><strong>లలితా కాశ్మీరు సందరేశి దేవి</strong> – లలిత త్రిపురసుందరి యొక్క ఒక ప్రత్యేక అవతారం. సౌందర్యం, కరుణ, ఐశ్వర్యం ప్రసాదిస్తుంది.</li>
                    <li><strong>మహాలక్ష్మి దేవి</strong> – ఐశ్వర్యం, సంపద, సౌఖ్యం ఇచ్చే శక్తి. భక్తుల గృహాలలో శ్రేయస్సు కలుగజేస్తుంది.</li>
                    <li><strong>దుర్గా దేవి</strong> – అశుభాన్ని తొలగించే అమ్మవారు. దుష్ట శక్తులపై విజయం సాధించడానికి ఆశ్రయించే దేవి.</li>
                    <li><strong>మహానిశి దేవి</strong> – అంధకారాన్ని తొలగించి, జ్ఞానప్రకాశాన్ని ఇచ్చే అవతారం. భక్తుల మానసిక బలం పెంచుతుంది.</li>
                    <li><strong>రాజరాజేశ్వరి దేవి</strong> – నవరాత్రుల ముగింపులో దర్శనమిచ్చే తల్లి. శక్తులన్నింటి ఆది రూపం. భక్తులకు శ్రేయస్సు, సంపూర్ణత ప్రసాదిస్తుంది.</li>
                </ol>
            </section>
            
            <section id="calendar">
                <h2>📅 దసరా నవరాత్రి అమ్మవారి అవతారములు – 2025 వివరాలు</h2>
                <div class="calendar">
                    <!-- Calendar items will be inserted by JavaScript -->
                </div>
                <p class="highlight">🌺 ఇలా ప్రతి రోజూ అమ్మవారు ఒక ప్రత్యేక అవతారంలో దర్శనమిస్తారు. శ్రీ బాలాత్రిపురసుందరి అవతారం</p>
            </section>
        </div>
        
        <footer>
            <p>శ్రీ బాలాత్రిపురసుందరి దేవి భక్తులందరికీ ఆశీర్వాదాలు ప్రసాదించాలి</p>
        </footer>
    </div>

    <script>
        // Calendar data
        const calendarData = [
            {
                date: "22-09-2025 | సోమవారం | ఆర్ధ్ర నక్షత్రం",
                avatar: "శ్రీ బాలాత్రిపురసుందరి దేవి",
                decoration: "గులాబీ పూవుల కిరీటం",
                color: "గులాబీ రంగు",
                offering: "పరవన్నం / డ్రై ఫ్రూట్స్"
            },
            {
                date: "23-09-2025 | మంగళవారం | పునర్వసు నక్షత్రం",
                avatar: "శ్రీ గాయత్రి దేవి",
                decoration: "అల్లం పూవుల కిరీటం",
                color: "పచ్చ రంగు",
                offering: "మినప గారెలు / లడ్డూలు"
            },
            {
                date: "24-09-2025 | బుధవారం | పుష్యమి నక్షత్రం",
                avatar: "శ్రీ అన్నపూర్ణ దేవి",
                decoration: "జాజిపూవుల కిరీటం",
                color: "ఎరుపు రంగు",
                offering: "పూర్ణాలు, రవ్వ లడ్డూలు"
            },
            {
                date: "25-09-2025 | గురువారం | ఆశ్లేష నక్షత్రం",
                avatar: "శ్రీ త్రిపురమహిషి దేవి",
                decoration: "కంకర పూవుల కిరీటం",
                color: "పసుపు రంగు",
                offering: "పూర్ణాలు, రవ్వ కాజాలు"
            },
            {
                date: "26-09-2025 | శుక్రవారం | మఘ నక్షత్రం",
                avatar: "శ్రీ మహేశ్వరి దేవి",
                decoration: "నందివర్ధన పూవుల కిరీటం",
                color: "నీలం రంగు",
                offering: "పూర్ణాలు, శెనగ పప్పు పాయసం"
            },
            {
                date: "27-09-2025 | శనివారం | పూర్వ ఫల్గుణి నక్షత్రం",
                avatar: "శ్రీ లలిత కాశ్మీరు సందరేశి దేవి",
                decoration: "బంగారు పూవుల కిరీటం",
                color: "తెలుపు రంగు",
                offering: "సీమయ్య పాయసం"
            },
            {
                date: "28-09-2025 | ఆదివారం | ఉత్తర ఫల్గుణి నక్షత్రం",
                avatar: "శ్రీ మహాలక్ష్మి దేవి",
                decoration: "రెడ్ రోజ్ పూవుల కిరీటం",
                color: "ఎరుపు రంగు",
                offering: "ముద్దపప్పు, జిలేబీలు"
            },
            {
                date: "29-09-2025 | సోమవారம் | హస్త నక్షత్రం",
                avatar: "శ్రీ దుర్గా దేవి",
                decoration: "నీలా పూవుల కిరీటం",
                color: "ఎరుపు రంగు",
                offering: "కచోరి / సమోసా"
            },
            {
                date: "30-09-2025 | మంగళవారం | చిత్త నక్షత్రం",
                avatar: "శ్రీ మహానిశి దేవి",
                decoration: "రేగుపూవుల కిరీటం",
                color: "నలుపు రంగు",
                offering: "రైస్, శెనగ కూర"
            },
            {
                date: "01-10-2025 | బుధవారం | స్వాతి నక్షత్రం",
                avatar: "శ్రీ రాజరాజేశ్వరి దేవి",
                decoration: "చెండ పూవుల కిరీటం",
                color: "పసుపు రంగు",
                offering: "పులిహోర, ముద్దపప్పు"
            }
        ];

        // Function to create calendar cards
        function createCalendar() {
            const calendarContainer = document.querySelector('.calendar');
            
            calendarData.forEach(day => {
                const dayCard = document.createElement('div');
                dayCard.className = 'day-card';
                
                dayCard.innerHTML = `
                    <div class="date">${day.date}</div>
                    <div class="avatar-name">${day.avatar}</div>
                    <div class="avatar-details">
                        <div class="detail-item">
                            <span class="detail-label">అలంకారం:</span> ${day.decoration}
                        </div>
                        <div class="detail-item">
                            <span class="detail-label">చీర వర్ణం:</span> ${day.color}
                        </div>
                        <div class="detail-item">
                            <span class="detail-label">నైవేద్యం:</span> ${day.offering}
                        </div>
                    </div>
                `;
                
                calendarContainer.appendChild(dayCard);
            });
        }

        // Function to add floating effect to sections on scroll
        function addScrollEffects() {
            const sections = document.querySelectorAll('section');
            
            const observer = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.style.opacity = '1';
                        entry.target.style.transform = 'translateY(0)';
                    }
                });
            }, { threshold: 0.1 });
            
            sections.forEach(section => {
                section.style.opacity = '0';
                section.style.transform = 'translateY(20px)';
                section.style.transition = 'opacity 0.5s ease, transform 0.5s ease';
                observer.observe(section);
            });
        }

        // Initialize when page loads
        document.addEventListener('DOMContentLoaded', function() {
            createCalendar();
            addScrollEffects();
            
            // Add click effect to mantra box
            const mantraBox = document.querySelector('.mantra-box');
            mantraBox.addEventListener('click', function() {
                this.style.transform = 'scale(1.05)';
                setTimeout(() => {
                    this.style.transform = 'scale(1)';
                }, 300);
            });
        });
    </script>
</body>
</html>
