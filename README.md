<!DOCTYPE html>
<html lang="fr" dir="ltr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover">

<title>Menuiserie Aluminium & PVC | Fabrication & Installation</title>

<meta
  name="description"
  content="Fabrication et installation de solutions en aluminium et PVC : fenêtres, portes, cuisines, parois de douche et réalisations sur mesure."
>

<meta name="theme-color" content="#171717">

<link
  rel="icon"
  href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'%3E%3Ctext y='.9em' font-size='90'%3E🪟%3C/text%3E%3C/svg%3E"
>

<style>
/* =========================================================
   RESET / VARIABLES
========================================================= */

:root {
  --ivory: #f7f6f2;
  --white: #ffffff;
  --black: #111111;
  --graphite: #171717;
  --charcoal: #242424;
  --gray: #777777;
  --light-gray: #dddddd;
  --bronze: #b59a6a;

  --container: 1280px;
  --nav-height: 82px;

  box-sizing: border-box;
}

*,
*::before,
*::after {
  box-sizing: inherit;
}

html {
  scroll-behavior: smooth;
  scroll-padding-top: 90px;
}

body {
  margin: 0;
  padding: 0;
  background: var(--ivory);
  color: var(--graphite);
  font-family:
    "Helvetica Neue",
    Helvetica,
    Arial,
    "Segoe UI",
    sans-serif;
  overflow-x: hidden;
  -webkit-font-smoothing: antialiased;
}

body.no-scroll {
  overflow: hidden;
}

img {
  display: block;
  max-width: 100%;
}

button,
input,
textarea,
select {
  font: inherit;
}

button {
  border: 0;
  cursor: pointer;
}

a {
  color: inherit;
  text-decoration: none;
}

.container {
  width: min(var(--container), calc(100% - 12vw));
  margin-inline: auto;
}

/* =========================================================
   ACCESSIBILITY
========================================================= */

.sr-only {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  white-space: nowrap;
  border: 0;
}

/* =========================================================
   NAVIGATION
========================================================= */

.nav {
  position: fixed;
  inset: 0 0 auto 0;
  z-index: 1000;
  transition:
    background-color 0.3s ease,
    box-shadow 0.3s ease;
}

.nav.scrolled {
  background: rgba(247, 246, 242, 0.94);
  backdrop-filter: blur(14px);
  box-shadow: 0 1px 0 rgba(0, 0, 0, 0.08);
}

.nav-inner {
  min-height: var(--nav-height);
  width: min(var(--container), calc(100% - 12vw));
  margin-inline: auto;

  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 30px;

  transition: min-height 0.3s ease;
}

.logo {
  flex-shrink: 0;
  font-size: 0.85rem;
  font-weight: 600;
  line-height: 1.2;
}

.logo-main {
  display: block;
}

.logo-sub {
  display: block;
  margin-top: 4px;
  color: var(--gray);
  font-size: 0.68rem;
  font-weight: 400;
  letter-spacing: 0.1em;
  text-transform: uppercase;
}

.nav-links {
  display: flex;
  align-items: center;
  gap: 2vw;
  margin: 0;
  padding: 0;
  list-style: none;
}

.nav-links a {
  position: relative;
  padding: 5px 0;
  font-size: 0.82rem;
}

.nav-links a::after {
  content: "";
  position: absolute;
  left: 0;
  bottom: 0;

  width: 0;
  height: 1px;

  background: currentColor;
  transition: width 0.25s ease;
}

.nav-links a:hover::after {
  width: 100%;
}

.nav-right {
  display: flex;
  align-items: center;
  gap: 20px;
}

.lang-switch {
  display: flex;
  align-items: center;
  gap: 8px;
}

.lang-switch button {
  padding: 3px;
  background: transparent;
  color: inherit;
  opacity: 0.4;
  font-size: 0.72rem;
  font-weight: 500;
  transition: opacity 0.2s ease;
}

.lang-switch button.active {
  opacity: 1;
  font-weight: 700;
}

.nav-cta {
  display: inline-flex;
  align-items: center;
  justify-content: center;

  padding: 10px 20px;

  background: var(--graphite);
  color: var(--ivory);

  border-radius: 2px;

  font-size: 0.78rem;
  white-space: nowrap;

  transition:
    background 0.25s ease,
    transform 0.25s ease;
}

.nav-cta:hover {
  background: var(--bronze);
  transform: translateY(-1px);
}

.burger {
  display: none;
  width: 28px;
  height: 24px;

  flex-direction: column;
  justify-content: center;
  gap: 5px;

  padding: 0;

  background: transparent;
}

.burger span {
  display: block;
  width: 100%;
  height: 1px;
  background: currentColor;
}

/* =========================================================
   MOBILE MENU
========================================================= */

.mobile-menu {
  position: fixed;
  inset: 0;
  z-index: 2000;

  display: flex;
  flex-direction: column;
  justify-content: center;
  gap: 22px;

  padding: 8vh 8vw;

  background: var(--graphite);
  color: var(--ivory);

  transform: translateY(-100%);
  transition: transform 0.45s cubic-bezier(0.7, 0, 0.3, 1);
}

.mobile-menu.open {
  transform: translateY(0);
}

.mobile-menu a {
  font-size: 1.5rem;
  font-weight: 300;
}

.mobile-menu .m-cta {
  width: fit-content;
  margin-top: 15px;

  padding: 13px 24px;

  border: 1px solid rgba(255, 255, 255, 0.5);

  font-size: 0.95rem;
}

.mobile-menu .m-lang {
  display: flex;
  gap: 15px;
  margin-top: 10px;
}

.mobile-menu .m-lang button {
  background: transparent;
  color: var(--ivory);
  opacity: 0.5;
}

.mobile-menu .m-lang button.active {
  opacity: 1;
  text-decoration: underline;
}

/* =========================================================
   HERO
========================================================= */

.hero {
  position: relative;

  width: 100%;
  height: 100svh;
  min-height: 580px;

  overflow: hidden;
  background: var(--graphite);
}

.hero-image {
  position: absolute;
  inset: 0;

  width: 100%;
  height: 100%;

  object-fit: cover;

  transform: scale(1.06);
  animation: heroZoom 10s ease-out forwards;
}

@keyframes heroZoom {
  to {
    transform: scale(1);
  }
}

.hero-overlay {
  position: absolute;
  inset: 0;

  background:
    linear-gradient(
      to bottom,
      rgba(0, 0, 0, 0.12) 0%,
      rgba(0, 0, 0, 0.08) 45%,
      rgba(0, 0, 0, 0.72) 100%
    );
}

.hero-content {
  position: absolute;

  left: 6vw;
  right: 6vw;
  bottom: 11vh;

  max-width: 780px;

  color: var(--ivory);
}

.hero-title {
  margin: 0;

  font-size: clamp(2.5rem, 6vw, 5rem);
  font-weight: 300;
  line-height: 1.04;
  letter-spacing: -0.02em;

  animation: rise 0.9s 0.2s ease both;
}

.hero-sub {
  margin: 22px 0 0;

  max-width: 580px;

  color: rgba(247, 246, 242, 0.85);

  font-size: clamp(1rem, 1.6vw, 1.15rem);
  font-weight: 300;
  line-height: 1.6;

  animation: rise 0.9s 0.4s ease both;
}

.hero-buttons {
  display: flex;
  flex-wrap: wrap;
  gap: 14px;

  margin-top: 35px;

  animation: rise 0.9s 0.6s ease both;
}

@keyframes rise {
  from {
    opacity: 0;
    transform: translateY(24px);
  }

  to {
    opacity: 1;
    transform: translateY(0);
  }
}

.btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;

  min-height: 50px;
  padding: 14px 27px;

  border-radius: 2px;

  font-size: 0.88rem;

  transition:
    background 0.25s ease,
    color 0.25s ease,
    transform 0.25s ease,
    border-color 0.25s ease;
}

