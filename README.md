/* =========================================
   IVORY · PLANTILLA FLOR · ROSA Y DORADO
========================================= */

body {
  background: #fff7f7;
  color: #70535b;
}

.opening-screen {
  background:
    radial-gradient(circle at 50% 45%, rgba(255,220,230,.8), transparent 42%),
    radial-gradient(circle at 15% 20%, rgba(255,255,255,.8), transparent 25%),
    linear-gradient(145deg, #f8e5e9 0%, #e9c4ce 50%, #fdf5f0 100%);
}

.opening-name,
.hero-name {
  color: #fffaf8;
  text-shadow:
    0 0 4px #fff,
    0 0 12px #e8bdc8,
    0 0 28px #d4a0ad;
}

.crown,
.important-crown {
  color: #d4af68;
  text-shadow: 0 0 8px #fff1c9, 0 0 20px #d4af68;
}

.opening-small,
.opening-title,
.hero-small,
.hero-date {
  color: #98717a;
  text-shadow: none;
}

.open-button,
.photos-button,
.whatsapp {
  color: #fff;
  border: 1px solid #d4af68;
  background: linear-gradient(135deg, #d9aab7, #bd8294);
  box-shadow: 0 5px 18px rgba(180,125,143,.2);
}

.open-button:hover,
.photos-button:hover,
.whatsapp:hover {
  box-shadow: 0 5px 25px rgba(180,125,143,.35);
}

.hero {
  background:
    radial-gradient(circle at center, rgba(255,255,255,.75), transparent 48%),
    linear-gradient(160deg, #f9e9ec, #e9c4ce, #fff7f2);
}

section {
  background: #fff8f7;
}

.section-title {
  color: #bd8294;
  text-shadow: 0 2px 8px rgba(212,175,104,.2);
}

.story,
.photos-text,
.alias-intro,
.dress-text,
.event-place,
.confirm {
  color: #80636a;
}

.event-card,
.photos-share {
  border: 1px solid rgba(212,175,104,.55);
  background: linear-gradient(145deg, #fffdfb, #f9e9ec);
  box-shadow: 0 8px 28px rgba(190,145,155,.12);
}

.event-date {
  color: #bd8294;
}

.event-time {
  color: #98717a;
}

.btn,
.copy-btn {
  color: #9b7180;
  border: 1px solid #d4af68;
  background: #fffaf8;
}

.btn:hover,
.copy-btn:hover {
  background: #f8e5e9;
}

.important-section {
  background: radial-gradient(circle at center, #f5e1e5, transparent 65%);
}

.important-title {
  color: #bd8294;
}

.important-text {
  color: #80636a;
}

.important-text strong {
  color: #c99a55;
  text-shadow: 0 0 8px rgba(212,175,104,.35);
}

.dress-main {
  color: #bd8294;
}

.mate-important {
  color: #80636a;
  border-color: rgba(212,175,104,.5);
}

.mate-important strong {
  color: #c99a55;
}

.count-box {
  background: #fffdfb;
  border: 1px solid rgba(212,175,104,.55);
}

.count-number {
  color: #bd8294;
}

.count-label {
  color: #98717a;
}

.alias {
  color: #bd8294;
  border-color: #d4af68;
  background: #fffdfb;
}

.gift-options {
  color: #d4af68;
}

.music-button {
  color: #fff;
  background: #c18b9b;
  border-color: #d4af68;
}

footer {
  color: #98717a;
  background: #f2dfe4;
  border-color: rgba(212,175,104,.5);
}

/* Mariposas en rosa con detalles dorados */
.butterfly svg path,
.photo-butterfly svg path {
  fill: #e8b9c5 !important;
  stroke: #d4af68 !important;
}

.butterfly svg ellipse,
.photo-butterfly svg ellipse {
  fill: #d4af68 !important;
}

.butterfly svg circle,
.photo-butterfly svg circle {
  fill: #fff9f3 !important;
}

.butterfly,
.photo-butterfly {
  filter: drop-shadow(0 0 7px rgba(212,175,104,.5));
}

/* Destellos dorados */
.sparkle {
  background: #fff2c9;
  box-shadow:
    0 0 5px #fff,
    0 0 13px #e7c77e,
    0 0 22px rgba(212,175,104,.7);
}

.sparkle.big {
  box-shadow:
    0 0 7px #fff,
    0 0 18px #e7c77e,
    0 0 30px #d4af68;
}

/* Galería */
.photo-frame img {
  border: 3px solid #fffaf8;
  border-radius: 18px;
  box-shadow: 0 8px 25px rgba(160,110,125,.2);
}

@media (max-width:650px) {
  .opening-screen {
    padding: 15px;
  }
}
