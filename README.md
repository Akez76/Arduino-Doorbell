# Wireless Contactless Doorbell using Arduino
A wireless, contactless Arduino-based smart doorbell system using RF communication and IR/ultrasonic sensors to detect visitors and trigger remote alerts with a buzzer and LED. Ideal for hygiene-friendly and remote notification solutions.

# 1.Description
This project demonstrates how to build a *wireless and contactless doorbell* using Arduino and 434 MHz RF modules. The system uses an IR sensor or ultrasonic sensor to detect a person near the door, then transmits a signal to a remote receiver that activates a buzzer and LED — completely eliminating the need to physically press a button.

# 2.Components Used

| Component                             | Quantity |
|---------------------------------------|----------|
| Arduino NANO                          | Main arduino board |
| Arduino UNO 2x                         | Main arduino board №2       |
| Ultrasonic Sensor (or IR Module)      | 1        |
| IR Module (optional)                  | 1        |
| Battery (3.7V 1100mAh or similar)     | 1        |
| 434 MHz RF Transmitter Module         | 1        |
| 434 MHz RF Receiver Module (RX470C)   | 1        |
| LED                                   | 1        |
| 100µF Capacitor                       | 1        |


# 3.How It Works

1. The *transmitter unit* (IR or ultrasonic sensor + RF transmitter) detects when a person approaches the door.
2. It sends a signal via the *434 MHz RF Transmitter*.
3. The *receiver unit* (connected to a second Arduino or to a relay module) receives the signal.
4. Upon receiving, it activates the *buzzer and LED*, notifying the presence of a visitor.

This design allows creating a *wireless doorbell system* with *contactless triggering*, improving hygiene and user convenience.

# 4.Applications
- Wireless home or office doorbell system  
- Touchless entrance notification system  
- Basic remote sensor communication demo

# 5.Photos
- Scheme (https://github.com/Akez76/Arduino-Doorbell/blob/main/Wireless%20Contactless%20Doorbell%20scheme.jpeg)
- (https://github.com/Akez76/Arduino-Doorbell/blob/main/Arduino%20doorbell1.jpeg)
- (https://github.com/Akez76/Arduino-Doorbell/blob/main/Arduino%20doorbell2.jpeg)
- (https://github.com/Akez76/Arduino-Doorbell/blob/main/Arduino%20doorbell3.jpeg)
- (https://github.com/Akez76/Arduino-Doorbell/blob/main/Arduino%20doorbell4.jpeg)
- (https://github.com/Akez76/Arduino-Doorbell/blob/main/Arduino%20doorbell2.jpeg)

# 6.Skills Learned
- Wireless communication using RF (434 MHz) modules  
- IR and ultrasonic proximity sensing  
- Signal decoding and response  
- Relay and output device control
- Remote alert with buzzer and LED
- Built using Arduino UNO R3(2x) and Arduino NANO
- Powered by a 3.7V battery



## Author
Akezhan Kurbanov
