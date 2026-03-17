# react-contact-form-no-backend
Send forms submission to your email without backend

# Quick Start
Copy and paste this into your HTML file. Replace your-public-key with the key provided in your FormSend dashboard.

# React 
```html
export default function Contact()
{
  return (
      <form action="https://formsend.ct.ws/php/submit.php?apikey=your-public-key" method="POST">
        <input type="email" name="email" required>
        <input type="text" name="message" required>
        <button type="submit">Send</button>
      </form>
  )
}
```

HTML VERSION: 

You can style the form as you see fit.
Live demo link: https://formsend.ct.ws/demo.html

# Why Formsend?
→ No backend code required
→ Works with plain HTML
→ No javascript
→ Fast setup (under a min)
→ Free to start

# Use cases
→ Portfolio
→ Landing pages
→ Static sites (HTML, React, Next.js)
→ MVPs and quick builds


# Next.js
Same as React

# Advanced (Optional)
Redirect after submission (Basic/pro users)
```html
<input type="hidden" name="redirect" value="https://yoursite.com/thankyou">
```

#Contributing

Feel free to add more examples.

# License
MIT