.btn-primary {
  background: var(--ivory);
  color: var(--graphite);
}

.btn-primary:hover {
  background: var(--bronze);
  color: var(--white);
  transform: translateY(-2px);
}

.btn-outline {
  border: 1px solid rgba(247, 246, 242, 0.55);
  color: var(--ivory);
}

.btn-outline:hover {
  border-color: var(--ivory);
  background: rgba(255, 255, 255, 0.1);
}

.scroll-hint {
  position: absolute;
  right: 5vw;
  bottom: 4vh;

  color: var(--ivory);

  font-size: 0.68rem;
  letter-spacing: 0.18em;
  text-transform: uppercase;

  writing-mode: vertical-rl;
  opacity: 0.7;
}

/* =========================================================
   GENERAL SECTIONS
========================================================= */

section {
  position: relative;
}

.section-padding {
  padding: 12vh 0;
}

.section-head {
  display: flex;
  align-items: flex-end;
  justify-content: space-between;
  gap: 30px;

  margin-bottom: 55px;
}

.section-head h2 {
  margin: 0;

  font-size: clamp(2rem, 3.6vw, 3rem);
  font-weight: 300;
  line-height: 1.15;
}

.section-head p {
  max-width: 380px;
  margin: 0;

  color: var(--gray);

  font-size: 0.95rem;
  line-height: 1.7;
}

/* =========================================================
   SCROLL REVEAL
========================================================= */

.reveal {
  opacity: 0;
  transform: translateY(30px);

  transition:
    opacity 0.8s ease,
    transform 0.8s ease;
}

.reveal.visible {
  opacity: 1;
  transform: translateY(0);
}

/* =========================================================
   INTRO
========================================================= */

.intro {
  padding: 14vh 0 9vh;
}

.eyebrow {
  margin-bottom: 18px;

  color: var(--bronze);

  font-size: 0.74rem;
  letter-spacing: 0.15em;
  text-transform: uppercase;
}

.intro h2 {
  max-width: 850px;
  margin: 0;

  font-size: clamp(2rem, 4vw, 3.2rem);
  font-weight: 300;
  line-height: 1.2;
}

.intro p {
  max-width: 580px;
  margin: 25px 0 0;

  color: var(--gray);

  font-size: 1rem;
  line-height: 1.8;
}

/* =========================================================
   FEATURED
========================================================= */

.featured {
  padding: 6vh 0 12vh;
}

.featured-grid {
  display: grid;
  grid-template-columns: 1.25fr 1fr;
}

.featured-image {
  min-height: 500px;
  overflow: hidden;
  background: #ddd;
}

.featured-image img {
  width: 100%;
  height: 100%;
  object-fit: cover;

  transition: transform 1s ease;
}

.featured-image:hover img {
  transform: scale(1.04);
}

.featured-text {
  display: flex;
  flex-direction: column;
  justify-content: center;

  padding: 8vh 5vw;

  background: var(--graphite);
  color: var(--ivory);
}

.featured-number {
  margin-bottom: 18px;

  color: var(--bronze);

  font-size: 0.75rem;
  letter-spacing: 0.15em;
}

.featured-text h3 {
  margin: 0;

  font-size: clamp(1.8rem, 3vw, 2.5rem);
  font-weight: 300;
  line-height: 1.2;
}

.featured-text p {
  max-width: 520px;
  margin: 20px 0 0;

  color: rgba(247, 246, 242, 0.68);

  font-size: 0.98rem;
  line-height: 1.75;
}

.featured-text .btn {
  width: fit-content;
  margin-top: 32px;
}

/* =========================================================
   PRODUCTS
========================================================= */

.products {
  padding: 12vh 0;
}

.product-grid {
  display: grid;
  grid-template-columns: repeat(4, 1fr);

  width: 100%;
}

.product-card {
  position: relative;

  aspect-ratio: 3 / 4;

  overflow: hidden;

  background: #ddd;
}

.product-card img {
  width: 100%;
  height: 100%;

  object-fit: cover;

  transition: transform 0.8s ease;
}

.product-card:hover img {
  transform: scale(1.07);
}

.product-card::after {
  content: "";

  position: absolute;
  inset: 0;

  background:
    linear-gradient(
      to bottom,
      transparent 40%,
      rgba(0, 0, 0, 0.8) 100%
    );
}

.product-info {
  position: absolute;
  left: 22px;
  right: 22px;
  bottom: 22px;

  z-index: 2;

  color: var(--white);
}

.product-number {
  display: block;
  margin-bottom: 6px;

  color: var(--bronze);

  font-size: 0.68rem;
  letter-spacing: 0.15em;
}

.product-info h3 {
  margin: 0;

  font-size: 1.05rem;
  font-weight: 400;
  line-height: 1.35;
}

/* =========================================================
   GALLERY
========================================================= */

.gallery {
  padding: 12vh 0;
}

.filters {
  display: flex;
  flex-wrap: wrap;
  gap: 9px;

  margin-bottom: 45px;
}

.filter-button {
  padding: 9px 19px;

  border: 1px solid rgba(23, 23, 23, 0.18);
  border-radius: 30px;

  background: transparent;
  color: var(--graphite);

  font-size: 0.78rem;

  transition:
    background 0.25s ease,
    color 0.25s ease,
    border-color 0.25s ease;
}

.filter-button:hover,
.filter-button.active {
  border-color: var(--graphite);
  background: var(--graphite);
  color: var(--ivory);
}

.gallery-grid {
  columns: 4 220px;
  column-gap: 14px;
}

.gallery-item {
  position: relative;

  margin-bottom: 14px;

  break-inside: avoid;
  overflow: hidden;

  border-radius: 2px;

  background: #ddd;

  cursor: pointer;
}

.gallery-item.hidden {
  display: none;
}

.gallery-item img {
  width: 100%;
  height: auto;

  transition:
    transform 0.7s ease,
    opacity 0.3s ease;
}

.gallery-item:hover img {
  transform: scale(1.05);
}

.gallery-overlay {
  position: absolute;
  inset: auto 0 0 0;

  padding: 35px 14px 14px;

  color: var(--white);

  background:
    linear-gradient(
      to bottom,
      transparent,
      rgba(0, 0, 0, 0.75)
    );

  opacity: 0;

  transition: opacity 0.3s ease;
}

.gallery-item:hover .gallery-overlay {
  opacity: 1;
}

.gallery-label {
  font-size: 0.72rem;
  text-transform: uppercase;
  letter-spacing: 0.08em;
}

/* =========================================================
   LIGHTBOX
========================================================= */

.lightbox {
  position: fixed;
  inset: 0;

  z-index: 3000;

  display: none;
  align-items: center;
  justify-content: center;

  padding: 50px;

  background: rgba(10, 10, 10, 0.97);
}

.lightbox.open {
  display: flex;
}

.lightbox-image {
  max-width: 90vw;
  max-height: 84vh;

  width: auto;
  height: auto;

  object-fit: contain;

  box-shadow: 0 20px 60px rgba(0, 0, 0, 0.5);
}

.lightbox-close,
.lightbox-prev,
.lightbox-next {
  position: absolute;

  display: flex;
  align-items: center;
  justify-content: center;

  width: 50px;
  height: 50px;

  background: transparent;
  color: var(--white);

  font-size: 2rem;

  opacity: 0.7;

  transition: opacity 0.2s ease;
}

.lightbox-close:hover,
.lightbox-prev:hover,
.lightbox-next:hover {
  opacity: 1;
}

.lightbox-close {
  top: 20px;
  right: 25px;
}

.lightbox-prev {
  left: 20px;
  top: 50%;
  transform: translateY(-50%);
}

.lightbox-next {
  right: 20px;
  top: 50%;
  transform: translateY(-50%);
}

/* =========================================================
   SERVICES
========================================================= */

