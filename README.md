=== Service Cost Calculator with Appointment Booking ===

Contributors: Mikheili Nakeuri  
Tags: calculator, construction, cost calculator, service calculator, estimate, appointment booking  
Requires at least: 5.0  
Tested up to: 6.4  
Stable tag: 1.0.0  
License: GPLv2 or later  
License URI: http://www.gnu.org/licenses/gpl-2.0.html  

A powerful and user-friendly cost calculator for construction and renovation services with real-time pricing, integrated appointment booking, and no registration required.

== Description ==

The **Service Cost Calculator with Appointment Booking** allows clients to instantly estimate the cost of various construction and renovation services, book appointments through an intuitive multi-step process, and submit inquiries—all without needing an account. This plugin provides a seamless experience for both clients and administrators.

### Key Features

#### For Clients:
* Choose from multiple construction services (tile installation, wall plastering, flooring, painting, etc.)
* Get real-time cost estimates based on area measurements and service rates
* Book appointments with available time slots based on your business schedule
* Select preferred dates and times for service consultations
* Support for multiple unit types (m², ft², hr, pcs)
* Instantly calculate subtotals, tax, and grand totals
* Submit estimates and appointments without registration

#### For Administrators:
* Manage services, rates, descriptions, and icons
* Organize services into customizable categories
* Set currency, tax rates, and global options
* Configure business hours and appointment availability
* Review, confirm, or reschedule appointments
* Send automatic appointment reminders and confirmations
* Generate reports on appointments and services
* Import/export services via CSV
* View analytics on service demand and client submissions

### Appointment Booking System
The built-in appointment booking system allows you to:
* Set business hours and availability for each day of the week
* Define appointment durations and buffer times
* Prevent double-booking with automatic scheduling checks
* Send email confirmations and reminders to clients
* Manage appointments via calendar or list view
* Generate reports on appointment trends and availability

### Shortcode Usage

Basic usage: `[construction_calculator]`

With options:  
`[construction_calculator title="Renovation Calculator" category="flooring" theme="blue" columns="2" appointment_enabled="yes"]`

**Available attributes:**
* `title` - Custom calculator title
* `description` - Custom description text
* `category` - Display services from a specific category
* `services` - Display specific services (comma-separated IDs)
* `theme` - Color theme (default, blue, orange, dark)
* `show_contact_form` - Show/hide the contact form (yes/no)
* `columns` - Number of columns for service display (1-4)
* `appointment_enabled` - Enable/disable appointment booking (yes/no)
* `appointment_instructions` - Custom appointment step instructions

== Installation ==

1. Upload the `service-cost-calculator` folder to `/wp-content/plugins/` or install via the WordPress plugin directory.
2. Activate the plugin from the 'Plugins' menu in WordPress.
3. Configure services, categories, and settings in the **Construction Calculator** admin menu.
4. Set up business hours and appointment availability under **Appointments**.
5. Use the `[construction_calculator]` shortcode to display the calculator.

== Frequently Asked Questions ==

= How do I add a new service? =
Navigate to **Construction Calculator > Services > Add New**. Enter the service name, rate, unit type, and category. Optionally, add an icon and description.

= How do I set up business hours for appointments? =
Go to **Construction Calculator > Appointments > Availability** to configure your working hours and set exceptions for holidays.

= Can clients book appointments outside of my business hours? =
No, the system only shows available slots that do not conflict with your schedule.

= How do I manage client appointments? =
Appointments appear under **Construction Calculator > Appointments** as "Pending." You can confirm, reschedule, or cancel them while notifying clients automatically.

= Does the plugin send automated notifications? =
Yes! Clients and admins receive email notifications for:
* New appointment bookings
* Appointment confirmations or reschedules
* Appointment reminders before the scheduled time

= Can I customize the calculator’s appearance? =
Yes! Choose from multiple color themes and adjust layout settings from the admin panel.

= Does this plugin support multiple currencies? =
Yes, you can set your currency symbol and formatting preferences in the settings.

= Can I export service data? =
Yes! Use the **Tools** section to export/import services via CSV.

= Can I generate reports on appointments and services? =
Yes! The **Appointments** section includes reporting features to track service demand, appointment trends, and business performance.

== Screenshots ==

1. Front-end cost calculator with booking options
2. Appointment selection step
3. Admin dashboard overview
4. Service management interface
5. Appointment calendar view
6. Appointment confirmation management
7. Settings page
8. Submission tracking and analytics

== Changelog ==

= 1.0.0 =
* Initial release with integrated appointment booking system

== Upgrade Notice ==

= 1.0.0 =
* First stable version with appointment booking functionality

== Credits ==

Developed by Mikheili Nakeuri.

