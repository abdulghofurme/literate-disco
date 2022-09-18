<script>
  import Output from "./Output.svelte";

  let courseGoal = "";
</script>

<main class="w-2/3 float-right p-8">
  <div class="relative">
    <label for="course-goal" class="leading-7 text-sm text-gray-600"
      >Course Goal</label
    >
    <input
      type="text"
      id="course-goal"
      name="course-goal"
      class="w-full bg-white rounded-md border border-gray-300 focus:border-indigo-500 focus:ring-2 focus:ring-indigo-200 text-base outline-none text-gray-700 py-1 px-3 leading-8 transition-colors duration-200 ease-in-out"
      bind:value={courseGoal}
    />
  </div>

  <Output {courseGoal} />
</main>
