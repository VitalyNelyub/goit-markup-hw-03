# goit-markup-hw-01
<li>
<a href="https://hellenglish.goit.global">https://hellenglish.goit.global/</a>
</li>

rel="noreferrer noopener"

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

/* --------------------------------Початок шапки --------------------------------------------*/
.head-logo {
  font-family: 'Raleway';
  font-style: normal;
  font-weight: 700;
  font-size: 26px;
  line-height: 1.19;
  letter-spacing: 0.03em;
  color: #2196f3;
  text-decoration: none;
}
.logo-style {
  color: #000000;
}

.head-list-link {
  font-style: normal;
  font-weight: 500;
  font-size: 14px;
  line-height: 1.14;
  letter-spacing: 0.02em;
  color: #212121;
}

.head-list {
  list-style: none;
}

.head-list-link {
  text-decoration: none;
}

.head-list-link:hover,
.head-list-link:focus {
  color: #2196f3;
}

.contact-link {
  font-family: 'Roboto';
  font-weight: 500;
  font-size: 14px;
  line-height: 1.14;
  letter-spacing: 0.02em;
  color: #757575;
}

.contact-link:hover,
.contact-link:focus {
  color: #2196f3;
}

.contact-link {
  text-decoration: none;
}

.head-contacts {
  list-style: none;
}
/* --------------------------------Кінець шапки --------------------------------------------*/

/* ------------------------------------Герой---------------------------------------------- */
.hero {
  background-color: #2f303a;
}

.hero-head {
  font-family: 'Roboto';
  font-weight: 900;
  font-size: 44px;
  line-height: 1.36;
  text-align: center;
  letter-spacing: 0.06em;
  text-transform: uppercase;
  color: #ffffff;
}

.hero-btn {
  font-weight: 700;
  font-size: 16px;
  line-height: 1.88;
  display: flex;
  align-items: center;
  text-align: center;
  letter-spacing: 0.06em;
  color: #ffffff;
  background-color: #2196f3;
  cursor: pointer;
}

/* -------------------------------Кінеці герой--------------------------------------- */

/* -------------------------------Main----------------------------------------------- */

/* ----------------------------------Кінець main ----------------------------------*/

/* --------------------------------Підвал---------------------------------------- */
.footer {
  background-color: #2f303a;
}

.footer-logo {
  font-family: 'Raleway';
  font-style: normal;
  font-weight: 700;
  font-size: 26px;
  line-height: 1.19;
  letter-spacing: 0.03em;
  color: #2196f3;
  text-decoration: none;
}

.logo-footer-style {
  color: #ffffff;
}

.footer-adress {
  font-family: 'Roboto';
  font-style: normal;
  font-weight: 400;
  font-size: 14px;
  line-height: 1.71;
  letter-spacing: 0.03em;
  color: #ffffff;
  text-decoration: none;
}

.footer-link {
  font-family: 'Roboto';
  font-style: normal;
  font-weight: 400;
  font-size: 14px;
  line-height: 1.71;
  letter-spacing: 0.03em;
  color: rgba(255, 255, 255, 0.6);
  text-decoration: none;
}
.footer-list {
  list-style: none;
}

.footer-adress:hover,
.footer-adress:focus {
  color: #2196f3;
}

.footer-link:hover,
.footer-link:focus {
  color: #2196f3;
}




<!-- Шапка сторінки портфоліо -->
    <header class="header">
      <a class="head-logo" href="./index.html">Web<span class="logo-style">Studio</span></a>
      <nav class="head-nav">
        <ul class="head-list">
          <li>
            <a  class="head-list-link" href="./index.html">Студія</a>
          </li>
          <li>
            <a class="head-list-link" href="./portfolio.html">Портфоліо</a>
          </li>
          <li>
            <a class="head-list-link" href="">Контакти</a>
          </li>
        </ul>
      </nav>
      <ul class="head-contacts">
        <li><a class="contact-link" href="mailto:info@devstudio.com">info@devstudio.com</a></li>
        <li><a class="contact-link" href="tel:+380961111111">+38 096 111 11 11</a></li>
      </ul>
    </header>




    <!--Підвал-->
    <footer class="footer">
      <h2>Контактні данні</h2>
      <a class="footer-logo" href="./index.html">Web<span class="logo-footer-style">Studio</span></a>
      <address>
        <ul class="footer-list">
          <li>
            <a class="footer-adress"
              href="https://goo.gl/maps/V1AfotGjKbNemnyBA"
              target="_blank"
              rel="noreferrer noopener"
              >м. Київ, пр-т Лесі Українки, 26</a
            >
          </li>
          <li><a class="footer-link" href="mailto:info@devstudio.com">info@devstudio.com</a></li>
          <li><a class="footer-link" href="tel:+380961111111">+38 096 111 11 11</a></li>
        </ul>
      </address>
    </footer>