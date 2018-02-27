<template>
    <div id="start">
    <h1>{{ getFullName1() }}</h1>
    </div>
</template>
 

<script>
new Vue({
	el: '#start',
  data: {
		firstName: 'Bo',
        lastName: 'Andersen'
  },
  methods: {
  	getFullName1: function() {
    	return this.firstName + ' ' + this.lastName;
    },
});
</script>

<style scoped>
.title
{
  margin-top: 30px;
}
.info
{
  font-weight: 300;
  color: #9aabb1;
  margin: 0;
  margin-top: 10px;
}
.button
{
  margin-top: 30px;
}
</style>
