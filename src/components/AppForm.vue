<template>
  <div>
    <form name="contact" method="POST">
      <!--add some things here to make it work with Netlify-->
      <p class="visually-hidden">
        <!--add something here to catch the bots!-->
        <label>Don’t fill this out if you're human: <input name="bot-field" /></label>
      </p>
      <p>
        <label>
          Email
          <input type="text" name="email" />
        </label>
      </p>
      <p>
        <label>
          Message
          <textarea name="message"></textarea>
        </label>
      </p>
      <p>
        <button type="submit">Send me a message!</button>
      </p>
    </form>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
button {
  width: 100%;
}

label,
button {
  margin-top: 20px;
}
</style>