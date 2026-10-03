<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Online Examination System</title>

<style>
*{
    box-sizing:border-box;
    margin:0;
    padding:0;
}

body{
    font-family:Arial,sans-serif;
    background:#eef3f8;
    color:#172033;
}

header{
    background:linear-gradient(135deg,#071d35,#1261a0);
    color:white;
    padding:17px 22px;
    display:flex;
    justify-content:space-between;
    align-items:center;
}

.logo{
    font-size:21px;
    font-weight:bold;
}

header button{
    padding:9px 14px;
    border:1px solid #ffffff55;
    border-radius:8px;
    background:#ffffff18;
    color:white;
    cursor:pointer;
}

.container{
    width:92%;
    max-width:1100px;
    margin:30px auto;
}

.card{
    background:white;
    padding:28px;
    border-radius:16px;
    box-shadow:0 5px 20px #00000012;
}

h1{
    margin-bottom:12px;
}

.subtitle{
    color:#667085;
    margin-bottom:22px;
}

input{
    width:100%;
    padding:13px;
    margin:8px 0 16px;
    border:1px solid #ccd5e0;
    border-radius:9px;
    font-size:15px;
}

.primary{
    width:100%;
    padding:13px;
    background:#1261a0;
    color:white;
    border:0;
    border-radius:9px;
    font-size:16px;
    font-weight:bold;
    cursor:pointer;
}

.primary:hover{
    background:#0b4f86;
}

.hidden{
    display:none !important;
}

.subject-grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(190px,1fr));
    gap:18px;
}

.subject{
    background:white;
    padding:25px;
    text-align:center;
    border-radius:15px;
    box-shadow:0 4px 15px #00000010;
    cursor:pointer;
    border:2px solid transparent;
    transition:.2s;
}

.subject:hover{
    transform:translateY(-4px);
    border-color:#1261a0;
}

.icon{
    font-size:40px;
    margin-bottom:10px;
}

.exam-bar{
    position:sticky;
    top:0;
    z-index:5;
    background:white;
    padding:15px;
    margin-bottom:20px;
    border-radius:12px;
    box-shadow:0 3px 15px #00000015;
}

.timer{
    color:#c62828;
    font-size:22px;
    font-weight:bold;
}

.progress-bg{
    height:9px;
    background:#e5eaf0;
    border-radius:10px;
    margin-top:12px;
}

.progress{
    width:0%;
    height:100%;
    background:#1261a0;
    border-radius:10px;
}

.question{
    background:white;
    padding:23px;
    margin-bottom:18px;
    border-radius:14px;
    box-shadow:0 4px 15px #0000000d;
}

.option{
    display:block;
    padding:12px;
    margin:8px 0;
    background:#f5f7fa;
    border:1px solid #d9e0e8;
    border-radius:8px;
    cursor:pointer;
}

.option input{
    width:auto;
    margin-right:8px;
}

.submit{
    padding:13px 22px;
    background:#c62828;
    color:white;
    border:0;
    border-radius:9px;
    font-weight:bold;
    cursor:pointer;
}

.success{
    text-align:center;
    padding:45px 20px;
}

.success-icon{
    font-size:60px;
    margin-bottom:15px;
}

table{
    width:100%;
    border-collapse:collapse;
}

th{
    background:#1261a0;
    color:white;
    padding:12px;
}

td{
    padding:10px;
    border-bottom:1px solid #ddd;
}

@media(max-width:600px){
    .container{
        width:95%;
        margin:15px auto;
    }

    .card{
        padding:20px;
    }

    .logo{
        font-size:17px;
    }
}
</style>
</head>

<body>

<header>
    <div class="logo">
        Online Examination System
    </div>
    <button onclick="showAdminLogin()">
        🔐 Admin
    </button>
</header>

<!-- STUDENT LOGIN -->
<section id="loginPage" class="container">
    <div class="card">
        <h1>🎓 Student Login</h1>
        <p class="subtitle">Enter your information to start the examination.</p>
        
        <label>Student Name</label>
        <input id="studentName" type="text" placeholder="Enter your full name">

        <label>Student ID</label>
        <input id="studentId" type="text" placeholder="Enter your student ID">

        <button class="primary" onclick="studentLogin()">Start Examination</button>
    </div>
</section>

