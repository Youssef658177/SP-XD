 !DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yusuf Soliman - Software & Information Systems Engineer</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Inter Font for modern look -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc;
            color: #334155;
        }
        .container-wrapper {
            max-width: 1024px;
            margin: 0 auto;
            padding: 2rem;
        }
        .card {
            background-color: #ffffff;
            border-radius: 1.5rem;
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
            padding: 2.5rem;
            margin-bottom: 2rem;
            border: 1px solid #e2e8f0;
        }
        h1, h2, h3 {
            font-weight: 700;
            color: #1e293b;
            margin-bottom: 1rem;
        }
        h1 {
            font-size: 2.5rem;
            text-align: center;
            border-bottom: 2px solid #cbd5e1;
            padding-bottom: 1rem;
            margin-bottom: 2rem;
        }
        h2 {
            font-size: 2rem;
            display: flex;
            align-items: center;
            gap: 0.75rem;
        }
        .icon-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(60px, 1fr));
            gap: 1.5rem;
            justify-items: center;
            align-items: center;
        }
        .icon-grid img {
            width: 50px;
            height: 50px;
            transition: transform 0.2s ease-in-out;
        }
        .icon-grid img:hover {
            transform: scale(1.1);
        }
        .social-badges {
            display: flex;
            flex-wrap: wrap;
            gap: 0.75rem;
            justify-content: center;
        }
        .social-badges img {
            height: 30px;
        }
        .list-item-emoji {
            font-size: 1.25rem;
            margin-right: 0.5rem;
        }
        .main-gif {
            border-radius: 1rem;
            border: 4px solid #3b82f6;
            box-shadow: 0 15px 25px -5px rgba(0, 0, 0, 0.3), 0 8px 10px -6px rgba(0, 0, 0, 0.15);
        }
    </style>
