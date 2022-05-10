<template>
  <div class="hello">
    <div class="overflow-hidden">
      <div class="container-fluid col-xxl-12">
        <div class="row flex-lg-nowrap align-items-center g-5">
          <div
            class="col-lg-12 col-xl-5 text-center text-lg-start pt-lg-5 mt-xl-4"
          >
            <div class="lc-block mb-4">
              <div editable="rich">
                <h1 class="fw-bold display-3">Farmacia Estrella</h1>
              </div>
            </div>

            <div class="lc-block mb-5">
              <div editable="rich">
                <p class="rfs-8">
                  Ofrece los mejores productos para tu salud y bienestar
                </p>
              </div>
            </div>

            <div class="lc-block">
              <div editable="rich">
                <p class="fw-bold">Página en construcción</p>
              </div>
            </div>
          </div>
        </div>
        <!-- /lc-block -->
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
