<template>
  <div class="contact">
    <h1>Contact Me</h1>
    <h3> I will be glad to hear from you</h3>
      <form v-on:submit.prevent="addInputName">
      <label for="new-name">Input your Name</label>
      <input v-model="newName"
      id="new-name"
      placeholder="your full name">
      </form><br>
          <form v-on:submit.prevent="addText">
      <label for="new-text">Your Text for me</label><br><br>
      <input v-model="newText"
      id="new-Text"
      placeholder="What do you wanna tell me"><br>
      <button>Send Message</button>
      </form>
  </div>
</template>
<script>
export default {
  data () {
  }
}
</script>
