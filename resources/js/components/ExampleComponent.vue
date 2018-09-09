<template>
    <div class="container test">
        <div class="row justify-content-center">
            <div class="col-md-8">
                <div class="card card-default">
                    <div class="card-header">Example Component</div>

                    <div class="card-body">
                        I'm an example component.
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
      data: {
        temp: 12,
        temp2: 1231
      },
      mounted() {
        console.log('Component mounted.')
      },
      methods: {
        test() {
          return 1 + this.temp
        }
      }
    }
</script>


<style lang="sass">
    .test
        color: red

        &.test2
            color: green
</style>