# She Loves Tutoring Invoice Generator

A modern, interactive invoice generator for tutoring services. Designed with a beautiful pink theme, it is fully editable, supports PDF export, local data persistence, and is mobile-friendly. Built with Tailwind CSS and vanilla JavaScript, with no backend required.

---

## Features

- **Editable Invoice Fields**: Click any field (e.g., names, addresses, amounts) to edit directly in the browser.
- **Add/Remove Services**: Add or remove line items dynamically with a modal dialog.
- **Live Calculations**: Subtotal, discount, tax (0%), and total due are updated automatically.
- **Beautiful Design**: Responsive, modern UI with a pink color scheme using Tailwind CSS.
- **PDF Export**: Export your invoice to a professional-looking PDF with a single click (`Export PDF` button, powered by [html2pdf.js](https://github.com/eKoopmans/html2pdf.js)).
- **Local Storage**: All invoice data and styling preferences are saved in your browser, so your invoice persists across sessions.
- **Context Menu**: Right-click or click on any field to quickly edit or copy its value.
- **Payment Instructions**: Customizable payment section for your bank details.
- **Print-friendly**: Custom CSS ensures the invoice prints as it appears on screen.
- **Mobile Friendly**: Fully responsive layout for all device sizes.
- **Customization Options**: (Styling panel included in code, currently hidden) for color, font size, bold/capitalize/underline.

---

## Getting Started

1. **Download or Clone the Repository**

2. **Open the File**
   - Open `index.html` (or your file) in any modern web browser.

3. **Edit Your Invoice**
   - Click on any field (e.g., "Client Name", "Invoice #", "Bank Name") to edit it.
   - Right-click or click to open the context menu for quick edit or copy.
   - Use the "+ Add Item" button to add more services.
   - Remove services with the "Remove" button next to each row.

4. **Export to PDF**
   - Click the green `Export PDF` button in the bottom-right corner to download a PDF version of your invoice.

5. **Data Persistence**
   - All your changes are saved automatically in your browser's local storage. Reopen the page to continue where you left off.

---

## Customization

- **Styling**: The pink color theme is set via Tailwind and custom CSS. You can adjust colors in the `<style>` section of the HTML.
- **Branding**: Replace "She Loves Tutoring" and contact details with your own.
- **Styling Panel**: A hidden styling panel exists in the code, which can be shown by calling `toggleStylingPanel(true)` in the browser console for advanced customization.

---

## Dependencies

- [Tailwind CSS CDN](https://cdn.tailwindcss.com/)
- [html2pdf.js CDN](https://cdnjs.cloudflare.com/ajax/libs/html2pdf.js/0.10.1/html2pdf.bundle.min.js)

No installation necessary—everything runs in the browser.

---

## File Structure

- **index.html**: The main HTML file containing all markup, styles, and JavaScript.
- **README.md**: This documentation.

---

## Known Limitations

- No backend or cloud saving; data is only stored in your browser.
- Tax is set to 0% by default (edit in the JS if you need tax handling).
- The styling panel is disabled in the UI but can be enabled via code.
- The Gemini API code for description suggestions is included but not active (API key required).

---

## License

MIT License.  
Copyright © 2025 She Loves Tutoring.

---

## Credits

- UI inspired by modern SaaS invoicing tools.
- PDF generation: [html2pdf.js](https://github.com/eKoopmans/html2pdf.js)
- Styles: [Tailwind CSS](https://tailwindcss.com/)

---

**Happy invoicing!**
