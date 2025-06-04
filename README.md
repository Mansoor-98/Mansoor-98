<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Saqib Mansoor - Software Engineer & AI Innovator</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;700&family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
        }
        
        .code-font {
            font-family: 'JetBrains Mono', monospace;
        }
        
        .gradient-text {
            background: linear-gradient(45deg, #667eea, #764ba2, #f093fb, #f5576c);
            background-size: 400% 400%;
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            animation: gradientShift 4s ease-in-out infinite;
        }
        
        @keyframes gradientShift {
            0%, 100% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
        }
        
        .typing-animation {
            overflow: hidden;
            border-right: 3px solid #667eea;
            white-space: nowrap;
            margin: 0 auto;
            animation: typing 3s steps(40, end), blink-caret 0.75s step-end infinite;
        }
        
        @keyframes typing {
            from { width: 0; }
            to { width: 100%; }
        }
        
        @keyframes blink-caret {
            from, to { border-color: transparent; }
            50% { border-color: #667eea; }
        }
        
        .tech-badge {
            transition: all 0.3s ease;
        }
        
        .tech-badge:hover {
            transform: translateY(-2px) scale(1.05);
            box-shadow: 0 10px 25px rgba(0,0,0,0.2);
        }
        
        .project-card {
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255,255,255,0.2);
            transition: all 0.3s ease;
        }
        
        .project-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 40px rgba(0,0,0,0.2);
        }
        
        .glow-effect {
            box-shadow: 0 0 20px rgba(102, 126, 234, 0.4);
        }
        
        .pulse-animation {
            animation: pulse 2s infinite;
        }
        
        @keyframes pulse {
            0%, 100% { opacity: 1; }
            50% { opacity: 0.7; }
        }
        
        .stats-card {
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.2);
        }
    </style>