.services {
  padding: 12vh 0;
  background: var(--graphite);
  color: var(--ivory);
}

.services .section-head p {
  color: rgba(247, 246, 242, 0.55);
}

.service-row {
  display: grid;
  grid-template-columns: 90px 1fr 360px;
  align-items: baseline;
  gap: 40px;

  padding: 32px 0;

  border-top: 1px solid rgba(247, 246, 242, 0.14);
}

.service-row:last-child {
  border-bottom: 1px solid rgba(247, 246, 242, 0.14);
}

.service-number {
  color: var(--bronze);

  font-size: clamp(1.7rem, 3vw, 2.5rem);
  font-weight: 200;
}

.service-row h3 {
  margin: 0;

  font-size: clamp(1.15rem, 2vw, 1.55rem);
  font-weight: 300;
}

.service-row p {
  max-width: 360px;
  margin: 0;

  color: rgba(247, 246, 242, 0.55);

  font-size: 0.9rem;
  line-height: 1.65;
}

/* =========================================================
   ABOUT
========================================================= */

.about {
  padding: 14vh 0;
}

.about-inner {
  max-width: 800px;
}

.about h2 {
  margin: 0;

  font-size: clamp(2rem, 3.8vw, 3rem);
  font-weight: 300;
  line-height: 1.25;
}

.about p {
  margin: 25px 0 0;

  color: var(--gray);

  font-size: 1rem;
  line-height: 1.8;
}

/* =========================================================
   CONTACT
========================================================= */

.contact {
  padding: 15vh 0 12vh;

  background: var(--graphite);
  color: var(--ivory);
}

.contact h2 {
  max-width: 750px;
  margin: 0;

  font-size: clamp(2.3rem, 5vw, 4rem);
  font-weight: 300;
  line-height: 1.1;
}

.contact-intro {
  max-width: 500px;
  margin: 22px 0 0;

  color: rgba(247, 246, 242, 0.65);

  font-size: 1rem;
  line-height: 1.7;
}

.contact-buttons {
  display: flex;
  flex-wrap: wrap;
  gap: 15px;

  margin-top: 45px;
}

.whatsapp-button {
  display: inline-flex;
  align-items: center;
  gap: 12px;

  padding: 18px 30px;

  background: var(--white);
  color: var(--graphite);

  border-radius: 2px;

  font-size: 0.95rem;

  transition:
    transform 0.25s ease,
    background 0.25s ease,
    color 0.25s ease;
}

.whatsapp-button:hover {
  background: var(--bronze);
  color: var(--white);
  transform: translateY(-2px);
}

.contact-meta {
  display: flex;
  flex-wrap: wrap;
  gap: 60px;

  margin-top: 60px;
  padding-top: 30px;

  border-top: 1px solid rgba(247, 246, 242, 0.15);
}

.contact-meta-item span {
  display: block;

  margin-bottom: 8px;

  color: var(--bronze);

  font-size: 0.68rem;
  letter-spacing: 0.1em;
  text-transform: uppercase;
}

.contact-meta-item a {
  color: var(--ivory);
  font-size: 0.95rem;
  font-weight: 300;
}

.contact-meta-item a:hover {
  text-decoration: underline;
}

/* =========================================================
   FOOTER
========================================================= */

.footer {
  padding: 6vh 0;

  background: var(--ivory);
}

.footer-inner {
  display: flex;
  align-items: center;
  justify-content: space-between;
  flex-wrap: wrap;
  gap: 20px;

  color: var(--gray);

  font-size: 0.78rem;
}

.footer-links {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
}

.footer-links a:hover {
  color: var(--graphite);
}

/* =========================================================
   FLOATING WHATSAPP
========================================================= */

.whatsapp-float {
  position: fixed;

  right: 24px;
  bottom: calc(24px + env(safe-area-inset-bottom));

  z-index: 900;

  display: flex;
  align-items: center;
  justify-content: center;

  width: 58px;
  height: 58px;

  border-radius: 50%;

  background: var(--graphite);
  color: var(--white);

  box-shadow: 0 10px 30px rgba(0, 0, 0, 0.25);

  transition:
    transform 0.25s ease,
    background 0.25s ease;
}

.whatsapp-float:hover {
  background: var(--bronze);
  transform: scale(1.08);
}

/* =========================================================
   RTL
========================================================= */

[dir="rtl"] body {
  font-family:
    "Segoe UI",
    Tahoma,
    Arial,
    sans-serif;
}

[dir="rtl"] .scroll-hint {
  right: auto;
  left: 5vw;
  writing-mode: vertical-lr;
}

[dir="rtl"] .nav-links,
[dir="rtl"] .nav-right,
[dir="rtl"] .lang-switch,
[dir="rtl"] .filters,
[dir="rtl"] .contact-meta,
[dir="rtl"] .footer-links {
  direction: rtl;
}

[dir="rtl"] .whatsapp-float {
  right: auto;
  left: 24px;
}

[dir="rtl"] .hero-content {
  text-align: right;
}

/* =========================================================
   RESPONSIVE
========================================================= */

@media (max-width: 1050px) {

  .nav-links,
  .nav-right .lang-switch,
  .nav-cta {
    display: none;
  }

  .burger {
    display: flex;
  }

  .featured-grid {
    grid-template-columns: 1fr;
  }

  .featured-image {
    min-height: 380px;
  }

  .product-grid {
    grid-template-columns: repeat(2, 1fr);
  }

  .service-row {
    grid-template-columns: 70px 1fr;
  }

  .service-row p {
    grid-column: 2;
  }

  .gallery-grid {
    columns: 2 180px;
  }
}

@media (max-width: 650px) {

  :root {
    --nav-height: 70px;
  }

  .container {
    width: calc(100% - 44px);
  }

  .hero-content {
    left: 22px;
    right: 22px;
    bottom: 12vh;
  }

  .hero-title {
    font-size: clamp(2.25rem, 12vw, 3.7rem);
  }

  .hero-buttons {
    flex-direction: column;
    align-items: stretch;
  }

  .hero-buttons .btn {
    width: 100%;
  }

  .scroll-hint {
    display: none;
  }

  .section-padding,
  .products,
  .gallery,
  .services {
    padding: 10vh 0;
  }

  .intro {
    padding: 11vh 0 8vh;
  }

  .section-head {
    align-items: flex-start;
    flex-direction: column;
    margin-bottom: 38px;
  }

  .featured-image {
    min-height: 300px;
  }

  .featured-text {
    padding: 7vh 22px;
  }

  .product-grid {
    grid-template-columns: 1fr 1fr;
  }

  .product-info {
    left: 14px;
    right: 14px;
    bottom: 15px;
  }

  .product-info h3 {
    font-size: 0.9rem;
  }

  .gallery-grid {
    columns: 1;
  }

  .service-row {
    display: flex;
    flex-direction: column;
    gap: 10px;
    padding: 25px 0;
  }

  .service-row p {
    max-width: 100%;
  }

  .contact-meta {
    flex-direction: column;
    gap: 25px;
  }

  .footer-inner {
    align-items: flex-start;
    flex-direction: column;
  }

  .lightbox {
    padding: 20px;
  }

  .lightbox-image {
    max-width: 94vw;
    max-height: 78vh;
  }

  .lightbox-prev {
    left: 4px;
  }

  .lightbox-next {
    right: 4px;
  }

  .whatsapp-float {
    right: 18px;
    bottom: calc(18px + env(safe-area-inset-bottom));
  }

  [dir="rtl"] .whatsapp-float {
    right: auto;
    left: 18px;
  }
}
</style>
</head>

<body>

