<template>
    <footer class="footer">
      <hr class="footer-separator" />
      <div class="footer-content">
        <nav class="bottom-nav">
          <a href="#">Home</a>
          <span class="divider">|</span>
          <a href="#">Usługi</a>
          <span class="divider">|</span>
          <a href="#">Technologie</a>
          <span class="divider">|</span>
          <a href="#">Cennik</a>
          <span class="divider">|</span>
          <a href="#">Kontakt</a>
        </nav>
        <p class="footer-info">
          Pietruszczak Stomatologia | Copyright 2024 | Polityka prywatności
        </p>
      </div>
    </footer>
  </template>
  
  <style scoped>
  .footer {
    background-color: #fff;
    padding: 1.5rem 2rem;
    box-sizing: border-box;
  }
  .footer-separator {
    margin: 0;
    padding: 0;
    border: none;
    border-top: 2px solid #0e1f35;
  }
  .footer-content {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-top: 1rem;
  }
  .bottom-nav {
    width: min-content;
    display: flex;
    align-items: center;
  }
  .bottom-nav a {
    font-family: 'Figtree', cursive;
    text-decoration: underline;
    color: #0e1f35;
    font-size: 16px;
    line-height: 22px;
  }

  .divider {
    color: #0e1f35;
    margin-left: 4px;
    margin-right: 4px;
  }

  .footer-info {
    font-size: 0.9rem;
    color: #0e1f35;
    margin: 0;
    font-family: 'Figtree', cursive;
  }
  .footer-info a {
    color: #0e1f35;
    text-decoration: none;
    font-weight: 500;
    margin-left: 0.3rem;
  }
  .footer-info a:hover {
    text-decoration: underline;
  }
  </style>
  