<!-- SUBJECT PAGE -->
<section id="subjectPage" class="container hidden">
    <div class="card">
        <h1>📚 Choose Subject</h1>
        <p class="subtitle">Grade 12 Hard / Entrance Examination</p>
        <p>Student: <strong id="displayStudent"></strong></p>
    </div>
    <br>
    <div class="subject-grid">
        <div class="subject" onclick="startExam('Mathematics')">
            <div class="icon">📐</div>
            <h2>Mathematics</h2>
            <p>20 Questions</p>
        </div>
        <div class="subject" onclick="startExam('Physics')">
            <div class="icon">⚛️</div>
            <h2>Physics</h2>
            <p>20 Questions</p>
        </div>
        <div class="subject" onclick="startExam('Chemistry')">
            <div class="icon">🧪</div>
            <h2>Chemistry</h2>
            <p>20 Questions</p>
        </div>
        <div class="subject" onclick="startExam('Biology')">
            <div class="icon">🧬</div>
            <h2>Biology</h2>
            <p>20 Questions</p>
        </div>
        <div class="subject" onclick="startExam('English')">
            <div class="icon">🇬🇧</div>
            <h2>English</h2>
            <p>20 Questions</p>
        </div>
        <div class="subject" onclick="startExam('Aptitude')">
            <div class="icon">🧠</div>
            <h2>Aptitude</h2>
            <p>20 Questions</p>
        </div>
    </div>
</section>

<!-- EXAM PAGE -->
<section id="examPage" class="container hidden">
    <div class="exam-bar">
        <div style="display:flex; justify-content:space-between; flex-wrap:wrap; gap:10px;">
            <strong id="examSubject">Examination</strong>
            <span class="timer">⏱️ <span id="timer">30:00</span></span>
        </div>
        <div class="progress-bg">
            <div id="progress" class="progress"></div>
        </div>
    </div>

    <div id="questionsContainer"></div>

    <button class="submit" onclick="submitExam()">Submit Examination</button>
</section>

<!-- SUBMITTED PAGE -->
<section id="submittedPage" class="container hidden">
    <div class="card success">
        <div class="success-icon">✅</div>
        <h1>Exam Submitted Successfully</h1>
        <p class="subtitle">Your examination has been submitted.</p>
        <p>Your score is not displayed. The administrator will review your result.</p>
        <br>
        <button class="primary" onclick="location.reload()">Finish</button>
    </div>
</section>

<!-- ADMIN LOGIN -->
<section id="adminLoginPage" class="container hidden">
    <div class="card">
        <h1>🔐 Admin Login</h1>
        <p class="subtitle">Administrator access</p>
        
        <label>Username</label>
        <input id="adminUsername" type="text" placeholder="Username">

        <label>Password</label>
        <input id="adminPassword" type="password" placeholder="Password">

        <button class="primary" onclick="adminLogin()">Login</button>
        <br><br>
        <button onclick="showStudentLogin()" style="border:0; background:none; color:#1261a0; cursor:pointer;">
            ← Student Login
        </button>
    </div>
</section>

<!-- ADMIN DASHBOARD -->
<section id="adminPage" class="container hidden">
    <div class="card">
        <h1>📊 Admin Dashboard</h1>
        <p class="subtitle">Student examination results</p>
        
        <div id="resultsContainer"></div>
        <br>
        <button onclick="clearResults()" style="padding:12px 18px; background:#c62828; color:white; border:0; border-radius:8px; cursor:pointer;">
            Delete All Results
        </button>
        <br><br>
        <button onclick="showStudentLogin()" style="padding:10px 15px; border:0; border-radius:8px; cursor:pointer;">
            Logout
        </button>
    </div>
</section>

<script>
let currentStudent = "";
let currentStudentId = "";
let currentSubject = "";
let currentQuestions = [];
let timerInterval;
let timeLeft = 30 * 60;

