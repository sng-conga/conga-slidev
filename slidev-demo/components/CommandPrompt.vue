<!-- This example requires Tailwind CSS v2.0+ -->
<template>
<div class="w-full subpixel-antialiased h-64 bg-black border-black mx-auto">
    <div class="flex justify-between bg-white border-b border-gray-500">
        <div class="flex flex-row">
            <div style="padding: 5px"><img height="5px" width="12px" src="https://i.postimg.cc/bNnF0xB3/icon.png"></div>
            <div class="text-xs" style="padding-top: 3px;">Command Prompt</div>
        </div>
        <div class="flex">
            <span class="p-2 px-3 hover:bg-gray-300"><img height="10px" width="10px" src="https://i.postimg.cc/BtB4zdMC/min.png"></span>
            <span class="p-2 px-3 hover:bg-gray-300"><img height="10px" width="10px" src="https://i.postimg.cc/vDsG3QLB/max.png"></span>
            <span class="p-2 px-3 hover:bg-red-500 invert"><img height="10px" width="10px" src="https://i.postimg.cc/xNRxPGGK/close.png"></span>
        </div>
    </div>
    <div class="pl-1 pt-1 h-auto text-white font-mono text-xs bg-black">
        <p class="pb-1">Microsoft Windows [Versión 10.0.18363.476]</p>
        <p class="pb-1">(c) 2019 Microsoft Corporation. All rights reserved.</p>
        <p class="pb-1">&nbsp;</p>
        <p class="pb-1">C:\Users\SheingDev> echo " I LOVE CONGA ";</p>
        <p class="pb-1">I LOVE CONGA</p>
    </div>
</div>
</template>
<style>
  .invert:hover > img {
  	filter:invert(100%);
  }
</style>