<!-- NAVIGATION -->
<nav class="nav" id="nav">
  <div class="nav-inner">
    <a href="#top" class="logo" aria-label="Accueil">
      <span class="logo-main" data-i18n="logo_main">نجارة الألمنيوم و PVC</span>
      <span class="logo-sub" data-i18n="logo_sub">Aluminium & PVC</span>
    </a>
    <ul class="nav-links">
      <li><a href="#top" data-i18n="nav_home">Accueil</a></li>
      <li><a href="#produits" data-i18n="nav_products">Produits</a></li>
      <li><a href="#galerie" data-i18n="nav_gallery">Réalisations</a></li>
      <li><a href="#services" data-i18n="nav_services">Services</a></li>
      <li><a href="#apropos" data-i18n="nav_about">À propos</a></li>
      <li><a href="#contact" data-i18n="nav_contact">Contact</a></li>
    </ul>
    <div class="nav-right">
      <div class="lang-switch">
        <button type="button" data-lang-btn="fr" onclick="setLanguage('fr')">FR</button>
        <button type="button" data-lang-btn="ar" onclick="setLanguage('ar')">AR</button>
        <button type="button" data-lang-btn="en" onclick="setLanguage('en')">EN</button>
      </div>
      <a class="nav-cta" href="https://wa.me/213792106924" target="_blank" rel="noopener noreferrer" data-i18n="whatsapp">WhatsApp</a>
    </div>
    <button class="burger" type="button" onclick="toggleMobileMenu()" aria-label="Menu" aria-controls="mobileMenu" aria-expanded="false">
      <span></span><span></span><span></span>
    </button>
  </div>
</nav>

<!-- MOBILE MENU -->
<div class="mobile-menu" id="mobileMenu">
  <a href="#top" onclick="closeMobileMenu()" data-i18n="nav_home">Accueil</a>
  <a href="#produits" onclick="closeMobileMenu()" data-i18n="nav_products">Produits</a>
  <a href="#galerie" onclick="closeMobileMenu()" data-i18n="nav_gallery">Réalisations</a>
  <a href="#services" onclick="closeMobileMenu()" data-i18n="nav_services">Services</a>
  <a href="#apropos" onclick="closeMobileMenu()" data-i18n="nav_about">À propos</a>
  <a href="#contact" onclick="closeMobileMenu()" data-i18n="nav_contact">Contact</a>
  <a class="m-cta" href="https://wa.me/213792106924" target="_blank" rel="noopener noreferrer" data-i18n="whatsapp">WhatsApp</a>
  <div class="m-lang">
    <button type="button" data-lang-btn="fr" onclick="setLanguage('fr')">FR</button>
    <button type="button" data-lang-btn="ar" onclick="setLanguage('ar')">AR</button>
    <button type="button" data-lang-btn="en" onclick="setLanguage('en')">EN</button>
  </div>
</div>

<!-- HERO -->
<header class="hero" id="top">
  <img class="hero-image" src="https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=1600&q=80" alt="Réalisation en aluminium" fetchpriority="high">
  <div class="hero-overlay"></div>
  <div class="hero-content">
    <h1 class="hero-title" data-i18n-html="hero_title">Aluminium &amp; PVC,<br>pensés pour votre espace.</h1>
    <p class="hero-sub" data-i18n="hero_sub">Fabrication et installation sur mesure.</p>
    <div class="hero-buttons">
      <a class="btn btn-primary" href="https://wa.me/213792106924" target="_blank" rel="noopener noreferrer" data-i18n="hero_cta">Parler sur WhatsApp</a>
      <a class="btn btn-outline" href="#galerie" data-i18n="hero_gallery">Voir nos réalisations</a>
    </div>
  </div>
  <span class="scroll-hint" data-i18n="scroll">Défiler</span>
</header>

<!-- INTRO -->
<section class="intro">
  <div class="container reveal">
    <div class="eyebrow" data-i18n="intro_eyebrow">Savoir-faire</div>
    <h2 data-i18n="intro_title">Le savoir-faire au service de vos espaces.</h2>
    <p data-i18n="intro_text">Nous réalisons et installons des solutions en aluminium et PVC adaptées à chaque espace, du résidentiel aux projets sur mesure.</p>
  </div>
</section>

<!-- FEATURED PROJECT -->
<section class="featured">
  <div class="featured-grid reveal">
    <div class="featured-image">
      <img src="https://images.unsplash.com/photo-1556911220-e15b29be8c8f?auto=format&fit=crop&w=1200&q=80" alt="Cuisine sur mesure" loading="lazy">
    </div>
    <div class="featured-text">
      <span class="featured-number">01</span>
      <h3 data-i18n="featured_title">Créations sur mesure</h3>
      <p data-i18n="featured_text">Chaque réalisation est pensée selon les dimensions et les besoins réels de l'espace, du choix des matériaux à la pose finale.</p>
      <a class="btn btn-outline" href="#galerie" data-i18n="featured_button">Découvrir nos réalisations</a>
    </div>
  </div>
</section>

<!-- PRODUCTS -->
<section class="products" id="produits">
  <div class="container">
    <div class="section-head reveal">
      <h2 data-i18n="products_title">Produits</h2>
      <p data-i18n="products_subtitle">Une gamme complète en aluminium et PVC, fabriquée et installée sur mesure.</p>
    </div>
  </div>
  <div class="product-grid reveal">
    <a href="#galerie" class="product-card" onclick="setFilter('aluminium')">
      <img src="https://images.unsplash.com/photo-1513694203232-719a280e022f?auto=format&fit=crop&w=800&q=80" alt="Fenêtres et portes aluminium" loading="lazy">
      <div class="product-info">
        <span class="product-number">01</span>
        <h3 data-i18n="product_aluminium">Fenêtres & portes Aluminium</h3>
      </div>
    </a>
    <a href="#galerie" class="product-card" onclick="setFilter('pvc')">
      <img src="https://images.unsplash.com/photo-1503387762-592deb58ef4e?auto=format&fit=crop&w=800&q=80" alt="Fenêtres et portes PVC" loading="lazy">
      <div class="product-info">
        <span class="product-number">02</span>
        <h3 data-i18n="product_pvc">Fenêtres & portes PVC</h3>
      </div>
    </a>
    <a href="#galerie" class="product-card" onclick="setFilter('cuisines')">
      <img src="https://images.unsplash.com/photo-1556911220-e15b29be8c8f?auto=format&fit=crop&w=800&q=80" alt="Cuisines sur mesure" loading="lazy">
      <div class="product-info">
        <span class="product-number">03</span>
        <h3 data-i18n="product_kitchens">Cuisines & rangements</h3>
      </div>
    </a>
    <a href="#galerie" class="product-card" onclick="setFilter('douche')">
      <img src="https://images.unsplash.com/photo-1584622650111-993a426fbf0a?auto=format&fit=crop&w=800&q=80" alt="Parois et portes de douche" loading="lazy">
      <div class="product-info">
        <span class="product-number">04</span>
        <h3 data-i18n="product_shower">Parois & portes de douche</h3>
      </div>
    </a>
  </div>
</section>

<!-- GALLERY -->
<section class="gallery" id="galerie">
  <div class="container">
    <div class="section-head reveal">
      <h2 data-i18n="gallery_title">Réalisations</h2>
      <p data-i18n="gallery_subtitle">Un aperçu de nos fabrications et installations récentes.</p>
    </div>
    <div class="filters reveal">
      <button type="button" class="filter-button active" data-filter="all" onclick="setFilter('all')" data-i18n="filter_all">Tout</button>
      <button type="button" class="filter-button" data-filter="aluminium" onclick="setFilter('aluminium')" data-i18n="filter_aluminium">Aluminium</button>
      <button type="button" class="filter-button" data-filter="pvc" onclick="setFilter('pvc')" data-i18n="filter_pvc">PVC</button>
      <button type="button" class="filter-button" data-filter="cuisines" onclick="setFilter('cuisines')" data-i18n="filter_kitchens">Cuisines</button>
      <button type="button" class="filter-button" data-filter="douche" onclick="setFilter('douche')" data-i18n="filter_shower">Douche</button>
    </div>
    <div class="gallery-grid reveal" id="galleryGrid"></div>
  </div>
