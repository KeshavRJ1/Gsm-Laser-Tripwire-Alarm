🚨 GSM Laser Tripwire Alarm System

An IoT  based security system designed to provide real  time intrusion detection. When the laser beam is interrupted, the system immediately triggers a buzzer alarm and sends an instant SMS alert to the user's mobile device via a GSM module.

   📋 Table of Contents
   [Project Overview](project  overview)
   [Key Features]  (key  features)
   [Hardware Components](hardware  components)
   [How It Works](how it works)
   [Future Scope](future  scope)
  

      

   🚀 Project Overview
The GSM Laser Tripwire Alarm System is a low  cost, effective security solution for protecting restricted areas. By utilizing an LDR (Light Dependent Resistor) and a laser module, the system creates an invisible (or visible) barrier. Once the integrity of this beam is broken, the microcontroller detects the change in resistance and initiates an automated response protocol.

   ✨ Key Features
     Instant Notification:   Sends an SMS to a predefined phone number immediately upon detection.
     Audible Alert:   Triggers a local buzzer to alert people in the immediate vicinity.
     Low Power Consumption:   Efficient design suitable for battery  operated deployment.
     Reliable Detection:   Uses LDR technology for consistent beam  break sensitivity.

   🛠 Hardware Components
| Component | Purpose |
| :       | :       |
|   Arduino Uno/Nano   | Central Processing Unit |
|   Laser Module   | Creates the tripwire beam |
|   LDR Sensor   | Detects the presence of the laser beam |
|   SIM800L / SIM900 GSM Module   | Handles SMS transmission |
|   Active Buzzer   | Local alarm indicator |
|   Jumper Wires & Breadboard   | Connectivity |
|   9V/12V Power Supply   | System power |
      

   ⚙ How It Works
1.   Calibration:   Upon startup, the LDR continuously receives the laser beam.
2.   Monitoring:   The Arduino reads the analog/digital value from the LDR.
3.   Trigger:   If the beam is broken, the voltage across the LDR changes, signaling an intrusion to the Arduino.
4.   Action:  
       The   Buzzer   is activated to sound an alarm.
       The   GSM Module   sends an "Intrusion Detected!" SMS alert to the programmed number using AT commands.


      
🔮 Future Scope
Camera Integration:   Automatically capture a photo of the intruder upon detection.
Cloud Monitoring:   Log all security events to a Firebase or ThingSpeak dashboard.
Mobile App:   Develop a control panel to arm/disarm the system remotely.

      
👨‍💻 Developed by
Keshav Joshi  

