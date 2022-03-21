<template>
    <div class="work py-5" id="work">
        <h1 class=" text-center">My Work</h1>

        <div class="d-flex justify-content-around pt-5">
            <WorkCard name="Amazing E Book" 
            link="https://github.com/Xcaliburx/AmazingEBook" 
            image="work1.jpg"/>

            <WorkCard name="JH Furniture" 
            link="https://github.com/Xcaliburx/JHFurniture" 
            image="work2.jpg"/>
        </div>

        <div class="pt-5">
            <WorkCard name="MbWek Center" 
            link="https://github.com/Xcaliburx/MbWekCenter" 
            image="work3.jpg"/>
        </div>
    </div>
</template>

<style scoped>
    .work{
        background-color: #1d1f21;
    }

    h1, p{
        color: white;
    }
</style>

<script>
import WorkCard from '@/components/WorkCard.vue'

export default {
  components: {
    WorkCard
  }
}
</script>
