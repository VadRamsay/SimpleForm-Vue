
<template>
  <div class="min-h-screen flex items-center justify-center">
    <div class="bg-gray-200 border-2 border-black-300 p-8 flex flex-col gap-2 rounded p-2">

      <h2 class="text-center text-">Contact Form</h2>

      <form class="flex flex-col w-96">
        <input class="text-center text-blue-700 border m-2 border-gray-300 rounded p-2" type="text" placeholder="Name Please" />
        <input class="text-center text-blue-700 border m-2 border-gray-300 rounded p-2" type="email" placeholder="Email Please" />
        <input class="text-center text-blue-700 border m-2 pb-46 border-gray-300 rounded p-2" type="text" placeholder="Just Some Random Text..." />
        <button class="border-2 border-gray-500 hover:bg-green-100 m-2 rounded p-2" type="submit">Send</button>
      </form>

    </div>
  </div>
</template>

<script setup>
</script>