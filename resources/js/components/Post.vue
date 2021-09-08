<template>
    <div class="bg-white rounded shadow w-2/3 mt-6 overflow-hidden">
        <div class="flex flex-col p-4">
            <div class="flex items-center">
                <div class="w-8">

                </div>
                <div class="ml-6">
                    <div class="text-sm font-bold">Josue Barros</div>
                    <div class="text-sm text-gray-600">12 minutes</div>
                </div>
            </div>
            <div>
                <div class="mt-4">
                    <p>Lorem Ipsum Dolor Amet...</p>
                </div>
            </div>
        </div>

        <div class="w-full">
            <img src="https://images.unsplash.com/photo-1514888286974-6c03e2ca1dba?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1027&q=80" alt="post image" class="w-full">
        </div>

        <div class="px-4 pt-2 flex justify-between text-gray-700 text-sm">
            <div>
                <p>George Washington and 969 others liked</p>
            </div>

            <div>
                <p>123 comments</p>
            </div>
        </div>

        <div class="flex justify-between border-1 border-gray-400 m-4">
            <button>Like</button>
            <button>Comment</button>
        </div>

    </div>
</template>

<script>
    export default {
        name: "Post"
    }
</script>


<style scoped>

</style>
