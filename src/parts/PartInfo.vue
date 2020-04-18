<template>
    <div>
        <h1>{{part.title}}</h1>
        <div>
            {{part.description}}
        </div>
    </div>
</template>

<script>
    export default {
        name: "PartInfo",
        data(){
            return{
                part: {
                    title:'Pasdsd',
                    description:'a'
                },
            };

        },
    }
</script>

<style scoped>

</style>