</head>
<body class="text-white">
    <div class="container mx-auto px-6 py-10">
        <!-- Header Section -->
        <div class="text-center mb-16">
            <div class="inline-block relative mb-6">
                <img src="https://via.placeholder.com/150x150/4CAF50/FFFFFF?text=SM" alt="Saqib Mansoor" class="w-32 h-32 rounded-full mx-auto border-4 border-white shadow-lg glow-effect">
                <div class="absolute -bottom-2 -right-2 bg-green-500 w-8 h-8 rounded-full border-4 border-white pulse-animation"></div>
            </div>
            
            <h1 class="text-5xl font-bold mb-4 gradient-text">Saqib Mansoor</h1>
            <div class="typing-animation text-xl mb-6 code-font">Software Engineer & AI Innovation Enthusiast</div>
            
            <div class="flex justify-center space-x-6 mb-8">
                <a href="mailto:saqib.mansoor.sm@gmail.com" class="tech-badge bg-red-500 hover:bg-red-600 px-4 py-2 rounded-full flex items-center space-x-2">
                    <i class="fas fa-envelope"></i>
                    <span>Email</span>
                </a>
                <a href="#" class="tech-badge bg-blue-500 hover:bg-blue-600 px-4 py-2 rounded-full flex items-center space-x-2">
                    <i class="fab fa-linkedin"></i>
                    <span>LinkedIn</span>
                </a>
                <a href="#" class="tech-badge bg-gray-800 hover:bg-gray-900 px-4 py-2 rounded-full flex items-center space-x-2">
                    <i class="fab fa-github"></i>
                    <span>GitHub</span>
                </a>
            </div>
            
            <p class="text-xl max-w-3xl mx-auto leading-relaxed">
                🏆 <strong>Award-Winning IEEE Project Developer</strong> | Recent Graduate passionate about creating 
                <span class="gradient-text font-semibold">AI-powered solutions</span> that make a real difference. 
                Specializing in Full-Stack Development with a focus on AI automations and assistive technologies.
            </p>
        </div>

        <!-- Award-Winning Project Spotlight -->
        <div class="mb-16">
            <h2 class="text-3xl font-bold text-center mb-8 gradient-text">🏆 Award-Winning Project Spotlight</h2>
            <div class="project-card bg-white bg-opacity-10 rounded-2xl p-8 max-w-4xl mx-auto">
                <div class="flex items-center mb-6">
                    <div class="bg-gradient-to-r from-purple-500 to-pink-500 w-16 h-16 rounded-2xl flex items-center justify-center text-3xl mr-6">
                        👁️
                    </div>
                    <div>
                        <h3 class="text-2xl font-bold">BlinkAI Companion</h3>
                        <p class="text-purple-300">IEEE Competition 2025 Winner • Flutter & AI Powered</p>
                    </div>
                </div>
                
                <p class="text-lg mb-6 leading-relaxed">
                    A revolutionary Flutter-based mobile application designed as an assistive technology tool for users with visual impairments. 
                    Features real-time computer vision models, voice control, and multiple AI-powered assistance modes.
                </p>
                
                <div class="grid md:grid-cols-2 gap-6 mb-6">
                    <div class="space-y-3">
                        <h4 class="font-semibold text-purple-300">🔥 Key Features:</h4>
                        <ul class="space-y-2 text-sm">
                            <li class="flex items-center"><i class="fas fa-eye text-blue-400 mr-2"></i> Real-time Object Detection</li>
                            <li class="flex items-center"><i class="fas fa-exclamation-triangle text-red-400 mr-2"></i> Hazard Detection & Alerts</li>
                            <li class="flex items-center"><i class="fas fa-image text-green-400 mr-2"></i> AI Scene Description</li>
                            <li class="flex items-center"><i class="fas fa-font text-yellow-400 mr-2"></i> OCR Text Reading</li>
                            <li class="flex items-center"><i class="fas fa-barcode text-purple-400 mr-2"></i> Barcode Scanner</li>
                        </ul>
                    </div>
                    <div class="space-y-3">
                        <h4 class="font-semibold text-purple-300">⚡ Technologies Used:</h4>
                        <div class="flex flex-wrap gap-2">
                            <span class="tech-badge bg-blue-600 px-3 py-1 rounded-full text-xs">Flutter</span>
                            <span class="tech-badge bg-green-600 px-3 py-1 rounded-full text-xs">Python</span>
                            <span class="tech-badge bg-orange-600 px-3 py-1 rounded-full text-xs">PyTorch</span>
                            <span class="tech-badge bg-red-600 px-3 py-1 rounded-full text-xs">OpenCV</span>
                            <span class="tech-badge bg-purple-600 px-3 py-1 rounded-full text-xs">WebSockets</span>
                            <span class="tech-badge bg-indigo-600 px-3 py-1 rounded-full text-xs">TTS</span>
                        </div>
                    </div>
                </div>
                
                <div class="flex space-x-4">
                    <button class="tech-badge bg-gradient-to-r from-purple-500 to-pink-500 px-6 py-2 rounded-full flex items-center space-x-2">
                        <i class="fab fa-github"></i>
                        <span>View Project</span>
                    </button>
                    <button class="tech-badge bg-gradient-to-r from-blue-500 to-purple-500 px-6 py-2 rounded-full flex items-center space-x-2">
                        <i class="fas fa-play"></i>
                        <span>Live Demo</span>
                    </button>
                </div>
            </div>
        </div>

        <!-- Tech Stack -->
        <div class="mb-16">
            <h2 class="text-3xl font-bold text-center mb-8 gradient-text">💻 Tech Stack & Skills</h2>
            <div class="grid md:grid-cols-4 gap-6">
                <div class="stats-card rounded-2xl p-6 text-center">
                    <i class="fas fa-code text-4xl text-blue-400 mb-4"></i>
                    <h3 class="font-semibold mb-3">Languages</h3>
                    <div class="space-y-2">
                        <div class="tech-badge bg-yellow-600 px-3 py-1 rounded-full text-xs">Python</div>
                        <div class="tech-badge bg-yellow-500 px-3 py-1 rounded-full text-xs">JavaScript</div>
                        <div class="tech-badge bg-blue-600 px-3 py-1 rounded-full text-xs">Dart</div>
                    </div>
                </div>
                
                <div class="stats-card rounded-2xl p-6 text-center">
                    <i class="fas fa-layer-group text-4xl text-green-400 mb-4"></i>
                    <h3 class="font-semibold mb-3">Frontend</h3>
                    <div class="space-y-2">
                        <div class="tech-badge bg-blue-500 px-3 py-1 rounded-full text-xs">React</div>
                        <div class="tech-badge bg-blue-600 px-3 py-1 rounded-full text-xs">Flutter</div>
                        <div class="tech-badge bg-orange-500 px-3 py-1 rounded-full text-xs">HTML/CSS</div>
                    </div>
                </div>
                
                <div class="stats-card rounded-2xl p-6 text-center">
                    <i class="fas fa-brain text-4xl text-purple-400 mb-4"></i>
                    <h3 class="font-semibold mb-3">AI/ML</h3>
                    <div class="space-y-2">
                        <div class="tech-badge bg-orange-600 px-3 py-1 rounded-full text-xs">PyTorch</div>
                        <div class="tech-badge bg-green-600 px-3 py-1 rounded-full text-xs">OpenCV</div>
                        <div class="tech-badge bg-gray-700 px-3 py-1 rounded-full text-xs">Ollama</div>
                    </div>
                </div>
                
                <div class="stats-card rounded-2xl p-6 text-center">
                    <i class="fas fa-robot text-4xl text-red-400 mb-4"></i>
                    <h3 class="font-semibold mb-3">Automation</h3>
                    <div class="space-y-2">
                        <div class="tech-badge bg-purple-600 px-3 py-1 rounded-full text-xs">Make.com</div>
                        <div class="tech-badge bg-indigo-600 px-3 py-1 rounded-full text-xs">n8n</div>
                        <div class="tech-badge bg-green-700 px-3 py-1 rounded-full text-xs">AI Caller</div>
                    </div>
                </div>
            </div>
        </div>

        <!-- GitHub Stats -->
        <div class="mb-16">
            <h2 class="text-3xl font-bold text-center mb-8 gradient-text">📊 GitHub Statistics</h2>
            <div class="grid md:grid-cols-2 gap-6 max-w-4xl mx-auto">
                <div class="stats-card rounded-2xl p-6 text-center">
                    <img src="https://github-readme-stats.vercel.app/api?username=Mansoor-98&show_icons=true&theme=radical&hide_border=true&bg_color=0D1117" alt="GitHub Stats" class="w-full rounded-lg">
                </div>
                <div class="stats-card rounded-2xl p-6 text-center">
                    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Mansoor-98&layout=compact&theme=radical&hide_border=true&bg_color=0D1117" alt="Top Languages" class="w-full rounded-lg">
                </div>
            </div>
            <div class="text-center mt-6">
                <img src="https://github-readme-streak-stats.herokuapp.com/?user=Mansoor-98&theme=radical&hide_border=true&background=0D1117" alt="GitHub Streak" class="mx-auto rounded-lg">
            </div>
        </div>

        <!-- Featured Projects -->
        <div class="mb-16">
            <h2 class="text-3xl font-bold text-center mb-8 gradient-text">🚀 Featured Projects</h2>
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-6">
                <div class="project-card bg-white bg-opacity-10 rounded-2xl p-6">
                    <div class="flex items-center mb-4">
                        <div class="bg-blue-500 w-12 h-12 rounded-lg flex items-center justify-center text-2xl mr-4">
                            📱
                        </div>
                        <div>
                            <h3 class="font-bold">Simple Login</h3>
                            <p class="text-sm text-gray-300">HTML Authentication</p>
                        </div>
                    </div>
                    <p class="text-sm mb-4">Clean and simple login interface with modern design principles.</p>
                    <div class="flex justify-between items-center">
                        <span class="tech-badge bg-orange-600 px-2 py-1 rounded text-xs">HTML</span>
                        <span class="text-green-400 text-xs">Public</span>
                    </div>
                </div>
                
                <div class="project-card bg-white bg-opacity-10 rounded-2xl p-6">
                    <div class="flex items-center mb-4">
                        <div class="bg-green-500 w-12 h-12 rounded-lg flex items-center justify-center text-2xl mr-4">
                            🐍
                        </div>
                        <div>
                            <h3 class="font-bold">Python Selenium Scraper</h3>
                            <p class="text-sm text-gray-300">Web Automation</p>
                        </div>
                    </div>
                    <p class="text-sm mb-4">Advanced web scraping tool using Selenium for dynamic content extraction.</p>
                    <div class="flex justify-between items-center">
                        <span class="tech-badge bg-yellow-600 px-2 py-1 rounded text-xs">Python</span>
                        <span class="text-green-400 text-xs">Public</span>
                    </div>
                </div>
                
                <div class="project-card bg-white bg-opacity-10 rounded-2xl p-6">
                    <div class="flex items-center mb-4">
                        <div class="bg-purple-500 w-12 h-12 rounded-lg flex items-center justify-center text-2xl mr-4">
                            🤖
                        </div>
                        <div>
                            <h3 class="font-bold">AI Cold Caller</h3>
                            <p class="text-sm text-gray-300">Lead Automation</p>
                        </div>
                    </div>
                    <p class="text-sm mb-4">Intelligent system that automatically books and qualifies leads based on custom criteria.</p>
                    <div class="flex justify-between items-center">
                        <span class="tech-badge bg-purple-600 px-2 py-1 rounded text-xs">AI</span>
                        <span class="text-yellow-400 text-xs">Private</span>
                    </div>
                </div>
            </div>
        </div>

        <!-- Current Focus -->
        <div class="mb-16">
            <h2 class="text-3xl font-bold text-center mb-8 gradient-text">🎯 Current Focus</h2>
            <div class="max-w-3xl mx-auto stats-card rounded-2xl p-8 text-center">
                <div class="grid md:grid-cols-3 gap-6">
                    <div>
                        <i class="fas fa-laptop-code text-4xl text-blue-400 mb-4"></i>
                        <h3 class="font-semibold mb-2">Full-Stack Development</h3>
                        <p class="text-sm text-gray-300">Building end-to-end web applications with modern technologies</p>
                    </div>
                    <div>
                        <i class="fas fa-robot text-4xl text-green-400 mb-4"></i>
                        <h3 class="font-semibold mb-2">AI Automation</h3>
                        <p class="text-sm text-gray-300">Creating intelligent automation solutions using Make & n8n platforms</p>
                    </div>
                    <div>
                        <i class="fas fa-graduation-cap text-4xl text-purple-400 mb-4"></i>
                        <h3 class="font-semibold mb-2">Continuous Learning</h3>
                        <p class="text-sm text-gray-300">Always exploring new technologies and building innovative projects</p>
                    </div>
                </div>
            </div>
        </div>

        <!-- Fun Facts -->
        <div class="text-center">
            <h2 class="text-3xl font-bold mb-8 gradient-text">⚡ Fun Facts</h2>
            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-4 max-w-4xl mx-auto">
                <div class="stats-card rounded-2xl p-4 text-center">
                    <i class="fas fa-trophy text-3xl text-yellow-400 mb-2"></i>
                    <div class="font-bold">IEEE Winner</div>
                    <div class="text-xs text-gray-300">2025 Competition</div>
                </div>
                <div class="stats-card rounded-2xl p-4 text-center">
                    <i class="fas fa-heart text-3xl text-red-400 mb-2"></i>
                    <div class="font-bold">Tech Enthusiast</div>
                    <div class="text-xs text-gray-300">Love Learning</div>
                </div>
                <div class="stats-card rounded-2xl p-4 text-center">
                    <i class="fas fa-coffee text-3xl text-yellow-600 mb-2"></i>
                    <div class="font-bold">Coffee Driven</div>
                    <div class="text-xs text-gray-300">Code & Create</div>
                </div>
                <div class="stats-card rounded-2xl p-4 text-center">
                    <i class="fas fa-rocket text-3xl text-blue-400 mb-2"></i>
                    <div class="font-bold">Innovation</div>
                    <div class="text-xs text-gray-300">Always Building</div>
                </div>
            </div>
            
            <div class="mt-12">
                <p class="text-lg mb-4">💡 <em>"Passionate about creating technology that makes a difference"</em></p>
                <p class="text-sm text-gray-300">Let's connect and build something amazing together! 🚀</p>
            </div>
        </div>
    </div>
</body>
</html>
