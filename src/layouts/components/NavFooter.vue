<template>
  <!-- footer -->
  <footer
    class="flex items-center h-12 mt-5 text-sm bg-gray-100 dark:bg-[#171d30] py-2 z-10 w-full"
  >
    <div class="flex flex-1">
      &copy;&nbsp;
      {{ new Date().getFullYear() }}&nbsp;
      Made With&nbsp;
      <img src="../../assets/images/heart.svg" />&nbsp;
      By&nbsp;
      <a
        class="link link-primary no-underline"
        href="https://kt10vip.xyz"
        target="_blank"
        rel="noopener noreferrer"
        >kt10vip.xyz</a
      >
    </div>
    <div
      class="hidden md:!block"
    >
      <a
        class="link link-primary no-underline mr-4"
        href="https:github.com/KT10VN"
        target="noopener noreferrer"
        >Github</a
      >
      <a
        class="link link-primary no-underline"
        href="https://github.com/KT10VN/explorer"
        target="noopener noreferrer"
        >explorer</a
      >
    </div>
  </footer>
</template>
