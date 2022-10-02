# Configuration profiles for configuring iOS and MacOS to use encrypted DNS

## Cloudflare

| Profile | Description |
| - | - |
| [Cloudflare](https://github.com/bjartesola/dns/raw/main/cloudflare-signed.mobileconfig) | Configures device to use Cloudflare encrypted DNS|
| [Cloudflare - security](https://github.com/bjartesola/dns/raw/main/cloudflare_security-signed.mobileconfig) | Configures device to use Cloudflare encrypted DNS with malware blocked |
| [Cloudflare - family](https://github.com/bjartesola/dns/raw/main/cloudflare_family-signed.mobileconfig) | Configures device to use Cloudflare encrypted DNS with malware and adult content blocked |

### Switching between **DNS over HTTPS** and **DNS over TLS**

Once the profile is installed, the user can switch between **DNS over HTTPS** and **DNS over TLS** here:

`Settings` &rarr; `General` &rarr; `VPN, DNS & Device Management` &rarr; `DNS`

### More information 

For more information see [Cloudflare documentation.](https://developers.cloudflare.com/1.1.1.1/setup/)