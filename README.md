# 📧 PowerApps Event RSVP Mailer

A low-code Power Platform solution designed to automate bulk email reminders based on user-defined filters. Originally built to streamline Accounts Receivable collections, this app has been repurposed to support event RSVP management across universities, corporate events, and training sessions.

Built with:
- **Power Apps** – for user interaction and selection logic  
- **Power Automate** – to automate personalized email reminders via Outlook  
- **Power BI** – to fetch filtered data dynamically from event or customer datasets  

---

## 🔍 Use Case: Event RSVP Mailer

This version of the app enables event coordinators to:
- Send RSVP reminder emails to attendees
- Filter by **Event Organizer** or **Event Location**
- Preview the list of recipients before sending
- Track responses via integrated datasets

The email template is personalized and sent using the user's Outlook connection via Power Automate.

---

## 🧠 Other Applicable Scenarios

The core logic of this app — **filter data + send automated emails** — makes it reusable for a wide range of business use cases:

### 📌 1. **Accounts Receivable Collection**
- Send automated payment reminders to customers
- Filter by **Accounting Clerk** or **Company Code**

### 📌 2. **HR Follow-up Tool**
- Follow up with employees who haven’t submitted required documents (ID proofs, tax forms, etc.)
- Filter by **HR Executive** or **Employee Department**

### 📌 3. **IT Notifications**
- Notify users of upcoming system outages or mandatory updates
- Filter by **IT Admin** or **Application/Team**

### 📌 4. **Training Completion Reminders**
- Email employees or students who haven’t completed assigned learning modules
- Filter by **Trainer** or **Course Title**

### 📌 5. **School/University Parent Communication**
- Remind parents/students about fee dues, exam schedules, etc.
- Filter by **Teacher** or **Class**

---

## 🔧 Tech Stack

| Platform      | Purpose                                      |
|---------------|----------------------------------------------|
| **Power Apps**     | User interface for selecting organizers/locations and triggering email logic |
| **Power Automate** | Backend logic to fetch data and send Outlook emails |
| **Power BI**       | Source of dynamic RSVP/customer data (can be Excel/SharePoint/SQL/Dataverse) |
| **Microsoft Outlook** | Email platform used via Power Automate connector |
| **Excel (Mock Data)** | Sample dataset used in this GitHub version (replaceable with live data) |


## 📁 Project Structure

powerapps-event-rsvp-mailer/
├── powerapp/
│   └── event_mailer.msapp              # Exported Power App
├── powerautomate/
│   └── send_rsvp_reminder_flow.zip     # Exported Power Automate Flow
├── powerbi/
│   └── event_rsvp_data_sample.pbix     # Sample Power BI report (if built)
├── data/
│   └── event_rsvp_data_sample.csv      # Sample dataset
├── screenshots/
│   └── home_screen.png                 # Images of the UI
│   └── filtering_screen.png
├── README.md
├── LICENSE


