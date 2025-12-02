# Simple Newsletter Subscription Form

This project is a basic, standalone HTML webpage designed to capture user subscriptions for a newsletter. It is built using **HTML5 only**, focusing on accessibility and leveraging built-in browser validation features without requiring JavaScript or CSS.

## 🚀 Features

* **HTML5 Structure:** Clear separation of header, form sections, and footer.
* **Email Input Validation:** Uses `type="email"` to ensure a standard email format is entered.
* **Required Fields:** Uses the `required` attribute on the email and consent fields to prevent submission without necessary information.
* **User Preferences:** Includes checkboxes for users to specify content interests.
* **Semantic Elements:** Uses `<form>`, `<section>`, `<label>`, and `<button>` for proper structuring.

## 🛠️ Technology Used

* **HTML5** (HyperText Markup Language)

## 💻 How to Use

1.  **Save the Code:** Copy the entire HTML code and save it as an `.html` file (e.g., `index.html`).
2.  **Open in Browser:** Double-click the saved file to open it in any modern web browser.
3.  **Test Validation:**
    * Try submitting the form without filling in the **Email Address** field—the browser will block the submission and prompt the user.
    * Try submitting the form without checking the **Terms and Conditions** checkbox—the browser will block the submission.
4.  **Form Submission:** When submitted successfully, the form will attempt to send data to the endpoint specified in the `action` attribute (`/subscribe-handler`) using the `POST` method. *Note: Since this is an HTML-only project, this action will result in an error or a blank page unless a server-side script is actually running at that location.*

## ⚠️ Limitations (HTML Only)

This form is intentionally basic and has several limitations due to the HTML-only constraint:

* **No Styling:** The form has no visual styling (colors, fonts, layout) as this requires **CSS**.
* **No Dynamic Interaction:** There is no advanced client-side interactivity (like instantly showing a "Thank You" message) as this requires **JavaScript**.
* **Server Required:** The form data cannot actually be stored or processed without a **server-side scripting language** (like Python, PHP, or Node.js) configured to receive the data sent to the `/subscribe-handler` endpoint. The built-in HTML validation only happens on the client (browser) side.
