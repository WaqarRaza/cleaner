<template>
<!-- component -->
<div>
      <div class="relative min-h-screen  grid bg-black ">
        <div class="flex flex-col sm:flex-row items-center md:items-start sm:justify-center md:justify-start flex-auto min-w-0 ">
          <div
            class="relative sm:w-1/2 xl:w-3/5 bg-blue-500 h-full hidden md:flex flex-auto items-center justify-center p-10 overflow-hidden  text-white bg-no-repeat bg-cover relative" style="background-image: url(https://abs.twimg.com/sticky/illustrations/lohp_en_1302x955.png);">
            <div class="absolute bg-black  opacity-25 inset-0 z-0"></div>
            <div class="w-full  lg:max-w-2xl md:max-w-md z-10 items-center text-center ">
              <div class=" font-bold leading-tight mb-6 mx-auto w-full content-center items-center text-8xl">
              Cleaner
              </div>
            </div>
          </div>
          <div
            class="md:flex md:items-center md:justify-left w-full sm:w-auto md:h-full xl:w-1/2 p-8  md:p-10 lg:p-14 sm:rounded-lg md:rounded-none "
          >
            <div class="max-w-xl w-full space-y-12">
              <div class="lg:text-left text-center">
                <h2 class="mt-6  font-bold text-gray-100">
        
                </h2>
                <h2 class="mt-6 text-7xl font-bold text-gray-100">
                  Happening now
                </h2>
                <p class="mt-10 text-4xl text-gray-200">Join us today.</p>
              </div>
              <div class="flex flex-row justify-center items-center space-x-3"></div>

              <div>
                <button
                  type="submit"
                  class="lg:w-3/5 w-full flex justify-center text-gray-100 p-4   rounded-full tracking-wide font-bold  focus:outline-none focus:shadow-outline hover:bg-indigo-600 shadow-lg bg-indigo-600 cursor-pointer transition ease-in duration-300"
                >
                  Sign up
                </button>
              </div>
              <div>
                    <NuxtLink
                    to="/login"
                    class="lg:w-3/5 w-full flex justify-center border-indigo-600 bg-transparent text-gray-100 p-4 border rounded-full tracking-wide font-semibold  focus:outline-none focus:shadow-outline hover:bg-gray-900 shadow-lg cursor-pointer transition ease-in duration-300"
                  >
                    Log in
                  </NuxtLink>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
</template>

<script>
export default {
  name: 'LoginPage',
}
</script>
