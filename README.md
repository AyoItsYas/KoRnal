# KoRnal

A kernel written for ESP32 micro controller written in Rust, for an ESP32 embedded within a Laptop or Desktop computer. This kernel is a work in progress and is not yet fully functional. The goal is to have a kernel that can be used to interact with the ESP32 micro controller, and to be able to run Rust code on the ESP32 to work with various magnetic attachments that can be connected to the ESP32. Kornal is not a traditional kernel, it will have a host process running on the host computer that will communicate with the ESP32 micro controller to run code on the ESP32 acting as somewhat like a backend to offload computations and provide extended memory from the host system. This is a solution to the problem of memory and computational limitations of the ESP32 micro controller and the hardware limitations of the host computer.