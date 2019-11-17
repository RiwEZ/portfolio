<template>
  <div>
    <div class="bg-gray-900 flex flex-col lg:flex-row mt-16 p-12 pb-16 sm:p-16">
      <img
        src="../assets/pic/aboutpic.png"
        class="sm:w-5/12 lg:w-1/5 lg:ml-16 self-center"
      />
      <div class="mt-5 lg:mt-0 lg:ml-20">
        <h1 class="font-bold text-white text-2xl lg:text-4xl">
          Hi, I'm Tanat. Nice to meet you!
        </h1>
        <p class="text-gray-500 text-lg lg:text-2xl">
          My full name is Tanat Tangun. My nickname is Riw. I'm living in
          Thailand. I just start learning and writing web and code a while ago
          because I'm interested in machine-learning and web-app. I'm quietly
          confident in my eager to learning new things. I think I'm a
          fast-learner and kind of jack of all trades. I love to improving my
          self to be better so I can make more cool projects.
        </p>
      </div>
    </div>
    <!-- Cool card -->
    <div class="flex justify-center">
      <div
        id="gradient"
        class="rounded-full pt-4 py-6 lg:py-8 px-4 w-4/5 lg:w-1/2 shadow-2xl"
      >
        <h1 class="text-lg lg:text-4xl font-bold text-center text-white">
          Congratulations!
          <br class="sm:hidden" />Now you know who I am.
          <br />
          <a class="text-base lg:text-3xl font-normal text-center text-white"
            >So how this website have made?</a
          >
        </h1>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  methods: {
    iglink: function() {
      window.open("https://www.instagram.com/tanat_riwww/", "_blank");
    }
  }
};
</script>

<style scoped>
#gradient {
  margin-top: -40px;
  background: linear-gradient(180deg, #5e2563 0%, #65799b 100%);
}
</style>
