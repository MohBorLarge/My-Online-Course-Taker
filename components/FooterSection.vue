<template>
  <div class="bg-blue-600">
    <div class="container w-full px-8 lg:my-0 lg:mx-auto lg:w-7/12 justify-between text-black">
      <div class="flex py-24">
        <div class="w-2/4 text-2xl font-bold pr-16">
          <p class="mb-4">My Online Course Taker, VI, Lekki, Lagos</p>
          <p class="mb-4">+234 999999123 & +234 89987887</p>
          <a href="mailto@myonlinecoursetaker.ng" class="color-green"
            >info@myonlinecoursetaker.ng</a
          >
        </div>
        <div class="w-1/4 text-xl">
          <ul>
            <li>
              <nuxt-link to="/all-houses">More Info</nuxt-link>
            </li>
            <li>
              <nuxt-link to="/about-myonlinecoursetaker">About myonlinecoursetaker</nuxt-link>
            </li>
            <li>
              <nuxt-link to="/terms-conditions"
                >Term &amp; Conditions</nuxt-link
              >
            </li>
          </ul>
        </div>
        <div class="w-1/4 text-xl ml-8">
          <ul>
            <li class="flex items-center">
              <twitter-icon size="1x" class="custom-class mr-4"></twitter-icon>
              <a href="https://www.twitter.com">Twitter</a>
            </li>
            <li class="flex items-center">
              <facebook-icon
                size="1x"
                class="custom-class mr-4"
              ></facebook-icon>
              <a href="https://www.facebook.com">Facebook</a>
            </li>
            <li></li>
            <li class="flex items-center">
              <instagram-icon
                size="1x"
                class="custom-class mr-4"
              ></instagram-icon>
              <a href="https://www.instagram.com/myonlinecoursetakerng/">Instagram</a>
            </li>
          </ul>
        </div>
      </div>
      <hr style="border-color: white" />
      <div class="pb-12 text-center mt-12 text-xl">
        <p>
          © {{ new Date().getFullYear() }}
          <strong class="font-black">myonlinecoursetaker</strong>. All right reserved
        </p>
      </div>
    </div>
  </div>
</template>

<script>
import { TwitterIcon, FacebookIcon, InstagramIcon } from 'vue-feather-icons'

export default {
  name: 'FooterSection',
  components: { TwitterIcon, FacebookIcon, InstagramIcon },
  data() {
    return {}
  },
}
</script>

<style scoped>
ul li {
  margin: 1rem 0;
}
ul li:first-child {
  margin-top: 0;
}
ul li:last-child {
  margin-bottom: 0;
}
</style>