const questionBank = {
    Mathematics: [
        { question: "If 2x² - 5x - 3 = 0, what is the product of its roots?", options: ["-3/2", "3/2", "-5/2", "5/2"], answer: 0 },
        { question: "If log₂(x) = 5, what is x?", options: ["10", "16", "25", "32"], answer: 3 },
        { question: "Find the derivative of y = x³ - 4x² + 7x.", options: ["3x² - 8x + 7", "3x² - 4x + 7", "x² - 8x + 7", "3x - 8"], answer: 0 },
        { question: "Evaluate lim(x→2) (x² - 4)/(x - 2).", options: ["2", "4", "6", "8"], answer: 1 },
        { question: "The 20th term of 3, 7, 11, 15, ... is:", options: ["76", "79", "80", "83"], answer: 0 },
        { question: "The sum of the first 20 terms of 3, 7, 11, 15, ... is:", options: ["760", "800", "820", "840"], answer: 2 },
        { question: "If sin θ = 3/5 and θ is acute, cos θ is:", options: ["3/5", "4/5", "5/3", "1/5"], answer: 1 },
        { question: "Solve: 3ˣ = 81.", options: ["2", "3", "4", "5"], answer: 2 },
        { question: "What is the determinant of [[2,3],[1,4]]?", options: ["5", "6", "8", "11"], answer: 0 },
        { question: "If f(x) = 2x + 3, find f(5).", options: ["10", "11", "13", "15"], answer: 2 },
        { question: "What is ∫2x dx?", options: ["x² + C", "2x² + C", "x + C", "x²/2 + C"], answer: 0 },
        { question: "If x + 1/x = 5, find x² + 1/x².", options: ["21", "23", "25", "27"], answer: 1 },
        { question: "A fair die is rolled once. Probability of getting a prime number is:", options: ["1/3", "1/2", "2/3", "5/6"], answer: 1 },
        { question: "If 5x - 7 = 18, find x.", options: ["4", "5", "6", "7"], answer: 1 },
        { question: "The vertex of y = x² - 6x + 5 is:", options: ["(2,-1)", "(3,-4)", "(3,4)", "(6,5)"], answer: 1 },
        { question: "If 2ˣ⁺¹ = 16, then x is:", options: ["2", "3", "4", "5"], answer: 1 },
        { question: "Coefficient of x² in (x + 2)⁴ is:", options: ["12", "16", "24", "32"], answer: 2 },
        { question: "If vectors a=(2,3) and b=(4,-1), then a·b equals:", options: ["5", "8", "11", "13"], answer: 0 },
        { question: "Solve |x - 3| = 5.", options: ["x=8 only", "x=-2 only", "x=8 or -2", "x=2 or -8"], answer: 2 },
        { question: "If the radius of a circle is doubled, its area becomes:", options: ["2 times", "3 times", "4 times", "8 times"], answer: 2 }
    ],
    Physics: [
        { question: "A car starts from rest and accelerates at 4 m/s² for 5 s. Final velocity?", options: ["10 m/s", "15 m/s", "20 m/s", "25 m/s"], answer: 2 },
        { question: "For the same car, distance travelled in 5 s is:", options: ["25 m", "40 m", "50 m", "100 m"], answer: 2 },
        { question: "Newton's first law is also called the law of:", options: ["Acceleration", "Inertia", "Momentum", "Gravitation"], answer: 1 },
        { question: "A 10 kg object is acted on by a net force of 50 N. Acceleration?", options: ["2 m/s²", "5 m/s²", "10 m/s²", "500 m/s²"], answer: 1 },
        { question: "Work done by a force is zero when force and displacement are:", options: ["Parallel", "Opposite", "Perpendicular", "Equal"], answer: 2 },
        { question: "SI unit of power is:", options: ["Joule", "Newton", "Watt", "Pascal"], answer: 2 },
        { question: "Momentum is equal to:", options: ["mv", "ma", "m/v", "F/t"], answer: 0 },
        { question: "If velocity doubles, kinetic energy becomes:", options: ["2 times", "3 times", "4 times", "8 times"], answer: 2 },
        { question: "Acceleration due to gravity near Earth's surface is approximately:", options: ["4.9 m/s²", "9.8 m/s²", "19.6 m/s²", "98 m/s²"], answer: 1 },
        { question: "A wave has frequency 50 Hz and wavelength 2 m. Speed?", options: ["25 m/s", "50 m/s", "100 m/s", "150 m/s"], answer: 2 },
        { question: "Ohm's law is:", options: ["V=IR", "P=IV²", "F=ma²", "Q=mc"], answer: 0 },
        { question: "A 12 V battery is connected to a 4 Ω resistor. Current?", options: ["2 A", "3 A", "4 A", "48 A"], answer: 1 },
        { question: "In a series circuit, current through each resistor is:", options: ["Different", "The same", "Always zero", "Infinite"], answer: 1 },
        { question: "Unit of electrical resistance is:", options: ["Volt", "Ampere", "Ohm", "Coulomb"], answer: 2 },
        { question: "Energy of a photon is given by:", options: ["E=mc²", "E=hf", "E=mv", "E=IR"], answer: 1 },
        { question: "Which particle has a negative electric charge?", options: ["Proton", "Neutron", "Electron", "Photon"], answer: 2 },
        { question: "A transformer works mainly with:", options: ["DC only", "AC", "Static charge", "Mechanical energy only"], answer: 1 },
        { question: "Centripetal force is directed:", options: ["Outward", "Tangentially", "Toward the centre", "Upward"], answer: 2 },
        { question: "Unit of frequency is:", options: ["Newton", "Hertz", "Joule", "Tesla"], answer: 1 },
        { question: "When an object is thrown vertically upward, velocity at maximum height is:", options: ["Maximum", "Zero", "9.8 m/s", "Infinite"], answer: 1 }
    ],
    Chemistry: [
        { question: "Atomic number represents the number of:", options: ["Neutrons", "Protons", "Electrons + neutrons", "Nucleons"], answer: 1 },
        { question: "Which quantum number determines the main energy level?", options: ["n", "l", "m", "s"], answer: 0 },
        { question: "pH of a neutral solution at 25°C is:", options: ["0", "5", "7", "14"], answer: 2 },
        { question: "Which bond involves sharing of electrons?", options: ["Ionic", "Covalent", "Metallic only", "Hydrogen only"], answer: 1 },
        { question: "Oxidation is generally:", options: ["Gain of electrons", "Loss of electrons", "Gain of neutrons", "Loss of protons"], answer: 1 },
        { question: "A reducing agent is:", options: ["Reduced", "Oxidized", "Never reacted", "Only gains protons"], answer: 1 },
        { question: "Avogadro's number is approximately:", options: ["6.02×10²³", "3.00×10⁸", "9.81", "1.60×10⁻¹⁹"], answer: 0 },
        { question: "Acid + carbonate produces which gas?", options: ["O₂", "H₂", "CO₂", "N₂"], answer: 2 },
        { question: "Molar mass of H₂O is approximately:", options: ["16 g/mol", "18 g/mol", "20 g/mol", "22 g/mol"], answer: 1 },
        { question: "A catalyst increases reaction rate by:", options: ["Increasing activation energy", "Decreasing activation energy", "Increasing product mass", "Changing equilibrium constant"], answer: 1 },
        { question: "Most electronegative element is:", options: ["Oxygen", "Chlorine", "Fluorine", "Nitrogen"], answer: 2 },
        { question: "Conversion of liquid into gas is:", options: ["Condensation", "Evaporation", "Freezing", "Sublimation"], answer: 1 },
        { question: "Which is a strong acid?", options: ["CH₃COOH", "HCl", "NH₃", "H₂O"], answer: 1 },
        { question: "Oxidation number of oxygen in most compounds is:", options: ["+2", "-2", "0", "+1"], answer: 1 },
        { question: "Which particle determines chemical identity of an element?", options: ["Neutron", "Proton", "Electron", "Photon"], answer: 1 },
        { question: "At constant temperature, increasing pressure on a gas causes volume to:", options: ["Increase", "Decrease", "Become infinite", "Always become zero"], answer: 1 },
        { question: "Functional group present in alcohols:", options: ["-COOH", "-OH", "-CHO", "-NH₂"], answer: 1 },
        { question: "Complete combustion of a hydrocarbon produces:", options: ["CO and H₂", "CO₂ and H₂O", "C and H₂", "O₂ and H₂"], answer: 1 },
        { question: "Electrolysis uses electrical energy to drive a:", options: ["Spontaneous reaction", "Non-spontaneous reaction", "Nuclear reaction", "Gravitational reaction"], answer: 1 },
        { question: "Increasing temperature usually increases reaction rate because particles:", options: ["Move more slowly", "Have greater kinetic energy", "Disappear", "Lose all energy"], answer: 1 }
    ],
    Biology: [
        { question: "Organelle mainly responsible for ATP production:", options: ["Nucleus", "Mitochondrion", "Ribosome", "Golgi apparatus"], answer: 1 },
        { question: "DNA replication occurs during:", options: ["G1", "S", "G2", "M"], answer: 1 },
        { question: "Basic unit of heredity is:", options: ["Chromosome", "Gene", "Cell", "Protein"], answer: 1 },
        { question: "Which molecule carries genetic information?", options: ["ATP", "DNA", "Glucose", "Lipid"], answer: 1 },
        { question: "Transcription produces:", options: ["DNA from RNA", "RNA from DNA", "Protein from RNA", "ATP from glucose"], answer: 1 },
        { question: "Translation occurs mainly at the:", options: ["Nucleus", "Ribosome", "Mitochondrion", "Lysosome"], answer: 1 },
        { question: "Which cells produce antibodies?", options: ["Red blood cells", "B lymphocytes", "Platelets", "Neurons"], answer: 1 },
        { question: "Functional unit of kidney is:", options: ["Neuron", "Nephron", "Alveolus", "Villus"], answer: 1 },
        { question: "Photosynthesis mainly occurs in:", options: ["Mitochondria", "Chloroplasts", "Ribosomes", "Nuclei"], answer: 1 },
        { question: "Pigment that absorbs light for photosynthesis:", options: ["Hemoglobin", "Chlorophyll", "Melanin", "Keratin"], answer: 1 },
        { question: "Insulin is produced by:", options: ["Liver", "Pancreas", "Kidney", "Thyroid"], answer: 1 },
        { question: "Process producing genetically different gametes:", options: ["Mitosis", "Meiosis", "Binary fission", "Budding"], answer: 1 },
        { question: "Xylem mainly transports:", options: ["Sugars", "Water and minerals", "Proteins", "Hormones"], answer: 1 },
        { question: "Phloem mainly transports:", options: ["Water only", "Minerals", "Organic food substances", "Oxygen"], answer: 2 },
        { question: "Natural selection is strongly associated with:", options: ["Newton", "Darwin", "Einstein", "Mendel"], answer: 1 },
        { question: "Main site of gas exchange in lungs:", options: ["Trachea", "Alveoli", "Bronchi", "Diaphragm"], answer: 1 },
        { question: "Structure controlling entry and exit of substances from cell:", options: ["Cell wall", "Cell membrane", "Nucleus", "Ribosome"], answer: 1 },
        { question: "Mendel studied inheritance mainly using:", options: ["Fruit flies", "Pea plants", "Bacteria", "Mice"], answer: 1 },
        { question: "Homeostasis means:", options: ["Growth only", "Maintenance of stable internal conditions", "Cell division only", "Digestion only"], answer: 1 },
        { question: "Hormone associated with fight-or-flight response:", options: ["Insulin", "Adrenaline", "Estrogen", "Melatonin"], answer: 1 }
    ],
    English: [
        { question: "Choose the correct sentence:", options: ["She have finished her work.", "She has finished her work.", "She having finished her work.", "She finish her work."], answer: 1 },
        { question: "If I had studied harder, I _____ the exam.", options: ["pass", "will pass", "would have passed", "would pass"], answer: 2 },
        { question: "Opposite of 'ancient' is:", options: ["Old", "Modern", "Historic", "Past"], answer: 1 },
        { question: "Passive form of 'They built the house.'", options: ["The house built them.", "The house was built by them.", "The house is building.", "The house has build."], answer: 1 },
        { question: "Which word is an adjective?", options: ["Quickly", "Beauty", "Beautiful", "Beautify"], answer: 2 },
        { question: "He has lived here _____ 2019.", options: ["for", "since", "during", "from"], answer: 1 },
        { question: "She is interested _____ science.", options: ["on", "at", "in", "for"], answer: 2 },
        { question: "Synonym of 'rapid' is:", options: ["Slow", "Fast", "Weak", "Late"], answer: 1 },
        { question: "By the time we arrived, the movie _____.", options: ["starts", "started", "had started", "has started"], answer: 2 },
        { question: "Reported speech: He said, 'I am tired.'", options: ["He said that I am tired.", "He said that he was tired.", "He says he tired.", "He said he is tired yesterday."], answer: 1 },
        { question: "Neither Ali nor his friends _____ ready.", options: ["is", "was", "are", "be"], answer: 2 },
        { question: "The word 'although' introduces:", options: ["Reason", "Contrast", "Purpose", "Result"], answer: 1 },
        { question: "If it rains tomorrow, we _____ at home.", options: ["stay", "will stay", "would stay", "stayed"], answer: 1 },
        { question: "He is _____ honest man.", options: ["a", "an", "the", "no article"], answer: 1 },
        { question: "Choose the correct sentence:", options: ["I have never seen such a beautiful place.", "I never have saw such beautiful place.", "I has never seen a place.", "I never seeing such place."], answer: 0 },
        { question: "Meaning of 'reluctant':", options: ["Eager", "Unwilling", "Excited", "Certain"], answer: 1 },
        { question: "She speaks English _____ than her brother.", options: ["good", "best", "better", "well"], answer: 2 },
        { question: "Plural of 'criterion' is:", options: ["Criterions", "Criteria", "Criteriones", "Criterias"], answer: 1 },
        { question: "If I were you, I _____ apologize.", options: ["will", "would", "can", "shall"], answer: 1 },
        { question: "Closest meaning to 'essential':", options: ["Optional", "Necessary", "Rare", "Simple"], answer: 1 }
    ],
    Aptitude: [
        { question: "Find the next number: 2, 6, 12, 20, 30, ?", options: ["36", "40", "42", "44"], answer: 2 },
        { question: "Find the next number: 3, 9, 27, 81, ?", options: ["162", "243", "324", "729"], answer: 1 },
        { question: "If CAT is coded as DBU, how is DOG coded?", options: ["EPH", "EOH", "DPH", "FPH"], answer: 0 },
        { question: "If TODAY is coded as UPEBZ, NIGHT is coded as:", options: ["OJHIU", "OJHGU", "NJHIU", "OJGIU"], answer: 0 },
        { question: "A man walks 5 km north then 5 km east. Distance from starting point?", options: ["5 km", "10 km", "5√2 km", "25 km"], answer: 2 },
        { question: "If all roses are flowers, which conclusion is definitely true?", options: ["All flowers are roses.", "All roses are flowers.", "No roses are flowers.", "Some flowers are not roses."], answer: 1 },
        { question: "A clock shows 3:00. Angle between hands?", options: ["30°", "60°", "90°", "180°"], answer: 2 },
        { question: "5 workers complete a job in 12 days. 10 workers need:", options: ["3 days", "6 days", "12 days", "24 days"], answer: 1 },
        { question: "Father is 40 and son is 10. After how many years will father be twice son's age?", options: ["10", "15", "20", "25"], answer: 2 },
        { question: "Find the odd one out:", options: ["Triangle", "Square", "Circle", "Rectangle"], answer: 2 },
        { question: "4 pencils cost 20 birr. 10 pencils cost:", options: ["40", "45", "50", "60"], answer: 2 },
        { question: "Book : Reading :: Fork : ?", options: ["Writing", "Eating", "Walking", "Sleeping"], answer: 1 },
        { question: "A train travels 120 km in 2 hours. Average speed?", options: ["40 km/h", "50 km/h", "60 km/h", "80 km/h"], answer: 2 },
        { question: "Complete: A, C, F, J, O, ?", options: ["T", "U", "V", "W"], answer: 1 },
        { question: "If yesterday was Monday, what day will it be three days from today?", options: ["Wednesday", "Thursday", "Friday", "Saturday"], answer: 2 },
        { question: "A bag has 3 red and 2 blue balls. Probability of red:", options: ["2/5", "3/5", "1/2", "3/2"], answer: 1 },
        { question: "Which number does not belong? 4, 9, 16, 25, 36, 50", options: ["16", "25", "36", "50"], answer: 3 },
        { question: "If SOME = 1234 and MORE = 5234, then M =", options: ["1", "2", "3", "5"], answer: 3 },
        { question: "A student scores 70, 80, 90. What score gives an average of 85 after four tests?", options: ["90", "95", "100", "105"], answer: 2 },
        { question: "A number is increased by 20% and becomes 120. Original number?", options: ["90", "100", "110", "115"], answer: 1 }
    ]
};

