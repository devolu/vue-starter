<template>
<div id="start">
  <a v-bind:href="blogUrl">Visit my blog</a>
</div>
</template>



<script>
new Vue({
	el: '#start',
  data: {
		blogUrl: 'http://codingexplained.com'
  }
});
</script>