<template>
    <div>
        <div class="flash-news">
            <div class="container">
                <div class="row">
                    <div class="col-12 col-lg-6 offset-lg-3">
                        <div id="app" class="ticker box">
                          <article class="media d-flex align-items-center justify-content-between">
                            <div class="media-content">
                              <transition name="fade" mode="out-in">
                                <a class="news" href="#" >
                                  {{news[0].summary}}</a>
                                </span>
                              </transition>
                            </div>
                            <span class="badge bg-dark rounded-0 text-white">Check Now</span>
                          </article>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {

  name: 'FlashNews',

  data () {
    return {
        index: 0,
        news: [
            {
              summary: 'There has been a massive explosion at the cheese factory'
            },
            {
              summary: 'Bob is on fire'
            },
            {
              summary: 'Look its Superman!'
            }
        ]
    }
  },

  created: function() {
    setInterval(this.updateTicker, 5000);
  },
  methods: {
    updateTicker: function() {
      var removed = this.news.pop();
      this.news.unshift(removed);
    }
  },
}
</script>

<style lang="scss" scoped>
.flash-news{
    background: #ff9f9f;
    padding: 10px 0;

    a{
        color: #6f3232;

        &:hover{
            color: #461818;
        }
    }
}
</style>