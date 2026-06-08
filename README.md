```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ESP32 Blink Project</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            max-width: 900px;
            margin: 40px auto;
            padding: 20px;
            line-height: 1.6;
        }

        h1, h2 {
            color: #333;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin: 15px 0;
        }

        table, th, td {
            border: 1px solid #ddd;
        }

        th, td {
            padding: 10px;
            text-align: left;
        }

        pre {
            background: #f4f4f4;
            padding: 15px;
            overflow-x: auto;
        }

        .section {
            margin-bottom: 30px;
        }
    </style>
</head>
<body>

    <h1>ESP32 Blink Project</h1>

    <p>
        A simple ESP32 project that blinks an LED every second using GPIO2.
    </p>

    <div class="section">
        <h2>Hardware Required</h2>

        <table>
            <tr>
                <th>Component</th>
                <th>Quantity</th>
            </tr>
            <tr>
                <td>ESP32 Dev Board</td>
                <td>1</td>
            </tr>
            <tr>
                <td>LED</td>
                <td>1</td>
            </tr>
            <tr>
                <td>220Ω Resistor</td>
                <td>1</td>
            </tr>
            <tr>
                <td>Breadboard</td>
                <td>1</td>
            </tr>
            <tr>
                <td>Jumper Wires</td>
                <td>2</td>
            </tr>
        </table>
    </div>

    <div class="section">
        <h2>Circuit Diagram</h2>

        <pre>
GPIO2 ----[220Ω]----|>|---- GND
                    LED
        </pre>
    </div>

    <div class="section">
        <h2>Connections</h2>

        <table>
            <tr>
                <th>ESP32 Pin</th>
                <th>Connection</th>
            </tr>
            <tr>
                <td>GPIO2</td>
                <td>220Ω Resistor</td>
            </tr>
            <tr>
                <td>Resistor</td>
                <td>LED Anode (+)</td>
            </tr>
            <tr>
                <td>LED Cathode (-)</td>
                <td>GND</td>
            </tr>
        </table>
    </div>

    <div class="section">
        <h2>Working Principle</h2>

        <ol>
            <li>ESP32 sets GPIO2 as an OUTPUT pin.</li>
            <li>LED turns ON for 1 second.</li>
            <li>LED turns OFF for 1 second.</li>
            <li>The cycle repeats continuously.</li>
        </ol>
    </div>

    <div class="section">
        <h2>Author</h2>
        <p><strong>Yashwanth R</strong></p>
        <p>Electronics & Communication Engineering</p>
        <p>AIoT | Embedded Systems | IoT Developer</p>
    </div>

</body>
</html>
```
