# TL;DR - Perl

*- personal notes for Perl scripting language.*

## Installation

### Linux

#### Arch Linux

1. Install Perl interpreter:
    ```sh
    perl -v || pacman -S --needed --noconfirm perl
    ```

### Windows

1. Install [Chocolatey](https://github.com/chocolatey/choco) package manager:
    ```powershell
    try { choco -v } catch { Set-ExecutionPolicy Bypass -Scope Process -Force ; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072 ; Invoke-Expression ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1')) }
    ```
2. Install Perl interpreter:
    ```powershell
    try { perl -v } catch { choco install -fy StrawberryPerl }
    ```

## Resources

- Perl:
    - [Documentation](https://perldoc.perl.org)
