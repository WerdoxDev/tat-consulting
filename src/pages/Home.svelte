<script lang="ts">
  import { Icon } from "@steeze-ui/svelte-icon";
  import { MapPin, Clock, Phone, ChevronRight, Beaker } from "@steeze-ui/heroicons";
  import { Twitter, Facebook, Linkedin, Instagram } from "@steeze-ui/remix-icons";
</script>

<div class="w-full flex flex-col justify-center items-center sm:gap-y-10 gap-y-3">
  <div class="flex justify-center items-center bg-slate-700 p-5 sm:mt-10 mt-3 rounded-2xl gap-x-10 w-11/12 sm:w-max">
    <img src="/src/assets/logo.png" class="sm:w-36 w-40" alt="logo" />
    <div class="justify-center items-center gap-x-5 hidden sm:flex">
      <div class="w-0.5 bg-slate-600 h-10" />
      <a href="/#home" class="px-2 py-1 rounded-lg text-white border-sky-500 hover:border-b-2 transition-all duration-75 font-bold cursor-pointer">Home</a>
      <div class="w-0.5 bg-slate-600 h-10" />
      <a href="/#about" class="px-2 py-1 rounded-lg text-white border-sky-500 hover:border-b-2 transition-all duration-75 font-bold cursor-pointer">About</a>
      <div class="w-0.5 bg-slate-600 h-10" />
      <a href="/#service" class="px-2 py-1 rounded-lg text-white border-sky-500 hover:border-b-2 transition-all duration-75 font-bold cursor-pointer">Service</a>
    </div>
  </div>
  <div class="h-0.5 w-1/2 bg-slate-600" />
  <div class="flex flex-col sm:flex-row justify-center items-center gap-x-10 gap-y-3 scroll-my-20" id="home">
    <div class="sm:w-[30rem] sm:h-[30rem] w-72 flex justify-center items-center">
      <div class="border-2 border-lime-500 rounded-3xl sm:p-10 p-5">
        <p class="font-bold sm:text-5xl text-4xl text-center text-white sm:mb-5 mb-2">Welcome to Tatbilling.com</p>
        <p class="text-xl text-slate-400 text-center sm:text-left">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
      </div>
    </div>
    <div class="border-2 border-sky-500 overflow-hidden rounded-3xl h-max">
      <img src="/src/assets/home.jpg" alt="home" class="sm:w-[30rem] sm:h-[30rem] w-72 h-72 object-cover" />
    </div>
  </div>
  <div class="flex flex-col sm:flex-row-reverse justify-center items-center gap-x-10 gap-y-3 scroll-my-20" id="about">
    <div class="sm:w-[30rem] sm:h-[30rem] w-72 flex justify-center items-center">
      <div class="border-2 border-lime-500 rounded-3xl sm:p-10 p-5">
        <p class="font-bold sm:text-5xl text-4xl text-center sm:text-left text-white sm:mb-5 mb-2">About Us!</p>
        <p class="text-xl text-slate-400 text-center sm:text-left">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Blandit turpis cursus in hac habitasse platea dictumst quisque sagittis. Duis ultricies lacus sed turpis tincidunt id aliquet risus feugiat. Nunc vel risus commodo
          viverra maecenas accumsan lacus.
        </p>
      </div>
    </div>
    <div class="border-2 border-sky-500 overflow-hidden rounded-3xl">
      <img src="/src/assets/about.jpg" alt="about" class="sm:w-[30rem] sm:h-[30rem] w-72 h-72 object-cover" />
    </div>
  </div>
  <div class="h-0.5 w-1/2 bg-slate-600" />
  <div class="border-2 border-sky-500 text bg-slate-700 text-white font-bold p-2 text-xl rounded-xl" id="service">Our Service</div>
  <div class="flex flex-wrap justify-center items-center w-full gap-x-5 gap-y-3 sm:gap-y-5">
    <div class="bg-slate-700 p-5 rounded-xl flex flex-col justify-center items-center gap-y-2 sm:max-w-sm max-w-xs">
      <div class="bg-slate-800 rounded-lg p-2 w-max flex justify-center items-center gap-x-3">
        <Icon src={Beaker} theme="solid" class="text-sky-500 w-10 h-10" />
        <p class="text-white font-bold text-xl">Key point 1</p>
      </div>
      <p class="text-slate-300 text-xl text-center sm:text-left">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
    </div>
    <div class="bg-slate-700 p-5 rounded-xl flex flex-col justify-center items-center gap-y-2 sm:max-w-sm max-w-xs">
      <div class="bg-slate-800 rounded-lg p-2 w-max flex justify-center items-center gap-x-3">
        <Icon src={Beaker} theme="solid" class="text-sky-500 w-10 h-10" />
        <p class="text-white font-bold text-xl">Key point 2</p>
      </div>
      <p class="text-slate-300 text-xl text-center sm:text-left">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
    </div>
    <div class="bg-slate-700 p-5 rounded-xl flex flex-col justify-center items-center gap-y-2 sm:max-w-sm max-w-xs">
      <div class="bg-slate-800 rounded-lg p-2 w-max flex justify-center items-center gap-x-3">
        <Icon src={Beaker} theme="solid" class="text-sky-500 w-10 h-10" />
        <p class="text-white font-bold text-xl">Key point 3</p>
      </div>
      <p class="text-slate-300 text-xl text-center sm:text-left">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
    </div>
  </div>
  <div class="bg-slate-700 w-full p-5 flex flex-col justify-center items-center">
    <div class="flex flex-col sm:flex-row justify-around items-start w-full h-full gap-x-10 gap-y-5">
      <div class="flex flex-col justify-center items-start gap-y-2">
        <p class="text-2xl text-white mb-3">Info</p>
        <div class="flex justify-center items-center gap-x-2 bg-slate-600 rounded-lg py-1 px-2 shadow-sm">
          <Icon src={MapPin} theme="solid" class="text-sky-400 w-7 h-7" />
          <p class="text-slate-200">Jam-e Jam, Shiraz, Iran</p>
        </div>
        <div class="flex justify-center items-center gap-x-2 bg-slate-600 rounded-lg py-1 px-2 shadow-sm">
          <Icon src={Clock} theme="solid" class="text-sky-400 w-7 h-7" />
          <p class="text-slate-200">Sat - Tue: 09.00 AM - 05.00 PM</p>
        </div>
        <div class="flex justify-center items-center gap-x-2 bg-slate-600 rounded-lg py-1 px-2 shadow-sm">
          <Icon src={Phone} theme="solid" class="text-sky-400 w-7 h-7" />
          <p class="text-slate-200">+98 939 930 7656</p>
        </div>
        <div class="flex justify-center items-center gap-x-3">
          <div class="bg-slate-600 p-1 rounded-lg shadow-sm">
            <Icon src={Twitter} theme="solid" class="text-sky-400 w-7 h-7" />
          </div>
          <div class="bg-slate-600 p-1 rounded-lg shadow-sm">
            <Icon src={Facebook} theme="solid" class="text-sky-400 w-7 h-7" />
          </div>
          <div class="bg-slate-600 p-1 rounded-lg shadow-sm">
            <Icon src={Linkedin} theme="solid" class="text-sky-400 w-7 h-7" />
          </div>
          <div class="bg-slate-600 p-1 rounded-lg shadow-sm">
            <Icon src={Instagram} theme="solid" class="text-sky-400 w-7 h-7" />
          </div>
        </div>
      </div>
      <div class="flex flex-col justify-center items-start gap-y-2">
        <p class="text-2xl text-white mb-3">Quick links</p>
        <div class="flex justify-center items-center gap-x-2 cursor-pointer">
          <Icon src={ChevronRight} theme="solid" class="text-white w-5 h-5" />
          <a href="/#home" class="text-slate-200">Home</a>
        </div>
        <div class="flex justify-center items-center gap-x-2 cursor-pointer">
          <Icon src={ChevronRight} theme="solid" class="text-white w-5 h-5" />
          <a href="/#about" class="text-slate-200">About</a>
        </div>
        <div class="flex justify-center items-center gap-x-2 cursor-pointer">
          <Icon src={ChevronRight} theme="solid" class="text-white w-5 h-5" />
          <a href="/#service" class="text-slate-200">Service</a>
        </div>
      </div>
    </div>
    <a href="mailto:matin.tat85@gmail.com" class="text-slate-400 text-center">Designed by Matin Tat</a>
  </div>
</div>
