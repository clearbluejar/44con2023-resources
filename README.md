# 44con2023-resources

# Tools

- [Ghidra 10.3.3](https://github.com/NationalSecurityAgency/ghidra/releases/tag/Ghidra_10.3.3_build) 
  - [Install Instructions](https://github.com/NationalSecurityAgency/ghidra/tree/master#install)
- Ghidra Extensions:
  - [PatchDiffCorrelator](https://github.com/clearbluejar/ghidra-patchdiff-correlator/releases)
    - [Install Instructions](https://github.com/clearbluejar/ghidra-patchdiff-correlator#how-do-i-install-it)
  - [ghidra_BinExport]()
- [VS code](https://code.visualstudio.com/download)
  - [VS Code Diff settings.json](vscode/settings.json) (optional)
  - Install VS code [mermaidjs preview](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-mermaid) (optional)
- [ghidra_scripts](ghidra_scripts/)

# Optional VM
- [Download lubuntu VM (~8GB)](https://drive.google.com/file/d/1tP3cu78KJi7O5FdpJ16UbeNrIfzKX4W3/view?usp=sharing)

# Exercise 1 - CVE-2023-21768

- vulnerable (N-1): [afd.sys.10.0.22621.1028](CVE-2023-21768/afd.sys.10.0.22621.1028)
- patched: [afd.sys.10.0.22621.1415](CVE-2023-21768/afd.sys.10.0.22621.1415)
- Ghidra Analyzed Project
  - [CVE-2023-21768.gar](https://github.com/clearbluejar/recon2023-resources/releases/download/v1.0.0/CVE-2023-21768.gar)

# Exercise 2 - CVE-2022-34690

- vulnerable (N-1): [fxsroute.dll.x64.10.0.22000.795](CVE-2022-34690/fxsroute.dll.x64.10.0.22000.795)
- patched: [fxsroute.dll.x64.10.0.22000.856](CVE-2022-34690/fxsroute.dll.x64.10.0.22000.856)
- Ghidra Analyzed Project
  - [CVE-2022-34690.gar](https://github.com/clearbluejar/recon2023-resources/releases/download/v1.0.0/CVE-2022-34690.gar)

# Exercise 3 - CVE-2023-28302

- vulnerable (N-1): [mqqm.dll.x64.10.0.17763.3770](CVE-2023-28302/mqqm.dll.x64.10.0.17763.3770)
- patched: [mqqm.dll.x64.10.0.17763.4252](CVE-2023-28302/mqqm.dll.x64.10.0.17763.4252)
- Ghidra Analyzed Project
  - [CVE-2023-28302.gar](https://github.com/clearbluejar/recon2023-resources/releases/download/v1.0.0/CVE-2023-28302.gar)

# Exercise 4 - CVE-2022-36934

- vulnerable (N-1): [com.whatsapp.2.22.16.11.libwhatsapp.so](CVE-2022-36934/com.whatsapp.2.22.16.11.libwhatsapp.so)
- patched: [com.whatsapp.2.22.16.12.libwhatsapp.so](CVE-2022-36934/com.whatsapp.2.22.16.12.libwhatsapp.so)
- Ghidra Analyzed Project
  - [CVE-2022-36934.gar](https://github.com/clearbluejar/recon2023-resources/releases/download/v1.0.0/CVE-2022-36934.gar)
  - [CVE-2022-36934_2023_06_10.gar](https://github.com/clearbluejar/recon2023-resources/releases/download/v1.0.0/CVE-2022-36934_2023_06_10.gar) (with completed VT session)

# Exercise 5 - CVE-2023-23420 (Bonus)

- vulnerable (N-1): [ntoskrnl.exe.10.0.22621.1344](CVE-2023-23420/ntoskrnl.exe.10.0.22621.1344)
- patched: [ntoskrnl.exe.10.0.22621.1413](CVE-2023-23420/ntoskrnl.exe.10.0.22621.1413)

# Exercise 6 - CVE-2021-24043 (Bonus)

- vulnerable (N-1): [com.whatsapp.2.21.23.1-arm64-v8a.libwhatsapp.so](CVE-2021-24043/com.whatsapp.2.21.23.1-arm64-v8a.libwhatsapp.so)
- patched: [com.whatsapp.2.21.23.2-arm64-v8a.libwhatsapp.so](CVE-2021-24043/com.whatsapp.2.21.23.2-arm64-v8a.libwhatsapp.so)
- Ghidra Analyzed Project
  - [CVE-2021-24043.gar](https://github.com/clearbluejar/recon2023-resources/releases/download/v1.0.0/CVE-2021-24043.gar) 