<script>
  export let courseGoal;
</script>

<h1 class={`text-3xl my-4 ${courseGoal.includes("!") ? "text-red-500" : ""}`}>
  {courseGoal}
</h1>
