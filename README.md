# Tailwind OS

Tailwind is an operating system developed by Strawberry.  
It is designed as a serious systems project focused on correctness, clarity, and long-term maintainability.

This documentation describes the public interfaces, architecture, and behavior of Tailwind OS.  
Internal or experimental components may not be documented here.

## Project Status

- Architecture: x86_64
- Kernel: monolithic
- Boot: successful on real hardware and emulators
- Terminal: functional
- Virtual File System (VFS): implemented
- Userspace: minimal
- Networking: not yet implemented

## Design Goals

- Clear and stable syscall ABI
- Minimal but well-defined kernel interfaces
- Predictable behavior over convenience
- Avoid unnecessary abstraction
- Documentation that reflects actual behavior

## Documentation Scope

This documentation focuses on:
- Public syscalls
- Core kernel subsystems
- ABI guarantees

It does **not** cover:
- Internal helper syscalls
- Debug or temporary interfaces
- Experimental features

Some syscall numbers may exist in the kernel without being documented here.