</head>
<body>
    <div class="container-wrapper">
        <h1 class="text-blue-700">Yusuf Soliman: Software & Information Systems Engineer</h1>

        <!-- Greeting Section -->
        <div class="card text-center">
            <h2 class="justify-center text-gray-800">
                Hi there!
                <img src="https://user-images.githubusercontent.com/42378118/110234147-e3259600-7f4e-11eb-95be-0c4047144dea.gif" alt="Wave GIF" class="inline-block w-8 h-8">
            </h2>
            <p class="text-lg text-gray-700 mt-4">
                I'm Yusuf Soliman, a passionate Software and Information Systems Engineer. My journey in technology is driven by a deep fascination with building robust, efficient, and intelligent systems.
            </p>
            <div class="mt-8 flex justify-center">
                <!-- New Real GIF of Software Engineer -->
                <img src="https://media.giphy.com/media/h408T6Y5GfmXBKW62l/giphy.gif"
                     alt="Software Engineer Working in Front of Screens"
                     class="w-full max-w-2xl main-gif"
                     onerror="this.onerror=null; this.src='https://placehold.co/800x450/CCCCCC/333333?text=GIF+Load+Error';">
            </div>
        </div>

        <!-- Technologies and Tools Section -->
        <div class="card">
            <h2 class="text-gray-800">
                <span class="text-xl">🛠️</span> Technologies and Tools I Use:
            </h2>
            <div class="icon-grid mt-6">
                <!-- Frontend -->
                <a href="https://www.w3.org/html/" target="_blank" title="HTML5"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="HTML5"/> </a>
                <a href="https://www.w3schools.com/css/" target="_blank" title="CSS3"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="CSS3"/> </a>
                <a href="https://sass-lang.com" target="_blank" title="Sass"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/sass/sass-original.svg" alt="Sass"/> </a>
                <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" title="JavaScript"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript"/> </a>
                <a href="https://reactjs.org/" target="_blank" title="React"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="React"/> </a>
                <a href="https://webpack.js.org/" target="_blank" title="Webpack"> <img src="https://www.vectorlogo.zone/logos/js_webpack/js_webpack-icon.svg" alt="Webpack"/> </a>
                <a href="https://www.gatsbyjs.com/" target="_blank" title="Gatsby"> <img src="https://www.vectorlogo.zone/logos/gatsbyjs/gatsbyjs-icon.svg" alt="Gatsby"/> </a>

                <!-- Backend -->
                <a href="https://nodejs.org" target="_blank" title="Node.js"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="Node.js"/> </a>
                <a href="https://expressjs.com" target="_blank" title="Express.js"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" alt="Express.js"/> </a>
                <a href="https://www.mongodb.com/" target="_blank" title="MongoDB"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="MongoDB"/> </a>
                <a href="https://www.postman.com/" target="_blank" title="Postman"> <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="Postman"/> </a>

                <!-- DevOps/Cloud/Tools -->
                <a href="https://git-scm.com/" target="_blank" title="Git"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="Git"/> </a>
                <a href="https://azure.microsoft.com/en-us/" target="_blank" title="Microsoft Azure"> <img src="https://www.vectorlogo.zone/logos/microsoft_azure/microsoft_azure-icon.svg" alt="Azure"/> </a>
                <a href="https://cloud.google.com/" target="_blank" title="Google Cloud"> <img src="https://www.vectorlogo.zone/logos/google_cloud/google_cloud-icon.svg" alt="Google Cloud"/> </a>
                <a href="https://firebase.google.com/" target="_blank" title="Firebase"> <img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="Firebase"/> </a>
            </div>
        </div>
        <!-- Technologies and Tools Section -->
        <div class="card">
            <h2 class="text-gray-800">
                <span class="text-xl">🛠️</span> Technologies and Tools I Use:
            </h2>
            <div class="icon-grid mt-6">
                <!-- Frontend -->
                <a href="https://www.w3.org/html/" target="_blank" title="HTML5"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="HTML5"/> </a>
                <a href="https://www.w3schools.com/css/" target="_blank" title="CSS3"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="CSS3"/> </a>
                <a href="https://sass-lang.com" target="_blank" title="Sass"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/sass/sass-original.svg" alt="Sass"/> </a>
                <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" title="JavaScript"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript"/> </a>
                <a href="https://reactjs.org/" target="_blank" title="React"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="React"/> </a>
                <a href="https://webpack.js.org/" target="_blank" title="Webpack"> <img src="https://www.vectorlogo.zone/logos/js_webpack/js_webpack-icon.svg" alt="Webpack"/> </a>
                <a href="https://www.gatsbyjs.com/" target="_blank" title="Gatsby"> <img src="https://www.vectorlogo.zone/logos/gatsbyjs/gatsbyjs-icon.svg" alt="Gatsby"/> </a>

                <!-- Backend -->
                <a href="https://nodejs.org" target="_blank" title="Node.js"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="Node.js"/> </a>
                <a href="https://expressjs.com" target="_blank" title="Express.js"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" alt="Express.js"/> </a>
                <a href="https://www.mongodb.com/" target="_blank" title="MongoDB"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="MongoDB"/> </a>
                <a href="https://www.postman.com/" target="_blank" title="Postman"> <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="Postman"/> </a>

                <!-- DevOps/Cloud/Tools -->
                <a href="https://git-scm.com/" target="_blank" title="Git"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="Git"/> </a>
                <a href="https://azure.microsoft.com/en-us/" target="_blank" title="Microsoft Azure"> <img src="https://www.vectorlogo.zone/logos/microsoft_azure/microsoft_azure-icon.svg" alt="Azure"/> </a>
                <a href="https://cloud.google.com/" target="_blank" title="Google Cloud"> <img src="https://www.vectorlogo.zone/logos/google_cloud/google_cloud-icon.svg" alt="Google Cloud"/> </a>
                <a href="https://firebase.google.com/" target="_blank" title="Firebase"> <img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="Firebase"/> </a>
            </div>
        </div>

        <!-- About Me Section -->
        <div class="card">
            <h2 class="text-gray-800">
                <span class="text-xl">👨🏻‍💻</span> About Me:
            </h2>
            <ul class="list-none space-y-3 mt-6 text-lg text-gray-700">
                <li><span class="list-item-emoji">💡</span> As a Software and Information Systems Engineer, I specialize in designing and implementing efficient solutions using diverse programming paradigms.</li>
                <li><span class="list-item-emoji">📊</span> My expertise lies in optimizing algorithms and selecting appropriate data structures to solve complex computational problems.</li>
                <li><span class="list-item-emoji">🌐</span> I am continuously exploring advanced topics in distributed systems, cloud computing (Google Cloud & Microsoft Azure), and cutting-edge AI/ML methodologies, including Deep Learning.</li>
                <li><span class="list-item-emoji">🤝</span> Always eager to collaborate on innovative projects and contribute to open-source initiatives.</li>
                <li><span class="list-item-emoji">🚀</span> Passionate about turning theoretical concepts into practical, scalable software.</li>
                <li><span class="list-item-emoji">🧠</span> Life Philosophy: "Continuously learn, meticulously build, and boldly innovate."</li>
                <li><span class="list-item-emoji">✨</span> Fun fact: I enjoy participating in tech meetups and conferences to connect with fellow engineers and share knowledge.</li>
            </ul>
        </div>

        <!-- Let's Get Connected Section -->
        <div class="card">
            <h2 class="text-gray-800">
                <span class="text-xl">❤️</span> Let's Get Connected:
            </h2>
            <div class="social-badges mt-6">
                <a href="[Your LinkedIn Profile URL]" target="_blank" title="LinkedIn Profile">
                    <img src="https://img.shields.io/badge/-YusufSoliman-blue?style=flat-square&logo=Linkedin&logoColor=white" alt="LinkedIn Badge">
                </a>
                <a href="[Your Twitter Profile URL]" target="_blank" title="Twitter Profile">
                    <img src="https://img.shields.io/badge/-@YusufSoliman-1ca0f1?style=flat-square&labelColor=1ca0f1&logo=twitter&logoColor=white" alt="Twitter Badge">
                </a>
                <a href="[Your GitHub Profile URL]" target="_blank" title="GitHub Profile">
                    <img src="https://img.shields.io/badge/-YusufSoliman-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub Badge">
                </a>
                <a href="[Your Personal Website/Portfolio URL]" target="_blank" title="Personal Website">
                    <img src="https://img.shields.io/badge/-YusufSoliman.tech-blueviolet?style=flat-square&logo=appveyor&logoColor=white" alt="Website Badge">
                </a>
            </div>
        </div>

        <p class="text-center text-gray-600 text-sm mt-8">
            &copy; 2025 Yusuf Soliman. All rights reserved.
        </p>
    </div>
</body>
</html>

