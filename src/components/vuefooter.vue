<template>
  <div class="bg-gray-900 p-4 mt-0 lg:mt-24">
    <div class="text-gray-500 font-semi font-semibold text-center text-sm mb-2">
      The dragon is leveling up
      <br />to be more mysterios
    </div>
    <div class="text-center mt-1 mb-1">
      <button
        v-on:click="iglink"
        class="cursor-pointer bg-gray-900 h-12 w-12 rounded-full hover:bg-white transition-all ml-1 mr-1"
        id="clr-trans"
      >
        <font-awesome-icon :icon="['fab', 'instagram']" size="2x" id="compo" style="color:white" />
      </button>

      <button
        v-on:click="githublink"
        class="cursor-pointer bg-gray-900 h-12 w-12 rounded-full hover:bg-white transition-all ml-1 mr-1"
        id="clr-trans"
      >
        <font-awesome-icon :icon="['fab', 'github']" size="2x" id="compo" style="color:white" />
      </button>
    </div>
    <div
      class="text-gray-500 font-semi font-semibold text-center text-xs mt-1"
    >Created by me © MysteriosRyu</div>
    <!-- Icon from font awesome Thank for great Icons -->
  </div>
</template>

<script>
export default {
  methods: {
    iglink: function() {
      window.open("https://www.instagram.com/tanat_riwww/", "_blank");
    },
    githublink: function() {
      window.open("https://github.com/RiwEZ", "_blank");
    }
  }
};
</script>

<style scoped>
#clr-trans:hover #compo {
  color: #1a202c !important;
  transition-duration: 250ms;
}
</style>