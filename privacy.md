# Privacy Policy

**Last updated:** 1 June 2026

This Privacy Policy explains how **Point1EM Ventures** ("we", "us", "our") collects, uses, stores, and shares information when you use our WhatsApp-based invoice processing service ("the Service"), which integrates with Tally accounting software.

By using the Service, you agree to the practices described below.

---

## 1. Who We Are

The Service is operated by **Point1EM Ventures**, based in **Bengaluru, Karnataka, India**. You can contact us at **veerendra@point1emventures.com**.

---

## 2. Information We Collect

When you interact with our WhatsApp bot, we collect:

- **Your WhatsApp phone number**, which is used to identify you and route replies.
- **Messages you send to the bot**, including text and images such as invoices, receipts, and bills.
- **Metadata** associated with your messages (timestamps, message IDs) provided by the WhatsApp Business Platform.
- **Extracted invoice data** that we derive from the images and documents you send — vendor names, invoice numbers, dates, amounts, GSTINs, line items, and similar fields.
- **Account configuration data** you provide directly to set up the Service, such as your business name, GSTIN, and Tally company configuration details.

We do not collect WhatsApp profile photos, contact lists, location data, or messages you exchange with anyone other than our bot.

---

## 3. How We Use Your Information

We use the information described above to:

- Receive your messages via the WhatsApp Business Platform and reply to you.
- Extract structured data from invoice images using third-party large language model providers (see Section 5).
- Post the extracted data into your TallyPrime instance via the Tally Agent installed on your Windows machine, when you instruct us to.
- Provide you with summaries, confirmations, and review prompts for invoices you have sent.
- Maintain audit trails of which invoices were processed and posted, for your reference.
- Diagnose errors, improve service reliability, and prevent abuse.

We do not use your messages or invoice contents to train AI models.

---

## 4. Legal Basis (DPDP Act, 2023)

We process your personal data on the basis of your consent, given when you begin interacting with the bot. You may withdraw this consent at any time by messaging "STOP" to the bot or by writing to us at the email above. Withdrawal of consent will result in the discontinuation of the Service for you.

We act as a **Data Fiduciary** under the Digital Personal Data Protection Act, 2023, with respect to your personal data.

---

## 5. Who We Share Your Information With

We share information only with the following categories of recipients, each strictly for the purpose of operating the Service:

- **Meta Platforms, Inc.**, as the operator of the WhatsApp Business Platform, for message delivery.
- **Anthropic, PBC**, the provider of the Claude large language model API, which we use to extract structured data from your invoice images. Anthropic processes images and text on our behalf and does not use this data to train its models, per its API terms.
- **Amazon Web Services (AWS)**, for object storage of invoice images in the Asia Pacific (Mumbai) region.
- **Neon, Inc.**, for hosting our Postgres database in the AWS Mumbai region.
- **Upstash, Inc.**, for ephemeral message-deduplication cache.
- **Render Services, Inc.**, for hosting our application server.

We do not sell your personal data. We do not share it with advertisers, marketers, or data brokers.

We may disclose information if required to do so by law, by a valid order from an Indian court or government authority, or to protect our legal rights.

---

## 6. Data Storage and Residency

- Invoice images and extracted data are stored in **AWS Mumbai (ap-south-1)**.
- Database records are stored in **Neon's Mumbai region (AWS ap-south-1)**.
- Application servers may be located outside India; in such cases, your data is processed in transit but persistent storage remains within India.

---

## 7. Data Retention

- **Invoice images**: retained for **90 days** from the date of upload, then automatically deleted.
- **Extracted invoice data** (vendor, amounts, etc.): retained for **7 years** to support audit and statutory record-keeping requirements under Indian tax law. You may request earlier deletion by writing to us, subject to our legal obligations.
- **Account configuration data**: retained for as long as your account is active, and for 90 days after you discontinue the Service.
- **Diagnostic logs**: retained for **30 days**.

---

## 8. Your Rights

Under the DPDP Act, 2023, you have the right to:

- **Access** the personal data we hold about you.
- **Correct or update** inaccurate or incomplete data.
- **Erase** your personal data, subject to legal retention requirements.
- **Withdraw consent** to processing at any time.
- **Nominate** another person to exercise these rights on your behalf in the event of death or incapacity.
- **Lodge a grievance** with us, and subsequently with the Data Protection Board of India if unresolved.

To exercise any of these rights, write to **veerendra@point1emventures.com**. We will respond within 30 days.

---

## 9. Security

We protect your data using:

- HTTPS for all communication between the bot, our servers, and third parties.
- HMAC signature verification on all webhook payloads received from WhatsApp.
- Encryption-at-rest for invoice images (AWS S3 SSE-S3) and database records.
- Access controls limiting which of our team members can access stored data.

No system is fully secure. We will notify you and the Data Protection Board of India of any personal data breach affecting you, in accordance with the DPDP Act.

---

## 10. Children

The Service is intended for use by businesses and their representatives. We do not knowingly collect personal data from individuals under 18 years of age. If you believe a minor has provided data to us, please contact us so we can delete it.

---

## 11. Changes to This Policy

We may update this Privacy Policy from time to time. The "Last updated" date at the top reflects the most recent change. Material changes will be communicated to active users via WhatsApp message.

---

## 12. Contact

For any privacy-related questions, requests, or grievances:

**Point1EM Ventures**
**Email:** veerendra@point1emventures.com
**Address:** Flat 303, Block 5A, Skyline City Apartment, Bengaluru, Karnataka, India

**Grievance Officer:** Prakhar Suhalka
**Email:** prakharsuhalka25@gmail.com
