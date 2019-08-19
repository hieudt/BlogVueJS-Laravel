<template>
    <div>
        <span>{{ message }}</span> <br/>
        <input type="text" v-model="message">
    </div>
</template>

<script>
    export default {
        mounted() {
            console.log('Component mounted.')
        },
      data() {
          return {
              message: 'That is hieu',
              signatures: [],
              pageCount: 1,
              endpoint: 'api/signatures?page='
          };
        },

        created() {
        },

        methods: {
        }
    }
</script>