function hideAll(){
    document.querySelectorAll("section").forEach(section => {
        section.classList.add("hidden");
    });
}

function studentLogin(){
    const name = document.getElementById("studentName").value.trim();
    const id = document.getElementById("studentId").value.trim();

    if(!name || !id){
        alert("Please enter Student Name and Student ID.");
        return;
    }

    currentStudent = name;
    currentStudentId = id;

    document.getElementById("displayStudent").textContent = name + " (" + id + ")";
    hideAll();
    document.getElementById("subjectPage").classList.remove("hidden");
}

function showStudentLogin(){
    clearInterval(timerInterval);
    hideAll();
    document.getElementById("loginPage").classList.remove("hidden");
}

function showAdminLogin(){
    hideAll();
    document.getElementById("adminLoginPage").classList.remove("hidden");
}

function startExam(subject){
    currentSubject = subject;
    currentQuestions = questionBank[subject];

    if(!currentQuestions || currentQuestions.length === 0){
        alert("No questions found for " + subject);
        return;
    }

    document.getElementById("examSubject").textContent = subject + " Examination";
    hideAll();
    document.getElementById("examPage").classList.remove("hidden");

    renderQuestions();
    startTimer();
}

function renderQuestions(){
    const container = document.getElementById("questionsContainer");
    container.innerHTML = "";

    currentQuestions.forEach((q, index) => {
        const div = document.createElement("div");
        div.className = "question";

        let html = `<h3>${index + 1}. ${q.question}</h3>`;

        q.options.forEach((option, optIndex) => {
            html += `
                <label class="option">
                    <input type="radio" name="question${index}" value="${optIndex}" onchange="updateProgress()">
                    ${option}
                </label>
            `;
        });

        div.innerHTML = html;
        container.appendChild(div);
    });
}

