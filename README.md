@i1xfi url("https://fonts.googleapis.com/css2?family=Libre+Baskerville:wght@400;700&display=swap");

html,
body {
position: relative;
  height: 100%;
}
body {
  background: #eee;
  font-family: Helvetica Neue, Helvetica, Arial, sans-serif;
  font-size: 14px;
  color: #000;
  margin: 0;
  padding: 0;
  overflow-x: hidden;
}
.swiper {
  max-width: 50%;
  overflow: visible;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}
.swiper-slide {
  background-position: center;
  background-size: cover;
  width: 300px;
  height: 300px;
}

.swiper-slide::after {
  position: absolute;
  content: "";
  inset: 0;
  width: 100%;
  aspect-ratio: 1/1;
  border-radius: 50%;
  background: linear-gradient(to bottom right, #b8b8b88f, #ffffff5e);
}
.swiper-slide-active::after {
  background: none;
}
.swiper-slide > div {
  text-align: center;
  display: none;
  opacity: 0;
}
.swiper-slide-active div {
  display: block;
  opacity: 1;
}

.swiper-slide h2 {
  font-size: 1.2rem;
  font-family: "Libre Baskerville", serif;
  position: relative;
}

.swiper-slide h2::after {
  position: absolute;
  content: "";
  bottom: -20px;
  left: 50%;
  transform: translateX(-50%);
  height: 2px;
  background: linear-gradient(#e66465, #9198e5);
}

@keyframes line {
  0% {
    }
}

.swiper-slide-active h2::after {
  animation: line 0.5s linear forwards;
}
.swiper-slide img {
  display: block;
  width: 100%;
  object-fit: cover;
  box-shadow: 0px 3px 17px rgb(0 0 0 / 25%);
  border-radius: 50%;
  aspect-ratio: 1/1;
}

@media (min-width: 768px) {
  .swiper-slide h2 {
    font-size: 2rem;
  }
}
