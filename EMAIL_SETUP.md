# Email Notification Setup Instructions

## ✅ Songs Updated to Your Preferences:
1. **Track 1**: "Summertime in Paris" by Jaden (intro/questions)
2. **Track 2**: "Espresso" by Sabrina Carpenter (analysis/results) 
3. **Track 3**: "Adore You" by Harry Styles (final confirmation)

## 📧 To Receive Email Notifications:

### Step 1: Netlify Form Notifications
1. Go to [Netlify Dashboard](https://app.netlify.com)
2. Find your `blackcoffeex` site → Settings → Forms
3. Click "Form notifications" 
4. Click "Add notification" → "Email notification"
5. Set:
   - **Form**: `coffee-response`
   - **Email**: `ayush18599@gmail.com` 
   - **Subject**: `☕ New Coffee Date Response`

### Step 2: Alternative - ntfy.sh Email Setup
1. Subscribe to: https://ntfy.sh/coffee-simran-ayush2024
2. Or install ntfy app and subscribe to `coffee-simran-ayush2024`
3. This will send push notifications + emails

### Step 3: Test the Form
1. Go to your deployed site: https://blackcoffeex.netlify.app
2. Complete the test yourself with a test name
3. Check if you receive the email

## 🔧 If Emails Still Don't Work:

### Option A: Manual Netlify Deploy
1. Download the updated `index.html` from your GitHub repo
2. Go to Netlify → Deploys → Drag & drop the new file
3. This ensures the latest form code is live

### Option B: Webhook Integration
If Netlify emails don't work, we can set up a webhook to send directly to your email.

## 📝 What You'll Receive:
- **Name**: Simran (or whatever she enters)
- **Date**: Her selected date
- **Time**: Her preferred time slot  
- **Coffee**: Her coffee choice
- **All Quiz Answers**: Every answer she selected
- **Timestamp**: When she completed it

The updated code is now in your GitHub repo and ready to deploy! 🚀