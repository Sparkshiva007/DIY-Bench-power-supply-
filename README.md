# DIY-Bench-power-supply-
This project showcases the transformation of a salvaged ATX SMPS (Switch Mode Power Supply) into a reliable and functional bench power supply unit. The design integrates variable voltage and current regulation using potentiometer-based control, making it a versatile tool for electronics prototyping, testing, and development.

## 🔧 Features

- **ATX SMPS Conversion**  
  Repurposed a standard desktop ATX power supply into a reliable lab bench power unit.

- **Adjustable Voltage & Current**  
  Integrated **XL4016 buck converter**, replacing default trimmers with external multi-turn potentiometers for fine control.

- **Digital Voltage & Current Display**  
  Incorporated an **LNN-type digital display module**, widely available online, to show real-time voltage and current output.

- **Thermal Protection**  
  Added a **temperature sensor and op-amp-based comparator** circuit. When internal temperatures exceed a safe limit, a **relay disconnects the output**, preventing thermal damage during prolonged high current delivery.

- **High Current Capability**  
  Designed to deliver up to **10A** from the 12V rail, suitable for powering motors, high-load circuits, and battery charging.

- **Built-in Safety Features**  
  The XL4016 module includes short-circuit protection and overcurrent limiting, with the ATX unit's native protections retained.

---

## 📦 Components Used

- Salvaged **ATX SMPS**
- **XL4016 Buck Converter Module**
- **10k Potentiometers** (for voltage & current adjustment)
- **LNN Digital Display Module** (voltage & current)
- **Op-Amp** (e.g., LM358 or similar)
- **Relay Module**
- **NTC Thermistor** or **LM35** temperature sensor
- **Heatsinks**, cooling fans (from ATX), wiring terminals, casing

---

## 🧰 Applications

- DIY electronics prototyping and circuit testing
- Battery charging with adjustable current limits
- Powering microcontroller projects (Arduino, ESP, STM32, etc.)
- Running small motors or LED arrays under controlled conditions

---

## 🛡 Safety & Reliability

- Ensure proper ventilation and fan operation inside the ATX enclosure
- Use heat-resistant wire and proper terminal blocks for high current
- Place the temperature sensor close to heat-generating components
- Double-check polarity when wiring the buck converter and digital display

---

## 📁 Repository Contents

- `README.md` – This documentation
- `parts_list.txt` – Bill of materials
- `images/` – Build photos and wiring diagrams
- (Optional) `Arduino_display_code/` – If using a microcontroller-based display

---

## 📜 License

This project is open-source under the [MIT License](LICENSE).

---
