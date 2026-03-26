# Email Form Setup Instructions

## Your Email Configuration
- **Email Address:** archibonghenry38@gmail.com
- **Contact Form Service:** Formspree

## Setup Steps

1. **Visit Formspree** at https://formspree.io/

2. **Create a New Form:**
   - Click "Create Form"
   - Select "Email" as your form type
   - Enter your email: `archibonghenry38@gmail.com`
   - Click "Create"

3. **Get Your Form ID:**
   - After creating the form, Formspree will give you a Form ID (looks like `f_abc123def456`)
   - Copy this ID

4. **Update the HTML:**
   - Open your `index.html` file
   - Find the line: `<form action="https://formspree.io/f/xvgzwnya" method="POST">`
   - Replace `xvgzwnya` with your actual Form ID from step 3
   - Save the file

5. **Verify Your Email:**
   - Users will submit the form
   - An email will be sent to you for verification (from Formspree)
   - Click the verification link to activate form submissions

6. **Start Receiving Messages:**
   - Your form is now live!
   - All messages submitted by users will appear in your inbox at archibonghenry38@gmail.com

## Form Features Configured
✓ Name field (required)
✓ Email field (required)
✓ Message field (required)
✓ Sends directly to your email
✓ Responsive and styled with your existing CSS

## Support
If you need help, visit: https://formspree.io/help
