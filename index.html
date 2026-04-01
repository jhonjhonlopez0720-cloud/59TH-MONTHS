<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title> Our 59th Monthsary!! </title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <style>
    /* ===== RESET + BASE ===== */
    *,
    *::before,
    *::after {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body,
    html {
      width: 100%;
      height: 100%;
      overflow: hidden;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
      font-size: 16px;
      line-height: 1.5;
      background: linear-gradient(135deg, #0b1a30, #020408);
      color: #f5f5f5;
      position: relative;
      display: flex;
      align-items: center;
      justify-content: center;
    }

    /* Soft glow / particle background */
    body::before {
      content: "";
      position: absolute;
      top: 0;
      left: 0;
      right: 0;
      bottom: 0;
      background: radial-gradient(circle at 20% 20%, rgba(255, 77, 109, 0.1) 0%, transparent 40%),
                  radial-gradient(circle at 80% 60%, rgba(70, 190, 140, 0.1) 0%, transparent 50%);
      pointer-events: none;
      z-index: 0;
      opacity: 0.8;
      transition: opacity 1.5s ease-in-out;
    }

    body.bloomed::before {
      opacity: 1;
    }

    /* Container */
    .container {
      position: relative;
      max-width: 100vw;
      max-height: 100vh;
      padding: 2rem;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      gap: 2rem;
      z-index: 1;
    }

    /* Title */
    .title {
      font-size: 1.8rem;
      font-weight: 500;
      text-align: center;
      letter-spacing: 0.5px;
      opacity: 0;
      transform: translateY(20px);
      transition: opacity 1.2s ease-in-out, transform 1.2s ease-in-out;
    }

    .title.show {
      opacity: 1;
      transform: translateY(0);
    }

    /* Tulip bouquet group */
    .tulips-container {
      position: relative;
      display: flex;
      justify-content: center;
      align-items: flex-end;
      gap: 40px;
      overflow: visible;
      margin-top: 2rem;
      min-height: 280px;
      width: 100%;
    }

    .tulip {
      position: relative;
      display: flex;
      flex-direction: column;
      align-items: center;
      --petal-color: #ff4d6d;
      --stem-color: #4ca56c;
      --leaf-color: #3a8c5c;
      opacity: 1;
      transform: translateY(0);
      transition: all 0.8s cubic-bezier(0.4, 0.0, 0.2, 1);
    }

    .tulip.closed {
      opacity: 0.8;
      transform: translateY(20px);
    }

    .tulip.bloomed {
      opacity: 1;
      transform: translateY(0);
    }

    .stem {
      position: absolute;
      bottom: 0;
      height: 200px;
      width: 8px;
      background: var(--stem-color);
      border-radius: 4px;
      box-shadow: 0 0 20px rgba(76, 165, 108, 0.6);
      z-index: 2;
      transform-origin: bottom;
      transform: rotate(0deg);
      transition: transform 0.8s ease-in-out;
    }

    .tulip.bloomed .stem {
      transform: rotate(1deg);
    }

    .leaf {
      position: absolute;
      width: 30px;
      height: 12px;
      background: var(--leaf-color);
      border-radius: 50% 50% 50% 50% / 60% 60% 40% 40%;
      transform-origin: bottom center;
      box-shadow: 0 0 10px rgba(58, 140, 92, 0.5);
      z-index: 1;
      opacity: 0.8;
    }

    .tulip.bloomed .leaf {
      opacity: 1;
    }

    .leaf-1 {
      top: 60px;
      left: 10px;
      transform: rotate(-30deg);
    }

    .tulip.bloomed .leaf-1 {
      transform: rotate(-20deg);
    }

    .leaf-2 {
      top: 90px;
      right: 12px;
      transform: rotate(25deg);
    }

    .tulip.bloomed .leaf-2 {
      transform: rotate(15deg);
    }

    .buds {
      position: absolute;
      top: 40px;
      left: 50%;
      transform: translateX(-50%) scale(1);
      width: 22px;
      height: 32px;
      border-radius: 50% 50% 0 0;
      background: #ff4d6d;
      box-shadow: 0 0 25px rgba(255, 77, 109, 0.8);
      transition: all 0.8s ease, transform 0.8s cubic-bezier(0.4, 0.0, 0.2, 1);
      z-index: 3;
    }

    .tulip.closed .buds {
      transform: translateX(-50%) scale(0.8);
      box-shadow: 0 0 15px rgba(255, 77, 109, 0.6);
    }

    .petals {
      position: absolute;
      top: 0;
      left: 50%;
      transform: translateX(-50%);
      opacity: 1;
      width: 100%;
      height: 100%;
      z-index: 4;
    }

    .petal {
      position: absolute;
      width: 16px;
      height: 28px;
      background: var(--petal-color);
      border-radius: 50% 50% 0 0;
      transform-origin: bottom center;
      box-shadow: 0 0 15px rgba(255, 77, 109, 0.8);
      opacity: 0;
      transform: rotate(0deg) translateY(-100px);
      transition: opacity 0.8s ease, transform 0.8s cubic-bezier(0.4, 0.0, 0.2, 1);
    }

    .petal-1 {
      left: 50%;
      transform-origin: bottom left;
      transform: rotate(-40deg) translateY(-100px);
    }

    .petal-2 {
      left: 50%;
      transform: rotate(-10deg) translateY(-100px);
    }

    .petal-3 {
      left: 50%;
      transform-origin: bottom right;
      transform: rotate(20deg) translateY(-100px);
    }

    .tulip.bloomed .petal {
      opacity: 1;
      transform: rotate(0deg) translateY(0);
    }

    .tulip.bloomed .petal-1 {
      transform: rotate(-10deg) translateY(0);
    }

    .tulip.bloomed .petal-2 {
      transform: rotate(0deg) translateY(0);
    }

    .tulip.bloomed .petal-3 {
      transform: rotate(10deg) translateY(0);
    }

    /* Hearts container */
    .hearts {
      position: absolute;
      top: 0;
      left: 0;
      right: 0;
      bottom: 0;
      pointer-events: none;
      overflow: hidden;
      z-index: 2;
    }

    .heart {
      position: absolute;
      width: 16px;
      height: 14px;
      opacity: 0;
      animation: float-heart 8s ease-in-out infinite;
      transform: translateX(0);
    }

    .heart::before,
    .heart::after {
      content: "";
      position: absolute;
      width: 10px;
      height: 16px;
      background: #ff4d6d;
      border-radius: 50% 50% 0 0;
      transform: rotate(-45deg);
    }

    .heart::after {
      transform: rotate(45deg);
      top: -10px;
      left: 0;
    }

    @keyframes float-heart {
      0% {
        opacity: 0;
        transform: translateY(100vh) scale(0.5);
      }
      10% {
        opacity: 1;
        transform: translateY(80vh) scale(0.8);
      }
      90% {
        opacity: 1;
        transform: translateY(-10vh) scale(0.9);
      }
      100% {
        opacity: 0;
        transform: translateY(-30vh) scale(0.5);
      }
    }

    /* Message card */
    .card {
      background: rgba(18, 28, 48, 0.7);
      backdrop-filter: blur(10px);
      border-radius: 18px;
      border: 1px solid rgba(255, 255, 255, 0.1);
      box-shadow: 0 10px 30px rgba(0, 0, 0, 0.4),
                  0 0 30px rgba(255, 77, 109, 0.2);
      padding: 1.5rem;
      max-width: 420px;
      width: 100%;
      text-align: center;
      margin-top: 1rem;
      opacity: 0;
      transform: translateY(20px);
      transition: opacity 1.2s ease-in-out, transform 1.2s ease-in-out;
    }

    .card.bloomed {
      opacity: 1;
      transform: translateY(0);
    }

    .card p {
      font-size: 1.05rem;
      line-height: 1.7;
      letter-spacing: 0.3px;
    }

    /* Button */
    .btn {
      position: relative;
      background: rgba(255, 77, 109, 0.15);
      border: 1px solid rgba(255, 77, 109, 0.4);
      color: #ff4d6d;
      font-size: 1.05rem;
      font-weight: 500;
      padding: 0.9rem 1.6rem;
      border-radius: 50px;
      cursor: pointer;
      outline: none;
      box-shadow: 0 4px 15px rgba(255, 77, 109, 0.15),
                  0 0 20px rgba(255, 77, 109, 0.25);
      transition: all 0.4s ease-in-out;
      letter-spacing: 0.5px;
    }

    .btn:hover {
      transform: translateY(-2px);
      box-shadow: 0 6px 20px rgba(255, 77, 109, 0.25),
                  0 0 30px rgba(255, 77, 109, 0.35);
    }

    .btn:active {
      transform: translateY(0);
    }

    /* Responsive tweaks */
    @media (max-width: 600px) {
      .tulips-container {
        gap: 20px;
      }

      .tulip {
        scale: 0.9;
      }

      .title {
        font-size: 1.5rem;
      }

      .card {
        padding: 1.2rem;
        font-size: 0.95rem;
      }

      .btn {
        font-size: 1rem;
        padding: 0.8rem 1.4rem;
      }
    }

    @media (max-height: 600px) {
      .tulips-container {
        min-height: 200px;
      }

      .stem {
        height: 140px;
      }
    }

    /* Typing animation */
    .typing {
      border-right: 0.1em solid #ff4d6d;
      white-space: nowrap;
      overflow: hidden;
      animation: typing 2.5s steps(30, end) forwards;
    }

    @keyframes typing {
      from {
        width: 0;
      }
      to {
        width: 100%;
      }
    }
  </style>
</head>
<body>
  <!-- Hidden YouTube embed -->
  <div id="yt-container" style="position: absolute; top: -1000px;">
    <iframe
      id="yt-player"
      width="560"
      height="315"
      src="https://www.youtube.com/embed/https://www.youtube.com/watch?v=8Q-C6-A-FAY?start=12&enablejsapi=1"
      title="YouTube video player"
      frameborder="0"
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
      allowfullscreen>
    </iframe>
  </div>

  <!-- Main container -->
  <div class="container">
    <h1 class="title"> Happy Monthsary 💫</h1>

    <div class="tulips-container">
      <!-- Tulips will be generated via JS -->
    </div>

    <button class="btn" id="bloom-btn"> Click Me! </button>

    <div class="card" id="message-card">
      <p id="Thank you for everything love, I love you!!" class="typing"></p>
    </div>
  </div>

  <!-- Hearts container -->
  <div class="hearts" id="hearts"></div>

  <script>
    document.addEventListener("DOMContentLoaded", () => {
      const container = document.querySelector(".tulips-container");
      const btn = document.getElementById("bloom-btn");
      const messageCard = document.getElementById("message-card");
      const messageText = document.getElementById("message-text");
      const heartsContainer = document.getElementById("hearts");
      const ytPlayer = document.getElementById("yt-player");
      const ytContainer = document.getElementById("yt-container");

      // Create tulips
      const tulipCount = 7;
      const tulips = [];

      for (let i = 0; i < tulipCount; i++) {
        const tulip = document.createElement("div");
        tulip.classList.add("tulip", "closed");
        tulip.dataset.index = i;

        const stem = document.createElement("div");
        stem.classList.add("stem");

        const leaf1 = document.createElement("div");
        leaf1.classList.add("leaf", "leaf-1");

        const leaf2 = document.createElement("div");
        leaf2.classList.add("leaf", "leaf-2");

        const buds = document.createElement("div");
        buds.classList.add("buds");

        const petals = document.createElement("div");
        petals.classList.add("petals");

        const petal1 = document.createElement("div");
        petal1.classList.add("petal", "petal-1");

        const petal2 = document.createElement("div");
        petal2.classList.add("petal", "petal-2");

        const petal3 = document.createElement("div");
        petal3.classList.add("petal", "petal-3");

        petals.appendChild(petal1);
        petals.appendChild(petal2);
        petals.appendChild(petal3);

        tulip.appendChild(stem);
        tulip.appendChild(leaf1);
        tulip.appendChild(leaf2);
        tulip.appendChild(buds);
        tulip.appendChild(petals);

        container.appendChild(tulip);
        tulips.push(tulip);
      }

      // Floating hearts
      function createHeart() {
        const heart = document.createElement("div");
        heart.classList.add("heart");

        const size = 12 + Math.random() * 10;
        const duration = 5 + Math.random() * 5;
        const delay = Math.random() * 1
