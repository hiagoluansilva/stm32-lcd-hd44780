# STM32 LCD HD44780 — Display LCD em Modo Paralelo 4-bit

🇧🇷 **Português** | 🇺🇸 [English](#english)

---

## Português

Driver para display LCD HD44780 em modo paralelo 4-bit no STM32F4xx, sem I2C — comunicação direta pelos pinos de dados.

### O que faz
- Inicializa e controla display **LCD HD44780** em modo **4 bits** paralelo
- Implementa funções: `lcd_init()`, `lcd_send_cmd()`, `lcd_send_data()`, `lcd_print()`
- Suporta display 16×2 (2 linhas × 16 caracteres)

### Ligação dos pinos (típica)
| LCD | STM32 |
|---|---|
| RS | PB0 |
| E | PB1 |
| D4–D7 | PB4–PB7 |

### Microcontrolador
STM32F4xx — Atollic TrueSTUDIO

---

## English

HD44780 LCD display driver in 4-bit parallel mode on STM32F4xx, without I2C — direct communication via data pins.

### What it does
- Initializes and controls **LCD HD44780** in **4-bit** parallel mode
- Implements functions: `lcd_init()`, `lcd_send_cmd()`, `lcd_send_data()`, `lcd_print()`
- Supports 16×2 display (2 rows × 16 characters)

### Pin connections (typical)
| LCD | STM32 |
|---|---|
| RS | PB0 |
| E | PB1 |
| D4–D7 | PB4–PB7 |

### MCU
STM32F4xx — Atollic TrueSTUDIO
