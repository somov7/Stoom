<template>
  <div id="profilePromoteGame">
    <div
      class="col-span-12 md:border-solid md:border-l md:border-black md:border-opacity-25 h-full pb-12 md:col-span-10"
    >
      <div class="px-4 pt-4">
        <form action="#" class="flex flex-col space-y-8">
          <div>
            <h3 class="text-2xl">Promote your crap!</h3>
            <hr />
          </div>
          <div>
            <label class="text-xl">Name of the game</label>
            <select class="w-full py-1 px-2 bg-green-300">
              <option>Mario 64</option>
              <option>Mario 2</option>
              <option>Mario Odessey</option>
            </select>
          </div>
          <div class="w-full">
            <label class="text-xl">Sale %</label>
            <input type="text" class="w-full py-1 px-2 bg-green-300" />
          </div>
          <div class="w-full">
            <label class="text-xl">Due date</label>
            <input type="text" class="w-full py-1 px-2 bg-green-300" />
          </div>
          <div>
            <h3 class="text-2xl">Discount description</h3>
            <hr />
          </div>
          <div class="w-full">
            <textarea
              cols="30"
              rows="10"
              class="w-full py-1 px-2 bg-green-300"
              disabled
            >
Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorem natus nobis odio. Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusantium, eveniet fugiat? Explicabo assumenda dignissimos quisquam perspiciatis corporis sint commodi cumque rem tempora!</textarea
            >
          </div>
          <div class="pt-4 flex justify-center">
            <button class="w-64 bg-green-400 px-2 py-1" type="submit">
              Start promotion
            </button>
          </div>
        </form>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "stoom-profile-add-promotion",
  props: {},
  methods: {},
};
</script>