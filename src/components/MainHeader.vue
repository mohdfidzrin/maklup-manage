<template>
  <div
    class="d-flex justify-content-between flex-wrap flex-md-nowrap align-items-center pt-3 pb-2 mb-3 border-bottom no-print"
  >
    <h1 class="h2">{{ title }}</h1>
    <div class="btn-toolbar mb-2 mb-md-0">
      <div class="btn-group mr-2 d-none">
        <button class="btn btn-sm btn-outline-secondary">Share</button>
        <button class="btn btn-sm btn-outline-secondary">Export</button>
      </div>
      <button class="btn btn-sm btn-outline-secondary dropdown-toggle d-none">
        <span data-feather="calendar"></span>
        This week
      </button>
    </div>
  </div>
</template>

<script>
export default {
  name: "mainheader",
  props: {
    title: String
  }
};
</script>
