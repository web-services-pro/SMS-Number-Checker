# 📱 Phone Number SMS Analysis Tool

A free, client-side web application that analyzes phone numbers from spreadsheets to determine SMS capability. No server required - runs entirely in your browser!

## 🌐 Live Demo

**[Try it now!](https://yourusername.github.io/phone-sms-analyzer)**

## ✨ Features

- **Upload spreadsheets** (CSV, Excel) via drag-and-drop
- **Analyze phone numbers** for SMS capability
- **Visual results dashboard** with statistics
- **Download analyzed data** in CSV or Excel format
- **100% client-side** - your data never leaves your browser
- **Mobile responsive** design
- **Free to use** - no API keys or accounts required

## 🚀 How to Use

1. **Upload your file** - Drag and drop or click to select your CSV/Excel file
2. **Select phone column** - Choose which column contains your phone numbers
3. **Click Analyze** - Watch as each number is processed
4. **View results** - See statistics and detailed analysis
5. **Download data** - Export your results with new SMS capability columns

## 📊 Analysis Results

The tool adds these columns to your data:

- `phone_is_valid` - Whether the number format is valid
- `phone_formatted` - Standardized E164 format
- `phone_country` - Geographic region
- `phone_carrier` - Carrier information (when available)
- `phone_type` - Line type (Mobile/Landline/etc.)
- `sms_capable` - SMS capability (Yes/No/Possible/Unknown)
- `sms_confidence` - Analysis confidence level
- `phone_error` - Error details for invalid numbers

## 🔒 Privacy & Security

- **No data uploads** - Everything runs in your browser
- **No tracking** - No analytics or cookies
- **No storage** - Files aren't saved on any server
- **Open source** - View the code yourself

## 🛠️ Technical Details

- Pure HTML/CSS/JavaScript
- Uses PapaParse for CSV processing
- Uses SheetJS for Excel file handling
- Client-side phone number validation
- Responsive design with modern UI

## 📝 Supported Formats

- **Input:** CSV, Excel (.xlsx, .xls)
- **Output:** CSV, Excel with analysis columns
- **Phone formats:** US and international numbers

## 🤝 Contributing

Feel free to:
- Report issues
- Suggest features
- Submit pull requests
- Share with others who might find it useful

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🔗 Related Projects

Looking for more advanced features? Check out:
- [Twilio Lookup API](https://www.twilio.com/lookup) for real-time validation
- [Google libphonenumber](https://github.com/google/libphonenumber) for comprehensive parsing

---

**Made with ❤️ for the community | No servers, no tracking, just results**