</section>

<!-- SERVICES -->
<section class="services" id="services">
  <div class="container">
    <div class="section-head reveal">
      <h2 data-i18n="services_title">Services</h2>
      <p data-i18n="services_subtitle">De la fabrication à la pose, un accompagnement complet.</p>
    </div>
    <div class="reveal">
      <div class="service-row">
        <span class="service-number">01</span>
        <h3 data-i18n="service1_title">Fabrication</h3>
        <p data-i18n="service1_text">Fabrication d'éléments en aluminium et PVC adaptés à vos dimensions.</p>
      </div>
      <div class="service-row">
        <span class="service-number">02</span>
        <h3 data-i18n="service2_title">Solutions Aluminium</h3>
        <p data-i18n="service2_text">Fenêtres, portes et parois en aluminium, sur mesure.</p>
      </div>
      <div class="service-row">
        <span class="service-number">03</span>
        <h3 data-i18n="service3_title">Solutions PVC</h3>
        <p data-i18n="service3_text">Fenêtres et portes PVC, isolantes et durables.</p>
      </div>
      <div class="service-row">
        <span class="service-number">04</span>
        <h3 data-i18n="service4_title">Installation</h3>
        <p data-i18n="service4_text">Pose soignée directement sur site par l'atelier.</p>
      </div>
      <div class="service-row">
        <span class="service-number">05</span>
        <h3 data-i18n="service5_title">Aménagement intérieur</h3>
        <p data-i18n="service5_text">Cuisines, rangements et parois de douche sur mesure.</p>
      </div>
    </div>
  </div>
</section>

<!-- ABOUT -->
<section class="about" id="apropos">
  <div class="container about-inner reveal">
    <h2 data-i18n="about_title">Un atelier local. Des réalisations sur mesure.</h2>
    <p data-i18n="about_text">Spécialisé dans la fabrication et l'installation de solutions en aluminium et PVC, nous adaptons chaque réalisation aux besoins et aux dimensions de votre espace.</p>
  </div>
</section>

<!-- CONTACT -->
<section class="contact" id="contact">
  <div class="container reveal">
    <h2 data-i18n="contact_title">Votre projet commence ici.</h2>
    <p class="contact-intro" data-i18n="contact_text">Parlez-nous de votre besoin directement sur WhatsApp.</p>
    <div class="contact-buttons">
      <a class="whatsapp-button" href="https://wa.me/213792106924" target="_blank" rel="noopener noreferrer">
        <svg width="22" height="22" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M12.04 2C6.58 2 2.13 6.45 2.13 11.91c0 1.75.46 3.45 1.32 4.95L2 22l5.25-1.38c1.44.79 3.06 1.2 4.79 1.2 5.46 0 9.91-4.45 9.91-9.91C21.95 6.45 17.5 2 12.04 2zm5.8 14.02c-.24.68-1.4 1.32-1.93 1.4-.5.08-1.13.11-1.82-.11-.42-.14-.96-.32-1.65-.62-2.9-1.25-4.79-4.16-4.94-4.35-.14-.19-1.18-1.57-1.18-3 0-1.42.75-2.12 1.01-2.41.27-.29.58-.36.78-.36.19 0 .39 0 .55.01.18.01.42-.07.65.5.24.58.82 2 .89 2.15.07.14.12.31.02.5-.09.19-.14.31-.28.48-.14.17-.29.37-.42.5-.14.14-.28.29-.12.57.16.28.72 1.19 1.55 1.93 1.07.95 1.96 1.25 2.24 1.39.28.14.44.12.6-.07.16-.19.68-.79.87-1.06.18-.28.36-.23.6-.14.24.09 1.55.73 1.82.87.27.14.44.21.51.32.07.11.07.65-.17 1.33z"/></svg>
        <span data-i18n="contact_button">Contacter sur WhatsApp</span>
      </a>
    </div>
    <div class="contact-meta">
      <div class="contact-meta-item">
        <span data-i18n="phone_label">Téléphone</span>
        <a href="tel:+213792106924">+213 792 10 69 24</a>
      </div>
      <div class="contact-meta-item">
        <span>Facebook</span>
        <a href="https://www.facebook.com/profile.php?id=61575091777923" target="_blank" rel="noopener noreferrer" data-i18n="facebook_link">Voir la page</a>
      </div>
    </div>
  </div>
</section>

<!-- FOOTER -->
<footer class="footer">
  <div class="container footer-inner">
    <div>
      <span data-i18n="footer_name">Menuiserie Aluminium & PVC</span>
      <span> — </span>
      <span data-i18n="footer_rights">Tous droits réservés</span>
    </div>
    <div class="footer-links">
      <a href="https://wa.me/213792106924" target="_blank" rel="noopener noreferrer">WhatsApp</a>
      <a href="https://www.facebook.com/profile.php?id=61575091777923" target="_blank" rel="noopener noreferrer">Facebook</a>
      <a href="#top" data-i18n="nav_home">Accueil</a>
      <a href="#contact" data-i18n="nav_contact">Contact</a>
    </div>
  </div>
</footer>

<!-- FLOATING WHATSAPP -->
<a class="whatsapp-float" href="https://wa.me/213792106924" target="_blank" rel="noopener noreferrer" aria-label="WhatsApp">
  <svg width="26" height="26" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M12.04 2C6.58 2 2.13 6.45 2.13 11.91c0 1.75.46 3.45 1.32 4.95L2 22l5.25-1.38c1.44.79 3.06 1.2 4.79 1.2 5.46 0 9.91-4.45 9.91-9.91C21.95 6.45 17.5 2 12.04 2zm5.8 14.02c-.24.68-1.4 1.32-1.93 1.4-.5.08-1.13.11-1.82-.11-.42-.14-.96-.32-1.65-.62-2.9-1.25-4.79-4.16-4.94-4.35-.14-.19-1.18-1.57-1.18-3 0-1.42.75-2.12 1.01-2.41.27-.29.58-.36.78-.36.19 0 .39 0 .55.01.18.01.42-.07.65.5.24.58.82 2 .89 2.15.07.14.12.31.02.5-.09.19-.14.31-.28.48-.14.17-.29.37-.42.5-.14.14-.28.29-.12.57.16.28.72 1.19 1.55 1.93 1.07.95 1.96 1.25 2.24 1.39.28.14.44.12.6-.07.16-.19.68-.79.87-1.06.18-.28.36-.23.6-.14.24.09 1.55.73 1.82.87.27.14.44.21.51.32.07.11.07.65-.17 1.33z"/></svg>
</a>

<!-- LIGHTBOX -->
<div class="lightbox" id="lightbox" role="dialog" aria-modal="true" aria-label="Image preview">
  <button class="lightbox-close" type="button" onclick="closeLightbox()" aria-label="Close">&times;</button>
  <button class="lightbox-prev" type="button" onclick="changeLightbox(-1)" aria-label="Previous image">&#8249;</button>
  <img class="lightbox-image" id="lightboxImage" src="" alt="">
  <button class="lightbox-next" type="button" onclick="changeLightbox(1)" aria-label="Next image">&#8250;</button>
</div>

<script>
"use strict";

/* =========================================================
   IMAGE DATA WITH HIGH-QUALITY DIRECT URLS & DETAILED DESCRIPTIONS
========================================================= */

