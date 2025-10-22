<script setup></script>

<template>
  <div
    class="px-4 py-6 bg-[#070707] duration-300 whitespace-nowrap h-screen overflow-y-auto overflow-x-hidden shrink-0 max-w-[220px] flex flex-col items-start justify-between fixed left-0"
  >
    <div>
      <nav class="w-full">
        <a class="px-4 flex" href="./index.html"
          ><svg width="130" height="15.5" class="mb-8">
            <use href="../assets/icons/logo.svg"></use>
          </svg>
        </a>
        <ul class="flex flex-col gap-1 w-full">
          <li>
            <a
              class="flex items-center gap-3 border rounded-lg border-transparent py-2.5 px-4 bg-linear-to-b hover:from-[#1DDE6A]/0 hover:to-[#9FFFCD]/10 hover:border-[#9FFFCD] duration-300 transition text-sm"
              href="#"
              ><svg class="size-5">
                <use href="../assets/icons/home.svg"></use>
              </svg>
              Home
            </a>
          </li>
          <li>
            <a
              class="flex items-center gap-3 border rounded-lg border-transparent py-2.5 px-4 bg-linear-to-b hover:from-[#1DDE6A]/0 hover:to-[#9FFFCD]/10 hover:border-[#9FFFCD] duration-300 transition text-sm"
              href="#"
              ><svg class="size-5">
                <use href="../assets/icons/explore.svg"></use>
              </svg>
              Explore
            </a>
          </li>
        </ul>
        <p
          class="uppercase text-xs text-white/50 mb-1 pb-1 border-b border-white/10 duration-300 w-full px-4"
        >
          tools
        </p>
        <ul class="flex flex-col gap-1 w-full">
          <li>
            <a
              class="flex items-center gap-3 border rounded-lg border-transparent py-2.5 px-4 bg-linear-to-b hover:from-[#1DDE6A]/0 hover:to-[#9FFFCD]/10 hover:border-[#9FFFCD] duration-300 transition text-sm"
              href="#"
              ><svg class="size-5">
                <use href="../assets/icons/text-to-video.svg"></use>
              </svg>
              Text-to-Video</a
            >
          </li>
          <li>
            <a
              class="flex items-center gap-3 border rounded-lg border-transparent py-2.5 px-4 bg-linear-to-b hover:from-[#1DDE6A]/0 hover:to-[#9FFFCD]/10 hover:border-[#9FFFCD] duration-300 transition text-sm"
              href="#"
              ><svg class="size-5">
                <use href="../assets/icons/image-to-video.svg"></use>
              </svg>
              Image-to-Video</a
            >
          </li>
          <li>
            <a
              class="flex items-center gap-3 border rounded-lg border-transparent py-2.5 px-4 bg-linear-to-b hover:from-[#1DDE6A]/0 hover:to-[#9FFFCD]/10 hover:border-[#9FFFCD] duration-300 transition text-sm"
              href="#"
              ><svg class="size-5">
                <use href="../assets/icons/script-to-video.svg"></use>
              </svg>
              Script-to-Video</a
            >
          </li>
          <li>
            <a
              class="flex items-center gap-3 border rounded-lg border-transparent py-2.5 px-4 bg-linear-to-b hover:from-[#1DDE6A]/0 hover:to-[#9FFFCD]/10 hover:border-[#9FFFCD] duration-300 transition text-sm"
              href="#"
              ><svg class="size-5">
                <use href="../assets/icons/voice-and-sound.svg"></use>
              </svg>
              Voice & Sound</a
            >
          </li>
        </ul>
        <p
          class="uppercase text-xs text-white/50 mb-1 pb-1 border-b border-white/10 duration-300 w-full px-4"
        >
          assets
        </p>
        <ul class="flex flex-col gap-1 w-full">
          <li>
            <a
              class="flex items-center gap-3 border rounded-lg border-transparent py-2.5 px-4 bg-linear-to-b hover:from-[#1DDE6A]/0 hover:to-[#9FFFCD]/10 hover:border-[#9FFFCD] duration-300 transition text-sm"
              href="#"
              ><svg class="size-5">
                <use href="../assets/icons/effects.svg"></use>
              </svg>
              Effects</a
            >
          </li>
          <li>
            <a
              class="flex items-center gap-3 border rounded-lg border-transparent py-2.5 px-4 bg-linear-to-b hover:from-[#1DDE6A]/0 hover:to-[#9FFFCD]/10 hover:border-[#9FFFCD] duration-300 transition text-sm"
              href="#"
              ><svg class="size-5">
                <use href="../assets/icons/templates.svg"></use>
              </svg>
              Templates</a
            >
          </li>
          <li>
            <a
              class="flex items-center gap-3 border rounded-lg border-transparent py-2.5 px-4 bg-linear-to-b hover:from-[#1DDE6A]/0 hover:to-[#9FFFCD]/10 hover:border-[#9FFFCD] duration-300 transition text-sm"
              href="#"
              ><svg class="size-5">
                <use href="../assets/icons/library.svg"></use>
              </svg>
              Library
            </a>
          </li>
        </ul>
      </nav>
    </div>
    <div>
      <p
        class="uppercase text-xs text-white/50 mb-2 pb-1 border-b border-white/10 duration-300 w-full px-4"
      >
        social media
      </p>
      <ul class="flex gap-2">
        <li>
          <a
            class="flex items-center justify-center p-1.5 border rounded-lg bg-linear-to-b hover:from-[#1DDE6A]/0 hover:to-[#9FFFCD]/10 hover:border-[#9FFFCD] duration-300 transition"
            href="#"
            ><svg class="size-5">
              <use href="../assets/icons/instagram.svg"></use>
            </svg>
          </a>
        </li>
        <li>
          <a
            class="flex items-center justify-center p-1.5 border rounded-lg bg-linear-to-b hover:from-[#1DDE6A]/0 hover:to-[#9FFFCD]/10 hover:border-[#9FFFCD] duration-300 transition"
            href="#"
          >
            <svg class="size-5">
              <use href="../assets/icons/facebook.svg"></use>
            </svg>
          </a>
        </li>
        <li>
          <a
            class="flex items-center justify-center p-1.5 border rounded-lg bg-linear-to-b hover:from-[#1DDE6A]/0 hover:to-[#9FFFCD]/10 hover:border-[#9FFFCD] duration-300 transition"
            href="#"
            ><svg class="size-5">
              <use href="../assets/icons/tiktok.svg"></use>
            </svg>
          </a>
        </li>
        <li>
          <a
            class="flex items-center justify-center p-1.5 border rounded-lg bg-linear-to-b hover:from-[#1DDE6A]/0 hover:to-[#9FFFCD]/10 hover:border-[#9FFFCD] duration-300 transition"
            href="#"
            ><svg class="size-5">
              <use href="../assets/icons/discord.svg"></use>
            </svg>
          </a>
        </li>
      </ul>
    </div>
  </div>
</template>
