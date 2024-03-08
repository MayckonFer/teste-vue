<script></script>

<template>
  <footer class="footer_container">
    <div class="spacing">
      <h5 class="description_footer">
        Desenvolvido por Fulana de Tal {{ new Date().getFullYear() }}
      </h5>
    </div>
  </footer>
</template>

<style>
.footer_container {
  padding: 3.2rem 0;
  box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
}

.description_footer {
  font-size: 1.6rem;
  font-weight: 400;
  color: var(--gray_700);
  text-align: center;
}
</style>
