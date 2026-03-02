<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Atrix Bloom V1 - Fortnite Bloom Reducer</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700;900&family=Rajdhani:wght@500;700&display=swap');
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            background: #0a0a0f;
            color: #fff;
            font-family: 'Rajdhani', sans-serif;
            overflow-x: hidden;
            min-height: 100vh;
        }
        
        /* Animated Background */
        .bg-grid {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-image: 
                linear-gradient(rgba(0, 255, 255, 0.03) 1px, transparent 1px),
                linear-gradient(90deg, rgba(0, 255, 255, 0.03) 1px, transparent 1px);
            background-size: 50px 50px;
            z-index: -2;
            animation: gridMove 20s linear infinite;
        }
        
        @keyframes gridMove {
            0% { transform: perspective(500px) rotateX(60deg) translateY(0); }
            100% { transform: perspective(500px) rotateX(60deg) translateY(50px); }
        }
        
        .glow-orb {
            position: fixed;
            border-radius: 50%;
            filter: blur(100px);
            opacity: 0.4;
            z-index: -1;
            animation: float 10s ease-in-out infinite;
        }
        
        .glow-orb:nth-child(1) {
            width: 400px;
            height: 400px;
            background: radial-gradient(circle, rgba(0, 255, 255, 0.4), transparent);
            top: -100px;
            right: -100px;
        }
        
        .glow-orb:nth-child(2) {
            width: 300px;
            height: 300px;
            background: radial-gradient(circle, rgba(255, 0, 255, 0.3), transparent);
            bottom: -50px;
            left: -50px;
            animation-delay: -5s;
        }
        
        @keyframes float {
            0%, 100% { transform: translate(0, 0); }
            50% { transform: translate(30px, -30px); }
        }
        
        /* Header */
        header {
            padding: 20px 40px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-bottom: 1px solid rgba(0, 255, 255, 0.1);
            background: rgba(10, 10, 15, 0.8);
            backdrop-filter: blur(10px);
            position: sticky;
            top: 0;
            z-index: 100;
        }
        
        .logo {
            display: flex;
            align-items: center;
            gap: 15px;
        }
        
        .logo-icon {
            width: 50px;
            height: 50px;
            background: linear-gradient(135deg, #00ffff, #ff00ff);
            border-radius: 12px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-family: 'Orbitron', sans-serif;
            font-weight: 900;
            font-size: 24px;
            box-shadow: 0 0 20px rgba(0, 255, 255, 0.5);
            animation: pulse 2s ease-in-out infinite;
        }
        
        @keyframes pulse {
            0%, 100% { box-shadow: 0 0 20px rgba(0, 255, 255, 0.5); }
            50% { box-shadow: 0 0 40px rgba(0, 255, 255, 0.8); }
        }
        
        .logo-text h1 {
            font-family: 'Orbitron', sans-serif;
            font-size: 28px;
            background: linear-gradient(90deg, #00ffff, #ff00ff);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            letter-spacing: 2px;
        }
        
        .logo-text span {
            color: #666;
            font-size: 12px;
            letter-spacing: 4px;
            text-transform: uppercase;
        }
        
        .status-badge {
            padding: 8px 20px;
            background: rgba(0, 255, 0, 0.1);
            border: 1px solid rgba(0, 255, 0, 0.3);
            border-radius: 20px;
            color: #00ff88;
            font-weight: 700;
            display: flex;
            align-items: center;
            gap: 8px;
            animation: glow 2s ease-in-out infinite alternate;
        }
        
        @keyframes glow {
            from { box-shadow: 0 0 5px rgba(0, 255, 136, 0.2); }
            to { box-shadow: 0 0 20px rgba(0, 255, 136, 0.4); }
        }
        
        .status-dot {
            width: 8px;
            height: 8px;
            background: #00ff88;
            border-radius: 50%;
            animation: blink 1s infinite;
        }
        
        @keyframes blink {
            0%, 100% { opacity: 1; }
            50% { opacity: 0.3; }
        }
        
        /* Main Container */
        .container {
            max-width: 1400px;
            margin: 0 auto;
            padding: 40px;
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 40px;
        }
        
        /* Panel Styling */
        .panel {
            background: rgba(20, 20, 30, 0.6);
            border: 1px solid rgba(0, 255, 255, 0.1);
            border-radius: 20px;
            padding: 30px;
            backdrop-filter: blur(10px);
            position: relative;
            overflow: hidden;
        }
        
        .panel::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 2px;
            background: linear-gradient(90deg, transparent, #00ffff, #ff00ff, transparent);
            animation: scan 3s linear infinite;
        }
        
        @keyframes scan {
            0% { transform: translateX(-100%); }
            100% { transform: translateX(100%); }
        }
        
        .panel-title {
            font-family: 'Orbitron', sans-serif;
            font-size: 20px;
            margin-bottom: 25px;
            color: #00ffff;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .panel-title::after {
            content: '';
            flex: 1;
            height: 1px;
            background: linear-gradient(90deg, rgba(0, 255, 255, 0.3), transparent);
            margin-left: 15px;
        }
        
        /* Visualizer Canvas */
        #bloomCanvas {
            width: 100%;
            height: 400px;
            background: radial-gradient(circle at center, #1a1a2e 0%, #0a0a0f 100%);
            border-radius: 15px;
            border: 1px solid rgba(0, 255, 255, 0.2);
            position: relative;
            overflow: hidden;
        }
        
        .crosshair {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 40px;
            height: 40px;
            pointer-events: none;
        }
        
        .crosshair::before,
        .crosshair::after {
            content: '';
            position: absolute;
            background: rgba(0, 255, 255, 0.8);
            box-shadow: 0 0 10px rgba(0, 255, 255, 0.8);
        }
        
        .crosshair::before {
            width: 2px;
            height: 100%;
            left: 50%;
            transform: translateX(-50%);
        }
        
        .crosshair::after {
            width: 100%;
            height: 2px;
            top: 50%;
            transform: translateY(-50%);
        }
        
        /* Controls */
        .control-group {
            margin-bottom: 25px;
        }
        
        .control-label {
            display: flex;
            justify-content: space-between;
            margin-bottom: 10px;
            font-weight: 500;
            color: #aaa;
        }
        
        .control-label span:last-child {
            color: #00ffff;
            font-family: 'Orbitron', sans-serif;
            font-weight: 700;
        }
        
        .slider-container {
            position: relative;
            height: 40px;
            display: flex;
            align-items: center;
        }
        
        input[type="range"] {
            width: 100%;
            height: 6px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 3px;
            outline: none;
            -webkit-appearance: none;
        }
        
        input[type="range"]::-webkit-slider-thumb {
            -webkit-appearance: none;
            width: 20px;
            height: 20px;
            background: linear-gradient(135deg, #00ffff, #ff00ff);
            border-radius: 50%;
            cursor: pointer;
            box-shadow: 0 0 15px rgba(0, 255, 255, 0.6);
            transition: transform 0.2s;
        }
        
        input[type="range"]::-webkit-slider-thumb:hover {
            transform: scale(1.2);
        }
        
        .toggle-switch {
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 15px;
            background: rgba(0, 0, 0, 0.3);
            border-radius: 10px;
            margin-bottom: 15px;
            cursor: pointer;
            transition: all 0.3s;
            border: 1px solid transparent;
        }
        
        .toggle-switch:hover {
            border-color: rgba(0, 255, 255, 0.3);
            background: rgba(0, 255, 255, 0.05);
        }
        
        .toggle-switch.active {
            border-color: #00ff88;
            background: rgba(0, 255, 136, 0.1);
        }
        
        .toggle-switch h3 {
            font-size: 16px;
            color: #fff;
            margin-bottom: 4px;
        }
        
        .toggle-switch p {
            font-size: 12px;
            color: #666;
        }
        
        .switch {
            width: 50px;
            height: 26px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 13px;
            position: relative;
            transition: 0.3s;
        }
        
        .switch::after {
            content: '';
            position: absolute;
            width: 22px;
            height: 22px;
            background: #666;
            border-radius: 50%;
            top: 2px;
            left: 2px;
            transition: 0.3s;
        }
        
        .toggle-switch.active .switch {
            background: rgba(0, 255, 136, 0.3);
        }
        
        .toggle-switch.active .switch::after {
            background: #00ff88;
            left: 26px;
            box-shadow: 0 0 10px rgba(0, 255, 136, 0.8);
        }
        
        /* Stats Grid */
        .stats-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 15px;
            margin-top: 20px;
        }
        
        .stat-card {
            background: rgba(0, 0, 0, 0.4);
            padding: 15px;
            border-radius: 10px;
            text-align: center;
            border: 1px solid rgba(0, 255, 255, 0.1);
            transition: transform 0.3s;
        }
        
        .stat-card:hover {
            transform: translateY(-5px);
            border-color: rgba(0, 255, 255, 0.3);
        }
        
        .stat-value {
            font-family: 'Orbitron', sans-serif;
            font-size: 24px;
            color: #00ffff;
            font-weight: 700;
        }
        
        .stat-label {
            font-size: 11px;
            color: #666;
            text-transform: uppercase;
            letter-spacing: 1px;
            margin-top: 5px;
        }
        
        /* Action Buttons */
        .action-buttons {
            display: flex;
            gap: 15px;
            margin-top: 30px;
        }
        
        .btn {
            flex: 1;
            padding: 15px 30px;
            border: none;
            border-radius: 10px;
            font-family: 'Orbitron', sans-serif;
            font-weight: 700;
            font-size: 14px;
            cursor: pointer;
            transition: all 0.3s;
            text-transform: uppercase;
            letter-spacing: 1px;
            position: relative;
            overflow: hidden;
        }
        
        .btn-primary {
            background: linear-gradient(135deg, #00ffff, #0088ff);
            color: #000;
            box-shadow: 0 0 20px rgba(0, 255, 255, 0.3);
        }
        
        .btn-primary:hover {
            transform: translateY(-2px);
            box-shadow: 0 0 30px rgba(0, 255, 255, 0.5);
        }
        
        .btn-secondary {
            background: transparent;
            color: #00ffff;
            border: 1px solid rgba(0, 255, 255, 0.3);
        }
        
        .btn-secondary:hover {
            background: rgba(0, 255, 255, 0.1);
            border-color: #00ffff;
        }
        
        .btn::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.4), transparent);
            transition: 0.5s;
        }
        
        .btn:hover::before {
            left: 100%;
        }
        
        /* Console Log */
        .console {
            background: rgba(0, 0, 0, 0.8);
            border-radius: 10px;
            padding: 20px;
            font-family: 'Courier New', monospace;
            font-size: 12px;
            height: 150px;
            overflow-y: auto;
            border: 1px solid rgba(0, 255, 255, 0.1);
            margin-top: 20px;
        }
        
        .console-line {
            margin-bottom: 5px;
            color: #00ff88;
            opacity: 0;
            animation: fadeIn 0.3s forwards;
        }
        
        @keyframes fadeIn {
            to { opacity: 1; }
        }
        
        .console-line.error { color: #ff4444; }
        .console-line.warning { color: #ffaa00; }
        .console-line.info { color: #00ffff; }
        
        /* Responsive */
        @media (max-width: 968px) {
            .container {
                grid-template-columns: 1fr;
            }
        }
        
        /* Particle Effects */
        .particle {
            position: absolute;
            width: 2px;
            height: 2px;
            background: #00ffff;
            border-radius: 50%;
            pointer-events: none;
            animation: particleFloat 3s linear infinite;
        }
        
        @keyframes particleFloat {
            0% { transform: translateY(0) translateX(0); opacity: 0; }
            10% { opacity: 1; }
            90% { opacity: 1; }
            100% { transform: translateY(-100px) translateX(50px); opacity: 0; }
        }
    </style>
</head>
<body>
    <div class="bg-grid"></div>
    <div class="glow-orb"></div>
    <div class="glow-orb"></div>
    
    <header>
        <div class="logo">
            <div class="logo-icon">A</div>
            <div class="logo-text">
                <h1>ATRIX BLOOM</h1>
                <span>Version 1.0.0 // Build 2024</span>
            </div>
        </div>
        <div class="status-badge">
            <div class="status-dot"></div>
            <span>SYSTEM ACTIVE</span>
        </div>
    </header>
    
    <div class="container">
        <!-- Left Panel: Visualizer -->
        <div class="panel">
            <h2 class="panel-title">Bloom Visualizer</h2>
            <div id="bloomCanvas">
                <canvas id="canvas"></canvas>
                <div class="crosshair"></div>
            </div>
            
            <div class="stats-grid">
                <div class="stat-card">
                    <div class="stat-value" id="accuracyStat">98%</div>
                    <div class="stat-label">Accuracy</div>
                </div>
                <div class="stat-card">
                    <div class="stat-value" id="spreadStat">2.4°</div>
                    <div class="stat-label">Spread</div>
                </div>
                <div class="stat-card">
                    <div class="stat-value" id="fpsStat">240</div>
                    <div class="stat-label">FPS Impact</div>
                </div>
            </div>
            
            <div class="console" id="console">
                <div class="console-line info">> Atrix Bloom V1 initialized...</div>
                <div class="console-line info">> Loading configuration...</div>
                <div class="console-line info">> Ready to optimize</div>
            </div>
        </div>
        
        <!-- Right Panel: Controls -->
        <div class="panel">
            <h2 class="panel-title">Configuration</h2>
            
            <div class="control-group">
                <div class="control-label">
                    <span>Bloom Reduction Intensity</span>
                    <span id="intensityValue">75%</span>
                </div>
                <div class="slider-container">
                    <input type="range" id="intensitySlider" min="0" max="100" value="75">
                </div>
            </div>
            
            <div class="control-group">
                <div class="control-label">
                    <span>Recoil Stabilization</span>
                    <span id="recoilValue">60%</span>
                </div>
                <div class="slider-container">
                    <input type="range" id="recoilSlider" min="0" max="100" value="60">
                </div>
            </div>
            
            <div class="control-group">
                <div class="control-label">
                    <span>ADS Precision</span>
                    <span id="adsValue">85%</span>
                </div>
                <div class="slider-container">
                    <input type="range" id="adsSlider" min="0" max="100" value="85">
                </div>
            </div>
            
            <div class="control-group">
                <div class="control-label">
                    <span>Hip-Fire Tightening</span>
                    <span id="hipValue">40%</span>
                </div>
                <div class="slider-container">
                    <input type="range" id="hipSlider" min="0" max="100" value="40">
                </div>
            </div>
            
            <h3 style="margin: 25px 0 15px; color: #00ffff; font-family: 'Orbitron', sans-serif; font-size: 14px;">Advanced Features</h3>
            
            <div class="toggle-switch active" onclick="toggleFeature(this, 'dynamicBloom')">
                <div>
                    <h3>Dynamic Bloom Scaling</h3>
                    <p>Auto-adjust based on weapon type</p>
                </div>
                <div class="switch"></div>
            </div>
            
            <div class="toggle-switch" onclick="toggleFeature(this, 'recoilComp')">
                <div>
                    <h3>Recoil Compensation</h3>
                    <p>Vertical recoil prediction</p>
                </div>
                <div class="switch"></div>
            </div>
            
            <div class="toggle-switch active" onclick="toggleFeature(this, 'fpsOptimize')">
                <div>
                    <h3>FPS Optimization</h3>
                    <p>Reduce GPU load</p>
                </div>
                <div class="switch"></div>
            </div>
            
            <div class="action-buttons">
                <button class="btn btn-primary" onclick="applySettings()">Apply Settings</button>
                <button class="btn btn-secondary" onclick="resetSettings()">Reset Default</button>
            </div>
        </div>
    </div>
    
    <script>
        // Canvas Setup
        const canvas = document.getElementById('canvas');
        const ctx = canvas.getContext('2d');
        const container = document.getElementById('bloomCanvas');
        
        function resizeCanvas() {
            canvas.width = container.clientWidth;
            canvas.height = container.clientHeight;
        }
        resizeCanvas();
        window.addEventListener('resize', resizeCanvas);
        
        // Bloom Simulation State
        let bloomRadius = 50;
        let targetRadius = 50;
        let particles = [];
        let recoilOffset = 0;
        let time = 0;
        
        class Particle {
            constructor() {
                this.x = canvas.width / 2 + (Math.random() - 0.5) * bloomRadius * 2;
                this.y = canvas.height / 2 + (Math.random() - 0.5) * bloomRadius * 2 + recoilOffset;
                this.vx = (Math.random() - 0.5) * 2;
                this.vy = (Math.random() - 0.5) * 2;
                this.life = 1;
                this.color = Math.random() > 0.5 ? '#00ffff' : '#ff00ff';
            }
            
            update() {
                this.x += this.vx;
                this.y += this.vy;
                this.life -= 0.02;
                this.vx *= 0.98;
                this.vy *= 0.98;
            }
            
            draw() {
                ctx.globalAlpha = this.life * 0.5;
                ctx.fillStyle = this.color;
                ctx.beginPath();
                ctx.arc(this.x, this.y, 2, 0, Math.PI * 2);
                ctx.fill();
                ctx.globalAlpha = 1;
            }
        }
        
        function drawBloom() {
            ctx.fillStyle = '#0a0a0f';
            ctx.fillRect(0, 0, canvas.width, canvas.height);
            
            // Draw grid
            ctx.strokeStyle = 'rgba(0, 255, 255, 0.05)';
            ctx.lineWidth = 1;
            const gridSize = 30;
            
            for (let x = 0; x < canvas.width; x += gridSize) {
                ctx.beginPath();
                ctx.moveTo(x, 0);
                ctx.lineTo(x, canvas.height);
                ctx.stroke();
            }
            for (let y = 0; y < canvas.height; y += gridSize) {
                ctx.beginPath();
                ctx.moveTo(0, y);
                ctx.lineTo(canvas.width, y);
                ctx.stroke();
            }
            
            // Smooth radius transition
            bloomRadius += (targetRadius - bloomRadius) * 0.1;
            
            // Draw bloom circle
            const centerX = canvas.width / 2;
            const centerY = canvas.height / 2 + recoilOffset;
            
            // Outer glow
            const gradient = ctx.createRadialGradient(centerX, centerY, 0, centerX, centerY, bloomRadius * 2);
            gradient.addColorStop(0, 'rgba(0, 255, 255, 0.2)');
            gradient.addColorStop(0.5, 'rgba(0, 255, 255, 0.1)');
            gradient.addColorStop(1, 'transparent');
            
            ctx.fillStyle = gradient;
            ctx.beginPath();
            ctx.arc(centerX, centerY, bloomRadius * 2, 0, Math.PI * 2);
            ctx.fill();
            
            // Inner bloom
            ctx.strokeStyle = 'rgba(0, 255, 255, 0.6)';
            ctx.lineWidth = 2;
            ctx.beginPath();
            ctx.arc(centerX, centerY, bloomRadius, 0, Math.PI * 2);
            ctx.stroke();
            
            // Crosshair lines
            ctx.strokeStyle = 'rgba(255, 255, 255, 0.8)';
            ctx.lineWidth = 1;
            
            // Horizontal
            ctx.beginPath();
            ctx.moveTo(centerX - bloomRadius - 10, centerY);
            ctx.lineTo(centerX - 5, centerY);
            ctx.moveTo(centerX + 5, centerY);
            ctx.lineTo(centerX + bloomRadius + 10, centerY);
            ctx.stroke();
            
            // Vertical
            ctx.beginPath();
            ctx.moveTo(centerX, centerY - bloomRadius - 10);
            ctx.lineTo(centerX, centerY - 5);
            ctx.moveTo(centerX, centerY + 5);
            ctx.lineTo(centerX, centerY + bloomRadius + 10);
            ctx.stroke();
            
            // Particles
            if (Math.random() < 0.3) {
                particles.push(new Particle());
            }
            
            particles = particles.filter(p => p.life > 0);
            particles.forEach(p => {
                p.update();
                p.draw();
            });
            
            // Simulate recoil breathing
            time += 0.05;
            recoilOffset = Math.sin(time) * 5;
            
            requestAnimationFrame(drawBloom);
        }
        
        drawBloom();
        
        // Controls
        const intensitySlider = document.getElementById('intensitySlider');
        const recoilSlider = document.getElementById('recoilSlider');
        const adsSlider = document.getElementById('adsSlider');
        const hipSlider = document.getElementById('hipSlider');
        
        function updateValues() {
            document.getElementById('intensityValue').textContent = intensitySlider.value + '%';
            document.getElementById('recoilValue').textContent = recoilSlider.value + '%';
            document.getElementById('adsValue').textContent = adsSlider.value + '%';
            document.getElementById('hipValue').textContent = hipSlider.value + '%';
            
            // Update bloom visualization
            const reduction = intensitySlider.value / 100;
            targetRadius = 80 - (reduction * 60); // 80 to 20
            
            // Update stats
            const accuracy = Math.floor(85 + (reduction * 14));
            document.getElementById('accuracyStat').textContent = accuracy + '%';
            
            const spread = (5 - (reduction * 4)).toFixed(1);
            document.getElementById('spreadStat').textContent = spread + '°';
        }
        
        intensitySlider.addEventListener('input', updateValues);
        recoilSlider.addEventListener('input', updateValues);
        adsSlider.addEventListener('input', updateValues);
        hipSlider.addEventListener('input', updateValues);
        
        // Toggle Features
        function toggleFeature(element, feature) {
            element.classList.toggle('active');
            const isActive = element.classList.contains('active');
            logConsole(`${feature}: ${isActive ? 'ENABLED' : 'DISABLED'}`, isActive ? 'info' : 'warning');
        }
        
        // Console Logger
        function logConsole(message, type = 'info') {
            const console = document.getElementById('console');
            const line = document.createElement('div');
            line.className = `console-line ${type}`;
            line.textContent = `> ${message}`;
            console.appendChild(line);
            console.scrollTop = console.scrollHeight;
            
            // Keep only last 20 lines
            while (console.children.length > 20) {
                console.removeChild(console.firstChild);
            }
        }
        
        // Apply Settings
        function applySettings() {
            logConsole('Applying bloom reduction settings...', 'info');
            
            setTimeout(() => {
                logConsole(`Intensity set to ${intensitySlider.value}%`, 'info');
                logConsole(`Recoil stabilization: ${recoilSlider.value}%`, 'info');
                logConsole(`ADS precision: ${adsSlider.value}%`, 'info');
                logConsole('Configuration saved successfully!', 'info');
                
                // Visual feedback
                const btn = document.querySelector('.btn-primary');
                const originalText = btn.textContent;
                btn.textContent = 'APPLIED!';
                btn.style.background = 'linear-gradient(135deg, #00ff88, #00aa88)';
                
                setTimeout(() => {
                    btn.textContent = originalText;
                    btn.style.background = '';
                }, 2000);
            }, 500);
        }
        
        // Reset Settings
        function resetSettings() {
            intensitySlider.value = 75;
            recoilSlider.value = 60;
            adsSlider.value = 85;
            hipSlider.value = 40;
            updateValues();
            logConsole('Settings reset to default values', 'warning');
        }
        
        // Initialize
        updateValues();
        
        // Add random console messages
        setInterval(() => {
            const messages = [
                'Monitoring input latency...',
                'Optimizing render pipeline...',
                'Syncing with game client...',
                'Bloom pattern analyzed',
                'Recoil data updated'
            ];
            if (Math.random() < 0.3) {
                logConsole(messages[Math.floor(Math.random() * messages.length)], 'info');
            }
        }, 5000);
    </script>
</body>
</html>
