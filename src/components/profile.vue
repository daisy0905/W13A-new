<template>
  <div class="sub-content-grid">
    <h2>ABOUT THE ARTIST</h2>
    <div>
      <img alt="Artist logo" src="../assets/logo.jpg">
    </div>
    <p>
      Eileen Figueroa http://eileenartstudio135.com is a contemporary realist painter who lives and works in Houston, Texas. A native of Barranquitas, Puerto Rico, her colorful paintings pay homage to her homeland. Her distinctive personal style emanates joy and peace and expresses the vibrant spirit and atmosphere of the Caribbean culture.
      Picturesque landscapes, tropical birds and flowers, musical instruments, and farmers tending to their fields are all brought to life with contrasting and harmonious colors and bold compositions. As the artist explains, “I am a story teller and I welcome you to join me on this visual journey.”
    </p>
  </div>
</template>

<script>
export default {
  name: "sub-content"
};
</script>

<style scoped>
.sub-content-grid {
  width: 90%;
  height: 100%;
  display: grid;
}

h2 {
  text-align: left;
  margin-top: 1em;
}

img {
  width: 12vw;
  object-fit: cover;
  align-self: center;
}

p {
  width: 80%;
  text-align: left;
  font-size: 1rem;
  line-height: 1.5em;
}
</style>