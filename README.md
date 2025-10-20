# SRAM Controller
Ana Isabel Guzmán 16863


Este proyecto aborda el diseño completo de un controlador de memoria SRAM, partiendo desde la abstracción más básica hasta la construcción de un sistema funcional y escalable. Se inicia con compuertas lógicas simples (AND, OR), se implementan registros con control de escritura (WE) y lectura (RE), y se agrupan en una matriz de celdas direccionables mediante un decoder binario. La arquitectura incluye señales estándar como Di, Do, ADDR, WE, RE y clk, replicando el comportamiento de una memoria SRAM real.

La implementación se realiza en dos plataformas:

Logisim Evolution: Se construye un sistema modular visual que integra subcircuitos reutilizables (memory_cell, decoder, MUX) para formar una matriz de memoria direccionable. El diseño permite simular operaciones de lectura y escritura, validando el funcionamiento mediante interacción directa en el entorno.

Vivado con SystemVerilog: Se modela el mismo sistema en HDL, utilizando módulos jerárquicos que representan registros, decoders y multiplexores. La funcionalidad se verifica mediante testbenches y simulación en waveform, demostrando precisión lógica y control temporal.
