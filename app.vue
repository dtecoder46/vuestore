<script setup>
function link() {
  window.location.replace("https://youtu.be/cxrEb7MT84E?si=he-LKskfZBY_ybvN");
}

function msg() {
  const rand = (Math.floor(Math.random() * 11));
  let rand_bool;
  
  if (rand == 7) {
    const para = document.createElement("p");
    const txt = document.createTextNode("HAHAHA SIKE. Did you really think you could get away with deleting a Vue box? You foolish mortal. VUE IS IMMORTAL. Redirecting to your punishment...");
    para.appendChild(txt);

    document.getElementById("msg").appendChild(para);

    setTimeout(link, 10000);
  }
}

function print() {
  window.print();
}
</script>

<template>
<div class="text-nuxt-mint bg-nuxt-green scroll-smooth">

  <br><br><br>
  
  <h1 id="name" class="text-5xl ml-20 drop-shadow-2xl">VueStore</h1><br><br>
  <NuxtImg src="/vuestore.jpeg" width="100" height="100" class="ml-20" />

  <br><br><br>

  <div>
    <div class="border-4 w-1/3 ml-20">
      <textarea id="vuefile" value="File name" class="text-2xl ml-5 bg-nuxt-green ring-2 ring-emerald-200 hover:bg-emerald-700"></textarea><br>
      <textarea id="vuetext" value="File content" class="ml-5 bg-nuxt-green ring-2 ring-emerald-200 hover:bg-emerald-700"></textarea>
    </div>
    <button v-on:click="msg" class="ml-20 bg-red-400 flex w-16 p-1 shadow-xl shadow-red-400 ring-2 ring-red-200 active:bg-red-600 active:ring-red-400 hover:bg-red-500">Delete</button>
  </div>

  <br>

  <div id="msg" class="text-emerald-700"></div>
  <br>

  <div>
    <div class="border-4 w-1/3 ml-20">
      <textarea id="vuefile2" value="File name" class="text-2xl ml-5 bg-nuxt-green ring-2 ring-emerald-200 hover:bg-emerald-700"></textarea><br>
      <textarea id="vuetext2" value="File content" class="ml-5 bg-nuxt-green ring-2 ring-emerald-200 hover:bg-emerald-700"></textarea>
    </div>
    <button v-on:click="msg" class="ml-20 bg-red-400 flex w-16 p-1 shadow-xl shadow-red-400 ring-2 ring-red-200 active:bg-red-600 active:ring-red-400 hover:bg-red-500">Delete</button>
  </div>

  <br>

  <div id="msg" class="text-emerald-700"></div>
  <br>

  <div>
    <div class="border-4 w-1/3 ml-20">
      <textarea id="vuefile3" value="File name" class="text-2xl ml-5 bg-nuxt-green ring-2 ring-emerald-200 hover:bg-emerald-700"></textarea><br>
      <textarea id="vuetext3" value="File content" class="ml-5 bg-nuxt-green ring-2 ring-emerald-200 hover:bg-emerald-700"></textarea>
    </div>
    <button v-on:click="msg" class="ml-20 bg-red-400 flex w-16 p-1 shadow-xl shadow-red-400 ring-2 ring-red-200 active:bg-red-600 active:ring-red-400 hover:bg-red-500">Delete</button>
  </div>

  <br>

  <div id="msg" class="text-emerald-700"></div>
  <br>

  <div>
    <div class="border-4 w-1/3 ml-20">
      <textarea id="vuefile4" value="File name" class="text-2xl ml-5 bg-nuxt-green ring-2 ring-emerald-200 hover:bg-emerald-700"></textarea><br>
      <textarea id="vuetext4" value="File content" class="ml-5 bg-nuxt-green ring-2 ring-emerald-200 hover:bg-emerald-700"></textarea>
    </div>
    <button v-on:click="msg" class="ml-20 bg-red-400 flex w-16 p-1 shadow-xl shadow-red-400 ring-2 ring-red-200 active:bg-red-600 active:ring-red-400 hover:bg-red-500">Delete</button>
  </div>

  <br>

  <div id="msg" class="text-emerald-700"></div>
  <br>

  <div>
    <div class="border-4 w-1/3 ml-20">
      <textarea id="vuefile5" value="File name" class="text-2xl ml-5 bg-nuxt-green ring-2 ring-emerald-200 hover:bg-emerald-700"></textarea><br>
      <textarea id="vuetext5" value="File content" class="ml-5 bg-nuxt-green ring-2 ring-emerald-200 hover:bg-emerald-700"></textarea>
    </div>
    <button v-on:click="msg" class="ml-20 bg-red-400 flex w-16 p-1 shadow-xl shadow-red-400 ring-2 ring-red-200 active:bg-red-600 active:ring-red-400 hover:bg-red-500">Delete</button>
  </div>

  <br>

  <div id="msg" class="text-emerald-700"></div>
  <br>

  <div>
    <div class="border-4 w-1/3 ml-20">
      <textarea id="vuefile6" value="File name" class="text-2xl ml-5 bg-nuxt-green ring-2 ring-emerald-200 hover:bg-emerald-700"></textarea><br>
      <textarea id="vuetext6" value="File content" class="ml-5 bg-nuxt-green ring-2 ring-emerald-200 hover:bg-emerald-700"></textarea>
    </div>
    <button v-on:click="msg" class="ml-20 bg-red-400 flex w-16 p-1 shadow-xl shadow-red-400 ring-2 ring-red-200 active:bg-red-600 active:ring-red-400 hover:bg-red-500">Delete</button>
  </div>

  <br>

  <div id="msg" class="text-emerald-700"></div>
  <br>

  <div>
    <div class="border-4 w-1/3 ml-20">
      <textarea id="vuefile7" value="File name" class="text-2xl ml-5 bg-nuxt-green ring-2 ring-emerald-200 hover:bg-emerald-700"></textarea><br>
      <textarea id="vuetext7" value="File content" class="ml-5 bg-nuxt-green ring-2 ring-emerald-200 hover:bg-emerald-700"></textarea>
    </div>
    <button v-on:click="msg" class="ml-20 bg-red-400 flex w-16 p-1 shadow-xl shadow-red-400 ring-2 ring-red-200 active:bg-red-600 active:ring-red-400 hover:bg-red-500">Delete</button>
  </div>

  <br>

  <div id="msg" class="text-emerald-700"></div>
  <br>

  <div>
    <div class="border-4 w-1/3 ml-20">
      <textarea id="vuefile8" value="File name" class="text-2xl ml-5 bg-nuxt-green ring-2 ring-emerald-200 hover:bg-emerald-700"></textarea><br>
      <textarea id="vuetext8" value="File content" class="ml-5 bg-nuxt-green ring-2 ring-emerald-200 hover:bg-emerald-700"></textarea>
    </div>
    <button v-on:click="msg" value="File content" class="ml-20 bg-red-400 flex w-16 p-1 shadow-xl shadow-red-400 ring-2 ring-red-200 active:bg-red-600 active:ring-red-400 hover:bg-red-500">Delete</button>
  </div>

  <br>

  <div id="msg" class="text-emerald-700"></div>
  <br>

  <div>
    <div class="border-4 w-1/3 ml-20">
      <textarea id="vuefile9" value="File name" class="text-2xl ml-5 bg-nuxt-green ring-2 ring-emerald-200 hover:bg-emerald-700"></textarea><br>
      <textarea id="vuetext9" value="File content" class="ml-5 bg-nuxt-green ring-2 ring-emerald-200 hover:bg-emerald-700"></textarea>
    </div>
    <button v-on:click="msg" class="ml-20 bg-red-400 flex w-16 p-1 shadow-xl shadow-red-400 ring-2 ring-red-200 active:bg-red-600 active:ring-red-400 hover:bg-red-500">Delete</button>
  </div>

  <br>

  <div id="msg" class="text-emerald-700"></div>
  <br>
  <div>
    <div class="border-4 w-1/3 ml-20">
      <textarea id="vuefile10" value="File name" class="text-2xl ml-5 bg-nuxt-green ring-2 ring-emerald-200 hover:bg-emerald-700"></textarea><br>
      <textarea id="vuetext10" value="File content" class="ml-5 bg-nuxt-green ring-2 ring-emerald-200 hover:bg-emerald-700"></textarea>
    </div>
    <button v-on:click="msg" class="ml-20 bg-red-400 flex w-16 p-1 shadow-xl shadow-red-400 ring-2 ring-red-200 active:bg-red-600 active:ring-red-400 hover:bg-red-500">Delete</button>
  </div>

  <br>

  <button v-on:click="print" class="ml-20">
    <NuxtImg src="/printer.jpeg" width="40" height="40" />
    Print
  </button>

  <br><br>

  <div id="credits_div" class="ml-20 ring-4 ring-emerald-500 w-96 p-5 bg-emerald-700">
    <h1 id="credits" class="text-2xl">Credits</h1><br>
    <ul>
      <li>Music: Lupang Hinirang (epic version) by L'Orchestra Cinématique</li><br>
      <li>Channel link: <a href="https://www.youtube.com/@LOrchestraCinematique/videos" class="underline">Here</a></li><br>
      <li>Video link: <a href="https://youtu.be/cxrEb7MT84E?si=HjUIqrXovMmELd-Y" class="underline">Here</a></li>
    </ul>
  </div>

  <br>

</div>

</template>

<style scoped>
div {
  font-family: Flavors, sans-serif;
}
</style>