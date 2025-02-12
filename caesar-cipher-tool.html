# caesar-cipher-tool-



<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Caesar Cipher Encryption & Decryption</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Caesar Cipher Tool</h1>
        <textarea id="inputText" placeholder="Enter your message here..."></textarea>
        <input type="number" id="shiftValue" placeholder="Enter shift value">
        <div>
            <button class="encrypt" onclick="encryptText()">Encrypt</button>
            <button class="decrypt" onclick="decryptText()">Decrypt</button>
        </div>
        <div class="output" id="outputText"></div>
    </div>

    <script src="script.js"></script>
</body>
</html>


Csss 
/* Global body settings */
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background-color: #000; /* Deep black background */
    color: #fff;
    overflow: hidden;
    position: relative;
}

/* Container for the cipher tool */
.container {
    width: 500px;
    padding: 30px;
    background: rgba(0, 0, 0, 0.8);
    border-radius: 10px;
    box-shadow: 0 4px 20px rgba(0, 0, 0, 0.7);
    text-align: center;
    position: relative;
    z-index: 2;
    border: 2px solid #00ff99; /* Neon border */
}

/* Heading style with glowing text */
h1 {
    color: #00ff99;
    font-size: 32px;
    font-family: 'Roboto', sans-serif;
    text-shadow: 0 0 15px rgba(0, 255, 153, 0.7), 0 0 30px rgba(0, 255, 153, 0.5); /* Glowing neon effect */
}

/* Style for input fields */
textarea, input[type="number"] {
    width: 100%;
    margin-bottom: 20px;
    padding: 10px;
    font-size: 16px;
    border-radius: 8px;
    border: 1px solid #333;
    background-color: #222;
    color: #fff;
    font-family: 'Courier New', Courier, monospace;
    transition: 0.3s;
}

textarea:focus, input[type="number"]:focus {
    outline: none;
    border-color: #00ff99;
    box-shadow: 0 0 10px rgba(0, 255, 153, 0.7); /* Focus glow */
}

/* Button styles */
button {
    padding: 12px 25px;
    margin: 10px;
    font-size: 18px;
    color: #fff;
    border: none;
    border-radius: 8px;
    cursor: pointer;
    transition: 0.4s;
    font-family: 'Courier New', Courier, monospace;
    background-color: #00b0ff; /* Cool blue */
}

button.encrypt {
    background-color: #007bff;
}

button.decrypt {
    background-color: #28a745;
}

button:hover {
    transform: scale(1.1); /* Slight zoom on hover */
    box-shadow: 0 0 15px rgba(0, 255, 153, 0.9); /* Hover glow */
}

/* Output text area */
.output {
    margin-top: 20px;
    padding: 15px;
    background-color: #111;
    border: 1px solid #333;
    border-radius: 8px;
    font-size: 16px;
    color: #fff;
    white-space: pre-wrap;
}

/* Animated tech-style background */
body::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-image: url('https://www.transparenttextures.com/patterns/3px-pencil.png'), linear-gradient(45deg, rgba(0, 255, 153, 0.1) 25%, transparent 25%, transparent 50%, rgba(0, 255, 153, 0.1) 50%, transparent 50%, transparent 75%, rgba(0, 255, 153, 0.1) 75%, transparent 100%);
    background-size: 40px 40px, 100% 100%;
    z-index: 1;
    animation: movingGlow 4s linear infinite;
}

/* Moving glowing tech animation */
@keyframes movingGlow {
    0% {
        background-position: 0 0, 0 0;
    }
    100% {
        background-position: 40px 40px, 40px 40px;
    }
}

/* Glowing, pulsating lines that mimic circuit patterns */
@keyframes circuitPulse {
    0% {
        box-shadow: 0 0 40px rgba(0, 255, 153, 0.8);
    }
    50% {
        box-shadow: 0 0 80px rgba(0, 255, 153, 0.9);
    }
    100% {
        box-shadow: 0 0 40px rgba(0, 255, 153, 0.8);
    }
}

/* Container's glowing outline and pulsating effect */
.container::before {
    content: '';
    position: absolute;
    top: -20px;
    left: -20px;
    width: calc(100% + 40px);
    height: calc(100% + 40px);
    background: rgba(0, 255, 153, 0.2);
    border-radius: 10px;
    z-index: -1;
    animation: circuitPulse 1.5s ease-in-out infinite;
}

Js
function caesarCipher(str, shift, isDecrypt = false) {
    if (isDecrypt) shift = -shift;
    const result = [];

    for (let i = 0; i < str.length; i++) {
        const char = str[i];

        if (char.match(/[a-z]/)) {
            const code = ((char.charCodeAt(0) - 97 + shift + 26) % 26) + 97;
            result.push(String.fromCharCode(code));
        } else if (char.match(/[A-Z]/)) {
            const code = ((char.charCodeAt(0) - 65 + shift + 26) % 26) + 65;
            result.push(String.fromCharCode(code));
        } else {
            result.push(char);
        }
    }

    return result.join('');
}

function encryptText() {
    const inputText = document.getElementById('inputText').value;
    const shiftValue = parseInt(document.getElementById('shiftValue').value, 10);

    if (isNaN(shiftValue)) {
        alert('Please enter a valid shift value.');
        return;
    }

    const encryptedText = caesarCipher(inputText, shiftValue);
    document.getElementById('outputText').textContent = `Encrypted: \n${encryptedText}`;
}

function decryptText() {
    const inputText = document.getElementById('inputText').value;
    const shiftValue = parseInt(document.getElementById('shiftValue').value, 10);

    if (isNaN(shiftValue)) {
        alert('Please enter a valid shift value.');
        return;
    }

    const decryptedText = caesarCipher(inputText, shiftValue, true);
    document.getElementById('outputText').textContent = `Decrypted: \n${decryptedText}`;
}
