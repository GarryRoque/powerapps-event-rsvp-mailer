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

---

## 📦 Features

- Filter email targets by Event Organizer or Location
- Fetch data dynamically from Power BI datasets
- Personalized Outlook emails using Power Automate
- Exportable and reusable across domains

---

## 📸 Screenshots

![Home Screen](https://github.com/GarryRoque/powerapps-event-rsvp-mailer/blob/main/Screenshots/PowerApps.PNG) 
*Home screen with organizer/location-based mailer options*

![Filtering Screen](https://github.com/GarryRoque/powerapps-event-rsvp-mailer/blob/main/Screenshots/PowerApp2.PNG)  
*Filtering attendees and sending personalized RSVP reminders*

![Outlook Screen](https://github.com/GarryRoque/powerapps-event-rsvp-mailer/blob/main/Screenshots/Mail.PNG)  
*Mails sent to myself for now as we used dummy emails. the mails can go to dynamic emails*
---

## 👤 Author

**Garry Roque Fernandes**  
Business Intelligence Analyst  
📍 Exeter, UK  
📧 garryfernandes2@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/garryfernandes)



---

## 🙌 Contributions & Feedback

Have suggestions or want to use this logic in a new domain? Feel free to fork this repo, open issues, or reach out on LinkedIn.



