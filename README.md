# Ishaq Visualization Studio — GitHub Pages Website

This is a **single-file static website**. All layout, styling and interactive JavaScript are inside `index.html`. This avoids the missing-CSS problem shown in the browser screenshot and makes deployment straightforward.

## Before publishing
1. Open `index.html` in a text editor.
2. At the bottom, find `const CONFIG={email:"shariffcreater@gmail.com",whatsapp:"917995918775"};`
3. Replace the email and WhatsApp number with your actual business contact details. WhatsApp format: country code + number, digits only (India example: 919876543210).
4. Review the service rates and packages in `RATE_DATA`, `ADDON_DATA` and `PACKAGE_DATA` before accepting orders.
5. Replace the studio name if you choose another brand identity.

## Included
- Responsive desktop and mobile layout
- Custom CSS architectural hero illustration
- Service sections for 2D plans, 3D floor plans and interior renders
- India INR / international USD pricing switch
- Interactive quote builder with add/remove service items
- Package selection and urgent-delivery estimate
- Project enquiry form that opens WhatsApp or the visitor's email app
- Print / save rate card as PDF
- Payment, revision, scope and delivery terms

## Publish on GitHub Pages
1. Create a new GitHub repository.
2. Upload `index.html` and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then Save.
6. Wait for the Pages URL to appear in the Pages settings.

## Important limitations
- The enquiry form does not store submissions on a server. It opens WhatsApp or the visitor's email app.
- Google Fonts are loaded online; system fallback fonts are used if unavailable.
- The hero artwork is a CSS illustration, not a real completed project. Add your own verified FOYR project images when you have permission to show them.
- 8K export is offered only where the production workflow can actually supply it.

## Contact details configured
- Email: shariffcreater@gmail.com
- WhatsApp: +91 79959 18775
