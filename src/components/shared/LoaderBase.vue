<template>
  <svg class="prelaoder-animate" width="35" height="35" viewBox="0 0 35 35" fill="none" xmlns="http://www.w3.org/2000/svg">
    <path fill-rule="evenodd" clip-rule="evenodd" d="M33.4942 18.722C34.2474 10.0273 27.905 2.36785 19.2718 1.45089C19.2402 1.44576 19.2082 1.4418 19.1757 1.43905C18.4876 1.38072 17.8814 1.89141 17.8217 2.5797C17.7621 3.26799 18.2716 3.87325 18.9598 3.93158C26.2654 4.68696 31.6388 11.1604 31.0021 18.5107C30.3653 25.861 23.9569 31.3359 16.6281 30.8486C15.9397 30.7925 15.3335 31.3032 15.2739 31.9915C15.2142 32.6798 15.7238 33.2851 16.412 33.3434C16.4444 33.3461 16.4766 33.3476 16.5086 33.3479C25.1737 33.8971 32.741 27.4166 33.4942 18.722Z" fill="url(#paint0_linear_280_13054)"/>
    <path fill-rule="evenodd" clip-rule="evenodd" d="M1.61615 15.9799C2.36935 7.28523 9.93665 0.80474 18.6017 1.35397C18.6337 1.35423 18.6659 1.35572 18.6984 1.35846C19.3865 1.41679 19.8961 2.02205 19.8365 2.71034C19.7768 3.39863 19.1706 3.90932 18.4824 3.85099C11.1534 3.36595 4.745 8.84082 4.10827 16.1911C3.47153 23.5414 8.84488 30.0149 16.1507 30.768C16.8387 30.8286 17.3482 31.4339 17.2886 32.1222C17.229 32.8104 16.6228 33.3211 15.9346 33.2628C15.9022 33.2601 15.8701 33.2561 15.8386 33.251C7.20536 32.334 0.862961 24.6745 1.61615 15.9799Z" fill="currentColor"/>
    <defs>
      <linearGradient id="paint0_linear_280_13054" x1="22.4391" y1="4.58407" x2="30.9419" y2="21.3908" gradientUnits="userSpaceOnUse">
        <stop stop-color="currentColor"/>
        <stop offset="1" stop-color="currentColor" stop-opacity="0"/>
      </linearGradient>
    </defs>
  </svg>
</template>

<style scoped>
.prelaoder-animate {
  animation: rotate-loader 0.8s linear infinite;
}

@keyframes rotate-loader {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(360deg);
  }
}
</style>
