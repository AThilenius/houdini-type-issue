<script lang="ts">
  /* @type { import('./$houdini').PageData } */
  export let data;

  $: ({ Countries } = data);
</script>

<pre>{JSON.stringify($Countries.data.countries, null, 2)}</pre>
