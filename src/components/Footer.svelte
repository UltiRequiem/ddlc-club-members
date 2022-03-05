<script lang="ts">
  const currentYear = new Date().getFullYear();
  const date = currentYear >= 2022 ? "2022" : `2022-${currentYear}`;
</script>

<footer>
  <p>
     <a href="https://github.com/UltiRequiem"
      >© {date} Eliaz Bobadilla (a.k.a UltiRequiem)</a
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

  a {
    color: var(--theme-color);
    text-decoration: none;
  }

  a:hover {
    text-decoration: underline;
  }
</style>
