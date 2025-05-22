IDT_Parser.sys ::  Windows Kernel Level Driver for Parsing IDT (Interrupt Descriptor Table) at x86-64 env. Developed entilry in C. (tested at win10)

WP_Disabler.sys::  Windows Kernel Level Driver that Removes Write Protection from Memory pages, so all read-only pages beacome writable (plz note that read-only pages that are protected from write, cannot written at them even in kernel mode, unless before writting, remove this protection, this it what this driver does ). Developed entilry in C for x86-64 env (tested at win10)
