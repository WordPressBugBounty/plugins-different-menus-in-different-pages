=== Different Menu in Different Pages – Conditional Menu ===
Contributors: recorp
Tags: conditional menu, different menu, menu visibility, user roles, navigation, multiple menus
Requires at least: 5.1
Tested up to: 6.8.3
Stable tag: 2.4.5
Requires PHP: 5.4
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Easily assign different menus to pages, posts, user roles, devices, and custom URLs using advanced conditional menu visibility rules.

== Description ==

**Different Menu in Different Pages** lets you control menu visibility with flexible conditional rules.  
Display unique navigation menus based on **pages, posts, categories, tags, templates, user roles, devices,** and more — creating a fully personalized user experience.

For example:
- Show one menu on your homepage and a different one on product pages.  
- Display menus only for logged-in users or specific user roles.  
- Assign menus dynamically by URL patterns, post types, or page templates.

### 🎯 Key Features
✓ Show menus to **logged-in**, **logged-out**, or **all** users.  
✓ Restrict menus by **user roles** or exclude certain roles.  
✓ Insert dynamic data in menu items using shortcodes:  
  `{username}`, `{display_name}`, `{first_name}`, `{last_name}`, `{nickname}`, `{email}`, `{avatar}` (with size options).  
✓ Create **unlimited conditional menus** from the settings page.  
✓ Assign menus by **exact URL**, **page ID**, **slug**, or **URL pattern** (`%keyword%`).  
✓ Assign menus to **special pages** (Home, Front Page, Blog, 404, Search).  
✓ Support for **RTL** (right-to-left) layouts.  
✓ Duplicate any existing menu using the **Menu Duplicator** tool.  
✓ Modern AJAX-based interface for fast settings updates.  

---

### 🌟 Pro Features
The **Pro version** includes even more control and flexibility:

✓ Assign menus for **specific devices** (desktop, mobile, tablet) or **operating systems** (Android, iOS).  
✓ Create **multilingual or country-specific** menus (no extra plugins needed).  
✓ Quick **search filter** for settings.  
✓ Assign menus directly from the **post/page editor**.  
✓ **Backup & Restore** menu rules easily.  
✓ Temporarily **disable** a menu without deleting it.  
✓ **Unlimited conditional menus** support.  
✓ **Elementor header/footer** navigation compatibility.

👉 **Upgrade to the Pro version** for advanced functionality at [myrecorp.com](https://myrecorp.com).

---

== Installation ==

1. Upload the `different-menus-in-different-pages` folder to `/wp-content/plugins/`, or install via the WordPress Plugin Installer.  
2. Activate the plugin through **Plugins → Installed Plugins**.  
3. Navigate to **Settings → Different Menus**.  
4. Click **Add Different Menu** and choose one of your existing menus.  
5. Configure your **visibility conditions** (pages, URLs, roles, etc.) and click **Save**.  
6. Visit your site’s frontend to see the new conditional menu in action.

---

== Frequently Asked Questions ==

= What does “conditional menu” mean? =
A conditional menu is displayed only when specific rules are met — such as user roles, page types, or custom URLs.

= How do I assign different menus to specific pages or user roles? =
Go to **Settings → Different Menus → Add Different Menu**.  
Select your existing menu, then choose conditions like page IDs, templates, or user roles under **Visibility Rules**.  
Save to apply the menu to matching conditions.

= Can I show a menu only to logged-in or logged-out users? =
Yes. Choose **Logged In Users** or **Logged Out Users** under visibility rules.

= What shortcodes are available for menu items? =
You can personalize menu items with:
`{username}`, `{display_name}`, `{first_name}`, `{last_name}`, `{nickname}`, `{email}`, `{avatar}` (supports size attributes).

= What extra features does the Pro version include? =
Device-based menus, multilingual menus, backup/restore, search filters, quick assignment from editor, and Elementor header/footer compatibility.

= Where can I find support? =
Visit the plugin’s **[support forum](https://wordpress.org/support/plugin/different-menu-in-different-pages/)** or our website [myrecorp.com](https://myrecorp.com).

---

== Screenshots ==

1. Plugin settings page with conditional menu rules.  
2. Menu item conditions (restrict by role or login status).  
3. “Add Different Menu” popup for rule setup.  
4. Assign by custom URLs, page IDs, or slugs.  
5. Parent category/page condition setup.  
6. Restrict menus by specific user roles.  
7. *(Pro)* Device-based menu assignment.  
8. *(Pro)* Country/language-specific menus.

---

== Changelog ==

= 2.4.3 =
* Minor fixes and performance improvements.

= 2.4.2 =
* Miscellaneous updates and fixes.

= 2.4.1 =
* General improvements.

= 2.4.0 =
* Fixed multiple security vulnerabilities.

= 2.3.2 =
* Fixed tooltip display issues.

= 2.3.1 =
* Resolved pagination errors.

= 2.3.0 =
* Added menu item conditional options.
* Fixed menu duplication and backup errors.

= 2.2.2 =
* Minor bug fixes and updated flag images.

= 2.2.1 =
* Fixed critical issue causing menu mismatch.

= 2.2.0 =
* Added “Custom Links” rule (by URL, page ID, or slug).

= 2.1.7 =
* Increased subpage limit in Pages tab.

= 2.1.6 =
* Added hover URL preview and bug fixes.

= 2.1.4 =
* Fixed notices not closing and template page menu mismatch.

= 2.1.0 =
* Added parent category/page conditional menus.
* Resolved JavaScript conflicts.

= 2.0.2 =
* Removed Freemius framework.

= 1.0.7 =
* Increased limit for different menus.

= 1.0.3 =
* Added Menu Duplicator tool and screenshot.

= 1.0.0 =
* Initial release.

---

== Upgrade Notice ==

= 2.4.0 =
⚠️ **Important Security Fix** — Update immediately to ensure your site’s protection.

= 2.3.0 =
Introduced new conditional menu options and improvements.

= 2.2.0 =
Added “Custom Links” rule for flexible menu targeting.

= 2.1.0 =
Introduced parent category and parent page conditions for better hierarchy control.

= 1.0.0 =
Initial release.

