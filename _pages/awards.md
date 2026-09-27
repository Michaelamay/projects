---
layout: page
title: resume
---
<html>
  <head>
    <style>
       main { margin: 0 auto; max-width: 50rem !important; }
      .grid-container {
        display: grid;
        grid-template-columns: repeat(2, 1fr); 
        gap: 3px;
        padding: 10px;
      }
      .grid-box {
        position: relative;
        overflow: hidden;
        background: linear-gradient(145deg, #e0b63c 0%, #c69214 48%, #9f6f08 100%);
        color: black;
        padding: 40px;
        text-align: center;
        border-radius: 4px;
        font-family: sans-serif;
        border: 1px solid gray;
        box-shadow:
          inset 0 1px 0 rgba(255, 255, 255, 0.5),
          0 6px 14px rgba(75, 52, 5, 0.2);
      }
      .grid-box::before {
        content: "";
        position: absolute;
        inset: 0 0 auto;
        height: 42%;
        background: linear-gradient(to bottom, rgba(255, 255, 255, 0.3), rgba(255, 255, 255, 0));
        pointer-events: none;
      }
      .grid-box img { max-width: 100%; height: auto; }
      .grid-box--image {
        padding: 8px;
        display: flex;
        align-items: center;
        justify-content: center;
      }
    </style>
  </head>
  <body>
    <div class="grid-container">
      <div class="grid-box grid-box--image">
        <img src="/images/Leetcode-badge.png" />
      </div>
      <div class="grid-box grid-box--image">
        <img src="{{ '/images/skeleton/group.jpg' | relative_url }}" alt="Skeleton team at Yale Hackathon" />
      </div>
      <div class="grid-box">LeetCode recognition badge for completing 50 consecutive days of algorithmic problem solving, including challenges involving trees, hash maps, linked lists, arrays, queues, and time/space complexity optimization.</div>
      <div class="grid-box"><strong>Skeleton — Yale Hackathon, Best Use of Machine Learning</strong><br>Developed in 36 hours by Michael Amay, Adam Wolnikowskie, Michael Vargas, and Evan Visher, Skeleton reimagined the remote desktop application by replacing bitmap and video streaming with structured OCR data transmission. Using OpenCV, Tesseract, and Python, the team captured live screen frames, extracted text and positional metadata, and reconstructed the display on the receiving end — putting Machine Learning at the core of the pipeline.</div>
    </div>
    <script src="https://cdn.jsdelivr.net/npm/canvas-confetti@1.9.2/dist/confetti.browser.min.js"></script>
    <script>
      const duration = 7 * 1000;
      const end = Date.now() + duration;
      const frame = () => {
        confetti({
          particleCount: 10,
          spread: 160,
          origin: { y: 0 },
          colors: ['#FFD700', '#FFA500', '#FF4500', '#00BFFF', '#7CFC00']
        });
        if (Date.now() < end) requestAnimationFrame(frame);
      };
      frame();
    </script>
  </body>
</html>
