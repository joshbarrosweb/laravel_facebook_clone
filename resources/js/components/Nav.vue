<template>
    <div class="bg-white h-12 p-4 flex items-center border-b border-gray-400 shadow-sm">
        <div class="w-1/3">
            <div class="flex">

                <div class="ml-2">
                    <input type="text" name="search" class="rounded-full pl-8 w-56 bg-gray-200 h-8 focus:outline-none focus:shadow-outline text-sm" placeholder="Search Facebook...">
                </div>
            </div>
        </div>
        <div class="w-1/3 flex justify-center items-center">
            <router-link to="/" class="px-6 border-b-2 border-blue-400 h-full flex items-center">TEST</router-link>
            <router-link to="/" class="px-6 border-b-2 border-blue-400 h-full flex items-center">TEST</router-link>
            <router-link to="/" class="px-6 border-b-2 border-blue-400 h-full flex items-center">TEST</router-link>
        </div>
        <div class="w-1/3">

        </div>
    </div>
</template>

<script>
export default {
    name: "Nav",
}
</script>

<style scoped>

</style>
