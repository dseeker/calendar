<script>
export default {
  props: {
    event: { type: Object, required: true },
  },
  // mounted() {
  //   console.log("mounted: " + this.event);
  // },
  // beforeDestroy() {
  //   console.log("beforeDestroy: " + this.event.title);
  // },
  // destroyed() {
  //   console.log("destroyed: " + this.event.title);
  // },
};
</script>

<template>
  <div style="white-space: normal; overflow: hidden; text-overflow: ellipsis; display: -webkit-box; -webkit-line-clamp: 2; -webkit-box-orient: vertical;">{{ event.title }}</div>
</template>