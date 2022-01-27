<template>
  <div class="form">
    <h2>get start</h2>
    <form action="post">
      <label for="username">
        <input
          type="text"
          name="username"
          id="username"
          placeholder="username"
          required
        />
      </label>
      <label for="password">
        <input
          type="password"
          name="password"
          id="password"
          placeholder="password"
          required
        />
      </label>
    </form>
  </div>
</template>

<script>
export default {};
</script>

<style>
.form {
  width: 100%;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.5);
  position: fixed;
  top: 0;
  right: 0;
}
</style>
