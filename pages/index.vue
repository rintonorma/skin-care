<template>
  <div>
    <FlashNews />
    <HeroCarousel />
    <section>
      <div class="container">
        <BannerCarousel />
      </div>
    </section>
    <section id="sec-product">
      <div class="container">
        <div class="title">
          <h2>New Arrival</h2>
        </div>
        <VCarousel v-bind="CPSettings">
          <div>
            <div class="card figure">
              <div class="label-disc">New</div>
              <div class="ratio ratio-1x1">
                <img class="image-main" src="@/static/img/product/new-shop-54_748da1af-b8f8-4d68-884b-3d798a65386b_large.jpeg?w=360" srcset="@/static/img/product/new-shop-54_748da1af-b8f8-4d68-884b-3d798a65386b_large.jpeg?w=720 2x" alt="Demo image 1">
                <img class="image-hover" src="@/static/img/product/new-shop-59_274bbe12-a19a-41f2-aa82-e071b821fc35_large.jpeg?w=360" srcset="@/static/img/product/new-shop-59_274bbe12-a19a-41f2-aa82-e071b821fc35_large.jpeg?w=720 2x" alt="Demo image 2">
              </div>
              <div class="card-body">
                <h5 class="card-title"><a href="#">Ray Conditioner</a></h5>
                <div class="card-price">Rp322.150</div>
                <div class="card-disc">Rp379.000</div>
                <div class="rating">
                  <div class="stars">
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-empty"></star-icon>
                  </div>
                  <span class="review-no">(41)</span>
                </div>
                <div class="mt-3">
                  <nuxt-link to="" class="btn btn-outline-dark rounded-0">Add to Cart</nuxt-link>
                </div>
              </div>
            </div>
          </div>
          <div>
            <div class="card figure">
              <div class="ratio ratio-1x1">
                <img class="image-main" src="@/static/img/product/new-shop-56_large.jpeg?w=360" srcset="@/static/img/product/new-shop-56_large.jpeg?w=720 2x" alt="Demo image 1">
                <img class="image-hover" src="@/static/img/product/new-shop-53_large.jpeg?w=360" srcset="@/static/img/product/new-shop-53_large.jpeg?w=720 2x" alt="Demo image 2">
                </div>
                <div class="card-body">
                <h5 class="card-title"><a href="#">Alan Night Cream</a></h5>
                <div class="card-price">Rp322.150</div>
                <div class="card-disc">Rp379.000</div>
                <div class="rating">
                  <div class="stars">
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-empty"></star-icon>
                  </div>
                  <span class="review-no">(41)</span>
                </div>
                <div class="mt-3">
                  <div class="text-secondary">Habis</div>
                </div>
              </div>
            </div>
          </div>
          <div>
            <div class="card figure">
              <div class="ratio ratio-1x1">
                <img class="image-main" src="@/static/img/product/new-shop-55_large.jpeg?w=360" srcset="@/static/img/product/new-shop-55_large.jpeg?w=720 2x" alt="Demo image 1">
                <img class="image-hover" src="@/static/img/product/new-shop-82_large.jpeg?w=360" srcset="@/static/img/product/new-shop-82_large.jpeg?w=720 2x" alt="Demo image 2">
                </div>
                <div class="card-body">
                <h5 class="card-title"><a href="#">Niv Shampoo</a></h5>
                <div class="card-price">Rp322.150</div>
                <div class="card-disc">Rp379.000</div>
                <div class="rating">
                  <div class="stars">
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-empty"></star-icon>
                  </div>
                  <span class="review-no">(41)</span>
                </div>
                <div class="mt-3">
                  <nuxt-link to="" class="btn btn-outline-dark rounded-0">Add to Cart</nuxt-link>
                </div>
              </div>
            </div>
          </div>
          <div>
            <div class="card figure">
              <div class="ratio ratio-1x1">
                <img class="image-main" src="@/static/img/product/new-shop-60_1af62e44-dfe3-4fd1-a02a-91ce71ad5721_large.jpeg?w=360" srcset="@/static/img/product/new-shop-60_1af62e44-dfe3-4fd1-a02a-91ce71ad5721_large.jpeg?w=720 2x" alt="Demo image 1">
                <img class="image-hover" src="@/static/img/product/new-shop-64_e56af2f6-8266-4a25-8519-7ffb67fc8964_large.jpeg?w=360" srcset="@/static/img/product/new-shop-64_e56af2f6-8266-4a25-8519-7ffb67fc8964_large.jpeg?w=720 2x" alt="Demo image 2">
                </div>
                <div class="card-body">
                <h5 class="card-title"><a href="#">Laura Shampoo</a></h5>
                <div class="card-price">Rp322.150</div>
                <div class="card-disc">Rp379.000</div>
                <div class="rating">
                  <div class="stars">
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-empty"></star-icon>
                  </div>
                  <span class="review-no">(41)</span>
                </div>
                <div class="mt-3">
                  <nuxt-link to="" class="btn btn-outline-dark rounded-0">Add to Cart</nuxt-link>
                </div>
              </div>
            </div>
          </div>
          <div>
            <div class="card figure">
              <div class="label-disc">New</div>
              <div class="ratio ratio-1x1">
                <img class="image-main" src="@/static/img/product/new-shop-47_large.jpeg?w=360" srcset="@/static/img/product/new-shop-47_large.jpeg?w=720 2x" alt="Demo image 1">
                <img class="image-hover" src="@/static/img/product/new-shop-89_large.jpeg?w=360" srcset="@/static/img/product/new-shop-89_large.jpeg?w=720 2x" alt="Demo image 2">
                </div>
                <div class="card-body">
                <h5 class="card-title"><a href="#">Liva Hair Tonic</a></h5>
                <div class="card-price">Rp322.150</div>
                <div class="card-disc">Rp379.000</div>
                <div class="rating">
                  <div class="stars">
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-empty"></star-icon>
                  </div>
                  <span class="review-no">(41)</span>
                </div>
                <div class="mt-3">
                  <nuxt-link to="" class="btn btn-outline-dark rounded-0">Add to Cart</nuxt-link>
                </div>
              </div>
            </div>
          </div>
          <div>
            <div class="card figure">
              <div class="ratio ratio-1x1">
                <img class="image-main" src="@/static/img/product/new-shop-70_large.jpeg?w=360" srcset="@/static/img/product/new-shop-70_large.jpeg?w=720 2x" alt="Demo image 1">
                <img class="image-hover" src="@/static/img/product/new-shop-72_large.jpeg?w=360" srcset="@/static/img/product/new-shop-72_large.jpeg?w=720 2x" alt="Demo image 2">
                </div>
                <div class="card-body">
                <h5 class="card-title"><a href="#">DD Cleanser</a></h5>
                <div class="card-price">Rp322.150</div>
                <div class="card-disc">Rp379.000</div>
                <div class="rating">
                  <div class="stars">
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-empty"></star-icon>
                  </div>
                  <span class="review-no">(41)</span>
                </div>
                <div class="mt-3">
                  <nuxt-link to="" class="btn btn-outline-dark rounded-0">Add to Cart</nuxt-link>
                </div>
              </div>
            </div>
          </div>
        </VCarousel>
      </div>
    </section>
    <section id="sec-product">
      <div class="container">
        <div class="title">
          <h2>Our Pick</h2>
        </div>
        <VCarousel v-bind="CPSettings">
          <div>
            <div class="card figure">
              <div class="label-disc">New</div>
              <div class="ratio ratio-1x1">
                <img class="image-main" src="@/static/img/product/new-shop-54_748da1af-b8f8-4d68-884b-3d798a65386b_large.jpeg?w=360" srcset="@/static/img/product/new-shop-54_748da1af-b8f8-4d68-884b-3d798a65386b_large.jpeg?w=720 2x" alt="Demo image 1">
                <img class="image-hover" src="@/static/img/product/new-shop-59_274bbe12-a19a-41f2-aa82-e071b821fc35_large.jpeg?w=360" srcset="@/static/img/product/new-shop-59_274bbe12-a19a-41f2-aa82-e071b821fc35_large.jpeg?w=720 2x" alt="Demo image 2">
              </div>
              <div class="card-body">
                <h5 class="card-title"><a href="#">Ray Conditioner</a></h5>
                <div class="card-price">Rp322.150</div>
                <div class="card-disc">Rp379.000</div>
                <div class="rating">
                  <div class="stars">
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-empty"></star-icon>
                  </div>
                  <span class="review-no">(41)</span>
                </div>
                <div class="mt-3">
                  <nuxt-link to="" class="btn btn-outline-dark rounded-0">Add to Cart</nuxt-link>
                </div>
              </div>
            </div>
          </div>
          <div>
            <div class="card figure">
              <div class="ratio ratio-1x1">
                <img class="image-main" src="@/static/img/product/new-shop-56_large.jpeg?w=360" srcset="@/static/img/product/new-shop-56_large.jpeg?w=720 2x" alt="Demo image 1">
                <img class="image-hover" src="@/static/img/product/new-shop-53_large.jpeg?w=360" srcset="@/static/img/product/new-shop-53_large.jpeg?w=720 2x" alt="Demo image 2">
                </div>
                <div class="card-body">
                <h5 class="card-title"><a href="#">Alan Night Cream</a></h5>
                <div class="card-price">Rp322.150</div>
                <div class="card-disc">Rp379.000</div>
                <div class="rating">
                  <div class="stars">
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-empty"></star-icon>
                  </div>
                  <span class="review-no">(41)</span>
                </div>
                <div class="mt-3">
                  <div class="text-secondary">Habis</div>
                </div>
              </div>
            </div>
          </div>
          <div>
            <div class="card figure">
              <div class="ratio ratio-1x1">
                <img class="image-main" src="@/static/img/product/new-shop-55_large.jpeg?w=360" srcset="@/static/img/product/new-shop-55_large.jpeg?w=720 2x" alt="Demo image 1">
                <img class="image-hover" src="@/static/img/product/new-shop-82_large.jpeg?w=360" srcset="@/static/img/product/new-shop-82_large.jpeg?w=720 2x" alt="Demo image 2">
                </div>
                <div class="card-body">
                <h5 class="card-title"><a href="#">Niv Shampoo</a></h5>
                <div class="card-price">Rp322.150</div>
                <div class="card-disc">Rp379.000</div>
                <div class="rating">
                  <div class="stars">
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-empty"></star-icon>
                  </div>
                  <span class="review-no">(41)</span>
                </div>
                <div class="mt-3">
                  <nuxt-link to="" class="btn btn-outline-dark rounded-0">Add to Cart</nuxt-link>
                </div>
              </div>
            </div>
          </div>
          <div>
            <div class="card figure">
              <div class="ratio ratio-1x1">
                <img class="image-main" src="@/static/img/product/new-shop-60_1af62e44-dfe3-4fd1-a02a-91ce71ad5721_large.jpeg?w=360" srcset="@/static/img/product/new-shop-60_1af62e44-dfe3-4fd1-a02a-91ce71ad5721_large.jpeg?w=720 2x" alt="Demo image 1">
                <img class="image-hover" src="@/static/img/product/new-shop-64_e56af2f6-8266-4a25-8519-7ffb67fc8964_large.jpeg?w=360" srcset="@/static/img/product/new-shop-64_e56af2f6-8266-4a25-8519-7ffb67fc8964_large.jpeg?w=720 2x" alt="Demo image 2">
                </div>
                <div class="card-body">
                <h5 class="card-title"><a href="#">Laura Shampoo</a></h5>
                <div class="card-price">Rp322.150</div>
                <div class="card-disc">Rp379.000</div>
                <div class="rating">
                  <div class="stars">
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-empty"></star-icon>
                  </div>
                  <span class="review-no">(41)</span>
                </div>
                <div class="mt-3">
                  <nuxt-link to="" class="btn btn-outline-dark rounded-0">Add to Cart</nuxt-link>
                </div>
              </div>
            </div>
          </div>
          <div>
            <div class="card figure">
              <div class="label-disc">New</div>
              <div class="ratio ratio-1x1">
                <img class="image-main" src="@/static/img/product/new-shop-47_large.jpeg?w=360" srcset="@/static/img/product/new-shop-47_large.jpeg?w=720 2x" alt="Demo image 1">
                <img class="image-hover" src="@/static/img/product/new-shop-89_large.jpeg?w=360" srcset="@/static/img/product/new-shop-89_large.jpeg?w=720 2x" alt="Demo image 2">
                </div>
                <div class="card-body">
                <h5 class="card-title"><a href="#">Liva Hair Tonic</a></h5>
                <div class="card-price">Rp322.150</div>
                <div class="card-disc">Rp379.000</div>
                <div class="rating">
                  <div class="stars">
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-empty"></star-icon>
                  </div>
                  <span class="review-no">(41)</span>
                </div>
                <div class="mt-3">
                  <nuxt-link to="" class="btn btn-outline-dark rounded-0">Add to Cart</nuxt-link>
                </div>
              </div>
            </div>
          </div>
          <div>
            <div class="card figure">
              <div class="ratio ratio-1x1">
                <img class="image-main" src="@/static/img/product/new-shop-70_large.jpeg?w=360" srcset="@/static/img/product/new-shop-70_large.jpeg?w=720 2x" alt="Demo image 1">
                <img class="image-hover" src="@/static/img/product/new-shop-72_large.jpeg?w=360" srcset="@/static/img/product/new-shop-72_large.jpeg?w=720 2x" alt="Demo image 2">
                </div>
                <div class="card-body">
                <h5 class="card-title"><a href="#">DD Cleanser</a></h5>
                <div class="card-price">Rp322.150</div>
                <div class="card-disc">Rp379.000</div>
                <div class="rating">
                  <div class="stars">
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-empty"></star-icon>
                  </div>
                  <span class="review-no">(41)</span>
                </div>
                <div class="mt-3">
                  <nuxt-link to="" class="btn btn-outline-dark rounded-0">Add to Cart</nuxt-link>
                </div>
              </div>
            </div>
          </div>
        </VCarousel>
      </div>
    </section>
    <section id="sec-product">
      <div class="container">
        <div class="title">
          <h2>Best Sellers</h2>
        </div>
        <VCarousel v-bind="CPSettings">
          <div>
            <div class="card figure">
              <div class="label-disc">New</div>
              <div class="ratio ratio-1x1">
                <img class="image-main" src="@/static/img/product/new-shop-54_748da1af-b8f8-4d68-884b-3d798a65386b_large.jpeg?w=360" srcset="@/static/img/product/new-shop-54_748da1af-b8f8-4d68-884b-3d798a65386b_large.jpeg?w=720 2x" alt="Demo image 1">
                <img class="image-hover" src="@/static/img/product/new-shop-59_274bbe12-a19a-41f2-aa82-e071b821fc35_large.jpeg?w=360" srcset="@/static/img/product/new-shop-59_274bbe12-a19a-41f2-aa82-e071b821fc35_large.jpeg?w=720 2x" alt="Demo image 2">
              </div>
              <div class="card-body">
                <h5 class="card-title"><a href="#">Ray Conditioner</a></h5>
                <div class="card-price">Rp322.150</div>
                <div class="card-disc">Rp379.000</div>
                <div class="rating">
                  <div class="stars">
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-empty"></star-icon>
                  </div>
                  <span class="review-no">(41)</span>
                </div>
                <div class="mt-3">
                  <nuxt-link to="" class="btn btn-outline-dark rounded-0">Add to Cart</nuxt-link>
                </div>
              </div>
            </div>
          </div>
          <div>
            <div class="card figure">
              <div class="ratio ratio-1x1">
                <img class="image-main" src="@/static/img/product/new-shop-56_large.jpeg?w=360" srcset="@/static/img/product/new-shop-56_large.jpeg?w=720 2x" alt="Demo image 1">
                <img class="image-hover" src="@/static/img/product/new-shop-53_large.jpeg?w=360" srcset="@/static/img/product/new-shop-53_large.jpeg?w=720 2x" alt="Demo image 2">
                </div>
                <div class="card-body">
                <h5 class="card-title"><a href="#">Alan Night Cream</a></h5>
                <div class="card-price">Rp322.150</div>
                <div class="card-disc">Rp379.000</div>
                <div class="rating">
                  <div class="stars">
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-empty"></star-icon>
                  </div>
                  <span class="review-no">(41)</span>
                </div>
                <div class="mt-3">
                  <div class="text-secondary">Habis</div>
                </div>
              </div>
            </div>
          </div>
          <div>
            <div class="card figure">
              <div class="ratio ratio-1x1">
                <img class="image-main" src="@/static/img/product/new-shop-55_large.jpeg?w=360" srcset="@/static/img/product/new-shop-55_large.jpeg?w=720 2x" alt="Demo image 1">
                <img class="image-hover" src="@/static/img/product/new-shop-82_large.jpeg?w=360" srcset="@/static/img/product/new-shop-82_large.jpeg?w=720 2x" alt="Demo image 2">
                </div>
                <div class="card-body">
                <h5 class="card-title"><a href="#">Niv Shampoo</a></h5>
                <div class="card-price">Rp322.150</div>
                <div class="card-disc">Rp379.000</div>
                <div class="rating">
                  <div class="stars">
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-empty"></star-icon>
                  </div>
                  <span class="review-no">(41)</span>
                </div>
                <div class="mt-3">
                  <nuxt-link to="" class="btn btn-outline-dark rounded-0">Add to Cart</nuxt-link>
                </div>
              </div>
            </div>
          </div>
          <div>
            <div class="card figure">
              <div class="ratio ratio-1x1">
                <img class="image-main" src="@/static/img/product/new-shop-60_1af62e44-dfe3-4fd1-a02a-91ce71ad5721_large.jpeg?w=360" srcset="@/static/img/product/new-shop-60_1af62e44-dfe3-4fd1-a02a-91ce71ad5721_large.jpeg?w=720 2x" alt="Demo image 1">
                <img class="image-hover" src="@/static/img/product/new-shop-64_e56af2f6-8266-4a25-8519-7ffb67fc8964_large.jpeg?w=360" srcset="@/static/img/product/new-shop-64_e56af2f6-8266-4a25-8519-7ffb67fc8964_large.jpeg?w=720 2x" alt="Demo image 2">
                </div>
                <div class="card-body">
                <h5 class="card-title"><a href="#">Laura Shampoo</a></h5>
                <div class="card-price">Rp322.150</div>
                <div class="card-disc">Rp379.000</div>
                <div class="rating">
                  <div class="stars">
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-empty"></star-icon>
                  </div>
                  <span class="review-no">(41)</span>
                </div>
                <div class="mt-3">
                  <nuxt-link to="" class="btn btn-outline-dark rounded-0">Add to Cart</nuxt-link>
                </div>
              </div>
            </div>
          </div>
          <div>
            <div class="card figure">
              <div class="label-disc">New</div>
              <div class="ratio ratio-1x1">
                <img class="image-main" src="@/static/img/product/new-shop-47_large.jpeg?w=360" srcset="@/static/img/product/new-shop-47_large.jpeg?w=720 2x" alt="Demo image 1">
                <img class="image-hover" src="@/static/img/product/new-shop-89_large.jpeg?w=360" srcset="@/static/img/product/new-shop-89_large.jpeg?w=720 2x" alt="Demo image 2">
                </div>
                <div class="card-body">
                <h5 class="card-title"><a href="#">Liva Hair Tonic</a></h5>
                <div class="card-price">Rp322.150</div>
                <div class="card-disc">Rp379.000</div>
                <div class="rating">
                  <div class="stars">
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-empty"></star-icon>
                  </div>
                  <span class="review-no">(41)</span>
                </div>
                <div class="mt-3">
                  <nuxt-link to="" class="btn btn-outline-dark rounded-0">Add to Cart</nuxt-link>
                </div>
              </div>
            </div>
          </div>
          <div>
            <div class="card figure">
              <div class="ratio ratio-1x1">
                <img class="image-main" src="@/static/img/product/new-shop-70_large.jpeg?w=360" srcset="@/static/img/product/new-shop-70_large.jpeg?w=720 2x" alt="Demo image 1">
                <img class="image-hover" src="@/static/img/product/new-shop-72_large.jpeg?w=360" srcset="@/static/img/product/new-shop-72_large.jpeg?w=720 2x" alt="Demo image 2">
                </div>
                <div class="card-body">
                <h5 class="card-title"><a href="#">DD Cleanser</a></h5>
                <div class="card-price">Rp322.150</div>
                <div class="card-disc">Rp379.000</div>
                <div class="rating">
                  <div class="stars">
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-fill"></star-icon>
                    <star-icon size="1x" class="star-empty"></star-icon>
                  </div>
                  <span class="review-no">(41)</span>
                </div>
                <div class="mt-3">
                  <nuxt-link to="" class="btn btn-outline-dark rounded-0">Add to Cart</nuxt-link>
                </div>
              </div>
            </div>
          </div>
        </VCarousel>
      </div>
    </section>
    <section id="articles-col">
      <div class="container">
        <div class="title">
          <h2>SkinCare Story</h2>
        </div>
        <VCarousel v-bind="ARSettings" class="slider-articles">
            <div class="p-2">
                <div class="card">
                    <a href="./single-post.html" title="">
                        <div class="ratio ratio-16x9">
                            <img class="card-img-top" src="@/static/img/product/product4.jpg" alt="image 1">
                        </div>
                        <div class="card-body">
                            <small class="card-text text-secondary mb-2">Review</small>
                            <h5 class="card-title text-dark mb-2">Review Samsung Galaxy A01, Android di Bawah Satu Setengah Juta</h5>
                            <p class="card-text">Buat yang mencari smartphone Android dengan harga sejutaan, tapi mereknya harus Samsung, maka jawabannya adalah Galaxy A01. Walaupun harganya terjangkau, gaya desain Galaxy A01 sama seperti Galaxy A series yang dibanderol lebih mahal. Yuk cari tahu dan berikut reviewSamsung Galaxy A01 selengkapnya.</p>
                        </div>
                    </a>
                </div>
            </div>
            <div class="p-2">
                <div class="card">
                    <a href="./single-post.html" title="">
                        <div class="ratio ratio-16x9">
                            <img class="card-img-top" src="@/static/img/product/product5.jpg" alt="image 2">
                        </div>
                        <div class="card-body">
                            <small class="card-text text-secondary mb-2">News</small>
                            <h5 class="card-title text-dark mb-2">Resmi Masuk Indonesia, Ini Perbedaan vivo V20 dan V20 SE</h5>
                            <p class="card-text">Pada bulan Maret yang lalu, vivo V19 diluncurkan ke pasar. Tak butuh waktu lama, enam bulan kemudian vivo meluncurkan generasi terbaru V-Series. Produk yang dirilis pun langsung dua sekaligus yaitu vivo V20 dan V20 SE. Vivo menyebut kehadiran dua seri terbaru ini adalah upaya untuk terus menghadirkan teknologi dan inovasi smartphone sesuai kebutuhan bagi para konsumen di Indonesia.</p>
                        </div>
                    </a>
                </div>
            </div>
            <div class="p-2">
                <div class="card">
                    <a href="./single-post.html" title="">
                        <div class="ratio ratio-16x9">
                            <img class="card-img-top" src="@/static/img/product/product5.jpg" alt="image 3">
                        </div>
                        <div class="card-body">
                            <small class="card-text text-secondary mb-2">Tips & Trick</small>
                            <h5 class="card-title text-dark mb-2">4 Cara Melindungi Ponsel Android dari Serangan Hacker</h5>
                            <p class="card-text">Ponsel Android adalah favorit banyak orang. Tak heran jika para penjahat siber atau hacker rajin menyasar perangkat itu untuk beragam kepentingan, dari mencuri data penting, membobol kartu kredit ataupun aktivitas mata-mata. Nah, untuk melindungi ponsel Android dari serangan hacker, Jake Moore selaku Security Specialist di Eset membagikan 4 tips sederhana. Berikut daftarnya</p>
                        </div>
                    </a>
                </div>
            </div>
        </VCarousel>
      </div>
    </section>
    <MobileNav></MobileNav>
  </div>
