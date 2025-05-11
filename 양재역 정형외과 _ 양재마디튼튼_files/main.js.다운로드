$("document").ready(function() {
  var swiperAnimation = new SwiperAnimation();
  var mainswiper = new Swiper('.swiper_visual', {
    loop: true,
    effect: 'fade',
    speed: 3000,
    autoplay: {
      delay: 5000,
      disableOnInteraction: false,
    },
    on: {
      slideChange: function() {},
      init: function() {
        swiperAnimation.init(this).animate();
      },
      slideChange: function() {
        swiperAnimation.init(this).animate();
      }
    },

    navigation: {
        nextEl: ".swiper-visual-next",
        prevEl: ".swiper-visual-prev",
      },

  });
});