const GALLERY = [
  {
    src: "https://images.unsplash.com/photo-1541888946425-d0fbb186a5b3?auto=format&fit=crop&w=1200&q=80",
    category: "aluminium",
    label: {
      fr: "Fenêtre double en aluminium blanc avec volet roulant intégré - Vue intérieure 120x100cm",
      ar: "نافذة ألومنيوم بيضاء مزدوجة مع حماية أبجور أبيض مدمج (Volet Roulant) - رؤية من الداخل 120×100 سم",
      en: "Double white aluminium window with integrated roller shutter - Interior view 120x100cm"
    }
  },
  {
    src: "https://images.unsplash.com/photo-1600566753376-12c8ab7fb75b?auto=format&fit=crop&w=1200&q=80",
    category: "aluminium",
    label: {
      fr: "Baie vitrée coulissante en aluminium gris anthracite - Largeur 300cm, verre teinté داكن",
      ar: "باب واجهة سحاب ألمنيوم رمادي داكن (Anthracite Grey) بفتحات واسعة وزجاج داكن - عرض 300 سم",
      en: "Sliding patio door in anthracite grey aluminium - 300cm wide, tinted glass"
    }
  },
  {
    src: "https://images.unsplash.com/photo-1586023492125-27b2c045efd7?auto=format&fit=crop&w=1200&q=80",
    category: "pvc",
    label: {
      fr: "Porte de salle de bain en PVC blanc avec vitrage sablé opale - Isolation thermique 210x80cm",
      ar: "باب حمام PVC أبيض مع زجاج معتم معالج بالرمل للخصوصية - عزل حراري 210×80 سم",
      en: "White PVC bathroom door with frosted glass - Thermal insulation 210x80cm"
    }
  },
  {
    src: "https://images.unsplash.com/photo-1584622650111-993a426fbf0a?auto=format&fit=crop&w=1200&q=80",
    category: "douche",
    label: {
      fr: "Cabine de douche en verre trempé avec profilés aluminium noir - Système coulissant 200x90cm",
      ar: "كابينة دش زجاجية (Shower Box) سحاب ببروفيل ألمنيوم أسود وزجاج مثلج متدرج - 200×90 سم",
      en: "Glass shower enclosure with black aluminium frame - Sliding door 200x90cm"
    }
  },
  {
    src: "https://images.unsplash.com/photo-1584622650111-993a426fbf0a?auto=format&fit=crop&w=1200&q=80",
    category: "douche",
    label: {
      fr: "Paroi de douche coulissante en aluminium chromé et verre sécurit - Étanchéité renforcée",
      ar: "كابينة دش زجاجية سحاب بإطار ألمنيوم كروم لمعان مانع لتسرب المياه",
      en: "Sliding shower door with chrome aluminium frame and safety glass"
    }
  },
  {
    src: "https://images.unsplash.com/photo-1512917774080-9991f1c4c750?auto=format&fit=crop&w=1200&q=80",
    category: "pvc",
    label: {
      fr: "Fenêtre de salle de bain en PVC blanc avec vitre dépolie - Protection contre l'humidité",
      ar: "نافذة حمام صغيرة PVC أبيض مع زجاج معتم يسمح بمرور الضوء الطبيعي",
      en: "White PVC bathroom window with frosted privacy glass - Moisture resistant"
    }
  },
  {
    src: "https://images.unsplash.com/photo-1507089947368-19c1da9775ae?auto=format&fit=crop&w=1200&q=80",
    category: "cuisines",
    label: {
      fr: "Cuisine moderne en aluminium gris mat - Structure noire fine et éclairage LED intégré",
      ar: "مطبخ ألمنيوم رمادي مات (Matte Grey) بأسطح حديثة وهيكل أسود رفيع مع إضاءة LED مخفية",
      en: "Modern matte grey aluminium kitchen - Fine black framework with concealed LED strips"
    }
  },
  {
    src: "https://images.unsplash.com/photo-1556911220-e15b29be8c8f?auto=format&fit=crop&w=1200&q=80",
    category: "cuisines",
    label: {
      fr: "Cuisine classique en aluminium blanc - Poignées dorées élégantes pour petits espaces",
      ar: "مطبخ ألمنيوم أبيض كلاسيكي بمقابض ذهبية أنيقة يمنح اتساعاً وإضاءة للمكان",
      en: "Classic white aluminium kitchen - Elegant gold handles optimized for compact spaces"
    }
  },
  {
    src: "https://images.unsplash.com/photo-1507089947368-19c1da9775ae?auto=format&fit=crop&w=1200&q=80",
    category: "cuisines",
    label: {
      fr: "Cuisine haut de gamme en aluminium noir brillant - Plan de travail en marbre noir",
      ar: "مطبخ ألمنيوم أسود لامع (Glossy Black) تصميم فخم بأسطح رخامية وإضاءة داخلية رفيعة",
      en: "Luxury glossy black aluminium kitchen - Black marble countertops and accent lighting"
    }
  },
  {
    src: "https://images.unsplash.com/photo-1512917774080-9991f1c4c750?auto=format&fit=crop&w=1200&q=80",
    category: "cuisines",
    label: {
      fr: "Cuisine d'angle (L-Shape) en aluminium gris foncé - Éclairage plafond chaleureux",
      ar: "مطبخ ألمنيوم زاوي (L-Shape) رمادي غامق باستغلال مثالي للمساحات وإضاءة سقفية دافئة",
      en: "Dark grey L-shape aluminium kitchen - Space-maximizing design with ambient warm ceiling lights"
    }
  },
  {
    src: "https://images.unsplash.com/photo-1503387762-592deb58ef4e?auto=format&fit=crop&w=1200&q=80",
    category: "aluminium",
    label: {
      fr: "Porte en aluminium noir mat à grande baie vitrée - Vue frontale, cadre fin 210x90cm",
      ar: "باب ألمنيوم أسود مطفي بصفائح زجاجية واسعة - زاوية أماماية بفتحة 210×90 سم",
      en: "Matte black aluminium door with large glass pane - Frontal view, slim 210x90cm frame"
    }
  },
  {
    src: "https://images.unsplash.com/photo-1513694203232-719a280e022f?auto=format&fit=crop&w=1200&q=80",
    category: "aluminium",
    label: {
      fr: "Ensemble porte et fenêtre en aluminium anthracite - Angle latéral 45°, profilé renforcé",
      ar: "طقم باب ونافذة ألمنيوم رمادي داكن (رمادي أنثراسيت) - زاوية جانبية 45 درجة بمقاطع معززة",
      en: "Anthracite aluminium door and window set - 45-degree side angle, reinforced profile"
    }
  },
  {
    src: "https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=1200&q=80",
    category: "aluminium",
    label: {
      fr: "Porte vitrée en aluminium anodisé argent - Vue en contre-plongée, verre trempé transparent",
      ar: "باب ألمنيوم زجاجي فضي مؤكسد - زاوية مائلة من الأسفل، زجاج مقسى شفاف",
      en: "Glazed silver anodized aluminium door - Low angle shot, tempered transparent glass"
    }
  },
  {
    src: "https://images.unsplash.com/photo-1600607687939-ce8a6c25118c?auto=format&fit=crop&w=1200&q=80",
    category: "aluminium",
    label: {
      fr: "Porte d'entrée en aluminium bronze - Vue rapprochée du panneau isolant et de la poignée",
      ar: "باب دخول ألمنيوم باللون البرونزي - لقطة مقربة للوح العازل والمقبض المعدني",
      en: "Bronze entrance aluminium door - Close-up view of insulating panel and metal handle"
    }
  },
  {
    src: "https://images.unsplash.com/photo-1600585154526-990dced4db0d?auto=format&fit=crop&w=1200&q=80",
    category: "pvc",
    label: {
      fr: "Porte PVC blanche décorative avec moulures - Vue extérieure, isolation thermique renforcée",
      ar: "باب PVC أبيض مزخرف بنقوش حديثة - رؤية خارجية بعزل حراري عالي الجودة",
      en: "Decorative white PVC door with molded panels - Exterior view, enhanced thermal insulation"
    }
  },
  {
    src: "https://images.unsplash.com/photo-1513694203232-719a280e022f?auto=format&fit=crop&w=1200&q=80",
    category: "pvc",
    label: {
      fr: "Installation de fenêtres PVC sur chantier réhabilitation - Perspective latérale du cadre",
      ar: "تركيب نوافذ PVC في ورشة بناء حية - لقطة جانبية توضح تثبيت الإطار بدقة",
      en: "PVC window installation on renovation site - Side perspective showing frame fitting"
    }
  },
  {
    src: "https://images.unsplash.com/photo-1503387762-592deb58ef4e?auto=format&fit=crop&w=1200&q=80",
    category: "pvc",
    label: {
      fr: "Fenêtre PVC installée en façade moderne - Gris anthracite, double joint d'étanchéité",
      ar: "نافذة PVC حديثة مركبة في واجهة منزل - رمادي غامق مع حواف إحكام مزدوجة",
      en: "Installed PVC window on modern facade - Anthracite grey, double weather-stripping"
    }
  }
];

