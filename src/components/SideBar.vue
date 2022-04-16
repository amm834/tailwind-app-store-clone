<template>
  <div class="w-60 min-h-screen fixed bg-slate-800 flex flex-col items-center justify-between">
    <div class="w-full flex flex-col items-center">
      <!--      Search Box-->
      <div class="relative py-8  flex items-center text-gray-300">
        <input type="text" placeholder="Search"
               class="focus:outline-none rounded py-1 pl-10 bg-gray-600 border border-gray-500 caret-gray-300 text-sm">
        <div class="text-gray-500 absolute left-4  top-9">
          <svg class="w-5" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor"
               stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
            <circle cx="11" cy="11" r="8"></circle>
            <line
                x1="21" y1="21" x2="16.65" y2="16.65"></line>
          </svg>
        </div>
      </div>
      <!--      Menu Items-->
      <div class="w-full flex flex-col gap-y-3">
        <!--        Active Item -->
        <div class="w-ful flex px-10 gap-x-3 bg-gray-700 text-gray-300 py-2">
          <span>
<svg class="w-6 fill-current" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor"
     stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polygon
    points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"></polygon></svg>
          </span>
          <span>Discover</span>
        </div>
        <!--        None Active Items-->
        <div class="w-ful flex px-10 gap-x-3 text-gray-300 py-2">
          <span>

<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor"
     stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-feather"><path
    d="M20.24 12.24a6 6 0 0 0-8.49-8.49L5 10.5V19h8.5z"></path><line x1="16" y1="8" x2="2" y2="22"></line><line
    x1="17.5" y1="15" x2="9" y2="15"></line></svg>
          </span>
          <span>Create</span>
        </div>
        <div class="w-ful flex px-10 gap-x-3 text-gray-300 py-2">
          <span>
<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor"
     stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="22" y1="2" x2="11" y2="13"></line><polygon
    points="22 2 15 22 11 13 2 9 22 2"></polygon></svg>
          </span>
          <span>Work</span>
        </div>
        <div class="w-ful flex px-10 gap-x-3 text-gray-300 py-2">
          <span>

<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor"
     stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-play"><polygon
    points="5 3 19 12 5 21 5 3"></polygon></svg>
          </span>
          <span>Play</span>
        </div>
        <div class="w-ful flex px-10 gap-x-3 text-gray-300 py-2">
          <span>

<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor"
     stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-pen-tool"><path
    d="M12 19l7-7 3 3-7 7-3-3z"></path><path d="M18 13l-1.5-7.5L2 2l3.5 14.5L13 18l5-5z"></path><path
    d="M2 2l7.586 7.586"></path><circle cx="11" cy="11" r="2"></circle></svg>
          </span>
          <span>Develop</span>
        </div>
        <div class="w-ful flex px-10 gap-x-3 text-gray-300 py-2">
          <span>

<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor"
     stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-layers"><polygon
    points="12 2 2 7 12 12 22 7 12 2"></polygon><polyline points="2 17 12 22 22 17"></polyline><polyline
    points="2 12 12 17 22 12"></polyline></svg>
          </span>
          <span>Categories</span>
        </div>
        <div class="w-ful flex px-10 gap-x-3 text-gray-300 py-2">
          <span>

<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor"
     stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-upload"><path
    d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"></path><polyline points="17 8 12 3 7 8"></polyline><line x1="12"
                                                                                                           y1="3"
                                                                                                           x2="12"
                                                                                                           y2="15"></line></svg>
          </span>
          <span>Updates</span>
        </div>
      </div>
    </div>
    <!--      Footer -->
    <div class="py-8">
      <div class="flex items-center gap-x-2">
        <div class="w-12 h-12 rounded-full bg-gray-500 flex items-center justify-center text-gray-800">
          AM
        </div>
        <span class="text-gray-300 font-bold">
            Aung Myat Moe
          </span>
      </div>
    </div>
  </div>
</template>