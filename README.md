# stm32-lcd-hd44780

Driver STM32 HAL para display LCD baseado no controlador HITACHI HD44780U via I2C, com suporte a FreeRTOS.

## Descrição

Biblioteca HAL para controle de display LCD alfanumérico HD44780 via barramento I2C. Suporta FreeRTOS e inclui funções de alto nível para escrita, posicionamento, criação de caracteres customizados e suporte a símbolos cirílicos.

## Créditos

Autor original: **Nikita Bulaev (2017)**
Repositório original: `STM32-LCD-HD44780-I2C`

## Hardware suportado

- Controlador: HITACHI HD44780U
- Interface: I2C (via expansor PCF8574)
- Qualquer STM32 com HAL

## Funcionalidades

- Escrita de string e caractere
- Posicionamento de cursor
- Scroll horizontal e vertical
- Caracteres customizados (8 slots)
- Suporte a FreeRTOS (`vTaskDelay`)
- Símbolos cirílicos incluídos como exemplos

## Estrutura

```
STM32-LCD-HD44780-I2C-master/
├── Src/
│   └── lcd_hd44780_i2c.c
├── Inc/
│   └── lcd_hd44780_i2c.h
└── docs/
```

## Dependências

- STM32 HAL (I2C)
- FreeRTOS (opcional)

## IDE

Atollic TrueSTUDIO 9.3 / STM32CubeIDE
