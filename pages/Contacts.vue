<template>
  <section class="contacts">
    <div class="contacts__title-wrap">
      <h1 class="contacts__title">КОНТАКТЫ</h1>
      <!-- <i class="contacts__btn">
        <svg width="89" height="40" viewBox="0 0 89 40" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path fill-rule="evenodd" clip-rule="evenodd"
            d="M41.9124 37.8508L42.9 38.6917C43.6473 39.328 44.7459 39.328 45.4932 38.6917L46.4808 37.8508L87.8724 2.60829C88.5668 2.01703 88.5668 0.944591 87.8724 0.353325C87.3191 -0.117775 86.5057 -0.117775 85.9524 0.353325L45.4932 34.802C44.7459 35.4383 43.6473 35.4383 42.9 34.802L2.4408 0.353325C1.8875 -0.117775 1.07412 -0.117775 0.520822 0.353325C-0.173607 0.944591 -0.173608 2.01703 0.520821 2.60829L41.9124 37.8508Z"
            fill="white" />
        </svg>

      </i> -->
    </div>
    <h2 class="contacts__subtitle">
      Офис на Остоженке
    </h2>
    <img src="../assets/img/contacts-bg.png" alt="" class="contacts__img">
    <div class="container">
      <div class="container__elem container__elem--12">
        <div class="contacts__inner" id="contacts__inner">
          <div class="contacts__info">
            <div class="contacts__item">
              <p class="contacts__item-text">Москва, ул. Остоженка, 37/7с2, <br> 4 этаж</p>
            </div>
            <div class="contacts__item">
              <p class="contacts__item-name">
                Как к нам пройти
              </p>
              <p class="contacts__item-text">Голубой особняк, вход через <br> Conversation Cafe, 4 этаж</p>
            </div>
          </div>
          <div class="contacts__slider">
            <div class="contacts__slider-items">
              <div class="contacts__slider-item active">
                <img src="../assets/img/contacts-slider-img-1.png" alt="" class="contacts__slider-img">
              </div>
              <div class="contacts__slider-item">
                <img src="../assets/img/contacts-slider-img-2.png" alt="" class="contacts__slider-img">
              </div>
              <div class="contacts__slider-item">
                <img src="../assets/img/contacts-slider-img-3.png" alt="" class="contacts__slider-img">
              </div>
              <div class="contacts__slider-item">
                <img src="../assets/img/contacts-slider-img-4.png" alt="" class="contacts__slider-img">
              </div>
              <div class="contacts__slider-item">
                <img src="../assets/img/contacts-slider-img-5.png" alt="" class="contacts__slider-img">
              </div>
              <div class="contacts__slider-item">
                <img src="../assets/img/contacts-slider-img-6.png" alt="" class="contacts__slider-img">
              </div>
            </div>
            <div class="contacts__slider-bottom">
              <div class="contacts__slider-arrow contacts__slider-arrow--prev">
                <svg width="46" height="8" viewBox="0 0 46 8" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path
                    d="M0.646447 3.64645C0.451184 3.84171 0.451184 4.15829 0.646447 4.35355L3.82843 7.53553C4.02369 7.7308 4.34027 7.7308 4.53553 7.53553C4.7308 7.34027 4.7308 7.02369 4.53553 6.82843L1.70711 4L4.53553 1.17157C4.7308 0.976311 4.7308 0.659729 4.53553 0.464466C4.34027 0.269204 4.02369 0.269204 3.82843 0.464466L0.646447 3.64645ZM1 4.5L46 4.5L46 3.5L1 3.5L1 4.5Z"
                    fill="black" />
                </svg>
              </div>
              <p class="contacts__slider-num">0 <span>1</span></p>
              <div class="contacts__slider-arrow contacts__slider-arrow--next">
                <svg width="46" height="8" viewBox="0 0 46 8" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path
                    d="M45.3536 4.35356C45.5488 4.1583 45.5488 3.84171 45.3536 3.64645L42.1716 0.46447C41.9763 0.269208 41.6597 0.269208 41.4645 0.46447C41.2692 0.659732 41.2692 0.976314 41.4645 1.17158L44.2929 4L41.4645 6.82843C41.2692 7.02369 41.2692 7.34028 41.4645 7.53554C41.6597 7.7308 41.9763 7.7308 42.1716 7.53554L45.3536 4.35356ZM-4.37114e-08 4.5L45 4.5L45 3.5L4.37114e-08 3.5L-4.37114e-08 4.5Z"
                    fill="black" />
                </svg>
              </div>
            </div>
          </div>
        </div>
        <div class="contacts__map">
          <div style="position:relative;overflow:hidden;border-radius:16px;">
            <iframe class="contacts__map-wrap"
              src="https://yandex.ru/map-widget/v1/?ll=37.595920%2C55.738562&mode=whatshere&whatshere%5Bpoint%5D=37.595872%2C55.738628&whatshere%5Bzoom%5D=21&z=21"
              width="1200" height="650" frameborder="0" allowfullscreen="true" style="position:relative;">
            </iframe>
          </div>
        </div>
      </div>
    </div>
  </section>
  <section class="eight" style="margin-top: 80px;">
    <div class="container">
      <div class="container__elem container__elem--12">
        <div class="eight__inner">
          <div class="eight__info">
            <p class="eight__info-title">Напишите или <br> позвоните нам</p>
            <div class="eight__info-links">
              <a href="tel:88001016856">
                <i>
                  <svg width="40" height="35" viewBox="0 0 40 35" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path
                      d="M37.9794 24.8459L37.9497 25.0801C36.9583 24.6116 32.1296 22.3721 31.2304 22.0629C29.2113 21.3539 29.7811 21.9504 25.9043 26.1608C25.3279 26.7699 24.7548 26.8168 23.7765 26.3951C22.7884 25.9266 19.6164 24.9427 15.8615 21.7568C12.9366 19.2736 10.9735 16.2283 10.3938 15.2912C9.42874 13.7108 11.4478 13.4859 13.2858 10.1875C13.6151 9.53161 13.4472 9.01624 13.2034 8.55084C12.9564 8.08233 10.99 3.49086 10.1665 1.66052C9.37603 -0.163574 8.56247 0.0675615 7.95311 0.0675615C6.05589 -0.0886108 4.6692 -0.0636237 3.4472 1.14203C-1.86898 6.68302 -0.528407 12.3989 4.02032 18.4772C12.9597 29.5716 17.7225 31.6144 26.4313 34.4505C28.7831 35.1595 30.9273 35.0595 32.6236 34.8284C34.5143 34.5442 38.4438 32.5764 39.2639 30.3744C40.1038 28.1723 40.1038 26.3451 39.8568 25.9235C39.6131 25.5018 38.9675 25.2675 37.9794 24.8459Z"
                      fill="white" />
                  </svg>

                </i>
                <p>8 800 101 68 56</p>
              </a>
              <a href="tel:89015953988">
                <i>
                  <svg width="40" height="35" viewBox="0 0 40 35" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path
                      d="M37.9794 24.8459L37.9497 25.0801C36.9583 24.6116 32.1296 22.3721 31.2304 22.0629C29.2113 21.3539 29.7811 21.9504 25.9043 26.1608C25.3279 26.7699 24.7548 26.8168 23.7765 26.3951C22.7884 25.9266 19.6164 24.9427 15.8615 21.7568C12.9366 19.2736 10.9735 16.2283 10.3938 15.2912C9.42874 13.7108 11.4478 13.4859 13.2858 10.1875C13.6151 9.53161 13.4472 9.01624 13.2034 8.55084C12.9564 8.08233 10.99 3.49086 10.1665 1.66052C9.37603 -0.163574 8.56247 0.0675615 7.95311 0.0675615C6.05589 -0.0886108 4.6692 -0.0636237 3.4472 1.14203C-1.86898 6.68302 -0.528407 12.3989 4.02032 18.4772C12.9597 29.5716 17.7225 31.6144 26.4313 34.4505C28.7831 35.1595 30.9273 35.0595 32.6236 34.8284C34.5143 34.5442 38.4438 32.5764 39.2639 30.3744C40.1038 28.1723 40.1038 26.3451 39.8568 25.9235C39.6131 25.5018 38.9675 25.2675 37.9794 24.8459Z"
                      fill="white" />
                  </svg>

                </i>
                <p>8 901 595 3988</p>
              </a>
              <a href="mailto:AM@remixmedia.ru">
                <i>
                  <svg width="51" height="51" viewBox="0 0 51 51" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path
                      d="M3.51733 13.049V37.9722L15.9789 25.5106L3.51733 13.049ZM5.99347 10.5518L21.7701 26.3283C23.7626 28.3209 27.2376 28.3209 29.2301 26.3283L45.0067 10.5518H5.99347Z"
                      fill="white" />
                    <path
                      d="M31.7166 28.8149C30.0583 30.475 27.8494 31.3912 25.4999 31.3912C23.1504 31.3912 20.9416 30.475 19.2832 28.8149L18.4654 27.9971L6.0144 40.4481H44.9854L32.5344 27.9971L31.7166 28.8149ZM35.0211 25.5104L47.4827 37.972V13.0488L35.0211 25.5104Z"
                      fill="white" />
                  </svg>

                </i>
                <p>AM@remixmedia.ru</p>
              </a>
            </div>
          </div>
          <ContactForm page="ContactsPage" />
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import ContactForm from "@/components/ContactForm.vue";


