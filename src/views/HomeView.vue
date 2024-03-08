<script setup>
import "./HomeView.css";
import CardProduct from "../components/CardProduct.vue";
</script>

<template>
  <main class="container_main">
    <!-- Banner -->
    <div class="banner">
      <div class="spacing">
        <div class="wrapper_text_banner">
          <h1>Dezembro Promocional</h1>
          <p>Produtos selecionados com 33% de desconto</p>
          <button type="button" title="Ver Consoles">Ver Consoles</button>
        </div>
      </div>
    </div>
    <!-- Produtos -->
    <div class="spacing">
      <section class="container_section">
        <div class="content_section">
          <div class="header_section">
            <h3>Star Wars</h3>

            <button type="button" title="Ver tudo">Ver tudo ></button>
          </div>
          <div class="wrapper_cards">
            <CardProduct
              img="/src/assets/image-card.png"
              alt="Produto XYZ"
              name="Produto XYZ"
              :price="60"
            />
            <CardProduct
              img="/src/assets/image-card.png"
              alt="Produto XYZ"
              name="Produto XYZ"
              :price="60"
            />
            <CardProduct
              img="/src/assets/image-card.png"
              alt="Produto XYZ"
              name="Produto XYZ"
              :price="60"
            />
            <CardProduct
              img="/src/assets/image-card.png"
              alt="Produto XYZ"
              name="Produto XYZ"
              :price="60"
            />
            <CardProduct
              img="/src/assets/image-card.png"
              alt="Produto XYZ"
              name="Produto XYZ"
              :price="60"
            />
          </div>
        </div>

        <div class="content_section">
          <div class="header_section">
            <h3>Consoles</h3>

            <button type="button" title="Ver tudo">Ver tudo ></button>
          </div>
          <div class="wrapper_cards">
            <CardProduct
              img="/src/assets/image-card.png"
              alt="Produto XYZ"
              name="Produto XYZ"
              :price="60"
            />
            <CardProduct
              img="/src/assets/image-card.png"
              alt="Produto XYZ"
              name="Produto XYZ"
              :price="60"
            />
            <CardProduct
              img="/src/assets/image-card.png"
              alt="Produto XYZ"
              name="Produto XYZ"
              :price="60"
            />
            <CardProduct
              img="/src/assets/image-card.png"
              alt="Produto XYZ"
              name="Produto XYZ"
              :price="60"
            />
            <CardProduct
              img="/src/assets/image-card.png"
              alt="Produto XYZ"
              name="Produto XYZ"
              :price="60"
            />
          </div>
        </div>

        <div class="content_section">
          <div class="header_section">
            <h3>Diversos</h3>

            <button type="button" title="Ver tudo">Ver tudo ></button>
          </div>
          <div class="wrapper_cards">
            <CardProduct
              img="/src/assets/image-card.png"
              alt="Produto XYZ"
              name="Produto XYZ"
              :price="60"
            />
            <CardProduct
              img="/src/assets/image-card.png"
              alt="Produto XYZ"
              name="Produto XYZ"
              :price="60"
            />
            <CardProduct
              img="/src/assets/image-card.png"
              alt="Produto XYZ"
              name="Produto XYZ"
              :price="60"
            />
            <CardProduct
              img="/src/assets/image-card.png"
              alt="Produto XYZ"
              name="Produto XYZ"
              :price="60"
            />
            <CardProduct
              img="/src/assets/image-card.png"
              alt="Produto XYZ"
              name="Produto XYZ"
              :price="60"
            />
          </div>
        </div>
      </section>
    </div>
  </main>
</template>
