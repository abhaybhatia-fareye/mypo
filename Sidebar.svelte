
<div id="middle" class="flex">
    <div class="md:bg-slate-100 bg-white lg:w-[15%]  w-0 md:w-0">


      <div id="sidebar ">
          <span class=" text-white text-4xl top-5 left-4 cursor-pointer" onclick="Openbar()">
            <i id="aa" class="bi bi-filter-left px-2 bg-gray-900 rounded-md"></i>
          </span>
          <div class="sidebar fixed top-20 bottom-0 lg:left-0 left-[-300px] duration-1000
            p-2 w-[288px] overflow-y-auto text-center bg-gray-100 shadow h-screen">
            <div class="text-gray-900 text-xl">
              
              <div class="p-2.5 mt-1 flex items-center rounded-md ">
                <button type="button" onclick="closeSidebar()"> <i class="bi bi-app-indicator lg:hidden    px-2 py-1 bg-blue-600 rounded-md"></i></button>
              
                <h1 class="text-[15px]  ml-3 text-xl text-gray-900 font-bold">Tailwindbar</h1>
              </div></div>

              <hr class="my-2 text-gray-600">
              
              <div>
                <div class="p-2.5 mt-3 flex items-center rounded-md 
                px-4 duration-300 cursor-pointer  bg-gray-200">
                  <i class="bi bi-search text-sm"></i>
                  <input class="text-[15px] ml-4 w-full bg-transparent focus:outline-none" placeholder="Serach" />
                </div>
        
                <div class="p-2.5 mt-2 flex items-center rounded-md px-4 duration-300 cursor-pointer  hover:bg-blue-600">
                  <i class="bi bi-house-door-fill"></i>
                  <span class="text-[15px] ml-4 text-gray-900">Home</span>
                </div>
                <div class="p-2.5 mt-2 flex items-center rounded-md px-4 duration-300 cursor-pointer  hover:bg-blue-600">
                  <i class="bi bi-bookmark-fill"></i>
                  <span class="text-[15px] ml-4 text-gray-900">Bookmark</span>
                </div>
                <hr class="my-4 text-gray-600">
                <div class="p-2.5 mt-2 flex items-center rounded-md px-4 duration-300 cursor-pointer  hover:bg-blue-600">
                  <i class="bi bi-envelope-fill"></i>
                  <span class="text-[15px] ml-4 text-gray-900">Messages</span>
                </div>
        
                <div class="p-2.5 mt-2 flex items-center rounded-md px-4 duration-300 cursor-pointer  hover:bg-blue-600">
                  <i class="bi bi-chat-left-text-fill"></i>
                  <div class="flex justify-between w-full items-center" onclick="dropDown()">
                    <span class="text-[15px] ml-4 text-gray-900">Chatbox</span>
                    <span class="text-sm rotate-180" id="arrow">
                      <i class="bi bi-chevron-down"></i>
                    </span>
                  </div>
                </div>
                <div class=" leading-7 text-left text-sm font-thin mt-2 w-4/5 mx-auto text-gray-900" id="submenu">
                  <h1 class="cursor-pointer p-2 hover:bg-gray-700  hover:text-white hover:font-bold rounded-md mt-1">Social</h1>
                  <h1 class="cursor-pointer p-2 hover:bg-gray-700  hover:text-white hover:font-bold rounded-md mt-1">Personal</h1>
                  <h1 class="cursor-pointer p-2 hover:bg-gray-700  hover:text-white hover:font-bold rounded-md mt-1">Friends</h1>
                </div> 
                <div class="p-2.5 lg:hidden mt-2 flex items-center rounded-md px-4 duration-300 cursor-pointer  hover:bg-blue-600">
                  <i class="bi bi-envelope-fill"></i>
                  <span class="text-[15px] ml-4 text-gray-900">Home</span>
                </div>
                <div class="p-2.5 lg:hidden mt-2 flex items-center rounded-md px-4 duration-300 cursor-pointer  hover:bg-blue-600">
                  <i class="bi bi-envelope-fill"></i>
                  <span class="text-[15px] ml-4 text-gray-900">About</span>
                </div>
                <div class="p-2.5 lg:hidden mt-2 flex items-center rounded-md px-4 duration-300 cursor-pointer  hover:bg-blue-600">
                  <i class="bi bi-envelope-fill"></i>
                  <span class="text-[15px] ml-4 text-gray-900">Company</span>
                </div>
        
                <div class="p-2.5 mt-3 flex items-center rounded-md px-4 duration-300 cursor-pointer  hover:bg-blue-600">
                  <i class="bi bi-box-arrow-in-right"></i>
                  <span class="text-[15px] ml-4 text-gray-900">Logout</span>
                </div>
        
              </div>
            </div>
          </div>
      
      </div>
  </div>
<div class="w-[30vw]"></div>
