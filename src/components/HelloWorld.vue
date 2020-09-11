<template>
  <div>
    <h1>Hello {{person.firstname}} {{person.lastname}} from {{from}} !</h1>
  </div>
</template>
<script>
export default {
  data () {
    return {
      person: {
        firstname: 'Irvin',
        lastname:'Tarlao'
      },
      from: 'Lyon'
    }
  }
};
</script>
<style></style>
