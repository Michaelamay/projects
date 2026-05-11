---
layout: page
title: resume
---
<html>
  <head>
    <style>
        main {
                margin: 0 auto;
                max-width: 76rem !important;
        }
      .grid-container {
        display: grid;
        grid-template-columns: repeat(2, 1fr); 
        gap: 3px; /* Space between boxes */
        padding: 10px;
      }
      .grid-box {
        background-color: white;
        color: black;
        padding-left: 1px;  /* Reduce left spacing */
        padding-right: 1px; /* Reduce right spacing */
        padding: 40px;
        text-align: center;
        border-radius: 4px;
        font-family: sans-serif;
        border: 1px solid gray; /* Add this line */
      }
      .grid-box img {
        max-width: 100%;
        height: auto; /* Maintains aspect ratio */
      }
      .grid-box--image {
        padding: 8px;
        display: flex;
        align-items: center;    /* Centers vertically */
        justify-content: center; /* Centers horizontally */
      }
    </style>
    <script src="https://cdn.jsdelivr.net/npm/canvas-confetti@1.9.2/dist/confetti.browser.min.js"></script>
  </head>

  <body>
      <script>
            const duration = 7 * 1000; // 5 seconds
            const end = Date.now() + duration;
            const frame = () => {
            confetti({ particleCount: 5, spread: 160, origin: { y: 0 } });
            if (Date.now() < end) requestAnimationFrame(frame);
            };
            frame();
      </script>
      <script>
              confetti({
                particleCount: 200,
                spread: 160,
                origin: { y: 0 },      /* Drops from the top */
                colors: ['#FFD700', '#FFA500', '#FF4500', '#00BFFF', '#7CFC00']
              });
      </script>
      <div class="grid-container">
        <div class="grid-box grid-box--image">
          <img src="/images/Leetcode-badge.png" />
        </div>
        <div class="grid-box grid-box--image">
          <img src="/images/group.jpg" />
        </div>
        <div class="grid-box">
          LeetCode recognition badge for completing 50 consecutive days of algorithmic problem solving, including challenges involving trees, hash maps, linked lists, arrays, queues, and time/space complexity optimization.
        </div>
        <div class="grid-box">
          Member of the winning 4-person team at the Yale Annual Hackathon for developing “Skeleton,” a remote desktop software solution designed to improve the efficiency of traditional remote desktop applications. Built a machine learning–driven alternative to conventional video bitmap streaming by extracting screen data, transmitting it through lightweight JSON payloads, and reconstructing the interface on the client side, resulting in improved speed, reduced bandwidth usage, and enhanced performance.
        </div>
      </div>
  </body>
</html>
