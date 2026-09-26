<!-- REVERSIO — GitHub Profile README -->

<div align="center">

```
██████╗ ███████╗██╗   ██╗███████╗██████╗ ███████╗██╗ ██████╗
██╔══██╗██╔════╝██║   ██║██╔════╝██╔══██╗██╔════╝██║██╔═══██╗
██████╔╝█████╗  ██║   ██║█████╗  ██████╔╝███████╗██║██║   ██║
██╔══██╗██╔══╝  ╚██╗ ██╔╝██╔══╝  ██╔══██╗╚════██║██║██║   ██║
██║  ██║███████╗ ╚████╔╝ ███████╗██║  ██║███████║██║╚██████╔╝
╚═╝  ╚═╝╚══════╝  ╚═══╝  ╚══════╝╚═╝  ╚═╝╚══════╝╚═╝ ╚═════╝
```

### Disassemble. Build. Own the Stack.

</div>

```
$ whoami
```

iOS security research, binary analysis, and full-stack development - hands-on, production-grade, no fluff.

We reverse real iOS apps *and* build the tools around them: SSL pinning bypass, ARM64 assembly, jailbreak detection removal, runtime protection stripping - plus the backends, automation, and native apps that turn research into something usable.

Not toy apps. Not sanitized demos. Live targets, real code.

---

```
$ ls -la ./toolkit
```

```
drwxr-xr-x  ARM64 Assembly        # AArch64 instruction analysis, calling conventions, stack frames
drwxr-xr-x  SSL Pinning Bypass    # Frida hooks + binary patches for NSURLSession, OkHttp, TrustKit, Alamofire
drwxr-xr-x  Jailbreak Detection   # Substrate/Substitute bypass, Cydia file checks, codesign analysis
drwxr-xr-x  Decrypted IPAs        # Ready to load in IDA Pro, Ghidra, or Radare2
drwxr-xr-x  Frida Scripts         # Working scripts against real production targets
-rw-r--r--  60+ Reversed Apps     # And counting
```

---

```
$ ls -la ./dev
```

```
drwxr-xr-x  Swift / Xcode         # Native iOS apps, instrumentation tooling
drwxr-xr-x  Python Automation     # Scripting, pipeline automation, static/dynamic analysis tooling
drwxr-xr-x  PHP Backends          # APIs, dashboards, licensing systems
drwxr-xr-x  HTML / Web            # Landing pages, client panels, lightweight front-ends
-rw-r--r--  Available for hire    # Dev work built with the same rigor as the RE work
```

---

`$ cat ./methodology.txt`

Most resources teach you what to run.
We teach you why it works — and how to build around it — so the knowledge transfers anywhere.

```asm
; Example: certificate validation hook (ARM64)
; bl    _SecTrustEvaluateWithError   ; original call
  mov   w0, #0x1                     ; patch: force trust result = true
  ret                                ; bypass complete ✓
```

---

`$ cat ./disclaimer`

All resources are provided strictly for educational and authorized security research purposes.
Build real skills. Use them responsibly.

---

`$ open https://reversio.net`

→ **[reversio.net](https://reversio.net)** — Browse the shop, or get in touch for dev work. No account required. Instant access.

<div align="center">

**Reversio** · iOS Security Research, Binary Analysis & Development

</div>
