## 🔐 FortifySec™ SP Bash Program

**Author:** [mastercodibaby](https://github.com/mastercodibaby)  
**Version:** 1.0.0  
**License:** MIT LICENSE (Some Rights Reserved)  
**Copyright:** © FortifySec™ SP

---

### 🧩 Overview
This standalone **Bash configuration utility** is designed to load and display secure system configurations in a JSON-like format. It demonstrates principles of encryption, device identity, and basic network parameter setup.

---

### ⚙️ Features
- MAC and Bluetooth address configuration
- IPv4/IPv6 setup
- Firewall rule simulation
- Telemetry toggling
- Hostname and DNS configuration
- SHA-256 encryption with generated SHA-256 key
- Traceroute blocking and fingerprint blocking
- JSON-style formatted system Traceroute

---

### 🚀 Usage
1. Ensure Bash is installed on your system.
2. Save the script as `fortify.sh`.
3. Make it executable:
   ```bash
   chmod +x fortify.sh
   ```
4. Run the script:
   ```bash
   ./fortify.sh
   ```
5. View the generated system configuration and license key.

---

### 📦 Example Output
```json
{
      fortify_sec: {
        status: "Fortified",
        hostname: $hostname,
        ipv4: $ip4,
        firewall: {
          input_policy: "DROP",
          forward_policy: "DROP",
          output_policy: "ACCEPT",
          loopback_allowed: true
        },
        kernel_hardening: {
          icmp_ping_blocked: true,
          ip_forwarding_enabled: false,
          rp_filter_enabled: true
        },
        encryption: {
          method: "SHA-256",
          session_key_sha256: $crypto_key
        }
      }
    }
```
---

## Disclaimer of Liability
THIS SOFTWARE AND ITS DOCUMENTATION ARE PROVIDED **“AS IS”** AND WITHOUT WARRANTIES OF ANY KIND, EITHER EXPRESS OR IMPLIED. THE AUTHOR AND COPYRIGHT HOLDERS OR PUBLISHERS SHALL NOT BE LIABLE FOR ANY DAMAGES, WHETHER DIRECT, INDIRECT, INCIDENTAL, CONSEQUENTIAL, OR OTHERWISE, ARISING FROM THE USE OR INABILITY TO USE THIS SOFTWARE.

By using this program, you agree to take full responsibility for its operation and any resulting effects on systems, data, or networks.
