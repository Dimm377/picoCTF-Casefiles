---
title: "<% tp.file.title %>"
platform: picoCTF
category: Reverse Engineering
difficulty:
status: solved
date: <% tp.file.creation_date("YYYY-MM-DD") %>
tags:
  - ctf
  - picoctf
  - reverse-engineering
---

# <% tp.file.title %>

> **Platform:** picoCTF
>
> **Category:** Reverse Engineering
>
> **Difficulty:**

<!-- Delete unused sections. Prefer named functions, addresses, constants, and observed behavior over generic tool descriptions. -->

## Challenge

> [Challenge description]

## File Information

- **File:** `[Filename]`
- **Type and architecture:** [ELF/PE, x86-64/ARM/etc.]
- **Hash:** `[SHA-256 if useful]`

```bash
file challenge
sha256sum challenge
```

## Initial Behavior

<!-- Run the program safely and record its inputs, outputs, and failure conditions. -->

```text
[Observed program behavior]
```

## Static Analysis

<!-- Record relevant strings, imports, functions, control flow, and constants. -->

[Static-analysis findings]

```c
// Relevant decompiled logic or pseudocode
```

## Dynamic Analysis

<!-- Include breakpoints, register or memory values, and the observation each one supports. -->

```text
[Debugger commands and results]
```

## Key Logic

[Explain how the program validates, transforms, or reconstructs the target value.]

## Solution

```python
# Minimal script if automation is useful
```

```text
[Solution output]
```

## Flag

```text
picoCTF{REDACTED}
```

## Lessons Learned

- [A lesson tied to a function, instruction, or runtime observation]

## References

- [Instruction-set, debugger, or file-format documentation]
