<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Caio Cordeiro - Data Scientist & ML Researcher</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #111827; /* Dark Blue-Gray */
            color: #E5E7EB; /* Light Gray */
        }
        .tech-pill {
            display: inline-block;
            background-color: #374151; /* Medium Gray */
            color: #E5E7EB;
            padding: 0.5rem 1rem;
            margin: 0.25rem;
            border-radius: 9999px;
            font-size: 0.875rem;
            font-weight: 500;
            transition: all 0.2s ease-in-out;
        }
        .tech-pill:hover {
            background-color: #4F46E5; /* Indigo */
            transform: translateY(-2px);
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .project-tab {
            cursor: pointer;
            padding: 0.75rem 1.5rem;
            border-radius: 0.5rem;
            transition: background-color 0.2s ease-in-out;
        }
        .project-tab.active {
            background-color: #4F46E5; /* Indigo */
            color: #FFFFFF;
        }
        .project-content {
            display: none;
        }
        .project-content.active {
            display: block;
        }
        .icon-link svg {
            transition: transform 0.2s ease-in-out;
        }
        .icon-link:hover svg {
            transform: scale(1.1);
        }
    </style>
</head>
<body class="antialiased">

    <div class="max-w-4xl mx-auto p-4 sm:p-6 lg:p-8">
        
        <!-- Header Section -->
        <header class="text-center mb-12">
            <h1 class="text-4xl sm:text-5xl font-bold text-white">Caio Cordeiro, MSc.</h1>
            <p class="mt-2 text-xl sm:text-2xl text-indigo-400">Data Scientist & Machine Learning Researcher</p>
            <p class="mt-4 max-w-2xl mx-auto text-gray-300">
                Passionate about building solutions that matter. I thrive on exploring new technologies, turning complex problems into elegant code, and bringing ideas to life.
            </p>
            <div class="mt-6 flex justify-center space-x-6">
                <a href="https://www.linkedin.com/in/caio-cordeiro2" target="_blank" class="text-gray-400 hover:text-white icon-link">
                    <span class="sr-only">LinkedIn</span>
                    <svg class="w-8 h-8" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path fill-rule="evenodd" d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-11 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.113-4 0v5.604h-3v-11h3v1.765c1.396-2.586 7-2.777 7 2.476v6.759z" clip-rule="evenodd"/></svg>
                </a>
                <a href="https://github.com/CaioCordeiro" target="_blank" class="text-gray-400 hover:text-white icon-link">
                    <span class="sr-only">GitHub</span>
                    <svg class="w-8 h-8" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path fill-rule="evenodd" d="M12 2C6.477 2 2 6.477 2 12c0 4.418 2.865 8.168 6.839 9.492.5.092.682-.217.682-.482 0-.237-.009-.868-.014-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.555-4.951 0-1.093.39-1.988 1.031-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0112 6.844c.85.004 1.705.115 2.504.337 1.909-1.296 2.747-1.027 2.747-1.027.546 1.378.203 2.398.1 2.651.64.7 1.03 1.595 1.03 2.688 0 3.848-2.338 4.695-4.566 4.943.359.309.678.92.678 1.855 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.001 10.001 0 0022 12c0-5.523-4.477-10-10-10z" clip-rule="evenodd"/></svg>
                </a>
            </div>
        </header>

        <!-- Toolkit Section -->
        <section class="mb-12">
            <h2 class="text-3xl font-bold text-center text-white mb-6">My Digital Toolkit</h2>
            <div class="text-center">
                <span class="tech-pill">Python</span>
                <span class="tech-pill">JavaScript</span>
                <span class="tech-pill">SQL</span>
                <span class="tech-pill">Node.js</span>
                <span class="tech-pill">React</span>
                <span class="tech-pill">Flask</span>
                <span class="tech-pill">AWS</span>
                <span class="tech-pill">Azure</span>
                <span class="tech-pill">GCP</span>
                <span class="tech-pill">Docker</span>
                <span class="tech-pill">PostgreSQL</span>
                <span class="tech-pill">MongoDB</span>
                <span class="tech-pill">Microservices</span>
                <span class="tech-pill">REST APIs</span>
                <span class="tech-pill">Machine Learning</span>
                <span class="tech-pill">Data Science</span>
            </div>
        </section>

        <!-- Projects Section -->
        <section class="mb-12">
            <h2 class="text-3xl font-bold text-center text-white mb-8">Featured Projects</h2>
            <div class="bg-gray-800 rounded-lg shadow-lg p-4 sm:p-6">
                <div class="flex flex-col sm:flex-row justify-center border-b border-gray-700 mb-6">
                    <button class="project-tab active" onclick="showProject('p1')">PII Classification</button>
                    <button class="project-tab" onclick="showProject('p2')">Demand Forecasting</button>
                    <button class="project-tab" onclick="showProject('p3')">Smart City Testbed</button>
                </div>
                <div id="project-container">
                    <!-- Project 1 -->
                    <div id="p1" class="project-content active">
                        <h3 class="text-2xl font-semibold text-indigo-400">Automated PII Classification System</h3>
                        <p class="mt-2 text-gray-300">Engineered a system to automatically detect and classify Personally Identifiable Information (PII) in large datasets. This solution significantly enhances data privacy and ensures regulatory compliance by leveraging a state-of-the-art Named Entity Recognition (NER) model within a resilient microservices architecture.</p>
                        <div class="mt-4">
                            <span class="tech-pill">NER</span>
                            <span class="tech-pill">Python</span>
                            <span class="tech-pill">Microservices</span>
                            <span class="tech-pill">Data Privacy</span>
                        </div>
                    </div>
                    <!-- Project 2 -->
                    <div id="p2" class="project-content">
                        <h3 class="text-2xl font-semibold text-indigo-400">ML-Powered Demand Forecasting</h3>
                        <p class="mt-2 text-gray-300">Innovated and implemented an effective demand forecast solution for retail stores. By applying advanced machine learning techniques, the model provided highly accurate sales predictions, offering valuable insights for strategic decision-making, inventory management, and revenue optimization.</p>
                         <div class="mt-4">
                            <span class="tech-pill">Machine Learning</span>
                            <span class="tech-pill">Python</span>
                            <span class="tech-pill">Flask</span>
                            <span class="tech-pill">Microsoft Azure</span>
                        </div>
                    </div>
                    <!-- Project 3 -->
                    <div id="p3" class="project-content">
                        <h3 class="text-2xl font-semibold text-indigo-400">Synthetic Data Testbed for Smart Cities</h3>
                        <p class="mt-2 text-gray-300">Led the development of a versatile testing environment for Smart City applications. This project involved building a REST API and a user-facing interface to generate synthetic data, enabling robust testing and validation of urban-scale digital solutions before real-world deployment.</p>
                         <div class="mt-4">
                            <span class="tech-pill">React</span>
                            <span class="tech-pill">Node.js</span>
                            <span class="tech-pill">MongoDB</span>
                            <span class="tech-pill">REST API</span>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- About Me Section -->
        <section>
            <h2 class="text-3xl font-bold text-center text-white mb-6">When I'm Not Coding...</h2>
            <div class="grid grid-cols-2 md:grid-cols-4 gap-6 text-center">
                <div class="bg-gray-800 p-4 rounded-lg">
                    <p class="text-4xl">🍥</p>
                    <p class="mt-2 font-semibold">Watching Anime</p>
                    <p class="text-sm text-gray-400">Naruto, Slime Isekai</p>
                </div>
                <div class="bg-gray-800 p-4 rounded-lg">
                    <p class="text-4xl">🃏</p>
                    <p class="mt-2 font-semibold">Playing MTG</p>
                    <p class="text-sm text-gray-400">Tapping mana & cards</p>
                </div>
                <div class="bg-gray-800 p-4 rounded-lg">
                    <p class="text-4xl">🌌</p>
                    <p class="mt-2 font-semibold">Time Traveling</p>
                    <p class="text-sm text-gray-400">With The Doctor</p>
                </div>
                <div class="bg-gray-800 p-4 rounded-lg">
                    <p class="text-4xl">🎸</p>
                    <p class="mt-2 font-semibold">Listening to Music</p>
                    <p class="text-sm text-gray-400">BaianaSystem</p>
                </div>
            </div>
        </section>

    </div>

    <script>
        // Simple script to handle project tab switching
        const projectTabs = document.querySelectorAll('.project-tab');
        const projectContents = document.querySelectorAll('.project-content');

        function showProject(projectId) {
            // Update tab styles
            projectTabs.forEach(tab => {
                tab.classList.remove('active');
                if (tab.getAttribute('onclick').includes(projectId)) {
                    tab.classList.add('active');
                }
            });

            // Show the selected project content
            projectContents.forEach(content => {
                content.classList.remove('active');
                if (content.id === projectId) {
                    content.classList.add('active');
                }
            });
        }
    </script>

</body>
</html>
