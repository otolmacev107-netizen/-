<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>YOU WON IPHONE 16!!!</title>
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }
        
        body {
            font-family: 'Comic Sans MS', 'Arial', sans-serif;
            background: linear-gradient(45deg, #ff0000, #ffff00, #ff00ff, #00ffff);
            background-size: 400% 400%;
            animation: gradientBG 3s ease infinite;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 10px;
            cursor: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><text x="0" y="20" font-size="20">👆</text></svg>') 12 12, auto;
        }
        
        @keyframes gradientBG {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }
        
        .container {
            max-width: 500px;
            width: 100%;
            background-color: rgba(0, 0, 0, 0.8);
            padding: 20px;
            border: 5px solid yellow;
            border-radius: 20px;
            box-shadow: 0 0 50px red, 0 0 100px blue;
            animation: borderPulse 1s infinite;
            position: relative;
            backdrop-filter: blur(5px);
        }
        
        @keyframes borderPulse {
            0% { border-color: yellow; }
            33% { border-color: red; }
            66% { border-color: blue; }
            100% { border-color: yellow; }
        }
        
        .blink {
            animation: blinker 0.5s infinite;
            font-size: 24px;
            font-weight: bold;
            color: white;
            text-shadow: 3px 3px 0 red, 6px 6px 0 blue;
        }
        
        @keyframes blinker {
            0% { opacity: 1; transform: rotate(0deg); }
            25% { opacity: 0.5; transform: rotate(2deg); }
            50% { opacity: 1; transform: rotate(-2deg); }
            75% { opacity: 0.5; transform: rotate(1deg); }
            100% { opacity: 1; transform: rotate(0deg); }
        }
        
        .banner {
            background-color: yellow;
            color: red;
            padding: 15px;
            margin: 15px 0;
            font-size: 28px;
            text-align: center;
            font-weight: bold;
            border: 3px dashed black;
            transform: rotate(-1deg);
            box-shadow: 10px 10px 0 red;
        }
        
        .fake-button {
            background: linear-gradient(45deg, #ff0000, #ff6666);
            color: white;
            padding: 20px;
            margin: 15px 0;
            text-align: center;
            font-size: 30px;
            font-weight: bold;
            border: 3px solid white;
            border-radius: 50px;
            cursor: pointer;
            transition: all 0.1s;
            text-shadow: 2px 2px 0 black;
            box-shadow: 0 10px 0 #8b0000, 0 20px 20px black;
            position: relative;
            z-index: 10;
        }
        
        .fake-button:active {
            transform: translateY(5px);
            box-shadow: 0 5px 0 #8b0000, 0 15px 20px black;
        }
        
        .glitch-button {
            background-color: black;
            color: lime;
            padding: 15px;
            margin: 10px 0;
            text-align: center;
            font-size: 25px;
            border: 2px solid lime;
            cursor: pointer;
            font-family: 'Courier New', monospace;
            position: relative;
            overflow: hidden;
        }
        
        .glitch-button:hover {
            background-color: lime;
            color: black;
        }
        
        .popup {
            position: fixed;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            background: black;
            color: red;
            padding: 30px;
            border: 5px solid red;
            z-index: 1000;
            text-align: center;
            font-size: 20px;
            box-shadow: 0 0 500px red;
            animation: popupGlitch 0.2s infinite;
        }
        
        @keyframes popupGlitch {
            0% { left: 49%; top: 50%; }
            25% { left: 51%; top: 49%; }
            50% { left: 48%; top: 51%; }
            75% { left: 52%; top: 48%; }
            100% { left: 50%; top: 50%; }
        }
        
        .hidden {
            display: none;
        }
        
        .counter {
            color: white;
            font-size: 12px;
            text-align: center;
            margin-top: 10px;
            opacity: 0.5;
        }
        
        .glitch-text {
            animation: glitchText 0.1s infinite;
        }
        
        @keyframes glitchText {
            0% { text-shadow: 2px 0 red, -2px 0 blue; }
            25% { text-shadow: -3px 0 red, 3px 0 blue; }
            50% { text-shadow: 4px 0 red, -4px 0 blue; }
            75% { text-shadow: -5px 0 red, 5px 0 blue; }
            100% { text-shadow: 2px 0 red, -2px 0 blue; }
        }
        
        .red-screen {
            background-color: red !important;
            animation: redFlash 0.1s infinite;
        }
        
        @keyframes redFlash {
            0%, 100% { background-color: red; }
            50% { background-color: black; }
        }
        
        .inverted {
            filter: invert(1);
        }
        
        .shake {
            animation: shake 0.1s infinite;
        }
        
        @keyframes shake {
            0% { transform: translate(1px, 1px); }
            10% { transform: translate(-1px, -2px); }
            20% { transform: translate(-3px, 0px); }
            30% { transform: translate(3px, 2px); }
            40% { transform: translate(1px, -1px); }
            50% { transform: translate(-1px, 2px); }
            60% { transform: translate(-3px, 1px); }
            70% { transform: translate(3px, 1px); }
            80% { transform: translate(-1px, -1px); }
            90% { transform: translate(1px, 2px); }
            100% { transform: translate(1px, -2px); }
        }
    </style>
</head>
<body>
    <div class="container" id="mainContainer">
        <!-- Main page (visible initially) -->
        <div id="mainPage">
            <div class="banner">
                ⚡⚡⚡ ATTENTION!!! ⚡⚡⚡
            </div>
            
            <div class="blink">
                🎉 YOU WON IPHONE 16 PRO MAX! 🎉
            </div>
            
            <div class="fake-button" id="prizeButton">
                CLAIM PRIZE ➡️
            </div>
            
            <div class="fake-button" id="resultButton" style="background: linear-gradient(45deg, #0000ff, #6666ff);">
                CHECK RESULT ❓
            </div>
            
            <div class="glitch-button" id="continueButton">
                [CONTINUE]
            </div>
            
            <div style="color: yellow; text-align: center; margin-top: 20px; font-size: 10px;">
                *offer valid only today
            </div>
            
            <div class="counter" id="clickCounter">
                Clicks: 0
            </div>
        </div>
        
        <!-- Red button page (hidden initially) -->
        <div id="redButtonPage" class="hidden">
            <div class="banner" style="background: black; color: red; border-color: red;">
                ⚠️ WARNING ⚠️
            </div>
            
            <div style="color: white; text-align: center; font-size: 24px; margin: 30px 0;">
                DO NOT PRESS UNDER ANY CIRCUMSTANCES
            </div>
            
            <div class="fake-button" id="redButton" style="background: red; box-shadow: 0 10px 0 #8b0000, 0 20px 20px black; font-size: 50px;">
                🔴 DO NOT PRESS 🔴
            </div>
            
            <div class="glitch-button" id="backFromRed">
                [go back]
            </div>
        </div>
        
        <!-- Calibration page (hidden initially) -->
        <div id="calibrationPage" class="hidden">
            <div class="banner" style="background: black; color: lime; border-color: lime; animation: none;">
                SYSTEM ERROR 0x00A7F
            </div>
            
            <div style="color: lime; text-align: center; font-family: 'Courier New'; margin: 20px 0; font-size: 14px;">
                Phone sensors are not working correctly.<br>
                Calibration procedure started.
            </div>
            
            <div class="glitch-button" id="calibrationStep1" style="background: black; color: lime;">
                [STEP 1: Microphone calibration]
            </div>
            
            <div class="glitch-button" id="calibrationStep2" style="background: black; color: lime;">
                [STEP 2: Light sensor calibration]
            </div>
            
            <div class="glitch-button" id="calibrationStep3" style="background: black; color: lime;">
                [STEP 3: Gyroscope calibration]
            </div>
            
            <div style="color: #333; text-align: center; margin-top: 20px; font-size: 10px;">
                Progress: <span id="calibrationProgress">0/3</span>
            </div>
        </div>
        
        <!-- Black screen for effects -->
        <div id="blackScreen" class="hidden" style="position: fixed; top: 0; left: 0; width: 100%; height: 100%; background: black; z-index: 9999;"></div>
    </div>
    
    <!-- Audio elements (will be created via JS) -->
    <script>
        // Audio initialization
        const audioContext = new (window.AudioContext || window.webkitAudioContext)();
        
        // Function to create heartbeat sound
        function createHeartbeat() {
            const oscillator = audioContext.createOscillator();
            const gainNode = audioContext.createGain();
            
            oscillator.type = 'sine';
            oscillator.frequency.value = 60;
            
            gainNode.gain.value = 0.5;
            
            oscillator.connect(gainNode);
            gainNode.connect(audioContext.destination);
            
            // Heartbeat simulation
            const now = audioContext.currentTime;
            gainNode.gain.setValueAtTime(0, now);
            gainNode.gain.linearRampToValueAtTime(0.5, now + 0.05);
            gainNode.gain.linearRampToValueAtTime(0, now + 0.15);
            gainNode.gain.linearRampToValueAtTime(0.5, now + 0.5);
            gainNode.gain.linearRampToValueAtTime(0, now + 0.6);
            
            oscillator.start(now);
            oscillator.stop(now + 1);
        }
        
        // Function to create whisper sound
        function createWhisper() {
            const oscillator = audioContext.createOscillator();
            const gainNode = audioContext.createGain();
            
            oscillator.type = 'sawtooth';
            oscillator.frequency.value = 150;
            
            gainNode.gain.value = 0.1;
            
            oscillator.connect(gainNode);
            gainNode.connect(audioContext.destination);
            
            const now = audioContext.currentTime;
            oscillator.start(now);
            oscillator.stop(now + 2);
            
            // Whisper imitation
            setTimeout(() => {
                if (confirm("Are you still here?")) {
                    // Do nothing
                }
            }, 1000);
        }
        
        // Global variables
        let clickCount = 0;
        let calibrationCount = 0;
        let currentPage = 'main';
        
        // Elements
        const mainPage = document.getElementById('mainPage');
        const redButtonPage = document.getElementById('redButtonPage');
        const calibrationPage = document.getElementById('calibrationPage');
        const clickCounter = document.getElementById('clickCounter');
        const blackScreen = document.getElementById('blackScreen');
        const mainContainer = document.getElementById('mainContainer');
        
        // Function to switch pages
        function showPage(page) {
            mainPage.classList.add('hidden');
            redButtonPage.classList.add('hidden');
            calibrationPage.classList.add('hidden');
            
            if (page === 'main') {
                mainPage.classList.remove('hidden');
            } else if (page === 'red') {
                redButtonPage.classList.remove('hidden');
            } else if (page === 'calibration') {
                calibrationPage.classList.remove('hidden');
            }
            
            currentPage = page;
        }
        
        // Function to update counter
        function updateCounter() {
            clickCount++;
            clickCounter.textContent = `Clicks: ${clickCount}`;
            
            // Every 3 clicks - glitch
            if (clickCount % 3 === 0) {
                triggerGlitch();
            }
            
            // On 5th click - show calibration
            if (clickCount === 5) {
                showPage('calibration');
            }
        }
        
        // Function to trigger glitch
        function triggerGlitch() {
            // Sound glitch
            if (audioContext.state === 'suspended') {
                audioContext.resume();
            }
            
            // Visual glitches
            mainContainer.classList.add('glitch-text');
            document.body.classList.add('inverted');
            
            setTimeout(() => {
                mainContainer.classList.remove('glitch-text');
                document.body.classList.remove('inverted');
            }, 200);
            
            // Random popup
            if (Math.random() > 0.5) {
                alert("⚠️ SYSTEM ERROR ⚠️");
            }
        }
        
        // Function to move button away from cursor
        function moveButton(button) {
            const x = Math.random() * (window.innerWidth - 200);
            const y = Math.random() * (window.innerHeight - 100);
            button.style.position = 'absolute';
            button.style.left = x + 'px';
            button.style.top = y + 'px';
            button.style.zIndex = '9999';
        }
        
        // Function for calibration steps
        function doCalibration(step) {
            calibrationCount++;
            document.getElementById('calibrationProgress').textContent = `${calibrationCount}/3`;
            
            if (step === 1) {
                alert("Blow into the microphone 3 times");
                createWhisper();
            } else if (step === 2) {
                alert("Place the phone screen down and cover with palm for 5 seconds");
                blackScreen.classList.remove('hidden');
                setTimeout(() => {
                    blackScreen.classList.add('hidden');
                    alert("Light sensor calibration complete");
                }, 5000);
            } else if (step === 3) {
                alert("Place the phone on a flat surface and do not move it for 8 seconds");
                setTimeout(() => {
                    alert("Gyroscope calibration complete");
                }, 8000);
            }
            
            if (calibrationCount >= 3) {
                setTimeout(() => {
                    alert("All sensors calibrated. System restored.");
                    showPage('main');
                    calibrationCount = 0;
                    document.getElementById('calibrationProgress').textContent = '0/3';
                }, 9000);
            }
        }
        
        // Main page button handlers
        document.getElementById('prizeButton').addEventListener('click', function(e) {
            e.preventDefault();
            updateCounter();
            
            // Create popup
            const popup = document.createElement('div');
            popup.className = 'popup';
            popup.innerHTML = 'ERROR 404<br>PRIZE NOT FOUND';
            document.body.appendChild(popup);
            
            setTimeout(() => {
                popup.remove();
            }, 2000);
        });
        
        document.getElementById('resultButton').addEventListener('click', function(e) {
            e.preventDefault();
            updateCounter();
            moveButton(this);
        });
        
        document.getElementById('continueButton').addEventListener('click', function(e) {
            e.preventDefault();
            updateCounter();
            showPage('red');
        });
        
        // Red button page handlers
        document.getElementById('redButton').addEventListener('click', function(e) {
            e.preventDefault();
            
            // Black screen
            blackScreen.classList.remove('hidden');
            
            // Heartbeat
            if (audioContext.state === 'suspended') {
                audioContext.resume();
            }
            createHeartbeat();
            
            // Shake effects
            mainContainer.classList.add('shake');
            document.body.classList.add('red-screen');
            
            setTimeout(() => {
                blackScreen.classList.add('hidden');
                mainContainer.classList.remove('shake');
                document.body.classList.remove('red-screen');
                
                // After red button, go to calibration
                showPage('calibration');
            }, 10000);
        });
        
        document.getElementById('backFromRed').addEventListener('click', function(e) {
            e.preventDefault();
            showPage('main');
        });
        
        // Calibration page handlers
        document.getElementById('calibrationStep1').addEventListener('click', function() {
            doCalibration(1);
        });
        
        document.getElementById('calibrationStep2').addEventListener('click', function() {
            doCalibration(2);
        });
        
        document.getElementById('calibrationStep3').addEventListener('click', function() {
            doCalibration(3);
        });
        
        // Background glitches
        setInterval(() => {
            if (Math.random() > 0.7) {
                document.body.style.transform = `rotate(${Math.random() * 0.5 - 0.25}deg)`;
                setTimeout(() => {
                    document.body.style.transform = 'none';
                }, 100);
            }
        }, 5000);
        
        // Prevent tab close attempt
        window.onbeforeunload = function() {
            if (clickCount > 2) {
                return "Site is trying to block this tab. Really want to leave?";
            }
        };
        
        // Block right-click menu
        document.addEventListener('contextmenu', function(e) {
            e.preventDefault();
            alert("Access denied");
        });
        
        // Track page visibility
        document.addEventListener('visibilitychange', function() {
            if (document.hidden && clickCount > 3) {
                setTimeout(() => {
                    alert("I can see you");
                }, 1000);
            }
        });
        
        // Auto trigger calibration after 30 seconds
        setTimeout(() => {
            if (currentPage === 'main') {
                showPage('calibration');
            }
        }, 30000);
        
        // Make result button run away periodically
        setInterval(() => {
            if (currentPage === 'main' && Math.random() > 0.8) {
                const resultBtn = document.getElementById('resultButton');
                if (resultBtn) {
                    moveButton(resultBtn);
                    setTimeout(() => {
                        resultBtn.style.position = 'relative';
                        resultBtn.style.left = '0';
                        resultBtn.style.top = '0';
                    }, 1000);
                }
            }
        }, 10000);
    </script>
</body>
</html>
