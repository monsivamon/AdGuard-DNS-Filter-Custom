# AdGuard DNS Filter for Personal Use

This is a custom AdGuard DNS filter list, created primarily for personal learning and experimentation.
Please note that I am still learning GitHub and filter creation, so this repository may not follow all best practices or produce perfect results.

---

## 📌 Important Notes

- This filter is intended for testing and personal use only.
- I do not guarantee its effectiveness in blocking ads, trackers, or harmful content.
- Use at your own risk. I am not responsible for any issues caused by using this filter.

---

## 🔧 Filter Creation Process

- The filter list is initially generated using the official AdGuard DNS filter compiler.
- After generation, shell scripts are used to clean up and customize the list.
- Customizations include:
  - Filtering out non-existent domains using `massdns`.

Please note: These modifications are unofficial and may reduce the effectiveness of the original filters.

---

## 🔗 How to Use with AdGuard

To use this filter in AdGuard (AdGuard Home, AdGuard DNS, etc.), add the following URL to your custom DNS filter list:

https://raw.githubusercontent.com/monsivamon/AdGuard_DNS_Filter_for_myself/master/Filters/main_filter.txt

---

## 🔄 Update Policy

- This filter is automatically updated every 8 hours using GitHub Actions.
- Each update pulls the latest source rules, verifies domains using massdns, and rebuilds the list.
- Manual edits or updates may also be made at any time during testing or maintenance.

---

## 📝 Credits & Source Projects

This filter includes references, ideas, and in some cases direct rules from the following GPL-licensed projects:

- [AdGuardTeam/AdGuardSDNSFilter](https://github.com/AdguardTeam/AdGuardSDNSFilter) – DNS-based blocking of ads and tracking.
- [Yuki2718/adblock2](https://github.com/Yuki2718/adblock2) – AdGuard/uBlock-compatible filter tailored for Japanese websites.
- [uBlockOrigin/uAssets](https://github.com/uBlockOrigin/uAssets) – Official filter list from the uBlock Origin team.
- [blechschmidt/massdns](https://github.com/blechschmidt/massdns) – High-performance DNS resolver used here to verify domains.
- [brave/adblock-lists](https://github.com/brave/adblock-lists/) – brave-unbreak.txt – Partial unbreak rules sourced from Brave’s adblock lists

I deeply respect the original authors and thank them for their contributions.

---

## ⚖️ License

This project includes components from other repositories licensed under the GNU General Public License v3.0.
Therefore, this repository is also distributed under the **GPL v3** license.
For full terms, please refer to the [LICENSE](./LICENSE) file.

---

## 📝 Additional Credits for Brave Adblock List
This filter also incorporates some rules sourced from Brave’s adblock lists, which are licensed under the Mozilla Public License Version 2.0 (MPL 2.0).
We comply with MPL 2.0 by clearly acknowledging Brave’s original work and providing attribution.
The original source can be found here:
https://github.com/brave/adblock-lists/blob/master/brave-unbreak.txt
For details on MPL 2.0, see https://mozilla.org/MPL/2.0/.

---

Thank you for visiting this repository!  
I hope it may be helpful or inspiring in your own filtering efforts.

