---
layout: layouts/base.njk
title: Contact
description: Contact YoYo Sitar for bookings.
permalink: /contact/index.html
bodyClass: contact
---
# Contact

<form name="contact" method="POST" data-netlify="true">
  <input type="hidden" name="form-name" value="contact" />

  <p>
    <input type="text" name="name" placeholder="Name" required />
  </p>

  <p>
    <input type="email" name="email" placeholder="Email" required />
  </p>

  <p>
    <textarea name="message" rows="6" placeholder="Message" required></textarea>
  </p>

  <p>
    <button type="submit">Send</button>
  </p>
</form>