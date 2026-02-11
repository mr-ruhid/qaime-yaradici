🧾 OBir Natürel - Invoice Receipt Generator

A modern, print-ready Invoice Receipt Generator built for OBir Natürel, designed to create clean, professional A4-format receipts directly in the browser.
Developed with HTML, TailwindCSS, and Vanilla JavaScript — no backend required.

🌟 Features

📄 A4 print-optimized layout (ideal for PDF export or direct print)

🔢 Automatic invoice ID generator (stored in localStorage)

🧮 Dynamic product/service table with automatic calculations

💰 Subtotal, VAT, and Grand Total auto-updated in real time

🧾 7 editable item rows with smart input resizing

🧠 Hides empty rows when printing for a cleaner layout

🕒 Auto-fills today’s date on new receipts

🧍‍♂️ Customer & logistics fields included

🖋️ Signature and logo placeholders for branding

🖨️ One-click “Print / Save as PDF” button

🧩 Tech Stack
Technology	Purpose
HTML5	Document structure
TailwindCSS (via CDN)	Clean, responsive styling
JavaScript (Vanilla)	Dynamic calculations and ID management
LocalStorage API	Persisting the last used invoice ID
📁 Project Structure
📁 obir-invoice-generator/
│
├── index.html            # Main application file
├── logo.png              # Company logo (optional)
├── imza.png              # Seller’s signature image (optional)
└── README.md             # Project documentation
⚙️ Usage

Clone or download this repository:

git clone https://github.com/mr-ruhid/obir-invoice-generator.git

Open index.html in your browser.

Fill in invoice details — customer info, items, quantities, prices.

The total values will be calculated automatically.

Click “PDF / Print” to print or save your invoice as a PDF.

Use “Reset & New ID” to generate a new invoice and increment the ID.

🖋️ Customization

Replace logo.png with your company logo (same filename).

Replace imza.png with your signature image for the seller’s signature area.

Update address and contact info in the top-right section of the invoice.

🧠 Notes

The app runs entirely in the browser — no server or database needed.

Invoice IDs are stored locally (localStorage), so each new receipt increments automatically.

For best results, use Google Chrome or Microsoft Edge when printing to PDF (A4 format).

📜 License

This project is open-source and available under the MIT License.

👨‍💻 Author

Ruhid Cavadov
OBir Natürel
📧 ruhidjavadoff@gmail.com
