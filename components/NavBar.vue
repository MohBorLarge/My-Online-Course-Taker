<template>
  <div>
    <nav
      class="container w-full px-8 lg:my-0 lg:mx-auto lg:w-7/12 flex justify-between"
    >
      <div class="w-36 mt-0"><img src="@/assets/images/logo.png" alt="" /></div>
      <div class="hidden flex justify-between mt-2 p-2 text-blue-500 font-semibold lg:flex">
        <ul class="sm:flex">
          <li><a href="" class="hover:text-yellow-400 mr-6">Home</a></li>
          <li><a href="" class="hover:text-yellow-400 mr-6">About Us</a></li>
          <li><a href="" class="hover:text-yellow-400 mr-6">Subject</a></li>
          <li><a href="" class="hover:text-yellow-400 mr-6">Testimonial</a></li>
          <li><a href="" class="hover:text-yellow-400">Contact Us</a></li>
        </ul>
      </div>
      <div class="hidden flex justify-between mt-4 text-blue-500 font-semibold lg:flex">
        <ul class="sm:flex">
          <li>
            <a class="mr-6 hover:bg-yellow-400 rounded p-2 hover:text-white"
              >Sign In</a
            >
          </li>
          <li>
            <a class="mr-6 hover:bg-yellow-400 rounded p-2 hover:text-white"
              >Sign Up</a
            >
          </li>
        </ul>
      </div>
      <div class="menu lg:hidden  mt-4">
        <img src="@/assets/icons/menu.png" alt=""  class="w-6 h-6 mt-1"/>
      </div>
    </nav>
  </div>
</template>
