<!-- REVERSIO — GitHub Profile README -->

```
██████╗ ███████╗██╗   ██╗███████╗██████╗ ███████╗██╗ ██████╗
██╔══██╗██╔════╝██║   ██║██╔════╝██╔══██╗██╔════╝██║██╔═══██╗
██████╔╝█████╗  ██║   ██║█████╗  ██████╔╝███████╗██║██║   ██║
██╔══██╗██╔══╝  ╚██╗ ██╔╝██╔══╝  ██╔══██╗╚════██║██║██║   ██║
██║  ██║███████╗ ╚████╔╝ ███████╗██║  ██║███████║██║╚██████╔╝
╚═╝  ╚═╝╚══════╝  ╚═══╝  ╚══════╝╚═╝  ╚═╝╚══════╝╚═╝ ╚═════╝
```

> **Disassemble. Understand. Own the Binary.**

---

### `$ whoami`

iOS security research & binary analysis — hands-on, production-grade, no fluff.

We reverse real iOS apps so you can study what actually happens inside:  
SSL pinning bypass, ARM64 assembly, jailbreak detection removal, and runtime protection stripping.  
Not toy apps. Not sanitized demos. **Live targets.**

---

### `$ ls -la ./toolkit`

```
drwxr-xr-x  ARM64 Assembly        # AArch64 instruction analysis, calling conventions, stack frames
drwxr-xr-x  SSL Pinning Bypass    # Frida hooks + binary patches for NSURLSession, OkHttp, TrustKit, Alamofire
drwxr-xr-x  Jailbreak Detection   # Substrate/Substitute bypass, Cydia file checks, codesign analysis
drwxr-xr-x  Decrypted IPAs        # Ready to load in IDA Pro, Ghidra, or Radare2
drwxr-xr-x  Frida Scripts         # Working scripts against real production targets
-rw-r--r--  50+ Reversed Apps     # And counting
```

---

### `$ cat ./methodology.txt`

Most security resources teach you *what* to run.  
We teach you *why it works* — so you can transfer that knowledge anywhere.

```asm
; Example: certificate validation hook (ARM64)
; bl    _SecTrustEvaluateWithError   ; original call
  mov   w0, #0x1                     ; patch: force trust result = true
  ret                                ; bypass complete ✓
```

---

### `$ frida-trace --what-we-use`

![iOS](https://img.shields.io/badge/iOS-000000?style=flat-square&logo=apple&logoColor=white)
![ARM64](https://img.shields.io/badge/ARM64-AArch64-0078D4?style=flat-square)
![Frida](https://img.shields.io/badge/Frida-Dynamic_Instrumentation-FF4E00?style=flat-square)
![IDA Pro](https://img.shields.io/badge/IDA_Pro-Disassembly-6E4AFF?style=flat-square)
![Ghidra](https://img.shields.io/badge/Ghidra-NSA_SRE-red?style=flat-square)
![Radare2](https://img.shields.io/badge/Radare2-r2-333333?style=flat-square)

---

### `$ cat ./disclaimer`

> All resources are provided strictly for **educational and authorized security research** purposes.  
> Build real skills. Use them responsibly.

---

### `$ open https://reversio.net`

**→ [reversio.net](https://reversio.net)** — Browse the shop. No account required. Instant access.

---

*Reversio · iOS Security Research & Binary Analysis*
