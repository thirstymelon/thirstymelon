<!-- Minimal header with subtle gradient -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=120&color=gradient&customColorList=12,14,16&section=header&text=Lokesh%20Panditi&fontSize=40&fontColor=86efac&animation=fadeIn" />
</p>

<p align="center">
  <b>Systems Programmer | Embedded Engineer</b>
</p>

<p align="center">
  <sub>Building reliable, efficient software at the hardware-software interface</sub>
</p>

<!-- Minimal divider -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&height=1&color=gradient&customColorList=12" width="60%">
</p>

<br>

## `0x01` About

```asm
; System profile initialization
.section .data
    developer:      .asciz "Lokesh Panditi"
    role:           .asciz "Systems Programmer & Embedded Engineer"
    location:       .asciz "Close to the Metal"
    
.section .text
.global _start
_start:
    ; Core interests (stack-based)
    adr x0, interests
    mov x1, #5
    
interests:
    .asciz "Low-level programming"
    .asciz "Embedded systems"
    .asciz "Operating systems"
    .asciz "Networking fundamentals"
    .asciz "Hardware-software interfaces"
```

I'm a systems programmer focused on low-level software development and embedded systems. My work centers on understanding how systems operate from first principles and building solutions that are efficient, minimal, and predictable.

**Primary Technologies:** `Rust` • `Assembly` | **Target Platforms:** `ARM64` • `ESP32`

<br>

---

## `0x02` Current Work

```rust
// Active development branch
struct CurrentProject {
    name: &'static str,
    description: &'static str,
    tech_stack: [&'static str; 4],
    status: Status,
}

impl CurrentProject {
    const ACTIVE: Self = Self {
        name: "Custom Mesh Network Implementation",
        description: "Building a mesh network for ESP32 from scratch using Rust",
        tech_stack: ["Rust", "ESP32", "Embedded", "Networking"],
        status: Status::InProgress,
    };
}
```

**Custom Mesh Network Implementation**  
Exploring low-level networking, embedded communication protocols, and distributed system design on ESP32 hardware using Rust.

<br>

---

## `0x03` Tech Stack & Tools

### Core Languages
<p>
  <img src="https://img.shields.io/badge/Rust-8BFFC8?style=for-the-badge&logo=rust&logoColor=0A0E27" />
  <img src="https://img.shields.io/badge/Assembly-7DFFAF?style=for-the-badge&logo=assemblyscript&logoColor=0A0E27" />
</p>

### Embedded & Hardware
<p>
  <img src="https://img.shields.io/badge/ESP32-9DFFDB?style=for-the-badge&logo=espressif&logoColor=0A0E27" />
  <img src="https://img.shields.io/badge/Arduino-8BFFC8?style=for-the-badge&logo=arduino&logoColor=0A0E27" />
  <img src="https://img.shields.io/badge/ARM-7DFFAF?style=for-the-badge&logo=arm&logoColor=0A0E27" />
</p>

### Tools & Platforms
<p>
  <img src="https://img.shields.io/badge/Linux-5DCFBF?style=for-the-badge&logo=linux&logoColor=0A0E27" />
  <img src="https://img.shields.io/badge/Git-9DFFDB?style=for-the-badge&logo=git&logoColor=0A0E27" />
  <img src="https://img.shields.io/badge/GitHub-8BFFC8?style=for-the-badge&logo=github&logoColor=0A0E27" />
  <img src="https://img.shields.io/badge/VS_Code-7DFFAF?style=for-the-badge&logo=visualstudiocode&logoColor=0A0E27" />
</p>

### Architecture & Systems
<p>
  <img src="https://img.shields.io/badge/ARM64-5DCFBF?style=for-the-badge&logo=arm&logoColor=0A0E27" />
  <img src="https://img.shields.io/badge/RISC--V-9DFFDB?style=for-the-badge&logo=riscv&logoColor=0A0E27" />
  <img src="https://img.shields.io/badge/Linux-8BFFC8?style=for-the-badge&logo=linux&logoColor=0A0E27" />
  <img src="https://img.shields.io/badge/Bare_Metal-7DFFAF?style=for-the-badge&logoColor=0A0E27" />
</p>

<br>

---

## `0x04` Technical Expertise

```asm
; Expertise domains (bitmask representation)
.equ EMBEDDED,      0b00000001  ; Microcontroller programming
.equ RTOS,          0b00000010  ; Real-time operating systems
.equ PROTOCOLS,     0b00000100  ; I2C, SPI, UART
.equ POWER_OPT,     0b00001000  ; Power optimization
.equ OS_KERNEL,     0b00010000  ; Kernel development
.equ DRIVERS,       0b00100000  ; Device drivers
.equ FILESYSTEMS,   0b01000000  ; File systems
.equ CONCURRENCY,   0b10000000  ; Concurrency primitives

; Combined skillset
mov x0, #0xFF                    ; All domains active
```

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>⚡ Embedded Systems</h3>
      <ul>
        <li>Microcontroller programming</li>
        <li>Real-time operating systems</li>
        <li>Hardware protocols (I2C, SPI, UART)</li>
        <li>Power optimization</li>
        <li>Sensor integration</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>🔬 Operating Systems</h3>
      <ul>
        <li>Kernel development</li>
        <li>Device drivers</li>
        <li>File systems</li>
        <li>Concurrency primitives</li>
        <li>Virtual memory</li>
      </ul>
    </td>
  </tr>
</table>

<br>

---

## `0x05` Development Philosophy

```rust
fn principles() -> [&'static str; 5] {
    [
        "Understand the system",
        "Build from first principles",
        "Break things to learn",
        "Keep it simple and correct",
        "Optimize only when needed",
    ]
}

// Execute principles
fn main() {
    for (index, principle) in principles().iter().enumerate() {
        println!("[0x{:02x}] ✓ {}", index, principle);
    }
}
```

> **"The best way to understand a system is to build it yourself."**

<br>

---

## `0x06` Connect

```asm
; Contact information (memory-mapped I/O style)
.section .rodata
    GITHUB:     .quad 0x0000_GITHUB_BASE      ; thirstymelon
    EMAIL:      .quad 0x0000_EMAIL_BASE       ; thirstymelon.01@gmail.com
    LINKEDIN:   .quad 0x0000_LINKEDIN_BASE    ; lokesh-panditi-123801339
```

<p align="center">
  <a href="https://github.com/thirstymelon">
    <img src="https://img.shields.io/badge/GitHub-9DFFDB?style=for-the-badge&logo=github&logoColor=0A0E27" />
  </a>
  <a href="mailto:thirstymelon.01@gmail.com">
    <img src="https://img.shields.io/badge/Email-8BFFC8?style=for-the-badge&logo=gmail&logoColor=0A0E27" />
  </a>
  <a href="https://www.linkedin.com/in/lokesh-panditi-123801339">
    <img src="https://img.shields.io/badge/LinkedIn-7DFFAF?style=for-the-badge&logo=linkedin&logoColor=0A0E27" />
  </a>
</p>

---

<!-- Minimal footer wave -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=100&color=gradient&customColorList=12,14,16&section=footer" />
</p>

<p align="center">
  <sub>🌱 Building systems close to the metal, one instruction at a time</sub>
</p>

<br>
