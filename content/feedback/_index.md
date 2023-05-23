---
title: "Feedback"
---

<h1>  <font size="+3">Feedback </font></h1>

Wenn Sie Fragen haben, Anregungen oder uns etwas anderes mitteilen möchten, benutzen Sie bitte unser Feedbackformular. Wir werden so schnell wie möglich auf Ihre Nachricht antworten!
Contact form:

<br>
<br>

<html >
<script src="https://unpkg.com/tailwindcss-jit-cdn"></script>
<form action={FORM_ENDPOINT} method="POST" target="_blank">
  <div class="mb-3 pt-0">
    <input
      type="text"
      placeholder="Your name"
      name="name"
      class="px-3 py-3 placeholder-gray-400 text-gray-600 relative bg-white bg-white rounded text-sm border-0 shadow outline-none focus:outline-none focus:ring w-full"
      required
    />
  </div>
  <div class="mb-3 pt-0">
    <input
      type="email"
      placeholder="Email"
      name="email"
      class="px-3 py-3 placeholder-gray-400 text-gray-600 relative bg-white bg-white rounded text-sm border-0 shadow outline-none focus:outline-none focus:ring w-full"
      required
    />
  </div>
  <div class="mb-3 pt-0">
    <textarea
      placeholder="Your message"
      name="message"
      class="px-3 py-3 placeholder-gray-400 text-gray-600 relative bg-white bg-white rounded text-sm border-0 shadow outline-none focus:outline-none focus:ring w-full"
      required
    ></textarea>
  </div>
  <div class="mb-3 pt-0">
    <button
      class="bg-blue-500 text-white active:bg-blue-600 font-bold uppercase text-sm px-6 py-3 rounded shadow hover:shadow-lg outline-none focus:outline-none mr-1 mb-1 ease-linear transition-all duration-150"
      type="submit"
    >Send a message</button>
  </div>
</form>
</html >
 
 <h1> Anderes Formular</h1>
<html>
<div class="w-60 center">
   <form accept-charset="UTF-8" action="https://www.formbackend.com/f/{your-identifier}" method="POST">
    <div class="mt2">
      <label for="name" class="db mb1">Name</label>
      <input type="text" id="name" name="name" required>
    </div>
    <div class="mt2">
      <label for="email" class="db mb1">Email</label>
      <input type="email" id="email" name="email" required>
    </div>
    <div class="mt2">
      <label for="message" class="db mb1">Message</label>
      <textarea type="email" id="message" name="message" required></textarea>
    </div>
    <button 
       class="bg-blue-500 text-white active:bg-blue-600 font-bold uppercase text-sm px-6 py-3 rounded shadow hover:shadow-lg outline-none focus:outline-none mr-1 mb-1 ease-linear transition-all duration-150"
       type="submit">Submit</button>
  </form>
</div>
</html>
