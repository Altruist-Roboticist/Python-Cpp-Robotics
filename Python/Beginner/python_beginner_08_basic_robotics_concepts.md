# Basic Robotics Concepts in Python

In this tutorial, we'll learn some basic robotics concepts using Python. We'll cover how to control servos and read sensors using popular libraries such as `RPi.GPIO` for Raspberry Pi.

## Controlling Servos

Servos are motors that can be controlled to move to a specific angle. Let's see how to control a servo motor using Python and `RPi.GPIO`.

### Prerequisites

- A Raspberry Pi with Raspbian installed
- A servo motor
- Jumper wires

### Installing `RPi.GPIO`

First, we need to install the `RPi.GPIO` library. You can install it using `pip`.

```bash
pip install RPi.GPIO
```

### Example

```python
import RPi.GPIO as GPIO
import time

# Set the GPIO mode
GPIO.setmode(GPIO.BOARD)

# Set the GPIO pin for the servo
servo_pin = 11
GPIO.setup(servo_pin, GPIO.OUT)

# Set the PWM frequency
pwm = GPIO.PWM(servo_pin, 50)  # 50 Hz

# Start the PWM with a duty cycle of 0
pwm.start(0)

def set_angle(angle):
    duty = angle / 18 + 2
    GPIO.output(servo_pin, True)
    pwm.ChangeDutyCycle(duty)
    time.sleep(1)
    GPIO.output(servo_pin, False)
    pwm.ChangeDutyCycle(0)

# Set the servo to 0 degrees
set_angle(0)

# Set the servo to 90 degrees
set_angle(90)

# Set the servo to 180 degrees
set_angle(180)

# Stop the PWM
pwm.stop()
