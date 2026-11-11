# Smart Staircase Lighting Automation on ARM Cortex-M4 (STM32F446RE)

System-level project for **23ECE313 Embedded Systems / 23ECE387 Embedded Systems Laboratory** (B.Tech ECE, Amrita School of Engineering, Bengaluru).

Two IR sensors at opposite ends of a staircase detect a person's **direction of movement**. Going up, the lights turn on in sequence from LED1 to LED5; going down, in reverse order. When the person reaches the other end, all lights switch off. The fifth light is switched through a **relay module**, to show how high-power AC loads would be controlled.

**Hardware:** STM32F446RE, 2 IR sensors, relay module, LEDs, resistors.
**Concepts:** GPIO input sensing, direction detection logic, sequencing with delays, relay interfacing, energy-efficient control.

## Files
- `STM32_Smart_Staircase_Lighting_Report.pdf` — report with aim, theory, circuit, code and results

Team project; team members are listed in the report.
