<template>
  <h1>Jobs</h1>
  <div v-for="job in jobs" :key="job.id">

  </div>
</template>

<script>
export default {
    data() {
        return {
             jobs: [
                {title: 'UX Designer', id: 1, details: 'detail 1'},
                {title: 'Web Developer', id: 2, details: 'detail 2'},
                {title: 'Mobile Developer', id: 3, details: 'detail 3'},
             ]
        }
    }
}
</script>

<style>

</style>