</template>

<script>
import FlashNews from '../components/FlashNews.vue'
import MobileNav from '../components/MobileNav.vue'
import VCarousel from 'vue-slick-carousel'
import { StarIcon } from 'vue-feather-icons'

export default {

  name: 'index',

  components: {
    FlashNews,
    VCarousel,
    MobileNav,
    StarIcon
  },

  data () {
    return {
      CPSettings: {
        "arrows": true,
        "speed": 500,
        "infinite": false,
        "slidesToShow": 5,
        "slidesToScroll": 1,
        "responsive": [
          {
            "breakpoint": 1024,
            "settings": {
            "slidesToShow": 6,
            "slidesToScroll": 1,
            }
          },
          {
            "breakpoint": 600,
            "settings": {
            "slidesToShow": 2,
            "slidesToScroll": 1,
            "initialSlide": 1
            }
          },
          {
            "breakpoint": 480,
            "settings": {
            "slidesToShow": 2,
            "slidesToScroll": 1,
            "dots": false,
            "centerMode": true,
            "centerPadding": "20px",
            "initialSlide": 1
            }
          }
        ]
      },
      ARSettings: {
        "infinite": true,
        "slidesToShow": 3,
        "slidesToScroll": 1,
        "dots": false,
        "arrows": false,
        "responsive": [
          {
            "breakpoint": 1024,
            "settings": {
              "slidesToShow": 3,
              "slidesToScroll": 1,
              "infinite": true,
              "dots": false
            }
          },
          {
            "breakpoint": 600,
            "settings": {
              "slidesToShow": 3,
              "slidesToScroll": 1
            }
          },
          {
            "breakpoint": 480,
            "settings": {
              "slidesToShow": 1,
              "slidesToScroll": 1,
              "arrows": false,
              "dots": true,
            }
          }
        ]
      },
    }
  }
}
</script>

