<template>
    <div>
        <a :href='link' target="_blank">
            <img :src='require(`@/assets/${image}`)' class="image" alt="">
        </a>

        <h3>{{ name }}</h3>
    </div>

</template>

<style scoped>
    h3{
        color: white;
    }

    .image{
        width: 500px;
        height: 300px;
    }
</style>

<script>
export default {
  props: ['link','image', 'name'],
}
</script>