function updateProgress(){
    let answered = 0;
    currentQuestions.forEach((q, index) => {
        const selected = document.querySelector(`input[name="question${index}"]:checked`);
        if(selected){
            answered++;
        }
    });

    const percent = (answered / currentQuestions.length) * 100;
    document.getElementById("progress").style.width = percent + "%";
}

function startTimer(){
    clearInterval(timerInterval);
    timeLeft = 30 * 60;
    updateTimer();

    timerInterval = setInterval(() => {
        timeLeft--;
        updateTimer();

        if(timeLeft <= 0){
            clearInterval(timerInterval);
            alert("Time is over. Your exam will be submitted.");
            submitExam();
        }
    }, 1000);
}

function updateTimer(){
    const minutes = Math.floor(timeLeft / 60);
    const seconds = timeLeft % 60;

    document.getElementById("timer").textContent =
        String(minutes).padStart(2, "0") + ":" + String(seconds).padStart(2, "0");
}

function submitExam(){
    if(!confirm("Are you sure you want to submit?")){
        return;
    }

    clearInterval(timerInterval);

    let score = 0;
    currentQuestions.forEach((q, index) => {
        const selected = document.querySelector(`input[name="question${index}"]:checked`);
        if(selected && Number(selected.value) === q.answer){
            score++;
        }
    });

    const percentage = (score / currentQuestions.length) * 100;

    const result = {
        studentName: currentStudent,
        studentId: currentStudentId,
        subject: currentSubject,
        score: score,
        total: currentQuestions.length,
        percentage: percentage.toFixed(1),
        date: new Date().toLocaleString()
    };

    const results = JSON.parse(localStorage.getItem("examResults") || "[]");
    results.push(result);
    localStorage.setItem("examResults", JSON.stringify(results));

    hideAll();
    document.getElementById("submittedPage").classList.remove("hidden");
}

