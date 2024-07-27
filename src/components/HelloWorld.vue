<template>

  <body class="page-body">
    <header class="page-header">
      <!-- ОТКРЫТОЕ МЕНЮ МОДАЛЬНОЕ -->
      <nav class="page-header__nav-modal">
        <div class="page-header__nav-modal-container">
          <div class="page-header__modal-btn-wrap">
            <a href="#" class="page-header__nav-item-link">
              <span class="text-hidden">Главная</span>

              <div class="page-header__logo-open">
                <picture>
                  <source media="(min-width: 1440px)" srcset="img/logo-desktop-blue@2x.png" />
                  <source media="(min-width: 768px)" srcset="img/logo-desktop-blue@2x.png" />
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
            <a class="page-header__nav-call" href="tel:+88005558628"><span class="text-hidden">Позвонить</span></a>
            <span class="page-header__link-text">8 800 555-86-28</span>

            <a class="page-header__nav-email" href="mailto:mail@htmlacademy.ru"><span class="text-hidden">Отправить
                email</span></a>
            <span class="page-header__link-text">mail@htmlacademy.ru</span>
          </div>
          <div class="page-header__social">
            <a class="page-header__link-fb" href="https://www.facebook.com/htmlacademy">
              <svg class="page-header__icon-fb" width="11" height="21" viewBox="0 0 11 21" fill="none"
                xmlns="http://www.w3.org/2000/svg">
                <path
                  d="M7.48786 20.8125H2.12929V11.1375H0V6.3525H2.06643C1.90929 4.185 2.30214 2.6025 3.26071 1.5225C3.71777 1.04316 4.27461 0.66015 4.89562 0.397985C5.51662 0.13582 6.18812 0.000268301 6.86714 0L10.6229 0V4.6125H7.66857C7.49452 5.1766 7.42799 5.76595 7.47214 6.3525H10.615V11.1375H7.47214L7.48786 20.8125ZM3.31571 19.6875H6.28571V10.0125H9.42857V7.5H6.28571V6.93C6.28571 5.43 6.28571 4.0875 7.07143 3.585L7.22071 3.4875H9.42857V1.125H6.89857C6.38444 1.11866 5.87465 1.21553 5.40225 1.40933C4.92986 1.60314 4.50541 1.88955 4.15643 2.25C3.37071 3.1725 3.04857 4.7175 3.29214 6.855L3.37071 7.4775H1.17857V10.0125H3.31571V19.6875Z"
                  fill="#192144" />
              </svg>
              <span class="text-hidden">Мы в Фейсбуке</span>
            </a>
            <a class="page-header__link-vk" href="https://vk.com/htmlacademy">
              <svg class="page-header__icon-vk" width="23" height="12" viewBox="0 0 23 12" fill="none"
                xmlns="http://www.w3.org/2000/svg">
                <path
                  d="M17.7664 11.8542C17.219 11.8419 16.6854 11.6812 16.2232 11.3893C15.7407 11.065 15.2975 10.6862 14.9026 10.2604C14.5761 9.93579 14.0345 9.38979 13.8268 9.38979C13.619 9.38979 13.4706 10.0686 13.478 10.5482C13.4812 10.8792 13.3564 11.1989 13.1293 11.441C12.8712 11.6507 12.5561 11.7791 12.2242 11.8099H10.7997C8.75222 11.7651 6.79178 10.9779 5.28708 9.59639C2.55676 7.10987 0.21224 2.35818 0.115789 2.15159C0.0237889 1.97899 -0.0147389 1.78317 0.00506792 1.58882C0.0248747 1.39447 0.102128 1.21031 0.227079 1.05958C0.509857 0.825057 0.867951 0.699369 1.23611 0.705422H4.26321H4.35224C4.6027 0.741762 4.84277 0.829721 5.05708 0.963666C5.25875 1.09815 5.42022 1.28422 5.5245 1.50229C5.8444 2.18336 6.2113 2.84161 6.62256 3.47232C7.5945 4.948 8.02482 5.2874 8.18063 5.36119C8.35396 4.66929 8.40169 3.95217 8.3216 3.24359C8.3476 2.92086 8.29412 2.5967 8.16579 2.29915C8.00289 2.16957 7.80288 2.09466 7.5945 2.08518L7.05289 1.57607C6.94901 1.0891 7.49063 0.66853 7.86902 0.506205C8.62414 0.270907 9.41638 0.175863 10.2061 0.225826H10.7329C11.2686 0.211953 11.8041 0.26149 12.328 0.373394C13.5893 0.639016 13.5448 1.64986 13.4929 2.81564C13.4929 3.15505 13.4558 3.55348 13.4558 4.01094C13.4558 4.12162 13.4558 4.23967 13.4558 4.36511C13.4266 4.68633 13.4492 5.01013 13.5226 5.3243C14.1402 4.81043 14.6604 4.1907 15.0584 3.49445C15.4879 2.83611 15.865 2.14535 16.1861 1.4285C16.2839 1.20178 16.4516 1.01177 16.6649 0.885809C16.8782 0.75985 17.1262 0.704442 17.3732 0.727557H20.5487C20.6425 0.718658 20.7369 0.718658 20.8306 0.727557C21.5726 0.727557 22.0103 0.941531 22.1884 1.35472C22.3664 1.76791 22.3145 2.57953 20.4374 4.75616L19.6955 5.58992C19.336 5.93702 19.0264 6.3318 18.7755 6.76308C19.0565 7.08078 19.3754 7.36324 19.7251 7.60422C20.5778 8.24318 21.3283 9.0069 21.951 9.86939C22.097 10.0371 22.1925 10.2423 22.2266 10.4616C22.2608 10.6808 22.2321 10.9052 22.1439 11.109C21.9884 11.3346 21.7803 11.5196 21.5375 11.6481C21.2946 11.7765 21.0241 11.8447 20.749 11.8468L17.9371 11.8837L17.7664 11.8542ZM13.8268 8.28303C14.4945 8.28303 15.0732 8.86593 15.689 9.47833C16.0217 9.83957 16.3951 10.1614 16.8019 10.4375C17.1096 10.641 17.4711 10.7489 17.8406 10.7474H17.9148L20.7342 10.7105C20.8732 10.7026 21.0094 10.6675 21.1348 10.6072L21.0606 10.4892C20.499 9.72803 19.8292 9.052 19.0722 8.48225C18.1893 7.74441 17.7368 7.39762 17.6848 6.82949C17.6329 6.26135 18.0484 5.767 18.8793 4.82994L19.6213 4.01094C20.2477 3.37556 20.7619 2.6397 21.1422 1.83432C20.9767 1.82455 20.8107 1.82455 20.6451 1.83432H17.4029C17.3443 1.82128 17.2835 1.82128 17.2248 1.83432C16.8814 2.61749 16.4719 3.37032 16.0006 4.08473C14.5984 6.16543 13.938 6.44581 13.4706 6.44581C13.3257 6.44581 13.183 6.41034 13.0551 6.34251C12.3132 5.92195 12.3132 4.98489 12.3577 4.30608C12.3577 4.1954 12.3577 4.08473 12.3577 3.98881C12.3577 3.50921 12.3577 3.09602 12.3948 2.74186C12.4542 1.50229 12.3948 1.49491 12.1129 1.4285C11.6586 1.33924 11.1958 1.29965 10.7329 1.31045H10.221C9.74988 1.30077 9.27872 1.32543 8.81127 1.38423C8.88206 1.43611 8.94459 1.49829 8.99676 1.56869C9.30278 2.04854 9.4554 2.60935 9.4345 3.17718C9.53095 4.39462 9.47902 5.98097 8.69256 6.36465C8.5533 6.42946 8.40115 6.46224 8.2474 6.46057C7.5574 6.46057 6.87482 5.81127 5.70998 4.05521C5.26298 3.38283 4.86383 2.68017 4.51547 1.95237L4.45611 1.87859C4.38118 1.84061 4.30126 1.81329 4.21869 1.79742H1.25095H1.19901C1.63676 2.69759 3.71418 6.68192 6.03643 8.77001C7.34044 9.9614 9.02993 10.6497 10.7997 10.7105H12.1722C12.2422 10.6957 12.3097 10.6708 12.3726 10.6367C12.3726 10.6367 12.3726 10.6367 12.3726 10.5703C12.3726 10.3711 12.3726 8.65195 13.5448 8.35682C13.6356 8.32127 13.7302 8.29651 13.8268 8.28303Z"
                  fill="#192144" />
              </svg>
              <span class="text-hidden">Мы в Вконтакте</span>
            </a>
            <a class="page-header__link-inst" href="https://www.instagram.com/htmlacademy">
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
                <source media="(min-width: 1440px)" srcset="img/logo-desktop-white@2x.png" />
                <source media="(min-width: 768px)" srcset="img/logo-tablet-white@2x.png" />
                <img src="img/logo-mobile-white@2x.png" alt="главная" />
              </picture>
            </div>
          </a>
          <button class="page-header__close-button" type="button">
            <span class="text-hidden">Открыть меню</span>
          </button>
          <div class="page-header__desktop-line"></div>
          <a class="page-header__desktop-link page-header__desktop-link-service animation" href="index.html">
            <span data-hover="О сервисе">О сервисе</span>
          </a>
          <a class="page-header__desktop-link page-header__desktop-link-directions animation" href="form.html">
            <span data-hover="Направления">Направления</span>
          </a>
          <a class="page-header__desktop-link page-header__desktop-link-travelers animation" href="catalog.html">
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
            <svg class="page-header__icon-call" width="19" height="19" viewBox="0 0 19 19" fill="none"
              xmlns="http://www.w3.org/2000/svg">
              <path
                d="M9.77429 8.22389C9.77429 8.41289 9.92792 8.56139 10.1157 8.56139C10.5048 8.56139 10.8189 8.87526 10.8189 9.25664C10.8189 9.44226 10.9725 9.59414 11.1603 9.59414C11.348 9.59414 11.5017 9.44226 11.5017 9.25664C11.5017 8.50064 10.8804 7.88639 10.1157 7.88639C9.92792 7.88639 9.77429 8.03827 9.77429 8.22389ZM15.332 9.59414C15.5231 9.59414 15.6733 9.44226 15.6733 9.25664C15.6733 6.22589 13.1813 3.76215 10.1157 3.76215C9.92792 3.76215 9.77429 3.914 9.77429 4.09965C9.77429 4.28527 9.92792 4.43715 10.1157 4.43715C12.8057 4.43715 14.9906 6.60051 14.9906 9.25664C14.9906 9.44226 15.1442 9.59414 15.332 9.59414Z"
                fill="#161C35" />
              <path
                d="M12.9047 9.25661C12.9047 9.44223 13.0583 9.59411 13.2461 9.59411C13.4339 9.59411 13.5875 9.44223 13.5875 9.25661C13.5875 7.36324 12.0308 5.82424 10.1157 5.82424C9.9279 5.82424 9.77427 5.97612 9.77427 6.16174C9.77427 6.35074 9.9279 6.49924 10.1157 6.49924C11.6553 6.49924 12.9047 7.73786 12.9047 9.25661ZM10.1157 1.69998C9.9279 1.69998 9.77427 1.85186 9.77427 2.03748C9.77427 2.22312 9.9279 2.37498 10.1157 2.37498C13.9562 2.37498 17.0798 5.46312 17.0798 9.25661C17.0798 9.44223 17.23 9.59411 17.4212 9.59411C17.6089 9.59411 17.7626 9.44223 17.7626 9.25661C17.7626 5.0885 14.3317 1.69998 10.1157 1.69998ZM13.4509 12.8139L13.0037 13.0535C12.2493 13.4619 11.6622 14.5812 10.7312 13.7375L8.30011 11.3L6.20004 9.25661C5.14495 7.92348 6.32635 7.60623 6.73941 6.85699L6.98179 6.41825C7.25489 5.91873 7.35388 5.35849 7.27196 4.79823C7.19345 4.23799 6.93741 3.72836 6.52775 3.32336C6.02935 2.83062 5.36707 2.56062 4.66042 2.56062C3.95376 2.56062 3.28807 2.83062 2.78964 3.32336L2.61556 3.49886C1.69383 4.41012 1.588 5.97948 2.31514 7.92348C3.0013 9.77973 4.3839 11.7912 6.20004 13.5867C8.96862 16.3239 12.0513 17.9 14.2634 17.9C15.1373 17.9 15.8781 17.6536 16.4039 17.1339L16.5814 16.9584C17.0764 16.469 17.3529 15.8142 17.3563 15.1089C17.3529 14.4204 17.0695 13.7454 16.5814 13.2627C15.7587 12.4494 14.4717 12.2671 13.4509 12.8139Z"
                fill="#161C35" />
            </svg>
          </a>
          <a class="page-header__controls-item" href="#">
            <span class="visually-hidden">Отправить email</span>
            <svg class="page-header__icon-mail" width="19" height="17" viewBox="0 0 19 17" fill="none"
              xmlns="http://www.w3.org/2000/svg">
              <path
                d="M2.0166 3.32528L8.7666 7.55572C8.9934 7.69747 9.2868 7.76467 9.582 7.76467C9.8772 7.76467 10.1706 7.69747 10.3974 7.55572L17.1474 3.32528C17.5875 3.04913 18.0033 1.97498 17.196 1.97498H1.9689C1.1616 1.97498 1.5774 3.04913 2.0166 3.32528ZM17.3517 5.63842L10.3974 9.86677C10.0914 10.0537 9.8772 10.0757 9.582 10.0757C9.2868 10.0757 9.0726 10.0537 8.7666 9.86677C8.4606 9.67987 2.3469 5.94082 1.8474 5.63737C1.4964 5.42317 1.5 5.67412 1.5 5.86732V13.525C1.5 13.966 2.0094 14.575 2.4 14.575H16.8C17.1906 14.575 17.7 13.966 17.7 13.525V5.86837C17.7 5.67517 17.7036 5.42422 17.3517 5.63842Z"
                fill="#161C35" />
            </svg>
          </a>
          <a class="page-header__controls-item" href="#"> Авторизация </a>
        </div>
        <!-- СКРОЛЛ МЕНЮ -->
        <section class="page-header__scroll-modal hidden">
          <div class="page-header__scroll-logo">
            <picture>
              <source media="(min-width: 1440px)" srcset="img/logo-desktop-blue@2x.png" />
              <source media="(min-width: 768px)" srcset="img/logo-desktop-blue@2x.png" />
              <img src="img/logo-mobile-blue@2x.png" alt="главная" />
            </picture>
          </div>
          <div class="page-header__scroll-line"></div>
          <button class="page-header__scroll-btn-main" type="button"></button>
          <a class="page-header__scroll-service" href="index.html">
            О сервисе
          </a>
          <a class="page-header__scroll-directions" href="form.html">
            Направления
          </a>
          <a class="page-header__scroll-travelers" href="catalog.html">
            Попутчики
          </a>
          <a class="page-header__scroll-btn-call" href="#"><span class="visually-hidden">Позвонить</span></a>
          <a class="page-header__scroll-btn-email" href="#"><span class="visually-hidden">Отправить email</span></a>
          <a class="page-header__scroll-btn-authorization" href="#">Авторизация</a>
        </section>
      </div>
    </header>
    <main class="page-main">
      <section class="guide">
        <div class="guide__container">
          <blockquote class="guide__quote">
            «Лучшее приложение, что я видел в жизни!»
          </blockquote>
          <b class="guide__slogan">
            Мурат Эльтазин главный редактор газеты «гаджетлайф»
          </b>
          <ul class="guide__list">
            <li class="guide__item">
              <span class="guide__text">Выберите <br />
                направление</span>
              <span class="guide__number">1</span>
            </li>
            <li class="guide__item">
              <span class="guide__text">Изучите идеи <br />
                путешественников</span>
              <span class="guide__number">2</span>
            </li>
            <li class="guide__item">
              <span class="guide__text">Находите тех, <br />
                кто похож на вас</span>
              <span class="guide__number">3</span>
            </li>
            <li class="guide__item">
              <span class="guide__text">Путешествуйте <br />
                вместе!</span>
              <span class="guide__number">4</span>
            </li>
          </ul>
        </div>
      </section>
      <!-- БЛОК ОПИСАНИЯ СЕРВИСА -->
      <section class="about">
        <div class="about__container">
          <h2 class="about__title">О сервисе</h2>
          <blockquote class="about__quote">
            Любое путешествие веселее с попутчиками, которые на одной волне с
            тобой! Делитесь своими идеями путешествий и черпайте вдохновение в
            чужих.
          </blockquote>
          <b class="about__slogan">
            А если найдете кого-то близкого по духу —- скорее зовите в
            совместный трип!
          </b>
          <a class="about__btn" href="#"><span class="about__btn-text">Подробнее</span></a>
        </div>
      </section>
      <!-- БЛОК СО СПИСКОМ НАПРАВЛЕНИЙ -->
      <section class="directions">
        <div class="directions__container">
          <h2 class="directions__title">Направления</h2>
          <p class="directions__slogan">
            Мы не продаем туры и ничего не рекламируем. Люди сами пишут о
            странах, куда хотели бы отправиться и чем можно там заняться.
          </p>
          <ul class="directions__country-list">
            <li class="directions__country-item">
              <div class="directions__country-picture">
                <picture>
                  <source media="(min-width: 1440px)" srcset="
                      img/thailand-desktop@1x.jpg 1x,
                      img/thailand-desktop@2x.jpg 2x
                    " />
                  <source media="(min-width: 768px)" srcset="
                      img/thailand-desktop@1x.jpg 1x,
                      img/thailand-desktop@2x.jpg 2x
                    " />
                  <img class="directions__image" src="img/thailand-mobile.png" srcset="img/thailand-mobile@2x.jpg 2x"
                    alt="Тайланд" />
                </picture>
              </div>
              <div class="directions__country-wrap">
                <img class="directions__flag-icon" src="img/flag-thailand.svg" width="35" height="24" alt="флаг" />
                <h3 class="directions__country-title">Таиланд</h3>
                <p class="directions__quote">Джунгли зовут!</p>
                <p class="directions__rating">18321</p>
              </div>
            </li>
            <li class="directions__country-item">
              <div class="directions__country-picture directions__country-picture-france">
                <picture>
                  <source media="(min-width: 1440px)" srcset="
                      img/france-desktop@1x.jpg 1x,
                      img/france-desktop@2x.jpg 2x
                    " />
                  <source media="(min-width: 768px)" srcset="
                      img/france-desktop@1x.jpg 1x,
                      img/france-desktop@2x.jpg 2x
                    " />
                  <img class="directions__image" src="img/france-mobile.png" srcset="img/france-mobile@2x.jpg 2x"
                    alt="Франция" />
                </picture>
              </div>
              <div class="directions__country-wrap">
                <img class="directions__flag-icon" src="img/flag-france.svg" width="35" height="24" alt="флаг" />
                <h3 class="directions__country-title">Франция</h3>
                <p class="directions__quote">Трэ бьен, манифик!</p>
                <p class="directions__rating">12518</p>
              </div>
            </li>
            <li class="directions__country-item">
              <div class="directions__country-picture">
                <picture>
                  <source media="(min-width: 1440px)" srcset="
                      img/czech-desktop@1x.jpg 1x,
                      img/czech-desktop@2x.jpg 2x
                    " />
                  <source media="(min-width: 768px)" srcset="
                      img/czech-desktop@1x.jpg 1x,
                      img/czech-desktop@2x.jpg 2x
                    " />
                  <img class="directions__image" src="img/czech-mobile.png" srcset="img/czech-mobile@2x.jpg 2x"
                    alt="Чехия" />
                </picture>
              </div>
              <div class="directions__country-wrap">
                <img class="directions__flag-icon" src="img/flag-czech.svg" width="35" height="24" alt="флаг" />
                <h3 class="directions__country-title">Чехия</h3>
                <p class="directions__quote">Закоулки старой Европы</p>
                <p class="directions__rating directions__rating-last">5326</p>
              </div>
            </li>
          </ul>
          <a href="form.html" class="directions__button"><span class="directions__btn-text">Показать все</span></a>
        </div>
      </section>
      <!-- БЛОК СО СПИСКОМ ПОПУТЧИКОВ -->
      <section class="travelers">
        <div class="travelers__container">
          <h2 class="travelers__title">Попутчики</h2>
          <blockquote class="travelers__quote">
            Все мы индивидуальны и у каждого свой взгляд на идеальный отдых.
            Одному нужен пляж и коктейль, а другому маршрут для хайкинга.
          </blockquote>
          <b class="travelers__slogan">Теперь можно легко найти единомышленников!</b>
          <section class="travelers__item travelers__item-left">
            <span class="travelers__level-firsova"> </span>
            <div class="travelers__avatar">
              <picture>
                <source media="(min-width: 1440px)" srcset="
                    img/firsova-desktop@1x.jpg 1x,
                    img/firsova-desktop@2x.jpg 2x
                  " />
                <source media="(min-width: 768px)" srcset="
                    img/firsova-desktop@1x.jpg 1x,
                    img/firsova-desktop@2x.jpg 2x
                  " />
                <img class="travelers__pictire" src="img/firsova-desktop@1x.jpg" srcset="img/firsova-desktop@2x.jpg 2x"
                  width="270" height="270" alt="аватарка" />
              </picture>
            </div>
            <div class="travelers__preferences">
              <img src="img/flag-sri-lanka.png" width="35" height="25" alt="флаг" />
              <img src="img/flag-thailand.png" width="35" height="25" alt="флаг" />
              <img src="img/flag-seychelles.png" width="35" height="25" alt="флаг" />
            </div>
            <h3 class="travelers__name">Таня Фирсова</h3>
            <span class="travelers__hobbies">#ЗОЖ #ПП #Фитнес #пляж #авокадо #смузи</span>
            <div class="travelers__transport">
              <img class="travelers__plane-icon" src="img/transport-plane.svg" width="18" height="18" alt="транспорт" />
              <img class="travelers__bus-icon" src="img/transport-bus.svg" width="18" height="18" alt="транспорт" />
              <img class="travelers__bike-icon" src="img/transport-bike.svg" width="18" height="18" alt="транспорт" />
              <img class="travelers__run-icon" src="img/transport-run.svg" width="18" height="18" alt="транспорт" />
            </div>
          </section>
          <section class="travelers__item travelers__item-right">
            <span class="travelers__level-demin"> </span>
            <div class="travelers__avatar">
              <picture>
                <source media="(min-width: 1440px)" srcset="
                    img/demin-desktop@1x.jpg 1x,
                    img/demin-desktop@2x.jpg 2x
                  " />
                <source media="(min-width: 768px)" srcset="
                    img/demin-desktop@1x.jpg 1x,
                    img/demin-desktop@2x.jpg 2x
                  " />
                <img class="travelers__pictire" src="img/demin-desktop@1x.jpg" srcset="img/demin-desktop@2x.jpg 2x"
                  width="270" height="270" alt="аватарка" />
              </picture>
            </div>
            <div class="travelers__preferences">
              <img src="img/flag-belgium.png" width="35" height="25" alt="флаг" />
              <img src="img/flag-czech.png" width="35" height="25" alt="флаг" />
            </div>
            <h3 class="travelers__name">Петя Демин</h3>
            <span class="travelers__hobbies">#бургер #бар #футбол #концерт #крафт</span>
            <div class="travelers__transport">
              <img class="travelers__plane-icon" src="img/transport-plane.svg" width="18" height="18" alt="транспорт" />
              <img class="travelers__bus-icon" src="img/transport-bus.svg" width="18" height="18" alt="транспорт" />
              <img class="travelers__bike-icon" src="img/transport-bike.svg" width="18" height="18" alt="транспорт" />
              <img class="travelers__run-icon" src="img/transport-run.svg" width="18" height="18" alt="транспорт" />
            </div>
          </section>
          <a href="catalog.html" class="travelers__button"><span class="travelers__btn-text">Показать всех</span></a>
        </div>
      </section>
      <!-- БЛОК ДОБАВЛЕНИЯ СВОЕГО ПРОФИЛЯ -->
      <section class="profile">
        <div class="profile__container">
          <h2 class="profile__title">Добавьте свой профиль</h2>
          <img class="profile__rates" src="img/rates.svg" width="100" height="100" alt="rates" />
          <ul class="profile__list">
            <li class="profile__item">
              <span class="profile__list-text">Базовое размещение</span>
              <span class="profile__list-price">Бесплатно</span>
              <span class="profile__list-number">1</span>
            </li>
            <li class="profile__item">
              <span class="profile__list-text">Вывод на первых позициях</span>
              <span class="profile__list-price">99 руб./мес</span>
              <span class="profile__list-number">2</span>
            </li>
            <li class="profile__item">
              <span class="profile__list-text">Кастомный цвет карточки</span>
              <span class="profile__list-price">59 руб./мес</span>
              <span class="profile__list-number">3</span>
            </li>
          </ul>
          <a href="#" class="profile__button">Показать тарифы для бизнеса</a>
          <div class="profile__shadow-plate"></div>
          <!-- МОДАЛЬНОЕ ОКНО С ТАРИФАМИ ДЛЯ БИЗНЕСА -->
          <div class="profile__modal hidden">
            <h2 class="profile__modal-title">Бизнес-тарифы</h2>
            <div class="profile__cost-wrap">
              <p class="profile__modal-item">Реклама у блоггера</p>
              <p class="profile__modal-item-cost">300 000 руб./пост</p>
            </div>
            <div class="profile__cost-wrap">
              <p class="profile__modal-item">Накрутка подписчиков</p>
              <p class="profile__modal-item-cost">от 1 руб./шт.</p>
            </div>
            <div class="profile__cost-wrap">
              <p class="profile__modal-item">Лайки от ботов</p>
              <p class="profile__modal-item-cost">от 20 коп./лайк</p>
            </div>
            <div class="profile__cost-wrap">
              <p class="profile__modal-item">Ваш продакт-плейсмент</p>
              <p class="profile__modal-item-cost">Индивидуально</p>
            </div>
            <button class="profile__modal-close" type="button">
              Закрыть окно
            </button>
          </div>
        </div>
      </section>
      <!-- ФОРМА РЕГИСТРАЦИИ -->
      <section class="reg">
        <div class="reg__container">
          <h2 class="reg__title">Заинтересовались?</h2>
          <span class="reg__quote">Зарегистрируйтесь, это быстро и бесплатно! <br />
            Уже зарегистрированы? Тогда скорее
            <a class="reg__quote-link" href="#">авторизуйтесь</a>.</span>
          <div class="reg__button-wrapper">
            <input class="reg__input" type="text" id="reg__input" name="reg__input" placeholder="E-mail" />
            <button class="reg__button" type="button">
              <span class="reg__btn-text">Регистрация</span>
            </button>
          </div>
          <span class="reg__more">Остались вопросы? Мы с радостью на них ответим!</span>
          <div class="reg__contact-container">
            <div class="reg__contact-wrapper">
              <a class="reg__tel-link" href="tel:+88005558628">
                <span class="text-hidden">8 800 555-86-28</span>
                <svg class="reg__icon-tel" width="19" height="17" viewBox="0 0 19 17" fill="none"
                  xmlns="http://www.w3.org/2000/svg">
                  <path fill-rule="evenodd" clip-rule="evenodd"
                    d="M9.49995 1.08615C6.7035 1.08615 3.90033 1.55882 2.88322 2.50093C2.03934 3.28252 1.75804 4.66329 1.66321 5.53753C1.66321 5.53753 1.65015 5.62393 1.65015 5.66109C1.65015 6.00391 1.94445 6.27887 2.30427 6.27887C2.34678 6.27887 3.92002 6.15837 4.86851 6.08425C4.89134 6.08112 4.91434 6.07806 4.93716 6.07191C5.29043 6.0627 5.57505 5.7908 5.57505 5.45413L5.57822 4.237C5.57822 3.86014 5.90214 3.55737 6.3012 3.55737H12.6987C13.0978 3.55737 13.4218 3.86011 13.4218 4.237L13.425 5.45413C13.425 5.7908 13.7095 6.0627 14.0628 6.07191C14.0854 6.0781 14.1085 6.08112 14.1315 6.08425C15.0801 6.15834 16.6533 6.27887 16.6957 6.27887C17.0553 6.27887 17.3499 6.00391 17.3499 5.66109C17.3499 5.62393 17.3368 5.53753 17.3368 5.53753C17.2419 4.66329 16.9609 3.28255 16.117 2.50093C15.0996 1.55882 12.2964 1.08615 9.49995 1.08615ZM9.49995 9.11773C8.7771 9.11773 8.19164 9.67064 8.19164 10.3533C8.19164 11.036 8.7771 11.5889 9.49995 11.5889C10.2228 11.5889 10.8082 11.036 10.8082 10.3533C10.8082 9.67064 10.2228 9.11773 9.49995 9.11773ZM8.51873 6.33752V5.56528C8.51873 5.13902 8.15236 4.79304 7.70106 4.79304C7.24977 4.79304 6.8834 5.13905 6.8834 5.56528V6.33752L2.47095 10.7889C2.16689 11.07 1.97713 11.4622 1.97713 11.8948V13.1335C1.97713 13.8162 2.56264 14.3691 3.28545 14.3691H3.61254V15.1414C3.61254 15.5677 3.97895 15.9136 4.43025 15.9136C4.88154 15.9136 5.24792 15.5677 5.24792 15.1414V14.3691H13.752V15.1414C13.752 15.5677 14.1182 15.9136 14.5697 15.9136C15.021 15.9136 15.3873 15.5677 15.3873 15.1414V14.3691H15.7144C16.4373 14.3691 17.0227 13.8162 17.0227 13.1335V11.8948C17.0227 11.4622 16.833 11.07 16.5289 10.7889L12.1166 6.33752V5.56528C12.1166 5.13902 11.7502 4.79304 11.2989 4.79304C10.8476 4.79304 10.4812 5.13905 10.4812 5.56528V6.33752H8.51873ZM9.49995 7.8821C10.9456 7.8821 12.1166 8.98799 12.1166 10.3533C12.1166 11.7187 10.9457 12.8247 9.49995 12.8247C8.05426 12.8247 6.88336 11.7187 6.88336 10.3533C6.88336 8.98795 8.05426 7.8821 9.49995 7.8821Z"
                    fill="#FFD74B" />
                </svg>
              </a>
              <span class="reg__contact-text">8 800 555-86-28</span>
            </div>
            <div class="reg__contact-wrapper">
              <a class="reg__mail-link" href="mailto:mail@htmlacademy.ru">
                <span class="text-hidden">mail@htmlacademy.ru</span>
                <svg class="reg__icon-mail" width="19" height="13" viewBox="0 0 19 13" fill="none"
                  xmlns="http://www.w3.org/2000/svg">
                  <path fill-rule="evenodd" clip-rule="evenodd"
                    d="M16.1393 10.4663L11.8089 6.5L16.1393 2.53365L15.5488 1.90264L9.24997 7.67188L2.95117 1.90264L2.36066 2.53365L6.69108 6.5L2.36066 10.4663L2.95117 11.0974L7.33081 7.08594L9.24997 8.84375L11.1691 7.08594L15.5488 11.0974L16.1393 10.4663ZM1.57593 0.25C0.76692 0.25 0.111084 0.948839 0.111084 1.80786V11.1921C0.111084 12.0525 0.7616 12.75 1.57593 12.75H16.924C17.733 12.75 18.3889 12.0512 18.3889 11.1921V1.80786C18.3889 0.947478 17.7383 0.25 16.924 0.25H1.57593Z"
                    fill="#FFD74B" />
                </svg>
              </a>
              <span class="reg__contact-text">mail@htmlacademy.ru</span>
            </div>
          </div>
        </div>
      </section>
      <!-- БЛОК МАРШРУТ И КАРТА -->
      <section class="map">
        <div class="map__container">
          <div class="map__address">
            <div class="map__icon"></div>
            <span class="map__text">ул. Большая Конюшенная, 19/8</span>
          </div>
          <button type="button" class="map__button">
            <span class="map__btn-text">Проложить маршрут</span>
          </button>
        </div>
      </section>
      <section class="location">
        <iframe class="location__map"
          src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d1998.603625300316!2d30.320858716173465!3d59.93871916905408!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x4696310fca145cc1%3A0x42b32648d8238007!2sBolshaya%20Konyushennaya%20St%2C%2019%2F8%2C%20Sankt-Peterburg%2C%20Russia%2C%20191186!5e0!3m2!1sen!2sca!4v1599280905211!5m2!1sen!2sca"
          width="600" height="450" style="border: 0" allowfullscreen="" aria-hidden="false" tabindex="0">
        </iframe>
      </section>
    </main>
    <!-- ФУТЕР -->
    <footer class="page-footer">
      <div class="page-footer__container">
        <a class="page-footer__contacts" href="index.html">
          <span class="text-hidden">Главная</span>
          <div class="page-footer__logo">
            <picture>
              <source media="(min-width: 1440px)" srcset="img/logo-desktop-blue@2x.png" />
              <source media="(min-width: 768px)" srcset="img/logo-desktop-blue@2x.png" />
              <img src="img/logo-mobile-blue@2x.png" alt="главная" />
            </picture>
          </div>
        </a>
        <div class="page-footer__social">
          <a class="page-footer__link" href="https://www.facebook.com/htmlacademy">
            <svg class="page-footer__icon-fb" width="11" height="21" viewBox="0 0 11 21" fill="none"
              xmlns="http://www.w3.org/2000/svg">
              <path
                d="M7.48786 20.7695H2.12929V11.2513H0V6.54393H2.06643C1.90929 4.41158 2.30214 2.85474 3.26071 1.79225C3.71777 1.32067 4.27461 0.94388 4.89562 0.685966C5.51662 0.428052 6.18812 0.294698 6.86714 0.294434L10.6229 0.294434V4.83215H7.66857C7.49452 5.3871 7.42799 5.9669 7.47214 6.54393H10.615V11.2513H7.47214L7.48786 20.7695ZM3.31571 19.6627H6.28571V10.1446H9.42857V7.67283H6.28571V7.11207C6.28571 5.63639 6.28571 4.31566 7.07143 3.82131L7.22071 3.72539H9.42857V1.40119H6.89857C6.38444 1.39495 5.87465 1.49025 5.40225 1.68092C4.92986 1.87158 4.50541 2.15335 4.15643 2.50795C3.37071 3.41549 3.04857 4.93544 3.29214 7.03829L3.37071 7.65069H1.17857V10.1446H3.31571V19.6627Z"
                fill="#192144" />
            </svg>
            <span class="text-hidden">Мы в Фейсбуке</span></a>
          <a class="page-footer__link" href="https://vk.com/htmlacademy">
            <svg class="page-footer__icon-vk" width="23" height="12" viewBox="0 0 23 12" fill="none"
              xmlns="http://www.w3.org/2000/svg">
              <path
                d="M17.7664 11.8542C17.219 11.8419 16.6854 11.6812 16.2232 11.3893C15.7407 11.065 15.2975 10.6862 14.9026 10.2604C14.5761 9.93579 14.0345 9.38979 13.8268 9.38979C13.619 9.38979 13.4706 10.0686 13.478 10.5482C13.4812 10.8792 13.3564 11.1989 13.1293 11.441C12.8712 11.6507 12.5561 11.7791 12.2242 11.8099H10.7997C8.75222 11.7651 6.79178 10.9779 5.28708 9.59639C2.55676 7.10987 0.21224 2.35818 0.115789 2.15159C0.0237889 1.97899 -0.0147389 1.78317 0.00506792 1.58882C0.0248747 1.39447 0.102128 1.21031 0.227079 1.05958C0.509857 0.825057 0.867951 0.699369 1.23611 0.705422H4.26321H4.35224C4.6027 0.741762 4.84277 0.829721 5.05708 0.963666C5.25875 1.09815 5.42022 1.28422 5.5245 1.50229C5.8444 2.18336 6.2113 2.84161 6.62256 3.47232C7.5945 4.948 8.02482 5.2874 8.18063 5.36119C8.35396 4.66929 8.40169 3.95217 8.3216 3.24359C8.3476 2.92086 8.29412 2.5967 8.16579 2.29915C8.00289 2.16957 7.80288 2.09466 7.5945 2.08518L7.05289 1.57607C6.94901 1.0891 7.49063 0.66853 7.86902 0.506205C8.62414 0.270907 9.41638 0.175863 10.2061 0.225826H10.7329C11.2686 0.211953 11.8041 0.26149 12.328 0.373394C13.5893 0.639016 13.5448 1.64986 13.4929 2.81564C13.4929 3.15505 13.4558 3.55348 13.4558 4.01094C13.4558 4.12162 13.4558 4.23967 13.4558 4.36511C13.4266 4.68633 13.4492 5.01013 13.5226 5.3243C14.1402 4.81043 14.6604 4.1907 15.0584 3.49445C15.4879 2.83611 15.865 2.14535 16.1861 1.4285C16.2839 1.20178 16.4516 1.01177 16.6649 0.885809C16.8782 0.75985 17.1262 0.704442 17.3732 0.727557H20.5487C20.6425 0.718658 20.7369 0.718658 20.8306 0.727557C21.5726 0.727557 22.0103 0.941531 22.1884 1.35472C22.3664 1.76791 22.3145 2.57953 20.4374 4.75616L19.6955 5.58992C19.336 5.93702 19.0264 6.3318 18.7755 6.76308C19.0565 7.08078 19.3754 7.36324 19.7251 7.60422C20.5778 8.24318 21.3283 9.0069 21.951 9.86939C22.097 10.0371 22.1925 10.2423 22.2266 10.4616C22.2608 10.6808 22.2321 10.9052 22.1439 11.109C21.9884 11.3346 21.7803 11.5196 21.5375 11.6481C21.2946 11.7765 21.0241 11.8447 20.749 11.8468L17.9371 11.8837L17.7664 11.8542ZM13.8268 8.28303C14.4945 8.28303 15.0732 8.86593 15.689 9.47833C16.0217 9.83957 16.3951 10.1614 16.8019 10.4375C17.1096 10.641 17.4711 10.7489 17.8406 10.7474H17.9148L20.7342 10.7105C20.8732 10.7026 21.0094 10.6675 21.1348 10.6072L21.0606 10.4892C20.499 9.72803 19.8292 9.052 19.0722 8.48225C18.1893 7.74441 17.7368 7.39762 17.6848 6.82949C17.6329 6.26135 18.0484 5.767 18.8793 4.82994L19.6213 4.01094C20.2477 3.37556 20.7619 2.6397 21.1422 1.83432C20.9767 1.82455 20.8107 1.82455 20.6451 1.83432H17.4029C17.3443 1.82128 17.2835 1.82128 17.2248 1.83432C16.8814 2.61749 16.4719 3.37032 16.0006 4.08473C14.5984 6.16543 13.938 6.44581 13.4706 6.44581C13.3257 6.44581 13.183 6.41034 13.0551 6.34251C12.3132 5.92195 12.3132 4.98489 12.3577 4.30608C12.3577 4.1954 12.3577 4.08473 12.3577 3.98881C12.3577 3.50921 12.3577 3.09602 12.3948 2.74186C12.4542 1.50229 12.3948 1.49491 12.1129 1.4285C11.6586 1.33924 11.1958 1.29965 10.7329 1.31045H10.221C9.74988 1.30077 9.27872 1.32543 8.81127 1.38423C8.88206 1.43611 8.94459 1.49829 8.99676 1.56869C9.30278 2.04854 9.4554 2.60935 9.4345 3.17718C9.53095 4.39462 9.47902 5.98097 8.69256 6.36465C8.5533 6.42946 8.40115 6.46224 8.2474 6.46057C7.5574 6.46057 6.87482 5.81127 5.70998 4.05521C5.26298 3.38283 4.86383 2.68017 4.51547 1.95237L4.45611 1.87859C4.38118 1.84061 4.30126 1.81329 4.21869 1.79742H1.25095H1.19901C1.63676 2.69759 3.71418 6.68192 6.03643 8.77001C7.34044 9.9614 9.02993 10.6497 10.7997 10.7105H12.1722C12.2422 10.6957 12.3097 10.6708 12.3726 10.6367C12.3726 10.6367 12.3726 10.6367 12.3726 10.5703C12.3726 10.3711 12.3726 8.65195 13.5448 8.35682C13.6356 8.32127 13.7302 8.29651 13.8268 8.28303Z"
                fill="#192144" />
            </svg>
            <span class="text-hidden">Мы в Вконтакте</span></a>
          <a class="page-footer__link" href="https://www.instagram.com/htmlacademy">
            <svg class="page-footer__icon-inst" width="18" height="18" viewBox="0 0 18 18" fill="none"
              xmlns="http://www.w3.org/2000/svg">
              <g clip-path="url(#clip0)">
                <path
                  d="M12.9601 2.03319C13.8188 2.03506 14.6418 2.37148 15.249 2.96885C15.8562 3.56621 16.1982 4.37586 16.2001 5.22066V13.0122C16.1982 13.857 15.8562 14.6667 15.249 15.2641C14.6418 15.8614 13.8188 16.1978 12.9601 16.1997H5.04009C4.18262 16.196 3.36147 15.8587 2.75581 15.2616C2.15016 14.6644 1.80919 13.8558 1.80729 13.0122V5.22066C1.80919 4.37709 2.15016 3.5685 2.75581 2.97134C3.36147 2.37418 4.18262 2.03693 5.04009 2.03319H12.9601ZM12.9601 0.970703H5.04009C3.89436 0.970703 2.79555 1.41846 1.98539 2.21549C1.17523 3.01251 0.720093 4.0935 0.720093 5.22066L0.720093 13.0122C0.720093 14.1394 1.17523 15.2204 1.98539 16.0174C2.79555 16.8144 3.89436 17.2622 5.04009 17.2622H12.9601C14.1058 17.2622 15.2046 16.8144 16.0148 16.0174C16.8249 15.2204 17.2801 14.1394 17.2801 13.0122V5.22066C17.2801 4.0935 16.8249 3.01251 16.0148 2.21549C15.2046 1.41846 14.1058 0.970703 12.9601 0.970703V0.970703Z"
                  fill="#192144" />
                <path
                  d="M9.00703 5.98486C9.63787 5.98486 10.2545 6.16889 10.7791 6.51369C11.3036 6.85848 11.7124 7.34855 11.9538 7.92193C12.1953 8.4953 12.2584 9.12622 12.1353 9.73491C12.0123 10.3436 11.7085 10.9027 11.2624 11.3416C10.8163 11.7804 10.248 12.0793 9.62929 12.2003C9.01057 12.3214 8.36924 12.2593 7.78642 12.0218C7.2036 11.7843 6.70545 11.3821 6.35497 10.8661C6.00449 10.35 5.81743 9.74336 5.81743 9.12274C5.81648 8.71041 5.89833 8.30195 6.05829 7.92082C6.21824 7.53969 6.45315 7.19341 6.74952 6.90184C7.04589 6.61027 7.39789 6.37918 7.7853 6.22181C8.17271 6.06445 8.5879 5.98392 9.00703 5.98486V5.98486ZM9.00703 4.92237C8.16228 4.92097 7.33609 5.16612 6.63301 5.62681C5.92993 6.0875 5.38156 6.74302 5.0573 7.51042C4.73304 8.27781 4.64746 9.12259 4.81139 9.93784C4.97532 10.7531 5.38139 11.5022 5.97822 12.0903C6.57504 12.6785 7.3358 13.0792 8.16422 13.2419C8.99264 13.4045 9.85148 13.3218 10.6321 13.0041C11.4127 12.6863 12.0799 12.148 12.5494 11.4571C13.0188 10.7662 13.2694 9.9538 13.2694 9.12274C13.2704 8.57148 13.1608 8.02544 12.947 7.51586C12.7333 7.00629 12.4194 6.54319 12.0236 6.15306C11.6277 5.76293 11.1575 5.45342 10.6398 5.24224C10.1222 5.03107 9.56738 4.92237 9.00703 4.92237Z"
                  fill="#192144" />
                <path
                  d="M13.4282 5.73083C13.961 5.73083 14.393 5.30588 14.393 4.78168C14.393 4.25747 13.961 3.83252 13.4282 3.83252C12.8953 3.83252 12.4634 4.25747 12.4634 4.78168C12.4634 5.30588 12.8953 5.73083 13.4282 5.73083Z"
                  fill="#192144" />
              </g>
              <defs>
                <clipPath id="clip0">
                  <rect width="18" height="17.7081" fill="white" transform="translate(0 0.261719)" />
                </clipPath>
              </defs>
            </svg>
            <span class="text-hidden">Мы в Инстаграме</span></a>
        </div>
        <div class="page-footer__copyright">
          <b class="page-footer__text">Разработано:
            <a class="page-footer__copyright-link" href="https://htmlacademy.ru/intensive/adaptive">
              <span class="text-hidden">HTML Academy</span></a>
          </b>
        </div>
      </div>
    </footer>
  </body>
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
<style scoped>
@tablet-width: 768px;
@desktop-width: 1440px;
@mobile-width-only: 320px;

.about {
  min-width: 100%;
  width: 100%;
  background-color: #192144;
}
.about__container {
  position: relative;
  z-index: 9;
  display: flex;
  flex-direction: column;
  min-width: 318px;
  width: 318px;
  min-height: 341px;
  margin-top: 0px;
  margin-left: auto;
  margin-right: auto;
  padding-top: 16px;
  background-color: #192144;
  /* background-image: url(../assets/img/about-mobile@1x.png); */
  background-image: url(../assets/img/about-mobile@1x.png);
  color: #FFFFFF;
  border-bottom-left-radius: 30px;
  border-bottom-right-radius: 30px;
  border: solid 1px transparent;
}
@media (min-resolution: 2dppx) {
  .about__container {
    background-image: url(../assets/img/about-mobile@2x.png);
    background-repeat: no-repeat;
    background-position: center;
    background-size: 292px 353px;
  }
}
@media (min-width: 768px) {
  .about__container {
    background-image: url(../assets/img/about-tablet@1x.png);
    background-repeat: no-repeat;
    background-position: 382px 139px;
    min-width: 766px;
    width: 766px;
    min-height: 759px;
    background-color: #182044;
    margin-top: 0px;
    margin-left: auto;
    margin-right: auto;
    border-bottom-left-radius: 60px;
    border-bottom-right-radius: 60px;
  }
}
@media (min-width: 768px) and (min-resolution: 2dppx) {
  .about__container {
    background-image: url(../assets/img/about-tablet@2x.png);
    background-repeat: no-repeat;
    background-position: 382px 139px;
    background-size: 376px 548px;
  }
}
@media (min-width: 1440px) {
  .about__container {
    margin-top: -3px;
    margin-left: auto;
    margin-right: auto;
    background-image: url(../assets/img/about-desktop@1x.png);
    background-repeat: no-repeat;
    background-position: 750px 82px;
    min-width: 1438px;
    width: 1438px;
    min-height: 731px;
    background-color: #182044;
    border-bottom-left-radius: 60px;
    border-bottom-right-radius: 60px;
    position: relative;
    z-index: 9;
  }
}
@media (min-width: 1440px) and (min-resolution: 2dppx) {
  .about__container {
    background-image: url(../assets/img/about-desktop@2x.png);
    background-repeat: no-repeat;
    background-position: 750px 82px;
    background-size: 630px 665px;
  }
}
.about__title {
  color: #FF8D30;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: 700;
  font-size: 24px;
  line-height: 24px;
  padding-left: 48px;
}
@media (min-width: 768px) {
  .about__title {
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: bold;
    font-size: 45px;
    line-height: 45px;
    color: #FF8D30;
    margin-top: 113px;
    margin-bottom: 0px;
    margin-left: 23px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .about__title {
    font-style: normal;
    font-weight: bold;
    font-size: 45px;
    line-height: 45px;
    margin: 110px 0px 0px 82px;
  }
}
.about__quote {
  display: inline-block;
  width: 211px;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: 300;
  font-size: 16px;
  line-height: 22px;
  margin-left: 2px;
  margin-top: 0px;
  padding-left: 46px;
}
@media (min-width: 768px) {
  .about__quote {
    display: inline-block;
    width: 300px;
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: 300;
    font-size: 28px;
    line-height: 33px;
    color: #FFFFFF;
    margin-top: 42px;
    margin-bottom: 0px;
    margin-left: 26px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .about__quote {
    display: inline-block;
    width: 619px;
    height: 102px;
    font-style: normal;
    font-weight: 300;
    font-size: 28px;
    line-height: 34px;
    margin: 59px 0px 0px 84px;
  }
}
.about__slogan {
  display: inline-block;
  width: 202px;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: 700;
  font-size: 16px;
  line-height: 22px;
  margin: 0px;
  padding-top: 3px;
  padding-left: 48px;
}
@media (min-width: 768px) {
  .about__slogan {
    display: inline-block;
    width: 260px;
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: bold;
    font-size: 21px;
    line-height: 25px;
    color: #FFFFFF;
    margin-top: 28px;
    margin-bottom: 0px;
    margin-left: 23px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .about__slogan {
    width: 425px;
    height: 48px;
    font-style: normal;
    font-weight: bold;
    font-size: 21px;
    line-height: 24px;
    padding: 0px 0px 0px 0px;
    margin: 38px 0px 0px 131px;
  }
}
.about__btn {
  display: none;
}
@media (min-width: 768px) {
  .about__btn {
    display: block;
    width: 276px;
    height: 80px;
    background-color: #FFD74B;
    background-image: url(../assets/img/icon-btn-triangle.svg);
    background-repeat: no-repeat;
    background-position: 87%, 50%;
    border-radius: 20px;
    padding: 0px 0px 0px 0px;
    margin: 54px 0px 0px 71px;
  }
}
@media (min-width: 1440px) {
  .about__btn {
    display: block;
    width: 274px;
    height: 80px;
    background-color: #FFD74B;
    background-image: url(../assets/img/icon-btn-triangle.svg);
    background-repeat: no-repeat;
    background-position: 87%, 50%;
    border-radius: 20px;
    padding: 0px 0px 0px 0px;
    margin: 87px 0px 0px 131px;
  }
}
.about__btn-text {
  display: none;
}
@media (min-width: 768px) {
  .about__btn-text {
    display: inline-block;
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: bold;
    font-size: 24px;
    line-height: 78px;
    color: #1D2E5B;
    padding: 0px 0px 0px 0px;
    margin: 0px 0px 0px 33px;
  }
}
@media (min-width: 1440px) {
  .about__btn-text {
    display: inline-block;
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: bold;
    font-size: 24px;
    line-height: 78px;
    color: #1D2E5B;
    padding: 0px 0px 0px 0px;
    margin: 0px 0px 0px 33px;
  }
}
.about__btn:hover {
  background-color: #FFBD30;
}
.about__btn:active,
.about__btn-text:active {
  color: rgba(119, 110, 110, 0.3);
}
.add-plan {
  min-width: 100%;
  width: 100%;
  background-color: #D4D9EB;
}
.add-plan__container {
  display: flex;
  flex-direction: column;
  min-width: 318px;
  width: 318px;
  background-color: #D4D9EB;
  border: solid 1px transparent;
  border-radius: 20px;
  border-top-left-radius: 30px;
  border-top-right-radius: 30px;
  margin-top: -29px;
  margin-left: auto;
  margin-right: auto;
  padding-bottom: 160px;
  position: relative;
  z-index: 11;
}
@media (min-width: 768px) {
  .add-plan__container {
    min-width: 766px;
    width: 766px;
    border-top-left-radius: 30px;
    border-top-right-radius: 30px;
    margin-top: -26px;
    margin-left: auto;
    margin-right: auto;
    padding: 0px 0px 60px 0px;
    position: relative;
    z-index: 11;
  }
}
@media (min-width: 1440px) {
  .add-plan__container {
    min-width: 1438px;
    width: 1438px;
    border-top-left-radius: 50px;
    border-top-right-radius: 50px;
    margin: -26px auto 60px auto;
    padding: 0px 0px 112px 0px;
  }
}
.add-plan__header {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.add-plan__title {
  font-style: normal;
  font-weight: bold;
  font-size: 24px;
  line-height: 24px;
  color: #1D2E5B;
  margin-top: 25px;
  margin-bottom: 0px;
  margin-left: 24px;
  margin-right: 0px;
}
@media (min-width: 768px) {
  .add-plan__title {
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: bold;
    font-size: 36px;
    line-height: 36px;
    margin-top: 47px;
    margin-bottom: 59px;
    margin-left: 73px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .add-plan__title {
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: bold;
    font-size: 36px;
    line-height: 36px;
    margin-top: 51px;
    margin-bottom: 57px;
    margin-left: 128px;
    margin-right: 0px;
  }
}
.add-plan__toggles {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  width: 53px;
  height: 6px;
  margin: 27px 40px 0px 0px;
}
@media (min-width: 768px) {
  .add-plan__toggles {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    width: 81px;
    height: 6px;
    margin-top: -11px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 70px;
  }
}
@media (min-width: 1440px) {
  .add-plan__toggles {
    display: none;
  }
}
.add-plan__toggle-button {
  display: inline-block;
  width: 5px;
  height: 5px;
  background-color: transparent;
  border: none;
  background-image: url("../assets/img/slider-icon-grey.svg");
  background-repeat: no-repeat;
  background-position: center;
}
.add-plan__toggle-button--current {
  background-image: url("../assets/img/slider-icon-blue.svg");
  background-repeat: no-repeat;
  background-position: center;
}
.add-plan__item-one {
  display: grid;
  grid-template-columns: 1fr;
  grid-template-rows: 0.5fr 1fr 0.9fr 0.9fr 0.3fr 1fr 1fr 1fr 0.4fr;
  width: 270px;
  min-height: 773px;
  background-color: #FFFFFF;
  border-radius: 10px;
  margin: 0 auto;
  margin-top: 31px;
  align-items: center;
  padding-top: 24px;
  padding-bottom: 0px;
}
@media (min-width: 768px) {
  .add-plan__item-one {
    display: grid;
    grid-template-columns: 1fr;
    grid-template-rows: 0.5fr 0.5fr 0.9fr 0.9fr 0.3fr 1fr 1fr 0.5fr 0.5fr;
    min-width: 618px;
    min-height: 1437px;
    border-radius: 30px;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: auto;
    margin-right: auto;
    padding-top: 0px;
    padding-bottom: 0px;
  }
}
@media (min-width: 1440px) {
  .add-plan__item-one {
    display: grid;
    grid-template-columns: 1fr 1fr;
    grid-template-rows: 0.5fr 0.5fr 0.5fr 0.5fr 4fr 0.5fr;
    min-width: 1320px;
    min-height: 1205px;
    border-radius: 60px;
    margin: 0px auto 0px auto;
    padding: 98px 0px 0px 0px;
  }
}
.add-plan__step {
  grid-column-start: 1;
  grid-row-start: 1;
  grid-row-end: 2;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 20px;
  line-height: 20px;
  color: #1D2E5B;
  margin: -2px 0px 0px 0px;
  padding-left: 25px;
  padding-right: 20px;
  align-self: flex-start;
}
@media (min-width: 768px) {
  .add-plan__step {
    grid-column-start: 1;
    grid-row-start: 1;
    grid-row-end: 2;
    display: inline-block;
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: bold;
    font-size: 36px;
    line-height: 36px;
    width: 293px;
    height: 72px;
    margin-top: 45px;
    margin-bottom: 0px;
    margin-left: 17px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .add-plan__step {
    grid-column-start: 1;
    grid-column-end: 3;
    grid-row-start: 1;
    grid-row-end: 2;
    display: inline-block;
    width: 430px;
    height: 72px;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: 160px;
    margin-right: 0px;
    padding: 0px 0px 0px 0px;
  }
}
.add-plan__step-text {
  grid-column-start: 1;
  grid-row-start: 2;
  grid-row-end: 3;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 22px;
  color: #444444;
  margin-top: 0px;
  margin-bottom: 0px;
  padding-left: 23px;
  padding-right: 25px;
}
@media (min-width: 768px) {
  .add-plan__step-text {
    grid-column-start: 1;
    grid-row-start: 2;
    grid-row-end: 3;
    display: inline-block;
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: normal;
    font-size: 20px;
    line-height: 24px;
    width: 505px;
    height: 72px;
    margin-top: 36px;
    margin-bottom: 0px;
    margin-left: 21px;
    margin-right: 0px;
    padding-bottom: 37px;
    border-bottom: 1px solid #E1E3E9;
  }
}
@media (min-width: 1440px) {
  .add-plan__step-text {
    grid-column-start: 1;
    grid-column-end: 3;
    grid-row-start: 1;
    grid-row-end: 3;
    display: inline-block;
    width: 550px;
    height: 72px;
    margin-top: 28px;
    margin-bottom: 0px;
    margin-left: 161px;
    margin-right: 0px;
    padding: 0px 0px 0px 0px;
    border: none;
  }
}
.add-plan__desktop-slider {
  display: none;
}
@media (min-width: 768px) {
  .add-plan__desktop-slider {
    display: none;
  }
}
@media (min-width: 1440px) {
  .add-plan__desktop-slider {
    grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 1;
    grid-row-end: 3;
    display: grid;
    width: 220px;
    height: 137px;
    padding: 0px 0px 0px 0px;
    margin: -52px 0px 0px 251px;
    background-image: url(../assets/img/slider-one.svg);
    background-repeat: no-repeat;
    background-position: center;
    border: solid 1px transparent;
  }
}
.add-plan__desktop-slider-two {
  display: none;
}
@media (min-width: 768px) {
  .add-plan__desktop-slider-two {
    display: none;
  }
}
@media (min-width: 1440px) {
  .add-plan__desktop-slider-two {
    grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 1;
    grid-row-end: 3;
    display: grid;
    width: 220px;
    height: 137px;
    padding: 0px 0px 0px 0px;
    margin: 93px 186px 0px 0px;
    background-image: url(../assets/img/slider-two.svg);
    background-repeat: no-repeat;
    background-position: center;
    border: solid 1px transparent;
  }
}
.add-plan__desktop-slider-three {
  display: none;
}
@media (min-width: 768px) {
  .add-plan__desktop-slider-three {
    display: none;
  }
}
@media (min-width: 1440px) {
  .add-plan__desktop-slider-three {
    grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 1;
    grid-row-end: 3;
    display: grid;
    width: 220px;
    height: 137px;
    padding: 0px 0px 0px 0px;
    margin: 94px 186px 0px 0px;
    background-image: url(../assets/img/slider-three.svg);
    background-repeat: no-repeat;
    background-position: center;
    border: solid 1px transparent;
  }
}
.add-plan__form-field-person {
  grid-column-start: 1;
  grid-row-start: 3;
  margin-top: 0px;
  margin-bottom: 0px;
  margin: 0 auto;
}
@media (min-width: 768px) {
  .add-plan__form-field-person {
    grid-column-start: 1;
    grid-row-start: 3;
    grid-row-end: 4;
    min-width: 531px;
    min-height: 72px;
    margin-top: -39px;
    margin-bottom: 0px;
    margin-left: auto;
    margin-right: auto;
    padding-bottom: 0px;
  }
}
@media (min-width: 1440px) {
  .add-plan__form-field-person {
    grid-column-start: 1;
    grid-column-end: 3;
    grid-row-start: 3;
    grid-row-end: 4;
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    align-items: center;
    min-width: 516px;
    width: 516px;
    min-height: 72px;
    margin-top: 16px;
    margin-bottom: 0px;
    margin-left: 153px;
    margin-right: 0px;
    padding-bottom: 0px;
    border: solid 1px transparent;
  }
}
.add-plan__form-field-dates {
  grid-column-start: 1;
  grid-row-start: 4;
  margin-top: -26px;
  margin-bottom: 0px;
  margin-left: auto;
  margin-right: auto;
}
@media (min-width: 768px) {
  .add-plan__form-field-dates {
    grid-column-start: 1;
    grid-row-start: 4;
    grid-row-end: 5;
    min-width: 531px;
    min-height: 72px;
    margin-top: -7px;
    margin-bottom: 0px;
    margin-left: auto;
    margin-right: auto;
    padding-bottom: 0px;
  }
}
@media (min-width: 1440px) {
  .add-plan__form-field-dates {
    grid-column-start: 1;
    grid-column-end: 3;
    grid-row-start: 4;
    grid-row-end: 5;
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    align-items: center;
    width: 475px;
    min-height: 72px;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: 145px;
    margin-right: 0px;
    padding-bottom: 0px;
    box-sizing: border-box;
    border: solid 1px transparent;
  }
}
.add-plan__checkbox {
  grid-column-start: 1;
  grid-row-start: 5;
  grid-row-end: 6;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  margin-top: -11px;
  margin-bottom: 0px;
  margin-left: 24px;
  width: 140px;
  height: 30px;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: normal;
  font-size: 15px;
  line-height: 15px;
  color: #1D2E5B;
  cursor: pointer;
}
@media (min-width: 768px) {
  .add-plan__checkbox {
    grid-column-start: 1;
    grid-row-start: 2;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    width: 240px;
    height: 30px;
    margin-top: 26px;
    margin-bottom: 0px;
    margin-left: 47px;
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-size: 20px;
    line-height: 20px;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    color: #1D2E5B;
  }
}
@media (min-width: 1440px) {
  .add-plan__checkbox {
    grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 3;
    grid-row-end: 4;
    margin-top: 18px;
    margin-bottom: 0px;
    margin-left: 262px;
    margin-right: 0px;
    padding-bottom: 0px;
  }
}
.add-plan__kids {
  display: none;
}
.add-plan__checkbox-on {
  width: 26px;
  height: 26px;
  box-sizing: border-box;
  border: 1px solid #CBCED9;
  border-radius: 4px;
  background-image: url(../assets/img/checkbox-on.png);
  background-repeat: no-repeat;
  background-position: center;
}
@media (min-width: 768px) {
  .add-plan__checkbox-on {
    width: 36px;
    height: 36px;
    background-size: 25px;
    margin: 2px 0px 0px -3px;
  }
}
.add-plan__calendar {
  grid-column-start: 1;
  grid-row-start: 6;
  grid-row-end: 9;
  margin: 0 auto;
  margin-top: -28px;
  margin-bottom: 0px;
}
@media (min-width: 768px) {
  .add-plan__calendar {
    grid-column-start: 1;
    grid-row-start: 5;
    grid-row-end: 9;
    margin: -33px auto 0px auto;
  }
}
@media (min-width: 1440px) {
  .add-plan__calendar {
    grid-column-start: 1;
    grid-column-end: 3;
    grid-row-start: 5;
    grid-row-end: 7;
    height: auto;
    min-height: auto;
    margin-top: -222px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
    padding-bottom: 0px;
  }
}
.add-plan__button-next {
  grid-column-start: 1;
  grid-row-start: 9;
  grid-row-end: 10;
  width: 229px;
  height: 40px;
  background-color: #FFD74B;
  border-radius: 20px;
  border: none;
  margin-top: -43px;
  margin-bottom: 0px;
  margin-left: 21px;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 17px;
  line-height: 30px;
  text-transform: uppercase;
  color: #1D2E5B;
}
@media (min-width: 768px) {
  .add-plan__button-next {
    grid-column-start: 1;
    grid-row-start: 9;
    width: 284px;
    height: 80px;
    font-style: normal;
    font-weight: bold;
    font-size: 24px;
    line-height: 24px;
    text-transform: none;
    color: #1D2E5B;
    background-image: url("../assets/img/icon-btn-triangle.svg");
    background-repeat: no-repeat;
    background-position: 87%, 50%;
    margin-top: -77px;
    margin-left: 44px;
    padding: 0px 43px 2px 0px;
    box-sizing: border-box;
  }
}
@media (min-width: 1440px) {
  .add-plan__button-next {
    grid-column-start: 1;
    grid-column-end: 2;
    grid-row-start: 5;
    grid-row-end: 7;
    margin-top: 540px;
    margin-bottom: 0px;
    margin-left: 161px;
    margin-right: 0px;
    padding-bottom: 0px;
  }
}
.add-plan__button-next:hover {
  background-color: #FFBD30;
}
.add-plan__button-next:active {
  background-color: #FFBD30;
}
.add-plan__counter-person {
  display: flex;
  justify-content: center;
  border: solid 1px #1D2E5B;
  border-radius: 5px;
  width: 220px;
  min-height: 43px;
  margin-top: 0px;
  box-sizing: border-box;
}
@media (min-width: 768px) {
  .add-plan__counter-person {
    display: flex;
    justify-content: space-between;
    width: auto;
    min-height: 70px;
    margin-top: 24px;
    box-sizing: border-box;
    padding: 0px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .add-plan__counter-person {
    margin: 0px 0px 0px 24px;
    padding: 0px 0px 0px 0px;
    box-sizing: border-box;
  }
}
.add-plan__counter-date {
  display: flex;
  justify-content: center;
  border: solid 1px #1D2E5B;
  border-radius: 5px;
  width: 220px;
  min-height: 43px;
  margin-top: 0px;
  box-sizing: border-box;
}
@media (min-width: 768px) {
  .add-plan__counter-date {
    display: flex;
    justify-content: space-between;
    width: auto;
    min-height: 70px;
    margin: 23px 0px 0px 0px;
    box-sizing: border-box;
    padding: 0px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .add-plan__counter-date {
    margin: 0px -48px 0px 0px;
    padding: 0px 0px 0px 0px;
  }
}
.add-plan__minus {
  background-color: transparent;
  background-image: url("../assets/img/minus-icon-btn.svg");
  background-repeat: no-repeat;
  background-position: center;
  border: none;
}
@media (min-width: 768px) {
  .add-plan__minus {
    width: 25px;
    height: 25px;
    background-size: 20px, 20px;
    margin: 21px 0px 0px 21px;
  }
}
.add-plan__plus {
  background-color: transparent;
  background-image: url("../assets/img/plus-icon-btn.svg");
  background-repeat: no-repeat;
  background-position: center;
  border: none;
}
@media (min-width: 768px) {
  .add-plan__plus {
    width: 25px;
    height: 25px;
    background-size: 20px, 20px;
    margin: 21px 18px 0px 0px;
  }
}
.add-plan__left {
  background-color: transparent;
  background-image: url("../assets/img/arrow-back-icon.svg");
  background-repeat: no-repeat;
  background-position: center;
  border: none;
}
@media (min-width: 768px) {
  .add-plan__left {
    width: 36px;
    height: 36px;
    background-size: 28px, 20px;
    margin: 27px 0px 0px 10px;
  }
}
@media (min-width: 1440px) {
  .add-plan__left {
    width: 36px;
    height: 36px;
    background-size: 28px, 20px;
    margin: 27px 0px 0px -9px;
  }
}
.add-plan__right {
  background-color: transparent;
  background-image: url("../assets/img/arrow-next-icon.svg");
  background-repeat: no-repeat;
  background-position: center;
  border: none;
}
@media (min-width: 768px) {
  .add-plan__right {
    width: 36px;
    height: 36px;
    background-size: 28px, 20px;
    margin: 24px 8px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .add-plan__right {
    width: 36px;
    height: 36px;
    background-size: 28px, 20px;
    margin: 24px -8px 0px 0px;
  }
}
.add-plan__input-wrapper {
  display: flex;
  justify-content: center;
  width: 221px;
  min-height: 42px;
  border-top: solid 1px black;
  border-bottom: solid 1px black;
  margin: -4px 0px 0px 0px;
}
@media (min-width: 768px) {
  .add-plan__input-wrapper {
    display: flex;
    justify-content: space-between;
    min-width: 532px;
    min-height: 86px;
    margin-top: -28px;
    margin-bottom: 0px;
    margin-left: auto;
    margin-right: auto;
  }
}
@media (min-width: 1440px) {
  .add-plan__input-wrapper {
    width: 1000px;
    min-height: 86px;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: auto;
    margin-right: auto;
    padding: 0px 0px 0px 0px;
  }
}
.add-plan__search {
  border: none;
  text-align: center;
}
@media (min-width: 768px) {
  .add-plan__search {
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 18px;
    text-transform: uppercase;
    color: #1D2E5B;
  }
}
@media (min-width: 1440px) {
  .add-plan__search {
    width: 90px;
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 18px;
    text-transform: uppercase;
    color: #1D2E5B;
  }
}
.add-plan__time {
  border: none;
  text-align: center;
}
@media (min-width: 768px) {
  .add-plan__time {
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 18px;
    text-transform: uppercase;
    color: #1D2E5B;
  }
}
@media (min-width: 1440px) {
  .add-plan__time {
    width: 88px;
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 18px;
    text-transform: uppercase;
    color: #1D2E5B;
  }
}
.add-plan__date {
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 20px;
  line-height: 20px;
  color: #1D2E5B;
  border: none;
  text-align: center;
}
@media (min-width: 768px) {
  .add-plan__date {
    font-style: normal;
    font-weight: bold;
    font-size: 36px;
    line-height: 36px;
    color: #1D2E5B;
  }
}
.add-plan__label-person {
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: 500;
  font-size: 16px;
  line-height: 37px;
  letter-spacing: 0.09em;
  text-transform: uppercase;
  color: #1D2E5B;
  margin-bottom: 0px;
}
@media (min-width: 768px) {
  .add-plan__label-person {
    font-size: 20px;
    line-height: 18px;
  }
}
@media (min-width: 1440px) {
  .add-plan__label-person {
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 18px;
    letter-spacing: normal;
    margin: 0px 0px 0px -11px;
    padding: 0px 0px 0px 0px;
  }
}
.add-plan__label-dates {
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: 500;
  font-size: 16px;
  line-height: 35px;
  letter-spacing: 0.09em;
  text-transform: uppercase;
  color: #1D2E5B;
  margin-bottom: 0px;
}
@media (min-width: 768px) {
  .add-plan__label-dates {
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 18px;
    letter-spacing: 0.1em;
    margin: 0px 0px 0px 0px;
    padding: 0px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .add-plan__label-dates {
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 18px;
    letter-spacing: normal;
    margin: 0px 8px 0px -23px;
    padding: 0px 0px 0px 0px;
  }
}
.add-plan__label-desc-search {
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: 500;
  font-size: 16px;
  line-height: 16px;
  text-align: right;
  letter-spacing: 0.07em;
  text-transform: uppercase;
  color: #1D2E5B;
  opacity: 0.3;
  margin-left: 31px;
}
@media (min-width: 768px) {
  .add-plan__label-desc-search {
    font-size: 20px;
    line-height: 18px;
    margin-top: 0px;
    margin-left: 291px;
  }
}
@media (min-width: 1440px) {
  .add-plan__label-desc-search {
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 18px;
    letter-spacing: normal;
    text-transform: uppercase;
    opacity: 1;
    color: #1D2E5B;
    margin: 0px 19px 0px 0px;
    padding: 0px 0px 0px 0px;
    order: 3;
  }
}
.add-plan__label-desc-dates {
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: 500;
  font-size: 16px;
  line-height: 16px;
  text-align: right;
  letter-spacing: 0.07em;
  text-transform: uppercase;
  color: #1D2E5B;
  opacity: 0.3;
  margin-left: 60px;
}
@media (min-width: 768px) {
  .add-plan__label-desc-dates {
    font-size: 20px;
    line-height: 18px;
    margin-top: 0px;
    margin-left: 331px;
  }
}
@media (min-width: 1440px) {
  .add-plan__label-desc-dates {
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 18px;
    text-transform: uppercase;
    letter-spacing: normal;
    opacity: 1;
    color: #1D2E5B;
    margin: 0px 13px 0px 11px;
    padding: 0px 0px 0px 0px;
    order: 3;
  }
}
.add-plan__calendar-days {
  width: 224px;
  min-height: 224px;
  border-collapse: collapse;
  margin-top: 10px;
}
@media (min-width: 768px) {
  .add-plan__calendar-days {
    min-width: 532px;
    min-height: 400px;
    margin-top: 30px;
    margin-bottom: 0px;
    margin-left: auto;
    margin-right: auto;
  }
}
@media (min-width: 1440px) {
  .add-plan__calendar-days {
    min-width: 1000px;
    min-height: auto;
    height: 463px;
    width: auto;
    margin: 19px auto 0px auto;
    padding: 0px 0px 0px 0px;
  }
}
@media (min-width: 768px) {
  .add-plan__cal-mobile {
    display: none;
  }
}
@media (min-width: 1440px) {
  .add-plan__cal-mobile {
    display: none;
  }
}
.add-plan__cal-tablet {
  display: none;
}
@media (min-width: 768px) {
  .add-plan__cal-tablet {
    display: table-row;
  }
}
@media (min-width: 1440px) {
  .add-plan__cal-tablet {
    display: table-row;
  }
}
.add-plan__week-day {
  width: 32px;
  height: 32px;
  text-align: center;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: normal;
  font-size: 18px;
  line-height: 18px;
  color: #444444;
}
@media (min-width: 1440px) {
  .add-plan__week-day {
    text-align: left;
    vertical-align: top;
    padding: 0px 0px 18px 14px;
    box-sizing: border-box;
  }
}
.add-plan__weekend-day {
  width: 32px;
  height: 32px;
  text-align: center;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: normal;
  font-size: 18px;
  line-height: 18px;
  color: #FF5C23;
}
@media (min-width: 1440px) {
  .add-plan__weekend-day {
    text-align: left;
    vertical-align: top;
    padding: 0px 0px 0px 14px;
    box-sizing: border-box;
  }
}
.add-plan__week-date {
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 18px;
  color: #444444;
  opacity: 0.3;
  width: 32px;
  height: 27px;
  text-align: center;
  border: 1px solid #D6D9E6;
  cursor: pointer;
}
@media (min-width: 768px) {
  .add-plan__week-date {
    font-style: normal;
    font-weight: normal;
    font-size: 18px;
    line-height: 18px;
    height: 66px;
  }
}
@media (min-width: 1440px) {
  .add-plan__week-date {
    font-style: normal;
    font-weight: normal;
    font-size: 18px;
    line-height: 18px;
    height: auto;
    text-align: left;
    vertical-align: top;
    padding: 10px 0px 0px 15px;
    box-sizing: border-box;
  }
}
.add-plan__week-date:hover {
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  color: #FFFFFF;
  background-color: #1D2E5B;
  opacity: 1;
  box-sizing: border-box;
}
.add-plan__week-date:active {
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  color: #FFFFFF;
  background-color: #1D2E5B;
  box-shadow: inset 0px 0px 0px 8px #ff5c23;
  opacity: 1;
  box-sizing: border-box;
}
.add-plan__week-date:disabled {
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: normal;
  color: #444444;
  opacity: 0.3;
  text-align: center;
  border: 1px solid #D6D9E6;
  cursor: pointer;
}
.add-plan__week-date-blue {
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: 500;
  font-size: 14px;
  line-height: 18px;
  color: #FFFFFF;
  background-color: #1D2E5B;
  opacity: 1;
  box-sizing: border-box;
}
.add-plan__week-date-grey {
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: 500;
  font-size: 14px;
  line-height: 18px;
  color: #1D2E5B;
  background-color: #EDEFF6;
  opacity: 1;
  border: 1px solid #CBCED9;
  box-sizing: border-box;
}
.add-plan__button-back {
  width: 130px;
  height: 22px;
  border: none;
  background-color: transparent;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 17px;
  line-height: 30px;
  letter-spacing: 0.01em;
  text-transform: uppercase;
  color: #1D2E5B;
}
.add-plan__step-two {
  grid-column-start: 1;
  grid-row-start: 1;
  grid-row-end: 2;
  display: inline-block;
  width: 81px;
  height: 40px;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 20px;
  line-height: 20px;
  color: #1D2E5B;
  margin: -3px 0px 0px -2px;
  padding-left: 25px;
  padding-right: 20px;
  align-self: flex-start;
}
@media (min-width: 768px) {
  .add-plan__step-two {
    display: inline-block;
    width: 146px;
    height: 72px;
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: bold;
    font-size: 36px;
    line-height: 36px;
    grid-column-start: 1;
    grid-row-start: 1;
    grid-row-end: 2;
    margin-top: 45px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
    padding-left: 0px;
    padding-right: 0px;
  }
}
@media (min-width: 1440px) {
  .add-plan__step-two {
    grid-column-start: 1;
    grid-column-end: 2;
    grid-row-start: 1;
    grid-row-end: 3;
    width: 265px;
    height: 72px;
    margin-top: 95px;
    margin-bottom: 0px;
    margin-left: 159px;
    margin-right: 0px;
    padding: 0px 0px 0px 0px;
  }
}
.add-plan__step-two-text {
  grid-column-start: 1;
  grid-row-start: 2;
  grid-row-end: 3;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 22px;
  color: #444444;
  margin-top: 13px;
  margin-bottom: 0px;
  padding-left: 25px;
  padding-right: 25px;
}
@media (min-width: 768px) {
  .add-plan__step-two-text {
    grid-column-start: 1;
    grid-row-start: 2;
    grid-row-end: 3;
    display: inline-block;
    width: 534px;
    height: 48px;
    font-size: 20px;
    line-height: 24px;
    margin-top: 30px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
    padding-top: 0px;
    padding-bottom: 82px;
    padding-left: 0px;
    padding-right: 130px;
    border-bottom: 1px solid #E1E3E9;
    box-sizing: border-box;
  }
}
@media (min-width: 1440px) {
  .add-plan__step-two-text {
    grid-column-start: 1;
    grid-column-end: 2;
    grid-row-start: 2;
    grid-row-end: 3;
    width: 400px;
    height: 48px;
    margin-top: 38px;
    margin-bottom: 0px;
    margin-left: 159px;
    margin-right: 0px;
    padding: 0px 0px 0px 0px;
    border: none;
  }
}
.add-plan__country-field-one {
  grid-column-start: 1;
  grid-row-start: 3;
  grid-row-end: 4;
  display: flex;
  border-radius: 5px;
  width: 220px;
  height: 42px;
  align-items: center;
  margin-top: 21px;
  margin-bottom: 0px;
  margin-left: auto;
  margin-right: auto;
  border: solid 1px transparent;
}
@media (min-width: 768px) {
  .add-plan__country-field-one {
    grid-column-start: 1;
    grid-row-start: 3;
    grid-row-end: 4;
    display: flex;
    flex-direction: row;
    align-items: center;
    width: auto;
    height: 70px;
    margin-top: 42px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .add-plan__country-field-one {
    grid-column-start: 1;
    grid-column-end: 3;
    grid-row-start: 3;
    grid-row-end: 5;
    margin-top: 84px;
    margin-bottom: 0px;
    margin-left: 159px;
    margin-right: 0px;
    padding: 0px 0px 0px 0px;
  }
}
.add-plan__input-container {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  width: 168px;
  height: 42px;
  border: 1px solid #CBCED9;
  box-sizing: border-box;
  border-radius: 4px;
  padding: 0px 17px 0px 0px;
  margin: 0px 0px 0px 0px;
}
@media (min-width: 768px) {
  .add-plan__input-container {
    width: 369px;
    height: 70px;
    border: 1px solid #CBCED9;
    box-sizing: border-box;
    border-radius: 4px;
    padding: 0px 30px 0px 15px;
    margin: -16px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .add-plan__input-container {
    width: 730px;
    height: 70px;
    border: 1px solid #CBCED9;
    box-sizing: border-box;
    border-radius: 4px;
    padding: 0px 30px 0px 15px;
    margin: -16px 0px 0px 0px;
  }
}
.add-plan__btn-container {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  width: 53px;
  height: 42px;
  border: 1px solid #CBCED9;
  box-sizing: border-box;
  border-radius: 4px;
  padding: 0px 0px 0px 0px;
  margin: 0px 0px 0px 0px;
}
@media (min-width: 768px) {
  .add-plan__btn-container {
    width: 160px;
    height: 70px;
    border: 1px solid transparent;
    box-sizing: border-box;
    padding: 0px 0px 0px 0px;
    margin: -13px 0px 0px 19px;
  }
}
@media (min-width: 1440px) {
  .add-plan__btn-container {
    width: 240px;
    height: 70px;
    border: 1px solid transparent;
    box-sizing: border-box;
    padding: 0px 0px 0px 0px;
    margin: -13px 0px 0px 38px;
  }
}
.add-plan__country-field-two {
  grid-column-start: 1;
  grid-row-start: 4;
  grid-row-end: 5;
  display: flex;
  border: solid 1px #EDEFF6;
  border-radius: 5px;
  width: 220px;
  height: 42px;
  align-items: center;
  margin-top: 15px;
  margin-bottom: 0px;
  margin-left: auto;
  margin-right: auto;
}
@media (min-width: 768px) {
  .add-plan__country-field-two {
    grid-column-start: 1;
    grid-row-start: 4;
    grid-row-end: 5;
    width: auto;
    height: auto;
    margin-top: -35px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
    border: none;
  }
}
@media (min-width: 1440px) {
  .add-plan__country-field-two {
    grid-column-start: 1;
    grid-column-end: 3;
    grid-row-start: 4;
    grid-row-end: 5;
    margin-top: 24px;
    margin-bottom: 0px;
    margin-left: 160px;
    margin-right: 0px;
    padding: 0px 0px 0px 0px;
  }
}
.add-plan__dropdown-wrap {
  grid-column-start: 1;
  grid-row-start: 5;
  grid-row-end: 6;
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 220px;
  min-height: 42px;
  border: solid 1px #EDEFF6;
  border-radius: 5px;
  margin-top: 7px;
  margin-bottom: 0px;
  margin-left: auto;
  margin-right: auto;
  padding: 0px 13px 0px 0px;
  box-sizing: border-box;
}
@media (min-width: 768px) {
  .add-plan__dropdown-wrap {
    width: 370px;
    height: 70px;
    grid-column-start: 1;
    grid-row-start: 5;
    grid-row-end: 6;
    margin-top: -35px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
    padding: 0px 27px 0px 14px;
    box-sizing: border-box;
  }
}
@media (min-width: 1440px) {
  .add-plan__dropdown-wrap {
    grid-column-start: 1;
    grid-column-end: 3;
    grid-row-start: 5;
    grid-row-end: 6;
    width: 730px;
    height: 70px;
    margin-top: -11px;
    margin-bottom: 0px;
    margin-left: 160px;
    margin-right: 0px;
    padding: 0px 26px 0px 19px;
  }
}
.add-plan__add-button {
  grid-column-start: 1;
  grid-row-start: 6;
  grid-row-end: 7;
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 220px;
  height: 42px;
  background-color: #EDEFF6;
  border-radius: 4px;
  border: none;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: 500;
  font-size: 14px;
  line-height: 18px;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  color: #1D2E5B;
  margin-top: 23px;
  margin-bottom: 0px;
  margin-left: auto;
  margin-right: auto;
  padding: 0px 15px 0px 11px;
  box-sizing: border-box;
}
@media (min-width: 768px) {
  .add-plan__add-button {
    grid-column-start: 1;
    grid-row-start: 6;
    grid-row-end: 7;
    width: 369px;
    height: 70px;
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 20px;
    letter-spacing: 0.09em;
    text-transform: uppercase;
    color: #1D2E5B;
    margin-top: -73px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
    padding: 0px 28px 0px 27px;
    box-sizing: border-box;
  }
}
@media (min-width: 1440px) {
  .add-plan__add-button {
    grid-column-start: 1;
    grid-column-end: 3;
    grid-row-start: 6;
    grid-row-end: 7;
    width: 730px;
    height: 70px;
    margin-top: -56px;
    margin-bottom: 0px;
    margin-left: 160px;
    margin-right: 0px;
    padding: 0px 29px 0px 26px;
  }
}
.add-plan__add-button:hover {
  background-color: #DFE3F0;
}
.add-plan__add-button:active {
  background-color: #DFE3F0;
}
@media (min-width: 768px) {
  .add-plan__add-button .add-plan__circle-empty {
    position: absolute;
    transform: translate(2578%, -9%);
    width: 14px;
    height: 14px;
    border-radius: 50%;
    margin: 0px 0px 0px 0px;
    padding: 0px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .add-plan__add-button .add-plan__circle-empty {
    position: absolute;
    transform: translate(5308%, -9%);
    width: 14px;
    height: 14px;
    border-radius: 50%;
    margin: 0px 0px 0px 0px;
    padding: 0px 0px 0px 0px;
  }
}
.add-plan__btn-next-step-two {
  grid-column-start: 1;
  grid-row-start: 7;
  grid-row-end: 8;
  width: 229px;
  height: 40px;
  background-color: #FFD74B;
  border-radius: 20px;
  border: none;
  margin-top: 11px;
  margin-bottom: 0px;
  margin-left: auto;
  margin-right: auto;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 17px;
  line-height: 30px;
  text-transform: uppercase;
  color: #1D2E5B;
}
@media (min-width: 768px) {
  .add-plan__btn-next-step-two {
    grid-column-start: 1;
    grid-row-start: 7;
    grid-row-end: 8;
    width: 286px;
    height: 80px;
    font-style: normal;
    font-weight: bold;
    font-size: 24px;
    line-height: 24px;
    text-transform: none;
    background-image: url(../assets/img/icon-btn-triangle.svg);
    background-repeat: no-repeat;
    background-position: 87%, 50%;
    margin-top: -73px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
    padding: 0px 42px 0px 0px;
    box-sizing: border-box;
  }
}
@media (min-width: 1440px) {
  .add-plan__btn-next-step-two {
    grid-column-start: 1;
    grid-column-end: 2;
    grid-row-start: 7;
    grid-row-end: 8;
    margin-top: -56px;
    margin-bottom: 0px;
    margin-left: 160px;
    margin-right: 0px;
    padding: 0px 44px 0px 0px;
  }
}
.add-plan__btn-next-step-two:hover {
  background-color: #FFBD30;
}
.add-plan__btn-next-step-two:active {
  background-color: #FFBD30;
}
.add-plan__btn-next-step-two > span:hover {
  color: #1D2E5B;
  opacity: 0.3;
}
.add-plan__btn-back-step-two {
  grid-column-start: 1;
  grid-row-start: 8;
  grid-row-end: 9;
  width: 130px;
  height: 22px;
  border: none;
  background-color: transparent;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 17px;
  line-height: 30px;
  letter-spacing: 0.01em;
  text-transform: uppercase;
  color: #1D2E5B;
  margin-top: -18px;
  margin-bottom: 0px;
  margin-left: auto;
  margin-right: auto;
}
@media (min-width: 768px) {
  .add-plan__btn-back-step-two {
    grid-column-start: 1;
    grid-row-start: 7;
    width: 185px;
    height: 22px;
    margin-top: -47px;
    margin-bottom: 0px;
    margin-left: 349px;
    margin-right: 0px;
    background-image: url(../assets/img/triangle-arrow-left.svg);
    background-repeat: no-repeat;
    background-position: 2% 79%;
    background-size: 11px;
  }
}
@media (min-width: 1440px) {
  .add-plan__btn-back-step-two {
    grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 7;
    grid-row-end: 8;
    margin-top: -31px;
    margin-bottom: 0px;
    margin-left: 62px;
    margin-right: 0px;
    padding: 0px 0px 0px 0px;
    letter-spacing: normal;
  }
}
.add-plan__btn-back-step-two:hover {
  opacity: 0.7;
}
.add-plan__btn-back-step-two:active {
  opacity: 0.3;
}
button:focus {
  outline: 0;
}
.add-plan__country {
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: 500;
  font-size: 14px;
  line-height: 18px;
  letter-spacing: 0.09em;
  text-transform: uppercase;
  color: #1D2E5B;
  border: none;
  margin: 0px 0px 0px 0px;
  padding: 0px 0px 0px 9px;
}
@media (min-width: 768px) {
  .add-plan__country {
    font-size: 20px;
    line-height: 20px;
    letter-spacing: 0.1em;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .add-plan__country {
    width: 260px;
    font-size: 20px;
    line-height: 20px;
    letter-spacing: 0.1em;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
  }
}
.add-plan__checkmark {
  width: 16px;
  height: 12px;
  background-color: transparent;
  opacity: 0.3;
  transform: rotate(-90deg);
  background-image: url("../assets/img/arrow-back-icon.svg");
  background-repeat: no-repeat;
  background-position: center;
  margin: 0px 0px 0px 5px;
  padding: 0px 0px 0px 0px;
}
.add-plan__circle {
  position: absolute;
  transform: translate(-158%, -9%);
  width: 8px;
  height: 8px;
  border-radius: 50%;
  background-color: #1D2E5B;
  margin: 0px 0px 0px 6px;
  padding: 0px 0px 0px 0px;
}
@media (min-width: 768px) {
  .add-plan__circle {
    position: absolute;
    transform: translate(-8%, -29%);
    width: 14px;
    height: 14px;
    border-radius: 50%;
    background-color: #1D2E5B;
    margin: 0px 0px 0px 0px;
    padding: 0px 0px 0px 0px;
  }
}
.add-plan__circle-empty {
  width: 8px;
  height: 8px;
  border-radius: 50%;
  background-color: transparent;
  border: 1px solid #CBCED9;
  box-sizing: border-box;
}
@media (min-width: 768px) {
  .add-plan__circle-empty {
    position: absolute;
    transform: translate(2668%, -17%);
    width: 14px;
    height: 14px;
    border-radius: 50%;
    margin: 0px 0px 0px 0px;
    padding: 0px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .add-plan__circle-empty {
    position: absolute;
    transform: translate(5343%, -17%);
    width: 14px;
    height: 14px;
    border-radius: 50%;
    margin: 0px 0px 0px 0px;
    padding: 0px 0px 0px 0px;
  }
}
.add-plan__flag-bosnia {
  width: 53px;
  height: 42px;
  background-image: url("../assets/img/flag-bosnia.svg");
  background-repeat: no-repeat;
  background-position: 50%, 50%;
  background-size: 35px, 24px;
  margin: 0px 0px 0px 0px;
  padding: 0px 0px 0px 0px;
}
@media (min-width: 768px) {
  .add-plan__flag-bosnia {
    width: 70px;
    height: 47px;
    background-image: url("../assets/img/flag-bosnia.svg");
    background-repeat: no-repeat;
    background-position: 50%, 50%;
    background-size: 70px, 24px;
    margin: -2px 0px 0px 32px;
    padding: 0px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .add-plan__flag-bosnia {
    width: 70px;
    height: 47px;
    background-image: url("../assets/img/flag-bosnia.svg");
    background-repeat: no-repeat;
    background-position: 50%, 50%;
    background-size: 70px, 24px;
    margin: -2px 0px 0px 46px;
    padding: 0px 0px 0px 0px;
  }
}
.add-plan__flag-czech {
  width: 53px;
  height: 42px;
  background-image: url("../assets/img/flag-czech.svg");
  background-repeat: no-repeat;
  background-position: 50%, 50%;
  background-size: 35px, 24px;
  margin: 0px 0px 0px 0px;
  padding: 0px 0px 0px 0px;
}
@media (min-width: 768px) {
  .add-plan__flag-czech {
    width: 70px;
    height: 47px;
    background-image: url(../assets/img/flag-czech.svg);
    background-repeat: no-repeat;
    background-position: 50%, 50%;
    background-size: 70px, 24px;
    margin: -3px 0px 0px 33px;
    padding: 0px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .add-plan__flag-czech {
    width: 70px;
    height: 47px;
    background-image: url(../assets/img/flag-czech.svg);
    background-repeat: no-repeat;
    background-position: 50%, 50%;
    background-size: 70px, 24px;
    margin: -3px 0px 0px 46px;
    padding: 0px 0px 0px 0px;
  }
}
.add-plan__remove-btn {
  position: absolute;
  transform: translate(187%, -96%);
  width: 21px;
  height: 21px;
  border-radius: 50%;
  background-image: url("../assets/img/icon-close-btn.svg");
  background-repeat: no-repeat;
  background-position: center;
  border: none;
  margin: 0px 0px 0px 0px;
  padding: 0px 0px 0px 0px;
}
@media (min-width: 768px) {
  .add-plan__remove-btn {
    position: absolute;
    transform: translate(562%, -10%);
    width: 22px;
    height: 22px;
    border-radius: 0%;
    background-image: url(../assets/img/icon-close-btn.svg);
    background-repeat: no-repeat;
    background-position: center;
    background-size: 21px, 30px;
    border: none;
    margin: 0px 0px 0px 0px;
    padding: 0px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .add-plan__remove-btn {
    position: absolute;
    transform: translate(930%, -10%);
    width: 22px;
    height: 22px;
    border-radius: 0%;
    background-image: url(../assets/img/icon-close-btn.svg);
    background-repeat: no-repeat;
    background-position: center;
    background-size: 21px, 30px;
    border: none;
    margin: 0px 0px 0px 0px;
    padding: 0px 0px 0px 0px;
  }
}
.add-plan__dropdown-wrap .add-plan__remove-btn {
  position: absolute;
  transform: translate(984%, -96%);
  width: 21px;
  height: 21px;
  border-radius: 50%;
  background-image: url("../assets/img/icon-close-btn.svg");
  background-repeat: no-repeat;
  background-position: center;
  border: none;
  margin: 0px 0px 0px 0px;
  padding: 0px 0px 0px 0px;
}
@media (min-width: 768px) {
  .add-plan__dropdown-wrap .add-plan__remove-btn {
    position: absolute;
    transform: translate(2246%, -3%);
    width: 22px;
    height: 22px;
    border-radius: 0%;
    background-image: url("../assets/img/icon-close-btn.svg");
    background-repeat: no-repeat;
    background-position: center;
    border: none;
    margin: 0px 0px 0px 0px;
    padding: 0px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .add-plan__dropdown-wrap .add-plan__remove-btn {
    position: absolute;
    transform: translate(4339%, -3%);
    width: 22px;
    height: 22px;
    border-radius: 0%;
    background-image: url("../assets/img/icon-close-btn.svg");
    background-repeat: no-repeat;
    background-position: center;
    border: none;
    margin: 0px 0px 0px 0px;
    padding: 0px 0px 0px 0px;
  }
}
.add-plan__add-plus {
  width: 14px;
  height: 14px;
  background-image: url("../assets/img/icon-plus.svg");
  background-repeat: no-repeat;
  background-position: center;
  margin: 0px 0px 0px 0px;
  padding: 0px 0px 0px 0px;
  box-sizing: border-box;
}
.add-plan__choose-button {
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: 500;
  font-size: 14px;
  line-height: 18px;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  color: #1D2E5B;
  background-color: transparent;
  border: none;
  padding: 0px 0px 0px 10px;
  box-sizing: border-box;
}
@media (min-width: 768px) {
  .add-plan__choose-button {
    font-size: 20px;
    line-height: 20px;
    letter-spacing: 0.1em;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .add-plan__choose-button {
    font-size: 20px;
    line-height: 20px;
    letter-spacing: 0.1em;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
    padding: 0px 0px 0px 6px;
  }
}
.add-plan__todo {
  display: block;
  width: 218px;
  height: 220px;
  border: solid 1px #444444;
  border-radius: 5px;
  text-align: left;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 22px;
  color: #444444;
  opacity: 0.3;
  margin-top: 13px;
  margin-bottom: 0px;
  margin-left: auto;
  margin-right: auto;
  padding: 9px 0px 0px 11px;
  white-space: normal;
  box-sizing: border-box;
}
@media (min-width: 768px) {
  .add-plan__todo {
    font-style: normal;
    font-weight: normal;
    font-size: 20px;
    line-height: 23px;
    min-width: 500px;
    width: auto;
    height: 142px;
    border-radius: 5px;
    margin-top: 31px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
    padding: 16px 52px 0px 21px;
    box-sizing: border-box;
  }
}
@media (min-width: 1440px) {
  .add-plan__todo {
    font-style: normal;
    font-weight: normal;
    font-size: 20px;
    line-height: 23px;
    min-width: 731px;
    width: auto;
    height: 142px;
    border-radius: 5px;
    margin-top: 26px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
    padding: 21px 0px 0px 25px;
    box-sizing: border-box;
  }
}
.add-plan__todo:hover {
  border: 1px solid #959BB2;
}
.add-plan__todo:active {
  border: 1px solid #161C35;
}
.add-plan__todo:invalid {
  border: 1px solid #F47E7E;
}
.add-plan__border {
  position: absolute;
  width: 26px;
  height: 309px;
  background-image: url(../assets/img/line-country.svg);
  background-repeat: no-repeat;
  transform: translate(-58%, 4%);
}
@media (min-width: 768px) {
  .add-plan__border {
    position: absolute;
    width: 15px;
    height: 300px;
    border: none;
    background-image: url("../assets/img/tablet-line-country.png");
    background-repeat: no-repeat;
    transform: translate(3472%, 12%);
  }
}
@media (min-width: 1440px) {
  .add-plan__border {
    position: absolute;
    width: 15px;
    height: 300px;
    border: none;
    background-image: url("../assets/img/tablet-line-country.png");
    background-repeat: no-repeat;
    transform: translate(5112%, 12%);
  }
}
.add-plan__country-modal {
  position: absolute;
  z-index: 10;
  transform: translate(0%, 46%);
  width: 217px;
  min-height: 544px;
  background-color: #FFFFFF;
  border: solid 1px #CBCED9;
  border-radius: 4px;
}
@media (min-width: 768px) {
  .add-plan__country-modal {
    z-index: 10;
    display: grid;
    grid-template-columns: 2fr 1fr;
    grid-template-rows: 1fr 4fr;
    position: absolute;
    width: 575px;
    min-height: 485px;
    transform: translate(-4%, 42%);
    border: solid 1px transparent;
  }
}
@media (min-width: 1440px) {
  .add-plan__country-modal {
    z-index: 10;
    display: grid;
    grid-template-columns: 2fr 1fr;
    grid-template-rows: 1fr 4fr;
    position: absolute;
    width: 730px;
    min-height: 556px;
    transform: translate(-3%, 42%);
    border: solid 1px transparent;
  }
}
.add-plan__modal-btn {
  display: block;
  width: 100%;
  height: 42px;
  background: #1D2E5B;
  background-image: url(../assets/img/icon-close-btn.svg);
  background-repeat: no-repeat;
  background-position: 92%, 50%;
  text-align: left;
  border-top-right-radius: 4px;
  border-top-left-radius: 4px;
  border: none;
  margin: 0px 0px 0px 0px;
  padding: 0px 0px 0px 14px;
}
@media (min-width: 768px) {
  .add-plan__modal-btn {
    grid-column-start: 1;
    grid-column-end: 2;
    grid-row-start: 1;
    grid-row-end: 2;
    display: block;
    width: 369px;
    height: 71px;
    background: #1D2E5B;
    background-image: url(../assets/img/icon-close-btn.svg);
    background-repeat: no-repeat;
    background-position: 93%, 50%;
    background-size: 22px;
    text-align: left;
    border-top-right-radius: 4px;
    border-top-left-radius: 4px;
    border: none;
    margin: 1px 0px 0px 2px;
    padding: 0px 0px 0px 14px;
  }
}
@media (min-width: 1440px) {
  .add-plan__modal-btn {
    grid-column-start: 1;
    grid-column-end: 3;
    grid-row-start: 1;
    grid-row-end: 2;
    display: block;
    width: 727px;
    height: 71px;
    background: #1D2E5B;
    background-image: url(../assets/img/icon-close-btn.svg);
    background-repeat: no-repeat;
    background-position: 97%, 50%;
    background-size: 22px;
    text-align: left;
    border-top-right-radius: 4px;
    border-top-left-radius: 4px;
    border: none;
    margin: 8px 0px 0px 2px;
    padding: 0px 0px 0px 14px;
  }
}
.add-plan__modal-btn-text {
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: 500;
  font-size: 14px;
  line-height: 18px;
  letter-spacing: 0.02em;
  text-transform: uppercase;
  text-align: left;
  color: #FFFFFF;
  margin: 0px 0px 0px 0px;
  padding: 0px 0px 0px 0px;
}
@media (min-width: 768px) {
  .add-plan__modal-btn-text {
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 20px;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    margin: 0px 0px 0px 0px;
    padding: 0px 0px 0px 11px;
  }
}
@media (min-width: 1440px) {
  .add-plan__modal-btn-text {
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 20px;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    margin: 0px 0px 0px 0px;
    padding: 0px 0px 0px 9px;
  }
}
.add-plan__alphabet {
  border-collapse: collapse;
}
@media (min-width: 768px) {
  .add-plan__alphabet {
    grid-column-start: 1;
    grid-column-end: 2;
    grid-row-start: 2;
    grid-row-end: 3;
    width: 262px;
    height: 346px;
    margin: 10px 0px 0px 29px;
  }
}
@media (min-width: 1440px) {
  .add-plan__alphabet {
    grid-column-start: 1;
    grid-column-end: 2;
    grid-row-start: 2;
    grid-row-end: 3;
    border-collapse: separate;
    border-spacing: 15px;
    width: 391px;
    height: 438px;
    margin: -13px 0px 0px 12px;
  }
}
.add-plan__letters {
  width: 44px;
  height: 38px;
  border: 1px solid #CBCED9;
  font-family: "Blogger Sans";
  font-style: normal;
  font-weight: 500;
  font-size: 14px;
  line-height: 18px;
  text-align: center;
  text-transform: uppercase;
  color: #1D2E5B;
  cursor: pointer;
}
@media (min-width: 768px) {
  .add-plan__letters {
    font-size: 20px;
    line-height: 20px;
  }
}
@media (min-width: 1440px) {
  .add-plan__letters {
    width: auto;
    height: auto;
    font-size: 20px;
    line-height: 20px;
    border-radius: 4px;
  }
}
.add-plan__letters:hover {
  border: 1px solid #959BB2;
}
.add-plan__letters:active {
  background-color: #1D2E5B;
  color: #FFFFFF;
}
.add-plan__country-list {
  padding-top: 15px;
  padding-left: 16px;
  background-color: #FFFFFF;
}
@media (min-width: 768px) {
  .add-plan__country-list {
    grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 1;
    grid-row-end: 3;
    padding-top: 34px;
    padding-left: 8px;
    margin: 68px 0px 0px 5px;
  }
}
@media (min-width: 1440px) {
  .add-plan__country-list {
    grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 1;
    grid-row-end: 3;
    padding-top: 30px;
    padding-left: 8px;
    margin: 79px 0px 0px 21px;
  }
}
.add-plan__country-item {
  display: block;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 26px;
  color: #444444;
}
@media (min-width: 768px) {
  .add-plan__country-item {
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: normal;
    font-size: 20px;
    line-height: 30px;
    color: #444444;
  }
}
.add-plan__item-two {
  display: grid;
  grid-template-columns: 1fr;
  grid-template-rows: 0.5fr 1fr 0.9fr 0.9fr 0.3fr 1fr 1fr 0.3fr;
  width: 270px;
  min-height: 492px;
  background-color: #FFFFFF;
  border-radius: 10px;
  margin: 0 auto;
  margin-top: 9px;
  padding-top: 24px;
  padding-bottom: 0px;
}
@media (min-width: 768px) {
  .add-plan__item-two {
    display: grid;
    grid-template-columns: 1fr;
    grid-template-rows: 1fr 1fr 1fr 1fr 1fr 1fr 0.5fr;
    min-width: 575px;
    min-height: 784px;
    border-radius: 30px;
    margin-top: 39px;
    margin-bottom: 10px;
    margin-left: auto;
    margin-right: auto;
    padding-top: 0px;
    padding-bottom: 0px;
    padding-left: 43px;
  }
}
@media (min-width: 1440px) {
  .add-plan__item-two {
    display: grid;
    grid-template-columns: 3fr 1fr;
    grid-template-rows: 1fr 1fr 1fr 1fr 1fr 1fr 1fr;
    min-width: 1320px;
    min-height: 901px;
    border-radius: 60px;
    margin: 42px auto 0px auto;
    padding: 0px 0px 0px 0px;
  }
}
.add-plan__item-three {
  display: grid;
  grid-template-columns: 1fr;
  grid-template-rows: 0.5fr 1fr 1fr 1fr 1fr 1fr 1fr 0.5fr;
  width: 270px;
  min-height: 799px;
  background-color: #FFFFFF;
  border-radius: 10px;
  margin: 0 auto;
  margin-top: 10px;
  margin-bottom: 60px;
  padding-top: 20px;
  padding-bottom: 20px;
}
@media (min-width: 768px) {
  .add-plan__item-three {
    display: grid;
    grid-template-columns: 1fr;
    grid-template-rows: 0.5fr 1fr 1fr 1fr 1fr 1fr 1fr;
    min-width: 575px;
    min-height: 883px;
    margin-top: 51px;
    margin-bottom: 62px;
    margin-left: auto;
    margin-right: auto;
    padding-top: 0px;
    padding-bottom: 39px;
    padding-left: 43px;
    padding-right: 0px;
    border-radius: 30px;
  }
}
@media (min-width: 1440px) {
  .add-plan__item-three {
    display: grid;
    grid-template-columns: 3fr 1fr;
    grid-template-rows: 1fr 1fr 3fr 0.5fr;
    min-width: 1320px;
    min-height: 1064px;
    border-radius: 60px;
    margin: 43px auto 0px auto;
    padding: 0px 0px 0px 0px;
  }
}
.add-plan__step-three {
  display: inline-block;
  width: 116px;
  height: 40px;
  grid-column-start: 1;
  grid-row-start: 1;
  grid-row-end: 2;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 20px;
  line-height: 20px;
  color: #1D2E5B;
  margin: 2px 0px 0px -2px;
  padding-left: 25px;
  padding-right: 20px;
  align-self: flex-start;
}
@media (min-width: 768px) {
  .add-plan__step-three {
    grid-column-start: 1;
    grid-row-start: 1;
    grid-row-end: 2;
    display: inline-block;
    width: 209px;
    height: 72px;
    font-size: 36px;
    line-height: 36px;
    margin-top: 44px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
    padding: 0px;
  }
}
@media (min-width: 1440px) {
  .add-plan__step-three {
    grid-column-start: 1;
    grid-column-end: 2;
    grid-row-start: 1;
    grid-row-end: 2;
    width: 350px;
    height: 72px;
    margin-top: 97px;
    margin-bottom: 0px;
    margin-left: 158px;
    margin-right: 0px;
    padding: 0px 0px 0px 0px;
  }
}
.add-plan__step-three-text {
  grid-column-start: 1;
  grid-row-start: 2;
  grid-row-end: 3;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 22px;
  color: #444444;
  margin-top: 8px;
  margin-bottom: 0px;
  padding-left: 25px;
  padding-right: 25px;
}
@media (min-width: 768px) {
  .add-plan__step-three-text {
    grid-column-start: 1;
    grid-row-start: 2;
    grid-row-end: 3;
    display: inline-block;
    width: 505px;
    height: 48px;
    font-size: 20px;
    line-height: 24px;
    margin-top: 35px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
    padding-bottom: 35px;
    padding-left: 0px;
    padding-right: 0px;
    border-bottom: 1px solid #E1E3E9;
  }
}
@media (min-width: 1440px) {
  .add-plan__step-three-text {
    grid-column-start: 1;
    grid-column-end: 2;
    grid-row-start: 2;
    grid-row-end: 3;
    margin-top: -25px;
    margin-bottom: 0px;
    margin-left: 160px;
    margin-right: 0px;
    padding: 0px 0px 0px 0px;
    border: none;
  }
}
.add-plan__todo-container {
  grid-column-start: 1;
  grid-row-start: 3;
  grid-row-end: 9;
  margin-top: 13px;
  margin-bottom: 0px;
  margin-left: auto;
  margin-right: auto;
}
@media (min-width: 768px) {
  .add-plan__todo-container {
    grid-column-start: 1;
    grid-row-start: 3;
    grid-row-end: 7;
    min-width: 500px;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .add-plan__todo-container {
    grid-column-start: 1;
    grid-column-end: 3;
    grid-row-start: 3;
    grid-row-end: 4;
    margin-top: -61px;
    margin-bottom: 0px;
    margin-left: 160px;
    margin-right: 0px;
    padding: 0px 0px 0px 0px;
  }
}
.add-plan__todo-wrap-one {
  grid-column-start: 1;
  grid-row-start: 3;
  grid-row-end: 6;
  margin-top: 2px;
  margin-bottom: 0px;
  margin-left: auto;
  margin-right: auto;
}
@media (min-width: 768px) {
  .add-plan__todo-wrap-one {
    width: auto;
    margin-top: 17px;
    margin-bottom: 0px;
    margin-left: -1px;
    margin-right: 0px;
  }
}
.add-plan__todo-wrap-two {
  grid-column-start: 1;
  grid-row-start: 6;
  grid-row-end: 9;
  margin-top: 25px;
  margin-bottom: 0px;
  margin-left: auto;
  margin-right: auto;
}
@media (min-width: 768px) {
  .add-plan__todo-wrap-two {
    width: auto;
    margin-top: 41px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .add-plan__todo-wrap-two {
    width: auto;
    margin-top: 47px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
  }
}
.add-plan__submit-button {
  grid-column-start: 1;
  grid-row-start: 9;
  width: 230px;
  height: 40px;
  background-color: #FFD74B;
  border-radius: 20px;
  border: none;
  margin-top: 22px;
  margin-bottom: 0px;
  margin-left: auto;
  margin-right: auto;
}
@media (min-width: 768px) {
  .add-plan__submit-button {
    grid-column-start: 1;
    grid-row-start: 7;
    grid-row-end: 8;
    width: 286px;
    height: 80px;
    margin-top: 35px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
    background-image: url("../assets/img/icon-btn-triangle.svg");
    background-repeat: no-repeat;
    background-position: 87%, 50%;
  }
}
@media (min-width: 1440px) {
  .add-plan__submit-button {
    grid-column-start: 1;
    grid-column-end: 2;
    grid-row-start: 4;
    grid-row-end: 5;
    margin-top: -86px;
    margin-bottom: 0px;
    margin-left: 160px;
    margin-right: 0px;
    padding: 0px 0px 0px 0px;
  }
}
.add-plan__submit-button:hover {
  background-color: #FFBD30;
}
.add-plan__submit-button:active {
  background-color: #FFBD30;
}
.add-plan__submit-btn-text {
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 17px;
  line-height: 30px;
  text-transform: uppercase;
  color: #1D2E5B;
}
@media (min-width: 768px) {
  .add-plan__submit-btn-text {
    font-style: normal;
    font-weight: bold;
    font-size: 24px;
    line-height: 24px;
    text-transform: none;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: -104px;
    margin-right: 0px;
  }
}
.add-plan__btn-back-step-three {
  grid-column-start: 1;
  grid-row-start: 10;
  width: 130px;
  height: 22px;
  border: none;
  background-color: transparent;
  margin-top: 10px;
  margin-bottom: 0px;
  margin-left: auto;
  margin-right: auto;
}
@media (min-width: 768px) {
  .add-plan__btn-back-step-three {
    grid-column-start: 1;
    grid-row-start: 7;
    grid-row-end: 8;
    width: 185px;
    height: 22px;
    margin-top: 63px;
    margin-bottom: 0px;
    margin-left: 349px;
    margin-right: 0px;
    background-image: url(../assets/img/icon-triangle-back.svg);
    background-repeat: no-repeat;
    background-position: 2%, 50%;
  }
}
@media (min-width: 1440px) {
  .add-plan__btn-back-step-three {
    grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 4;
    grid-row-end: 5;
    background-image: url(../assets/img/triangle-arrow-left.svg);
    background-repeat: no-repeat;
    background-position: 2% 50%;
    background-size: 11px;
    margin-top: -58px;
    margin-bottom: 0px;
    margin-left: 63px;
    margin-right: 0px;
    padding: 0px 0px 0px 0px;
  }
}
.add-plan__btn-back-step-three:hover {
  opacity: 0.7;
}
.add-plan__btn-back-step-three:active {
  opacity: 0.3;
}
button:focus {
  outline: 0;
}
.add-plan__btn-back-text {
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 17px;
  line-height: 30px;
  letter-spacing: 0.01em;
  text-transform: uppercase;
  color: #1D2E5B;
}
@media (min-width: 768px) {
  .add-plan__btn-back-text {
    font-style: normal;
    font-weight: bold;
    font-size: 24px;
    line-height: 22px;
    text-transform: none;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: 24px;
    margin-right: -12px;
  }
}
.add-plan__todo-label-wrap {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin: 0px 0px 0px 0px;
  width: 220px;
}
@media (min-width: 768px) {
  .add-plan__todo-label-wrap {
    width: 500px;
  }
}
@media (min-width: 1440px) {
  .add-plan__todo-label-wrap {
    width: 886px;
  }
}
.add-plan__todo-label-dot {
  width: 6px;
  height: 6px;
  border-radius: 50%;
  background-color: #1D2E5B;
}
.add-plan__todo-label {
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: 500;
  font-size: 18px;
  line-height: 18px;
  letter-spacing: 0.01em;
  color: #1D2E5B;
  margin: 0px 0px 0px 10px;
  white-space: nowrap;
}
@media (min-width: 768px) {
  .add-plan__todo-label {
    font-style: normal;
    font-weight: bold;
    font-size: 30px;
    line-height: 30px;
    margin: 0px 0px 0px 0px;
    padding: 0px 0px 0px 0px;
    letter-spacing: normal;
  }
}
@media (min-width: 1440px) {
  .add-plan__todo-label {
    font-style: normal;
    font-weight: bold;
    font-size: 30px;
    line-height: 30px;
    letter-spacing: normal;
    margin: 0px 0px 0px 0px;
    padding: 0px 0px 0px 0px;
  }
}
.add-plan__todo-flag-bosnia {
  width: 35px;
  height: 24px;
  background-image: url("../assets/img/flag-bosnia.svg");
  background-repeat: no-repeat;
  background-position: center;
  background-size: 35px 24px;
  margin: 0px 0px 0px 0px;
}
@media (min-width: 768px) {
  .add-plan__todo-flag-bosnia {
    width: 70px;
    height: 47px;
    background-image: url("../assets/img/flag-bosnia.svg");
    background-repeat: no-repeat;
    background-position: center;
    background-size: 70px 47px;
    margin-left: 136px;
  }
}
@media (min-width: 1440px) {
  .add-plan__todo-flag-bosnia {
    width: 70px;
    height: 47px;
    background-image: url("../assets/img/flag-bosnia.svg");
    background-repeat: no-repeat;
    background-position: 50%, 50%;
    background-size: 70px, 47px;
    margin-top: 5px;
    margin-left: 136px;
  }
}
.add-plan__todo-flag-czech {
  width: 35px;
  height: 24px;
  background-image: url("../assets/img/flag-czech.svg");
  background-repeat: no-repeat;
  background-position: center;
  background-size: 35px 24px;
  margin: 0px 0px 0px 0px;
}
@media (min-width: 768px) {
  .add-plan__todo-flag-czech {
    width: 70px;
    height: 47px;
    background-image: url("../assets/img/flag-czech.svg");
    background-repeat: no-repeat;
    background-position: center;
    background-size: 70px 47px;
    margin-left: 352px;
  }
}
@media (min-width: 1440px) {
  .add-plan__todo-flag-czech {
    width: 70px;
    height: 47px;
    background-image: url("../assets/img/flag-czech.svg");
    background-repeat: no-repeat;
    background-position: center;
    background-size: 70px, 47px;
    margin-left: 352px;
  }
}
.add-plan__line-tablet-up {
  display: none;
}
@media (min-width: 768px) {
  .add-plan__line-tablet-up {
    display: block;
    position: absolute;
    transform: translate(616%, -63%);
    width: 1px;
    height: 71px;
    background-color: #E1E3E9;
  }
}
.add-plan__line-tablet-down {
  display: none;
}
@media (min-width: 768px) {
  .add-plan__line-tablet-down {
    display: block;
    position: absolute;
    transform: translate(523%, 176%);
    width: 1px;
    height: 71px;
    background-color: #E1E3E9;
  }
}
.add-plan__line-tablet-down-last {
  display: none;
}
@media (min-width: 768px) {
  .add-plan__line-tablet-down-last {
    display: block;
    position: absolute;
    transform: translate(36898%, 63%);
    width: 1px;
    height: 46px;
    background-color: #E1E3E9;
  }
}
@media (min-width: 1440px) {
  .add-plan__line-tablet-down-last {
    display: block;
    position: absolute;
    transform: translate(74863%, 63%);
    width: 1px;
    height: 46px;
    background-color: #E1E3E9;
  }
}
.add-plan__arrow-down {
  display: block;
  position: absolute;
  transform: translate(-58%, 191%);
  width: 15px;
  height: 15px;
  background-image: url(../assets/img/arrow-1.svg);
  background-repeat: no-repeat;
  background-position: center;
  border: solid 1px transparent;
}
@media (min-width: 768px) {
  .add-plan__arrow-down {
    display: none;
  }
}
@media (min-width: 1440px) {
  .add-plan__arrow-down {
    display: none;
  }
}
.add-plan__arrow-down-three {
  display: block;
  position: absolute;
  transform: translate(931%, 193%);
  width: 15px;
  height: 15px;
  background-image: url(../assets/img/arrow-1.svg);
  background-repeat: no-repeat;
  background-position: center;
  border: solid 1px transparent;
}
@media (min-width: 768px) {
  .add-plan__arrow-down-three {
    display: none;
  }
}
@media (min-width: 1440px) {
  .add-plan__arrow-down-three {
    display: none;
  }
}
::placeholder {
  color: #1D2E5B;
}
.directions {
  min-width: 100%;
  width: 100%;
  background-color: #EDEFF6;
}
.directions__container {
  position: relative;
  z-index: 8;
  display: flex;
  flex-direction: column;
  min-width: 318px;
  width: 318px;
  min-height: 915px;
  background-color: #EDEFF6;
  margin-top: -20px;
  margin-left: auto;
  margin-right: auto;
  padding-top: 97px;
  border-bottom-left-radius: 30px;
  border-bottom-right-radius: 30px;
  background-image: none;
}
@media (min-width: 768px) {
  .directions__container {
    margin-top: -50px;
    margin-left: auto;
    margin-right: auto;
    min-width: 766px;
    width: 766px;
    min-height: 1046px;
    border-bottom-left-radius: 60px;
    border-bottom-right-radius: 60px;
    background-image: url(../assets/img/flags-back@1x.png);
    background-repeat: no-repeat;
    background-position: 440px 128px;
    background-size: 288px 574px;
  }
}
@media (min-width: 768px) and (min-resolution: 2dppx) {
  .directions__container {
    background-image: url(../assets/img/flags-back@2x.png);
  }
}
@media (min-width: 1440px) {
  .directions__container {
    display: grid;
    grid-template-columns: 1fr 1fr;
    grid-template-rows: 1fr 1fr 1fr;
    min-width: 1438px;
    width: 1438px;
    min-height: 800px;
    padding: 0px 0px 0px 0px;
    margin: -50px auto 0px auto;
    background-image: url(../assets/img/flags-back@1x.png);
    background-repeat: no-repeat;
    background-position: 1093px 138px;
    background-size: 288px 574px;
  }
}
@media (min-width: 1440px) and (min-resolution: 2dppx) {
  .directions__container {
    background-image: url(../assets/img/flags-back@2x.png);
  }
}
.directions__title {
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 24px;
  line-height: 20px;
  color: #FF8D30;
  margin-top: -6px;
  margin-left: 50px;
}
@media (min-width: 768px) {
  .directions__title {
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: bold;
    font-size: 45px;
    line-height: 45px;
    color: #FF8D30;
    margin-top: 22px;
    margin-bottom: 0px;
    margin-left: 73px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .directions__title {
    grid-column-start: 2;
    grid-row-start: 1;
    grid-row-end: 3;
    font-style: normal;
    font-weight: bold;
    font-size: 45px;
    line-height: 45px;
    padding: 0px 0px 0px 0px;
    margin: 212px 0px 0px 142px;
  }
}
.directions__slogan {
  display: inline-block;
  text-align: left;
  width: 200px;
  align-self: flex-start;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: 300;
  font-size: 16px;
  line-height: 22px;
  color: #444444;
  margin-top: 2px;
  margin-bottom: 60px;
  margin-left: 49px;
}
@media (min-width: 768px) {
  .directions__slogan {
    display: inline-block;
    width: 350px;
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: 300;
    font-size: 28px;
    line-height: 33px;
    margin-top: 59px;
    margin-bottom: 0px;
    margin-left: 74px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .directions__slogan {
    grid-column-start: 2;
    grid-row-start: 2;
    width: 345px;
    height: 165px;
    font-style: normal;
    font-weight: 300;
    font-size: 28px;
    line-height: 33px;
    padding: 0px 0px 0px 0px;
    margin: 50px 0px 0px 144px;
  }
}
.directions__country-list {
  width: 270px;
  margin: 0 auto;
  border: solid 1px transparent;
}
@media (min-width: 768px) {
  .directions__country-list {
    width: auto;
    margin-top: 92px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .directions__country-list {
    grid-column-start: 1;
    grid-row-start: 1;
    grid-row-end: 4;
    padding: 0px 0px 0px 0px;
    margin: 233px 0px 0px 36px;
  }
}
.directions__country-item {
  list-style: none;
  box-sizing: border-box;
}
@media (min-width: 768px) {
  .directions__country-item {
    display: grid;
    grid-template-columns: 2fr 1fr;
    grid-template-rows: 1fr;
    width: 616px;
    min-height: 140px;
    margin-top: 12px;
    margin-bottom: 0px;
    margin-left: auto;
    margin-right: auto;
    box-sizing: border-box;
  }
}
@media (min-width: 1440px) {
  .directions__country-item {
    display: grid;
    grid-template-columns: 2fr 1fr;
    grid-template-rows: 1fr;
    width: 561px;
    height: 142px;
    padding: 0px 0px 0px 0px;
    margin: -24px 0px 33px 94px;
    box-sizing: border-box;
  }
}
.directions__country-picture {
  position: relative;
  z-index: 1;
}
@media (min-width: 768px) {
  .directions__country-picture {
    width: auto;
    height: 140px;
    grid-column-start: 1;
    grid-column-end: 3;
    grid-row-start: 1;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .directions__country-picture {
    grid-column-start: 1;
    grid-column-end: 3;
    grid-row-start: 1;
    padding: 0px 0px 0px 0px;
    margin: 0px 0px 0px 0px;
    width: auto;
    height: 137px;
  }
}
.directions__image {
  width: 270px;
  height: 110px;
  border-top-left-radius: 10px;
  border-top-right-radius: 10px;
}
@media (min-width: 768px) {
  .directions__image {
    width: 186px;
    height: 140px;
    margin-top: 2px;
    margin-bottom: 0px;
    margin-left: 431px;
    margin-right: 0px;
    border-top-right-radius: 20px;
    border-bottom-right-radius: 20px;
    border-top-left-radius: 0px;
    border-bottom-left-radius: 0px;
  }
}
@media (min-width: 1440px) {
  .directions__image {
    width: 187px;
    height: 140px;
    padding: 0px 0px 0px 0px;
    margin-top: 2px;
    margin-bottom: 0px;
    margin-left: 373px;
    margin-right: 0px;
    border-top-right-radius: 20px;
    border-bottom-right-radius: 20px;
    border-top-left-radius: 0px;
    border-bottom-left-radius: 0px;
  }
}
.directions__country-wrap {
  display: grid;
  grid-template-columns: 1fr 1fr;
  grid-template-rows: 1fr 1fr;
  width: 270px;
  min-height: 89px;
  border: solid 1px transparent;
  background-color: #FFFFFF;
  border-radius: 10px;
  margin-top: -15px;
  margin-bottom: 7px;
  position: relative;
  z-index: 2;
}
@media (min-width: 768px) {
  .directions__country-wrap {
    width: 427px;
    min-height: 89px;
    grid-column-start: 1;
    grid-row-start: 1;
    margin: 0px 0px 0px 0px;
    border-top-right-radius: 0px;
    border-bottom-right-radius: 0px;
    border-top-left-radius: 15px;
    border-bottom-left-radius: 15px;
  }
}
@media (min-width: 1440px) {
  .directions__country-wrap {
    grid-column-start: 1;
    grid-column-end: 2;
    grid-row-start: 1;
    width: 373px;
    height: 137px;
    padding: 0px 0px 0px 0px;
    margin: 0px 0px 0px 0px;
    border-top-right-radius: 0px;
    border-bottom-right-radius: 0px;
    border-top-left-radius: 15px;
    border-bottom-left-radius: 15px;
  }
}
.directions__button {
  display: block;
  width: 270px;
  height: 62px;
  margin: 0 auto;
  margin-top: 17px;
  background-color: #FFD74B;
  border-radius: 10px;
  background-image: url("../assets/img/icon-btn-triangle.svg");
  background-repeat: no-repeat;
  background-position: 92% 50%;
  box-sizing: border-box;
}
@media (min-width: 768px) {
  .directions__button {
    width: 616px;
    height: 82px;
    margin-top: 43px;
    margin-bottom: 0px;
    margin-left: 73px;
    margin-right: 0px;
    border-radius: 20px;
    background-position: 95% 50%;
    padding: 2px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .directions__button {
    grid-column-start: 2;
    grid-row-start: 3;
    width: 275px;
    height: 80px;
    border-radius: 20px;
    padding: 0px 0px 0px 0px;
    margin: 49px 0px 0px 144px;
    background-position: 87% 50%;
  }
}
.directions__btn-text {
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 18px;
  line-height: 63px;
  color: #1D2E5B;
  padding-left: 24px;
  padding-right: 0px;
}
@media (min-width: 768px) {
  .directions__btn-text {
    font-style: normal;
    font-weight: bold;
    font-size: 24px;
    line-height: 78px;
    padding: 0px 0px 0px 0px;
    margin: 0px 0px 0px 33px;
  }
}
@media (min-width: 1440px) {
  .directions__btn-text {
    font-style: normal;
    font-weight: bold;
    font-size: 24px;
    line-height: 78px;
    padding: 0px 0px 0px 0px;
    margin: 0px 0px 0px 33px;
  }
}
.directions__button:hover {
  background-color: #FFBD30;
}
.directions__button:active,
.directions__btn-text:active {
  background-color: #FFBD30;
  color: rgba(0, 0, 0, 0.3);
}
.directions__country-title {
  grid-column-start: 1;
  grid-row-start: 1;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 21px;
  line-height: 21px;
  color: #000000;
  margin-top: 24px;
  margin-bottom: 0px;
  margin-left: 25px;
  margin-right: 0px;
}
@media (min-width: 768px) {
  .directions__country-title {
    grid-column-start: 1;
    grid-row-start: 1;
    font-style: normal;
    font-weight: bold;
    font-size: 24px;
    line-height: 24px;
    padding: 0px 0px 0px 0px;
    margin: 27px 0px 0px 26px;
  }
}
@media (min-width: 1440px) {
  .directions__country-title {
    grid-column-start: 1;
    grid-row-start: 1;
    font-style: normal;
    font-weight: bold;
    font-size: 24px;
    line-height: 24px;
    padding: 0px 0px 0px 0px;
    margin: 21px 0px 0px 30px;
  }
}
.directions__quote {
  grid-column-start: 1;
  grid-column-end: 3;
  grid-row-start: 2;
  display: inline-block;
  width: 140px;
  height: auto;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: 500;
  font-size: 16px;
  line-height: 18px;
  color: #444444;
  opacity: 0.3;
  margin-top: 5px;
  margin-bottom: 0px;
  margin-left: 25px;
  margin-right: 0px;
}
@media (min-width: 768px) {
  .directions__quote {
    grid-column-start: 1;
    grid-column-end: 3;
    grid-row-start: 1;
    grid-row-end: 3;
    display: inline-block;
    width: 225px;
    height: auto;
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 20px;
    padding: 0px 0px 0px 0px;
    margin: 56px 0px 0px 27px;
  }
}
@media (min-width: 1440px) {
  .directions__quote {
    grid-column-start: 1;
    grid-column-end: 3;
    grid-row-start: 1;
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 20px;
    padding: 0px 0px 0px 0px;
    margin: 49px 0px 0px 32px;
  }
}
.directions__rating {
  grid-column-start: 2;
  grid-row-start: 1;
  grid-row-end: 3;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: 500;
  font-size: 16px;
  line-height: 20px;
  color: #161C35;
  opacity: 0.3;
  margin-top: 28px;
  margin-bottom: 0px;
  margin-left: 68px;
  margin-right: 0px;
}
@media (min-width: 768px) {
  .directions__rating {
    grid-column-start: 1;
    grid-column-end: 2;
    grid-row-start: 2;
    grid-row-end: 3;
    display: inline-block;
    width: 84px;
    height: 24px;
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 20px;
    padding: 0px 0px 0px 0px;
    margin: 29px 0px 0px 26px;
    background-image: url(../assets/img/user.svg);
    background-repeat: no-repeat;
    background-position: 3%, 50%;
    background-size: 19px 22px;
    text-align: end;
  }
}
@media (min-width: 1440px) {
  .directions__rating {
    grid-column-start: 1;
    grid-column-end: 2;
    grid-row-start: 2;
    grid-row-end: 3;
    display: inline-block;
    width: 84px;
    height: 24px;
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 20px;
    padding: 0px 0px 0px 0px;
    margin: 26px 0px 0px 30px;
    background-image: url("../assets/img/user.svg");
    background-repeat: no-repeat;
    background-position: 14%, 50%;
    background-size: 24px 24px;
    text-align: end;
  }
}
@media (min-width: 768px) {
  .directions__rating-last {
    padding: 0px 0px 0px 0px;
    margin: 25px 0px 0px 13px;
  }
}
.directions__flag-icon {
  grid-column-start: 1;
  grid-row-start: 1;
  margin-top: -12px;
  margin-bottom: 0px;
  margin-left: 25px;
  margin-right: 0px;
}
@media (min-width: 768px) {
  .directions__flag-icon {
    grid-column-start: 2;
    grid-row-start: 1;
    grid-row-end: 3;
    width: 70px;
    height: 47px;
    padding: 0px 0px 0px 0px;
    margin: 18px 0px 0px 182px;
  }
}
@media (min-width: 1440px) {
  .directions__flag-icon {
    grid-column-start: 2;
    grid-row-start: 1;
    grid-row-end: 3;
    width: 70px;
    height: 47px;
    padding: 0px 0px 0px 0px;
    margin: 22px 0px 0px 150px;
  }
}
.filter-toggle {
  min-width: 100%;
  width: 100%;
  background-color: #E5E5E5;
}
.filter-toggle__container {
  display: flex;
  flex-direction: column;
  justify-content: space-around;
  margin: -20px auto 0px auto;
  min-height: 73px;
  min-width: 320px;
  width: 320px;
  background-color: #E5E5E5;
  border-bottom-right-radius: 20px;
  border-bottom-left-radius: 20px;
  position: relative;
  z-index: 9;
}
@media (min-width: 768px) {
  .filter-toggle__container {
    min-width: 768px;
    width: 768px;
    min-height: 182px;
    border-bottom-left-radius: 58px;
    border-bottom-right-radius: 58px;
    position: relative;
    z-index: 9;
    margin: -40px auto 0px auto;
  }
}
@media (min-width: 1440px) {
  .filter-toggle__container {
    min-width: 1438px;
    width: 1438px;
    margin: -50px auto 0px auto;
    padding: 0px 0px 0px 0px;
  }
}
.filter-toggle__btn-wrap {
  display: flex;
  justify-content: space-between;
}
@media (min-width: 768px) {
  .filter-toggle__btn-wrap {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-top: 39px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
    padding-left: 72px;
    padding-right: 52px;
  }
}
@media (min-width: 1440px) {
  .filter-toggle__btn-wrap {
    display: flex;
    flex-direction: row;
    justify-content: start;
    align-items: center;
    margin: 0px 0px 0px 0px;
    padding: 0px 0px 0px 0px;
  }
}
.filter-toggle__title {
  font-style: normal;
  font-weight: bold;
  font-size: 16px;
  line-height: 18px;
  text-transform: uppercase;
  color: #192144;
  padding-top: 15px;
  margin-top: 26px;
  margin-left: -12px;
}
@media (min-width: 768px) {
  .filter-toggle__title {
    display: none;
  }
}
@media (min-width: 1440px) {
  .filter-toggle__title {
    display: inline-block;
    font-style: normal;
    font-weight: bold;
    font-size: 20px;
    line-height: 20px;
    margin: 57px 0px 0px 21px;
    padding: 0px 0px 0px 0px;
  }
}
.filter-toggle__europe {
  display: none;
}
@media (min-width: 768px) {
  .filter-toggle__europe {
    display: inline-block;
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: bold;
    font-size: 20px;
    line-height: 20px;
    text-transform: uppercase;
    color: #192144;
    cursor: pointer;
  }
}
@media (min-width: 1440px) {
  .filter-toggle__europe {
    display: inline-block;
    font-style: normal;
    font-weight: bold;
    font-size: 20px;
    line-height: 20px;
    margin: 57px 0px 0px 30px;
    padding: 0px 0px 0px 0px;
  }
}
.filter-toggle__asia {
  display: none;
}
@media (min-width: 768px) {
  .filter-toggle__asia {
    display: inline-block;
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: bold;
    font-size: 20px;
    line-height: 20px;
    text-transform: uppercase;
    color: #192144;
    opacity: 0.3;
    cursor: pointer;
  }
}
@media (min-width: 1440px) {
  .filter-toggle__asia {
    display: inline-block;
    font-style: normal;
    font-weight: bold;
    font-size: 20px;
    line-height: 20px;
    margin: 57px 0px 0px 28px;
    padding: 0px 0px 0px 0px;
  }
}
.filter-toggle__america {
  display: none;
}
@media (min-width: 768px) {
  .filter-toggle__america {
    display: inline-block;
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: bold;
    font-size: 20px;
    line-height: 20px;
    text-transform: uppercase;
    color: #192144;
    opacity: 0.3;
    cursor: pointer;
  }
}
@media (min-width: 1440px) {
  .filter-toggle__america {
    display: inline-block;
    font-style: normal;
    font-weight: bold;
    font-size: 20px;
    line-height: 20px;
    margin: 57px 0px 0px 28px;
    padding: 0px 0px 0px 0px;
  }
}
.filter-toggle__islands {
  display: none;
}
@media (min-width: 768px) {
  .filter-toggle__islands {
    display: inline-block;
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: bold;
    font-size: 20px;
    line-height: 20px;
    text-transform: uppercase;
    color: #192144;
    opacity: 0.3;
    cursor: pointer;
  }
}
@media (min-width: 1440px) {
  .filter-toggle__islands {
    display: inline-block;
    font-style: normal;
    font-weight: bold;
    font-size: 20px;
    line-height: 20px;
    margin: 57px 0px 0px 30px;
    padding: 0px 0px 0px 0px;
  }
}
.filter-toggle__btn-more {
  display: none;
}
@media (min-width: 768px) {
  .filter-toggle__btn-more {
    display: inline-block;
    width: 217px;
    height: 23px;
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: bold;
    font-size: 20px;
    line-height: 20px;
    text-transform: uppercase;
    color: #192144;
  }
}
.filter-toggle__button {
  width: 19px;
  height: 5px;
  background-image: url(../assets/img/filter-toggle-expand.svg);
  background-repeat: no-repeat;
  border: none;
  align-self: center;
  margin-top: 25px;
  margin-right: 27px;
}
@media (min-width: 768px) {
  .filter-toggle__button {
    display: flex;
    justify-content: flex-start;
    align-items: center;
    width: 250px;
    height: 45px;
    background-image: url(../assets/img/filter-toggle-expand-tablet.svg);
    background-repeat: no-repeat;
    background-position: 90%, 50%;
    background-color: transparent;
    margin-top: 3px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
    padding: 0px;
  }
}
@media (min-width: 1440px) {
  .filter-toggle__button {
    display: none;
  }
}
.filter-toggle__icon {
  width: 15px;
  height: 10px;
  background-image: url(../assets/img/filter-toggle-icon.svg);
  background-repeat: no-repeat;
  align-self: center;
  margin-top: 25px;
  margin-left: 25px;
}
@media (min-width: 768px) {
  .filter-toggle__icon {
    display: none;
  }
}
@media (min-width: 1440px) {
  .filter-toggle__icon {
    display: block;
    width: 24px;
    height: 16px;
    background-image: url(../assets/img/filter-toggle-icon-desktop.svg);
    background-size: 23px, 15px;
    margin: 58px 0px 0px 78px;
    padding: 0px 0px 0px 0px;
  }
}
.filter-toggle__btn-hide {
  display: none;
}
@media (min-width: 768px) {
  .filter-toggle__btn-hide {
    display: none;
  }
}
@media (min-width: 1440px) {
  .filter-toggle__btn-hide {
    display: block;
    width: 270px;
    height: 41px;
    background-color: transparent;
    background-image: url(../assets/img/menu-close.svg);
    background-repeat: no-repeat;
    background-position: 97%, 50%;
    background-size: 19px, 19px;
    border: none;
    margin: 55px 0px 0px 279px;
    padding: 0px 0px 0px 0px;
  }
}
.filter-toggle__hide-text {
  display: none;
}
@media (min-width: 768px) {
  .filter-toggle__hide-text {
    display: none;
  }
}
@media (min-width: 1440px) {
  .filter-toggle__hide-text {
    display: block;
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: bold;
    font-size: 20px;
    line-height: 20px;
    text-transform: uppercase;
    color: #192144;
  }
}
.guide {
  min-width: 100%;
  width: 100%;
  background-color: #192144;
}
@media (min-width: 1440px) {
  .guide {
    background-color: #161C35;
  }
}
.guide__container {
  display: flex;
  flex-direction: column;
  min-width: 318px;
  width: 318px;
  min-height: 555px;
  background-color: #161C35;
  background-image: none;
  color: #FFFFFF;
  border: solid 1px transparent;
  margin-top: -92px;
  margin-left: auto;
  margin-right: auto;
}
@media (min-width: 768px) {
  .guide__container {
    min-width: 766px;
    width: 766px;
    background-image: url(../assets/img/traveller-illustration-tablet@1x.png), url(../assets/img/globe-back-tablet@1x.jpg);
    background-repeat: no-repeat, no-repeat;
    background-position: 283px -7px, -356px -29px;
    background-color: #182044;
    margin-top: -160px;
    margin-left: auto;
    margin-right: auto;
  }
}
@media (min-width: 768px) and (min-resolution: 2dppx) {
  .guide__container {
    background-image: url(../assets/img/traveller-illustration-tablet@2x.png), url(../assets/img/globe-back-tablet@2x.jpg);
    background-repeat: no-repeat, no-repeat;
    background-position: 283px -7px, -356px -29px;
    background-size: 372px 451px, 768px 612px;
  }
}
@media (min-width: 1440px) {
  .guide__container {
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    min-width: 1438px;
    width: 1438px;
    min-height: 648px;
    margin-top: -648px;
    margin-left: auto;
    margin-right: auto;
    background-image: none;
    background-color: transparent;
    position: relative;
    z-index: 10;
  }
}
.guide__list {
  display: flex;
  flex-direction: column;
  align-content: stretch;
  width: 270px;
  margin: 0 auto;
  list-style: none;
  color: #161C35;
  border: solid 1px transparent;
}
@media (min-width: 768px) {
  .guide__list {
    display: grid;
    grid-template-columns: 1fr 1fr;
    grid-template-rows: 1fr 1fr;
    width: 689px;
    height: 280px;
    margin-top: 212px;
    margin-bottom: 0px;
    margin-right: auto;
    margin-left: auto;
  }
}
@media (min-width: 1440px) {
  .guide__list {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr 1fr;
    grid-template-rows: 1fr;
    width: 1330px;
    height: 107px;
    margin-top: 116px;
    margin-bottom: 0px;
    margin-right: auto;
    margin-left: auto;
  }
}
.guide__item {
  display: flex;
  justify-content: space-between;
  border-radius: 10px;
  padding-top: 20px;
  padding-left: 24px;
  padding-right: 20px;
  border: solid 1px transparent;
}
@media (min-width: 768px) {
  .guide__item {
    display: flex;
    flex-direction: column;
    justify-content: start;
    align-content: flex-start;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-right: 0px;
    margin-left: 0px;
    border-radius: 0px;
  }
}
@media (min-width: 1440px) {
  .guide__item {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    width: 375px;
    height: 107px;
    border-radius: 20px;
  }
}
.guide__item:nth-child(1) {
  height: 87px;
  background-color: #FF8D30;
}
@media (min-width: 768px) {
  .guide__item:nth-child(1) {
    grid-column-start: 1;
    grid-row-start: 1;
    width: 365px;
    height: auto;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-right: 0px;
    margin-left: 0px;
    border-top-left-radius: 20px;
  }
}
@media (min-width: 1440px) {
  .guide__item:nth-child(1) {
    grid-column-start: 1;
    grid-row-start: 1;
    width: 376px;
    height: auto;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-right: 0px;
    margin-left: 5px;
    padding: 0px 0px 0px 4px;
    box-sizing: border-box;
  }
}
@media (min-width: 1440px) {
  .guide__item:nth-child(1) .guide__number {
    margin-top: 26px;
    margin-bottom: 0px;
    margin-right: 95px;
    margin-left: 0px;
    padding: 0px 0px 0px 0px;
  }
}
.guide__item:nth-child(2) {
  height: 88px;
  margin-top: -30px;
  background-color: #FFA530;
}
@media (min-width: 768px) {
  .guide__item:nth-child(2) {
    grid-column-start: 2;
    grid-row-start: 1;
    width: 297px;
    height: auto;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-right: 0px;
    margin-left: -67px;
    border-top-left-radius: 20px;
    border-top-right-radius: 20px;
  }
}
@media (min-width: 1440px) {
  .guide__item:nth-child(2) {
    grid-column-start: 2;
    grid-row-start: 1;
    width: 375px;
    height: auto;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-right: 0px;
    margin-left: -62px;
    padding: 0px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .guide__item:nth-child(2) .guide__number {
    margin-top: 26px;
    margin-bottom: 0px;
    margin-right: 62px;
    margin-left: 0px;
    padding: 0px 0px 0px 0px;
  }
}
.guide__item:nth-child(3) {
  height: 88px;
  margin-top: -30px;
  background-color: #FFBD30;
}
@media (min-width: 768px) {
  .guide__item:nth-child(3) {
    grid-column-start: 1;
    grid-row-start: 2;
    width: 365px;
    height: auto;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-right: 0px;
    margin-left: 0px;
    border-bottom-left-radius: 20px;
  }
}
@media (min-width: 1440px) {
  .guide__item:nth-child(3) {
    grid-column-start: 3;
    grid-row-start: 1;
    width: 375px;
    height: auto;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-right: 0px;
    margin-left: -32px;
    padding: 0px 0px 0px 3px;
    box-sizing: border-box;
  }
}
@media (min-width: 1440px) {
  .guide__item:nth-child(3) .guide__number {
    margin-top: 26px;
    margin-bottom: 0px;
    margin-right: 62px;
    margin-left: 0px;
    padding: 0px 0px 0px 0px;
  }
}
.guide__item:last-child {
  height: 59px;
  margin-top: -30px;
  background-color: #FFD74B;
}
@media (min-width: 768px) {
  .guide__item:last-child {
    grid-column-start: 2;
    grid-row-start: 2;
    width: 297px;
    height: auto;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-right: 0px;
    margin-left: -67px;
    border-bottom-left-radius: 20px;
    border-bottom-right-radius: 20px;
  }
}
@media (min-width: 1440px) {
  .guide__item:last-child {
    grid-column-start: 4;
    grid-row-start: 1;
    width: 313px;
    height: 105px;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-right: 0px;
    margin-left: -28px;
    padding: 0px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .guide__item:last-child .guide__number {
    margin-top: 26px;
    margin-bottom: 0px;
    margin-right: 31px;
    margin-left: 0px;
    padding: 0px 0px 0px 0px;
  }
}
.guide__item:last-child > .guide__text,
.guide__item:last-child > .guide__number {
  display: block;
  height: 40px;
}
.guide__text {
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 18px;
  line-height: 18px;
  color: #161C35;
  margin-bottom: 0px;
  padding-bottom: 0px;
}
@media (min-width: 768px) {
  .guide__text {
    font-style: normal;
    font-weight: bold;
    font-size: 24px;
    line-height: 24px;
    margin-top: 7px;
    margin-bottom: 0px;
    margin-right: 0px;
    margin-left: 7px;
  }
}
@media (min-width: 1440px) {
  .guide__text {
    font-style: normal;
    font-weight: bold;
    font-size: 24px;
    line-height: 24px;
    margin-top: 26px;
    margin-bottom: 0px;
    margin-right: 0px;
    margin-left: 30px;
  }
}
.guide__number {
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 18px;
  line-height: 18px;
  color: #FFFFFF;
  margin-bottom: 0px;
  padding-bottom: 0px;
}
@media (min-width: 768px) {
  .guide__number {
    font-style: normal;
    font-weight: bold;
    font-size: 30px;
    line-height: 30px;
    margin-top: 11px;
    margin-bottom: 0px;
    margin-right: 0px;
    margin-left: 8px;
  }
}
@media (min-width: 1440px) {
  .guide__number {
    font-style: normal;
    font-weight: bold;
    font-size: 24px;
    line-height: 24px;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-right: 0px;
    margin-left: 0px;
  }
}
.guide__quote {
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: 300;
  font-size: 16px;
  margin-left: 49px;
  margin-right: 100px;
  margin-top: 45px;
  line-height: 22px;
}
@media (min-width: 768px) {
  .guide__quote {
    display: inline-block;
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: 300;
    font-size: 28px;
    line-height: 33px;
    color: #FFFFFF;
    margin-top: 46px;
    margin-bottom: 0px;
    margin-left: 69px;
    margin-right: 400px;
  }
}
@media (min-width: 1440px) {
  .guide__quote {
    display: inline-block;
    width: 264px;
    height: 64px;
    align-self: flex-end;
    font-style: normal;
    font-weight: 300;
    font-size: 28px;
    line-height: 32px;
    margin-top: 114px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 80px;
  }
}
.guide__slogan {
  display: block;
  height: auto;
  margin-top: 2px;
  margin-bottom: 29px;
  margin-left: 49px;
  margin-right: 90px;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: 500;
  font-size: 17px;
  line-height: 22px;
}
@media (min-width: 768px) {
  .guide__slogan {
    display: inline-block;
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: bold;
    font-size: 21px;
    line-height: 25px;
    color: #FFFFFF;
    margin-top: 45px;
    margin-bottom: 0px;
    margin-left: 69px;
    margin-right: 461px;
  }
}
@media (min-width: 1440px) {
  .guide__slogan {
    display: inline-block;
    width: 246px;
    height: 74px;
    align-self: flex-end;
    font-style: normal;
    font-weight: bold;
    font-size: 21px;
    line-height: 24px;
    margin-top: 47px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 98px;
  }
}
.map {
  min-width: 100%;
  width: 100%;
  background-color: #FFD74B;
}
.map__container {
  display: flex;
  flex-direction: column;
  min-width: 318px;
  width: 318px;
  min-height: 226px;
  margin-top: -21px;
  padding-top: 35px;
  padding-left: 25px;
  background-color: #FFD74B;
  border-bottom-left-radius: 30px;
  border-bottom-right-radius: 30px;
  position: relative;
  z-index: 4;
  box-sizing: border-box;
  margin-left: auto;
  margin-right: auto;
}
@media (min-width: 768px) {
  .map__container {
    min-width: 766px;
    width: 766px;
    margin-top: -50px;
    margin-left: auto;
    margin-right: auto;
    min-height: 374px;
    border-bottom-left-radius: 60px;
    border-bottom-right-radius: 60px;
  }
}
@media (min-width: 1440px) {
  .map__container {
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    align-items: center;
    min-width: 1438px;
    width: 1438px;
    min-height: 240px;
    padding: 0px 0px 0px 0px;
    margin-top: -40px;
    margin-bottom: 0px;
    margin-left: auto;
    margin-right: auto;
    position: relative;
    z-index: 4;
  }
}
.map__address {
  display: flex;
  align-items: center;
  justify-content: flex-start;
  width: auto;
  margin-top: 16px;
}
@media (min-width: 768px) {
  .map__address {
    display: flex;
    align-items: center;
    justify-content: flex-start;
    width: auto;
    margin-top: 63px;
    margin-bottom: 0px;
    margin-left: 48px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .map__address {
    width: auto;
    padding: 0px 0px 0px 0px;
    margin-top: 36px;
    margin-bottom: 0px;
    margin-left: 245px;
    margin-right: 0px;
  }
}
.map__icon {
  display: inline-block;
  width: 45px;
  height: 45px;
  border-radius: 50%;
  background-color: #121936;
  background-image: url("../assets/img/icon-location.svg");
  background-repeat: no-repeat;
  background-position: center;
}
@media (min-width: 768px) {
  .map__icon {
    width: 68px;
    height: 68px;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
    background-size: 32px 32px;
  }
}
@media (min-width: 1440px) {
  .map__icon {
    width: 90px;
    height: 90px;
    margin-top: 6px;
    margin-bottom: 0px;
    margin-left: -1px;
    margin-right: 0px;
    background-size: 45px 45px;
  }
}
.map__text {
  display: inline-block;
  width: 143px;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 16px;
  line-height: 22px;
  text-transform: uppercase;
  color: #1D2E5B;
  padding-left: 16px;
  text-align: left;
}
@media (min-width: 768px) {
  .map__text {
    display: inline-block;
    width: 500px;
    font-style: normal;
    font-weight: bold;
    font-size: 28px;
    line-height: 28px;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: 10px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .map__text {
    font-style: normal;
    font-weight: bold;
    font-size: 28px;
    line-height: 28px;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: 14px;
    margin-right: 0px;
  }
}
.map__button {
  width: 270px;
  height: 62px;
  background-color: transparent;
  border: 3px solid #192144;
  box-sizing: border-box;
  border-radius: 10px;
  margin: 34px 0px 0px -1px;
  background-image: url(../assets/img/icon-btn-triangle.svg);
  background-repeat: no-repeat;
  background-position: 92% 50%;
  cursor: pointer;
}
@media (min-width: 768px) {
  .map__button {
    width: 618px;
    height: 80px;
    margin-top: 44px;
    margin-bottom: 0px;
    margin-left: 48px;
    margin-right: 0px;
    border-radius: 20px;
    background-position: 569px 32px;
  }
}
@media (min-width: 1440px) {
  .map__button {
    width: 324px;
    height: 80px;
    padding: 0px 0px 0px 0px;
    margin-top: 40px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 94px;
    border-radius: 20px;
    background-position: 90% 50%;
  }
}
.map__button:hover {
  background-color: #192144;
  color: #FFFFFF;
}
.map__button:active {
  background-color: #192144;
  color: #FFFFFF;
}
.map__btn-text {
  font-family: "Blogger Sans";
  font-style: normal;
  font-weight: bold;
  font-size: 18px;
  line-height: 18px;
  color: #1D2E5B;
  margin-left: -59px;
}
@media (min-width: 768px) {
  .map__btn-text {
    font-style: normal;
    font-weight: bold;
    font-size: 24px;
    line-height: 24px;
    padding: 0px 0px 0px 0px;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: -324px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .map__btn-text {
    font-style: normal;
    font-weight: bold;
    font-size: 24px;
    line-height: 24px;
    padding: 0px 0px 0px 0px;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 27px;
  }
}
.map__btn-text:hover {
  color: #FFFFFF;
}
.map__btn-text:active {
  color: #FFFFFF;
  opacity: 0.3;
}
.my-profile {
  min-width: 100%;
  width: 100%;
  background-color: #E5E5E5;
}
.my-profile__container {
  display: flex;
  flex-direction: column;
  min-width: 318px;
  width: 318px;
  min-height: 436px;
  justify-content: space-between;
  align-items: center;
  background-color: #E5E5E5;
  border: solid 1px transparent;
  margin-top: -15px;
  margin-left: auto;
  margin-right: auto;
  padding-top: 38px;
  position: relative;
  z-index: 9;
}
@media (min-width: 768px) {
  .my-profile__container {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr 1fr;
    grid-template-rows: 1fr 1fr 1fr;
    min-width: 766px;
    width: 766px;
    min-height: 500px;
    margin-top: -45px;
    margin-bottom: 0px;
    margin-left: auto;
    margin-right: auto;
    padding-top: 45px;
    padding-bottom: 0px;
    padding-left: 0px;
    padding-right: 0px;
    position: relative;
    z-index: 9;
  }
}
@media (min-width: 1440px) {
  .my-profile__container {
    display: grid;
    grid-template-columns: 2fr 1fr;
    grid-template-rows: 1fr 1fr;
    min-width: 1438px;
    width: 1438px;
    min-height: 448px;
    padding: 0px 0px 0px 0px;
    margin: -191px auto 0px auto;
    background-color: transparent;
    position: relative;
    z-index: 10;
  }
}
.my-profile__wrapper {
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 236px;
}
@media (min-width: 768px) {
  .my-profile__wrapper {
    grid-column-start: 1;
    grid-column-end: 5;
    grid-row-start: 1;
    grid-row-end: 2;
    width: 624px;
    margin-top: 68px;
    margin-bottom: 0px;
    margin-left: 71px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .my-profile__wrapper {
    grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 1;
    grid-row-end: 3;
    width: 330px;
    height: 190px;
    padding: 0px 0px 0px 0px;
    margin: -261px 0px 0px -5px;
  }
}
.my-profile__level {
  width: 100px;
  height: 100px;
  background-image: url("../assets/img/my-profile-level.svg");
  background-repeat: no-repeat;
  background-position: center;
}
@media (min-width: 768px) {
  .my-profile__level {
    background-image: url("../assets/img/my-profile-level.svg");
    background-repeat: no-repeat;
    background-position: center;
    background-size: 94px;
    margin-top: -7px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .my-profile__level {
    background-image: url("../assets/img/my-profile-level-desktop.svg");
    background-repeat: no-repeat;
    background-position: center;
    background-size: 94px;
    margin-top: -9px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
  }
}
.my-profile__level-number {
  display: block;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 38px;
  line-height: 38px;
  text-align: center;
  color: #161C35;
  margin-top: 11px;
}
.my-profile__level-text {
  display: block;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: normal;
  font-size: 18px;
  line-height: 33px;
  text-align: center;
  color: #444444;
}
.my-profile__avatar {
  margin: 0px 0px 0px 0px;
}
@media (min-width: 768px) {
  .my-profile__avatar {
    margin-top: -11px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 3px;
  }
}
@media (min-width: 1440px) {
  .my-profile__avatar {
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
  }
}
.my-profile__icon {
  width: 100px;
  height: 100px;
  border-radius: 50px;
  margin: 0px 0px 0px 0px;
}
@media (min-width: 768px) {
  .my-profile__icon {
    width: 94px;
    height: 94px;
    border-radius: 5px;
    margin: 0px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .my-profile__icon {
    width: 190px;
    height: 190px;
    border-radius: 0px;
    margin: 0px 0px 0px 0px;
  }
}
.my-profile__button {
  width: 270px;
  height: 40px;
  background-color: #DFE3F0;
  border: none;
  border-radius: 20px;
  margin-top: 16px;
}
@media (min-width: 768px) {
  .my-profile__button {
    grid-column-start: 1;
    grid-column-end: 5;
    grid-row-start: 2;
    grid-row-end: 3;
    width: 618px;
    height: 60px;
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 18px;
    display: flex;
    align-items: center;
    letter-spacing: 0.09em;
    margin-top: -25px;
    margin-bottom: 0px;
    margin-left: auto;
    margin-right: auto;
    padding: 0px 0px 0px 228px;
    box-sizing: border-box;
  }
}
@media (min-width: 1440px) {
  .my-profile__button {
    grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 1;
    grid-row-end: 3;
    width: 190px;
    height: 47px;
    border-radius: 0%;
    margin-top: -22px;
    margin-bottom: 0px;
    margin-left: 136px;
    margin-right: 0px;
    padding: 0px 0px 0px 0px;
  }
}
.my-profile__button:hover {
  background-color: #D1D7E9;
}
.my-profile__button:active {
  background-color: #DFE3F0;
}
.my-profile__btn-text {
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: 500;
  font-size: 20px;
  line-height: 12px;
  text-transform: uppercase;
  color: #161C35;
}
@media (min-width: 768px) {
  .my-profile__btn-text {
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 18px;
    letter-spacing: 0.09em;
  }
}
@media (min-width: 1440px) {
  .my-profile__btn-text {
    display: none;
  }
}
.my-profile__btn-text-desktop {
  display: none;
}
@media (min-width: 768px) {
  .my-profile__btn-text-desktop {
    display: none;
  }
}
@media (min-width: 1440px) {
  .my-profile__btn-text-desktop {
    display: inline-block;
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 18px;
    text-transform: uppercase;
    color: #161C35;
    margin: 0 auto;
  }
}
.my-profile__tags {
  display: block;
  width: 270px;
  min-height: 86px;
  border: solid 1px #444444;
  border-radius: 10px;
  padding: 26px 0px 0px 25px;
  margin-top: 32px;
  box-sizing: border-box;
}
@media (min-width: 768px) {
  .my-profile__tags {
    grid-column-start: 1;
    grid-column-end: 5;
    grid-row-start: 3;
    grid-row-end: 4;
    width: 618px;
    min-height: 95px;
    margin-top: -95px;
    margin-bottom: 0px;
    margin-left: auto;
    margin-right: auto;
    padding: 31px 0px 0px 40px;
    box-sizing: border-box;
  }
}
@media (min-width: 1440px) {
  .my-profile__tags {
    grid-column-start: 1;
    grid-column-end: 2;
    grid-row-start: 2;
    grid-row-end: 3;
    width: 734px;
    height: 94px;
    margin-top: -52px;
    margin-bottom: 0px;
    margin-left: 122px;
    margin-right: 0px;
    padding: 35px 0px 0px 40px;
    box-sizing: border-box;
  }
}
.my-profile__tags:hover {
  color: #444444;
  opacity: 0.6;
}
.my-profile__tags:active {
  color: #444444;
  opacity: 1;
}
.my-profile__tags-text {
  display: block;
  width: 100%;
  height: 100%;
  margin: 0px 0px 0px 0px;
  padding: 0px 0px 0px 0px;
  border: none;
  background-color: transparent;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: 300;
  font-size: 16px;
  line-height: 18px;
  color: #444444;
  opacity: 0.6;
  resize: none;
}
@media (min-width: 768px) {
  .my-profile__tags-text {
    display: inline-block;
    width: 100%;
    height: 100%;
    font-style: normal;
    font-weight: normal;
    font-size: 20px;
    line-height: 22px;
    color: #444444;
    opacity: 0.6;
    margin: 0px 0px 0px 0px;
    padding: 0px 0px 0px 0px;
    border: none;
    background-color: transparent;
    resize: none;
  }
}
@media (min-width: 1440px) {
  .my-profile__tags-text {
    display: inline-block;
    width: 100%;
    height: 100%;
    font-style: normal;
    font-weight: normal;
    font-size: 20px;
    line-height: 22px;
    color: #444444;
    opacity: 0.6;
    margin: 0px 0px 0px 0px;
    padding: 0px 0px 0px 0px;
    border: none;
    background-color: transparent;
    resize: none;
  }
}
textarea {
  outline: none;
}
.my-profile__tags-title {
  display: block;
  width: 68px;
  height: 17px;
  border: solid 1px transparent;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: 700;
  font-size: 16px;
  line-height: 18px;
  text-align: center;
  text-transform: uppercase;
  color: #1D2E5B;
  margin: -39px 74px 18px;
  background-color: #E5E5E5;
}
@media (min-width: 768px) {
  .my-profile__tags-title {
    display: none;
  }
}
@media (min-width: 1440px) {
  .my-profile__tags-title {
    display: none;
  }
}
.my-profile__tags-title-tablet {
  display: none;
}
@media (min-width: 768px) {
  .my-profile__tags-title-tablet {
    display: block;
    width: 100px;
    height: 20px;
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 20px;
    text-align: center;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    color: #161C35;
    margin: 0px auto -10px 218px;
    padding: 0px 0px 0px 0px;
    box-sizing: border-box;
    background-color: #E5E5E5;
  }
}
@media (min-width: 1440px) {
  .my-profile__tags-title-tablet {
    display: block;
    width: 100px;
    height: 20px;
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 20px;
    text-align: center;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    color: #161C35;
    margin: -14px 0px -14px -25px;
    padding: 0px 0px 0px 0px;
    box-sizing: border-box;
    background-color: #E5E5E5;
  }
}
.my-profile__transport {
  display: block;
  margin: auto;
  width: 270px;
  min-height: 61px;
  border: solid 1px #444444;
  border-radius: 10px;
  padding: 0px;
  text-align: center;
  margin-top: 25px;
  padding-top: 1px;
}
@media (min-width: 768px) {
  .my-profile__transport {
    grid-column-start: 2;
    grid-column-end: 4;
    grid-row-start: 1;
    grid-row-end: 2;
    width: 308px;
    min-height: 93px;
    margin-top: 55px;
    margin-bottom: 0px;
    margin-left: auto;
    margin-right: auto;
    box-sizing: border-box;
  }
}
@media (min-width: 1440px) {
  .my-profile__transport {
    grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 2;
    grid-row-end: 3;
    width: 381px;
    height: 94px;
    margin-top: -52px;
    margin-bottom: 0px;
    margin-left: 36px;
    margin-right: 0px;
  }
}
.my-profile__transport-title {
  display: block;
  width: 112px;
  height: 17px;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 16px;
  line-height: 18px;
  text-align: center;
  text-transform: uppercase;
  color: #1D2E5B;
  margin: 0 auto;
  margin-top: -9px;
  background-color: #E5E5E5;
}
@media (min-width: 768px) {
  .my-profile__transport-title {
    display: none;
  }
}
@media (min-width: 1440px) {
  .my-profile__transport-title {
    display: none;
  }
}
.my-profile__transport-title-tablet {
  display: none;
}
@media (min-width: 768px) {
  .my-profile__transport-title-tablet {
    display: block;
    width: 149px;
    height: 20px;
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 21px;
    letter-spacing: 0.08em;
    text-align: center;
    text-transform: uppercase;
    color: #1D2E5B;
    background-color: #E5E5E5;
    margin-top: 14px;
    margin-bottom: -41px;
    margin-left: 78px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .my-profile__transport-title-tablet {
    display: block;
    width: 149px;
    height: 20px;
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 21px;
    letter-spacing: 0.08em;
    text-align: center;
    text-transform: uppercase;
    color: #1D2E5B;
    background-color: #E5E5E5;
    margin-top: 15px;
    margin-bottom: -41px;
    margin-left: 117px;
    margin-right: 0px;
  }
}
.my-profile__transport-plane {
  width: 32px;
  height: 32px;
  border-radius: 50px;
  background-color: #FFFFFF;
  background-image: url(../assets/img/plane.svg);
  background-size: 15px;
  background-repeat: no-repeat;
  background-position: center;
  margin: 5px 0px 0px -2px;
  border: none;
}
@media (min-width: 768px) {
  .my-profile__transport-plane {
    width: 44px;
    height: 44px;
    margin: 22px 0px 0px -8px;
    padding: 0px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .my-profile__transport-plane {
    width: 44px;
    height: 44px;
    margin: 22px 0px 0px 10px;
    padding: 0px 0px 0px 0px;
  }
}
.my-profile__transport-bus {
  width: 32px;
  height: 32px;
  border-radius: 50%;
  background-color: #FFFFFF;
  background-image: url("../assets/img/transport-bus.svg");
  background-repeat: no-repeat;
  background-position: center;
  margin: 0px 0px 0px -5px;
  border: none;
}
@media (min-width: 768px) {
  .my-profile__transport-bus {
    width: 44px;
    height: 44px;
    margin: 0px 0px 0px -7px;
    padding: 0px 0px 0px 0px;
    background-size: 24px 23px;
  }
}
@media (min-width: 1440px) {
  .my-profile__transport-bus {
    width: 44px;
    height: 44px;
    margin: 0px 0px 0px -7px;
    padding: 0px 0px 0px 0px;
    background-size: 26px;
  }
}
.my-profile__transport-bike {
  width: 32px;
  height: 32px;
  border-radius: 50%;
  background-color: #FFFFFF;
  background-image: url("../assets/img/transport-bike.svg");
  background-repeat: no-repeat;
  background-position: center;
  margin: 0px 0px 0px -5px;
  border: none;
}
@media (min-width: 768px) {
  .my-profile__transport-bike {
    width: 44px;
    height: 44px;
    margin: 0px 0px 0px -7px;
    padding: 0px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .my-profile__transport-bike {
    width: 44px;
    height: 44px;
    margin: 0px 0px 0px -7px;
    padding: 0px 0px 0px 0px;
  }
}
.my-profile__transport-run {
  width: 32px;
  height: 32px;
  border-radius: 50%;
  background-color: #FFFFFF;
  background-image: url("../assets/img/transport-run.svg");
  background-repeat: no-repeat;
  background-position: center;
  margin: 0px 0px 0px -5px;
  border: none;
}
@media (min-width: 768px) {
  .my-profile__transport-run {
    width: 44px;
    height: 44px;
    margin: 7px 0px 0px -6px;
    padding: 0px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .my-profile__transport-run {
    width: 44px;
    height: 44px;
    margin: 7px 0px 0px -6px;
    padding: 0px 0px 0px 0px;
  }
}
.text-hidden {
  font-size: 0px;
}
@media (min-width: 320px) {
  .page-body {
    width: 100%;
    max-width: 100%;
    min-width: 318px;
    min-height: 100%;
    margin: 0 auto;
    padding: 0;
    font-family: "Blogger Sans", "Arial", sans-serif;
  }
}
@media (min-width: 768px) {
  .page-body {
    width: 100%;
    max-width: 100%;
    min-width: 766px;
    min-height: 100%;
    margin: 0 auto;
    padding: 0;
    font-family: "Blogger Sans", "Arial", sans-serif;
  }
}
@media (min-width: 1440px) {
  .page-body {
    width: 100%;
    max-width: 100%;
    min-width: 1438px;
    min-height: 100%;
    margin: 0 auto;
    padding: 0;
    font-family: "Blogger Sans", "Arial", sans-serif;
  }
}
.page-footer {
  min-width: 100%;
  width: 100%;
  background-color: #FFFFFF;
}
.page-footer__container {
  position: relative;
  z-index: 10;
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  min-width: 318px;
  width: 318px;
  min-height: 240px;
  padding-top: 12px;
  background-color: #FFFFFF;
  color: #444444;
  border: solid 1px transparent;
  border-top-left-radius: 30px;
  border-top-right-radius: 30px;
  margin-top: -131px;
  margin-left: auto;
  margin-right: auto;
}
@media (min-width: 768px) {
  .page-footer__container {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    grid-template-rows: 140px;
    min-width: 766px;
    width: 766px;
    min-height: 140px;
    margin-top: -170px;
    margin-left: auto;
    margin-right: auto;
    border-top-left-radius: 60px;
    border-top-right-radius: 60px;
  }
}
@media (min-width: 1440px) {
  .page-footer__container {
    min-width: 1438px;
    width: 1438px;
    min-height: 154px;
    margin-top: -127px;
    margin-bottom: 0px;
    margin-left: auto;
    margin-right: auto;
    position: relative;
    z-index: 4;
  }
}
.page-footer__logo {
  width: 96px;
  height: 15px;
  margin: 24px 0px 0px 0px;
}
@media (min-width: 768px) {
  .page-footer__logo {
    width: 164px;
    height: 42px;
    margin-top: -2px;
    margin-bottom: 0px;
    margin-left: -51px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .page-footer__logo {
    width: 200px;
    height: 55px;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
  }
}
.page-footer__contacts {
  display: flex;
  justify-content: center;
  width: auto;
  height: auto;
}
@media (min-width: 768px) {
  .page-footer__contacts {
    grid-column-start: 1;
    grid-row-start: 1;
    width: auto;
    height: auto;
    margin-top: 43px;
    margin-bottom: 0px;
    margin-left: 33px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .page-footer__contacts {
    margin-top: 36px;
    margin-bottom: 0px;
    margin-left: -159px;
    margin-right: 0px;
  }
}
.page-footer__social {
  display: flex;
  justify-content: center;
  margin: 39px 0px 0px -3px;
}
@media (min-width: 768px) {
  .page-footer__social {
    grid-column-start: 2;
    grid-row-start: 1;
    width: 183px;
    height: auto;
    margin-top: 32px;
    margin-bottom: 0px;
    margin-left: 34px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .page-footer__social {
    margin-top: 33px;
    margin-bottom: 0px;
    margin-left: 148px;
    margin-right: 0px;
  }
}
.page-footer__social a:hover {
  background-color: #FFBD30;
}
.page-footer__social a:active {
  background-color: #FFBD30;
  fill-opacity: 0.3;
}
.page-footer__copyright {
  margin-top: 50px;
  padding-left: 23px;
  cursor: pointer;
}
@media (min-width: 768px) {
  .page-footer__copyright {
    grid-column-start: 3;
    grid-row-start: 1;
    height: auto;
    margin-top: 51px;
    margin-bottom: 0px;
    margin-left: 36px;
    margin-right: 0px;
    padding: 0px;
  }
}
@media (min-width: 1440px) {
  .page-footer__copyright {
    margin-top: 50px;
    margin-bottom: 0px;
    margin-left: 240px;
    margin-right: 0px;
  }
}
.page-footer__copyright:hover {
  opacity: 0.6;
}
.page-footer__copyright:active {
  opacity: 0.3;
}
.page-footer__link {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 45px;
  height: 45px;
  border-radius: 50%;
  background-color: #FFD74B;
}
@media (min-width: 768px) {
  .page-footer__link {
    width: 62px;
    height: 62px;
  }
}
@media (min-width: 1440px) {
  .page-footer__link:first-child {
    background-size: 30px 30px;
  }
}
@media (min-width: 1440px) {
  .page-footer__link:nth-child(2) {
    background-size: 30px 30px;
  }
}
@media (min-width: 1440px) {
  .page-footer__link:last-child {
    background-size: 30px 30px;
  }
}
.page-footer__icon-fb {
  margin: auto;
}
@media (min-width: 768px) {
  .page-footer__icon-fb {
    width: 14px;
    height: 28px;
  }
}
.page-footer__icon-vk {
  margin: auto;
}
@media (min-width: 768px) {
  .page-footer__icon-vk {
    width: 30px;
    height: 16px;
  }
}
.page-footer__icon-inst {
  margin: auto;
}
@media (min-width: 768px) {
  .page-footer__icon-inst {
    width: 23px;
    height: 23px;
  }
}
.page-footer__text {
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 30px;
  color: #444444;
}
@media (min-width: 768px) {
  .page-footer__text {
    font-style: normal;
    font-weight: normal;
    font-size: 20px;
    line-height: 20px;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: 25px;
    margin-right: 0px;
  }
}
.page-footer__copyright-link {
  display: inline-block;
  width: 28px;
  height: 34px;
  margin-left: 153px;
  background-image: url(../assets/img/html-footer-icon.svg);
  background-repeat: no-repeat;
}
@media (min-width: 768px) {
  .page-footer__copyright-link {
    width: 27px;
    height: 34px;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: 14px;
    margin-right: 0px;
  }
}
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
  background-image: url(../assets/img/traveller-illustration-mobile@1x.png), url(../assets/img/globe-back-mobile@1x.jpg);
  background-repeat: no-repeat, no-repeat;
  background-position: 79px 221px, 0px 0px;
  border: solid 1px transparent;
  margin-left: auto;
  margin-right: auto;
}
@media (min-resolution: 2dppx) {
  .page-header__container {
    background-image: url(../assets/img/traveller-illustration-mobile@2x.png), url(../assets/img/globe-back-mobile@2x.jpg);
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
    background-image: url(../assets/img/traveller-illustration-desktop@1x.png), url(../assets/img/globe-back-desktop@1x.jpg);
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
    background-image: url(../assets/img/traveller-illustration-desktop@2x.png), url(../assets/img/globe-back-desktop@2x.jpg);
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
  background-image: url("../assets/img/icon-menu-mobile-close.svg");
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
  background-image: url("../assets/img/icon-telephone-yellow.svg");
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
  background-image: url("../assets/img/icon-mail-yellow.svg");
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
  background-image: url(../assets/img/icon-menu-mobile.svg);
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
    background-image: url(../assets/img/scroll-btn-main.svg);
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
    background-image: url(../assets/img/scroll-icon-call.svg);
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
    background-image: url(../assets/img/scroll-icon-email.svg);
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
.page-main {
  height: auto;
}
.persons {
  min-width: 100%;
  width: 100%;
  background-color: #E5E5E5;
}
.persons__container {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-items: center;
  min-width: 320px;
  width: 320px;
  background-color: #E5E5E5;
  margin: 0px auto 0px auto;
  padding-top: 18px;
  padding-bottom: 66px;
}
@media (min-width: 768px) {
  .persons__container {
    min-width: 768px;
    width: 768px;
    margin: 0px auto 0px auto;
    padding-bottom: 120px;
  }
}
@media (min-width: 1440px) {
  .persons__container {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: flex-start;
    min-width: 1440px;
    width: 1440px;
    margin: -1088px auto 0px auto;
    padding: 0px 0px 140px 64px;
    position: relative;
    z-index: 9;
    box-sizing: border-box;
  }
}
.persons__item {
  display: grid;
  grid-template-columns: 90px 90px 90px;
  grid-template-rows: 0.8fr 0.4fr 2fr 0.4fr;
  width: 270px;
  background-color: #FFFFFF;
  border-radius: 20px;
  border: solid 1px transparent;
  list-style: none;
  margin-top: 10px;
  padding-top: 15px;
  padding-bottom: 21px;
  cursor: pointer;
}
@media (min-width: 768px) {
  .persons__item {
    grid-template-columns: 229px 229px 229px;
    grid-template-rows: 1fr 1fr 1fr 1fr;
    width: auto;
    padding: 0px;
    margin-top: 10px;
    margin-bottom: 27px;
  }
}
@media (min-width: 1440px) {
  .persons__item {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    grid-template-rows: 1fr 1fr 1fr 1fr;
    width: 948px;
    min-height: 283px;
    padding: 0px 0px 0px 0px;
    margin: 0px 0px 29px 0px;
  }
}
.persons__item:hover {
  filter: drop-shadow(0px 4px 9px rgba(0, 0, 0, 0.16));
}
@media (min-width: 320px) {
  .persons__item-one {
    min-height: 377px;
    height: 377px;
  }
}
@media (min-width: 768px) {
  .persons__item-one {
    margin-top: 10px;
    margin-bottom: 30px;
    min-height: 330px;
    height: 330px;
  }
}
@media (min-width: 1440px) {
  .persons__item-one {
    width: 945px;
    min-height: 284px;
    height: 284px;
    margin: 0px 0px 0px 0px;
  }
}
@media (min-width: 320px) {
  .persons__item-two {
    min-height: 355px;
    height: 355px;
  }
}
@media (min-width: 768px) {
  .persons__item-two {
    min-height: 330px;
    height: 330px;
    margin: 10px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .persons__item-two {
    width: 945px;
    min-height: 284px;
    height: 284px;
    margin: 29px 0px 0px 0px;
  }
}
@media (min-width: 320px) {
  .persons .persons__item-three {
    min-height: 379px;
    height: 379px;
  }
}
@media (min-width: 768px) {
  .persons .persons__item-three {
    min-height: 330px;
    height: 330px;
    margin: 40px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .persons .persons__item-three {
    width: 945px;
    min-height: 283px;
    height: 283px;
    margin: 31px 0px 0px 0px;
  }
}
@media (min-width: 320px) {
  .persons__item-four {
    min-height: 358px;
    height: 358px;
  }
}
@media (min-width: 768px) {
  .persons__item-four {
    min-height: 330px;
    height: 330px;
    margin: 40px 0px 29px 0px;
  }
}
@media (min-width: 1440px) {
  .persons__item-four {
    width: 945px;
    min-height: 283px;
    height: 283px;
    margin: 31px 0px 0px 0px;
  }
}
.persons__avatar {
  grid-column-start: 1;
  grid-row-start: 1;
  margin-top: 0px;
  margin-left: 18px;
}
@media (min-width: 768px) {
  .persons__avatar {
    grid-column-start: 1;
    grid-row-start: 1;
    grid-row-end: 4;
    margin-top: 34px;
    margin-bottom: 0px;
    margin-left: 33px;
    margin-right: 0px;
    width: 190px;
    height: 190px;
    border-radius: 20px;
  }
}
@media (min-width: 1440px) {
  .persons__avatar {
    grid-column-start: 1;
    grid-column-end: 3;
    grid-row-start: 1;
    grid-row-end: 5;
    width: 285px;
    height: 285px;
    padding: 0px 0px 0px 0px;
    margin: 0px 0px 0px -3px;
  }
}
.persons__icon {
  width: 70px;
  height: 70px;
  border-radius: 50%;
  padding: 0px 0px 0px 0px;
  margin: 0px 0px 0px 0px;
}
@media (min-width: 768px) {
  .persons__icon {
    width: 190px;
    height: 190px;
    border-radius: 20px;
    padding: 0px 0px 0px 0px;
    margin: 0px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .persons__icon {
    width: 285px;
    height: 285px;
    border-top-left-radius: 20px;
    border-bottom-left-radius: 20px;
    border-top-right-radius: 0px;
    border-bottom-right-radius: 0px;
    padding: 0px 0px 0px 0px;
    margin: 0px 0px 0px 0px;
  }
}
.persons__name {
  grid-column-start: 2;
  grid-row-start: 1;
  grid-row-end: 2;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-weight: 700;
  font-style: normal;
  font-size: 20px;
  line-height: 20px;
  color: #1D2E5B;
  margin-top: -3px;
  margin-bottom: 0px;
  margin-left: 14px;
}
@media (min-width: 768px) {
  .persons__name {
    grid-column-start: 2;
    grid-column-end: 4;
    grid-row-start: 1;
    font-style: normal;
    font-weight: bold;
    font-size: 30px;
    line-height: 30px;
    margin-top: 29px;
    margin-bottom: 0px;
    margin-left: 27px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .persons__name {
    grid-column-start: 2;
    grid-column-end: 4;
    grid-row-start: 1;
    grid-row-end: 3;
    padding: 0px 0px 0px 0px;
    margin: 43px 0px 0px 31px;
  }
}
.persons__dot {
  grid-column-start: 3;
  grid-row-start: 1;
  width: 6px;
  height: 6px;
  border-radius: 50%;
  background-color: #F97676;
  margin-top: 8px;
  margin-left: 61px;
}
@media (min-width: 768px) {
  .persons__dot {
    grid-column-start: 3;
    grid-row-start: 1;
    width: 8px;
    height: 8px;
    margin-top: 43px;
    margin-bottom: 0px;
    margin-left: 9px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .persons__dot {
    grid-column-start: 2;
    grid-row-start: 1;
    margin-top: 57px;
    margin-bottom: 0px;
    margin-left: 6px;
    margin-right: 0px;
  }
}
.persons__rating {
  grid-column-start: 2;
  grid-row-start: 1;
  margin-top: 38px;
  margin-left: -22px;
  display: flex;
  align-items: center;
  padding-left: 36px;
  width: 71px;
  height: 32px;
  background-image: url(../assets/img/heart-rating-icon-grey.svg);
  background-repeat: no-repeat;
  background-position: left;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 14px;
  line-height: 16px;
  text-transform: uppercase;
}
@media (min-width: 768px) {
  .persons__rating {
    grid-column-start: 3;
    grid-row-start: 3;
    grid-row-end: 4;
    width: 50px;
    height: 51px;
    background-image: url(../assets/img/heart-rating-icon-grey.svg);
    background-repeat: no-repeat;
    background-position: left;
    background-size: 50px 50px;
    font-size: 20px;
    line-height: 20px;
    margin-top: 5px;
    margin-bottom: 0px;
    margin-left: -56px;
    margin-right: 0px;
    padding: 0px 0px 0px 57px;
  }
}
@media (min-width: 1440px) {
  .persons__rating {
    grid-column-start: 2;
    grid-column-end: 4;
    grid-row-start: 3;
    grid-row-end: 5;
    padding: 0px 0px 0px 58px;
    margin: 42px 0px 0px 171px;
  }
}
.persons__hobby {
  grid-column-start: 1;
  grid-column-end: 4;
  grid-row-start: 2;
  display: inline-block;
  width: 177px;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: 300;
  font-size: 15px;
  line-height: 18px;
  color: #444444;
  margin-top: -1px;
  margin-bottom: 0px;
  margin-left: 25px;
  margin-right: 20px;
}
@media (min-width: 768px) {
  .persons__hobby {
    grid-column-start: 2;
    grid-row-start: 2;
    grid-row-end: 3;
    display: inline-block;
    width: 227px;
    font-size: 20px;
    line-height: 23px;
    margin-top: -4px;
    margin-bottom: 0px;
    margin-left: 30px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .persons__hobby {
    grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 2;
    grid-row-end: 4;
    padding: 0px 0px 0px 0px;
    margin: 23px 0px 0px 31px;
  }
}
.persons__about-list {
  grid-column-start: 1;
  grid-row-start: 3;
  display: grid;
  grid-template-columns: 1fr;
  grid-template-rows: 1.5fr 1fr;
  margin-top: 4px;
  margin-left: 25px;
}
@media (min-width: 768px) {
  .persons__about-list {
    grid-column-start: 1;
    grid-column-end: 4;
    grid-row-start: 1;
    grid-row-end: 5;
    display: grid;
    grid-template-columns: 4fr 1fr;
    grid-template-rows: 2fr 2fr 0.4fr;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .persons__about-list {
    grid-column-start: 1;
    grid-column-end: 4;
    grid-row-start: 1;
    grid-row-end: 5;
    display: grid;
    grid-template-columns: 675px 274px;
    grid-template-rows: 142px 143px;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
  }
}
.persons__about-item:nth-child(1) {
  grid-column-start: 1;
  grid-row-start: 1;
  border: solid 1px transparent;
  margin-top: 3px;
  margin-bottom: 0px;
}
@media (min-width: 768px) {
  .persons__about-item:nth-child(1) {
    grid-column-start: 1;
    grid-row-start: 3;
    margin-top: -59px;
    margin-bottom: 0px;
    margin-left: 35px;
    margin-right: 0px;
    order: 3;
  }
}
@media (min-width: 1440px) {
  .persons__about-item:nth-child(1) {
    grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 1;
    grid-row-end: 2;
    margin-top: 43px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
    padding: 0px 0px 0px 0px;
  }
}
.persons__about-item:nth-child(2) {
  grid-column-start: 1;
  grid-row-start: 2;
  grid-row-end: auto;
  border: solid 1px transparent;
  margin-top: 4px;
}
@media (min-width: 768px) {
  .persons__about-item:nth-child(2) {
    grid-column-start: 2;
    grid-row-start: 1;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .persons__about-item:nth-child(2) {
    grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 2;
    grid-row-end: 3;
    margin-top: 55px;
    margin-bottom: 0px;
    margin-left: -9px;
    margin-right: 0px;
    padding: 0px 0px 0px 0px;
  }
}
.persons__about-item:nth-child(3) {
  grid-column-start: 2;
  grid-row-start: 2;
  grid-row-end: 4;
  border: solid 1px transparent;
  margin: 4px 0px 0px 17px;
}
@media (min-width: 768px) {
  .persons__about-item:nth-child(3) {
    grid-column-start: 2;
    grid-row-start: 2;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: 43px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .persons__about-item:nth-child(3) {
    grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 2;
    grid-row-end: 3;
    margin-top: 27px;
    margin-bottom: 0px;
    margin-left: 163px;
    margin-right: 0px;
    padding: 0px 0px 0px 0px;
  }
}
.persons__button {
  grid-column-start: 1;
  grid-row-start: 4;
  margin-top: 13px;
  margin-left: 20px;
  width: 230px;
  height: 38px;
  background-color: #FFD74B;
  border-radius: 25px;
  border: solid 1px transparent;
}
@media (min-width: 768px) {
  .persons__button {
    grid-column-start: 2;
    grid-row-start: 3;
    grid-row-end: 4;
    width: 150px;
    height: 50px;
    margin-top: 8px;
    margin-bottom: 0px;
    margin-left: 23px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .persons__button {
    grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 3;
    grid-row-end: 5;
    padding: 1px 0px 0px 2px;
    margin: 44px 0px 0px 21px;
  }
}
.persons__btn-text {
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 17px;
  line-height: 17px;
  text-align: center;
  text-transform: uppercase;
  color: #161C35;
}
@media (min-width: 768px) {
  .persons__btn-text {
    font-size: 20px;
    line-height: 20px;
  }
}
.persons__button-two {
  width: 230px;
  height: 40px;
  padding: 0px 0px 0px 0px;
  margin: 0px 0px 0px 19px;
}
@media (min-width: 768px) {
  .persons__button-two {
    width: 150px;
    height: 50px;
    padding: 0px 0px 0px 0px;
    margin: 8px 0px 0px 23px;
  }
}
@media (min-width: 1440px) {
  .persons__button-two {
    width: 150px;
    height: 50px;
    padding: 1px 0px 0px 1px;
    margin: 45px 0px 0px 21px;
  }
}
.persons__button-three {
  padding: 0px 0px 0px 0px;
  margin: 12px 0px 0px 19px;
}
@media (min-width: 768px) {
  .persons__button-three {
    width: 150px;
    height: 50px;
    padding: 0px 0px 0px 0px;
    margin: 8px 0px 0px 23px;
  }
}
@media (min-width: 1440px) {
  .persons__button-three {
    width: 150px;
    height: 50px;
    padding: 2px 0px 0px 2px;
    margin: 44px 0px 0px 21px;
  }
}
.persons__button-four {
  padding: 0px 0px 0px 0px;
  margin: -2px 0px 0px 19px;
}
@media (min-width: 768px) {
  .persons__button-four {
    padding: 0px 0px 0px 0px;
    margin: 8px 0px 0px 25px;
  }
}
@media (min-width: 1440px) {
  .persons__button-four {
    padding: 2px 0px 0px 1px;
    margin: 44px 0px 0px 21px;
  }
}
.persons__wishes {
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: normal;
  font-size: 15px;
  line-height: 16px;
  color: #444444;
  margin-top: 0px;
}
@media (min-width: 768px) {
  .persons__wishes {
    padding: 0px 0px 0px 0px;
    margin: 0px 0px 0px 47px;
  }
}
@media (min-width: 1440px) {
  .persons__wishes {
    display: none;
  }
}
.persons__wish-wrapper {
  display: grid;
  grid-template-columns: 1fr 3fr;
  width: 150px;
  align-items: center;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: 500;
  font-size: 15px;
  line-height: 1px;
  text-transform: uppercase;
  color: #1D2E5B;
  margin-top: 13px;
}
@media (min-width: 768px) {
  .persons__wish-wrapper {
    display: flex;
    justify-content: flex-start;
    align-items: center;
    width: 100%;
    min-width: 465px;
    font-size: 20px;
    line-height: 20px;
    margin-top: 22px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
    padding: 0px;
  }
}
@media (min-width: 1440px) {
  .persons__wish-wrapper {
    display: grid;
    grid-template-columns: 1fr 3fr;
    align-items: center;
    min-width: 200px;
    width: 200px;
    min-height: 108px;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
    padding: 0px;
  }
}
.persons__wish-flag {
  margin: 8px 0px 0px 0px;
  padding: 0px 0px 0px 0px;
}
@media (min-width: 768px) {
  .persons__wish-flag {
    width: 35px;
    height: 24px;
    margin-top: -2px;
    margin-bottom: 0px;
    margin-left: -1px;
    margin-right: 9px;
    padding: 0px;
  }
}
@media (min-width: 1440px) {
  .persons__wish-flag {
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: -4px;
    margin-right: 0px;
    padding: 0px;
  }
}
.persons__wish-text {
  margin: 12px 0px 0px 0px;
  padding: 0px 0px 0px 0px;
}
@media (min-width: 768px) {
  .persons__wish-text {
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 28px;
    padding: 0px;
  }
}
@media (min-width: 1440px) {
  .persons__wish-text {
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
    padding: 0px;
  }
}
.persons__level {
  display: block;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: normal;
  font-size: 15px;
  line-height: 16px;
  color: #444444;
  margin-top: 2px;
  margin-left: 11px;
}
@media (min-width: 768px) {
  .persons__level {
    display: none;
  }
}
.persons__level-number-firsova {
  display: block;
  width: 45px;
  height: 45px;
  margin-top: 11px;
  margin-left: 6px;
  background-image: url("../assets/img/person-level-firsova.svg");
  background-repeat: no-repeat;
  background-position: center;
}
@media (min-width: 768px) {
  .persons__level-number-firsova {
    width: 63px;
    height: 63px;
    background-image: url("../assets/img/person-level-firsova-tablet.svg");
    background-repeat: no-repeat;
    background-position: center;
  }
}
.persons__level-number-demin {
  display: block;
  width: 45px;
  height: 45px;
  margin-top: 11px;
  margin-left: 6px;
  background-image: url("../assets/img/person-level-demin.svg");
  background-repeat: no-repeat;
  background-position: center;
}
@media (min-width: 768px) {
  .persons__level-number-demin {
    width: 63px;
    height: 63px;
    background-image: url("../assets/img/person-level-demin-tablet.svg");
    background-repeat: no-repeat;
    background-position: center;
  }
}
.persons__level-number-smolov {
  display: block;
  width: 45px;
  height: 45px;
  margin-top: 11px;
  margin-left: 6px;
  background-image: url("../assets/img/person-level-smolov.svg");
  background-repeat: no-repeat;
  background-position: center;
}
@media (min-width: 768px) {
  .persons__level-number-smolov {
    width: 63px;
    height: 63px;
    background-image: url("../assets/img/person-level-smolov-tablet.svg");
    background-repeat: no-repeat;
    background-position: center;
  }
}
.persons__level-number-rogovya {
  display: block;
  width: 45px;
  height: 45px;
  margin-top: 11px;
  margin-left: 6px;
  background-image: url("../assets/img/person-level-rogovya.svg");
  background-repeat: no-repeat;
  background-position: center;
}
@media (min-width: 768px) {
  .persons__level-number-rogovya {
    width: 63px;
    height: 63px;
    background-image: url("../assets/img/person-level-rogovya-tablet.svg");
    background-repeat: no-repeat;
    background-position: center;
  }
}
.persons__transport {
  display: block;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: 300;
  font-size: 15px;
  line-height: 16px;
  color: #444444;
}
@media (min-width: 768px) {
  .persons__transport {
    display: none;
  }
}
.persons__transport-wrapper {
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 130px;
  margin-top: 20px;
  margin-left: -3px;
}
@media (min-width: 768px) {
  .persons__transport-wrapper {
    display: flex;
    flex-direction: column;
    width: 30px;
    height: 128px;
    margin-top: 29px;
    margin-bottom: 0px;
    margin-left: 65px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .persons__transport-wrapper {
    display: flex;
    flex-direction: row;
    width: 131px;
    height: 30px;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
  }
}
.persons__transport-icon {
  display: inline-block;
  width: 32px;
  height: 32px;
  border-radius: 50%;
  background-color: #EDEFF6;
}
@media (min-width: 768px) {
  .persons__transport-icon {
    background-color: transparent;
  }
}
@media (min-width: 1440px) {
  .persons__transport-icon {
    background-color: transparent;
  }
}
.persons__transport-icon-plane {
  background-image: url(../assets/img/transport-plane.svg);
  background-repeat: no-repeat;
  background-position: center;
  background-size: 17px 17px;
  border: none;
}
@media (min-width: 768px) {
  .persons__transport-icon-plane {
    background-size: 23px 23px;
  }
}
@media (min-width: 1440px) {
  .persons__transport-icon-plane {
    background-size: 23px 23px;
  }
}
.persons__transport-icon-bus {
  background-image: url(../assets/img/transport-bus.svg);
  background-repeat: no-repeat;
  background-position: center;
  border: none;
}
@media (min-width: 768px) {
  .persons__transport-icon-bus {
    background-size: 20px 23px;
  }
}
@media (min-width: 1440px) {
  .persons__transport-icon-bus {
    background-size: 20px 23px;
  }
}
.persons__transport-icon-bike {
  background-image: url(../assets/img/transport-bike.svg);
  background-repeat: no-repeat;
  background-position: center;
  border: none;
}
@media (min-width: 768px) {
  .persons__transport-icon-bike {
    background-size: 23px 23px;
  }
}
@media (min-width: 1440px) {
  .persons__transport-icon-bike {
    background-size: 23px 23px;
  }
}
.persons__transport-icon-run {
  background-image: url(../assets/img/transport-run.svg);
  background-repeat: no-repeat;
  background-position: center;
  border: none;
}
@media (min-width: 768px) {
  .persons__transport-icon-run {
    background-size: 23px 23px;
  }
}
@media (min-width: 1440px) {
  .persons__transport-icon-run {
    background-size: 23px 23px;
  }
}
.persons__controls {
  display: flex;
  flex-direction: column;
  align-items: center;
  border: solid 1px transparent;
  margin-top: 12px;
  margin-left: 5px;
}
@media (min-width: 1440px) {
  .persons__controls {
    margin: 19px 0px 0px 3px;
  }
}
.persons__btn-more {
  min-width: 160px;
  width: auto;
  height: 30px;
  background-color: transparent;
  border: solid 1px transparent;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 17px;
  line-height: 30px;
  text-transform: uppercase;
  color: #1D2E5B;
  text-align: right;
  background-image: url(../assets/img/persons-btn-more.svg);
  background-repeat: no-repeat;
  background-position: 1% 82%;
  margin: 0px 0px 0px 0px;
  padding: 3px 9px 0px 0px;
  box-sizing: border-box;
}
@media (min-width: 768px) {
  .persons__btn-more {
    min-width: 213px;
    height: 50px;
    font-style: normal;
    font-weight: bold;
    font-size: 20px;
    line-height: 20px;
    margin-top: -10px;
    margin-bottom: 0px;
    margin-left: -22px;
    margin-right: 0px;
    background-image: url(../assets/img/persons-btn-more-tablet.svg);
    background-repeat: no-repeat;
    background-position: 9% 58%;
  }
}
@media (min-width: 1440px) {
  .persons__btn-more {
    min-width: 213px;
    height: 50px;
    font-style: normal;
    font-weight: bold;
    font-size: 20px;
    line-height: 20px;
    margin-top: 27px;
    margin-bottom: 0px;
    margin-left: -88px;
    margin-right: 0px;
    background-image: url(../assets/img/persons-btn-more-tablet.svg);
    background-repeat: no-repeat;
    background-position: 10% 63%;
  }
}
.persons__controls-wrap {
  display: flex;
  justify-content: space-between;
  width: 271px;
  margin-top: 22px;
  margin-left: -10px;
}
@media (min-width: 768px) {
  .persons__controls-wrap {
    display: flex;
    justify-content: flex-start;
    align-items: center;
    min-width: 688px;
    height: 100px;
    margin: 41px 9px 0px 5px;
    padding: 0px 0px 0px 28px;
    background-color: #FFFFFF;
    border-radius: 20px;
    box-sizing: border-box;
  }
}
@media (min-width: 1440px) {
  .persons__controls-wrap {
    display: flex;
    justify-content: flex-start;
    align-items: center;
    min-width: 947px;
    height: 100px;
    margin: 62px 0px 0px -5px;
    padding: 0px 0px 0px 28px;
    background-color: #FFFFFF;
    border-radius: 20px;
    box-sizing: border-box;
  }
}
.persons__breadcrumbs-btn {
  display: none;
}
@media (min-width: 768px) {
  .persons__breadcrumbs-btn {
    display: inline-block;
    width: 50px;
    height: 50px;
    border-radius: 50%;
    background-color: transparent;
    border: none;
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: bold;
    font-size: 20px;
    line-height: 20px;
    color: #1D2E5B;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
  }
}
.persons__breadcrumbs-btn-active {
  display: none;
}
@media (min-width: 768px) {
  .persons__breadcrumbs-btn-active {
    display: inline-block;
    background-color: #FFD74B;
  }
}
.persons__btn-prev {
  width: 135px;
  height: 51px;
  border-top-left-radius: 20px;
  border-bottom-left-radius: 20px;
  border: solid 1px transparent;
  background-image: url("../assets/img/icon-arrows-prev.svg");
  background-repeat: no-repeat;
  background-position: 53% 59%;
}
@media (min-width: 768px) {
  .persons__btn-prev {
    display: inline-block;
    width: 50px;
    height: 50px;
    background-color: transparent;
    border: none;
    line-height: 20px;
    margin-top: -6px;
    margin-bottom: 0px;
    margin-left: 351px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .persons__btn-prev {
    display: inline-block;
    width: 50px;
    height: 50px;
    background-color: transparent;
    border: none;
    line-height: 20px;
    margin-top: -3px;
    margin-bottom: 0px;
    margin-left: 602px;
    margin-right: 0px;
  }
}
.persons__btn-next {
  width: 135px;
  height: 51px;
  border-top-right-radius: 20px;
  border-bottom-right-radius: 20px;
  border: solid 1px transparent;
  background-image: url("../assets/img/icon-arrows-next.svg");
  background-repeat: no-repeat;
  background-position: 51% 52%;
}
@media (min-width: 768px) {
  .persons__btn-next {
    display: inline-block;
    width: 50px;
    height: 50px;
    background-color: transparent;
    border: none;
    line-height: 20px;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: -6px;
    margin-right: 0px;
  }
}
.persons__name-demin {
  padding: 0px 0px 0px 0px;
  margin: -2px 0px 0px 14px;
}
@media (min-width: 768px) {
  .persons__name-demin {
    padding: 0px 0px 0px 0px;
    margin: 30px 0px 0px 28px;
  }
}
@media (min-width: 1440px) {
  .persons__name-demin {
    padding: 0px 0px 0px 0px;
    margin: 44px 0px 0px 29px;
  }
}
.persons__dot-demin {
  padding: 0px 0px 0px 0px;
  margin: 7px 0px 0px 62px;
}
@media (min-width: 768px) {
  .persons__dot-demin {
    width: 8px;
    height: 8px;
    padding: 0px 0px 0px 0px;
    margin: 44px 0px 0px 9px;
  }
}
@media (min-width: 1440px) {
  .persons__dot-demin {
    padding: 0px 0px 0px 0px;
    margin: 57px 0px 0px 3px;
  }
}
.persons__rating-demin {
  padding: 0px 0px 0px 38px;
  margin: 40px 0px 0px -24px;
}
@media (min-width: 768px) {
  .persons__rating-demin {
    padding: 0px 0px 0px 56px;
    margin: 7px 0px 0px -55px;
  }
}
@media (min-width: 1440px) {
  .persons__rating-demin {
    padding: 0px 0px 0px 56px;
    margin: 44px 0px 0px 172px;
  }
}
.persons__hobby-demin {
  padding: 0px 0px 0px 0px;
  margin: 6px 0px 0px 25px;
}
@media (min-width: 768px) {
  .persons__hobby-demin {
    padding: 0px 0px 0px 0px;
    margin: -6px 0px 0px 30px;
  }
}
@media (min-width: 1440px) {
  .persons__hobby-demin {
    padding: 0px 0px 0px 0px;
    margin: 24px 0px 0px 29px;
  }
}
.persons__about-list-demin {
  padding: 0px 0px 0px 0px;
  margin: 7px 0px 0px 24px;
}
@media (min-width: 768px) {
  .persons__about-list-demin {
    padding: 0px 0px 0px 0px;
    margin: 0px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .persons__about-list-demin {
    padding: 0px 0px 0px 0px;
    margin: 0px 0px 0px 0px;
  }
}
.persons__about-list > .persons__demin-transport {
  padding: 0px 0px 0px 0px;
  margin: -11px 0px 0px 2px;
}
@media (min-width: 768px) {
  .persons__about-list > .persons__demin-transport {
    padding: 0px 0px 0px 0px;
    margin: 2px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .persons__about-list > .persons__demin-transport {
    padding: 0px 0px 0px 0px;
    margin: 55px 0px 0px -11px;
  }
}
.persons__about-list > .persons__demin-level {
  padding: 0px 0px 0px 0px;
  margin: -13px 0px 0px 20px;
}
@media (min-width: 768px) {
  .persons__about-list > .persons__demin-level {
    padding: 0px 0px 0px 0px;
    margin: -8px 0px 0px 43px;
  }
}
@media (min-width: 1440px) {
  .persons__about-list > .persons__demin-level {
    padding: 0px 0px 0px 0px;
    margin: 27px 0px 0px 159px;
  }
}
.persons__wish-wrapper-demin {
  padding: 0px 0px 0px 0px;
  margin: 3px 0px 0px 0px;
}
@media (min-width: 768px) {
  .persons__wish-wrapper-demin {
    width: 256px;
    min-width: auto;
    justify-content: space-between;
    padding: 0px 0px 0px 0px;
    margin: 20px 0px 0px -2px;
  }
}
@media (min-width: 1440px) {
  .persons__wish-wrapper-demin {
    width: 214px;
    min-width: auto;
    height: 72px;
    min-height: auto;
    padding: 0px 0px 0px 0px;
    margin: 0px 0px 0px -5px;
  }
}
.persons__wish-flag-demin {
  padding: 0px 0px 0px 0px;
  margin: 14px 0px -4px 0px;
}
@media (min-width: 768px) {
  .persons__wish-flag-demin {
    padding: 0px 0px 0px 0px;
    margin: 0px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .persons__wish-flag-demin {
    padding: 0px 0px 0px 0px;
    margin: 0px 0px 0px 0px;
  }
}
.persons__wish-text-demin {
  padding: 0px 0px 0px 0px;
  margin: 15px 0px -6px 2px;
}
@media (min-width: 768px) {
  .persons__wish-text-demin {
    padding: 0px 0px 0px 0px;
    margin: 2px 0px 0px -21px;
  }
}
@media (min-width: 1440px) {
  .persons__wish-text-demin {
    padding: 0px 0px 0px 0px;
    margin: 0px 0px 0px 0px;
  }
}
.persons__name-rog {
  padding: 0px 0px 0px 0px;
  margin: -2px 0px 0px 14px;
}
@media (min-width: 768px) {
  .persons__name-rog {
    padding: 0px 0px 0px 0px;
    margin: 30px 0px 0px 28px;
  }
}
@media (min-width: 1440px) {
  .persons__name-rog {
    padding: 0px 0px 0px 0px;
    margin: 43px 0px 0px 29px;
  }
}
.persons__dot-rog {
  background-color: #BBF085;
  padding: 0px 0px 0px 0px;
  margin: 7px 0px 0px 62px;
}
@media (min-width: 768px) {
  .persons__dot-rog {
    padding: 0px 0px 0px 0px;
    margin: 39px 0px 0px 42px;
  }
}
@media (min-width: 1440px) {
  .persons__dot-rog {
    padding: 0px 0px 0px 0px;
    margin: 56px 0px 0px 4px;
  }
}
.persons__rating-rog {
  padding: 0px 0px 0px 38px;
  margin: 40px 0px 0px -24px;
}
@media (min-width: 768px) {
  .persons__rating-rog {
    padding: 0px 0px 0px 57px;
    margin: 7px 0px 0px -56px;
  }
}
@media (min-width: 1440px) {
  .persons__rating-rog {
    padding: 0px 0px 0px 57px;
    margin: 43px 0px 0px 171px;
  }
}
.persons__hobby-rog {
  padding: 0px 0px 0px 0px;
  margin: 6px 0px 0px 25px;
}
@media (min-width: 768px) {
  .persons__hobby-rog {
    padding: 0px 0px 0px 0px;
    margin: -3px 0px 0px 30px;
  }
}
@media (min-width: 1440px) {
  .persons__hobby-rog {
    padding: 0px 0px 0px 0px;
    margin: 23px 0px 0px 30px;
  }
}
.persons__about-list-rog {
  padding: 0px 0px 0px 0px;
  margin: 7px 0px 0px 24px;
}
@media (min-width: 768px) {
  .persons__about-list-rog {
    padding: 0px 0px 0px 0px;
    margin: 0px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .persons__about-list-rog {
    padding: 0px 0px 0px 0px;
    margin: 0px 0px 0px 0px;
  }
}
.persons__about-list > .persons__rog-transport {
  padding: 0px 0px 0px 0px;
  margin: -11px 0px 0px 2px;
}
@media (min-width: 768px) {
  .persons__about-list > .persons__rog-transport {
    padding: 0px 0px 0px 0px;
    margin: 30px 0px 0px 64px;
  }
}
@media (min-width: 1440px) {
  .persons__about-list > .persons__rog-transport {
    padding: 0px 0px 0px 0px;
    margin: 54px 0px 0px -11px;
  }
}
.persons__about-list > .persons__rog-level {
  padding: 0px 0px 0px 0px;
  margin: -13px 0px 0px 11px;
}
@media (min-width: 768px) {
  .persons__about-list > .persons__rog-level {
    padding: 0px 0px 0px 0px;
    margin: -7px 0px 0px 44px;
  }
}
@media (min-width: 1440px) {
  .persons__about-list > .persons__rog-level {
    padding: 0px 0px 0px 0px;
    margin: 26px 0px 0px 160px;
  }
}
.persons__wish-wrapper-rog {
  width: 159px;
  padding: 0px 0px 0px 0px;
  margin: 6px 0px 0px 0px;
}
@media (min-width: 768px) {
  .persons__wish-wrapper-rog {
    width: 368px;
    min-width: auto;
    justify-content: space-between;
    padding: 0px 0px 0px 0px;
    margin: 18px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .persons__wish-wrapper-rog {
    width: 214px;
    min-width: auto;
    height: 76px;
    min-height: auto;
    padding: 0px 0px 0px 0px;
    margin: -4px 0px 0px -5px;
  }
}
.persons__wish-flag-rog {
  padding: 0px 0px 0px 0px;
  margin: 12px 0px -4px 0px;
}
@media (min-width: 768px) {
  .persons__wish-flag-rog {
    width: 35px;
    height: 24px;
    padding: 0px 0px 0px 0px;
    margin: 0px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .persons__wish-flag-rog {
    padding: 0px 0px 0px 0px;
    margin: 0px 0px 0px 0px;
  }
}
.persons__wish-text-rog {
  padding: 0px 0px 0px 0px;
  margin: 10px 0px -6px 2px;
}
@media (min-width: 768px) {
  .persons__wish-text-rog {
    padding: 0px 0px 0px 0px;
    margin: 3px 0px 0px -22px;
  }
}
@media (min-width: 1440px) {
  .persons__wish-text-rog {
    padding: 0px 0px 0px 0px;
    margin: 0px 0px 0px 0px;
  }
}
.persons__transport-wrapper-rog {
  padding: 0px 0px 0px 0px;
  margin: 15px 0px 0px -6px;
}
@media (min-width: 768px) {
  .persons__transport-wrapper-rog {
    padding: 0px 0px 0px 0px;
    margin: 0px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .persons__transport-wrapper-rog {
    padding: 0px 0px 0px 0px;
    margin: 0px 0px 0px 0px;
  }
}
.persons__wish-wrapper-smolov {
  width: 159px;
  padding: 0px 0px 0px 0px;
  margin: 8px 0px 0px 0px;
}
@media (min-width: 768px) {
  .persons__wish-wrapper-smolov {
    width: 428px;
    min-width: auto;
    justify-content: space-between;
    padding: 0px 0px 0px 0px;
    margin: 18px 0px 0px -2px;
  }
}
@media (min-width: 1440px) {
  .persons__wish-wrapper-smolov {
    width: 216px;
    min-width: auto;
    padding: 0px 0px 0px 0px;
    margin: -1px 0px 0px -5px;
  }
}
.persons__wish-flag-smolov {
  padding: 0px 0px 0px 0px;
  margin: 10px 0px 0px 0px;
}
@media (min-width: 768px) {
  .persons__wish-flag-smolov {
    padding: 0px 0px 0px 0px;
    margin: 0px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .persons__wish-flag-smolov {
    padding: 0px 0px 0px 0px;
    margin: 0px 0px 0px 0px;
  }
}
.persons__wish-text-smolov {
  padding: 0px 0px 0px 0px;
  margin: 10px 0px 0px 0px;
}
@media (min-width: 768px) {
  .persons__wish-text-smolov {
    padding: 0px 0px 0px 0px;
    margin: 0px 0px 0px -17px;
  }
}
@media (min-width: 1440px) {
  .persons__wish-text-smolov {
    padding: 0px 0px 0px 0px;
    margin: 0px 0px 0px 0px;
  }
}
.persons__about-list > .persons__smolov-transport {
  padding: 0px 0px 0px 0px;
  margin: 6px 0px 0px 0px;
}
@media (min-width: 768px) {
  .persons__about-list > .persons__smolov-transport {
    padding: 0px 0px 0px 0px;
    margin: 31px 0px 0px 64px;
  }
}
@media (min-width: 1440px) {
  .persons__about-list > .persons__smolov-transport {
    padding: 0px 0px 0px 0px;
    margin: 54px 0px 0px -11px;
  }
}
.persons__about-list > .persons__smolov-level {
  padding: 0px 0px 0px 0px;
  margin: 4px 0px 0px 10px;
}
@media (min-width: 768px) {
  .persons__about-list > .persons__smolov-level {
    padding: 0px 0px 0px 0px;
    margin: -9px 0px 0px 44px;
  }
}
@media (min-width: 1440px) {
  .persons__about-list > .persons__smolov-level {
    padding: 0px 0px 0px 0px;
    margin: 24px 0px 0px 160px;
  }
}
.persons__transport-wrapper-smolov {
  padding: 0px 0px 0px 0px;
  margin: 16px 0px 0px -5px;
}
@media (min-width: 768px) {
  .persons__transport-wrapper-smolov {
    padding: 0px 0px 0px 0px;
    margin: 0px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .persons__transport-wrapper-smolov {
    padding: 0px 0px 0px 0px;
    margin: 0px 0px 0px 0px;
  }
}
.persons__name-firsova {
  padding: 0px 0px 0px 0px;
  margin: -3px 0px 0px 13px;
}
@media (min-width: 768px) {
  .persons__name-firsova {
    padding: 0px 0px 0px 0px;
    margin: 30px 0px 0px 27px;
  }
}
@media (min-width: 1440px) {
  .persons__name-firsova {
    padding: 0px 0px 0px 0px;
    margin: 43px 0px 0px 29px;
  }
}
.persons__dot-firsova {
  padding: 0px 0px 0px 0px;
  margin: 7px 0px 0px 61px;
}
@media (min-width: 768px) {
  .persons__dot-firsova {
    width: 8px;
    height: 8px;
    padding: 0px 0px 0px 0px;
    margin: 43px 0px 0px 8px;
  }
}
@media (min-width: 1440px) {
  .persons__dot-firsova {
    padding: 0px 0px 0px 0px;
    margin: 56px 0px 0px 3px;
  }
}
.persons__rating-firsova {
  background-image: url(../assets/img/heart-rating-icon.svg);
  padding: 0px 0px 0px 36px;
  margin: 37px 0px 0px -23px;
  box-sizing: border-box;
}
@media (min-width: 768px) {
  .persons__rating-firsova {
    width: 120px;
    height: auto;
    padding: 0px 0px 0px 56px;
    margin: -18px 0px 0px -54px;
    background-size: 50px 50px;
    box-sizing: border-box;
  }
}
@media (min-width: 1440px) {
  .persons__rating-firsova {
    padding: 0px 0px 2px 58px;
    margin: -4px 0px 0px 171px;
  }
}
.persons__hobby-firsova {
  padding: 0px 0px 0px 0px;
  margin: -1px 0px 0px 25px;
}
@media (min-width: 768px) {
  .persons__hobby-firsova {
    padding: 0px 0px 0px 0px;
    margin: -3px 0px 0px 30px;
  }
}
@media (min-width: 1440px) {
  .persons__hobby-firsova {
    padding: 0px 0px 0px 0px;
    margin: 23px 0px 0px 29px;
  }
}
.persons__about-list-firsova {
  padding: 0px 0px 0px 0px;
  margin: 2px 0px 0px 0px;
}
@media (min-width: 768px) {
  .persons__about-list-firsova {
    padding: 0px 0px 0px 0px;
    margin: 0px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .persons__about-list-firsova {
    padding: 0px 0px 0px 0px;
    margin: 0px 0px 0px 0px;
  }
}
.persons__wish-wrapper-firsova {
  padding: 0px 0px 0px 0px;
  margin: 11px 0px 0px 23px;
}
@media (min-width: 768px) {
  .persons__wish-wrapper-firsova {
    width: 465px;
    padding: 0px 0px 0px 0px;
    margin: 19px 0px 0px 0px;
    justify-content: space-between;
  }
}
@media (min-width: 1440px) {
  .persons__wish-wrapper-firsova {
    width: 217px;
    padding: 0px 0px 0px 0px;
    margin: 0px 0px 0px -5px;
  }
}
.persons__wish-flag-firsova {
  padding: 0px 0px 0px 0px;
  margin: 9px 0px 0px 0px;
}
@media (min-width: 768px) {
  .persons__wish-flag-firsova {
    padding: 0px 0px 0px 0px;
    margin: 0px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .persons__wish-flag-firsova {
    padding: 0px 0px 0px 0px;
    margin: 0px 0px 0px 0px;
  }
}
.persons__wish-text-firsova {
  padding: 0px 0px 0px 0px;
  margin: 13px 0px 0px 2px;
}
@media (min-width: 768px) {
  .persons__wish-text-firsova {
    padding: 0px 0px 0px 0px;
    margin: 0px 0px 0px -18px;
  }
}
@media (min-width: 1440px) {
  .persons__wish-text-firsova {
    padding: 0px 0px 0px 0px;
    margin: 0px 0px 0px 0px;
  }
}
.persons__transport-wrapper-firsova {
  padding: 0px 0px 0px 0px;
  margin: 18px 0px 0px -5px;
}
@media (min-width: 768px) {
  .persons__transport-wrapper-firsova {
    width: 30px;
    height: 127px;
    padding: 0px 0px 0px 0px;
    margin: -1px 0px 0px -1px;
  }
}
@media (min-width: 1440px) {
  .persons__transport-wrapper-firsova {
    width: 133px;
    height: 30px;
    padding: 0px 0px 0px 0px;
    margin: 54px 0px 0px -11px;
  }
}
.persons__about-list > .persons__firsova-transport {
  padding: 0px 0px 0px 0px;
  margin: 5px 0px 0px 25px;
}
@media (min-width: 768px) {
  .persons__about-list > .persons__firsova-transport {
    padding: 0px 0px 0px 0px;
    margin: 32px 0px 0px 65px;
  }
}
@media (min-width: 1440px) {
  .persons__about-list > .persons__firsova-transport {
    padding: 0px 0px 0px 0px;
    margin: 0px 0px 0px 0px;
  }
}
.persons__about-list > .persons__firsova-level {
  padding: 0px 0px 0px 0px;
  margin: 4px 0px 0px 20px;
}
@media (min-width: 768px) {
  .persons__about-list > .persons__firsova-level {
    padding: 0px 0px 0px 0px;
    margin: -6px 0px 0px 43px;
  }
}
@media (min-width: 1440px) {
  .persons__about-list > .persons__firsova-level {
    padding: 0px 0px 0px 0px;
    margin: 26px 0px 0px 159px;
  }
}
.persons__wishes-firsova {
  padding: 0px 0px 0px 0px;
  margin: 0px 0px 0px 24px;
}
@media (min-width: 768px) {
  .persons__wishes-firsova {
    display: inline-block;
    width: 96px;
    height: 16px;
    padding: 0px 0px 0px 0px;
    margin: 0px 0px 0px 48px;
  }
}
@media (min-width: 1440px) {
  .persons__wishes-firsova {
    display: none;
  }
}
.plans {
  position: relative;
  z-index: 10;
  min-width: 100%;
  width: 100%;
  background-color: #DFE3F0;
}
.plans__container {
  display: flex;
  flex-direction: column;
  justify-content: space-around;
  width: 318px;
  min-width: 318px;
  min-height: 404px;
  margin-top: -36px;
  margin-left: auto;
  margin-right: auto;
  padding-bottom: 55px;
  border-top-left-radius: 30px;
  border-top-right-radius: 30px;
  background-color: #DFE3F0;
  border: solid 1px transparent;
  position: relative;
  z-index: 10;
}
@media (min-width: 768px) {
  .plans__container {
    justify-content: start;
    width: 766px;
    min-width: 766px;
    min-height: 558px;
    margin-top: -27px;
    margin-bottom: 0px;
    margin-left: auto;
    margin-right: auto;
    padding-top: 0px;
    padding-bottom: 0px;
    padding-left: 0px;
    padding-right: 0px;
    position: relative;
    z-index: 10;
  }
}
@media (min-width: 1440px) {
  .plans__container {
    display: flex;
    flex-direction: column;
    justify-content: start;
    width: 1438px;
    min-width: 1438px;
    min-height: 440px;
    margin-top: -27px;
    margin-bottom: 0px;
    margin-left: auto;
    margin-right: auto;
    padding: 54px 0px 0px 124px;
    border-top-left-radius: 50px;
    border-top-right-radius: 50px;
    box-sizing: border-box;
  }
}
.plans__title {
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 24px;
  line-height: 24px;
  color: #1D2E5B;
  margin-top: 21px;
  margin-left: 24px;
}
@media (min-width: 768px) {
  .plans__title {
    font-size: 36px;
    line-height: 36px;
    margin-top: 53px;
    margin-bottom: 50px;
    margin-left: 73px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .plans__title {
    font-style: normal;
    font-weight: bold;
    font-size: 36px;
    line-height: 36px;
    margin-top: -4px;
    margin-bottom: 35px;
    margin-left: 7px;
    margin-right: 0px;
  }
}
.plans__item {
  display: block;
  width: 270px;
  min-height: 108px;
  border-radius: 10px;
  background-color: #FFFFFF;
  align-self: center;
  margin-top: 0px;
  margin-bottom: 0px;
  padding-top: 21px;
  padding-bottom: 21px;
}
@media (min-width: 768px) {
  .plans__item {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    grid-template-rows: 2fr 1fr;
    white-space: nowrap;
    min-width: 618px;
    min-height: 153px;
    font-size: 24px;
    line-height: 24px;
    margin-top: 0px;
    margin-bottom: 10px;
    margin-left: auto;
    margin-right: auto;
    padding: 0px;
  }
}
@media (min-width: 1440px) {
  .plans__item {
    display: grid;
    grid-template-columns: 0.6fr 6fr 2fr 3fr 2fr;
    grid-template-rows: 1fr;
    align-self: flex-start;
    width: 1258px;
    min-height: 97px;
    margin-top: 16px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
    padding: 0px 0px 0px 0px;
    box-sizing: border-box;
  }
}
.plans__item-title {
  display: inline;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 16px;
  line-height: 16px;
  color: #1D2E5B;
}
@media (min-width: 768px) {
  .plans__item-title {
    grid-column-start: 1;
    grid-column-end: 3;
    grid-row-start: 1;
    font-size: 24px;
    line-height: 24px;
    margin-top: 39px;
    margin-bottom: 0px;
    margin-left: 36px;
    margin-right: 0px;
    padding: 0px;
  }
}
@media (min-width: 1440px) {
  .plans__item-title {
    grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 1;
    grid-row-end: 2;
    display: inline-block;
    font-style: normal;
    font-weight: bold;
    font-size: 24px;
    line-height: 24px;
    margin-top: auto;
    margin-bottom: auto;
    margin-left: 39px;
    margin-right: 0px;
    padding: 0px 0px 0px 0px;
  }
}
.plans__count {
  display: inline;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: 500;
  font-size: 16px;
  line-height: 16px;
  color: #1D2E5B;
  margin-left: 24px;
}
@media (min-width: 768px) {
  .plans__count {
    grid-column-start: 3;
    grid-column-end: 4;
    grid-row-start: 1;
    font-size: 20px;
    line-height: 20px;
    margin-top: 41px;
    margin-bottom: 0px;
    margin-left: 159px;
    margin-right: 0px;
    padding: 0px;
  }
}
@media (min-width: 1440px) {
  .plans__count {
    grid-column-start: 1;
    grid-column-end: 3;
    grid-row-start: 1;
    grid-row-end: 2;
    display: inline-block;
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 20px;
    margin-top: auto;
    margin-bottom: auto;
    margin-left: 42px;
    margin-right: 0px;
    padding: 0px 0px 0px 0px;
  }
}
.plans__number {
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: 500;
  font-size: 14px;
  line-height: 14px;
  letter-spacing: 0.06em;
  text-transform: uppercase;
  color: #1D2E5B;
  margin-top: 19px;
  margin-bottom: 0px;
  margin-left: 24px;
}
@media (min-width: 768px) {
  .plans__number {
    grid-column-start: 1;
    grid-row-start: 2;
    font-size: 21px;
    line-height: 20px;
    margin-top: 15px;
    margin-bottom: 0px;
    margin-left: 33px;
    margin-right: 0px;
    padding: 0px;
  }
}
@media (min-width: 1440px) {
  .plans__number {
    grid-column-start: 3;
    grid-column-end: 4;
    grid-row-start: 1;
    grid-row-end: 2;
    display: inline-block;
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 20px;
    letter-spacing: 0.09em;
    margin-top: auto;
    margin-bottom: auto;
    margin-left: 15px;
    margin-right: 0px;
    padding: 0px 0px 0px 0px;
  }
}
.plans__date {
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: 500;
  font-size: 14px;
  line-height: 14px;
  letter-spacing: 0.06em;
  text-transform: uppercase;
  color: #1D2E5B;
  margin-top: 5px;
  margin-bottom: 0px;
  margin-left: 24px;
}
@media (min-width: 768px) {
  .plans__date {
    grid-column-start: 2;
    grid-row-start: 2;
    font-size: 20px;
    line-height: 20px;
    margin-top: 14px;
    margin-bottom: 0px;
    margin-left: 14px;
    margin-right: 0px;
    padding: 0px;
  }
}
@media (min-width: 1440px) {
  .plans__date {
    grid-column-start: 4;
    grid-column-end: 5;
    grid-row-start: 1;
    grid-row-end: 2;
    display: inline-block;
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 20px;
    letter-spacing: 0.06em;
    margin-top: auto;
    margin-bottom: auto;
    margin-left: 8px;
    margin-right: 0px;
    padding: 0px 0px 0px 0px;
  }
}
.plans__button {
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: 500;
  font-size: 14px;
  line-height: 14px;
  text-align: center;
  letter-spacing: 0.03em;
  text-transform: uppercase;
  color: #000000;
  opacity: 0.3;
  border: none;
  background-color: transparent;
  margin-top: 23px;
  margin-bottom: 0px;
  margin-left: 19px;
}
@media (min-width: 768px) {
  .plans__button {
    grid-column-start: 3;
    grid-row-start: 2;
    font-size: 22px;
    line-height: 20px;
    margin-top: -3px;
    margin-bottom: 0px;
    margin-left: 32px;
    margin-right: 0px;
    padding: 0px;
  }
}
@media (min-width: 1440px) {
  .plans__button {
    grid-column-start: 5;
    grid-column-end: 6;
    grid-row-start: 1;
    grid-row-end: 2;
    display: inline-block;
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 20px;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 9px;
    padding: 0px 0px 0px 0px;
  }
}
.profile {
  min-width: 100%;
  width: 100%;
  background-color: #EDEFF6;
}
.profile__container {
  display: grid;
  grid-template-columns: 1fr 1fr;
  grid-template-rows: 1fr 1fr 1fr 0.6fr;
  min-width: 318px;
  width: 318px;
  min-height: 475px;
  margin-top: -25px;
  margin-left: auto;
  margin-right: auto;
  padding-top: 50px;
  padding-bottom: 0px;
  padding-left: 50px;
  padding-right: 25px;
  border-bottom-left-radius: 30px;
  border-bottom-right-radius: 30px;
  background-color: #EDEFF6;
  border: solid 1px transparent;
  position: relative;
  z-index: 6;
  box-sizing: border-box;
}
@media (min-width: 768px) {
  .profile__container {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr 1fr;
    grid-template-rows: 1fr 1fr 1fr 1fr;
    min-width: 766px;
    width: 766px;
    min-height: 605px;
    margin: -50px auto 0px auto;
    padding: 100px 0px 0px 0px;
    border-bottom-left-radius: 60px;
    border-bottom-right-radius: 60px;
  }
}
@media (min-width: 1440px) {
  .profile__container {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr 1fr;
    grid-template-rows: 1fr 1fr 1fr 1fr;
    min-width: 1438px;
    width: 1438px;
    min-height: 800px;
    margin-top: -50px;
    margin-bottom: 0px;
    margin-right: auto;
    margin-left: auto;
    padding: 0px 0px 0px 0px;
    border-bottom-left-radius: 50px;
    border-bottom-right-radius: 50px;
    position: relative;
    z-index: 6;
  }
}
.profile__title {
  grid-column-start: 1;
  grid-column-end: 2;
  grid-row-start: 1;
  grid-row-end: 2;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 24px;
  line-height: 24px;
  color: #FF8D30;
  margin-top: 24px;
}
@media (min-width: 768px) {
  .profile__title {
    grid-column-start: 1;
    grid-column-end: 5;
    grid-row-start: 1;
    grid-row-end: 2;
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: bold;
    font-size: 45px;
    line-height: 45px;
    color: #FF8D30;
    margin-top: 19px;
    margin-bottom: 0px;
    margin-left: 142px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .profile__title {
    grid-column-start: 2;
    grid-column-end: 4;
    grid-row-start: 1;
    grid-row-end: 3;
    margin-top: 152px;
    margin-bottom: 0px;
    margin-right: 0px;
    margin-left: 123px;
  }
}
.profile__rates {
  grid-column-start: 2;
  grid-column-end: 3;
  grid-row-start: 1;
  grid-row-end: 2;
  margin-top: 11px;
  margin-bottom: 0px;
  margin-left: 23px;
  margin-right: 0px;
  position: relative;
  z-index: 10;
}
@media (min-width: 768px) {
  .profile__rates {
    grid-column-start: 4;
    grid-column-end: 5;
    grid-row-start: 4;
    grid-row-end: 5;
    margin-top: -18px;
    margin-bottom: 0px;
    margin-right: 0px;
    margin-left: 7px;
  }
}
@media (min-width: 1440px) {
  .profile__rates {
    grid-column-start: 4;
    grid-column-end: 5;
    grid-row-start: 2;
    grid-row-end: 4;
    width: 198px;
    height: 198px;
    margin-top: 136px;
    margin-bottom: 0px;
    margin-right: 0px;
    margin-left: 28px;
  }
}
.profile__list {
  grid-column-start: 1;
  grid-column-end: 3;
  grid-row-start: 2;
  grid-row-end: 4;
  list-style: none;
  min-width: 244px;
  min-height: 192px;
  margin-top: 30px;
  margin-bottom: 0px;
  margin-left: 0px;
  margin-right: 0px;
  position: relative;
  z-index: 10;
}
@media (min-width: 768px) {
  .profile__list {
    grid-column-start: 1;
    grid-column-end: 5;
    grid-row-start: 2;
    grid-row-end: 4;
    min-width: auto;
    margin-top: 13px;
    margin-bottom: 0px;
    margin-left: 34px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .profile__list {
    grid-column-start: 1;
    grid-column-end: 5;
    grid-row-start: 2;
    grid-row-end: 4;
    margin-top: 135px;
    margin-bottom: 0px;
    margin-right: 0px;
    margin-left: 2px;
  }
}
.profile__item {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  grid-template-rows: 1fr 1fr;
  min-height: 56px;
}
@media (min-width: 768px) {
  .profile__item {
    display: grid;
    grid-template-columns: 0.15fr 1fr 0.5fr;
    grid-template-rows: 1fr;
    width: 657px;
    min-height: 70px;
    margin-top: 0px;
    margin-bottom: -3px;
    margin-right: 0px;
    margin-left: 0px;
  }
}
@media (min-width: 1440px) {
  .profile__item {
    display: grid;
    grid-template-columns: 0.15fr 1fr 0.5fr;
    grid-template-rows: 1fr;
    width: 907px;
    margin-top: -5px;
    margin-bottom: 0px;
    margin-right: 0px;
    margin-left: 125px;
    border: solid 1px transparent;
  }
}
.profile__item:nth-child(2) > .profile__list-number {
  background-color: #FFBD30;
}
.profile__item:nth-child(3) > .profile__list-number {
  background-color: #FFD74B;
}
.profile__list-text {
  grid-column-start: 1;
  grid-column-end: 4;
  grid-row-start: 1;
  display: inline-block;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: 300;
  font-size: 16px;
  line-height: 28px;
  color: #444444;
  margin-top: 0px;
  margin-bottom: 0px;
  margin-left: -1px;
  margin-right: 0px;
}
@media (min-width: 768px) {
  .profile__list-text {
    grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 1;
    grid-row-end: 2;
    font-style: normal;
    font-weight: 300;
    font-size: 28px;
    line-height: 69px;
    margin: 0px 0px 0px 22px;
    padding: 0px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .profile__list-text {
    grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 1;
    grid-row-end: 2;
    font-style: normal;
    font-weight: 300;
    font-size: 28px;
    line-height: 66px;
    margin: 0px 0px 0px 11px;
    padding: 0px 0px 0px 0px;
  }
}
.profile__list-price {
  grid-column-start: 1;
  grid-row-start: 2;
  display: inline-block;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: 300;
  font-size: 16px;
  line-height: 3px;
  color: #444444;
  margin-top: 0px;
  margin-bottom: 0px;
  margin-left: -2px;
  margin-right: 0px;
}
@media (min-width: 768px) {
  .profile__list-price {
    grid-column-start: 3;
    grid-column-end: 4;
    grid-row-start: 1;
    grid-row-end: 2;
    font-style: normal;
    font-weight: 300;
    font-size: 28px;
    line-height: 67px;
    margin: 0px 0px 0px auto;
    padding: 0px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .profile__list-price {
    font-style: normal;
    font-weight: 300;
    font-size: 28px;
    line-height: 67px;
    margin: 0px 0px 0px auto;
    padding: 0px 0px 0px 0px;
  }
}
.profile__list-number {
  grid-column-start: 3;
  grid-column-end: 4;
  grid-row-start: 1;
  display: inline-block;
  width: 34px;
  height: 34px;
  border-radius: 50px;
  font-family: "Blogger Sans";
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 35px;
  text-align: center;
  background-color: #FF8D30;
  color: #FFFFFF;
  margin-top: -1px;
  margin-bottom: 0px;
  margin-left: 46px;
  margin-right: 0px;
}
@media (min-width: 768px) {
  .profile__list-number {
    grid-column-start: 1;
    grid-column-end: 2;
    grid-row-start: 1;
    grid-row-end: 2;
    width: 68px;
    height: 68px;
    font-style: normal;
    font-weight: normal;
    font-size: 28px;
    line-height: 74px;
    margin: 0px 0px 0px 3px;
    padding: 0px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .profile__list-number {
    width: 68px;
    height: 68px;
    font-style: normal;
    font-weight: normal;
    font-size: 28px;
    line-height: 74px;
    margin: 0px 0px 0px 3px;
    padding: 0px 0px 0px 0px;
  }
}
.profile__button {
  grid-column-start: 1;
  grid-column-end: 3;
  grid-row-start: 4;
  grid-row-end: 5;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 16px;
  line-height: 16px;
  color: #132576;
  margin-top: 16px;
  margin-bottom: 0px;
  margin-left: -2px;
  margin-right: 0px;
  border: solid 1px transparent;
}
@media (min-width: 768px) {
  .profile__button {
    grid-column-start: 1;
    grid-column-end: 3;
    grid-row-start: 4;
    grid-row-end: 5;
    width: 360px;
    height: 68px;
    display: flex;
    flex-direction: row;
    justify-content: flex-end;
    align-items: center;
    font-style: normal;
    font-weight: bold;
    font-size: 20px;
    line-height: 20px;
    margin-top: -5px;
    margin-bottom: 0px;
    margin-left: 38px;
    margin-right: 0px;
    background-image: url("../assets/img/business-rates.png");
    background-repeat: no-repeat;
    background-position: 00%, 50%;
  }
}
@media (min-width: 1440px) {
  .profile__button {
    grid-column-start: 1;
    grid-column-end: 3;
    grid-row-start: 4;
    grid-row-end: 5;
    display: flex;
    flex-direction: row;
    justify-content: flex-end;
    align-items: center;
    font-style: normal;
    font-weight: bold;
    font-size: 20px;
    line-height: 20px;
    margin-top: -34px;
    margin-bottom: 0px;
    margin-left: 133px;
    margin-right: 0px;
    background-position: -1%, 50%;
    padding: 0px 0px 0px 0px;
  }
}
.profile__button:hover {
  opacity: 0.7;
}
.profile__button:active {
  opacity: 0.3;
}
.profile__modal {
  display: flex;
  flex-direction: column;
  position: absolute;
  z-index: 10;
  width: 270px;
  height: 443px;
  background-color: #FFFFFF;
  border: solid 1px transparent;
  border-radius: 20px;
  margin-bottom: 0px;
  align-self: center;
  transform: translate(8%, -1%);
}
@media (min-width: 768px) {
  .profile__modal {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    width: 688px;
    height: 526px;
    margin: 0px auto 0px auto;
    transform: translate(5%, 2%);
    border-radius: 20px;
  }
}
@media (min-width: 1440px) {
  .profile__modal {
    width: 750px;
    height: 526px;
    border-radius: 30px;
    transform: translate(46%, 4%);
  }
}
.profile__modal-title {
  display: block;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 24px;
  line-height: 24px;
  color: #FF8D30;
  text-align: center;
  border-bottom: 1px solid #F3F4F8;
  padding-bottom: 28px;
  margin-top: 33px;
  margin-bottom: 0px;
  margin-left: 25px;
  margin-right: 25px;
}
@media (min-width: 768px) {
  .profile__modal-title {
    font-style: normal;
    font-weight: bold;
    font-size: 45px;
    line-height: 82px;
  }
}
.profile__modal-close {
  width: 270px;
  height: 59px;
  background-color: #F3F4F8;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 16px;
  line-height: 24px;
  text-transform: uppercase;
  color: #1D2E5B;
  text-align: center;
  border-bottom-left-radius: 20px;
  border-bottom-right-radius: 20px;
  border: none;
  margin-top: 45px;
}
@media (min-width: 768px) {
  .profile__modal-close {
    width: 688px;
    height: 108px;
    font-style: normal;
    font-weight: bold;
    font-size: 24px;
    line-height: 24px;
    text-transform: none;
    margin-top: 49px;
  }
}
@media (min-width: 1440px) {
  .profile__modal-close {
    width: 749px;
    height: 106px;
    font-style: normal;
    font-weight: bold;
    font-size: 24px;
    line-height: 24px;
    text-transform: none;
    margin-top: 49px;
  }
}
.profile__cost-wrap {
  display: grid;
  grid-template-columns: 1fr;
  grid-template-rows: 16px 16px 16px 16px;
  border-bottom: 1px solid #F3F4F8;
}
@media (min-width: 768px) {
  .profile__cost-wrap {
    display: grid;
    grid-template-columns: 1fr 1fr;
    grid-template-rows: 1fr;
    height: 55px;
  }
}
@media (min-width: 1440px) {
  .profile__cost-wrap {
    margin: 0px 61px 0px 32px;
    padding: 0px 0px 0px 0px;
  }
}
.profile__modal-item {
  grid-row-start: 2;
  display: block;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: 300;
  font-size: 16px;
  line-height: 13px;
  color: #444444;
  margin-top: 0px;
  margin-bottom: 0px;
  margin-left: 25px;
  margin-right: 25px;
}
@media (min-width: 768px) {
  .profile__modal-item {
    grid-column-start: 1;
    grid-row-start: 1;
    font-size: 22px;
    line-height: 54px;
    padding: 0px 0px 0px 65px;
  }
}
@media (min-width: 1440px) {
  .profile__modal-item {
    padding: 0px 0px 0px 0px;
  }
}
.profile__modal-item-cost {
  grid-row-start: 3;
  display: block;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: 300;
  font-size: 16px;
  line-height: 22px;
  color: #444444;
  margin-top: 2px;
  margin-bottom: 0px;
  margin-left: 25px;
  margin-right: 25px;
}
@media (min-width: 768px) {
  .profile__modal-item-cost {
    grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 1;
    font-size: 22px;
    line-height: 54px;
    padding: 0px 94px 0px 66px;
    margin: 0px 0px 0px 0px;
    text-align: end;
  }
}
@media (min-width: 1440px) {
  .profile__modal-item-cost {
    padding: 0px 0px 0px 0px;
  }
}
.hidden {
  display: none;
}
::placeholder {
  color: #444444;
  opacity: 0.3;
}
.profile__shadow-plate {
  display: none;
}
@media (min-width: 768px) {
  .profile__shadow-plate {
    display: block;
    width: 198px;
    height: 285px;
    background-color: #E2E5F2;
    border-radius: 20px;
    position: absolute;
    transform: translate(263%, 69%);
    z-index: 9;
    margin: 0px;
    padding: 0px;
    border: solid 1px transparent;
  }
}
@media (min-width: 1440px) {
  .profile__shadow-plate {
    display: block;
    width: 446px;
    height: 300px;
    background-color: #E2E5F2;
    border-radius: 20px;
    position: absolute;
    transform: translate(167%, 94%);
    z-index: 9;
    margin: 0px;
    padding: 0px;
    border: solid 1px transparent;
  }
}
.reg {
  min-width: 100%;
  width: 100%;
  background-color: #192144;
}
.reg__container {
  display: flex;
  flex-direction: column;
  justify-self: start;
  min-width: 318px;
  width: 318px;
  min-height: 446px;
  margin-top: -20px;
  margin-left: auto;
  margin-right: auto;
  padding-top: 77px;
  background-color: #192144;
  border-bottom-left-radius: 30px;
  border-bottom-right-radius: 30px;
  position: relative;
  z-index: 5;
}
@media (min-width: 768px) {
  .reg__container {
    margin: -50px auto 0px auto;
    padding: 0px 0px 0px 0px;
    border-bottom-left-radius: 60px;
    border-bottom-right-radius: 60px;
    min-width: 766px;
    width: 766px;
    min-height: 765px;
  }
}
@media (min-width: 1440px) {
  .reg__container {
    min-width: 1438px;
    width: 1438px;
    min-height: 798px;
    padding: 0px 0px 0px 0px;
    margin-top: -48px;
    margin-bottom: 0px;
    margin-left: auto;
    margin-right: auto;
    border-bottom-left-radius: 50px;
    border-bottom-right-radius: 50px;
    position: relative;
    z-index: 5;
  }
}
.reg__title {
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 24px;
  line-height: 24px;
  color: #FF8D30;
  align-self: center;
  margin-top: 14px;
}
@media (min-width: 768px) {
  .reg__title {
    font-style: normal;
    font-weight: bold;
    font-size: 45px;
    line-height: 45px;
    margin-top: 122px;
    margin-bottom: 0px;
    margin-left: 2px;
    margin-right: 0px;
    padding: 0px;
  }
}
@media (min-width: 1440px) {
  .reg__title {
    padding: 0px 0px 0px 0px;
    margin: 153px 0px 0px 5px;
  }
}
.reg__quote {
  display: inline-block;
  width: 206px;
  height: 88px;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: 300;
  font-size: 16px;
  line-height: 22px;
  letter-spacing: 0.01em;
  color: #FFFFFF;
  text-align: center;
  align-self: center;
}
@media (min-width: 768px) {
  .reg__quote {
    display: inline-block;
    width: 638px;
    font-style: normal;
    font-weight: 300;
    font-size: 28px;
    line-height: 32px;
    text-align: center;
    letter-spacing: normal;
    margin-top: 61px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
    padding: 0px 0px 0px 20px;
    box-sizing: border-box;
  }
}
@media (min-width: 1440px) {
  .reg__quote {
    display: inline-block;
    width: 655px;
    height: 62px;
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: 300;
    font-size: 28px;
    line-height: 31px;
    text-align: center;
    padding: 0px 0px 0px 0px;
    margin: 59px 0px 0px 26px;
  }
}
.reg__quote .reg__quote-link {
  font-style: normal;
  font-weight: 300;
  font-size: 16px;
  line-height: 22px;
  color: #FFD74B;
  text-decoration: underline;
}
@media (min-width: 768px) {
  .reg__quote .reg__quote-link {
    font-style: normal;
    font-weight: 300;
    font-size: 28px;
    line-height: 32px;
  }
}
@media (min-width: 1440px) {
  .reg__quote .reg__quote-link {
    font-style: normal;
    font-weight: 300;
    font-size: 28px;
    line-height: 31px;
  }
}
.reg__quote .reg__quote-link:hover {
  color: #FF8D30;
}
.reg__quote .reg__quote-link:active {
  color: #FF8D30;
  opacity: 0.3;
}
.reg__button-wrapper {
  display: flex;
  align-self: center;
  margin-top: 29px;
  min-width: 270px;
}
@media (min-width: 768px) {
  .reg__button-wrapper {
    width: 614px;
    margin-top: 44px;
    margin-bottom: 0px;
    margin-left: -5px;
    margin-right: 0px;
    padding: 0px;
  }
}
@media (min-width: 1440px) {
  .reg__button-wrapper {
    width: 1174px;
    height: 81px;
    padding: 0px 0px 0px 0px;
    margin-top: 62px;
    margin-bottom: 0px;
    margin-left: 2px;
    margin-right: 0px;
  }
}
.reg__input {
  display: block;
  width: 100%;
  height: 62px;
  border-radius: 10px;
  border: none;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 18px;
  line-height: 18px;
  padding-left: 25px;
  outline: none;
  box-sizing: border-box;
}
@media (min-width: 768px) {
  .reg__input {
    font-style: normal;
    font-weight: bold;
    font-size: 24px;
    line-height: 24px;
    width: 500px;
    height: 80px;
    padding: 0px 0px 0px 37px;
    margin-top: -1px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
    border-bottom-left-radius: 20px;
    border-top-left-radius: 20px;
    border-bottom-right-radius: 0px;
    border-top-right-radius: 0px;
  }
}
@media (min-width: 1440px) {
  .reg__input {
    font-style: normal;
    font-weight: bold;
    font-size: 24px;
    line-height: 24px;
    width: 868px;
    height: 81px;
    padding: 0px 0px 0px 37px;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
    border-bottom-left-radius: 20px;
    border-top-left-radius: 20px;
    border-bottom-right-radius: 0px;
    border-top-right-radius: 0px;
  }
}
.reg__input:hover {
  color: rgba(0, 0, 0, 0.5);
}
.reg__input:active {
  background-color: #192144;
  color: #FFFFFF;
  box-shadow: inset 0px 0px 0px 4px #ffffff;
  box-sizing: border-box;
  opacity: 1;
}
.reg__button {
  position: relative;
  z-index: 1;
  margin-left: -44px;
  width: 62px;
  height: 62px;
  background-color: #FFD74B;
  border-radius: 10px;
  border: none;
  background-image: url("../assets/img/icon-btn-triangle.svg");
  background-repeat: no-repeat;
  background-position: center;
}
@media (min-width: 768px) {
  .reg__button {
    width: 80px;
    height: 80px;
    padding: 0px 0px 0px 0px;
    margin-top: -1px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: -2px;
    border-top-left-radius: 0px;
    border-bottom-left-radius: 0px;
    border-top-right-radius: 20px;
    border-bottom-right-radius: 20px;
    background-position: 51% 52%;
  }
}
@media (min-width: 1440px) {
  .reg__button {
    width: 330px;
    height: 81px;
    padding: 0px 0px 0px 0px;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
    border-top-left-radius: 0px;
    border-bottom-left-radius: 0px;
    border-top-right-radius: 20px;
    border-bottom-right-radius: 20px;
    background-position: 89%, 50%;
  }
}
.reg__btn-text {
  display: none;
}
@media (min-width: 768px) {
  .reg__btn-text {
    display: none;
  }
}
@media (min-width: 1440px) {
  .reg__btn-text {
    display: inline-block;
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: bold;
    font-size: 24px;
    line-height: 24px;
    color: #1D2E5B;
    margin: 0px 114px 0px 0px;
  }
}
.reg__button:hover {
  background-color: #FFBD30;
}
.reg__button:active,
.reg__btn-text:active {
  background-color: #FFBD30;
  color: rgba(0, 0, 0, 0.3);
}
.reg__more {
  display: inline-block;
  width: 216px;
  height: 44px;
  margin-top: 27px;
  margin-bottom: 17px;
  margin-left: auto;
  margin-right: auto;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: 300;
  font-size: 16px;
  line-height: 22px;
  letter-spacing: 0.01em;
  color: #FFFFFF;
  text-align: center;
  align-self: center;
}
@media (min-width: 768px) {
  .reg__more {
    display: inline-block;
    min-width: 614px;
    font-style: normal;
    font-weight: 300;
    font-size: 28px;
    line-height: 30px;
    margin-top: 58px;
    margin-bottom: 0px;
    margin-left: 6px;
    margin-right: 0px;
    padding: 0px;
  }
}
@media (min-width: 768px) and (min-width: 1440px) {
  .reg__more {
    font-style: normal;
    font-weight: 300;
    font-size: 28px;
    line-height: 30px;
    text-align: center;
    letter-spacing: 0.01em;
    margin: 68px 0px 0px -5px;
  }
}
.reg__contact-container {
  margin: 0px 0px 0px 0px;
}
@media (min-width: 768px) {
  .reg__contact-container {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: flex-start;
    width: 330px;
    margin: 29px 0px 0px 75px;
  }
}
@media (min-width: 1440px) {
  .reg__contact-container {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    width: 869px;
    margin: 32px 0px 0px 285px;
  }
}
.reg__contact-wrapper {
  display: flex;
  align-items: center;
  margin-left: 25px;
  cursor: pointer;
}
@media (min-width: 768px) {
  .reg__contact-wrapper {
    display: flex;
    align-items: center;
    width: auto;
    margin: 0px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .reg__contact-wrapper {
    display: flex;
    align-items: center;
    width: auto;
    margin: 0px 0px 0px 0px;
  }
}
.reg__tel-link {
  display: inline-block;
  width: 45px;
  height: 45px;
  border-radius: 50%;
  background-color: #121936;
}
@media (min-width: 768px) {
  .reg__tel-link {
    width: 68px;
    height: 68px;
    background-position: 50% 48%;
    background-size: 27px 27px;
    margin: 0px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .reg__tel-link {
    width: 90px;
    height: 90px;
    margin: 0px 0px 0px 0px;
    background-size: 33px 33px;
  }
}
.reg__mail-link {
  display: inline-block;
  width: 45px;
  height: 45px;
  border-radius: 50%;
  background-color: #121936;
}
@media (min-width: 768px) {
  .reg__mail-link {
    width: 68px;
    height: 68px;
    background-size: 29px 31px;
    margin: 0px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .reg__mail-link {
    width: 90px;
    height: 90px;
    background-size: 37px 37px;
    margin: 0px 0px 0px 0px;
  }
}
.reg__contact-text {
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 16px;
  line-height: 22px;
  color: #FFD74B;
  margin: 5px 0px 0px 16px;
  text-transform: uppercase;
}
@media (min-width: 768px) {
  .reg__contact-text {
    font-style: normal;
    font-weight: bold;
    font-size: 28px;
    line-height: 28px;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: 21px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .reg__contact-text {
    font-style: normal;
    font-weight: bold;
    font-size: 28px;
    line-height: 28px;
    color: #FFD74B;
    margin: 0px 0px 0px 33px;
  }
}
.reg__icon-tel {
  width: 16px;
  height: 15px;
  margin: 14px 0px 0px 9px;
}
@media (min-width: 768px) {
  .reg__icon-tel {
    width: 24px;
    height: 23px;
    margin: 20px 0px 0px 17px;
  }
}
@media (min-width: 1440px) {
  .reg__icon-tel {
    width: 32px;
    height: 30px;
    margin: 27px 0px 0px 24px;
  }
}
.reg__icon-mail {
  width: 19px;
  height: 13px;
  margin: 15px 0px 0px 8px;
}
@media (min-width: 768px) {
  .reg__icon-mail {
    width: 28px;
    height: 19px;
    margin: 23px 0px 0px 15px;
  }
}
@media (min-width: 1440px) {
  .reg__icon-mail {
    width: 37px;
    height: 25px;
    margin: 32px 0px 0px 22px;
  }
}
.reg__contact-wrapper:hover {
  color: #FFBD30;
  fill: #FFBD30;
}
.reg__contact-wrapper:active {
  opacity: 0.3;
}
.travelers {
  min-width: 100%;
  width: 100%;
  background-color: #192144;
}
.travelers__container {
  position: relative;
  z-index: 7;
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  min-width: 318px;
  width: 318px;
  min-height: 1271px;
  background-color: #192144;
  background-image: url(../assets/img/smolov-back-desktop@1x.png), url(../assets/img/rogovaya-back-mobile@1x.png);
  background-repeat: no-repeat, no-repeat;
  background-position: 152px 66px, -10px 337px;
  margin-top: -31px;
  margin-left: auto;
  margin-right: auto;
  padding-top: 75px;
  border: solid 1px transparent;
  border-bottom-left-radius: 30px;
  border-bottom-right-radius: 30px;
}
@media (min-width: 768px) {
  .travelers__container {
    display: grid;
    grid-template-columns: 1fr 1fr;
    grid-template-rows: 0.5fr 1fr 0.5fr 1fr 1fr 1fr;
    min-width: 766px;
    width: 766px;
    min-height: 1304px;
    border-bottom-left-radius: 60px;
    border-bottom-right-radius: 60px;
    background-image: url(../assets/img/smolov-back-desktop@2x.png), url(../assets/img/rogovaya-back-desktop@2x.png);
    background-repeat: no-repeat, no-repeat;
    background-position: 40px 474px, 409px 130px;
    background-size: 143px 143px, 285px 285px;
    margin-top: -50px;
    margin-left: auto;
    margin-right: auto;
    padding-top: 125px;
    padding-left: 74px;
    box-sizing: border-box;
  }
}
@media (min-width: 1440px) {
  .travelers__container {
    display: grid;
    grid-template-columns: 1fr 0.5fr 0.5fr;
    grid-template-rows: 1fr 1fr 1fr 0.5fr;
    min-width: 1438px;
    width: 1438px;
    min-height: 811px;
    background-image: url(../assets/img/smolov-back-desktop@2x.png), url(../assets/img/rogovaya-back-desktop@2x.png);
    background-repeat: no-repeat, no-repeat;
    background-position: 542px 192px, 186px 444px;
    background-size: 143px 143px, 285px 285px;
    padding: 0px 0px 0px 0px;
    margin: -60px auto 0px auto;
  }
}
.travelers__title {
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 24px;
  line-height: 24px;
  color: #FF8D30;
  margin-top: 22px;
  margin-left: 48px;
}
@media (min-width: 768px) {
  .travelers__title {
    grid-column-start: 1;
    grid-row-start: 1;
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: bold;
    font-size: 45px;
    line-height: 45px;
    color: #FF8D30;
    margin-top: 61px;
    margin-bottom: 0px;
    margin-left: -4px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .travelers__title {
    grid-column-start: 1;
    grid-column-end: 2;
    grid-row-start: 1;
    grid-row-end: 3;
    padding: 0px 0px 0px 0px;
    margin: 185px 0px 0px 129px;
  }
}
.travelers__quote {
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: 300;
  font-size: 16px;
  line-height: 22px;
  color: #FFFFFF;
  margin-top: 0px;
  margin-left: 49px;
  margin-right: 50px;
}
@media (min-width: 768px) {
  .travelers__quote {
    grid-column-start: 1;
    grid-column-end: 3;
    grid-row-start: 2;
    display: inline-block;
    width: 470px;
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: 300;
    font-size: 28px;
    line-height: 34px;
    color: #FFFFFF;
    margin-top: 45px;
    margin-bottom: 0px;
    margin-left: -2px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .travelers__quote {
    grid-column-start: 1;
    grid-row-start: 2;
    display: inline-block;
    width: 427px;
    font-style: normal;
    font-weight: 300;
    font-size: 28px;
    line-height: 33px;
    padding: 0px 0px 0px 0px;
    margin: 56px 0px 0px 131px;
  }
}
.travelers__slogan {
  display: inline-block;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 16px;
  line-height: 22px;
  color: #FFFFFF;
  margin-top: 5px;
  margin-bottom: 45px;
  margin-left: 48px;
}
@media (min-width: 768px) {
  .travelers__slogan {
    grid-column-start: 1;
    grid-row-start: 3;
    display: inline-block;
    width: 260px;
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: bold;
    font-size: 21px;
    line-height: 24px;
    color: #FFFFFF;
    margin-top: -15px;
    margin-bottom: 0px;
    margin-left: -2px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .travelers__slogan {
    grid-column-start: 1;
    grid-row-start: 3;
    display: inline-block;
    width: 260px;
    height: 48px;
    font-style: normal;
    font-weight: bold;
    font-size: 21px;
    line-height: 24px;
    padding: 0px 0px 0px 0px;
    margin: -1px 0px 0px 130px;
  }
}
.travelers__item {
  display: flex;
  flex-direction: column;
  align-items: center;
  width: 270px;
  min-height: 428px;
  align-self: center;
  margin-top: 9px;
  background-color: #FFFFFF;
  border-radius: 10px;
  cursor: pointer;
}
@media (min-width: 768px) {
  .travelers__item {
    width: 285px;
    height: 483px;
    border-radius: 20px;
  }
}
@media (min-width: 1440px) {
  .travelers__item {
    width: 285px;
    height: 483px;
    padding: 0px 0px 0px 0px;
    margin: 0px 0px 0px 0px;
    border-radius: 20px;
  }
}
@media (min-width: 768px) {
  .travelers__item-left {
    grid-column-start: 1;
    grid-row-start: 4;
    grid-row-end: 6;
    margin-top: -36px;
    margin-bottom: 0px;
    margin-left: -3px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .travelers__item-left {
    grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 1;
    grid-row-end: 5;
    padding: 0px 0px 0px 0px;
    margin: 60px 0px 0px 31px;
  }
}
@media (min-width: 768px) {
  .travelers__item-left > .travelers__name {
    padding: 0px 0px 0px 0px;
    margin: 18px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .travelers__item-left > .travelers__name {
    padding: 0px 0px 0px 0px;
    margin: 17px 0px 0px 2px;
  }
}
@media (min-width: 768px) {
  .travelers__item-right {
    grid-column-start: 2;
    grid-row-start: 4;
    grid-row-end: 6;
    margin-top: -35px;
    margin-bottom: 0px;
    margin-left: -14px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .travelers__item-right {
    grid-column-start: 3;
    grid-column-end: 4;
    grid-row-start: 1;
    grid-row-end: 5;
    padding: 0px 0px 0px 0px;
    margin: 60px 0px 0px 17px;
  }
}
@media (min-width: 768px) {
  .travelers__item-right > .travelers__hobbies {
    display: inline-block;
    width: 184px;
    height: 46px;
    padding: 0px 0px 0px 0px;
    margin: 24px 0px 0px 0px;
  }
}
@media (min-width: 320px) {
  .travelers__item:hover {
    filter: drop-shadow(0px 4px 9px rgba(0, 0, 0, 0.16));
  }
}
.travelers__preferences {
  display: flex;
  justify-content: space-between;
  width: auto;
  margin-top: -14px;
}
@media (min-width: 768px) {
  .travelers__preferences {
    margin: -12px 0px 0px 0px;
    padding: 0px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .travelers__preferences {
    margin: -11px 0px 0px 0px;
    padding: 0px 0px 0px 0px;
  }
}
.travelers__preferences img {
  margin-left: 20px;
}
.travelers__preferences img:first-child {
  margin-left: 0px;
}
.travelers__button {
  display: block;
  width: 270px;
  height: 61px;
  align-self: center;
  margin-top: 20px;
  background-color: #FFD74B;
  border-radius: 10px;
  background-image: url("../assets/img/icon-btn-triangle.svg");
  background-repeat: no-repeat;
  background-position: 92% 52%;
}
@media (min-width: 768px) {
  .travelers__button {
    grid-column-start: 1;
    grid-column-end: 3;
    grid-row-start: 6;
    width: 616px;
    height: 80px;
    border-radius: 20px;
    margin-top: -17px;
    margin-bottom: 0px;
    margin-left: -1px;
    margin-right: 0px;
    background-position: 94% 52%;
  }
}
@media (min-width: 1440px) {
  .travelers__button {
    grid-column-start: 1;
    grid-row-start: 4;
    width: 280px;
    height: 80px;
    padding: 0px 0px 0px 0px;
    margin: -230px 0px 0px 131px;
    background-position: 87% 52%;
  }
}
.travelers__btn-text {
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 18px;
  line-height: 60px;
  color: #1D2E5B;
  margin-left: 24px;
}
@media (min-width: 768px) {
  .travelers__btn-text {
    font-style: normal;
    font-weight: bold;
    font-size: 24px;
    line-height: 77px;
    padding: 0px 0px 0px 0px;
    margin: 0px 0px 0px 32px;
  }
}
@media (min-width: 1440px) {
  .travelers__btn-text {
    font-style: normal;
    font-weight: bold;
    font-size: 24px;
    line-height: 77px;
    padding: 0px 0px 0px 0px;
    margin: 0px 0px 0px 34px;
  }
}
.travelers__button:hover {
  background-color: #FFBD30;
}
.travelers__button:active,
.travelers__btn-text:active {
  background-color: #FFBD30;
  color: rgba(0, 0, 0, 0.3);
}
.travelers__name {
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 21px;
  line-height: 21px;
  color: #1D2E5B;
  margin-top: 11px;
  margin-left: -25px;
}
@media (min-width: 768px) {
  .travelers__name {
    font-style: normal;
    font-weight: bold;
    font-size: 24px;
    line-height: 22px;
    padding: 0px 0px 0px 0px;
    margin: 18px 0px 0px -21px;
  }
}
@media (min-width: 1440px) {
  .travelers__name {
    font-style: normal;
    font-weight: bold;
    font-size: 24px;
    line-height: 22px;
    padding: 0px 0px 0px 0px;
    margin: 17px 0px 0px -21px;
  }
}
.travelers__name::before {
  content: "";
  display: inline-block;
  width: 6px;
  height: 6px;
  background-color: #F97676;
  border-radius: 50%;
  margin: 3px 10px;
}
@media (min-width: 768px) {
  .travelers__name::before {
    width: 8px;
    height: 8px;
    position: absolute;
    transform: translate(-247%, 113%);
    padding: 0px 0px 0px 0px;
    margin: 0px 6px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .travelers__name::before {
    padding: 0px 0px 0px 0px;
    margin: 0px 0px 0px 0px;
  }
}
.travelers__hobbies {
  display: inline-block;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 18px;
  color: #444444;
  margin-top: -5px;
  margin-bottom: 0px;
  margin-left: 40px;
  margin-right: 40px;
  text-align: center;
}
@media (min-width: 768px) {
  .travelers__hobbies {
    font-style: normal;
    font-weight: normal;
    font-size: 20px;
    line-height: 23px;
    text-align: center;
    padding: 0px 0px 0px 0px;
    margin: 25px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .travelers__hobbies {
    font-style: normal;
    font-weight: normal;
    font-size: 20px;
    line-height: 23px;
    text-align: center;
    padding: 0px 0px 0px 0px;
    margin: 25px 0px 0px 0px;
  }
}
.travelers__level-firsova {
  position: absolute;
  width: 60px;
  height: 60px;
  transform: translate(-143%, 27%);
  background-image: url("../assets/img/travelers-level-firsova.svg");
  background-repeat: no-repeat;
  background-position: center;
}
@media (min-width: 768px) {
  .travelers__level-firsova {
    transform: translate(-151%, 34%);
  }
}
.travelers__level-demin {
  position: absolute;
  width: 60px;
  height: 60px;
  transform: translate(-143%, 27%);
  background-image: url("../assets/img/travelers-level-demin.svg");
  background-repeat: no-repeat;
  background-position: center;
}
@media (min-width: 768px) {
  .travelers__level-demin {
    transform: translate(-151%, 34%);
  }
}
.travelers__avatar {
  margin: 0px 0px 0px 0px;
}
@media (min-width: 768px) {
  .travelers__avatar {
    width: 285px;
    height: 284px;
    padding: 0px 0px 0px 0px;
    margin: 0px 0px 0px 0px;
    border-top-left-radius: 20px;
    border-top-right-radius: 20px;
  }
}
@media (min-width: 1440px) {
  .travelers__avatar {
    width: 285px;
    height: 284px;
    padding: 0px 0px 0px 0px;
    margin: 0px 0px 0px 0px;
  }
}
.travelers__pictire {
  width: 270px;
  height: 270px;
  border-top-left-radius: 10px;
  border-top-right-radius: 10px;
}
@media (min-width: 768px) {
  .travelers__pictire {
    width: 285px;
    height: 284px;
    padding: 0px 0px 0px 0px;
    margin: 0px 0px 0px 0px;
    border-top-left-radius: 20px;
    border-top-right-radius: 20px;
  }
}
@media (min-width: 1440px) {
  .travelers__pictire {
    width: 285px;
    height: 284px;
    padding: 0px 0px 0px 0px;
    margin: 0px 0px 0px 0px;
  }
}
.travelers__transport {
  display: flex;
  justify-content: space-between;
  width: 126px;
  margin-top: 15px;
  margin-left: 0px;
}
@media (min-width: 768px) {
  .travelers__transport {
    padding: 0px 0px 0px 0px;
    margin: 26px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .travelers__transport {
    padding: 0px 0px 0px 0px;
    margin: 26px 0px 0px 0px;
  }
}
.travelers__plane-icon {
  display: block;
  width: 24px;
  height: 24px;
}
.travelers__bus-icon {
  display: block;
  width: 24px;
  height: 24px;
}
.travelers__bike-icon {
  display: block;
  width: 24px;
  height: 24px;
}
.travelers__run-icon {
  display: block;
  width: 24px;
  height: 24px;
}
.travelers__name:hover {
  opacity: 0.7;
}
.travelers__name:active {
  opacity: 0.3;
}
.filter {
  min-width: 100%;
  width: 100%;
  background-color: #E5E5E5;
}
@media (min-width: 1440px) {
  .filter {
    background-color: transparent;
  }
}
.filter__container {
  min-width: 320px;
  width: 320px;
  margin-top: -36px;
  margin-bottom: 0px;
  margin-left: auto;
  margin-right: auto;
  background-color: #E5E5E5;
  padding-top: 36px;
  min-height: 662px;
}
@media (min-width: 768px) {
  .filter__container {
    min-width: 768px;
    width: 768px;
    background-color: #E5E5E5;
    min-height: 602px;
    margin: -50px auto 0px auto;
    padding: 51px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .filter__container {
    min-width: 1440px;
    width: 1440px;
    margin: -25px auto 0px auto;
    padding: 0px 0px 0px 1098px;
    background-color: transparent;
    position: relative;
    z-index: 10;
    box-sizing: border-box;
  }
}
.filter__form {
  display: flex;
  flex-direction: column;
  justify-content: start;
  width: 270px;
  min-height: 622px;
  margin: 0 auto;
  margin-top: 21px;
  margin-bottom: 0px;
  background-color: #FFD74B;
  border: solid 1px transparent;
  border-radius: 20px;
  padding-left: 25px;
  padding-right: 25px;
  padding-bottom: 21px;
  box-sizing: border-box;
}
@media (min-width: 768px) {
  .filter__form {
    min-width: 686px;
    min-height: 550px;
    padding-left: 21px;
    padding-right: 25px;
    margin: 39px auto 0px auto;
    box-sizing: border-box;
  }
}
@media (min-width: 1440px) {
  .filter__form {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    min-width: 285px;
    width: 285px;
    min-height: 814px;
    margin: 0px 0px 0px -2px;
    padding: 0px 0px 0px 0px;
    box-sizing: border-box;
  }
}
.filter__button {
  width: 230px;
  height: 41px;
  background: #FFFFFF;
  border-radius: 25px;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 17px;
  line-height: 17px;
  text-align: center;
  text-transform: uppercase;
  color: #161C35;
  align-self: center;
  border: none;
  margin-top: 13px;
}
@media (min-width: 768px) {
  .filter__button {
    font-style: normal;
    font-weight: bold;
    font-size: 20px;
    line-height: 20px;
    min-width: 617px;
    height: 50px;
    margin-top: 91px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .filter__button {
    min-width: auto;
    width: 194px;
    height: 49px;
    padding: 0px 0px 0px 0px;
    margin-top: 32px;
    margin-bottom: 47px;
    margin-left: 6px;
    margin-right: 0px;
    box-sizing: border-box;
  }
}
.filter__title {
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 22px;
  line-height: 22px;
  letter-spacing: 0.02em;
  color: #1D2E5B;
  margin-top: 23px;
  margin-bottom: 24px;
}
@media (min-width: 768px) {
  .filter__title {
    font-style: normal;
    font-weight: bold;
    font-size: 30px;
    line-height: 30px;
    letter-spacing: normal;
    margin-top: 34px;
    margin-bottom: 20px;
    margin-left: 10px;
    margin-right: 0px;
    padding: 0px 0px 39px 0px;
    border-bottom: solid 1px #F3C72B;
  }
}
@media (min-width: 1440px) {
  .filter__title {
    font-style: normal;
    font-weight: bold;
    font-size: 29px;
    line-height: 30px;
    border: none;
    margin: 43px 0px 33px 47px;
    padding: 0px 0px 0px 0px;
  }
}
.filter__item {
  border-top: solid 1px #F3C72B;
}
@media (min-width: 768px) {
  .filter__item {
    display: grid;
    grid-template-columns: 0.7fr 3fr;
    grid-template-rows: 1fr;
    border: none;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: 9px;
    margin-right: 0px;
    height: 49px;
    border: solid 1px transparent;
  }
}
@media (min-width: 1440px) {
  .filter__item {
    display: grid;
    grid-template-columns: 1fr 1fr;
    grid-template-rows: 1fr 4fr;
    height: 156px;
    margin: 0px 0px 22px 0px;
    padding: 0px 0px 0px 0px;
    box-sizing: border-box;
    border: solid 1px transparent;
  }
}
.filter__item-transport {
  margin-bottom: 20px;
}
@media (min-width: 1440px) {
  .filter__item-transport {
    display: grid;
    grid-template-columns: 1fr;
    grid-template-rows: 1fr 2fr;
    height: 100px;
    margin: 0px 0px 0px 0px;
    padding: 0px 0px 0px 0px;
    border: solid 1px transparent;
    box-sizing: border-box;
  }
}
@media (min-width: 768px) {
  .filter__item-transport .filter__sort-transport {
    display: flex;
    justify-content: flex-start;
  }
}
@media (min-width: 1440px) {
  .filter__item-transport .filter__sort-transport {
    display: flex;
    flex-direction: row;
    justify-content: flex-start;
    align-items: center;
    margin: -19px 0px 0px 42px;
    padding: 0px 0px 0px 0px;
  }
}
.filter__item-wrap {
  display: flex;
  justify-content: space-between;
}
@media (min-width: 768px) {
  .filter__item-wrap {
    grid-column-start: 1;
    grid-column-end: 2;
    grid-row-start: 1;
    grid-row-end: 2;
  }
}
@media (min-width: 1440px) {
  .filter__item-wrap {
    grid-column-start: 1;
    grid-column-end: 3;
    grid-row-start: 1;
    grid-row-end: 2;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    min-width: 190px;
    margin: 0px 0px 20px 0px;
    padding: 0px 0px 0px 0px;
    box-sizing: border-box;
    border: solid 1px transparent;
  }
}
@media (min-width: 1440px) {
  .filter__item-wrap-range {
    margin: 0px 0px 0px 0px;
    padding: 0px 0px 0px 0px;
    box-sizing: border-box;
  }
}
.filter__item-title {
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 16px;
  line-height: 18px;
  text-transform: uppercase;
  color: #1D2E5B;
  margin-top: 11px;
  margin-bottom: 10px;
}
@media (min-width: 768px) {
  .filter__item-title {
    display: block;
    height: 20px;
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 46px;
    margin-top: 1px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .filter__item-title {
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 22px;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: 47px;
    margin-right: 0px;
  }
}
@media (min-width: 768px) {
  .filter__item-title-transport {
    margin: 8px 0px 0px -2px;
    padding: 0px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .filter__item-title-transport {
    margin: 0px 0px 0px 45px;
    padding: 0px 0px 0px 0px;
  }
}
@media (min-width: 768px) {
  .filter__item-title-level {
    margin: 14px 0px 0px -2px;
    padding: 0px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .filter__item-title-level {
    margin: 0px 0px 0px 46px;
    padding: 0px 0px 0px 0px;
  }
}
.filter__toggle-btn {
  width: 20px;
  height: 20px;
  background-image: url("../assets/img/filter-btn-arrow.svg");
  background-repeat: no-repeat;
  background-position: center;
  border: none;
  background-color: transparent;
  background-size: 10px 6px;
  margin-top: 10px;
  margin-right: -7px;
}
@media (min-width: 768px) {
  .filter__toggle-btn {
    display: none;
  }
}
@media (min-width: 1440px) {
  .filter__toggle-btn {
    display: block;
    margin: 0px 39px 0px 0px;
    padding: 0px 0px 0px 0px;
  }
}
.filter__sort {
  border: none;
  padding: 0px;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: normal;
  font-size: 15px;
  line-height: 20px;
  color: #000000;
}
@media (min-width: 768px) {
  .filter__sort {
    grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 1;
    grid-row-end: 2;
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    grid-template-rows: 1fr;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
    border: solid 1px transparent;
  }
}
@media (min-width: 1440px) {
  .filter__sort {
    grid-column-start: 1;
    grid-column-end: 3;
    grid-row-start: 2;
    grid-row-end: 3;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: flex-start;
    margin: 0px 0px 0px 0px;
    padding: 0px 0px 0px 0px;
  }
}
.filter__sort label {
  display: block;
  cursor: pointer;
}
.filter__sort .filter__btn-plane {
  display: inline-block;
  width: 32px;
  height: 32px;
  border-radius: 50%;
  background-color: #FFFFFF;
  border: none;
  background-image: url("../assets/img/transport-plane.svg");
  background-repeat: no-repeat;
  background-position: center;
  cursor: pointer;
  margin-top: 5px;
  margin-left: -2px;
}
@media (min-width: 768px) {
  .filter__sort .filter__btn-plane {
    width: 44px;
    height: 44px;
    background-image: url("../assets/img/transport-plane-tablet.svg");
    background-repeat: no-repeat;
    background-position: center;
    margin: 5px 0px 0px 0px;
    padding: 0px 0px 0px 0px;
  }
}
.filter__sort .filter__btn-bus {
  display: inline-block;
  width: 32px;
  height: 32px;
  border-radius: 50%;
  background-color: #FFFFFF;
  border: none;
  background-image: url("../assets/img/transport-bus.svg");
  background-repeat: no-repeat;
  background-position: center;
  cursor: pointer;
  margin-top: 5px;
  margin-left: -4px;
}
@media (min-width: 768px) {
  .filter__sort .filter__btn-bus {
    width: 44px;
    height: 44px;
    background-image: url(../assets/img/bus.svg);
    background-repeat: no-repeat;
    background-position: center;
    background-size: 19px;
    margin: 5px 0px 0px 0px;
    padding: 0px 0px 0px 0px;
  }
}
.filter__sort .filter__btn-bike {
  display: inline-block;
  width: 32px;
  height: 32px;
  border-radius: 50%;
  background-color: #FFFFFF;
  border: none;
  background-image: url("../assets/img/transport-bike.svg");
  background-repeat: no-repeat;
  background-position: center;
  cursor: pointer;
  margin-top: 5px;
  margin-left: -6px;
}
@media (min-width: 768px) {
  .filter__sort .filter__btn-bike {
    width: 44px;
    height: 44px;
    background-image: url("../assets/img/transport-bike-tablet.svg");
    background-repeat: no-repeat;
    background-position: center;
    margin: 5px 0px 0px 0px;
    padding: 0px 0px 0px 0px;
  }
}
.filter__sort .filter__btn-run {
  display: inline-block;
  width: 32px;
  height: 32px;
  border-radius: 50%;
  background-color: #FFFFFF;
  border: none;
  background-image: url("../assets/img/transport-run.svg");
  background-repeat: no-repeat;
  background-position: center;
  cursor: pointer;
  margin-top: 5px;
  margin-left: -2px;
}
@media (min-width: 768px) {
  .filter__sort .filter__btn-run {
    width: 44px;
    height: 44px;
    background-image: url("../assets/img/transport-run-tablet.svg");
    background-repeat: no-repeat;
    background-position: center;
    margin: 5px 0px 0px 0px;
    padding: 0px 0px 0px 0px;
  }
}
.filter__checkbox {
  display: none;
}
.filter__range-input {
  display: inline-block;
  width: 110px;
  height: 34px;
  background-color: #FFFFFF;
  border: 1px solid #CBCED9;
  box-sizing: border-box;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: 500;
  font-size: 14px;
  line-height: 13px;
  letter-spacing: 0.06em;
  color: #1D2E5B;
  text-align: center;
}
@media (min-width: 1440px) {
  .filter__range-input {
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 20px;
    letter-spacing: 0.05em;
    color: #1D2E5B;
  }
}
.filter__range-input:first-child {
  border-bottom-left-radius: 4px;
  border-top-left-radius: 4px;
}
@media (min-width: 768px) {
  .filter__range-input:first-child {
    width: 74px;
    height: 46px;
    margin: 0px 0px 0px 0px;
    padding: 0px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .filter__range-input:first-child {
    width: 100%;
    height: 100%;
    margin: 0px 0px 0px 0px;
    padding: 0px 0px 0px 0px;
  }
}
.filter__range-input:last-child {
  border-bottom-right-radius: 4px;
  border-top-right-radius: 4px;
}
@media (min-width: 768px) {
  .filter__range-input:last-child {
    width: 74px;
    height: 46px;
    margin: 0px 0px 0px 0px;
    padding: 0px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .filter__range-input:last-child {
    width: 100%;
    height: 100%;
    margin: 0px 0px 0px 0px;
    padding: 0px 0px 0px 0px;
  }
}
@media (min-width: 768px) {
  .filter__item-range {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-top: -28px;
    margin-bottom: 0px;
    margin-left: 10px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .filter__item-range {
    display: grid;
    grid-template-columns: 1fr;
    grid-template-rows: 1fr 2fr;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
  }
}
@media (min-width: 768px) {
  .filter__item-range .filter__sort-range {
    display: flex;
    align-items: center;
    width: 500px;
  }
}
@media (min-width: 1440px) {
  .filter__item-range .filter__sort-range {
    grid-column-start: 1;
    grid-column-end: 2;
    grid-row-start: 2;
    grid-row-end: 3;
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
    width: auto;
    height: auto;
  }
}
.filter__range {
  width: 220px;
  height: 12px;
  margin-top: 24px;
  border: solid 1px transparent;
}
@media (min-width: 768px) {
  .filter__range {
    width: 270px;
    order: 2;
    margin: 48px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .filter__range {
    width: 193px;
    order: 3;
    margin-top: 5px;
    margin-bottom: -6px;
    margin-left: 0px;
    margin-right: 0px;
  }
}
.filter__range-line-one {
  position: absolute;
  transform: translate(-2%, 0%);
  width: 220px;
  height: 2px;
  background-color: #1D2E5B;
  opacity: 0.2;
}
@media (min-width: 768px) {
  .filter__range-line-one {
    position: absolute;
    transform: translate(0%, 0%);
    width: 220px;
    height: 2px;
    background-color: #1D2E5B;
    opacity: 0.2;
  }
}
@media (min-width: 1440px) {
  .filter__range-line-one {
    position: absolute;
    transform: translate(0%, 0%);
    width: 192px;
    height: 2px;
    background-color: #1D2E5B;
    opacity: 0.2;
  }
}
.filter__range-line-two {
  position: absolute;
  transform: translate(53%, 0%);
  width: 138px;
  height: 2px;
  background-color: #1D2E5B;
}
@media (min-width: 768px) {
  .filter__range-line-two {
    position: absolute;
    transform: translate(40%, 0%);
    width: 200px;
    height: 2px;
    background-color: #1D2E5B;
  }
}
@media (min-width: 1440px) {
  .filter__range-line-two {
    position: absolute;
    transform: translate(59%, 0%);
    width: 120px;
    height: 2px;
    background-color: #1D2E5B;
  }
}
.filter__btn-min {
  position: absolute;
  transform: translate(532%, -33%);
  width: 10px;
  height: 10px;
  border-radius: 50%;
  background-color: #1D2E5B;
  border: none;
}
@media (min-width: 768px) {
  .filter__btn-min {
    position: absolute;
    transform: translate(489%, -50%);
    width: 14px;
    height: 14px;
    border-radius: 50%;
    background-color: #1D2E5B;
    border: none;
  }
}
@media (min-width: 1440px) {
  .filter__btn-min {
    position: absolute;
    transform: translate(465%, -33%);
    width: 13px;
    height: 13px;
    border-radius: 50%;
    background-color: #1D2E5B;
    border: none;
  }
}
.filter__btn-max {
  position: absolute;
  transform: translate(1717%, -33%);
  width: 10px;
  height: 10px;
  border-radius: 50%;
  background-color: #1D2E5B;
  border: none;
}
@media (min-width: 768px) {
  .filter__btn-max {
    position: absolute;
    transform: translate(1917%, -50%);
    width: 14px;
    height: 14px;
    border-radius: 50%;
    background-color: #1D2E5B;
    border: none;
  }
}
@media (min-width: 1440px) {
  .filter__btn-max {
    position: absolute;
    transform: translate(1380%, -45%);
    width: 13px;
    height: 13px;
    border-radius: 50%;
    background-color: #1D2E5B;
    border: none;
  }
}
.filter__range-wrap {
  display: flex;
  margin-top: 2px;
  margin-left: -3px;
}
@media (min-width: 768px) {
  .filter__range-wrap {
    order: 3;
    width: 148px;
    height: 46px;
    margin: 40px 0px 0px 70px;
  }
}
@media (min-width: 1440px) {
  .filter__range-wrap {
    order: 2;
    width: 193px;
    height: 46px;
    margin: 0px 0px 30px 0px;
  }
}
.filter__range-split {
  position: absolute;
  transform: translate(419%, -139%);
  width: 21px;
  height: 17px;
  background-color: #FFFFFF;
  background-image: url(../assets/img/split.svg);
  background-repeat: no-repeat;
  background-position: center;
  border: solid 1px transparent;
}
@media (min-width: 768px) {
  .filter__range-split {
    position: absolute;
    transform: translate(1768%, 108%);
    width: 21px;
    height: 17px;
    background-color: #FFFFFF;
    background-image: url(../assets/img/split.svg);
    background-repeat: no-repeat;
    background-position: center;
    border: solid 1px transparent;
  }
}
@media (min-width: 1440px) {
  .filter__range-split {
    position: absolute;
    transform: translate(8%, 53%);
    width: 21px;
    height: 17px;
    background-color: #FFFFFF;
    background-image: url(../assets/img/split.svg);
    background-repeat: no-repeat;
    background-position: center;
    border: solid 1px transparent;
  }
}
.filter__checkbox-wrap {
  display: flex;
  margin-top: 11px;
  margin-bottom: 10px;
  margin-left: -4px;
  cursor: pointer;
}
@media (min-width: 768px) {
  .filter__checkbox-wrap {
    display: flex;
    flex-direction: row;
    justify-content: flex-start;
    align-items: center;
    grid-column-start: auto;
    grid-row-start: auto;
    margin: 0px 0px 0px 7px;
    border: solid 1px transparent;
  }
}
@media (min-width: 1440px) {
  .filter__checkbox-wrap {
    display: flex;
    flex-direction: row;
    justify-content: flex-start;
    align-items: center;
    margin: 1px 0px 0px 46px;
    border: solid 1px transparent;
  }
}
.filter__checkbox-wrap:last-child {
  margin-bottom: 18px;
}
@media (min-width: 768px) {
  .filter__checkbox-wrap:last-child {
    margin: 0px 0px 0px 9px;
  }
}
@media (min-width: 1440px) {
  .filter__checkbox-wrap:last-child {
    display: flex;
    flex-direction: row;
    justify-content: flex-start;
    align-items: center;
    margin: 0px 0px 3px 46px;
    border: solid 1px transparent;
  }
}
.filter__check-on {
  width: 20px;
  height: 20px;
  background-image: url("../assets/img/checkbox-on.png");
  background-repeat: no-repeat;
  background-position: center;
  margin-top: -8px;
  margin-left: 0px;
}
@media (min-width: 768px) {
  .filter__check-on {
    width: 24px;
    height: 24px;
    background-image: url("../assets/img/checkbox-on-tablet.png");
    background-repeat: no-repeat;
    background-position: center;
    margin: 0px 0px 0px 0px;
  }
}
.filter__check-off {
  width: 20px;
  height: 20px;
  background-image: url("../assets/img/checkbox-off.png");
  background-repeat: no-repeat;
  background-position: center;
  margin-top: -4px;
  margin-left: 0px;
}
@media (min-width: 768px) {
  .filter__check-off {
    width: 24px;
    height: 24px;
    background-image: url("../assets/img/checkbox-off-tablet.png");
    background-repeat: no-repeat;
    background-position: center;
    margin: 0px 0px 0px 0px;
  }
}
.filter__checkbox-level {
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: normal;
  font-size: 15px;
  line-height: 24px;
  color: #000000;
  margin-top: -7px;
  margin-left: 9px;
}
@media (min-width: 768px) {
  .filter__checkbox-level {
    font-style: normal;
    font-weight: normal;
    font-size: 20px;
    line-height: 20px;
    margin: 0px 0px 0px 12px;
  }
}
@media (min-width: 1440px) {
  .filter__checkbox-level {
    font-style: normal;
    font-weight: normal;
    font-size: 20px;
    line-height: 20px;
    color: #000000;
  }
}
.location {
  display: flex;
  flex-direction: column;
  min-width: 318px;
  width: 100%;
  min-height: 424px;
  margin-top: -30px;
  margin-left: auto;
  margin-right: auto;
}
@media (min-width: 768px) {
  .location {
    min-width: 766px;
    width: 100%;
    min-height: 685px;
    margin-top: -50px;
    margin-left: auto;
    margin-right: auto;
  }
}
@media (min-width: 1440px) {
  .location {
    min-width: 1438px;
    width: 100%;
    min-height: 625px;
    margin-top: -100px;
    margin-bottom: 0px;
    margin-left: auto;
    margin-right: auto;
    position: relative;
    z-index: 3;
  }
}
.location__map {
  width: 100%;
  height: 424px;
}
@media (min-width: 768px) {
  .location__map {
    width: 100%;
    height: 581px;
  }
}
@media (min-width: 1440px) {
  .location__map {
    width: 100%;
    height: 584px;
  }
}
.catalog-header {
  min-width: 100%;
  width: 100%;
  background-color: #182044;
}
.catalog-header__container {
  display: grid;
  grid-template-columns: 1fr 1fr;
  grid-template-rows: 1fr;
  min-width: 320px;
  width: 320px;
  min-height: 143px;
  background-color: #182044;
  border-bottom-left-radius: 20px;
  border-bottom-right-radius: 20px;
  margin: 0px auto 0px auto;
  padding: 0px;
  position: relative;
  z-index: 10;
}
@media (min-width: 768px) {
  .catalog-header__container {
    display: grid;
    grid-template-columns: 1fr 1fr;
    grid-template-rows: 1fr 1fr;
    min-width: 766px;
    width: 766px;
    min-height: 350px;
    border-bottom-left-radius: 58px;
    border-bottom-right-radius: 58px;
    position: relative;
    z-index: 10;
    margin: 0px auto 0px auto;
  }
}
@media (min-width: 1440px) {
  .catalog-header__container {
    display: grid;
    grid-template-columns: 3fr 1fr;
    grid-template-rows: 1fr 1fr;
    min-width: 1438px;
    width: 1438px;
    margin: 0px auto 0px auto;
    padding: 0px 0px 0px 0px;
    position: relative;
    z-index: 10;
  }
}
@media (min-width: 768px) {
  .catalog-header__logo-link {
    grid-column-start: 1;
    grid-row-start: 1;
    margin-top: 46px;
    margin-bottom: 0px;
    margin-left: 40px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .catalog-header__logo-link {
    grid-column-start: 1;
    grid-column-end: 2;
    grid-row-start: 1;
    grid-row-end: 2;
    margin: 47px 0px 0px 58px;
    padding: 0px 0px 0px 0px;
  }
}
.catalog-header__logo {
  grid-column-start: 1;
  grid-row-start: 1;
  width: 100px;
  height: 15px;
  margin-top: 19px;
  margin-left: 25px;
}
@media (min-width: 768px) {
  .catalog-header__logo {
    display: inline-block;
    width: 166px;
    height: 42px;
    margin: 0px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .catalog-header__logo {
    display: inline-block;
    width: 200px;
    height: 52px;
    margin: 0px 0px 0px 3px;
  }
}
.catalog-header__button {
  grid-column-start: 2;
  grid-row-start: 1;
  width: 30px;
  height: 20px;
  background-image: url(../assets/img/icon-menu-mobile.svg);
  background-repeat: no-repeat;
  background-color: transparent;
  border: none;
  margin-top: 23px;
  margin-left: 72px;
}
@media (min-width: 768px) {
  .catalog-header__button {
    grid-column-start: 2;
    grid-row-start: 1;
    margin-top: 61px;
    margin-bottom: 0px;
    margin-left: -12px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .catalog-header__button {
    display: none;
  }
}
@media (min-width: 768px) {
  .catalog-header__btn-container {
    grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 1;
    margin-top: -1px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .catalog-header__btn-container {
    grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 1;
    grid-row-end: 2;
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    margin: -27px 0px 0px -47px;
    padding: 0px 0px 0px 0px;
  }
}
.catalog-header__btn-call {
  display: none;
}
@media (min-width: 768px) {
  .catalog-header__btn-call {
    display: none;
  }
}
@media (min-width: 1440px) {
  .catalog-header__btn-call {
    display: block;
    width: 50px;
    height: 50px;
    border-radius: 50%;
    background-color: #FF8D30;
    margin: 0px 0px 0px 0px;
    padding: 0px 0px 0px 0px;
  }
}
.catalog-header__btn-call:hover {
  background-color: #F26926;
}
.catalog-header__btn-call:active {
  background-color: #F26926;
  fill-opacity: 0.3;
}
.catalog-header__btn-email {
  display: none;
}
@media (min-width: 768px) {
  .catalog-header__btn-email {
    display: none;
  }
}
@media (min-width: 1440px) {
  .catalog-header__btn-email {
    display: block;
    width: 50px;
    height: 50px;
    border-radius: 50%;
    background-color: #FFBD30;
    margin: 0px 0px 0px 0px;
    padding: 0px 0px 0px 0px;
  }
}
.catalog-header__btn-email:hover {
  background-color: #FF8D30;
}
.catalog-header__btn-email:active {
  background-color: #FF8D30;
  fill-opacity: 0.3;
}
.catalog-header__btn-authorization {
  display: none;
}
@media (min-width: 768px) {
  .catalog-header__btn-authorization {
    grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 1;
    display: block;
    width: 188px;
    height: 50px;
    background-color: #FFD74B;
    border-radius: 25px;
    border: none;
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: bold;
    font-size: 20px;
    line-height: 49px;
    text-align: center;
    text-transform: uppercase;
    color: #161C35;
    margin-top: 41px;
    margin-bottom: 0px;
    margin-left: 156px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .catalog-header__btn-authorization {
    margin: 0px 0px 0px 0px;
    padding: 0px 0px 0px 0px;
  }
}
.catalog-header__btn-authorization:hover {
  background-color: #FFBD30;
}
@media (min-width: 1440px) {
  .catalog-header__btn-authorization:active {
    background-color: #FFBD30;
    color: rgba(0, 0, 0, 0.3);
  }
}
.catalog-header__main-page-link {
  display: none;
}
@media (min-width: 768px) {
  .catalog-header__main-page-link {
    grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 2;
    display: block;
    width: 176px;
    height: 20px;
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: bold;
    font-size: 20px;
    line-height: 20px;
    text-transform: uppercase;
    color: #FFFFFF;
    margin-top: 69px;
    margin-bottom: 0px;
    margin-left: 134px;
    margin-right: 0px;
    background-image: url(../assets/img/icon-arrow-bend.svg);
    background-repeat: no-repeat;
    background-position: 99%, 50%;
  }
}
@media (min-width: 1440px) {
  .catalog-header__main-page-link {
    grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 2;
    grid-row-end: 3;
    margin: 68px 0px 0px 62px;
    padding: 0px 0px 0px 0px;
  }
}
.catalog-header__main-page-link:hover {
  opacity: 0.5;
}
.catalog-header__main-page-link:active {
  opacity: 0.3;
}
.catalog-header__nav {
  display: none;
}
@media (min-width: 768px) {
  .catalog-header__nav {
    display: none;
  }
}
@media (min-width: 1440px) {
  .catalog-header__nav {
    grid-column-start: 1;
    grid-column-end: 2;
    grid-row-start: 1;
    grid-row-end: 2;
    display: flex;
    justify-content: flex-start;
    align-items: center;
    width: 543px;
    height: 30px;
    margin: 60px 0px 0px 298px;
    padding: 0px 0px 0px 0px;
  }
}
.catalog-header__nav a:hover {
  color: #FFD74B;
}
.catalog-header__nav a:active {
  color: #FFD74B;
  opacity: 0.3;
}
.catalog-header__desktop-line {
  display: none;
}
@media (min-width: 768px) {
  .catalog-header__desktop-line {
    display: none;
  }
}
@media (min-width: 1440px) {
  .catalog-header__desktop-line {
    display: block;
    width: 60px;
    height: 2px;
    background-color: #FFFFFF;
  }
}
.catalog-header__nav-service {
  display: none;
}
@media (min-width: 768px) {
  .catalog-header__nav-service {
    display: none;
  }
}
@media (min-width: 1440px) {
  .catalog-header__nav-service {
    display: block;
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 20px;
    text-transform: uppercase;
    color: #FFFFFF;
    margin: 0px 0px 0px 44px;
    padding: 0px 0px 0px 0px;
  }
}
.catalog-header__nav-directions {
  display: none;
}
@media (min-width: 768px) {
  .catalog-header__nav-directions {
    display: none;
  }
}
@media (min-width: 1440px) {
  .catalog-header__nav-directions {
    display: block;
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 20px;
    text-transform: uppercase;
    color: #FFFFFF;
    margin: 0px 0px 0px 26px;
    padding: 0px 0px 0px 0px;
  }
}
.catalog-header__nav-travelers {
  display: none;
}
@media (min-width: 768px) {
  .catalog-header__nav-travelers {
    display: none;
  }
}
@media (min-width: 1440px) {
  .catalog-header__nav-travelers {
    display: block;
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 20px;
    text-transform: uppercase;
    color: #FFFFFF;
    margin: 0px 0px 0px 26px;
    padding: 0px 0px 0px 0px;
  }
}
.catalog-header__title {
  grid-column-start: 1;
  grid-row-start: 2;
  display: inline-block;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 36px;
  line-height: 4px;
  padding-left: 26px;
  padding-top: 21px;
  color: #FFFFFF;
}
@media (min-width: 768px) {
  .catalog-header__title {
    grid-column-start: 1;
    grid-row-start: 2;
    display: block;
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: bold;
    font-size: 60px;
    line-height: 20px;
    color: #FFFFFF;
    margin-top: 43px;
    margin-bottom: 0px;
    margin-left: 48px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .catalog-header__title {
    grid-column-start: 1;
    grid-column-end: 2;
    grid-row-start: 2;
    grid-row-end: 3;
    margin: 64px 0px 0px 125px;
    padding: 0px 0px 0px 0px;
  }
}
.catalog-header__title-underline {
  position: absolute;
  width: 173px;
  height: 5px;
  background-color: #FF8D30;
  border-radius: 4px;
  transform: translate(15%, 2801%);
}
@media (min-width: 768px) {
  .catalog-header__title-underline {
    width: 286px;
    height: 7px;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
    border-radius: 4px;
    transform: translate(27%, 4969%);
  }
}
@media (min-width: 1440px) {
  .catalog-header__title-underline {
    grid-column-start: 1;
    grid-column-end: 2;
    grid-row-start: 2;
    grid-row-end: 3;
    margin: 0px 0px 0px 0px;
    padding: 0px 0px 0px 0px;
    transform: translate(43%, 2466%);
  }
}
.visually-hidden {
  position: absolute;
  width: 1px;
  height: 1px;
  margin: -1px;
  border: 0;
  padding: 0;
  white-space: nowrap;
  clip-path: inset(100%);
  clip: rect(0 0 0 0);
  overflow: hidden;
}
.catalog-header__icon-call {
  margin: 15px 0px 0px 15px;
}
.catalog-header__icon-mail {
  margin: 15px 0px 0px 15px;
}
.form-header {
  min-width: 100%;
  width: 100%;
  background-color: #182044;
}
@media (min-width: 768px) {
  .form-header {
    background-color: #182044;
  }
}
@media (min-width: 1440px) {
  .form-header {
    background-color: #182044;
  }
}
.form-header__container {
  display: grid;
  grid-template-columns: 1fr 1fr;
  grid-template-rows: 1fr;
  min-width: 318px;
  width: 318px;
  min-height: 143px;
  background-color: #182044;
  border-bottom-left-radius: 20px;
  border-bottom-right-radius: 20px;
  margin: 0px auto 0px auto;
  padding: 0px;
  position: relative;
  z-index: 10;
}
@media (min-width: 768px) {
  .form-header__container {
    display: grid;
    grid-template-columns: 1fr 1fr;
    grid-template-rows: 1fr 1fr;
    min-width: 766px;
    width: 766px;
    min-height: 351px;
    margin: 0px auto 0px auto;
    border-bottom-left-radius: 58px;
    border-bottom-right-radius: 58px;
    position: relative;
    z-index: 10;
  }
}
@media (min-width: 1440px) {
  .form-header__container {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr 1fr 1fr 1fr;
    grid-template-rows: 1fr 2fr;
    min-width: 1438px;
    width: 1438px;
    padding: 0px 0px 0px 0px;
    margin: 0px auto 0px auto;
    position: relative;
    z-index: 9;
  }
}
@media (min-width: 768px) {
  .form-header__logo-link {
    grid-column-start: 1;
    grid-row-start: 1;
    margin-top: 27px;
    margin-bottom: 0px;
    margin-left: 40px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .form-header__logo-link {
    grid-column-start: 1;
    grid-column-end: 3;
    grid-row-start: 1;
    padding: 0px 0px 0px 0px;
    margin: 28px 0px 0px 60px;
  }
}
.form-header__logo {
  grid-column-start: 1;
  grid-row-start: 1;
  width: 104px;
  height: 15px;
  margin-top: 0px;
  margin-left: 22px;
}
@media (min-width: 768px) {
  .form-header__logo {
    display: block;
    width: 166px;
    height: 42px;
    margin: 0px 0px 0px 0px;
    padding: 0px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .form-header__logo {
    display: block;
    width: 200px;
    height: 52px;
    margin: 0px 0px 0px 0px;
    padding: 0px 0px 0px 0px;
  }
}
.form-header__button {
  grid-column-start: 2;
  grid-row-start: 1;
  width: 30px;
  height: 20px;
  background-image: url(../assets/img/icon-menu-mobile.svg);
  background-repeat: no-repeat;
  background-color: transparent;
  border: none;
  margin-top: 23px;
  margin-left: 30px;
}
@media (min-width: 768px) {
  .form-header__button {
    grid-column-start: 2;
    grid-row-start: 1;
    margin-top: 61px;
    margin-bottom: 0px;
    margin-left: -12px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .form-header__button {
    display: none;
  }
}
.form-header__btn-container {
  display: none;
}
@media (min-width: 768px) {
  .form-header__btn-container {
    grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 1;
    display: block;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .form-header__btn-container {
    grid-column-start: 5;
    grid-column-end: 7;
    grid-row-start: 1;
    grid-row-end: 2;
    display: flex;
    justify-content: space-around;
    align-items: center;
    width: 290px;
    height: 52px;
    margin: 48px 0px 0px 131px;
  }
}
.form-header__btn-call {
  display: none;
}
@media (min-width: 768px) {
  .form-header__btn-call {
    display: none;
  }
}
@media (min-width: 1440px) {
  .form-header__btn-call {
    display: block;
    width: 50px;
    height: 50px;
    border-radius: 50%;
    background-color: #FF8D30;
  }
}
.form-header__btn-call:hover {
  background-color: #F26926;
}
.form-header__btn-call:active {
  background-color: #F26926;
  fill-opacity: 0.3;
}
.form-header__btn-email {
  display: none;
}
@media (min-width: 768px) {
  .form-header__btn-email {
    display: none;
  }
}
@media (min-width: 1440px) {
  .form-header__btn-email {
    display: block;
    width: 50px;
    height: 50px;
    border-radius: 50%;
    background-color: #FFBD30;
  }
}
.form-header__btn-email:hover {
  background-color: #FF8D30;
}
.form-header__btn-email:active {
  background-color: #FF8D30;
  fill-opacity: 0.3;
}
.form-header__btn-authorization {
  display: none;
}
@media (min-width: 768px) {
  .form-header__btn-authorization {
    display: block;
    width: 188px;
    height: 50px;
    background-color: #FFD74B;
    border-radius: 25px;
    border: none;
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: bold;
    font-size: 20px;
    line-height: 49px;
    text-align: center;
    text-transform: uppercase;
    color: #161C35;
    margin-top: 40px;
    margin-bottom: 0px;
    margin-left: 156px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .form-header__btn-authorization {
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
  }
}
.form-header__btn-authorization:hover {
  background-color: #FFBD30;
}
.form-header__btn-authorization:active {
  background-color: #FFBD30;
  color: rgba(0, 0, 0, 0.3);
}
.form-header__main-page-link {
  display: none;
}
@media (min-width: 768px) {
  .form-header__main-page-link {
    display: none;
  }
}
@media (min-width: 1440px) {
  .form-header__main-page-link {
    display: none;
  }
}
.form-header__title {
  grid-column-start: 1;
  grid-row-start: 2;
  display: inline-block;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 36px;
  line-height: 4px;
  margin: -35px 0px 0px 25px;
  padding: 0px 0px 0px 0px;
  color: #FFFFFF;
}
@media (min-width: 768px) {
  .form-header__title {
    grid-column-start: 1;
    grid-column-end: 3;
    grid-row-start: 2;
    display: block;
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: bold;
    font-size: 60px;
    line-height: 20px;
    color: #FFFFFF;
    margin-top: 65px;
    margin-bottom: 0px;
    margin-left: 75px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .form-header__title {
    grid-column-start: 1;
    grid-column-end: 3;
    grid-row-start: 2;
    grid-row-end: 3;
    margin: 123px 0px 0px 124px;
    padding: 0px 0px 0px 0px;
  }
}
.form-header__title-underline {
  position: absolute;
  width: 212px;
  height: 5px;
  background-color: #FF8D30;
  border-radius: 4px;
  transform: translate(12%, 2800%);
}
@media (min-width: 768px) {
  .form-header__title-underline {
    width: 351px;
    height: 7px;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
    border-radius: 4px;
    transform: translate(22%, 4983%);
  }
}
@media (min-width: 1440px) {
  .form-header__title-underline {
    width: 359px;
    height: 7px;
    margin-top: -1px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
    border-radius: 4px;
    transform: translate(35%, 4983%);
  }
}
.form-header__nav {
  display: none;
}
@media (min-width: 768px) {
  .form-header__nav {
    display: none;
  }
}
@media (min-width: 1440px) {
  .form-header__nav {
    grid-column-start: 2;
    grid-column-end: 4;
    grid-row-start: 1;
    grid-row-end: 2;
    display: flex;
    justify-content: flex-start;
    align-items: center;
    width: 500px;
    height: 25px;
    padding: 0px 0px 0px 0px;
    margin: 62px 0px 0px 60px;
  }
}
@media (min-width: 1440px) {
  .form-header__nav a:hover {
    color: #FFD74B;
  }
}
@media (min-width: 1440px) {
  .form-header__nav a:active {
    color: #FFD74B;
    opacity: 0.3;
  }
}
@media (min-width: 1440px) {
  .form-header__desktop-line {
    width: 60px;
    height: 2px;
    background-color: #FFFFFF;
    margin: 0px 0px 0px 0px;
  }
}
.form-header__nav-item-service {
  display: none;
}
@media (min-width: 768px) {
  .form-header__nav-item-service {
    display: none;
  }
}
@media (min-width: 1440px) {
  .form-header__nav-item-service {
    display: inline-block;
    width: 100px;
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 20px;
    text-transform: uppercase;
    color: #FFFFFF;
    padding: 0px 0px 0px 0px;
    margin: 0px 0px 0px 42px;
  }
}
.form-header__nav-item-directions {
  display: none;
}
@media (min-width: 768px) {
  .form-header__nav-item-directions {
    display: none;
  }
}
@media (min-width: 1440px) {
  .form-header__nav-item-directions {
    display: inline-block;
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 20px;
    text-transform: uppercase;
    color: #FFFFFF;
    padding: 0px 0px 0px 0px;
    margin: 0px 0px 0px 18px;
  }
}
.form-header__nav-item-travelers {
  display: none;
}
@media (min-width: 768px) {
  .form-header__nav-item-travelers {
    display: none;
  }
}
@media (min-width: 1440px) {
  .form-header__nav-item-travelers {
    display: inline-block;
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 20px;
    text-transform: uppercase;
    color: #FFFFFF;
    padding: 0px 0px 0px 0px;
    margin: 0px 0px 0px 25px;
  }
}
.form-header__icon-call {
  margin: 15px 0px 0px 15px;
}
.form-header__icon-mail {
  margin: 15px 0px 0px 15px;
}
.catalog-footer {
  min-width: 100%;
  width: 100%;
  background-color: #FFFFFF;
}
.catalog-footer__container {
  display: flex;
  flex-direction: column;
  justify-content: start;
  min-width: 318px;
  width: 318px;
  min-height: 240px;
  padding-top: 12px;
  background-color: #FFFFFF;
  color: #444444;
  border: solid 1px transparent;
  border-top-left-radius: 30px;
  border-top-right-radius: 30px;
  margin-top: -20px;
  margin-left: auto;
  margin-right: auto;
}
@media (min-width: 768px) {
  .catalog-footer__container {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    grid-template-rows: 140px;
    min-width: 766px;
    width: 766px;
    min-height: 140px;
    margin-top: -59px;
    margin-left: auto;
    margin-right: auto;
    border-top-left-radius: 60px;
    border-top-right-radius: 60px;
  }
}
@media (min-width: 1440px) {
  .catalog-footer__container {
    min-width: 1438px;
    width: 1438px;
    min-height: 154px;
    margin-top: -63px;
    margin-bottom: 0px;
    margin-left: auto;
    margin-right: auto;
    border-top-left-radius: 60px;
    border-top-right-radius: 60px;
    position: relative;
    z-index: 10;
  }
}
.catalog-footer__logo {
  width: 100px;
  height: 15px;
  margin: 24px 0px 0px -2px;
}
@media (min-width: 768px) {
  .catalog-footer__logo {
    width: 164px;
    height: 42px;
    margin-top: -2px;
    margin-bottom: 0px;
    margin-left: -51px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .catalog-footer__logo {
    width: 200px;
    height: 55px;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
  }
}
.catalog-footer__contacts {
  display: flex;
  justify-content: center;
}
@media (min-width: 768px) {
  .catalog-footer__contacts {
    grid-column-start: 1;
    grid-row-start: 1;
    width: 164px;
    height: 42px;
    margin-top: 44px;
    margin-bottom: 0px;
    margin-left: 64px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .catalog-footer__contacts {
    grid-column-start: 1;
    grid-row-start: 1;
    width: auto;
    height: auto;
    margin-top: 38px;
    margin-bottom: 0px;
    margin-left: -163px;
    margin-right: 0px;
  }
}
.catalog-footer__social {
  display: flex;
  justify-content: center;
  margin: 40px 0px 0px -4px;
}
@media (min-width: 768px) {
  .catalog-footer__social {
    grid-column-start: 2;
    grid-row-start: 1;
    height: auto;
    margin-top: 32px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .catalog-footer__social {
    margin-top: 33px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 4px;
  }
}
.catalog-footer__social a:hover {
  background-color: #FFBD30;
}
.catalog-footer__social a:active {
  background-color: #FFBD30;
  fill-opacity: 0.3;
}
.catalog-footer__copyright {
  margin: 50px 0px 0px 22px;
}
@media (min-width: 768px) {
  .catalog-footer__copyright {
    grid-column-start: 3;
    grid-row-start: 1;
    height: auto;
    margin-top: 51px;
    margin-bottom: 0px;
    margin-left: 36px;
    margin-right: 0px;
    padding: 0px;
    cursor: pointer;
  }
}
@media (min-width: 1440px) {
  .catalog-footer__copyright {
    margin-top: 50px;
    margin-bottom: 0px;
    margin-left: 240px;
    margin-right: 0px;
  }
}
.catalog-footer__copyright:hover {
  opacity: 0.6;
}
.catalog-footer__copyright:active {
  opacity: 0.3;
}
.catalog-footer__link {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 45px;
  height: 45px;
  border-radius: 50%;
  background-color: #FFD74B;
}
@media (min-width: 768px) {
  .catalog-footer__link {
    width: 62px;
    height: 62px;
  }
}
.catalog-footer__icon-fb {
  margin: auto;
}
@media (min-width: 768px) {
  .catalog-footer__icon-fb {
    width: 14px;
    height: 28px;
  }
}
.catalog-footer__icon-vk {
  margin: auto;
}
@media (min-width: 768px) {
  .catalog-footer__icon-vk {
    width: 30px;
    height: 16px;
  }
}
.catalog-footer__icon-inst {
  margin: auto;
}
@media (min-width: 768px) {
  .catalog-footer__icon-inst {
    width: 23px;
    height: 23px;
  }
}
.catalog-footer__copyright-link {
  display: inline-block;
  width: 28px;
  height: 34px;
  margin-left: 158px;
  background-image: url(../assets/img/html-footer-icon.svg);
  background-repeat: no-repeat;
}
@media (min-width: 768px) {
  .catalog-footer__copyright-link {
    width: 27px;
    height: 34px;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: 19px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .catalog-footer__copyright-link {
    width: 27px;
    height: 34px;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: 18px;
    margin-right: 0px;
  }
}
.catalog-footer__text {
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 30px;
  color: #444444;
}
@media (min-width: 768px) {
  .catalog-footer__text {
    font-style: normal;
    font-weight: normal;
    font-size: 20px;
    line-height: 20px;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: 25px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .catalog-footer__text {
    font-style: normal;
    font-weight: normal;
    font-size: 20px;
    line-height: 20px;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: 25px;
    margin-right: 0px;
  }
}
.form-footer {
  min-width: 100%;
  width: 100%;
  background-color: transparent;
}
.form-footer__container {
  display: flex;
  flex-direction: column;
  justify-content: space-around;
  min-width: 318px;
  width: 318px;
  min-height: 240px;
  padding-top: 12px;
  background-color: #FFFFFF;
  color: #444444;
  border: solid 1px transparent;
  border-top-left-radius: 30px;
  border-top-right-radius: 30px;
  margin-top: -178px;
  margin-left: auto;
  margin-right: auto;
  position: relative;
  z-index: 12;
}
@media (min-width: 768px) {
  .form-footer__container {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    grid-template-rows: 140px;
    min-width: 766px;
    width: 766px;
    min-height: 140px;
    margin-top: -60px;
    margin-left: auto;
    margin-right: auto;
    border-top-left-radius: 55px;
    border-top-right-radius: 55px;
    position: relative;
    z-index: 12;
  }
}
@media (min-width: 1440px) {
  .form-footer__container {
    min-width: 1438px;
    width: 1438px;
    min-height: 155px;
    margin-top: -100px;
    margin-bottom: 0px;
    margin-left: auto;
    margin-right: auto;
  }
}
.form-footer__logo {
  width: 100px;
  height: 15px;
  margin: -1px 0px 0px -3px;
}
@media (min-width: 768px) {
  .form-footer__logo {
    display: inline-block;
    width: 164px;
    height: 42px;
    margin: 0px 0px 0px 0px;
  }
}
@media (min-width: 1440px) {
  .form-footer__logo {
    display: block;
    width: 200px;
    height: 52px;
    margin: 0px 0px 0px 0px;
  }
}
.form-footer__contacts {
  display: flex;
  justify-content: center;
  width: auto;
  height: auto;
}
@media (min-width: 768px) {
  .form-footer__contacts {
    grid-column-start: 1;
    grid-row-start: 1;
    width: auto;
    height: auto;
    margin-top: 43px;
    margin-bottom: 0px;
    margin-left: -14px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .form-footer__contacts {
    grid-column-start: 1;
    grid-row-start: 1;
    width: auto;
    height: auto;
    margin-top: 40px;
    margin-bottom: 0px;
    margin-left: -162px;
    margin-right: 0px;
  }
}
.form-footer__social {
  display: flex;
  justify-content: center;
  margin: -12px 0px 0px -4px;
}
@media (min-width: 768px) {
  .form-footer__social {
    grid-column-start: 2;
    grid-row-start: 1;
    height: auto;
    margin-top: 34px;
    margin-bottom: 0px;
    margin-left: 0px;
    margin-right: 0px;
  }
}
@media (min-width: 1440px) {
  .form-footer__social {
    margin-top: 36px;
    margin-bottom: 0px;
    margin-left: 3px;
    margin-right: 4px;
  }
}
.form-footer__social a:hover {
  background-color: #FFBD30;
}
.form-footer__social a:active {
  background-color: #FFBD30;
  fill-opacity: 0.3;
}
.form-footer__copyright {
  padding-left: 23px;
  margin: 0px 0px 6px 0px;
  cursor: pointer;
}
@media (min-width: 768px) {
  .form-footer__copyright {
    grid-column-start: 3;
    grid-row-start: 1;
    height: auto;
    margin-top: 51px;
    margin-bottom: 0px;
    margin-left: 36px;
    margin-right: 0px;
    padding: 0px;
  }
}
@media (min-width: 1440px) {
  .form-footer__copyright {
    margin-top: 51px;
    margin-bottom: 0px;
    margin-left: 240px;
    margin-right: 0px;
  }
}
.form-footer__copyright:hover {
  opacity: 0.6;
}
.form-footer__copyright:active {
  opacity: 0.3;
}
.form-footer__link {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 45px;
  height: 45px;
  border-radius: 50%;
  background-color: #FFD74B;
}
@media (min-width: 768px) {
  .form-footer__link {
    width: 62px;
    height: 62px;
  }
}
.form-footer__icon-fb {
  margin: auto;
}
@media (min-width: 768px) {
  .form-footer__icon-fb {
    width: 14px;
    height: 28px;
  }
}
.form-footer__icon-vk {
  margin: auto;
}
@media (min-width: 768px) {
  .form-footer__icon-vk {
    width: 30px;
    height: 16px;
  }
}
.form-footer__icon-inst {
  margin: auto;
}
@media (min-width: 768px) {
  .form-footer__icon-inst {
    width: 23px;
    height: 23px;
  }
}
.form-footer__copyright-link {
  display: inline-block;
  width: 28px;
  height: 34px;
  margin-left: 153px;
  background-image: url(../assets/img/html-footer-icon.svg);
  background-repeat: no-repeat;
}
@media (min-width: 768px) {
  .form-footer__copyright-link {
    width: 27px;
    height: 34px;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: 14px;
    margin-right: 0px;
  }
}
.form-footer__text {
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 30px;
  color: #444444;
}
@media (min-width: 768px) {
  .form-footer__text {
    font-style: normal;
    font-weight: normal;
    font-size: 20px;
    line-height: 20px;
    margin-top: 0px;
    margin-bottom: 0px;
    margin-left: 25px;
    margin-right: 0px;
  }
}
.filter-modal {
  display: flex;
  justify-content: flex-start;
  margin: 0px;
  padding-top: 13px;
  padding-bottom: 25px;
  position: absolute;
  transform: translate(0%, 0%);
  flex-direction: column;
  width: 320px;
  min-height: 650px;
  background-color: #E2E5F2;
  border-bottom-left-radius: 30px;
  border-bottom-right-radius: 30px;
  border: solid 1px transparent;
}
@media (min-width: 768px) {
  .filter-modal {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr;
    grid-template-rows: 0.25fr 1fr 1fr 0.5fr 0.5fr;
    min-width: 768px;
    min-height: 780px;
    margin: 0px 0px 0px 0px;
    padding: 0px 0px 31px 0px;
    border-bottom-left-radius: 60px;
    border-bottom-right-radius: 60px;
    position: absolute;
    transform: translate(0%, -19%);
    z-index: 9;
    box-sizing: border-box;
  }
}
.filter-modal__list {
  display: flex;
  flex-direction: column;
  justify-content: space-around;
  align-items: flex-start;
  width: 68px;
  height: 107px;
  margin: 0px 0px 0px 49px;
}
@media (min-width: 768px) {
  .filter-modal__list {
    grid-column-start: 1;
    grid-column-end: 4;
    grid-row-start: 1;
    grid-row-end: 2;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    width: 368px;
    height: 20px;
    margin: 64px 0px 0px 72px;
  }
}
.filter-modal__country-title {
  display: block;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 16px;
  line-height: 4px;
  text-transform: uppercase;
  color: #192144;
  margin: 0px 0px 0px 0px;
}
@media (min-width: 768px) {
  .filter-modal__country-title {
    font-size: 20px;
    line-height: 20px;
  }
}
@media (min-width: 768px) {
  .filter-modal__country-title:nth-child(1) {
    margin: 0px 0px 0px 0px;
    padding: 0px 0px 0px 0px;
  }
}
@media (min-width: 768px) {
  .filter-modal__country-title:nth-child(2) {
    margin: 0px 0px 0px 0px;
    padding: 0px 0px 0px 0px;
  }
}
@media (min-width: 768px) {
  .filter-modal__country-title:nth-child(3) {
    margin: 0px 0px 0px 0px;
    padding: 0px 0px 0px 0px;
  }
}
@media (min-width: 768px) {
  .filter-modal__country-title:nth-child(4) {
    grid-row-start: 1;
    margin: 0px 0px 0px 0px;
    padding: 0px 0px 0px 0px;
  }
}
.filter-modal__alphabet {
  width: 220px;
  border-collapse: collapse;
  margin: 19px 0px 0px 50px;
}
@media (min-width: 768px) {
  .filter-modal__alphabet {
    grid-column-start: 1;
    grid-column-end: 5;
    grid-row-start: 2;
    grid-row-end: 6;
    margin: 52px 0px 0px 56px;
    padding: 0px 0px 0px 0px;
    width: 380px;
    min-height: 411px;
  }
}
.filter-modal__letters {
  width: 40px;
  height: 38px;
  border: 1px solid #CBCED9;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: 500;
  font-size: 14px;
  line-height: 14px;
  text-align: center;
  text-transform: uppercase;
  color: #1D2E5B;
  background-color: #FFFFFF;
}
@media (min-width: 768px) {
  .filter-modal__letters {
    font-style: normal;
    font-weight: bold;
    font-size: 60px;
    line-height: 60px;
    text-transform: uppercase;
    color: #192144;
    opacity: 0.3;
    background-color: transparent;
    border: none;
  }
}
.filter-modal__country-list {
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 22px;
  color: #444444;
  margin-top: 12px;
  margin-bottom: 14px;
  margin-left: 52px;
  border: solid 1px transparent;
}
@media (min-width: 768px) {
  .filter-modal__country-list {
    grid-column-start: 6;
    grid-column-end: 9;
    grid-row-start: 2;
    grid-row-end: 5;
    font-size: 20px;
    line-height: 30px;
    margin: 59px 0px 0px 36px;
    padding: 0px 0px 0px 0px;
  }
}
.filter-modal__country-item {
  display: block;
}
.filter-modal__close {
  width: 270px;
  height: 39px;
  background-color: #D6DAED;
  border-radius: 20px;
  text-align: center;
  align-self: center;
  border: transparent;
  font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 16px;
  line-height: 20px;
  letter-spacing: 0.05em;
  text-transform: uppercase;
  color: #192144;
  background-image: url("../assets/img/filter-toggle-close.svg");
  background-repeat: no-repeat;
  background-position: 33% 50%;
  margin: 14px auto 0px auto;
  padding: 0px 0px 0px 26px;
}
@media (min-width: 768px) {
  .filter-modal__close {
    grid-column-start: 1;
    grid-column-end: 9;
    grid-row-start: 4;
    grid-row-end: 6;
    width: 615px;
    height: 100px;
    font-style: normal;
    font-weight: bold;
    font-size: 19px;
    line-height: 19px;
    background-image: url(../assets/img/icon-close-tablet.svg);
    background-repeat: no-repeat;
    background-position: 41% 50%;
    margin: 36px 0px 0px 75px;
    padding: 0px 0px 0px 46px;
    box-sizing: border-box;
  }
}
.filter-modal__close-tablet {
  display: none;
}
@media (min-width: 768px) {
  .filter-modal__close-tablet {
    display: block;
    grid-column-start: 6;
    grid-column-end: 9;
    grid-row-start: 1;
    grid-row-end: 3;
    width: 198px;
    height: 34px;
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: bold;
    font-size: 20px;
    line-height: 20px;
    text-align: left;
    text-transform: uppercase;
    color: #192144;
    border: none;
    background-color: transparent;
    background-image: url(../assets/img/icon-close-tablet.svg);
    background-repeat: no-repeat;
    background-position: 87%, 50%;
    margin: 58px 0px 0px 39px;
    padding: 0px 0px 0px 0px;
  }
}
.hidden {
  display: none;
}
.form-main {
  background-color: #E5E5E5;
}
.countries-modal {
  display: none;
}
@media (min-width: 768px) {
  .countries-modal {
    display: none;
  }
}
@media (min-width: 1440px) {
  .countries-modal {
    display: block;
    min-width: 100%;
    width: 100%;
    background-color: #E5E5E5;
  }
}
.countries-modal__container {
  display: none;
}
@media (min-width: 768px) {
  .countries-modal__container {
    display: none;
  }
}
@media (min-width: 1440px) {
  .countries-modal__container {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr 1fr 1fr;
    grid-template-rows: 1fr 1fr 1fr 1fr 1fr 0.5fr;
    min-width: 1440px;
    width: 1440px;
    height: 2755px;
    margin: -50px auto 0px auto;
    padding: 0px 0px 0px 0px;
    background-color: #E5E5E5;
    position: relative;
    z-index: 9;
    box-sizing: border-box;
    border: solid 1px transparent;
  }
}
.countries-modal__title {
  display: none;
}
@media (min-width: 768px) {
  .countries-modal__title {
    display: none;
  }
}
@media (min-width: 1440px) {
  .countries-modal__title {
    display: inline-block;
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: bold;
    font-size: 60px;
    line-height: 60px;
    text-transform: uppercase;
    color: #192144;
    margin: 0px 0px 32px 0px;
    padding: 0px 0px 0px 0px;
  }
}
.countries-modal__item-wrap {
  display: none;
}
@media (min-width: 768px) {
  .countries-modal__item-wrap {
    display: none;
  }
}
@media (min-width: 1440px) {
  .countries-modal__item-wrap {
    display: flex;
    flex-direction: column;
    justify-content: start;
    align-items: flex-start;
  }
}
.countries-modal__item-wrap:nth-child(1) {
  display: none;
}
@media (min-width: 768px) {
  .countries-modal__item-wrap:nth-child(1) {
    display: none;
  }
}
@media (min-width: 1440px) {
  .countries-modal__item-wrap:nth-child(1) {
    grid-column-start: 1;
    grid-column-end: 2;
    grid-row-start: 1;
    grid-row-end: 2;
    display: flex;
    margin: 70px 0px 0px 96px;
    padding: 0px 0px 0px 0px;
  }
}
.countries-modal__item-wrap:nth-child(2) {
  display: none;
}
@media (min-width: 768px) {
  .countries-modal__item-wrap:nth-child(2) {
    display: none;
  }
}
@media (min-width: 1440px) {
  .countries-modal__item-wrap:nth-child(2) {
    grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 1;
    grid-row-end: 2;
    display: flex;
    margin: 69px 0px 0px 60px;
    padding: 0px 0px 0px 0px;
  }
}
.countries-modal__item-wrap:nth-child(3) {
  display: none;
}
@media (min-width: 768px) {
  .countries-modal__item-wrap:nth-child(3) {
    display: none;
  }
}
@media (min-width: 1440px) {
  .countries-modal__item-wrap:nth-child(3) {
    grid-column-start: 3;
    grid-column-end: 4;
    grid-row-start: 1;
    grid-row-end: 2;
    display: flex;
    margin: 69px 0px 0px 23px;
    padding: 0px 0px 0px 0px;
  }
}
.countries-modal__item-wrap:nth-child(4) {
  display: none;
}
@media (min-width: 768px) {
  .countries-modal__item-wrap:nth-child(4) {
    display: none;
  }
}
@media (min-width: 1440px) {
  .countries-modal__item-wrap:nth-child(4) {
    grid-column-start: 4;
    grid-column-end: 5;
    grid-row-start: 1;
    grid-row-end: 2;
    display: flex;
    margin: 69px 0px 0px -12px;
    padding: 0px 0px 0px 0px;
  }
}
.countries-modal__item-wrap:nth-child(5) {
  display: none;
}
@media (min-width: 768px) {
  .countries-modal__item-wrap:nth-child(5) {
    display: none;
  }
}
@media (min-width: 1440px) {
  .countries-modal__item-wrap:nth-child(5) {
    grid-column-start: 5;
    grid-column-end: 6;
    grid-row-start: 1;
    grid-row-end: 2;
    display: flex;
    margin: 69px 0px 0px -54px;
    padding: 0px 0px 0px 0px;
  }
}
.countries-modal__item-wrap:nth-child(6) {
  display: none;
}
@media (min-width: 768px) {
  .countries-modal__item-wrap:nth-child(6) {
    display: none;
  }
}
@media (min-width: 1440px) {
  .countries-modal__item-wrap:nth-child(6) {
    grid-column-start: 1;
    grid-column-end: 2;
    grid-row-start: 2;
    grid-row-end: 3;
    display: flex;
    margin: 51px 0px 0px 95px;
    padding: 0px 0px 0px 0px;
  }
}
.countries-modal__item-wrap:nth-child(7) {
  display: none;
}
@media (min-width: 768px) {
  .countries-modal__item-wrap:nth-child(7) {
    display: none;
  }
}
@media (min-width: 1440px) {
  .countries-modal__item-wrap:nth-child(7) {
    grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 2;
    grid-row-end: 3;
    display: flex;
    margin: 48px 0px 0px 59px;
    padding: 0px 0px 0px 0px;
  }
}
.countries-modal__item-wrap:nth-child(8) {
  display: none;
}
@media (min-width: 768px) {
  .countries-modal__item-wrap:nth-child(8) {
    display: none;
  }
}
@media (min-width: 1440px) {
  .countries-modal__item-wrap:nth-child(8) {
    grid-column-start: 3;
    grid-column-end: 4;
    grid-row-start: 2;
    grid-row-end: 3;
    display: flex;
    margin: 49px 0px 0px 23px;
    padding: 0px 0px 0px 0px;
  }
}
.countries-modal__item-wrap:nth-child(9) {
  display: none;
}
@media (min-width: 768px) {
  .countries-modal__item-wrap:nth-child(9) {
    display: none;
  }
}
@media (min-width: 1440px) {
  .countries-modal__item-wrap:nth-child(9) {
    grid-column-start: 4;
    grid-column-end: 5;
    grid-row-start: 2;
    grid-row-end: 3;
    display: flex;
    margin: 50px 0px 0px -15px;
    padding: 0px 0px 0px 0px;
  }
}
.countries-modal__item-wrap:nth-child(10) {
  display: none;
}
@media (min-width: 768px) {
  .countries-modal__item-wrap:nth-child(10) {
    display: none;
  }
}
@media (min-width: 1440px) {
  .countries-modal__item-wrap:nth-child(10) {
    grid-column-start: 5;
    grid-column-end: 6;
    grid-row-start: 2;
    grid-row-end: 3;
    display: flex;
    margin: 50px 0px 0px -53px;
    padding: 0px 0px 0px 0px;
  }
}
.countries-modal__item-wrap:nth-child(11) {
  display: none;
}
@media (min-width: 768px) {
  .countries-modal__item-wrap:nth-child(11) {
    display: none;
  }
}
@media (min-width: 1440px) {
  .countries-modal__item-wrap:nth-child(11) {
    grid-column-start: 1;
    grid-column-end: 2;
    grid-row-start: 3;
    grid-row-end: 4;
    display: flex;
    margin: 47px 0px 0px 95px;
    padding: 0px 0px 0px 0px;
  }
}
.countries-modal__item-wrap:nth-child(12) {
  display: none;
}
@media (min-width: 768px) {
  .countries-modal__item-wrap:nth-child(12) {
    display: none;
  }
}
@media (min-width: 1440px) {
  .countries-modal__item-wrap:nth-child(12) {
    grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 3;
    grid-row-end: 4;
    display: flex;
    margin: 45px 0px 0px 59px;
    padding: 0px 0px 0px 0px;
  }
}
.countries-modal__item-wrap:nth-child(13) {
  display: none;
}
@media (min-width: 768px) {
  .countries-modal__item-wrap:nth-child(13) {
    display: none;
  }
}
@media (min-width: 1440px) {
  .countries-modal__item-wrap:nth-child(13) {
    grid-column-start: 3;
    grid-column-end: 4;
    grid-row-start: 3;
    grid-row-end: 4;
    display: flex;
    margin: 47px 0px 0px 22px;
    padding: 0px 0px 0px 0px;
  }
}
.countries-modal__item-wrap:nth-child(14) {
  display: none;
}
@media (min-width: 768px) {
  .countries-modal__item-wrap:nth-child(14) {
    display: none;
  }
}
@media (min-width: 1440px) {
  .countries-modal__item-wrap:nth-child(14) {
    grid-column-start: 4;
    grid-column-end: 5;
    grid-row-start: 3;
    grid-row-end: 4;
    display: flex;
    margin: 44px 0px 0px -13px;
    padding: 0px 0px 0px 0px;
  }
}
.countries-modal__item-wrap:nth-child(15) {
  display: none;
}
@media (min-width: 768px) {
  .countries-modal__item-wrap:nth-child(15) {
    display: none;
  }
}
@media (min-width: 1440px) {
  .countries-modal__item-wrap:nth-child(15) {
    grid-column-start: 5;
    grid-column-end: 6;
    grid-row-start: 3;
    grid-row-end: 4;
    display: flex;
    margin: 45px 0px 0px -53px;
    padding: 0px 0px 0px 0px;
  }
}
.countries-modal__item-wrap:nth-child(16) {
  display: none;
}
@media (min-width: 768px) {
  .countries-modal__item-wrap:nth-child(16) {
    display: none;
  }
}
@media (min-width: 1440px) {
  .countries-modal__item-wrap:nth-child(16) {
    grid-column-start: 1;
    grid-column-end: 2;
    grid-row-start: 4;
    grid-row-end: 6;
    display: flex;
    margin: 43px 0px 0px 95px;
    padding: 0px 0px 0px 0px;
  }
}
.countries-modal__item-wrap:nth-child(17) {
  display: none;
}
@media (min-width: 768px) {
  .countries-modal__item-wrap:nth-child(17) {
    display: none;
  }
}
@media (min-width: 1440px) {
  .countries-modal__item-wrap:nth-child(17) {
    grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 4;
    grid-row-end: 5;
    display: flex;
    margin: 45px 0px 0px 60px;
    padding: 0px 0px 0px 0px;
  }
}
.countries-modal__item-wrap:nth-child(18) {
  display: none;
}
@media (min-width: 768px) {
  .countries-modal__item-wrap:nth-child(18) {
    display: none;
  }
}
@media (min-width: 1440px) {
  .countries-modal__item-wrap:nth-child(18) {
    grid-column-start: 3;
    grid-column-end: 4;
    grid-row-start: 4;
    grid-row-end: 5;
    display: flex;
    margin: 44px 0px 0px 24px;
    padding: 0px 0px 0px 0px;
  }
}
.countries-modal__item-wrap:nth-child(19) {
  display: none;
}
@media (min-width: 768px) {
  .countries-modal__item-wrap:nth-child(19) {
    display: none;
  }
}
@media (min-width: 1440px) {
  .countries-modal__item-wrap:nth-child(19) {
    grid-column-start: 4;
    grid-column-end: 5;
    grid-row-start: 4;
    grid-row-end: 5;
    display: flex;
    margin: 43px 0px 0px -14px;
    padding: 0px 0px 0px 0px;
  }
}
.countries-modal__item-wrap:nth-child(20) {
  display: none;
}
@media (min-width: 768px) {
  .countries-modal__item-wrap:nth-child(20) {
    display: none;
  }
}
@media (min-width: 1440px) {
  .countries-modal__item-wrap:nth-child(20) {
    grid-column-start: 5;
    grid-column-end: 6;
    grid-row-start: 4;
    grid-row-end: 5;
    display: flex;
    margin: 45px 0px 0px -52px;
    padding: 0px 0px 0px 0px;
  }
}
.countries-modal__item-wrap:nth-child(21) {
  display: none;
}
@media (min-width: 768px) {
  .countries-modal__item-wrap:nth-child(21) {
    display: none;
  }
}
@media (min-width: 1440px) {
  .countries-modal__item-wrap:nth-child(21) {
    grid-column-start: 1;
    grid-column-end: 2;
    grid-row-start: 5;
    grid-row-end: 6;
    display: flex;
    margin: 91px 0px 0px 94px;
    padding: 0px 0px 0px 0px;
  }
}
.countries-modal__item-wrap:nth-child(22) {
  display: none;
}
@media (min-width: 768px) {
  .countries-modal__item-wrap:nth-child(22) {
    display: none;
  }
}
@media (min-width: 1440px) {
  .countries-modal__item-wrap:nth-child(22) {
    grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 5;
    grid-row-end: 6;
    display: flex;
    margin: 92px 0px 0px 58px;
    padding: 0px 0px 0px 0px;
  }
}
.countries-modal__item-wrap:nth-child(23) {
  display: none;
}
@media (min-width: 768px) {
  .countries-modal__item-wrap:nth-child(23) {
    display: none;
  }
}
@media (min-width: 1440px) {
  .countries-modal__item-wrap:nth-child(23) {
    grid-column-start: 3;
    grid-column-end: 4;
    grid-row-start: 5;
    grid-row-end: 6;
    display: flex;
    margin: 95px 0px 0px 26px;
    padding: 0px 0px 0px 0px;
  }
}
.countries-modal__item-wrap:nth-child(24) {
  display: none;
}
@media (min-width: 768px) {
  .countries-modal__item-wrap:nth-child(24) {
    display: none;
  }
}
@media (min-width: 1440px) {
  .countries-modal__item-wrap:nth-child(24) {
    grid-column-start: 4;
    grid-column-end: 5;
    grid-row-start: 5;
    grid-row-end: 6;
    display: flex;
    margin: 92px 0px 0px -12px;
    padding: 0px 0px 0px 0px;
  }
}
.countries-modal__item-wrap:nth-child(25) {
  display: none;
}
@media (min-width: 768px) {
  .countries-modal__item-wrap:nth-child(25) {
    display: none;
  }
}
@media (min-width: 1440px) {
  .countries-modal__item-wrap:nth-child(25) {
    grid-column-start: 5;
    grid-column-end: 6;
    grid-row-start: 5;
    grid-row-end: 6;
    display: flex;
    margin: 93px 0px 0px -49px;
    padding: 0px 0px 0px 0px;
  }
}
.countries-modal__list-item {
  display: none;
}
@media (min-width: 768px) {
  .countries-modal__list-item {
    display: none;
  }
}
@media (min-width: 1440px) {
  .countries-modal__list-item {
    display: block;
    font-family: "Blogger Sans", Arial, Helvetica, sans-serif;
    font-style: normal;
    font-weight: normal;
    font-size: 20px;
    line-height: 30px;
    color: #444444;
  }
}
.countries-modal__btn {
  display: none;
}
@media (min-width: 768px) {
  .countries-modal__btn {
    display: none;
  }
}
@media (min-width: 1440px) {
  .countries-modal__btn {
    grid-column-start: 1;
    grid-column-end: 6;
    grid-row-start: 6;
    grid-row-end: 7;
    display: block;
    width: 1320px;
    height: 100px;
    background-color: #D6DAED;
    background-image: url(../assets/img/menu-close.svg);
    background-repeat: no-repeat;
    background-position: 592px 39px;
    background-size: 22px, 22px;
    border-radius: 20px;
    border: none;
    margin: -51px auto 0px auto;
    padding: 0px 0px 0px 34px;
    box-sizing: border-box;
  }
}
.countries-modal__btn-text {
  display: none;
}
@media (min-width: 768px) {
  .countries-modal__btn-text {
    display: none;
  }
}
@media (min-width: 1440px) {
  .countries-modal__btn-text {
    display: block;
    font-family: Blogger Sans;
    font-style: normal;
    font-weight: bold;
    font-size: 20px;
    line-height: 20px;
    text-transform: uppercase;
    color: #192144;
  }
}
.container {
  margin: 0 auto;
}
.animation {
  overflow: hidden;
  padding: 0 4px;
  height: 1em;
}
.animation span {
  position: relative;
  display: inline-block;
  -webkit-transition: -webkit-transform 0.3s;
  -moz-transition: -moz-transform 0.3s;
  transition: transform 0.3s;
}
.animation span::before {
  position: absolute;
  top: 100%;
  content: attr(data-hover);
  font-weight: 500;
  -webkit-transform: translate3d(0, 0, 0);
  -moz-transform: translate3d(0, 0, 0);
  transform: translate3d(0, 0, 0);
}
.animation:hover span,
.animation:focus span {
  -webkit-transform: translateY(-100%);
  -moz-transform: translateY(-100%);
  transform: translateY(-100%);
}
@font-face {
  font-family: "Blogger Sans";
  font-weight: 300;
  font-style: normal;
  src: url("../assets/fonts/bloggersans-light.woff2") format("woff2");
}
@font-face {
  font-family: "Blogger Sans";
  font-weight: 400;
  font-style: normal;
  src: url("../assets/fonts/bloggersans.woff") format("woff");
  src: url("../assets/fonts/bloggersans.woff2") format("woff2");
}
@font-face {
  font-family: "Blogger Sans";
  font-weight: 500;
  font-style: normal;
  src: url("../assets/fonts/bloggersans-medium.woff") format("woff");
  src: url("../assets/fonts/bloggersans-medium.woff2") format("woff2");
}
@font-face {
  font-family: "Blogger Sans";
  font-weight: 700;
  font-style: normal;
  src: url("../assets/fonts/bloggersans-bold.woff") format("woff");
  src: url("../assets/fonts/bloggersans-bold.woff2") format("woff2");
}
main {
  min-width: 320px;
}
img {
  max-width: 100%;
  height: auto;
}
a {
  text-decoration: none;
  cursor: pointer;
}
ul {
  padding: 0px;
  margin: 0px;
}
li {
  list-style: none;
}
button {
  cursor: pointer;
}
.visually-hidden {
  position: absolute;
  width: 1px;
  height: 1px;
  margin: -1px;
  border: 0;
  padding: 0;
  white-space: nowrap;
  clip-path: inset(100%);
  clip: rect(0 0 0 0);
  overflow: hidden;
}
.text-hidden {
  font-size: 0px;
}

</style>
