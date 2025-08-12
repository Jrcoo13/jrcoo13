<!-- Tailwind CSS CDN -->
<script src="https://cdn.tailwindcss.com"></script>

<style>
@keyframes orbit {
  from {
    transform: rotate(0deg)
      translate(0, calc(-1 * var(--distance)))
      rotate(0deg);
  }
  to {
    transform: rotate(360deg)
      translate(0, calc(-1 * var(--distance)))
      rotate(-360deg);
  }
}
.tech {
  --angle: 0deg;
  --distance: calc((400px - 200px) / 1.2); /* orbit-size - size */
  position: absolute;
  left: 50%;
  top: 50%;
  transform:
    rotate(var(--angle))
    translate(0, calc(-1 * var(--distance)))
    rotate(calc(-1 * var(--angle)));
  animation: orbit 18s linear infinite;
  animation-delay: calc(var(--angle) / -440deg * 18s);
}
.tech:hover {
  background: rgba(255, 255, 255, 0.15);
}
</style>

<h1 class="text-center">
  <img src="https://readme-typing-svg.herokuapp.com/?font=Righteous&size=35&center=true&vCenter=true&width=500&height=70&duration=3000&lines=Hello+World;+I'm+Jerico+Ocal;&color=00FF9C" />
</h1>

<h3 class="text-center">Flutter Developer | AI/ML Enthusiast</h3>
<h4 class="text-center">Building smart, scalable, and user-focused solutions from 🇵🇭</h4>

<div class="flex items-center justify-center min-h-screen">
  <div class="relative flex items-center justify-center" style="width:400px;height:400px;">
    <!-- Profile -->
    <div class="rounded-full overflow-hidden z-20" style="width:400px;height:400px;">
      <img src="profile.jpg" alt="Profile Photo" class="w-full h-full object-cover" />
    </div>
    <div class="absolute left-1/2 top-1/2 -translate-x-1/2 -translate-y-1/2 w-full h-full z-30">
      <div class="tech w-10 h-10 flex items-center justify-center rounded-full" style="--angle:0deg;">
        <img src="flutter.svg" class="w-8 h-8" />
      </div>
      <div class="tech w-10 h-10 flex items-center justify-center rounded-full" style="--angle:40deg;">
        <img src="dart.svg" class="w-8 h-8" />
      </div>
      <div class="tech w-10 h-10 flex items-center justify-center rounded-full" style="--angle:80deg;">
        <img src="laravel.svg" class="w-8 h-8" />
      </div>
      <div class="tech w-10 h-10 flex items-center justify-center rounded-full" style="--angle:120deg;">
        <img src="php.svg" class="w-8 h-8" />
      </div>
      <div class="tech w-10 h-10 flex items-center justify-center rounded-full" style="--angle:160deg;">
        <img src="supabase.svg" class="w-8 h-8" />
      </div>
      <div class="tech w-10 h-10 flex items-center justify-center rounded-full" style="--angle:200deg;">
        <img src="html.svg" class="w-8 h-8" />
      </div>
      <div class="tech w-10 h-10 flex items-center justify-center rounded-full" style="--angle:240deg;">
        <img src="css.svg" class="w-8 h-8" />
      </div>
      <div class="tech w-10 h-10 flex items-center justify-center rounded-full" style="--angle:280deg;">
        <img src="mysql.svg" class="w-8 h-8" />
      </div>
      <div class="tech w-10 h-10 flex items-center justify-center rounded-full" style="--angle:320deg;">
        <img src="supabase.svg" class="w-8 h-8" />
      </div>
      <div class="tech w-10 h-10 flex items-center justify-center rounded-full" style="--angle:360deg;">
        <img src="tensorflow.svg" class="w-8 h-8" />
      </div>
      <div class="tech w-10 h-10 flex items-center justify-center rounded-full" style="--angle:400deg;">
        <img src="tensorflow.svg" class="w-8 h-8" />
      </div>
    </div>
  </div>
</div>

<h2 class="text-center">Stats</h2>
<div class="flex justify-center">
  <img alt="Top Languages" 
       src="https://github-readme-stats.vercel.app/api/top-langs/?username=Jrcoo13&layout=compact" 
       class="select-none" />
</div>

<h2 class="text-center mt-8">My Contributions</h2>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/tobiasmeyhoefer/tobiasmeyhoefer/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/tobiasmeyhoefer/tobiasmeyhoefer/output/github-snake.svg" />
  <img alt="github-snake" src="https://raw.githubusercontent.com/tobiasmeyhoefer/tobiasmeyhoefer/output/github-snake.svg" />
</picture>



<h1 align="center">
    <img src="https://readme-typing-svg.herokuapp.com/?font=Righteous&size=35&center=true&vCenter=true&width=500&height=70&duration=3000&lines=Hello+World;+I'm+Jerico+Ocal;&color=00FF9C" />
</h1>

<h3 align="center">Flutter Developer | AI/ML Enthusiast</h3>
<h4 align="center">Building smart, scalable, and user-focused solutions from 🇵🇭</h4>

<br/>
<br/>

<div align="center">
    <div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 10px;">
        <img src="https://skillicons.dev/icons?i=flutter,dart,androidstudio,apple,php,mysql,supabase,html,css,tailwind,tensorflow,figma,postman,vscode,android,xcode"
            style="pointer-events: none; user-select: none; max-width: 100%;">
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
