<template>
  <nav
    class="fixed bottom-5 left-1/2 w-[90%] rounded-full -translate-x-[50%] bg-[#6b6b67] z-[100] shadow-lg"
    v-if="!modal"
  >
    <div class="flex justify-evenly items-center gap-2 px-2">
      <a
        class="my-2 p-1 rounded-ful"
        href="#kata-pengantar"
        v-smooth-scroll
        id="btn-kata-pengantar"
      >
        <img
          src="@/assets/images/rings.png"
          class="h-[36px] w-[36px]"
          alt=""
        />
      </a>
      <a
        class="my-2 p-1 rounded-ful"
        href="#mempelai-wanita"
        v-smooth-scroll
        id="btn-mempelai-wanita"
      >
        <img
          src="@/assets/images/bride.png"
          class="h-[36px] w-[36px]"
          alt=""
        />
      </a>
      <a
        class="my-2 p-1 rounded-ful"
        href="#mempelai-pria"
        v-smooth-scroll
        id="btn-mempelai-pria"
      >
        <img
          src="@/assets/images/groom.png"
          class="h-[36px] w-[36px]"
          alt=""
        />
      </a>
      <a
        class="my-2 p-1 rounded-ful"
        href="#dday"
        v-smooth-scroll
        id="btn-dday"
      >
        <img
          src="@/assets/images/calendar.png"
          class="h-[36px] w-[36px]"
          alt=""
        />
      </a>
      <a
        class="my-2 p-1 rounded-ful"
        href="#lokasi"
        v-smooth-scroll
        id="btn-lokasi"
      >
        <img
          src="@/assets/images/wedding-location.png"
          class="h-[36px] w-[36px]"
          alt=""
        />
      </a>
      <a class="my-2 p-1 rounded-ful" href="#ucapan" v-smooth-scroll>
        <img
          src="@/assets/images/invitation.png"
          class="h-[36px] w-[36px]"
          alt=""
        />
      </a>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Menu",
  props: ["modal"],
};
</script>
