<template>
  <!-- ФУТЕР -->
  <footer class="page-footer">
    <div class="page-footer__container">
      <a class="page-footer__contacts" href="index.html">
        <span class="text-hidden">Главная</span>
        <div class="page-footer__logo">
          <picture>
            <source
              media="(min-width: 1440px)"
              srcset="img/logo-desktop-blue@2x.png"
            />
            <source
              media="(min-width: 768px)"
              srcset="img/logo-desktop-blue@2x.png"
            />
            <img src="@/assets/img/logo-mobile-blue@2x.png" alt="logo" />
          </picture>
        </div>
      </a>
      <div class="page-footer__social">
        <a
          class="page-footer__link"
          href="https://www.facebook.com/htmlacademy"
        >
          <svg
            class="page-footer__icon-fb"
            width="11"
            height="21"
            viewBox="0 0 11 21"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              d="M7.48786 20.7695H2.12929V11.2513H0V6.54393H2.06643C1.90929 4.41158 2.30214 2.85474 3.26071 1.79225C3.71777 1.32067 4.27461 0.94388 4.89562 0.685966C5.51662 0.428052 6.18812 0.294698 6.86714 0.294434L10.6229 0.294434V4.83215H7.66857C7.49452 5.3871 7.42799 5.9669 7.47214 6.54393H10.615V11.2513H7.47214L7.48786 20.7695ZM3.31571 19.6627H6.28571V10.1446H9.42857V7.67283H6.28571V7.11207C6.28571 5.63639 6.28571 4.31566 7.07143 3.82131L7.22071 3.72539H9.42857V1.40119H6.89857C6.38444 1.39495 5.87465 1.49025 5.40225 1.68092C4.92986 1.87158 4.50541 2.15335 4.15643 2.50795C3.37071 3.41549 3.04857 4.93544 3.29214 7.03829L3.37071 7.65069H1.17857V10.1446H3.31571V19.6627Z"
              fill="#192144"
            />
          </svg>
          <span class="text-hidden">Мы в Фейсбуке</span></a
        >
        <a class="page-footer__link" href="https://vk.com/htmlacademy">
          <svg
            class="page-footer__icon-vk"
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
          <span class="text-hidden">Мы в Вконтакте</span></a
        >
        <a
          class="page-footer__link"
          href="https://www.instagram.com/htmlacademy"
        >
          <svg
            class="page-footer__icon-inst"
            width="18"
            height="18"
            viewBox="0 0 18 18"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <g clip-path="url(#clip0)">
              <path
                d="M12.9601 2.03319C13.8188 2.03506 14.6418 2.37148 15.249 2.96885C15.8562 3.56621 16.1982 4.37586 16.2001 5.22066V13.0122C16.1982 13.857 15.8562 14.6667 15.249 15.2641C14.6418 15.8614 13.8188 16.1978 12.9601 16.1997H5.04009C4.18262 16.196 3.36147 15.8587 2.75581 15.2616C2.15016 14.6644 1.80919 13.8558 1.80729 13.0122V5.22066C1.80919 4.37709 2.15016 3.5685 2.75581 2.97134C3.36147 2.37418 4.18262 2.03693 5.04009 2.03319H12.9601ZM12.9601 0.970703H5.04009C3.89436 0.970703 2.79555 1.41846 1.98539 2.21549C1.17523 3.01251 0.720093 4.0935 0.720093 5.22066L0.720093 13.0122C0.720093 14.1394 1.17523 15.2204 1.98539 16.0174C2.79555 16.8144 3.89436 17.2622 5.04009 17.2622H12.9601C14.1058 17.2622 15.2046 16.8144 16.0148 16.0174C16.8249 15.2204 17.2801 14.1394 17.2801 13.0122V5.22066C17.2801 4.0935 16.8249 3.01251 16.0148 2.21549C15.2046 1.41846 14.1058 0.970703 12.9601 0.970703V0.970703Z"
                fill="#192144"
              />
              <path
                d="M9.00703 5.98486C9.63787 5.98486 10.2545 6.16889 10.7791 6.51369C11.3036 6.85848 11.7124 7.34855 11.9538 7.92193C12.1953 8.4953 12.2584 9.12622 12.1353 9.73491C12.0123 10.3436 11.7085 10.9027 11.2624 11.3416C10.8163 11.7804 10.248 12.0793 9.62929 12.2003C9.01057 12.3214 8.36924 12.2593 7.78642 12.0218C7.2036 11.7843 6.70545 11.3821 6.35497 10.8661C6.00449 10.35 5.81743 9.74336 5.81743 9.12274C5.81648 8.71041 5.89833 8.30195 6.05829 7.92082C6.21824 7.53969 6.45315 7.19341 6.74952 6.90184C7.04589 6.61027 7.39789 6.37918 7.7853 6.22181C8.17271 6.06445 8.5879 5.98392 9.00703 5.98486V5.98486ZM9.00703 4.92237C8.16228 4.92097 7.33609 5.16612 6.63301 5.62681C5.92993 6.0875 5.38156 6.74302 5.0573 7.51042C4.73304 8.27781 4.64746 9.12259 4.81139 9.93784C4.97532 10.7531 5.38139 11.5022 5.97822 12.0903C6.57504 12.6785 7.3358 13.0792 8.16422 13.2419C8.99264 13.4045 9.85148 13.3218 10.6321 13.0041C11.4127 12.6863 12.0799 12.148 12.5494 11.4571C13.0188 10.7662 13.2694 9.9538 13.2694 9.12274C13.2704 8.57148 13.1608 8.02544 12.947 7.51586C12.7333 7.00629 12.4194 6.54319 12.0236 6.15306C11.6277 5.76293 11.1575 5.45342 10.6398 5.24224C10.1222 5.03107 9.56738 4.92237 9.00703 4.92237Z"
                fill="#192144"
              />
              <path
                d="M13.4282 5.73083C13.961 5.73083 14.393 5.30588 14.393 4.78168C14.393 4.25747 13.961 3.83252 13.4282 3.83252C12.8953 3.83252 12.4634 4.25747 12.4634 4.78168C12.4634 5.30588 12.8953 5.73083 13.4282 5.73083Z"
                fill="#192144"
              />
            </g>
            <defs>
              <clipPath id="clip0">
                <rect
                  width="18"
                  height="17.7081"
                  fill="white"
                  transform="translate(0 0.261719)"
                />
              </clipPath>
            </defs>
          </svg>
          <span class="text-hidden">Мы в Инстаграме</span></a
        >
      </div>
      <div class="page-footer__copyright">
        <b class="page-footer__text"
          >Разработано:
          <a
            class="page-footer__copyright-link"
            href="https://htmlacademy.ru/intensive/adaptive"
          >
            <span class="text-hidden">HTML Academy</span></a
          >
        </b>
      </div>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style scoped>
.page-footer {
  min-width: 100%;
  width: 100%;
  background-color: #ffffff;
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
  background-color: #ffffff;
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
  background-color: #ffbd30;
}
.page-footer__social a:active {
  background-color: #ffbd30;
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
  background-color: #ffd74b;
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
  background-image: url(../../assets/img/html-footer-icon.svg);
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
</style>