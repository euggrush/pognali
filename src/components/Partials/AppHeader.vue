<template>
  <header class="page-header">
    <!-- ОТКРЫТОЕ МЕНЮ МОДАЛЬНОЕ -->
    <nav class="page-header__nav-modal">
      <div class="page-header__nav-modal-container">
        <div class="page-header__modal-btn-wrap">
          <a href="#" class="page-header__nav-item-link">
            <span class="text-hidden">Главная</span>

            <div class="page-header__logo-open">
              <picture>
                <source
                  media="(min-width: 1440px)"
                  srcset="img/logo-desktop-blue@2x.png"
                />
                <source
                  media="(min-width: 768px)"
                  srcset="img/logo-desktop-blue@2x.png"
                />
                <img src="img/logo-mobile-blue@2x.png" alt="главная" />
              </picture>
            </div>
          </a>
          <button class="page-header__button" type="button">
            <span class="text-hidden">закрыть меню</span>
          </button>
        </div>

        <a class="page-header__nav-item" href="index.html"> О сервисе </a>
        <a class="page-header__nav-item" href="form.html"> Направления </a>
        <a class="page-header__nav-item" href="catalog.html"> Попутчики </a>
        <a class="page-header__nav-button" href="#"> Авторизация </a>
        <div class="page-header__contact-wrap">
          <a class="page-header__nav-call" href="tel:+88005558628"
            ><span class="text-hidden">Позвонить</span></a
          >
          <span class="page-header__link-text">8 800 555-86-28</span>

          <a class="page-header__nav-email" href="mailto:mail@htmlacademy.ru"
            ><span class="text-hidden">Отправить email</span></a
          >
          <span class="page-header__link-text">mail@htmlacademy.ru</span>
        </div>
        <div class="page-header__social">
          <a
            class="page-header__link-fb"
            href="https://www.facebook.com/htmlacademy"
          >
            <svg
              class="page-header__icon-fb"
              width="11"
              height="21"
              viewBox="0 0 11 21"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M7.48786 20.8125H2.12929V11.1375H0V6.3525H2.06643C1.90929 4.185 2.30214 2.6025 3.26071 1.5225C3.71777 1.04316 4.27461 0.66015 4.89562 0.397985C5.51662 0.13582 6.18812 0.000268301 6.86714 0L10.6229 0V4.6125H7.66857C7.49452 5.1766 7.42799 5.76595 7.47214 6.3525H10.615V11.1375H7.47214L7.48786 20.8125ZM3.31571 19.6875H6.28571V10.0125H9.42857V7.5H6.28571V6.93C6.28571 5.43 6.28571 4.0875 7.07143 3.585L7.22071 3.4875H9.42857V1.125H6.89857C6.38444 1.11866 5.87465 1.21553 5.40225 1.40933C4.92986 1.60314 4.50541 1.88955 4.15643 2.25C3.37071 3.1725 3.04857 4.7175 3.29214 6.855L3.37071 7.4775H1.17857V10.0125H3.31571V19.6875Z"
                fill="#192144"
              />
            </svg>
            <span class="text-hidden">Мы в Фейсбуке</span>
          </a>
          <a class="page-header__link-vk" href="https://vk.com/htmlacademy">
            <svg
              class="page-header__icon-vk"
              width="23"
              height="12"
              viewBox="0 0 23 12"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M17.7664 11.8542C17.219 11.8419 16.6854 11.6812 16.2232 11.3893C15.7407 11.065 15.2975 10.6862 14.9026 10.2604C14.5761 9.93579 14.0345 9.38979 13.8268 9.38979C13.619 9.38979 13.4706 10.0686 13.478 10.5482C13.4812 10.8792 13.3564 11.1989 13.1293 11.441C12.8712 11.6507 12.5561 11.7791 12.2242 11.8099H10.7997C8.75222 11.7651 6.79178 10.9779 5.28708 9.59639C2.55676 7.10987 0.21224 2.35818 0.115789 2.15159C0.0237889 1.97899 -0.0147389 1.78317 0.00506792 1.58882C0.0248747 1.39447 0.102128 1.21031 0.227079 1.05958C0.509857 0.825057 0.867951 0.699369 1.23611 0.705422H4.26321H4.35224C4.6027 0.741762 4.84277 0.829721 5.05708 0.963666C5.25875 1.09815 5.42022 1.28422 5.5245 1.50229C5.8444 2.18336 6.2113 2.84161 6.62256 3.47232C7.5945 4.948 8.02482 5.2874 8.18063 5.36119C8.35396 4.66929 8.40169 3.95217 8.3216 3.24359C8.3476 2.92086 8.29412 2.5967 8.16579 2.29915C8.00289 2.16957 7.80288 2.09466 7.5945 2.08518L7.05289 1.57607C6.94901 1.0891 7.49063 0.66853 7.86902 0.506205C8.62414 0.270907 9.41638 0.175863 10.2061 0.225826H10.7329C11.2686 0.211953 11.8041 0.26149 12.328 0.373394C13.5893 0.639016 13.5448 1.64986 13.4929 2.81564C13.4929 3.15505 13.4558 3.55348 13.4558 4.01094C13.4558 4.12162 13.4558 4.23967 13.4558 4.36511C13.4266 4.68633 13.4492 5.01013 13.5226 5.3243C14.1402 4.81043 14.6604 4.1907 15.0584 3.49445C15.4879 2.83611 15.865 2.14535 16.1861 1.4285C16.2839 1.20178 16.4516 1.01177 16.6649 0.885809C16.8782 0.75985 17.1262 0.704442 17.3732 0.727557H20.5487C20.6425 0.718658 20.7369 0.718658 20.8306 0.727557C21.5726 0.727557 22.0103 0.941531 22.1884 1.35472C22.3664 1.76791 22.3145 2.57953 20.4374 4.75616L19.6955 5.58992C19.336 5.93702 19.0264 6.3318 18.7755 6.76308C19.0565 7.08078 19.3754 7.36324 19.7251 7.60422C20.5778 8.24318 21.3283 9.0069 21.951 9.86939C22.097 10.0371 22.1925 10.2423 22.2266 10.4616C22.2608 10.6808 22.2321 10.9052 22.1439 11.109C21.9884 11.3346 21.7803 11.5196 21.5375 11.6481C21.2946 11.7765 21.0241 11.8447 20.749 11.8468L17.9371 11.8837L17.7664 11.8542ZM13.8268 8.28303C14.4945 8.28303 15.0732 8.86593 15.689 9.47833C16.0217 9.83957 16.3951 10.1614 16.8019 10.4375C17.1096 10.641 17.4711 10.7489 17.8406 10.7474H17.9148L20.7342 10.7105C20.8732 10.7026 21.0094 10.6675 21.1348 10.6072L21.0606 10.4892C20.499 9.72803 19.8292 9.052 19.0722 8.48225C18.1893 7.74441 17.7368 7.39762 17.6848 6.82949C17.6329 6.26135 18.0484 5.767 18.8793 4.82994L19.6213 4.01094C20.2477 3.37556 20.7619 2.6397 21.1422 1.83432C20.9767 1.82455 20.8107 1.82455 20.6451 1.83432H17.4029C17.3443 1.82128 17.2835 1.82128 17.2248 1.83432C16.8814 2.61749 16.4719 3.37032 16.0006 4.08473C14.5984 6.16543 13.938 6.44581 13.4706 6.44581C13.3257 6.44581 13.183 6.41034 13.0551 6.34251C12.3132 5.92195 12.3132 4.98489 12.3577 4.30608C12.3577 4.1954 12.3577 4.08473 12.3577 3.98881C12.3577 3.50921 12.3577 3.09602 12.3948 2.74186C12.4542 1.50229 12.3948 1.49491 12.1129 1.4285C11.6586 1.33924 11.1958 1.29965 10.7329 1.31045H10.221C9.74988 1.30077 9.27872 1.32543 8.81127 1.38423C8.88206 1.43611 8.94459 1.49829 8.99676 1.56869C9.30278 2.04854 9.4554 2.60935 9.4345 3.17718C9.53095 4.39462 9.47902 5.98097 8.69256 6.36465C8.5533 6.42946 8.40115 6.46224 8.2474 6.46057C7.5574 6.46057 6.87482 5.81127 5.70998 4.05521C5.26298 3.38283 4.86383 2.68017 4.51547 1.95237L4.45611 1.87859C4.38118 1.84061 4.30126 1.81329 4.21869 1.79742H1.25095H1.19901C1.63676 2.69759 3.71418 6.68192 6.03643 8.77001C7.34044 9.9614 9.02993 10.6497 10.7997 10.7105H12.1722C12.2422 10.6957 12.3097 10.6708 12.3726 10.6367C12.3726 10.6367 12.3726 10.6367 12.3726 10.5703C12.3726 10.3711 12.3726 8.65195 13.5448 8.35682C13.6356 8.32127 13.7302 8.29651 13.8268 8.28303Z"
                fill="#192144"
              />
            </svg>
            <span class="text-hidden">Мы в Вконтакте</span>
          </a>
          <a
            class="page-header__link-inst"
            href="https://www.instagram.com/htmlacademy"
          >
            <!-- <svg
                class="page-header__icon-inst"
                version="1.1"
                id="Layer_1"
                xmlns="http://www.w3.org/2000/svg"
                xmlns:xlink="http://www.w3.org/1999/xlink"
                x="0px"
                y="0px"
                viewBox="0 0 23 23"
                style="enable-background: new 0 0 23 23"
                xml:space="preserve"
              >
                <style type="text/css">
                  .st0 {
                    fill: #231f20;
                  }
                </style>
                <path
                  class="st0"
                  d="M17,1.5c2.5,0,4.5,2,4.5,4.5v11c0,2.5-2,4.5-4.5,4.5H6c-2.5,0-4.5-2-4.5-4.5V6c0-2.5,2-4.5,4.5-4.5L17,1.5
	 M17,0H6C2.7,0,0,2.7,0,6v11c0,3.3,2.7,6,6,6h11c3.3,0,6-2.7,6-6V6C23,2.7,20.3,0,17,0L17,0z"
                />
                <path
                  class="st0"
                  d="M11.5,7.1c2.4,0,4.4,2,4.4,4.4c0,2.4-2,4.4-4.4,4.4c-2.4,0-4.4-2-4.4-4.4C7.1,9.1,9.1,7.1,11.5,7.1 M11.5,5.6
	c-3.3,0-5.9,2.7-5.9,5.9s2.7,5.9,5.9,5.9s5.9-2.7,5.9-5.9S14.8,5.6,11.5,5.6L11.5,5.6z"
                />
                <circle class="st0" cx="17.6" cy="5.4" r="1.3" />
              </svg> -->
            <span class="text-hidden">Мы в Инстаграме</span>
          </a>
        </div>
      </div>
    </nav>
    <div class="page-header__container">
      <!-- БЛОК ЕСЛИ МЕНЮ ЗАКРЫТО -->
      <div class="page-header__btn-wrap">
        <a href="index.html" class="page-header__link">
          <span class="visually-hidden">Главная</span>
          <div class="page-header__logo">
            <picture>
              <source
                media="(min-width: 1440px)"
                srcset="img/logo-desktop-white@2x.png"
              />
              <source
                media="(min-width: 768px)"
                srcset="img/logo-tablet-white@2x.png"
              />
              <img src="img/logo-mobile-white@2x.png" alt="главная" />
            </picture>
          </div>
        </a>
        <button class="page-header__close-button" type="button">
          <span class="text-hidden">Открыть меню</span>
        </button>
        <div class="page-header__desktop-line"></div>
        <a
          class="page-header__desktop-link page-header__desktop-link-service animation"
          href="index.html"
        >
          <span data-hover="О сервисе">О сервисе</span>
        </a>
        <a
          class="page-header__desktop-link page-header__desktop-link-directions animation"
          href="form.html"
        >
          <span data-hover="Направления">Направления</span>
        </a>
        <a
          class="page-header__desktop-link page-header__desktop-link-travelers animation"
          href="catalog.html"
        >
          <span data-hover="Попутчики">Попутчики</span>
        </a>
      </div>
      <h1 class="page-header__title">
        В путешествие <br />
        с крутыми попутчиками!
      </h1>
      <div class="page-header__controls">
        <a class="page-header__controls-item" href="#">
          <span class="visually-hidden">Позвонить</span>
          <svg
            class="page-header__icon-call"
            width="19"
            height="19"
            viewBox="0 0 19 19"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              d="M9.77429 8.22389C9.77429 8.41289 9.92792 8.56139 10.1157 8.56139C10.5048 8.56139 10.8189 8.87526 10.8189 9.25664C10.8189 9.44226 10.9725 9.59414 11.1603 9.59414C11.348 9.59414 11.5017 9.44226 11.5017 9.25664C11.5017 8.50064 10.8804 7.88639 10.1157 7.88639C9.92792 7.88639 9.77429 8.03827 9.77429 8.22389ZM15.332 9.59414C15.5231 9.59414 15.6733 9.44226 15.6733 9.25664C15.6733 6.22589 13.1813 3.76215 10.1157 3.76215C9.92792 3.76215 9.77429 3.914 9.77429 4.09965C9.77429 4.28527 9.92792 4.43715 10.1157 4.43715C12.8057 4.43715 14.9906 6.60051 14.9906 9.25664C14.9906 9.44226 15.1442 9.59414 15.332 9.59414Z"
              fill="#161C35"
            />
            <path
              d="M12.9047 9.25661C12.9047 9.44223 13.0583 9.59411 13.2461 9.59411C13.4339 9.59411 13.5875 9.44223 13.5875 9.25661C13.5875 7.36324 12.0308 5.82424 10.1157 5.82424C9.9279 5.82424 9.77427 5.97612 9.77427 6.16174C9.77427 6.35074 9.9279 6.49924 10.1157 6.49924C11.6553 6.49924 12.9047 7.73786 12.9047 9.25661ZM10.1157 1.69998C9.9279 1.69998 9.77427 1.85186 9.77427 2.03748C9.77427 2.22312 9.9279 2.37498 10.1157 2.37498C13.9562 2.37498 17.0798 5.46312 17.0798 9.25661C17.0798 9.44223 17.23 9.59411 17.4212 9.59411C17.6089 9.59411 17.7626 9.44223 17.7626 9.25661C17.7626 5.0885 14.3317 1.69998 10.1157 1.69998ZM13.4509 12.8139L13.0037 13.0535C12.2493 13.4619 11.6622 14.5812 10.7312 13.7375L8.30011 11.3L6.20004 9.25661C5.14495 7.92348 6.32635 7.60623 6.73941 6.85699L6.98179 6.41825C7.25489 5.91873 7.35388 5.35849 7.27196 4.79823C7.19345 4.23799 6.93741 3.72836 6.52775 3.32336C6.02935 2.83062 5.36707 2.56062 4.66042 2.56062C3.95376 2.56062 3.28807 2.83062 2.78964 3.32336L2.61556 3.49886C1.69383 4.41012 1.588 5.97948 2.31514 7.92348C3.0013 9.77973 4.3839 11.7912 6.20004 13.5867C8.96862 16.3239 12.0513 17.9 14.2634 17.9C15.1373 17.9 15.8781 17.6536 16.4039 17.1339L16.5814 16.9584C17.0764 16.469 17.3529 15.8142 17.3563 15.1089C17.3529 14.4204 17.0695 13.7454 16.5814 13.2627C15.7587 12.4494 14.4717 12.2671 13.4509 12.8139Z"
              fill="#161C35"
            />
          </svg>
        </a>
        <a class="page-header__controls-item" href="#">
          <span class="visually-hidden">Отправить email</span>
          <svg
            class="page-header__icon-mail"
            width="19"
            height="17"
            viewBox="0 0 19 17"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              d="M2.0166 3.32528L8.7666 7.55572C8.9934 7.69747 9.2868 7.76467 9.582 7.76467C9.8772 7.76467 10.1706 7.69747 10.3974 7.55572L17.1474 3.32528C17.5875 3.04913 18.0033 1.97498 17.196 1.97498H1.9689C1.1616 1.97498 1.5774 3.04913 2.0166 3.32528ZM17.3517 5.63842L10.3974 9.86677C10.0914 10.0537 9.8772 10.0757 9.582 10.0757C9.2868 10.0757 9.0726 10.0537 8.7666 9.86677C8.4606 9.67987 2.3469 5.94082 1.8474 5.63737C1.4964 5.42317 1.5 5.67412 1.5 5.86732V13.525C1.5 13.966 2.0094 14.575 2.4 14.575H16.8C17.1906 14.575 17.7 13.966 17.7 13.525V5.86837C17.7 5.67517 17.7036 5.42422 17.3517 5.63842Z"
              fill="#161C35"
            />
          </svg>
        </a>
        <a class="page-header__controls-item" href="#"> Авторизация </a>
      </div>
      <!-- СКРОЛЛ МЕНЮ -->
      <section class="page-header__scroll-modal hidden">
        <div class="page-header__scroll-logo">
          <picture>
            <source
              media="(min-width: 1440px)"
              srcset="img/logo-desktop-blue@2x.png"
            />
            <source
              media="(min-width: 768px)"
              srcset="img/logo-desktop-blue@2x.png"
            />
            <img src="img/logo-mobile-blue@2x.png" alt="главная" />
          </picture>
        </div>
        <div class="page-header__scroll-line"></div>
        <button class="page-header__scroll-btn-main" type="button"></button>
        <a class="page-header__scroll-service" href="index.html"> О сервисе </a>
        <a class="page-header__scroll-directions" href="form.html">
          Направления
        </a>
        <a class="page-header__scroll-travelers" href="catalog.html">
          Попутчики
        </a>
        <a class="page-header__scroll-btn-call" href="#"
          ><span class="visually-hidden">Позвонить</span></a
        >
        <a class="page-header__scroll-btn-email" href="#"
          ><span class="visually-hidden">Отправить email</span></a
        >
        <a class="page-header__scroll-btn-authorization" href="#"
          >Авторизация</a
        >
      </section>
    </div>
  </header>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.page-header {
  min-width: 100%;
  width: 100%;
  background-color: #161C35;
}
@media (min-width: 768px) {
  .page-header {
    background-color: #182044;
  }
}
@media (min-width: 1440px) {
  .page-header {
    background-color: #161C35;
  }
}
.page-header__container {
  display: flex;
  flex-direction: column;
  text-align: center;
  min-width: 318px;
  width: 318px;
  min-height: 568px;
  color: #ffffff;
  background-color: #161C35;
  background-image: url(../../assets/img/traveller-illustration-mobile@1x.png), url(../../assets/img/globe-back-mobile@1x.jpg);
  background-repeat: no-repeat, no-repeat;
  background-position: 79px 221px, 0px 0px;
  border: solid 1px transparent;
  margin-left: auto;
  margin-right: auto;
}
@media (min-resolution: 2dppx) {
  .page-header__container {
    background-image: url(../../assets/img/traveller-illustration-mobile@2x.png), url(../../assets/img/globe-back-mobile@2x.jpg);
    background-repeat: no-repeat, no-repeat;
    background-position: 79px 221px, 0px 0px;
    background-size: 192px 255px, 320px 569px;
  }
}
@media (min-width: 768px) {
  .page-header__container {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr 1fr;
    grid-template-rows: 1fr 1fr 1fr 1fr;
    background-color: #182044;
    background-image: none;
    min-width: 766px;
    width: 766px;
    margin-left: auto;
    margin-right: auto;
  }
}
@media (min-width: 1440px) {
  .page-header__container {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr 1fr 1fr 1fr;
    grid-template-rows: 1fr 1fr 1fr 1fr;
    min-width: 1438px;
    width: 1438px;
    min-height: 750px;
    background-color: #182044;
    background-image: url(../../assets/img/traveller-illustration-desktop@1x.png), url(../../assets/img/globe-back-desktop@1x.jpg);
    background-repeat: no-repeat, no-repeat;
    background-position: 605px 109px, -180px 1px;
    position: relative;
    z-index: 10;
    margin-left: auto;
    margin-right: auto;
  }
}
@media (min-width: 1440px) and (min-resolution: 2dppx) {
  .page-header__container {
    background-image: url(../../assets/img/traveller-illustration-desktop@2x.png), url(../../assets/img/globe-back-desktop@2x.jpg);
    background-repeat: no-repeat, no-repeat;
    background-position: 603px 109px, 0px 0px;
    background-size: 431px 640px, 1440px 750px;
  }
}
.page-header__nav-modal {
  position: absolute;
  min-width: 100%;
  width: 100%;
  background-color: #FFFFFF;
}
.page-header__nav-modal-container {
  display: flex;
  flex-direction: column;
  min-height: 568px;
  background-color: #FFFFFF;
  text-align: center;
  text-transform: uppercase;
  min-width: 318px;
  width: 318px;
  margin-left: auto;
  margin-right: auto;
  padding-top: 4px;
  box-sizing: border-box;
  border: solid 1px transparent;
}
@media (min-width: 768px) {
  .page-header__nav-modal-container {
    display: grid;
    grid-template-columns: 1fr 1fr;
    grid-template-rows: 0.5fr 0.5fr 0.5fr 0.5fr 1fr 1fr;
    min-width: 766px;
    width: 766px;
    margin-left: auto;
    margin-right: auto;
    min-height: 910px;
    padding-top: 0px;
    padding-left: 6px;
  }
}
@media (min-width: 1440px) {
  .page-header__nav-modal-container {
    display: none;
  }
}
.page-header__btn-wrap {
  display: flex;
  justify-content: space-between;
  align-items: center;
  border: 1px solid transparent;
  margin-bottom: 50px;
}
@media (min-width: 768px) {
  .page-header__btn-wrap {
    grid-column-start: 1;
    grid-column-end: 3;
    grid-row-start: 1;
    margin-top: -24px;
    margin-bottom: 0px;
    margin-left: 80px;
    margin-right: -36px;
  }
}
@media (min-width: 768px) and (min-width: 1440px) {
  .page-header__btn-wrap {
    grid-column-start: 1;
    grid-column-end: 5;
    grid-row-start: 1;
    display: flex;
    justify-content: flex-start;
    margin-top: -37px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
  }
}
.page-header__modal-btn-wrap {
  display: flex;
  justify-content: space-between;
  align-items: center;
  border: 1px solid transparent;
  box-sizing: border-box;
  margin: 0px 0px 64px 0px;
  padding: 13px 0px 0px 20px;
}
@media (min-width: 768px) {
  .page-header__modal-btn-wrap {
    grid-column-start: 1;
    grid-column-end: 3;
    grid-row-start: 1;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
  }
}
.page-header__button {
  width: 30px;
  height: 30px;
  border: none;
  background-color: transparent;
  background-image: url("../../assets/img/icon-menu-mobile-close.svg");
  background-repeat: no-repeat;
  background-position: center;
  margin-right: 22px;
}
@media (min-width: 768px) {
  .page-header__button {
    grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 1;
    margin: 21px 373px 0px 0px;
    padding: 0px 0px 0px 0px;
  }
}
.page-header__social {
  display: flex;
  justify-content: space-between;
  align-items: center;
  align-self: center;
  width: 115px;
  margin-top: 38px;
}
@media (min-width: 768px) {
  .page-header__social {
    grid-column-start: 1;
    grid-row-start: 6;
    margin: 11px 0px 0px 107px;
    width: 150px;
  }
}
.page-header__social a {
  display: flex;
  justify-content: center;
  align-items: center;
}
.page-header__social a:hover {
  fill-opacity: 0.3;
}
.page-header__social a:active {
  fill-opacity: 0.5;
}
.page-header__link-fb {
  display: inline-block;
  width: 25px;
  height: 25px;
  background-color: transparent;
}
@media (min-width: 768px) {
  .page-header__link-fb {
    width: 33px;
    height: 33px;
    margin: -1px 0px 0px -4px;
  }
}
.page-header__link-vk {
  display: inline-block;
  width: 25px;
  height: 25px;
}
@media (min-width: 768px) {
  .page-header__link-vk {
    width: 35px;
    height: 35px;
    margin: 0px 0px 0px 0px;
  }
}
.page-header__link-inst {
  display: inline-block;
  width: 25px;
  height: 25px;
}
@media (min-width: 768px) {
  .page-header__link-inst {
    width: 35px;
    height: 35px;
    margin: 0px 0px 0px 0px;
  }
}
.page-header__icon-fb {
  width: 11px;
  height: 21px;
}
@media (min-width: 768px) {
  .page-header__icon-fb {
    width: 14px;
    height: 28px;
  }
}
.page-header__icon-vk {
  width: 23px;
  height: 12px;
}
@media (min-width: 768px) {
  .page-header__icon-vk {
    width: 31px;
    height: 16px;
  }
}
.page-header__icon-inst {
  width: 18px;
  height: 18px;
}
@media (min-width: 768px) {
  .page-header__icon-inst {
    width: 24px;
    height: 24px;
  }
}
.page-header__title {
  display: inline-block;
  align-self: center;
  font-family: "Blogger Sans", Arial, sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 36px;
  line-height: 40px;
  color: #FFFFFF;
  margin-top: -12px;
}
@media (min-width: 768px) {
  .page-header__title {
    grid-column-start: 2;
    grid-column-end: 4;
    grid-row-start: 2;
    grid-row-end: 4;
    width: 400px;
    font-size: 60px;
    line-height: 70px;
    text-align: center;
    margin-top: -43px;
    margin-bottom: 0px;
    margin-left: -9px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .page-header__title {
    grid-column-start: 1;
    grid-column-end: 4;
    grid-row-start: 2;
    grid-row-end: 4;
    display: inline-block;
    width: 418px;
    height: 210px;
    font-size: 60px;
    line-height: 70px;
    text-align: left;
    margin-top: -133px;
    margin-bottom: 0px;
    margin-left: 128px;
    margin-right: 0px;
  }
}
.page-header__logo-open {
  width: 100px;
  height: 15px;
  margin: -20px 0px 0px 0px;
}
@media (min-width: 768px) {
  .page-header__logo-open {
    display: inline-block;
    width: 164px;
    height: 42px;
    margin: 8px 0px 0px 6px;
  }
}
@media (min-width: 1440px) {
  .page-header__logo-open {
    display: none;
  }
}
.page-header__logo-modal-tablet {
  display: none;
}
@media (min-width: 768px) {
  .page-header__logo-modal-tablet {
    display: block;
    grid-column-start: 1;
    grid-column-end: 2;
    grid-row-start: 1;
    grid-row-end: 2;
    margin: -69px 0px 0px 34px;
    padding: 0px 0px 0px 0px;
  }
}
.page-header__logo {
  width: 100px;
  height: 20px;
  margin-top: 22px;
  margin-left: 23px;
}
@media (min-width: 768px) {
  .page-header__logo {
    width: 166px;
    height: 42px;
    margin-top: 13px;
    margin-bottom: 0px;
    margin-left: -43px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .page-header__logo {
    width: 200px;
    height: 63px;
    margin-top: 4px;
    margin-bottom: 0px;
    margin-left: 59px;
    margin-right: 0px;
  }
}
.page-header__nav-item {
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: 500;
  font-size: 30px;
  line-height: 35px;
  color: #192144;
}
@media (min-width: 768px) {
  .page-header__nav-item {
    font-style: normal;
    font-weight: 500;
    font-size: 60px;
    line-height: 71px;
    text-transform: uppercase;
  }
}
.page-header__nav-item-link {
  margin: 0px 0px 0px 0px;
  padding: 0px 0px 0px 0px;
}
@media (min-width: 768px) {
  .page-header__nav-item:nth-child(2) {
    grid-column-start: 1;
    grid-column-end: 2;
    grid-row-start: 2;
    margin: 69px 0px 0px 71px;
    padding: 0px 0px 0px 0px;
  }
}
@media (min-width: 768px) {
  .page-header__nav-item:nth-child(3) {
    grid-column-start: 1;
    grid-column-end: 3;
    grid-row-start: 3;
    margin: 0px 0px 0px -202px;
    padding: 0px 0px 0px 0px;
  }
}
@media (min-width: 768px) {
  .page-header__nav-item:nth-child(4) {
    grid-column-start: 1;
    grid-column-end: 3;
    grid-row-start: 4;
    margin: -38px 0px 0px -277px;
    padding: 0px 0px 0px 0px;
  }
}
.page-header__nav-button {
  display: block;
  width: 270px;
  height: 50px;
  margin: 0 auto;
  margin-top: 54px;
  font-style: normal;
  font-weight: bold;
  font-size: 17px;
  line-height: 50px;
  background-color: #FFD74B;
  border-radius: 25px;
}
@media (min-width: 768px) {
  .page-header__nav-button {
    grid-column-start: 2;
    grid-row-start: 1;
    width: 188px;
    height: 50px;
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: normal;
    font-size: 20px;
    line-height: 51px;
    text-align: center;
    letter-spacing: 0.03em;
    text-transform: uppercase;
    margin: 39px 0px 0px 151px;
  }
}
.page-header__contact-wrap {
  display: grid;
  grid-template-columns: 1fr 3fr;
  grid-template-rows: 1fr 1fr;
  border: solid 1px transparent;
  margin-top: 50px;
}
@media (min-width: 768px) {
  .page-header__contact-wrap {
    grid-column-start: 1;
    grid-column-end: 3;
    grid-row-start: 5;
    grid-row-end: 6;
    margin: 54px 0px 0px -1px;
    width: 527px;
    height: 126px;
  }
}
.page-header__nav-call {
  display: inline-block;
  width: 45px;
  height: 45px;
  border-radius: 50%;
  font-style: normal;
  font-weight: bold;
  font-size: 16px;
  line-height: 18px;
  background-color: #121936;
  background-image: url("../../assets/img/icon-telephone-yellow.svg");
  background-repeat: no-repeat;
  background-position: center;
  background-size: 17px 16px;
  margin-left: 23px;
}
@media (min-width: 768px) {
  .page-header__nav-call {
    width: 68px;
    height: 68px;
    background-size: 27px 26px;
    margin: -1px 0px 0px 88px;
  }
}
.page-header__nav-email {
  display: block;
  width: 45px;
  height: 45px;
  border-radius: 50%;
  font-style: normal;
  font-weight: bold;
  font-size: 16px;
  line-height: 18px;
  background-color: #121936;
  background-image: url("../../assets/img/icon-mail-yellow.svg");
  background-repeat: no-repeat;
  background-position: center;
  background-size: 17px 16px;
  margin-left: 23px;
}
@media (min-width: 768px) {
  .page-header__nav-email {
    width: 68px;
    height: 68px;
    background-size: 29px 29px;
    margin: 0px 0px 0px 88px;
  }
}
.page-header__link-text {
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 16px;
  line-height: 18px;
  color: #192144;
  text-align: left;
  margin-top: 14px;
  margin-left: 4px;
  cursor: pointer;
}
@media (min-width: 768px) {
  .page-header__link-text {
    font-style: normal;
    font-weight: bold;
    font-size: 28px;
    line-height: 0px;
    margin: 36px 0px 0px 22px;
    padding: 0px 0px 0px 0px;
  }
}
.page-header__controls {
  display: flex;
  justify-content: center;
  margin-top: 222px;
}
@media (min-width: 768px) {
  .page-header__controls {
    grid-column-start: 4;
    grid-row-start: 1;
    margin-top: 39px;
    margin-bottom: 0px;
    margin-left: -75px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .page-header__controls {
    grid-column-start: 5;
    grid-column-end: 7;
    grid-row-start: 1;
    margin-top: 48px;
    margin-bottom: 0px;
    margin-left: 77px;
    margin-right: 0px;
  }
}
.page-header__controls-item:nth-child(1) {
  display: inline-block;
  width: 40px;
  height: 40px;
  background-color: #FF8D30;
  border-radius: 50%;
}
@media (min-width: 768px) {
  .page-header__controls-item:nth-child(1) {
    display: none;
  }
}
@media (min-width: 1440px) {
  .page-header__controls-item:nth-child(1) {
    display: block;
    width: 50px;
    height: 50px;
  }
}
@media (min-width: 1440px) {
  .page-header__controls-item:nth-child(1):hover {
    background-color: #F26926;
  }
}
@media (min-width: 1440px) {
  .page-header__controls-item:nth-child(1):active {
    background-color: #F26926;
    fill-opacity: 0.3;
  }
}
.page-header__controls-item:nth-child(2) {
  display: inline-block;
  width: 40px;
  height: 40px;
  background-color: #FFBD30;
  border-radius: 50%;
}
@media (min-width: 768px) {
  .page-header__controls-item:nth-child(2) {
    display: none;
  }
}
@media (min-width: 1440px) {
  .page-header__controls-item:nth-child(2) {
    display: block;
    width: 50px;
    height: 50px;
  }
}
@media (min-width: 1440px) {
  .page-header__controls-item:nth-child(2):hover {
    background-color: #FF8D30;
  }
}
@media (min-width: 1440px) {
  .page-header__controls-item:nth-child(2):active {
    background-color: #FF8D30;
    fill-opacity: 0.3;
  }
}
.page-header__controls-item:nth-child(3) {
  display: inline-block;
  width: 190px;
  height: 40px;
  background-color: #FFD74B;
  border-radius: 25px;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 20px;
  line-height: 44px;
  text-align: center;
  text-transform: uppercase;
  color: #161C35;
}
@media (min-width: 768px) {
  .page-header__controls-item:nth-child(3) {
    width: 190px;
    height: 50px;
  }
}
@media (min-width: 1440px) {
  .page-header__controls-item:nth-child(3) {
    width: 189px;
    height: 50px;
    font-style: normal;
    font-weight: bold;
    font-size: 20px;
    line-height: 49px;
    margin: 0px 0px 0px 0px;
    padding: 0px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .page-header__controls-item:nth-child(3):hover {
    background-color: #FFBD30;
  }
}
@media (min-width: 1440px) {
  .page-header__controls-item:nth-child(3):active {
    background-color: #FFBD30;
    color: rgba(0, 0, 0, 0.3);
  }
}
.page-header__close-button {
  width: 30px;
  height: 20px;
  background-color: transparent;
  background-image: url(../../assets/img/icon-menu-mobile.svg);
  background-repeat: no-repeat;
  border: none;
  margin-top: 29px;
  margin-right: 20px;
}
@media (min-width: 768px) {
  .page-header__close-button {
    margin: 21px 18px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .page-header__close-button {
    display: none;
  }
}
.page-header__desktop-line {
  display: none;
}
@media (min-width: 1440px) {
  .page-header__desktop-line {
    display: block;
    width: 60px;
    height: 1px;
    background-color: #FFFFFF;
    margin: -2px 0px 0px 40px;
  }
}
.page-header__desktop-link {
  display: none;
}
@media (min-width: 1440px) {
  .page-header__desktop-link {
    display: inline-block;
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 20px;
    text-transform: uppercase;
    color: #FFFFFF;
    margin: 0px 0px 0px 0px;
  }
}
.page-header__desktop-link:hover {
  color: #FFD74B;
}
.page-header__desktop-link:active {
  color: #FFD74B;
  opacity: 0.3;
}
.page-header__desktop-link-service {
  display: none;
}
@media (min-width: 1440px) {
  .page-header__desktop-link-service {
    display: inline-block;
    margin: -2px 0px 0px 41px;
  }
}
.page-header__desktop-link-directions {
  display: none;
}
@media (min-width: 1440px) {
  .page-header__desktop-link-directions {
    display: inline-block;
    margin: -2px 0px 0px 26px;
  }
}
.page-header__desktop-link-travelers {
  display: none;
}
@media (min-width: 1440px) {
  .page-header__desktop-link-travelers {
    display: inline-block;
    margin: -2px 0px 0px 26px;
  }
}
.page-header__scroll-modal {
  display: none;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  width: 320px;
  height: 73px;
  background-color: #FFFFFF;
  box-sizing: border-box;
  border: solid 1px transparent;
  margin: 0px 0px 0px 0px;
  padding: 0px 0px 0px 0px;
  position: absolute;
  transform: translate(0%, 0%);
}
@media (min-width: 768px) {
  .page-header__scroll-modal {
    position: absolute;
    transform: translate(0%, -1%);
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    width: 766px;
    height: 132px;
    background-color: #FFFFFF;
    box-sizing: border-box;
    border: solid 1px transparent;
    margin: 0px 0px 0px 0px;
    padding: 0px 38px 0px 38px;
  }
}
@media (min-width: 1440px) {
  .page-header__scroll-modal {
    position: absolute;
    transform: translate(0%, 832%);
    display: flex;
    flex-direction: row;
    justify-content: start;
    align-items: center;
    width: 100%;
    height: 90px;
    background-color: #FFFFFF;
    margin: 0px 0px 0px 0px;
    padding: 0px 0px 0px 0px;
  }
}
.page-header__scroll-logo {
  display: none;
}
@media (min-width: 768px) {
  .page-header__scroll-logo {
    display: block;
    width: 164px;
    height: 42px;
    margin: 0px 0px 0px 0px;
    padding: 0px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .page-header__scroll-logo {
    display: inline-block;
    width: 198px;
    height: 60px;
    margin: 11px 0px 0px 40px;
    cursor: pointer;
  }
}
.page-header__scroll-line {
  display: none;
}
@media (min-width: 768px) {
  .page-header__scroll-line {
    display: none;
  }
}
@media (min-width: 1440px) {
  .page-header__scroll-line {
    display: inline-block;
    width: 44px;
    height: 2px;
    background-color: #192144;
    margin: 2px 0px 0px 58px;
  }
}
.page-header__scroll-btn-main {
  display: none;
}
@media (min-width: 768px) {
  .page-header__scroll-btn-main {
    display: block;
    width: 26px;
    height: 12px;
    border: none;
    background-color: transparent;
    background-image: url(../../assets/img/scroll-btn-main.svg);
    background-position: center;
    background-repeat: no-repeat;
    margin: 2px 0px 0px 21px;
    padding: 0px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .page-header__scroll-btn-main {
    display: none;
  }
}
.page-header__scroll-service {
  display: none;
}
@media (min-width: 768px) {
  .page-header__scroll-service {
    display: none;
  }
}
@media (min-width: 1440px) {
  .page-header__scroll-service {
    display: inline-block;
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 20px;
    text-transform: uppercase;
    color: #192144;
    margin: 2px 0px 0px 40px;
  }
}
.page-header__scroll-directions {
  display: none;
}
@media (min-width: 768px) {
  .page-header__scroll-directions {
    display: none;
  }
}
@media (min-width: 1440px) {
  .page-header__scroll-directions {
    display: inline-block;
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 20px;
    text-transform: uppercase;
    color: #192144;
    margin: 2px 0px 0px 34px;
  }
}
.page-header__scroll-travelers {
  display: none;
}
@media (min-width: 768px) {
  .page-header__scroll-travelers {
    display: none;
  }
}
@media (min-width: 1440px) {
  .page-header__scroll-travelers {
    display: inline-block;
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 20px;
    text-transform: uppercase;
    color: #192144;
    margin: 2px 0px 0px 34px;
  }
}
.page-header__scroll-btn-call {
  display: none;
}
@media (min-width: 768px) {
  .page-header__scroll-btn-call {
    display: none;
  }
}
@media (min-width: 1440px) {
  .page-header__scroll-btn-call {
    display: inline-block;
    width: 50px;
    height: 50px;
    border-radius: 50%;
    background-color: #FF8D30;
    background-image: url(../../assets/img/scroll-icon-call.svg);
    background-repeat: no-repeat;
    background-position: center;
    margin: 1px 0px 0px 297px;
  }
}
.page-header__scroll-btn-email {
  display: none;
}
@media (min-width: 768px) {
  .page-header__scroll-btn-email {
    display: none;
  }
}
@media (min-width: 1440px) {
  .page-header__scroll-btn-email {
    display: inline-block;
    width: 50px;
    height: 50px;
    border-radius: 50%;
    background-color: #FFBD30;
    background-image: url(../../assets/img/scroll-icon-email.svg);
    background-repeat: no-repeat;
    background-position: center;
    margin: 1px 0px 0px 0px;
  }
}
.page-header__scroll-btn-authorization {
  display: none;
}
@media (min-width: 768px) {
  .page-header__scroll-btn-authorization {
    display: inline-block;
    width: 188px;
    height: 50px;
    border-radius: 25px;
    background-color: #FFD74B;
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: bold;
    font-size: 20px;
    line-height: 48px;
    text-align: center;
    text-transform: uppercase;
    color: #161C35;
    margin: 0px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .page-header__scroll-btn-authorization {
    display: inline-block;
    width: 188px;
    height: 50px;
    border-radius: 25px;
    background-color: #FFD74B;
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: bold;
    font-size: 20px;
    line-height: 48px;
    text-align: center;
    text-transform: uppercase;
    color: #161C35;
    margin: 1px 0px 0px 0px;
  }
}
.hidden {
  display: none;
}
.page-header__icon-call {
  margin: 15px auto 0px auto;
}
.page-header__icon-mail {
  margin: 15px auto 0px auto;
}
</style>