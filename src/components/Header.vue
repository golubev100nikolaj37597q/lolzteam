<template>
  <header>
    <img src="./assets/logo.svg" alt="" class="logo">
    <div class="line"></div>
    <div class="search">
      <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 20 20" fill="none">
        <path
          d="M17.5 17.5L14.5834 14.5833M16.6667 9.58333C16.6667 13.4954 13.4954 16.6667 9.58333 16.6667C5.67132 16.6667 2.5 13.4954 2.5 9.58333C2.5 5.67132 5.67132 2.5 9.58333 2.5C13.4954 2.5 16.6667 5.67132 16.6667 9.58333Z"
          stroke="#B2BEE2" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round" />
      </svg>
      <input type="text" name="" id="" placeholder="Search...">
      
    </div>
    <ul class="list list__flex list__gap-32">
      <li>Trade</li>
      <li>P2P</li>
      <li>Partners</li>
      <li>Mining</li>
      <li>Academy</li>
    </ul>
    <div class="line"></div>
    <div class="btn-group gap-8">
      <button class="button__dark">Register</button>
      <button class="button__blue">Log In</button>
    </div>

  </header>
</template>

<script>
export default {
  name: 'headerCrypto',
  props: {
    
  }
}
</script>
