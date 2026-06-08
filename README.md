#  ESP32 Blink Project

![ESP32](https://img.shields.io/badge/Board-ESP32-blue)
![Arduino](https://img.shields.io/badge/Platform-Arduino_IDE-green)
![Status](https://img.shields.io/badge/Project-Working-success)

A simple ESP32 project that blinks an LED every second using GPIO2.

---

## Hardware Required

| Component | Quantity |
|------------|-----------|
| ESP32 Dev Board | 1 |
| LED | 1 |
| 220Ω Resistor | 1 |
| Breadboard | 1 |
| Jumper Wires | 2 |

---

## 🔌 Circuit Diagram

```text
            ESP32

          GPIO2
            |
            |
         [220Ω]
            |
            |
           LED
         (+   -)
            |
            |
           GND
```

### Connection Table

| ESP32 Pin | Connection |
|------------|------------|
| GPIO2 | 220Ω Resistor |
| Resistor | LED Anode (+) |
| LED Cathode (-) | GND |

---

## ⚙️ Working Principle

1. ESP32 sets GPIO2 as an OUTPUT pin.
2. LED turns ON for 1 second.
3. LED turns OFF for 1 second.
4. The cycle repeats continuously.

---

##  Arduino Code

```cpp
const int LED_PIN = 2;

void setup() {
  pinMode(LED_PIN, OUTPUT);
}

void loop() {
  digitalWrite(LED_PIN, HIGH);
  delay(1000);

  digitalWrite(LED_PIN, LOW);
  delay(1000);
}
```

---

## 📂 Project Structure

```text
ESP32-Blink/
│
├── blink.ino
├── README.md
└── images/
```

---

## Output

- LED blinks every 1 second.
- Demonstrates basic GPIO control using ESP32.

---

## Author

**Yashwanth R**

  
AIoT | Embedded Systems | IoT Developer

---

 If you found this project useful, give it a star on GitHub.