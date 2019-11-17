<template>
  <div class="flex justify-center mt-24" id="m">
    <div
      id="gradient"
      class="sm:flex sm:flex-row items-center ml-4 mr-4 lg:mr-0 lg:ml-0 justify-center rounded-large pb-4"
      style="width: 850px"
    >
      <div class="mt-6 sm:mt-0 lg:mt-12 lg:mb-12">
        <h1 class="text-center font-bold text-xl lg:text-4xl text-white">Want to know more?</h1>
        <h2 class="font-normal text-center text-sm lg:text-2xl text-white">
          This website is an open-source on
          <br />github so visit my github right now!
        </h2>
      </div>
      <img
        src="../assets/pic/githublogo.png"
        alt
        class="ml-20 inline lg:block w-1/3 sm:w-1/5 lg:w-1/6 mt-3 lg:mt-0 lg:ml-4 cursor-pointer"
        v-on:click="githublink"
      />
      <img
        src="../assets/pic/githubmask.png"
        alt
        class="mt-3 inline w-16 sm:w-20 lg:w-24 cursor-pointer"
        v-on:click="githublink"
      />
    </div>
  </div>
</template>

<script>
export default {
  methods: {
    githublink: function() {
      window.open("https://github.com/RiwEZ/portfolio", "_blank");
    }
  }
};
</script>

<style scoped>
#gradient {
  background: linear-gradient(180deg, #6c63ff 0%, #1a202c 100%);
}
</style>