<script lang="ts">
  import Timer from './Timer.svelte'

  let numberTimer = 1

  const addTimer = () => {
    numberTimer += 1
  }
</script>

<div class="flex flex-col">
  <Timer />
</div>

<style></style>