function adminLogin(){
    const username = document.getElementById("adminUsername").value;
    const password = document.getElementById("adminPassword").value;

    if(username === "admin" && password === "12345"){
        hideAll();
        document.getElementById("adminPage").classList.remove("hidden");
        loadResults();
    } else {
        alert("Wrong username or password.");
    }
}

function loadResults(){
    const results = JSON.parse(localStorage.getItem("examResults") || "[]");
    const container = document.getElementById("resultsContainer");

    if(results.length === 0){
        container.innerHTML = "<p>No results yet.</p>";
        return;
    }

    let html = `
    <div style="overflow-x:auto">
    <table>
    <tr>
        <th>Student</th>
        <th>ID</th>
        <th>Subject</th>
        <th>Score</th>
        <th>Percentage</th>
        <th>Date</th>
    </tr>
    `;

    results.forEach(result => {
        html += `
        <tr>
            <td>${result.studentName}</td>
            <td>${result.studentId}</td>
            <td>${result.subject}</td>
            <td>${result.score}/${result.total}</td>
            <td>${result.percentage}%</td>
            <td>${result.date}</td>
        </tr>
        `;
    });

    html += `</table></div>`;
    container.innerHTML = html;
}

function clearResults(){
    if(!confirm("Delete ALL results?")){
        return;
    }
    localStorage.removeItem("examResults");
    loadResults();
    alert("All results deleted.");
}
</script>

</body>
</html>
