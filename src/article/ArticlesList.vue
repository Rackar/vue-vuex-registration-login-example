<template>
    <div>
        <div>{{article.title}}</div>
        -------------------------
        <div>
            {{article.content}}
        </div>
    </div>
</template>

<script>
    export default {
        props: {
            article: {
                type: Object,
                default: {
                    title:'',
                    content:'',
                }
            },
        },
        data() {
            return {
                myArticle: {},

            }
        },
        
    }
</script>

<style>

</style>