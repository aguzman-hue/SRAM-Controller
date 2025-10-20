# SRAM Controller
Ana Isabel Guzmán 16863

La implementación en HDL utiliza módulos jerárquicos en SystemVerilog simulados en Vivado. Se modelan registros con control de escritura (WE), lectura (RE) y reset (rst), junto con un decoder para direccionamiento y un multiplexor para selección de salida. El sistema replica el comportamiento de una memoria SRAM, permitiendo el acceso por dirección y el control del flujo de datos. La simulación se valida con testbenches y waveform, demostrando funcionamiento preciso y modularización escalable.
