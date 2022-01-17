<template>
  <div>
    <header-rdev />
    <div class="h-96">
      <video class="w-full object-cover top-0 fixed -z-50 w-full" loop autoplay>
        <source src="~assets/video/video-for-background-website.mp4" type="video/mp4">
      </video>
    </div>
    <div class="w-screen">
      <div class="z-10 -mt-10 mb-10">
      <div class="flex h-60 py-11 gap-x-5 flex-row flex-nowrap overflow-x-scroll hide-scrollbar" style="-webkit-scrollbar: none;">
          <div class="grid grid-cols-4 bg-white py-4 rounded-2xl shadow-xl grow-0 shrink-0" style="width:500px;">
            <div class="p-5">
              <img class="w-20 h-20 object-cover rounded-full" src="~assets/image/sincerely-media-HFeG2vERmWo-unsplash.jpg">
            </div>
            <div class="col-span-3 m-auto">
              <h4 class="font-bold text-xl">Lorem Ipsum</h4>
              <p class="text-sm italic">Lorem ipsum dolor sit amet consectetur adipisicing elit. Hic aperiam sed omnis earum quis corporis accusantium, facilis maxime ab? Dicta enim impedit laudantium.</p>
            </div>
          </div>
          <div class="grid grid-cols-4 bg-white py-4 rounded-2xl shadow-xl grow-0 shrink-0" style="width:500px;">
            <div class="p-5">
              <img class="w-20 h-20 object-cover rounded-full" src="~assets/image/sincerely-media-HFeG2vERmWo-unsplash.jpg">
            </div>
            <div class="col-span-3 m-auto">
              <h4 class="font-bold text-xl">Lorem Ipsum</h4>
              <p class="text-sm italic">Lorem ipsum dolor sit amet consectetur adipisicing elit. Hic aperiam sed omnis earum quis corporis accusantium, facilis maxime ab? Dicta enim impedit laudantium.</p>
            </div>
          </div>
          <div class="grid grid-cols-4 bg-white py-4 rounded-2xl shadow-xl grow-0 shrink-0" style="width:500px;">
            <div class="p-5">
              <img class="w-20 h-20 object-cover rounded-full" src="~assets/image/sincerely-media-HFeG2vERmWo-unsplash.jpg">
            </div>
            <div class="col-span-3 m-auto">
              <h4 class="font-bold text-xl">Lorem Ipsum</h4>
              <p class="text-sm italic">Lorem ipsum dolor sit amet consectetur adipisicing elit. Hic aperiam sed omnis earum quis corporis accusantium, facilis maxime ab? Dicta enim impedit laudantium.</p>
            </div>
          </div>
          <div class="grid grid-cols-4 bg-white py-4 rounded-2xl shadow-xl grow-0 shrink-0" style="width:500px;">
            <div class="p-5">
              <img class="w-20 h-20 object-cover rounded-full" src="~assets/image/sincerely-media-HFeG2vERmWo-unsplash.jpg">
            </div>
            <div class="col-span-3 m-auto">
              <h4 class="font-bold text-xl">Lorem Ipsum</h4>
              <p class="text-sm italic">Lorem ipsum dolor sit amet consectetur adipisicing elit. Hic aperiam sed omnis earum quis corporis accusantium, facilis maxime ab? Dicta enim impedit laudantium.</p>
            </div>
          </div>
          <div class="grid grid-cols-4 bg-white py-4 rounded-2xl shadow-xl grow-0 shrink-0" style="width:500px;">
            <div class="p-5">
              <img class="w-20 h-20 object-cover rounded-full" src="~assets/image/sincerely-media-HFeG2vERmWo-unsplash.jpg">
            </div>
            <div class="col-span-3 m-auto">
              <h4 class="font-bold text-xl">Lorem Ipsum</h4>
              <p class="text-sm italic">Lorem ipsum dolor sit amet consectetur adipisicing elit. Hic aperiam sed omnis earum quis corporis accusantium, facilis maxime ab? Dicta enim impedit laudantium.</p>
            </div>
          </div>
      </div>
      </div>
    </div>
    <div class="bg-white h-screen -mt-40 pt-28">
      <div class="grid grid-cols-2">
        <div class="m-auto px-10">
          <h3 class="text-2xl font-bold text-blue-900">About Us</h3>
          <p class="text-gray-500">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quod exercitationem, fuga nostrum, architecto ducimus at dignissimos autem commodi quisquam dolorum harum dolorem quia, sed doloremque ratione soluta. Ipsam, repellat inventore.</p>
        </div>
        <div>
          <img class=" relative m-auto z-10 h-128 w-128 object-cover rounded-3xl rounded-br-none" src="~assets/image/IMG_8419.jpg" alt="">
          <svg class="absolute z-0 -mt-44 right-0" height="400" width="400">
            <circle cx="250" cy="200" r="150" stroke="green" stroke-width="50" fill="transparent" />
          </svg>
        </div>
      </div>
    </div>
    <footer-rdev />
  </div>
</template>

<style>
/* Hide scrollbar for Chrome, Safari and Opera */
.hide-scrollbar::-webkit-scrollbar {
    display: none;
}

/* Hide scrollbar for IE, Edge and Firefox */
.hide-scrollbar {
    -ms-overflow-style: none; /* IE and Edge */
    scrollbar-width: none; /* Firefox */
}
</style>

<script>
import FooterRdev from '~/components/FooterRdev.vue'
import HeaderRdev from '~/components/HeaderRdev'
export default {
  name: 'IndexPage',
  components: { HeaderRdev, FooterRdev },
}
</script>

  
    FooterRdev  FooterRdev