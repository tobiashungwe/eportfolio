<template>
  <div id="contact">
    <div>
      <h2>Contact me</h2>
      <div class="row">
        <section class="col">
          <form>
          <span>
          <label for="name">Name:</label>
          <input type="text" id="name" name="name" placeholder="Write here your name..">
            </span>
            <span>
          <label for="phone">Telephone number:</label>
          <input type="text" id="phone" name="phone" placeholder="Write here your number..">
            </span>
            <span>
          <label for="email">Email:</label>
          <input type="text" id="email" name="email" placeholder="Write here your email..">
          </span>
            <span>
          <label for="message">:Message</label>
          <textarea name="message" id="message" placeholder="Write here your message.." rows="10" cols="60"></textarea>
          </span>
            <span>
          <input type="submit" value="Send">
          </span>
          </form>
        </section>
        <section class="col">
          <iframe
              src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d1249.2811673505153!2d2.9084354!3d51.2271377!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x47dca8d2d2a5f543%3A0xcb45aaa5f496e43d!2sChaletstraat%207%2C%208400%20Oostende!5e0!3m2!1sen!2sbe!4v1622214990658!5m2!1sen!2sbe"
              width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
        </section>
      </div>
    </div>
  </div>
</template>
