# message
leave me a message

## Description

The form is built with HTML and CSS, powered by `Netlify` Platform.

## Demo

```html
<!-- Only add the Attr `netlify` to the form tag. and set method="POST" to the form tag. -->
<form name="contact" method="POST" netlify>
    <div class="form-group">
        <label for="name">Name</label>
        <input type="text" id="name" name="name" required placeholder="Your name">
    </div>

    <div class="form-group">
        <label for="email">Email / WeChat ID</label>
        <input type="text" id="email" name="email" required placeholder="Your email address or WeChat ID">
    </div>

    <div class="form-group">
        <label for="message">Message</label>
        <textarea id="message" name="message" required placeholder="Please write your message here..."></textarea>
    </div>

    <div class="form-group">
        <button type="submit">Send Message</button>
    </div>
</form>
```

Deploy your web page on `Netlify`, enter your project, and enable `Form Submissions` in the `Forms` section. Set your email address in the `Form Notifications` section. Then you will recieve the message in your email.
