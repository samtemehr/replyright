# ReplyRight – Write in English Like a Pro

> Write in any language. Send in perfect English.

ReplyRight is a Chrome extension that helps you write professional English messages anywhere on the web – Gmail, LinkedIn, Upwork, WhatsApp, and more. Simply type what you want to say in any language, and ReplyRight will generate a polished English response in your desired tone.

## Features

- **Multi-language Input**: Type in Persian, Spanish, French, or any language – output is always in English
- **Tone Selection**: Choose from Professional, Friendly, or Assertive (Pro only)
- **Works Everywhere**: Gmail, LinkedIn, Upwork, WhatsApp, and any text input field
- **Free Tier**: 5 free messages per day
- **Pro Version**: Unlimited messages for $9/month

## Installation

### Method 1: Load Unpacked (Developer Mode)

1. Download or clone the `replyright` folder to your computer
2. Open Chrome and go to `chrome://extensions`
3. Enable **Developer mode** in the top-right corner
4. Click **Load unpacked**
5. Select the `replyright` folder
6. The extension is now installed!

### Method 2: From Chrome Web Store (Coming Soon)

The extension will be available on the Chrome Web Store soon for easy installation.

## Getting Started

1. **Click the ReplyRight icon** in your browser toolbar to open the popup
2. **Choose your language** (Persian/English) from the toggle
3. **Start writing** – click on any text input field on any website
4. **The ReplyRight button** will appear near the input field
5. **Click the button** to open the panel
6. **Type what you want to say** in any language
7. **Select your tone** (Professional, Friendly, or Assertive)
8. **Click "Generate"** to get your English response
9. **Copy or insert** the generated text

## Pricing

### Free Plan
- 5 messages per day
- Professional and Friendly tones
- Basic features

### Pro Plan ($9/month)
- Unlimited messages
- All tones including Assertive
- Priority support
- No daily limits

## Payment Methods

### International Users
- **USDT / TRX** via TRC-20 network
- Send $9 worth of USDT or TRX to the provided wallet address

### Iran Users
- **Bank Card Transfer** (Card-to-Card)
- Send the equivalent of $9 in Iranian Rials to the provided bank card

## Upgrading to Pro

1. Click the ReplyRight icon in your browser toolbar
2. Click **"Get Pro"** or **"خرید اشتراک Pro"**
3. Choose your payment method (Crypto or Bank Card)
4. Follow the payment instructions
5. Send the payment confirmation email with your User ID
6. You will receive an activation code via email
7. Enter the activation code in the popup to activate Pro

## Activation Code

If you've purchased Pro and received an activation code:

1. Click the ReplyRight icon in your browser toolbar
2. Click **"Enter Activation Code"** or **"وارد کردن کد فعال‌سازی"**
3. Enter your activation code
4. Click **"Activate"** or **"فعال‌سازی"**
5. Your Pro features are now unlocked!

## Troubleshooting

### Button not appearing
- Make sure you're on a supported website (Gmail, LinkedIn, etc.)
- Click on a text input field (textarea, contenteditable div, or input field)
- Refresh the page and try again
- Check that the extension is enabled in `chrome://extensions`

### Persian output instead of English
- The extension always outputs in English regardless of input language
- If you see Persian output, reload the extension in `chrome://extensions`
- Clear your browser cache and try again

### Activation code not working
- Make sure you've entered the code exactly as received (case-sensitive)
- Check that the code matches your User ID
- Contact support at samtemehr@gmail.com if the issue persists

## File Structure

```
replyright/
├── manifest.json       ← Extension manifest
├── content.js          ← Content script (detects text fields)
├── content.css         ← Styles for button and panel
├── popup.html          ← Popup UI
├── popup.js            ← Popup logic
├── background.js       ← Service worker (AI API calls)
├── README.md           ← This file
└── icons/
    ├── icon16.png
    ├── icon48.png
    └── icon128.png
```

## Support

For questions, issues, or support, email: samtemehr@gmail.com

## License

This extension is proprietary software. All rights reserved.

## Version History

- **v2.0.0** – Added bilingual support, improved field detection, fixed positioning
- **v1.0.0** – Initial release
