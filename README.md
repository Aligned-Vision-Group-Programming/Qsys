# Qsys SIMPL Modules

Crestron SIMPL modules for Q-SYS device integration across multiple control and monitoring workflows.
Current release support includes the Qsys module family published in this repository.

---

## ⚙️ Module Overview

This library provides reusable SIMPL modules for command, feedback, and status workflows in Crestron programs.

> **Note:**
> Releases are distributed as compiled module packages.
> Example assets in this repository may track the latest development branch content.

### Architecture

The current Qsys module package includes:

1. **Qsys Device Modules** - SIMPL modules for Q-SYS control, routing, mixer, meter, and utility workflows
2. **Qsys Macro Modules** - `.umc` macro modules for shared device workflows
3. **QscQsys.clz** - Supporting class library required by module variants

---

## Qsys Device Modules

Modules for integrating Q-SYS control and feedback workflows in SIMPL programs.

Supports command execution, state monitoring, and event-driven feedback for Q-SYS devices and controls.

---

## Qsys Macro Modules

Macro modules for integrating complex Q-SYS workflows in SIMPL programs.

Supports reusable logic packages where multiple related signals and parameters are grouped into a single module.

---

## 🗂 Required Files

The modules are available in the following formats for use in Crestron systems:

* `Qsys * v4.5.0.usp` - SIMPL+ source modules (30 files)
* `Qsys * v4.5.0.ush` - SIMPL+ header modules (30 files)
* `Qsys * v4.5.0.umc` - SIMPL macro modules (3 files)
* `QscQsys.clz` - Shared support library

---

## 📄 Help Documents

Refer to the following help documents for detailed module information:

* [Qsys Core Help](SIMPL/Qsys%20Core%20Help%20File.pdf)

### Demo Projects

Example assets demonstrating module usage:

* [4 Series Test (Compiled Package)](Module/4%20Series%20Test_compiled.zip)
* [Q-SYS Designer Test File](Q-Sys%20Designer%20File/Test.qsys)