export default {
  name: 'HomeView',
  components: {
    ContactForm,
  },
  mounted() {
    document.body.classList.add('light-theme');
    let items = document.querySelectorAll('.contacts__slider-item')
    let prev = document.querySelector('.contacts__slider-arrow--prev')
    let next = document.querySelector('.contacts__slider-arrow--next')
    let num = document.querySelector('.contacts__slider-num span')
    let sliderNum = 0;
    next.addEventListener('click', ()=>{
      if (sliderNum == 5){
        sliderNum = 0;
        changeSlider();
      } else {
        sliderNum++
        changeSlider();
      }
    })
    prev.addEventListener('click', ()=>{
      if (sliderNum == 0){
        sliderNum = 5;
        changeSlider();
      } else {
        sliderNum--
        changeSlider();
      }
    })
    function changeSlider(){
      items.forEach(item => {
        item.classList.remove('active')
      });
      items[sliderNum].classList.add('active')
      num.textContent = sliderNum + 1
    }

    // const scrollToElement = document.getElementById('contacts__inner');
    // const scrollButton = document.querySelector('.contacts__btn');

    // // Функция для прокрутки к элементу
    // function scrollToContacts() {
    //   scrollToElement.scrollIntoView({ behavior: 'smooth' }); // Прокрутка с плавным эффектом
    // }

    // // Добавляем обработчик события на клик по кнопке
    // scrollButton.addEventListener('click', scrollToContacts);
  }
}

</script>