<script>
export default {
  props: {
    img: String,
    alt: String,
    name: String,
    price: Number,
  },
};
</script>

<template>
  <div class="content_card">
    <img :src="img" :alt="alt" />

    <div class="card_informations">
      <h4 class="name_product">{{ name }}</h4>
      <strong class="price_product">R$ {{ price }}</strong>
      <a href="#" class="view_product">Ver produto</a>
    </div>
  </div>
</template>

<style>
.content_card {
  display: flex;
  flex-direction: column;
  gap: 8px;

  width: 100%;
  max-width: 17.4rem;
}

.card_informations {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  gap: 8px;
}

.card_informations h4 {
  font-size: 1.4rem;
  font-weight: 400;
  color: var(--gray_700);
}

.card_informations strong {
  font-size: 1.4rem;
  font-weight: 700;
  color: var(--gray_700);
}

.card_informations a {
  font-size: 1.4rem;
  font-weight: 700;
  color: var(--blue_200);
}
</style>
