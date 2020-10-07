<template >
  <footer>
    <section class="sign-up">
      <p class="sub-text">For enquiries, kindly send us an email</p>
      <form action="" class="flex-column">
        <input
          type="email"
          v-model="email"
          name="email"
          placeholder="Your email here..."
        />
        <textarea
          name="message"
          placeholder="Message..."
          cols="30"
          rows="10"
          v-model="message"
        ></textarea>
        <input type="submit" value="Send" />
      </form>
    </section>
  </footer>
</template>

<script>
import { Email } from "@/assets/js/smtp.js";
export default {
  data() {
    return {
      email: "",
      message: "",
    };
  },
  methods: {
    async sendEmail() {
      try {
        var message = await Email.send({
          Host: "smtp.gmail.com",
          To: "pddadson@gmail.com",
          From: this.email,
          Subject: "Hello world",
          Body: this.message,
        });
        console.log(message);
      } catch (error) {
        console.log(error);
      }
    },
  },
};
</script>