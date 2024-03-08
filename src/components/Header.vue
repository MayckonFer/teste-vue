<script></script>

<template>
  <header class="header">
    <div class="spacing">
      <div class="container_logo_and_search">
        <div class="wrapper_logo">
          <img src="../assets/logo.png" alt="Alura Geek" />
          <h2>
            Alura
            <span>Geek</span>
          </h2>
        </div>

        <input
          class="input_search_header"
          type="text"
          placeholder="O que deseja encontrar?"
        />
      </div>

      <button type="button" title="Login" class="button_signIn">Login</button>
    </div>
  </header>
</template>

<style>
.header {
  padding: 3.2rem 0;
}

.header > div:first-child {
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.wrapper_logo {
  display: flex;
  align-items: center;
  gap: 5px;

  width: 100%;
  max-width: max-content;
}

.wrapper_logo img {
  width: 5rem;
}

.wrapper_logo h2 {
  font-size: 1.6rem;
  font-weight: 700;
  color: var(--blue_200);
}

.wrapper_logo h2 > span {
  color: var(--gray_700);
}

.container_logo_and_search {
  display: flex;
  align-items: center;
  gap: 3.2rem;

  width: 100%;
}

.input_search_header {
  background-color: var(--gray_100);
  border-radius: 6px;
  border: none;

  width: 22rem;

  padding: 8px;

  font-size: 1.4rem;
  font-weight: 400;
  color: var(--gray_700);
}

.button_signIn {
  background: none;
  border: 1px solid var(--blue_200);

  padding: 1.6rem 7rem;

  font-size: 1.4rem;
  font-weight: 400;
  color: var(--blue_200);
}

@media (max-width: 576px) {
  .header > div:first-child {
    flex-direction: column;
  }

  .container_logo_and_search {
    justify-content: center;
  }
}

@media (max-width: 420px) {
  .container_logo_and_search {
    flex-direction: column;
    gap: 1rem;
  }

  .button_signIn {
    margin-top: 1rem;
  }
}
</style>
