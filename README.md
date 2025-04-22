<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Animated Tech Stack</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
      overflow-x: hidden;
    }
    .container {
      width: 100%;
      text-align: center;
      padding: 20px 0;
    }
    .icon-row {
      display: flex;
      white-space: nowrap;
      overflow: hidden;
      margin: 10px 0;
    }
    .icon-row img {
      width: 60px;
      height: 60px;
      margin: 0 15px;
      flex-shrink: 0;
    }
    .icon-row.laravel img[src*="Laravel"] {
      width: 80px;
    }
    .icon-row.first {
      animation: slide-left 20s linear infinite;
    }
    .icon-row.second {
      animation: slide-right 20s linear infinite;
    }
    @keyframes slide-left {
      0% { transform: translateX(0); }
      100% { transform: translateX(-100%); }
    }
    @keyframes slide-right {
      0% { transform: translateX(-100%); }
      100% { transform: translateX(0); }
    }
    .icon-row.first:hover, .icon-row.second:hover {
      animation-play-state: paused;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="icon-row first">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" alt="HTML"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" alt="CSS"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JavaScript"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" alt="TypeScript"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" alt="React"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vuejs/vuejs-original.svg" alt="VueJS"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" alt="NextJS"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" alt="NodeJS"/>
      <!-- Duplicate for seamless loop -->
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" alt="HTML"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" alt="CSS"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JavaScript"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" alt="TypeScript"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" alt="React"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vuejs/vuejs-original.svg" alt="VueJS"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" alt="NextJS"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" alt="NodeJS"/>
    </div>
    <div class="icon-row second laravel">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" alt="PHP"/>
      <img src="https://www.logo.wine/a/logo/Laravel/Laravel-Logo.wine.svg" alt="Laravel"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" alt="Git"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" alt="GitHub"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bash/bash-original.svg" alt="Bash"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" alt="Linux"/>
      <!-- Duplicate for seamless loop -->
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" alt="PHP"/>
      <img src="https://www.logo.wine/a/logo/Laravel/Laravel-Logo.wine.svg" alt="Laravel"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" alt="Git"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" alt="GitHub"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bash/bash-original.svg" alt="Bash"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" alt="Linux"/>
    </div>
  </div>
</body>
</html>
