---
title: "<% tp.file.title %>"
platform: picoCTF
category: Forensics
difficulty:
status: solved
date: <% tp.file.creation_date("YYYY-MM-DD") %>
tags:
  - ctf
  - picoctf
  - forensics
---

# <% tp.file.title %>

> **Platform:** picoCTF
>
> **Category:** Forensics
>
> **Difficulty:**

<!-- Delete unused sections. Preserve evidence by recording hashes and avoid changing the original artifact when possible. -->

## Challenge

> [Challenge description]

## Evidence

- **Artifact:** `[Filename or archive]`
- **Type:** [Disk image, packet capture, document, memory dump, etc.]
- **SHA-256:** `[Hash]`

```bash
file evidence
sha256sum evidence
```

## Initial Triage

<!-- Record metadata, archive contents, partitions, streams, or protocols that narrow the search. -->

```bash
# Triage commands
```

```text
[Relevant output]
```

## Artifact Analysis

<!-- Follow the evidence from observation to interpretation. Include offsets, timestamps, paths, packet numbers, or metadata fields. -->

[Analysis notes]

<!-- Example: ![Relevant artifact](../../Assets/challenge-name/artifact-detail.png) -->

## Recovery

<!-- Show the exact extraction or decoding steps. -->

```bash
# Recovery commands
```

```text
[Recovered data]
```

## Verification

[Explain how you verified the recovered value against the evidence.]

## Flag

```text
picoCTF{REDACTED}
```

## Lessons Learned

- [A lesson tied to the recovered artifact or forensic technique]

## References

- [File-format, protocol, or tool documentation]
