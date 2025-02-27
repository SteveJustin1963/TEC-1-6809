TEC-1 using 6809 CPU


 Motorola developed the **HD6309**, a **compatible** but **enhanced** version of the **6809**, which includes some features similar to the **6801**, such as additional integrated functions. However, there is **no direct equivalent of the 6801 with 6809 architecture**—so we would still need external peripherals.

---

### **HD6309 – An Enhanced 6809 with Some 6801-like Features**
- https://en.wikipedia.org/wiki/Hitachi_6309
- **Developed by:** Hitachi (licensed from Motorola).
- **Fully compatible with the 6809** (can run all 6809 software).
- **Faster Execution:** 8-bit and 16-bit operations are optimized.
- **Extra Registers:** Includes additional **16-bit registers (W, V)**, improving efficiency.
- **Extended Instructions:** Includes block memory moves, hardware division, and multiplication.
- **Lower Power Consumption:** Improved efficiency over the standard 6809.
- **Native Mode:** Unlocks additional performance (up to 30-50% faster than a 6809 at the same clock speed).

---

### **6809 + 6801 Features**
If we look for a **6809 with integrated peripherals (like the 6801)**, we’ll need **external chips** because:
1. The **6809 and HD6309** have no built-in **serial I/O, timers, or RAM** like the 6801.
2. To match a **6801**, we can combine a **6809 with peripheral chips** like:
   - **MC6821 (PIA - Peripheral Interface Adapter)** for parallel I/O.
   - **MC6850 (ACIA - Asynchronous Communication Interface Adapter)** for serial I/O.
   - **MC6840 (Timer IC)** for timers.
   - **External RAM/ROM** for memory.

---

### **Closest Option: 6309 + External Peripherals**
If we want **6809 performance with 6801-like integration**, so best bet is:
- **HD6309 (for performance, registers, and extended instructions).**
- **External support chips (6821, 6850, RAM/ROM).**
- This gives use the best of **6801-style integration** with **6809 performance.**
- btw the Tandy CoCo 3 has this chip!
