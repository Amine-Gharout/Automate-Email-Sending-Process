# Automated Email Sender  

This Python script automates the task of sending an email using the **smtplib** library. It is simple, efficient, and customizable, allowing users to send plain-text email messages with ease.  

---

## How It Works  

The script leverages the **SMTP (Simple Mail Transfer Protocol)** to send emails. Here's a breakdown of its operation:  
1. **SMTP Server Configuration**:  
   The user provides the SMTP server address, sender's email, recipient's email, and the sender's password.  

2. **Email Composition**:  
   - A subject line and body message are defined.  
   - The email is constructed using the **MIMEMultipart** class for flexibility.  

3. **Secure Connection**:  
   - The script establishes a secure connection using `starttls()` for encryption.  
   - It then logs in with the provided credentials.  

4. **Email Sending**:  
   - The email is sent via the `sendmail()` method.  
