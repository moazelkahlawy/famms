<template>
  <section class="inner_page_head">
    <div class="container_fuild">
      <div class="row">
        <div class="col-md-12">
          <div class="full">
            <h3>{{ title }}</h3>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  props: ["title"],
};
</script>

<style>
.inner_page_head {
  background: #f7444e;
  text-align: center;
  color: #fff;
  padding-top: 50px;
  padding-bottom: 40px;
}

.inner_page_head h3 {
  font-size: 42px;
  font-weight: 800;
}
</style>
