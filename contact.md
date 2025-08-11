---
layout: default
title: Contact
permalink: /contact/
---

<h2>Contact Me</h2>

<p>Fill out the form below to send me a message.</p>

<style>
  form {
    max-width: 500px;
  }
  form label {
    display: block;
    margin-bottom: 10px;
  }
  form input[type="text"],
  form input[type="email"],
  form textarea {
    width: 100%;
    box-sizing: border-box;
    padding: 8px;
    font-size: 1em;
  }
  form textarea {
    resize: none; /* prevent dragging to resize */
    height: 150px;
  }
  form button {
    padding: 8px 16px;
    font-size: 1em;
    cursor: pointer;
  }
</style>

<form action="https://formspree.io/f/mrbljbpl" method="POST">
  <label>
    Your Name:
    <input type="text" name="name" required>
  </label>

  <label>
    Your Email:
    <input type="email" name="_replyto" required>
  </label>

  <label>
    Message:
    <textarea name="message" required></textarea>
  </label>

  <button type="submit">Send</button>
</form>
