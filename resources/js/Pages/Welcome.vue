<template>
    <div>
        <vue-editor v-model="content"></vue-editor>
        {{ content }}
    </div>

</template>

<style scope>

</style>

<script>
import { VueEditor, Quill } from "vue3-editor";

    export default {
        components: {
            VueEditor,
            Quill
        },

        props: {

        },
        mounted() {

        },
        data(){
            return {
                content: "<h1>Some initial content</h1>"
            }
        },
        methods:{

        },
        computed:{

        }
    }
</script>


