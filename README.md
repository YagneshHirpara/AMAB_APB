# AMAB_APB

# AMBA APB2 Protocol - Master and Slave Implementation

This project provides a Verilog implementation of the **AMBA APB2 (Advanced Peripheral Bus)** protocol, including both **Master** and **Slave** modules. The implementation covers two scenarios:
- **With wait states**
- **Without wait states**

## 📌 Overview

AMBA APB2 is a low-power, low-latency peripheral bus widely used in SoC (System-on-Chip) designs. It is primarily used for interfacing low-bandwidth peripherals like UARTs, timers, and GPIOs.

This project demonstrates:
- A custom-designed APB2 Master
- A parameterized APB2 Slave
- Read and Write transactions
- Wait state handling for slave readiness

---
