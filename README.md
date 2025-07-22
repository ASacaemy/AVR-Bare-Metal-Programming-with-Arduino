# AVR Bare-Metal Programming with Arduino

Welcome to the **AVR Bare-Metal Programming** repository — a hands-on learning environment to go beyond Arduino’s abstraction layer and dive deep into low-level **register-level programming** on **ATmega328P (Arduino UNO)**.

This project is built for:
- Embedded systems enthusiasts
- Engineers who want to understand what's happening "under the hood" of Arduino
- Learners aiming to transition from hobbyist to professional embedded developer

---

## 🔧 What You'll Learn

✅ Direct register-level manipulation of:
- GPIO (PORTB, DDRB, PINB)
- Timers
- Interrupts
- ADC
- USART
- SPI / I2C (coming soon)

✅ Compare Arduino-style functions (e.g., `digitalWrite()`) vs. **bare-metal** approaches:
```c
PORTB |= (1 << PB0);  // Set PB0 high — 10x faster than digitalWrite()
