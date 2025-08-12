<style>
:root{
  --size: 200px;
  --orbit-size: 400px;
  --bg: #0f172a;
}

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

.profile-container {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100vh;
  background: transparent;
  font-family: sans-serif;
  color: #fff;
}

.orbit-container {
  position: relative;
  width: var(--orbit-size);
  height: var(--orbit-size);
  display: flex;
  align-items: center;
  justify-content: center;
}

.profile {
  width: calc(var(--size) * 2);
  height: calc(var(--size) * 2);
  border-radius: 50%;
  overflow: hidden;
  z-index: 2;
}

.profile img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.orbit {
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);
  width: 100%;
  height: 100%;
  z-index: 3;
}

.tech {
  --angle: 0deg;
  --distance: calc((var(--orbit-size) - var(--size)) / 1.2);
  position: absolute;
  left: 50%;
  top: 50%;
  transform:
    rotate(var(--angle))
    translate(0, calc(-1 * var(--distance)))
    rotate(calc(-1 * var(--angle)));
  width: 40px;
  height: 40px;
  display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 50%;
  transition: background 0.3s;
  animation: orbit 18s linear infinite;
  animation-delay: calc(var(--angle) / -440deg * 18s);
}

.tech:hover {
  background: rgba(255, 255, 255, 0.15);
}

.tech img {
  width: 30px;
  height: 30px;
  object-fit: contain;
}

@keyframes orbit {
  from {
    transform:
      rotate(0deg)
      translate(0, calc(-1 * var(--distance)))
      rotate(0deg);
  }
  to {
    transform:
      rotate(360deg)
      translate(0, calc(-1 * var(--distance)))
      rotate(-360deg);
  }
}
</style>



<h1 align="center">
    <img src="https://readme-typing-svg.herokuapp.com/?font=Righteous&size=35&center=true&vCenter=true&width=500&height=70&duration=3000&lines=Hello+World;+I'm+Jerico+Ocal;&color=00FF9C" />
</h1>

<h3 align="center">Flutter Developer | AI/ML Enthusiast</h3>
<h4 align="center">Building smart, scalable, and user-focused solutions from 🇵🇭</h4>

<br/>
<br/>

<!--
<div align="center">
    <div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 10px;">
        <img src="https://skillicons.dev/icons?i=flutter,dart,androidstudio,apple,php,mysql,supabase,html,css,tailwind,tensorflow,figma,postman,vscode,android,xcode"
            style="pointer-events: none; user-select: none; max-width: 100%;">
    </div>
</div>
-->
<div class="profile-container">
<div class="orbit-container">
    <div class="profile">
      <img src="profile.jpg" alt="Profile Photo">
    </div>
    <div class="orbit">
      <div class="tech" style="--angle:0deg"><img src="flutter.svg" alt="Dart"></div>
      <div class="tech" style="--angle:40deg"><img src="dart.svg" alt="Flutter"></div>
      <div class="tech" style="--angle:80deg"><img src="laravel.svg" alt="Laravel"></div>
      <div class="tech" style="--angle:120deg"><img src="php.svg" alt="PHP"></div>
      <div class="tech" style="--angle:160deg"><img src="supabase.svg" alt="HTML"></div>
      <div class="tech" style="--angle:200deg"><img src="html.svg" alt="CSS"></div>
      <div class="tech" style="--angle:240deg"><img src="css.svg" alt="Tailwind CSS"></div>
      <div class="tech" style="--angle:280deg"><img src="mysql.svg" alt="MySQL"></div>
      <div class="tech" style="--angle:320deg"><img src="supabase.svg" alt="Supabase"></div>
      <div class="tech" style="--angle:360deg"><img src="tensorflow.svg" alt="Supabase"></div>
      <div class="tech" style="--angle:400deg"><img src="tensorflow.svg" alt="Supabase"></div>
    </div>
  </div>
</div>

<br/>
<br/>

<h2 align="center">Stats</h2>
<div align="center">
    <img alt="Top Languages" 
         src="https://github-readme-stats.vercel.app/api/top-langs/?username=Jrcoo13&layout=compact" 
         style="pointer-events: none; user-select: none;" />
</div>

<br/>
<br/>

<h2 align="center">My Contributions</h2>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/tobiasmeyhoefer/tobiasmeyhoefer/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/tobiasmeyhoefer/tobiasmeyhoefer/output/github-snake.svg" />
  <img alt="github-snake" src="https://raw.githubusercontent.com/tobiasmeyhoefer/tobiasmeyhoefer/output/github-snake.svg" />
</picture>
