<script>
  const currentYear = new Date().getFullYear();
  const date = currentYear >= 2022 ? '2022' : `2022-${currentYear}`;
</script>

<footer>
  <p>
    <a href="https://github.com/UltiRequiem"
      >Eliaz Bobadilla (a.k.a UltiRequiem) {date}</a
    >
  </p>
</footer>

<style>
  p {
    color: var(--theme-color);
    font-size: 17px;
  }

  footer {
    bottom: 0;
  }
</style>
