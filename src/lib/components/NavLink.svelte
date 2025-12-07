<script lang="ts">
  export let label: string = "";
  export let href: string = "#";
</script>

<a {href} class="text-sm font-medium text-gray-600 hover:text-gray-900 transition-colors">
  {label}
</a>