/* =========================================================
   STATE & TRANSLATIONS
========================================================= */

let currentLanguage = "fr";
let currentFilter = "all";
let currentLightboxIndex = 0;

const TRANSLATIONS = {
  fr: {
    logo_main: "نجارة الألمنيوم و PVC",
    logo_sub: "Aluminium & PVC",
    nav_home: "Accueil",
    nav_products: "Produits",
    nav_gallery: "Réalisations",
    nav_services: "Services",
    nav_about: "À propos",
    nav_contact: "Contact",
    whatsapp: "WhatsApp",
    hero_title: "Aluminium &amp; PVC,<br>pensés pour votre espace.",
    hero_sub: "Fabrication et installation sur mesure.",
    hero_cta: "Parler sur WhatsApp",
    hero_gallery: "Voir nos réalisations",
    scroll: "Défiler",
    intro_eyebrow: "Savoir-faire",
    intro_title: "Le savoir-faire au service de vos espaces.",
    intro_text: "Nous réalisons et installons des solutions en aluminium et PVC adaptées à chaque espace, du résidentiel aux projets sur mesure.",
    featured_title: "Créations sur mesure",
    featured_text: "Chaque réalisation est pensée selon les dimensions et les besoins réels de l'espace, du choix des matériaux à la pose finale.",
    featured_button: "Découvrir nos réalisations",
    products_title: "Produits",
    products_subtitle: "Une gamme complète en aluminium et PVC, fabriquée et installée sur mesure.",
    product_aluminium: "Fenêtres & portes Aluminium",
    product_pvc: "Fenêtres & portes PVC",
    product_kitchens: "Cuisines & rangements",
    product_shower: "Parois & portes de douche",
    gallery_title: "Réalisations",
    gallery_subtitle: "Un aperçu de nos fabrications et installations récentes.",
    filter_all: "Tout",
    filter_aluminium: "Aluminium",
    filter_pvc: "PVC",
    filter_kitchens: "Cuisines",
    filter_shower: "Douche",
    services_title: "Services",
    services_subtitle: "De la fabrication à la pose, un accompagnement complet.",
    service1_title: "Fabrication",
    service1_text: "Fabrication d'éléments en aluminium et PVC adaptés à vos dimensions.",
    service2_title: "Solutions Aluminium",
    service2_text: "Fenêtres, portes et parois en aluminium, sur mesure.",
    service3_title: "Solutions PVC",
    service3_text: "Fenêtres et portes PVC, isolantes et durables.",
    service4_title: "Installation",
    service4_text: "Pose soignée directement sur site par l'atelier.",
    service5_title: "Aménagement intérieur",
    service5_text: "Cuisines, rangements et parois de douche sur mesure.",
    about_title: "Un atelier local. Des réalisations sur mesure.",
    about_text: "Spécialisé dans la fabrication et l'installation de solutions en aluminium et PVC, nous adaptons chaque réalisation aux besoins et aux dimensions de votre espace.",
    contact_title: "Votre projet commence ici.",
    contact_text: "Parlez-nous de votre besoin directement sur WhatsApp.",
    contact_button: "Contacter sur WhatsApp",
    phone_label: "Téléphone",
    facebook_link: "Voir la page",
    footer_name: "Menuiserie Aluminium & PVC",
    footer_rights: "Tous droits réservés"
  },
  ar: {
    logo_main: "نجارة الألمنيوم و PVC",
    logo_sub: "ألمنيوم و PVC",
    nav_home: "الرئيسية",
    nav_products: "المنتجات",
    nav_gallery: "الإنجازات",
    nav_services: "الخدمات",
    nav_about: "من نحن",
    nav_contact: "اتصل بنا",
    whatsapp: "واتساب",
    hero_title: "ألمنيوم و PVC،<br>مصمّمان لمساحتك.",
    hero_sub: "تصنيع وتركيب حسب الطلب.",
    hero_cta: "تواصل عبر واتساب",
    hero_gallery: "شاهد إنجازاتنا",
    scroll: "مرّر للأسفل",
    intro_eyebrow: "خبرتنا",
    intro_title: "الخبرة في خدمة مساحتك.",
    intro_text: "نقوم بتصنيع وتركيب حلول الألمنيوم و PVC المناسبة لكل مساحة، من المنازل إلى المشاريع الخاصة.",
    featured_title: "إبداعات حسب الطلب",
    featured_text: "كل إنجاز يُصمم وفق أبعاد واحتياجات المساحة الفعلية، من اختيار المواد إلى التركيب النهائي.",
    featured_button: "اكتشف إنجازاتنا",
    products_title: "المنتجات",
    products_subtitle: "تشكيلة كاملة من الألمنيوم و PVC، مصنوعة ومركبة حسب الطلب.",
    product_aluminium: "نوافذ وأبواب ألمنيوم",
    product_pvc: "نوافذ وأبواب PVC",
    product_kitchens: "مطابخ وخزائن",
    product_shower: "حواجز وأبواب دش",
    gallery_title: "الإنجازات",
    gallery_subtitle: "نظرة على أحدث تصنيعاتنا وتركيباتنا.",
    filter_all: "الكل",
    filter_aluminium: "ألمنيوم",
    filter_pvc: "PVC",
    filter_kitchens: "مطابخ",
    filter_shower: "دش",
    services_title: "الخدمات",
    services_subtitle: "من التصنيع إلى التركيب، مرافقة كاملة.",
    service1_title: "التصنيع",
    service1_text: "تصنيع عناصر الألمنيوم و PVC حسب أبعادكم.",
    service2_title: "حلول الألمنيوم",
    service2_text: "نوافذ وأبواب وحواجز ألمنيوم حسب الطلب.",
    service3_title: "حلول PVC",
    service3_text: "نوافذ وأبواب PVC عازلة ومتينة.",
    service4_title: "التركيب",
    service4_text: "تركيب دقيق مباشرة في الموقع من طرف الورشة.",
    service5_title: "التهيئة الداخلية",
    service5_text: "مطابخ وخزائن وحواجز دش حسب الطلب.",
    about_title: "ورشة محلية. إنجازات حسب الطلب.",
    about_text: "متخصصون في تصنيع وتركيب حلول الألمنيوم و PVC، نكيّف كل إنجاز حسب احتياجات وأبعاد مساحتكم.",
    contact_title: "مشروعك يبدأ من هنا.",
    contact_text: "حدثونا عن احتياجكم مباشرة عبر واتساب.",
    contact_button: "تواصل عبر واتساب",
    phone_label: "الهاتف",
    facebook_link: "زيارة الصفحة",
    footer_name: "نجارة الألمنيوم و PVC",
    footer_rights: "جميع الحقوق محفوظة"
  },
  en: {
    logo_main: "نجارة الألمنيوم و PVC",
    logo_sub: "Aluminium & PVC",
    nav_home: "Home",
    nav_products: "Products",
    nav_gallery: "Projects",
    nav_services: "Services",
    nav_about: "About",
    nav_contact: "Contact",
    whatsapp: "WhatsApp",
    hero_title: "Aluminium &amp; PVC,<br>designed for your space.",
    hero_sub: "Custom fabrication and installation.",
    hero_cta: "Talk on WhatsApp",
    hero_gallery: "See our projects",
    scroll: "Scroll",
    intro_eyebrow: "Craftsmanship",
    intro_title: "Craftsmanship for every space.",
    intro_text: "We fabricate and install aluminium and PVC solutions tailored to every space, from homes to custom projects.",
    featured_title: "Custom creations",
    featured_text: "Every project is designed around the real dimensions and needs of the space, from material choice to final installation.",
    featured_button: "Discover our projects",
    products_title: "Products",
    products_subtitle: "A complete range of aluminium and PVC, made and installed to measure.",
    product_aluminium: "Aluminium windows & doors",
    product_pvc: "PVC windows & doors",
    product_kitchens: "Kitchens & storage",
    product_shower: "Shower doors & enclosures",
    gallery_title: "Projects",
    gallery_subtitle: "A look at our recent fabrication and installation work.",
    filter_all: "All",
    filter_aluminium: "Aluminium",
    filter_pvc: "PVC",
    filter_kitchens: "Kitchens",
    filter_shower: "Shower",
    services_title: "Services",
    services_subtitle: "From fabrication to installation, full support.",
    service1_title: "Fabrication",
    service1_text: "Aluminium and PVC elements made to your exact dimensions.",
    service2_title: "Aluminium solutions",
    service2_text: "Custom aluminium windows, doors and partitions.",
    service3_title: "PVC solutions",
    service3_text: "Insulating, durable PVC windows and doors.",
    service4_title: "Installation",
    service4_text: "Careful on-site installation by the workshop.",
    service5_title: "Interior fit-out",
    service5_text: "Custom kitchens, storage and shower enclosures.",
    about_title: "A local workshop. Work made to measure.",
    about_text: "Specialised in fabricating and installing aluminium and PVC solutions, we tailor every project to the needs and dimensions of your space.",
    contact_title: "Your project starts here.",
    contact_text: "Tell us about your needs directly on WhatsApp.",
    contact_button: "Contact on WhatsApp",
    phone_label: "Phone",
    facebook_link: "Visit the page",
    footer_name: "Aluminium & PVC Workshop",
    footer_rights: "All rights reserved"
  }
};