<style lang="scss">
#sec-product{
  background: #fff;

  .title{
    display: flex;
    align-items: center;
    justify-content: center;
    margin-bottom: 15px;

    h2{
      color: inherit;
    }

    .moreBtn{
    color: #069699;
    padding: 0 15px;
    border-left: 1px solid #ddd;
    margin-left: 15px;

      &:hover{
        color: #f4a21a;
      }
    }
  }

  .card{
    border: 0;
    text-align: center;
    margin: 10px;
    border-radius: 0px;
    overflow: hidden;

    &:hover{
      box-shadow: 0px 0px 5px 0px rgba(0,0,0,0.15);
      -webkit-box-shadow: 0px 0px 5px 0px rgba(0,0,0,0.15);
      -moz-box-shadow: 0px 0px 5px 0px rgba(0,0,0,0.15);
    }

    .card-img-top{
      border-top-left-radius: 15px;
      border-top-right-radius: 15px;
    }

    .card-title {
      font-size: 14px;
      font-weight: 500;
      line-height: 1.5em;
      height: 3em;
      margin-bottom: 15px;
      color: #333;
      text-align: center;
    }

    .card-price{
      text-align: center;
      color: #333;
      font-weight: 700;
      margin-bottom: 5px;
    }

    .card-disc{
      text-align: center;
      text-decoration: line-through;
      color: #777;
      margin-bottom: 15px;
      font-size: 12px;
    }

    .label-disc{
      position: absolute;
      background: #e9549e;
      color: white;
      z-index: 1;
      width: 36px;
      height: 36px;
      font-size: 12px;
      display: flex;
      align-items: center;
      justify-content: center;
      border-radius: 100%;
      right: 10px;
      top: 10px;
    }

    .rating{
      justify-content: center;
    }
  }

  .slick-slider {
    .slick-prev{
      //opacity: 1;
    }
    .slick-next{
      //opacity: 1;
    }
  }
}
#articles-col{
  background: #f8f9fa;

  .title{
    text-align: center;
  }

  .card{
    border-radius: 0;
    border: 0;
    background: transparent;
    transition: all ease .5s;

    &:hover{
      background: #fff;
      box-shadow: 0px 0px 5px 0px rgba(0,0,0,0.15);
      -webkit-box-shadow: 0px 0px 5px 0px rgba(0,0,0,0.15);
      -moz-box-shadow: 0px 0px 5px 0px rgba(0,0,0,0.15);
    }
  }
}
@media (max-width: 767px){
  #sec-product{
    .container{
      padding: 0;

      .title{
        padding: 0 16px;
      }

      .card{
        margin: 10px 5px;
      }
    }
  }
}
</style>
