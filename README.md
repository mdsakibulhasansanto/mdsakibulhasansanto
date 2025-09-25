<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sakibul Hasan Santo - Portfolio</title>
<style>
    body {
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        background-color: #0f111a;
        color: #fff;
        margin: 0;
        padding: 0;
    }
    header {
        text-align: center;
        padding: 50px 20px;
        background: linear-gradient(90deg, #00c6ff, #0072ff);
    }
    header h1 {
        font-size: 3em;
        margin: 0;
    }
    header code {
        display: block;
        margin-top: 10px;
        font-size: 1.2em;
        background-color: #222;
        padding: 10px;
        border-radius: 5px;
        cursor: pointer;
    }
    section {
        padding: 50px 20px;
        max-width: 900px;
        margin: auto;
    }
    .animated-text {
        font-size: 1.5em;
        margin: 10px 0;
        color: #00ffd5;
        overflow: hidden;
        white-space: nowrap;
        border-right: 0.15em solid #00ffd5;
        animation: typing 4s steps(40, end), blink-caret 0.75s step-end infinite;
    }
    @keyframes typing {
        from { width: 0; }
        to { width: 100%; }
    }
    @keyframes blink-caret {
        50% { border-color: transparent; }
    }
    h2 {
        border-bottom: 2px solid #00ffd5;
        padding-bottom: 10px;
        margin-bottom: 20px;
    }
    .highlight, .focus, .next-tech, .connect, .tools {
        margin-bottom: 30px;
    }
    a {
        color: #00ffd5;
        text-decoration: none;
        margin-right: 15px;
    }
    .badge {
        display: inline-block;
        margin: 5px;
    }
    .badge img {
        height: 30px;
    }
</style>
</head>
<body>

<header>
    <h1>Sakibul Hasan Santo</h1>
    <code onclick="copyText(this)">print('Sakibul Hasan Santo')</code>
    <code onclick="copyText(this)">fmt.Println("Sakibul Hasan Santo")</code>
</header>

<section>
    <h2>About Me</h2>
    <p>I graduated from <strong>Moulvibazar Polytechnic Institute</strong> with a degree in <strong>Computer Science & Technology (2021-22)</strong>.  
       I am a passionate software developer focusing on Flutter and Golang development.</p>
</section>

<section>
    <h2>Tech Animations</h2>
    <div class="animated-text">Software Developer at Sparktech Agency</div>
    <div class="animated-text">📱 Software Engineering is My Profession</div>
    <div class="animated-text">🚀 Flutter-Golang</div>
</section>

<section class="highlight">
    <h2>Quick Highlights & Current Focus</h2>
    <ul>
        <li>Developing cross-platform mobile apps using Flutter</li>
        <li>Backend API development using Golang (Gin, Fiber)</li>
        <li>Database & RESTful API Integration</li>
        <li>Continuous learning & improving coding skills</li>
    </ul>
</section>

<section class="next-tech">
    <h2>Next Technology</h2>
    <ul>
        <li>Microservices Architecture</li>
        <li>Cloud Deployment (AWS, GCP)</li>
        <li>Real-time Chat Apps</li>
        <li>AI & ML Integrations</li>
    </ul>
</section>

<section class="connect">
    <h2>Connect With Me</h2>
    <a href="https://facebook.com/SakibulHasanSanto" target="_blank">Facebook</a>
    <a href="https://instagram.com/SakibulHasanSanto" target="_blank">Instagram</a>
    <a href="mailto:sakibulsanto@example.com">Email</a>
</section>

<section class="tools">
    <h2>Languages & Tools</h2>
    <div class="badge"><img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white"></div>
    <div class="badge"><img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white"></div>
    <div class="badge"><img src="https://img.shields.io/badge/Golang-00ADD8?style=for-the-badge&logo=go&logoColor=white"></div>
    <div class="badge"><img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"></div>
    <div class="badge"><img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"></div>
</section>

<section class="github-stats">
    <h2>GitHub Stats</h2>
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=SakibulHasanSanto&layout=compact&theme=tokyonight" alt="Top Languages">
    <img src="https://github-readme-stats.vercel.app/api?username=SakibulHasanSanto&show_icons=true&theme=tokyonight" alt="GitHub Stats">
</section>

<script>
function copyText(el) {
    navigator.clipboard.writeText(el.textContent).then(() => {
        alert('Copied to clipboard!');
    });
}
</script>

</body>
</html>
