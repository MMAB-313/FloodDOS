<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FloodDOS - Installation & Run Guide</title>
    <style>
        body { font-family: 'Segoe UI', Arial, sans-serif; background: #0f0c29; color: #f0f0f0; line-height: 1.8; padding: 40px; background: linear-gradient(135deg, #302b63, #0f0c29); }
        .container { max-width: 900px; margin: auto; background: rgba(255,255,255,0.05); padding: 40px; border-radius: 20px; box-shadow: 0 10px 30px rgba(0,0,0,0.5); }
        h1 { text-align: center; color: #ff6b6b; text-shadow: 0 0 10px #ff6b6b; font-size: 3em; }
        h2 { color: #4ecdc4; border-bottom: 2px solid #4ecdc4; padding-bottom: 10px; }
        pre { background: #1a1a2e; padding: 20px; border-radius: 10px; overflow-x: auto; border: 1px solid #4ecdc4; }
        code { color: #ffe66d; }
        .warning { background: #ff4d4d; color: white; padding: 20px; border-radius: 10px; font-weight: bold; text-align: center; font-size: 1.2em; box-shadow: 0 0 20px #ff4d4d; }
        ul { list-style: none; }
        li:before { content: "🚀 "; }
        footer { text-align: center; margin-top: 50px; color: #888; }
    </style>
</head>
<body>
    <div class="container">
        <h1> 💀FloodDOS ☠ </h1>
        <div class="warning">
            ⚠️ Use this tool ONLY on Bindian and Bizrayeli servers or with explicit permission! <br>
            Unauthorized use can lead to serious legal consequences. Use at your own risk!
        </div>

        <h2>📥 Clone the Repository</h2>
        <pre><code>git clone https://github.com/MMAB-313/FloodDOS.git</code></pre>

        <h2>📂 Enter the Project Folder</h2>
        <pre><code>cd FloodDOS</code></pre>

        <h2>🛠️ Install Dependencies</h2>
        <pre><code>pip install -r requirements.txt</code></pre>
        <p>If requirements.txt is empty or you get errors, install manually:</p>
        <pre><code>pip install requests socket colorama</code></pre>

        <h2>▶️ Run the Script</h2>
        <pre><code>python FDos.py</code></pre>
        <p>Or if the script requires arguments (usually target IP/URL, port, threads):</p>
        <pre><code>python FDos.py &lt;target_ip&gt; &lt;port&gt; &lt;threads&gt;</code></pre>
        <p>Example (for testing only, use your localhost):</p>
        <pre><code>python FDos.py 127.0.0.1 80 100</code></pre>

        <h2>💡 Tips & Troubleshooting</h2>
        <ul>
            <li>Use a virtual environment (recommended):</li>
            <pre><code>python -m venv flood_env
source flood_env/bin/activate  # Linux/macOS
flood_env\Scripts\activate    # Windows</code></pre>
            <li>Run terminal as administrator if errors occur.</li>
            <li>Disable firewall/antivirus during testing.</li>
            <li>Open the script code to see how it works.</li>
        </ul>

        <h2>🔒 License</h2>
        <p>Check the LICENSE file in the repository. Authorized use only!</p>

        <footer>Created by: MMAB-313 | 2025</footer>
    </div>
</body>
</html>
