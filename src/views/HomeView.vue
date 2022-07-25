<template>
  <div class="flex gap-2 px-2 basis-4/6">
    <div class="card w-3/5 bg-base-100 shadow-xl h-full">
      <figure>
        <img src="https://placeimg.com/400/225/arch" alt="Shoes" />
      </figure>
      <div class="card-body">
        <h2 class="card-title">Shoes!</h2>
        <p>If a dog chews shoes whose shoes does he choose?</p>
      </div>
    </div>
    <div class="card w-2/5 bg-base-100 shadow-xl h-full">
      <div class="flex flex-col justify-center items-center">
        <text>图片上传</text>
        <button class="btn btn-active btn-primary">打开</button>
        <text>文字</text>
        <input
          type="text"
          placeholder="Type here"
          class="input input-bordered w-full max-w-xs"
        />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HomeView",
  components: {},
};
</script>
