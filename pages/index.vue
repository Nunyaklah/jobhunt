<template>
  <div class="p-10 bg-primary">
    <nav class="flex justify-between">
      <h1 class="font-extrabold text-2xl">Jobhunt</h1>
      <button
        class="bg-green-500 hover:bg-green-700 text-white font-bold py-2 px-8 rounded-full"
      >
        Login
      </button>
    </nav>
    <div class="flex gap-10 items-center pl-20 pr-20 pt-4 justify-center">
      <div class="w-2/5">
        <h1 class="font-extrabold text-6xl leading-none">
          Get hired by the popular teams
        </h1>
        <p class="pt-8">
          Find a job according to your interest simply click on search. And
          choose category accorfing to your skills.
        </p>
      </div>
      <img class="p-10 w-2/5" src="../assets/puzzle.png" alt="" />
    </div>
    <div
      class="bg-gray-400 w-3/6 h-20 ml-40 rounded-full flex p-4 justify-between font-bold items-center shadow"
    >
      <div class="flex items-center pl-4">
        <svg
          class="w-4 h-4"
          fill="none"
          stroke="currentColor"
          viewBox="0 0 24 24"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"
          ></path>
        </svg>
        <p class="pl-2">Job Title or keyword</p>
      </div>
      <div class="flex items-center">
        <svg
          class="w-6 h-6"
          fill="none"
          stroke="currentColor"
          viewBox="0 0 24 24"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"
          ></path>
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"
          ></path>
        </svg>
        <p class="pl-2">Location</p>
      </div>
      <div>
        <button
          class="bg-green-500 hover:bg-green-700 text-white font-bold py-4 px-10 rounded-full"
        >
          Search
        </button>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
@apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
</style>
