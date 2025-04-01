=== Service Cost Calculator with Appointment Booking ===
Contributors: Mikheili Nakeuri
Tags: calculator, construction, cost calculator, service calculator, estimate, appointment booking
Requires at least: 5.0
Tested up to: 6.4
Stable tag: 1.0.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

A comprehensive cost calculator for construction and renovation services with real-time calculations, integrated appointment booking, and no registration required.

== Description ==

The Construction Service Cost Calculator allows clients to estimate the cost of various construction and renovation services instantly, book appointments directly through a multi-step process, and submit inquiries without any registration. This plugin provides a flexible, user-friendly interface for both clients and administrators.

### Key Features

**For Clients:**
* Select from multiple construction services (tile installation, wall plastering, flooring, painting, etc.)
* Calculate costs based on area measurements and service rates in real-time
* Book appointments with available time slots based on your business schedule
* Select preferred dates and times for service consultations or estimates
* Support for multiple unit types (square meters, square feet, hours, items)
* Display proper unit symbols throughout the interface (m², ft², hr, pc)
* Calculate subtotals, tax, and grand totals instantly as selections are made
* Submit estimates and appointments without registration

**For Administrators:**
* Manage services including rates, descriptions, and SVG icons
* Organize services into customizable categories
* Configure units of measurement with proper symbols
* Set currency, tax rates, and other global options
* Configure business hours and availability for appointments
* Review, confirm or reschedule client appointment requests
* View daily, weekly, and monthly appointment schedules
* Send automatic appointment reminders and confirmations
* Generate comprehensive reports for appointments and services
* Review and respond to client submissions
* Generate HTML estimates for sharing
* Import/export services via CSV
* View analytics on popular services and submissions

### Appointment Booking System

The integrated appointment booking system allows you to:

* Set custom business hours for each day of the week
* Define appointment duration and buffer times
* Set maximum concurrent appointments per time slot
* Configure how far in advance bookings can be made
* Automatically prevent double-booking and scheduling conflicts
* Send email confirmations and reminders for appointments
* Allow customers to include special instructions with their bookings
* View all appointments in a calendar or list format
* Generate reports on appointment statistics and availability

### Shortcode Usage

Basic usage:
`[construction_calculator]`

With options:
`[construction_calculator title="Renovation Calculator" category="flooring" theme="blue" columns="2" appointment_enabled="yes"]`

Available attributes:
* title - Custom calculator title
* description - Custom description text
* category - Display services from a specific category only
* services - Display specific services only (comma-separated IDs)
* theme - Color theme (default, blue, orange, dark)
* show_contact_form - Show or hide the contact form (yes/no)
* columns - Number of columns for service display (1-4)
* appointment_enabled - Enable or disable appointment booking step (yes/no)
* appointment_instructions - Custom instructions for the appointment step
* hide_appointment_notes - Hide the appointment notes field (yes/no)

== Installation ==

1. Upload the plugin files to the `/wp-content/plugins/construction-service-calculator` directory, or install the plugin through the WordPress plugins screen directly.
2. Activate the plugin through the 'Plugins' screen in WordPress.
3. Configure your services, categories, and settings through the 'Construction Calculator' menu in the admin area.
4. Set up your availability for appointments in the 'Appointments' section.
5. Use the shortcode `[construction_calculator]` to display the calculator on any page or post.

== Frequently Asked Questions ==

= How do I add a new service? =

Go to Construction Calculator > Services > Add New. Enter the service name, rate, unit type, and category. You can also add an SVG icon and other optional details.

= How do I set up my business hours for appointments? =

Go to Construction Calculator > Appointments > Availability. Here you can set which days of the week you're available and your working hours for each day. You can also set special dates for holidays or exceptional working hours.

= Can clients book appointments outside of my business hours? =

No, the system only shows available time slots based on your business hours, existing appointments, and buffer times. Clients can only select from the available slots that don't conflict with your schedule.

= How do I confirm or reschedule an appointment? =

When a client books an appointment, it will appear in your Construction Calculator > Appointments section with a status of "Pending". You can click on the appointment to view details, then change the status to "Confirmed", "Rescheduled", etc. You can also add notes and choose whether to notify the client of any changes.

= Are there automated notifications for appointments? =

Yes, the system automatically sends:
* Confirmation emails when a client books an appointment
* Status update notifications when you confirm or reschedule
* Reminder emails to clients before their appointment date
* Notification emails to administrators for new bookings

= Can I customize the calculator appearance? =

Yes, you can choose from multiple color themes (default, blue, orange, dark) and customize many aspects through the Settings page. You can also use shortcode parameters to control appearance.

= Does this plugin support multiple currencies? =

Yes, you can set the currency symbol, position, and formatting options in the Settings page.

= Can I export my services data? =

Yes, go to Construction Calculator > Tools to export your services as a CSV file. You can also import services from CSV.

= Can I generate reports on appointments and services? =

Yes, the Appointments section includes comprehensive reporting features to analyze appointment patterns, service popularity, and business performance. You can export these reports as CSV files for further analysis.

== Screenshots ==

1. Front-end calculator with appointment booking
2. Appointment selection step
3. Admin dashboard
4. Service management
5. Appointment calendar view
6. Appointment management
7. Settings page
8. Submissions management

== Changelog ==

= 1.0.0 =
* Initial release with integrated appointment booking system

== Upgrade Notice ==

= 1.0.0 =
Initial release with appointment booking functionality

== Credits ==

Plugin developed by Mikheili Nakeuri.
