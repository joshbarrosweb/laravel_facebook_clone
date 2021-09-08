<template>
    <div class="bg-white rounded shadow w-2/3 p-4">
        <div class="flex">
            <div>
                <div class="w-8">

                </div>
            </div>
            <div class="flex-1 mx-4">
                <input type="text" name="body" class="w-full pl-4 h-8 bg-gray-200 rounded-full focus:outline-none focus:shadow-outline text-sm" placeholder="Add a post">
            </div>
            <div>
                <button class="flex justify-content items-center rounded-full w-10 h-10">
                    Upload
                </button>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "NewPost"
}
</script>

<style scoped>

</style>
