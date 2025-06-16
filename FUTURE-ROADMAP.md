# AvoNoNags – Future Releases Roadmap

Ideas and goals for upcoming versions of AvoNoNags.  
This file is our open canvas — a place to imagine, plan, and grow.

---

## 🔭 Planned Features (v1.1.0 to v2.0+)

### 1. ✅ Settings Panel (v1.1.0)
Add a user interface in wp-admin where users can:
- Enable/disable WooCommerce notice blocking
- Choose which plugins' notices to allow
- Restore default behavior

### 2. ✅ Notice Allowlist (v1.1.0)
Allow certain notices to show (like license reminders or security updates) by:
- Class name
- Message keyword
- Plugin source

### 3. 🔒 Role-Based Controls (v1.2.0)
Only hide notices for selected roles (e.g., Shop Manager, Editor), but keep them visible for Admins.

### 4. 📃 Log Hidden Notices (v1.2.0)
Create a debug log of notices that were blocked — helpful for devs and troubleshooting.

### 5. 🔘 Toggle Buttons in Toolbar (v1.2.0)
Quick enable/disable “Notice Blocking” directly from the WordPress toolbar.

### 6. 🔄 Auto-disable Marketing/Upgrade Notices (v1.3.0)
Built-in detection of known plugin nags (e.g., Elementor, WPForms, Yoast) and auto-block them.

### 7. 🌐 Multisite Support (v1.4.0)
Enable AvoNoNags network-wide or per site, with network settings panel.

### 8. 🔄 WooCommerce Setup Wizard Skipper (v1.4.0)
Auto-skip WooCommerce’s persistent setup wizard notice on fresh installs.

### 9. 🧩 Dev Hooks + Filters (v1.5.0)
Allow other plugins or themes to hook into AvoNoNags and register notices to block/allow dynamically.

### 10. 🌈 Optional Dashboard Cleaner Mode (v2.0.0)
Go beyond WooCommerce:
- Clean up dashboard widgets
- Remove Welcome Panels
- Optionally suppress update nags

---

## 📅 Timeline Thoughts

- v1.1.0 – Core settings + allowlist
- v1.2.0 – Roles + logging
- v1.3+ – Toolbar and marketing detection
- v2.0.0 – Full Dashboard Zen Mode ✨

---

*If you want to suggest a feature or report an issue, open a GitHub Issue or send a note via avocadoweb.net/contact.*

