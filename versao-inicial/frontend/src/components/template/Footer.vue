<template>
  <footer class="footer">
    <span>
      Copyright
      <strong>WSM</strong> © 2020
    </span>
  </footer>
</template>

<script>
export default {
  name: "Footer"
};
</script>

<style>
.footer {
  grid-area: footer;
  background-color: rgb(142, 158, 201);
  color: #333;

  display: flex;
  align-items: center;
  justify-content: flex-end;
  padding-right: 10px;
}
</style>
