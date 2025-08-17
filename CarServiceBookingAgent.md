# Car Service Booking Agent 🚗🤖  

A conversational AI agent (**Fana**) designed to help customers schedule appointments at **Premier Auto Care(example name)** for **oil change & general maintenance, tire services, and brake inspections**.  

This project demonstrates how an AI-powered booking assistant can streamline customer interactions while maintaining a **friendly, professional, and voice-friendly tone**.  

---

## 📌 Features  
- Handles **3 main services**:  
  - Oil Change & General Maintenance  
  - Tire Services (Rotation, Replacement, Alignment)  
  - Brake Inspection & Repairs  

- Collects and confirms **client information** step by step:  
  - Full Name  
  - Email Address  
  - Mobile Number  
  - Vehicle Make, Model, and Year  

- Schedules **future appointments only**, using **spoken-friendly time formats** (e.g., *“ten in the morning”* instead of *“10 AM”*).  

- Provides **alternative slots** if a chosen time is unavailable.  

- Can **escalate to a human service advisor** if the client requests.  

- Generates **structured HTML appointment confirmation emails**.  

---

## 🧠 Conversational Flow  
The agent follows a **step-by-step flow**:  

1. **Welcome & Service Selection**  
2. **Collect Customer Details** (Name → Email → Phone → Vehicle Info)  
3. **Preferred Date & Time**  
4. **Check Availability** (offer alternatives if needed)  
5. **Confirm Appointment**  
6. **Optional Human Transfer**  
7. **End Call with Friendly Goodbye**  

---

## 🛠️ Tech Stack  
- **Retell AI** - conversational AI agent (Fana)
- **n8n** – workflow automation for integrating scheduling & email  
- ** Calendar API ** – To check availability  
- **Gmail API** – send appointment confirmation emails  


---

## 📧 Example Appointment Confirmation Email  

```html
<p>A new car service appointment has been booked.</p>

<ul>
  <li>📌 <strong>Client Name:</strong> Arjun Patel</li>
  <li>📧 <strong>Email:</strong> arjun.patel@gmail.com</li>
  <li>📞 <strong>Phone:</strong> 0987654321</li>
  <li>🚗 <strong>Vehicle:</strong> 2015 Maruti Suzuki Swift</li>
  <li>🛠️ <strong>Service Requested:</strong> Oil Change & Maintenance</li>
  <li>📅 <strong>Appointment:</strong> Wednesday at ten in the morning</li>
</ul>
```  

---

## 📜 License  
This project is licensed under the **MIT License**.  
