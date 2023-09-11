<template>
  <div>
    <div class = "container">
      <div class = "cards-1 row justify-content-start">
        <div class = "col-6 col-md-4 col-lg-3 col-xxl-3 mb-3">
          <a href = "https://mycopa.ir" target = "_blank" class = "card">
            <img
                class = "card-img-top"
                src = "images/copa.jpg"
                alt = "طراحی سایت"
            />
            <div class = "card-body ">
              <h5 class = "card-title ms-auto me-3 text-center my-md-2">
                Copa
              </h5>
            </div>
          </a>
        </div>
        <div class = "col-6 col-md-4 col-lg-3 col-xxl-3 mb-3">
          <a href = "https://elitefood.ir" target = "_blank" class = "card">
            <img
                class = "card-img-top"
                src = "images/elite.jpg"
                alt = "طراحی سایت"
            />
            <div class = "card-body ">
              <h5 class = "card-title ms-auto me-3 text-center my-md-2">
                Noodelite
              </h5>
            </div>
          </a>
        </div>
        <div class = "col-6 col-md-4 col-lg-3 col-xxl-3 mb-3">
          <a href = "https://shop2.webagent.ir" target = "_blank" class = "card">
            <img
                class = "card-img-top"
                src = "images/shop2.jpg"
                alt = "web design"
            />
            <div class = "card-body ">
              <h5 class = "card-title ms-auto me-3 text-center my-md-2">
                shop
              </h5>
            </div>
          </a>
        </div>
        <div class = "col-6 col-md-4 col-lg-3 col-xxl-3 mb-3">
          <a href = "https://panel.shop2.webagent.ir/panel/login" target = "_blank" class = "card">
            <img
                class = "card-img-top"
                src = "images/shop.panel.jpg"
                alt = "web design"
            />
            <div class = "card-body ">
              <h5 class = "card-title ms-auto me-3 text-center my-md-2">
                Shop panel
              </h5>
            </div>
          </a>
        </div>
        <div class = "col-6 col-md-4 col-lg-3 col-xxl-3 mb-3">
          <a href = "https://res.webagent.ir" target = "_blank" class = "card">
            <img
                class = "card-img-top"
                src = "images/delish.jpg"
                alt = "web design"
            />
            <div class = "card-body ">
              <h5 class = "card-title ms-auto me-3 text-center my-md-2">
                Restaurant
              </h5>
            </div>
          </a>
        </div>
        <div class = "col-6 col-md-4 col-lg-3 col-xxl-3 mb-3">
          <a href = "https://school.webagent.ir" target = "_blank" class = "card">
            <img
                class = "card-img-top"
                src = "images/ielts.jpg"
                alt = "web design"
            />
            <div class = "card-body ">
              <h5 class = "card-title ms-auto me-3 text-center my-md-2">
                School </h5>
            </div>
          </a>
        </div>
        <div class = "col-6 col-md-4 col-lg-3 col-xxl-3 mb-3">
          <a href = "https://highjob.webagent.ir" target = "_blank" class = "card">
            <img
                class = "card-img-top"
                src = "/images/highjob.png"
                alt = "web design"
            />
            <div class = "card-body ">
              <h5 class = "card-title ms-auto me-3 text-center my-md-2">
                Job search </h5>
            </div>
          </a>
        </div>
        <div class = "col-6 col-md-4 col-lg-3 col-xxl-3 mb-3">
          <a href = "https://old.webagent.ir" target = "_blank" class = "card">
            <img
                class = "card-img-top"
                src = "images/old.jpg"
                alt = "web design"/>
            <div class = "card-body">
              <h5 class = "card-title ms-auto me-3 text-center my-md-2">
                Web agent
              </h5>
            </div>
          </a>
        </div>
        <div class = "col-6 col-md-4 col-lg-3 col-xxl-3 mb-3">
          <a href = "https://shop.webagent.ir" target = "_blank" class = "card">
            <img
                    class = "card-img-top"
                    src = "images/shop.jpg"
                    alt = "web design"
            />
            <div class = "card-body ">
              <h5 class = "card-title ms-auto me-3 text-center my-md-2">
                Shop
              </h5>
            </div>
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
    export default {

    };
</script>

<style scoped>
  a,
  a:hover {
    text-decoration: none;
  }

  .cards-1 .card {
    border-radius: 10px !important;
  }

  .card-img-top {
    border-top-left-radius: 10px !important;
    border-top-right-radius: 10px !important;
  }

  .card-body img {
    border-radius: 10px !important;
    height: 80px;
  }

  @media (max-width: 768px) {
    .card-title {
      line-height: 80px;
      margin-bottom: 0 !important;
    }
  }
</style>