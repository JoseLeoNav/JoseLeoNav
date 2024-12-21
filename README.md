<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JoseLeoNav</title>

    <script src="https://cdn.tailwindcss.com"></script>
    <style>

        @keyframes typing {
            0% {
                width: 0;
            }
            100% {
                width: 100%;
            }
        }

        @keyframes cursor-blink {
            0% {
                border-right-color: #fff;
            }
            100% {
                border-right-color: transparent;
            }
        }

        .typing-animation {
            display: inline-block;
            overflow: hidden;
            white-space: nowrap;
            border-right: 3px solid #fff;
            width: 0;
            animation: typing 3s steps(30) 1s forwards, cursor-blink 0.75s step-end infinite;
        }

        .typing-complete {
            animation: none;
            border-right: none;
        }

        .typing-animation-completed {
            animation: typing 3s steps(30) 1s forwards, cursor-blink 0.75s step-end infinite, hold 3s forwards;
        }

        @keyframes hold {
            0% {
                width: 100%;
            }
            100% {
                width: 100%;
            }
        }

        /* Nuevo estilo para los primeros textos */
        .large-text {
            font-size: 6rem; /* tamaño aumentado para h1 */
            font-family: 'Arial', sans-serif; /* fuente para h1 */
            color: #4c2882; /* color personalizado para h1 */
        }

        .larger-text {
            font-size: 4rem; /* tamaño aumentado para h2 */
            font-family: 'Arial', sans-serif; /* fuente para h2 */
            color: #4c2882; /* color personalizado para h2 */
        }

    </style>
</head>
<body class="text-white font-sans flex items-center justify-center min-h-screen p-8">

    <div class="text-center">

        <h1 class="text-4xl font-bold mb-4 large-text">
            <span class="typing-animation text-xl">Hi I'm Jose</span>
        </h1>
        <h2 class="text-3xl mb-4 larger-text">
            <span class="typing-animation text-lg">I'm Junior Web Developer</span>
        </h2>

        <p class="text-lg mb-6 max-w-3xl mx-auto">I’m a young web developer with an unstoppable enthusiasm for creating great things 🚀. My passion for web development shines through in crafting attractive and functional websites, where front-end development sparks my artistic side 🎨, while back-end development allows me to build flawless logic behind the scenes 🔧.</p>

        <p class="text-lg mb-6 max-w-3xl mx-auto">I’m always on the lookout for new technologies that help me create more meaningful and distinctive experiences for users 🌍. I love challenges that help me grow and improve as a developer, with the goal of always delivering the best possible results 💡. Follow my profile to check out my projects! 🙌</p>

        <h3 class="text-xl font-semibold mb-2">🌐 Socials:</h3>
        <a href="https://www.linkedin.com/in/joseleonnalvarte">
            <img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white" alt="LinkedIn Badge" class="mb-4"/>
        </a>

        <h3 class="text-xl font-semibold mb-2">💻 Tech Stack:</h3>
        <div class="flex space-x-2 mb-4 justify-center">
            <img src="https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3 Badge" />
            <img src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E" alt="JavaScript Badge" />
            <img src="https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL Badge" />
            <img src="https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript Badge" />
            <img src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" alt="React Badge" />
            <img src="https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white" alt="Spring Badge" />
        </div>

        <h3 class="text-xl font-semibold mb-2">📊 GitHub Stats:</h3>
        <p><img src="https://github-readme-streak-stats.herokuapp.com/?user=JoseLeoNav&theme=radical&hide_border=false" alt="GitHub Streak" class="mb-4" /></p>
        <p><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=JoseLeoNav&theme=radical&hide_border=false&include_all_commits=false&count_private=false&layout=compact" alt="GitHub Top Languages" class="mb-4" /></p>

        <p>
            <a href="https://visitcount.itsvg.in">
                <img src="https://visitcount.itsvg.in/api?id=JoseLeoNav&icon=0&color=0" alt="Visit Count" />
            </a>
        </p>
    </div>

</body>
</html>
