<template>
    <h1>Велосипедизам.мк - Вашиот велосипедски партнер</h1>
    <p>Бидете во тек со сите настани, трендови, огласи и се поврзано со велосипедизмот во Македонија!</p>
    <div class="grid grid-cols-1 sm:grid-cols-2 xl:grid-cols-3 xxl:grid-cols-4 gap-4 xxl:gap-8">
        <div v-for="i in 12" class="border-2 border-black p-5 rounded-lg">
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consequatur ea necessitatibus porro, possimus
                quidem sit?</p>
        </div>
    </div>
</template>

<script>
export default {
    name: "index"
}
</script>

<style scoped>

</style>