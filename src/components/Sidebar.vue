<script setup>
import SidebarButton from "./Buttons/SidebarButton.vue";
import Icon from "./Icon.vue";
</script>

<template>
  <div
    class="px-4 py-6 bg-[#070707] duration-300 whitespace-nowrap h-screen overflow-y-auto overflow-x-hidden shrink-0 w-[220px] flex flex-col items-start justify-between fixed left-0"
  >
    <div>
      <nav class="w-full">
        <a class="px-4 flex" href="./index.html" aria-label="logo"
          ><svg width="130" height="15.5" class="mb-8">
            <use href="../assets/icons/logo.svg"></use>
          </svg>
        </a>
        <ul class="flex flex-col gap-1 w-full mb-4">
          <li>
            <SidebarButton path="/" label="Home"
              ><template #icon><Icon name="home" class="size-5" /></template
            ></SidebarButton>
          </li>
          <li>
            <SidebarButton path="/explore" label="Explore"
              ><template #icon><Icon name="explore" class="size-5" /></template
            ></SidebarButton>
          </li>
          <li>
            <SidebarButton path="/library" label="Library"
              ><template #icon><Icon name="library" class="size-5" /></template
            ></SidebarButton>
          </li>
        </ul>
        <p
          class="uppercase text-xs text-white/50 mb-1 pb-1 border-b border-white/10 duration-300 w-full px-4"
        >
          tools
        </p>
        <ul class="flex flex-col gap-1 w-full mb-4">
          <li>
            <SidebarButton path="/text-to-video" label="Text-to-Video"
              ><template #icon
                ><Icon name="text-to-video" class="size-5" /></template
            ></SidebarButton>
          </li>
          <li>
            <SidebarButton path="/script-to-video" label="Script-to-Video"
              ><template #icon
                ><Icon name="script-to-video" class="size-5" /></template
            ></SidebarButton>
          </li>
          <li>
            <SidebarButton path="/image-to-video" label="Image-to-Video"
              ><template #icon
                ><Icon name="image-to-video" class="size-5" /></template
            ></SidebarButton>
          </li>
          <li>
            <SidebarButton path="/voice-and-sound" label="Voice & Sound"
              ><template #icon
                ><Icon name="voice-and-sound" class="size-5" /></template
            ></SidebarButton>
          </li>
        </ul>
        <p
          class="uppercase text-xs text-white/50 mb-1 pb-1 border-b border-white/10 duration-300 w-full px-4"
        >
          assets
        </p>
        <ul class="flex flex-col gap-1 w-full mb-4">
          <li>
            <SidebarButton path="/voice-and-sound" label="Voice & Sound"
              ><template #icon
                ><Icon name="voice-and-sound" class="size-5" /></template
            ></SidebarButton>
          </li>
          <li>
            <SidebarButton path="/voice-and-sound" label="Voice & Sound"
              ><template #icon
                ><Icon name="voice-and-sound" class="size-5" /></template
            ></SidebarButton>
          </li>
        </ul>
        <p
          class="uppercase text-xs text-white/50 mb-1 pb-1 border-b border-white/10 duration-300 w-full px-4"
        >
          guide
        </p>
        <ul>
          <li>
            <SidebarButton path="/voice-and-sound" label="Voice & Sound"
              ><template #icon
                ><Icon name="voice-and-sound" class="size-5" /></template
            ></SidebarButton>
          </li>
        </ul>
      </nav>
    </div>
    <div>
      <ul>
        <li>
          <SidebarButton path="/voice-and-sound" label="Voice & Sound"
            ><template #icon
              ><Icon name="voice-and-sound" class="size-5" /></template
          ></SidebarButton>
        </li>
        <li>
          <SidebarButton path="/voice-and-sound" label="Voice & Sound"
            ><template #icon
              ><Icon name="voice-and-sound" class="size-5" /></template
          ></SidebarButton>
        </li>
      </ul>
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
            aria-label="instagram"
            ><svg class="size-5">
              <use href="../assets/icons/instagram.svg"></use>
            </svg>
          </a>
        </li>
        <li>
          <a
            class="flex items-center justify-center p-1.5 border rounded-lg bg-linear-to-b hover:from-[#1DDE6A]/0 hover:to-[#9FFFCD]/10 hover:border-[#9FFFCD] duration-300 transition"
            href="#"
            aria-label="facebook"
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
            aria-label="tiktok"
            ><svg class="size-5">
              <use href="../assets/icons/tiktok.svg"></use>
            </svg>
          </a>
        </li>
        <li>
          <a
            class="flex items-center justify-center p-1.5 border rounded-lg bg-linear-to-b hover:from-[#1DDE6A]/0 hover:to-[#9FFFCD]/10 hover:border-[#9FFFCD] duration-300 transition"
            href="#"
            aria-label="discord"
            ><svg class="size-5">
              <use href="../assets/icons/discord.svg"></use>
            </svg>
          </a>
        </li>
      </ul>
    </div>
  </div>
</template>
