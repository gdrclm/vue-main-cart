<template>
  <header class="header-container">
    <span class="title">Агрегатор</span>
  </header>
</template>

<script>
export default {
  name: "header-item",
};
</script>

<style lang="scss" scoped>
.header-container {
  max-width: 100%;
  height: 90px;
  margin-bottom: 50px;
  background: #f5f8fe;
  border-radius: 0px 0px 15px 15px;
  display: flex;
  align-items: center;

  span {
    font-size: 24px;
    font-weight: 600;
    padding-left: 40px;
  }
}
@media (max-width: 415px) {
  .header-container {
    justify-content: center;
    align-items: center;
    padding: 0;
    span {
      padding-left: 0;
    }
  }
}
</style>
