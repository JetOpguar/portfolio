<template>
  <div class="max-w-7xl m-center pt-48">
    <div
      class="skills text-center mt-10"
      data-aos="fade-up"
      data-aos-delay="100"
      data-aos-duration="800"
    >
      <h2 class="text-5xl dark:text-white">Skills</h2>
      <span class="f-gray text-sm dark:text-white">My Technical Level</span>
    </div>
    <div class="skill-details flex mt-20 flex-col lg:flex-row lg:gap-10">
      <div
        data-aos="fade-down"
        data-aos-duration="1000"
        data-aos-delay="200"
        class="lg:w-1/3 md:w-96 md:m-auto md:mb-16 card bg-white drop-shadow-2xl dark:bg-slate-800"
      >
        <h2 class="pt-7 pl-5 flex items-center">
          <font-awesome-icon
            class="fa-2xl pr-3 f-blue w-20"
            :icon="['fas', 'code']"
          />
          <div class="flex flex-col">
            <h2 class="text-xl dark:text-white">Frontend Developer</h2>
            <span class="text-sm f-gray dark:text-white"
              >Currently using</span
            >
          </div>
        </h2>
        <div
          class="description grid grid-cols-4 gap-4 m-auto lg:px-10 px-5 pt-10"
        >
         
          <div class="p-1 card-mini">
            <img
              src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/61/HTML5_logo_and_wordmark.svg/130px-HTML5_logo_and_wordmark.svg.png"
              alt="HTML5"
              class="h-14"
            />
            <span class="dark:text-white">HTML5</span>
          </div>
          <div class="p-1 card-mini">
            <img
              src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/62/CSS3_logo.svg/800px-CSS3_logo.svg.png"
              class="h-14"
              alt="CSS"
            />
            <span class="dark:text-white">CSS</span>
          </div>

          <div class="p-1 card-mini">
            <img
              src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/6a/JavaScript-logo.png/600px-JavaScript-logo.png?20120221235433"
              class="h-14"
              alt="JavaScript"
            />
            <span class="dark:text-white">JavaScript</span>
          </div>
         
          <div class="p-1 card-mini">
            <img
              src="https://seeklogo.com/images/V/vuejs-logo-17D586B587-seeklogo.com.png"
              class="h-14"
              alt="VUEJS"
            />
            <span class="dark:text-white">VueJs</span>
          </div>
          

         
        </div>
      </div>
      <div
        data-aos="fade-down"
        data-aos-duration="1000"
        data-aos-delay="400"
        class="lg:w-1/3 md:w-96 md:m-auto md:mb-16 card bg-white drop-shadow-2xl dark:bg-slate-800"
      >
        <h2 class="pt-7 pl-5 flex items-center">
          <font-awesome-icon
            class="fa-2xl pr-3 f-blue w-20"
            :icon="['fas', 'code-branch']"
          />
         
          <div class="flex flex-col">
            <h2 class="text-xl dark:text-white">Others</h2>
            <span class="text-sm f-gray dark:text-white">Acquired Skills</span>
          </div>
        </h2>
        <div
          class="description grid grid-cols-4 gap-4 m-auto lg:px-10 px-5 pt-10"
        >
          <div class="p-1 card-mini">
            <img
              src="https://seeklogo.com/images/G/github-logo-5F384D0265-seeklogo.com.png"
              class="h-14"
              alt="Git"
            />
            <span class="dark:text-white">Git</span>
          </div>
          <div class="p-1 card-mini">
            <img
              src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/ec/Wondershare_filmora_logo.svg/640px-Wondershare_filmora_logo.svg.png"
              class="h-14"
              alt="Jira"
            />
            <span class="dark:text-white">Filmora</span>
          </div>
          <div class="p-1 card-mini">
            <img
              src="https://archive.axure.com/img/rpicon.png"
              class="h-14"
              alt="Figma"
            />
         <span class="dark:text-white">Axure RP</span>
          
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