/* =========================================================
   FUNCTIONS
========================================================= */

function renderGallery() {
  const galleryGrid = document.getElementById("galleryGrid");
  if (!galleryGrid) return;

  galleryGrid.innerHTML = "";

  GALLERY.forEach((item, index) => {
    const galleryItem = document.createElement("article");
    galleryItem.className = "gallery-item";

    if (currentFilter !== "all" && item.category !== currentFilter) {
      galleryItem.classList.add("hidden");
    }

    const image = document.createElement("img");
    image.src = item.src;
    image.alt = item.label[currentLanguage];
    image.loading = "lazy";

    const overlay = document.createElement("div");
    overlay.className = "gallery-overlay";

    const label = document.createElement("span");
    label.className = "gallery-label";
    label.textContent = item.label[currentLanguage];

    overlay.appendChild(label);
    galleryItem.appendChild(image);
    galleryItem.appendChild(overlay);

    galleryItem.addEventListener("click", () => openLightbox(index));
    galleryGrid.appendChild(galleryItem);
  });
}

function setFilter(category) {
  currentFilter = category;
  document.querySelectorAll(".filter-button").forEach(button => {
    button.classList.toggle("active", button.dataset.filter === category);
  });
  renderGallery();

  const gallery = document.getElementById("galerie");
  if (gallery) {
    setTimeout(() => {
      gallery.scrollIntoView({ behavior: "smooth", block: "start" });
    }, 50);
  }
}

function openLightbox(index) {
  currentLightboxIndex = index;
  const lightbox = document.getElementById("lightbox");
  const image = document.getElementById("lightboxImage");
  if (!lightbox || !image) return;

  const item = GALLERY[currentLightboxIndex];
  image.src = item.src;
  image.alt = item.label[currentLanguage];

  lightbox.classList.add("open");
  document.body.classList.add("no-scroll");
}

function closeLightbox() {
  const lightbox = document.getElementById("lightbox");
  if (!lightbox) return;
  lightbox.classList.remove("open");
  document.body.classList.remove("no-scroll");
}

function changeLightbox(direction) {
  currentLightboxIndex += direction;
  if (currentLightboxIndex < 0) currentLightboxIndex = GALLERY.length - 1;
  if (currentLightboxIndex >= GALLERY.length) currentLightboxIndex = 0;

  const item = GALLERY[currentLightboxIndex];
  const image = document.getElementById("lightboxImage");
  if (!image) return;

  image.src = item.src;
  image.alt = item.label[currentLanguage];
}

document.addEventListener("keydown", function (event) {
  const lightbox = document.getElementById("lightbox");
  if (!lightbox || !lightbox.classList.contains("open")) return;
  if (event.key === "Escape") closeLightbox();
  if (event.key === "ArrowRight") changeLightbox(1);
  if (event.key === "ArrowLeft") changeLightbox(-1);
});

document.getElementById("lightbox").addEventListener("click", function (event) {
  if (event.target === this) closeLightbox();
});

function toggleMobileMenu() {
  const menu = document.getElementById("mobileMenu");
  const burger = document.querySelector(".burger");
  if (!menu) return;
  const isOpen = menu.classList.toggle("open");
  if (burger) burger.setAttribute("aria-expanded", String(isOpen));
  document.body.classList.toggle("no-scroll", isOpen);
}

function closeMobileMenu() {
  const menu = document.getElementById("mobileMenu");
  const burger = document.querySelector(".burger");
  if (menu) menu.classList.remove("open");
  if (burger) burger.setAttribute("aria-expanded", "false");
  document.body.classList.remove("no-scroll");
}

window.addEventListener("scroll", function () {
  const nav = document.getElementById("nav");
  if (nav) nav.classList.toggle("scrolled", window.scrollY > 40);
}, { passive: true });

const revealObserver = new IntersectionObserver(function (entries, observer) {
  entries.forEach(entry => {
    if (entry.isIntersecting) {
      entry.target.classList.add("visible");
      observer.unobserve(entry.target);
    }
  });
}, { threshold: 0.1 });

document.querySelectorAll(".reveal").forEach(element => {
  revealObserver.observe(element);
});

function setLanguage(language) {
  if (!TRANSLATIONS[language]) return;
  currentLanguage = language;
  const dictionary = TRANSLATIONS[language];

  document.documentElement.lang = language;
  document.documentElement.dir = language === "ar" ? "rtl" : "ltr";

  document.querySelectorAll("[data-i18n]").forEach(element => {
    const key = element.getAttribute("data-i18n");
    if (Object.prototype.hasOwnProperty.call(dictionary, key)) {
      element.textContent = dictionary[key];
    }
  });

  document.querySelectorAll("[data-i18n-html]").forEach(element => {
    const key = element.getAttribute("data-i18n-html");
    if (Object.prototype.hasOwnProperty.call(dictionary, key)) {
      element.innerHTML = dictionary[key];
    }
  });

  document.querySelectorAll("[data-lang-btn]").forEach(button => {
    button.classList.toggle("active", button.dataset.langBtn === language);
  });

  if (language === "ar") {
    document.title = "نجارة الألمنيوم و PVC | تصنيع وتركيب";
  } else if (language === "en") {
    document.title = "Aluminium & PVC Workshop | Fabrication & Installation";
  } else {
    document.title = "Menuiserie Aluminium & PVC | Fabrication & Installation";
  }

  renderGallery();
}

document.addEventListener("DOMContentLoaded", function () {
  renderGallery();
  setLanguage("fr");
});
</script>

</body>
</html>
