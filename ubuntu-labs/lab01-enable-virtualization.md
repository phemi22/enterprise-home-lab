# Lab 01 — Enable Virtualization on HP Laptop

## Objective

Enable Intel Virtualization Technology (VT-x) in the BIOS to prepare the laptop for Oracle VirtualBox.

## Device Information

* Manufacturer: HP
* Model: HP Laptop 15-ra0xx
* Processor: Intel Celeron N3060
* RAM: 8 GB
* OS: Windows 10 Home Single Language

## Initial Status

Output from `systeminfo` showed:

* VM Monitor Mode Extensions: Yes
* Virtualization Enabled In Firmware: No
* Second Level Address Translation: Yes

## Steps Performed

1. Restarted the laptop.
2. Pressed `Esc` during startup.
3. Opened BIOS Setup using `F10`.
4. Navigated to **System Configuration**.
5. Enabled **Virtualization Technology**.
6. Saved changes and restarted Windows.

## Verification

Checked **Task Manager → Performance → CPU**.

Expected result:

`Virtualization: Enabled`

## Outcome

Virtualization enabled successfully.
