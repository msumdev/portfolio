<template>
  <section id="main-content ">
    <div class="text-4xl text-center lg:text-left">
      <p>Hello!</p>
      <p class="text-blue-400 font-bold">I make and break things.</p>
    </div>

    <p class="text-neutral-500 w-full max-w-[100%] lg:max-w-[60%] text-center lg:text-left">I'm a software engineer based in the United Kingdom with experience across a variety of projects and programming languages. I specialize in building, modernizing, and maintaining backends, ensuring scalable, efficient, and high-performing systems.</p>
  </section>
  
  <section id="professional-work">
    <p class="text-neutral-400 pt-8 pb-4"><i class="fa-solid fa-arrow-down mr-4"></i> Professional Work</p>
    <div class="grid grid-cols-3 gap-8">
      <article class="col-span-3 md:col-span-1 bg-stone-800 rounded-lg p-4">
        <p class="row-span-1 text-lg font-bold">E-Safety Platform</p>
        <p class="row-span-1 text-neutral-500 text-wrap mt-2 mb-4">
          An E-Safety platform backend created with Laravel and NodeJS with a C# windows client.
          The project was centered around creating tools to enable school staff to better protect their students. Designing a tool like this had its challenges given it had to be capable of supporting thousands of schools around the UK.
        </p>
        <div class="flex flex-wrap gap-2 pt-2">
          <div class="border-2 px-4 py-1 border-blue-400 rounded-full text-sm">laravel 11</div>
          <div class="border-2 px-4 py-1 border-blue-400 rounded-full text-sm">vue 3</div>
          <div class="border-2 px-4 py-1 border-blue-400 rounded-full text-sm">node</div>
          <div class="border-2 px-4 py-1 border-blue-400 rounded-full text-sm">soketi</div>
          <div class="border-2 px-4 py-1 border-blue-400 rounded-full text-sm">c#</div>
          <div class="border-2 px-4 py-1 border-blue-400 rounded-full text-sm">elasticsearch</div>
        </div>
      </article>
      <article class="col-span-3 md:col-span-1 bg-stone-800 rounded-lg p-4">
        <p class="row-span-1 text-lg font-bold">Deployment Engine</p>
        <p class="row-span-1 text-neutral-500 text-wrap mt-2 mb-4">
          To enhance deployment speed for legacy systems, I collaborated with senior developers to design and build a standalone microservice deployment engine.
        </p>
        <div class="flex flex-wrap gap-2 pt-2">
          <div class="border-2 px-4 py-1 border-blue-400 rounded-full text-sm">laravel 11</div>
          <div class="border-2 px-4 py-1 border-blue-400 rounded-full text-sm">kubernetes</div>
          <div class="border-2 px-4 py-1 border-blue-400 rounded-full text-sm">helm</div>
          <div class="border-2 px-4 py-1 border-blue-400 rounded-full text-sm">docker</div>
          <div class="border-2 px-4 py-1 border-blue-400 rounded-full text-sm">perl</div>
          <div class="border-2 px-4 py-1 border-blue-400 rounded-full text-sm">mysql</div>
          <div class="border-2 px-4 py-1 border-blue-400 rounded-full text-sm">tdd</div>
        </div>
      </article>
      <article class="col-span-3 md:col-span-1 bg-stone-800 rounded-lg p-4">
        <p class="row-span-1 text-lg font-bold">Quotation System</p>
        <p class="row-span-1 text-neutral-500 text-wrap mt-2 mb-4">
          As part of an internal initiative to boost productivity in the quoting process, I led the development of a quoting system that automatically generates quotes based on pricing from internet service providers.
        </p>
        <div class="flex flex-wrap gap-2 pt-2">
          <div class="border-2 px-4 py-1 border-blue-400 rounded-full text-sm">laravel 11</div>
          <div class="border-2 px-4 py-1 border-blue-400 rounded-full text-sm">vue 3</div>
          <div class="border-2 px-4 py-1 border-blue-400 rounded-full text-sm">redis</div>
          <div class="border-2 px-4 py-1 border-blue-400 rounded-full text-sm">ansible</div>
        </div>
      </article>
    </div>
  </section>
  
  <section id="personal-projects">
    <p class="text-neutral-400  pt-8"><i class="fa-solid fa-arrow-down mr-4"></i> Personal Projects</p>
    <div class="grid grid-cols-3 gap-8 pt-8">
      <a href="https://github.com/msumdev/discord-bot" target="_blank" class="col-span-3 md:col-span-1 bg-stone-800 hover:bg-stone-850 rounded-lg p-4 flex flex-col">
        <p class="text-lg font-bold">Discord Bot</p>
        <p class="text-neutral-500 text-wrap mt-2">
          A discord bot that was originally created to lookup movies for watch alongs
        </p>
        <div class="flex flex-wrap gap-2 pt-2">
          <div class="border-2 px-4 py-1 border-blue-400 rounded-full text-sm">python 3</div>
          <div class="border-2 px-4 py-1 border-blue-400 rounded-full text-sm">discord</div>
        </div>

        <div class="mt-auto pt-4">
          <p class="text-neutral-400"><i class="fa-brands fa-github text-xl pr-2"></i> Open in GitHub</p>
        </div>
      </a>

      <a href="https://github.com/msumdev/discord-bot-js" target="_blank" class="col-span-3 md:col-span-1 bg-stone-800 hover:bg-stone-850 rounded-lg p-4 flex flex-col">
        <p class="text-lg font-bold">Alexa Discord Bot</p>
        <p class="text-neutral-500 text-wrap mt-2">
          An discord bot designed in node js to be an interface to alexa
        </p>
        <div class="flex flex-wrap gap-2 pt-2">
          <div class="border-2 px-4 py-1 border-blue-400 rounded-full text-sm">node js</div>
          <div class="border-2 px-4 py-1 border-blue-400 rounded-full text-sm">discord</div>
          <div class="border-2 px-4 py-1 border-blue-400 rounded-full text-sm">amazon avs</div>
          <div class="border-2 px-4 py-1 border-blue-400 rounded-full text-sm">amazon api</div>
          <div class="border-2 px-4 py-1 border-blue-400 rounded-full text-sm">prototype</div>
        </div>

        <div class="mt-auto pt-4">
          <p class="text-neutral-400"><i class="fa-brands fa-github text-xl pr-2"></i> Open in GitHub</p>
        </div>
      </a>
      <a href="https://github.com/msumdev/notification-service" target="_blank" class="col-span-3 md:col-span-1 bg-stone-800 hover:bg-stone-850 rounded-lg p-4 flex flex-col">
        <p class="text-lg font-bold">Websocket Notification Service</p>
        <p class="text-neutral-500 text-wrap mt-2 mb-4">
          A websocket server designed to work alongside my laravel social media application
        </p>
        <div class="flex flex-wrap gap-2 pt-2">
          <div class="border-2 px-4 py-1 border-blue-400 rounded-full text-sm">node js</div>
          <div class="border-2 px-4 py-1 border-blue-400 rounded-full text-sm">redis</div>
          <div class="border-2 px-4 py-1 border-blue-400 rounded-full text-sm">docker</div>
        </div>

        <div class="mt-auto pt-4">
          <p class="text-neutral-400"><i class="fa-brands fa-github text-xl pr-2"></i> Open in GitHub</p>
        </div>
      </a>
      <a href="https://github.com/msumdev/social-media-app" target="_blank" class="col-span-3 md:col-span-1 bg-stone-800 hover:bg-stone-850 rounded-lg p-4 flex flex-col">
        <p class="text-lg font-bold">Social Media Application</p>
        <p class="text-neutral-500 text-wrap mt-2 mb-4">
          A social media application that is designed to assist with language learning and bring social media back to what it should be
        </p>
        <div class="flex flex-wrap gap-2 pt-2">
          <div class="border-2 px-4 py-1 border-blue-400 rounded-full text-sm">php 8.2</div>
          <div class="border-2 px-4 py-1 border-blue-400 rounded-full text-sm">laravel 11</div>
          <div class="border-2 px-4 py-1 border-blue-400 rounded-full text-sm">vue 3</div>
          <div class="border-2 px-4 py-1 border-blue-400 rounded-full text-sm">inertiajs</div>
          <div class="border-2 px-4 py-1 border-blue-400 rounded-full text-sm">redis</div>
          <div class="border-2 px-4 py-1 border-blue-400 rounded-full text-sm">mysql</div>
          <div class="border-2 px-4 py-1 border-blue-400 rounded-full text-sm">mongodb</div>
          <div class="border-2 px-4 py-1 border-blue-400 rounded-full text-sm">docker</div>
        </div>

        <div class="mt-auto pt-4">
          <p class="text-neutral-400"><i class="fa-brands fa-github text-xl pr-2"></i> Open in GitHub</p>
        </div>
      </a>
      <a href="https://github.com/msumdev/speech-service" target="_blank" class="col-span-3 md:col-span-1 bg-stone-800 hover:bg-stone-850 rounded-lg p-4 flex flex-col">
        <p class="text-lg font-bold">Speech Service</p>
        <p class="text-neutral-500 text-wrap mt-2 mb-4">
          A speech service designed in python using kaldi to detect wakewords
        </p>
        <div class="flex flex-wrap gap-2 pt-2">
          <div class="border-2 px-4 py-1 border-blue-400 rounded-full text-sm">python 3</div>
          <div class="border-2 px-4 py-1 border-blue-400 rounded-full text-sm">kaldi asr</div>
          <div class="border-2 px-4 py-1 border-blue-400 rounded-full text-sm">websockets</div>
        </div>

        <div class="mt-auto pt-4">
          <p class="text-neutral-400"><i class="fa-brands fa-github text-xl pr-2"></i> Open in GitHub</p>
        </div>
      </a>
      <a href="https://github.com/msumdev/twitch-video-archive-service" target="_blank" class="col-span-3 md:col-span-1 bg-stone-800 hover:bg-stone-850 rounded-lg p-4 flex flex-col">
        <p class="text-lg font-bold">Twitch Video Archive Service</p>
        <p class="text-neutral-500 text-wrap mt-2 mb-4">
          Twitch mute portions of a video depending on if it violates DMCA, this project solves that problem by listening for an online event subscription, then acting as a user to record the footage
        </p>
        <div class="flex flex-wrap gap-2 pt-2">
          <div class="border-2 px-4 py-1 border-blue-400 rounded-full text-sm">php 8.2</div>
          <div class="border-2 px-4 py-1 border-blue-400 rounded-full text-sm">laravel</div>
          <div class="border-2 px-4 py-1 border-blue-400 rounded-full text-sm">redis</div>
          <div class="border-2 px-4 py-1 border-blue-400 rounded-full text-sm">docker</div>
        </div>

        <div class="mt-auto pt-4">
          <p class="text-neutral-400"><i class="fa-brands fa-github text-xl pr-2"></i> Open in GitHub</p>
        </div>
      </a>
    </div>
  </section>
</template>