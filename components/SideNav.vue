<template>
    <div class=" space-y-4 mx-4 pr-4">
        <div class="flex bg-slate-200 hover:bg-slate-200 hover:cursor-pointer py-2 rounded-xl">
            <div class="mx-4 h-6">
                <svg viewBox="0 0 24 24" preserveAspectRatio="xMidYMid meet" focusable="false" style="pointer-events: none; width: 100%; height: 100%;"><g class="style-scope yt-icon"><path d="M4,10V21h6V15h4v6h6V10L12,3Z" class="style-scope yt-icon"></path></g></svg>
            </div>
            <div class="flex-none">
                <h1 class="inline-bloc font-semibold">Home</h1>
            </div>
        </div>
        <div class="flex hover:bg-slate-200 hover:cursor-pointer py-2 rounded-xl">
            <div class="mx-4 h-6">
                <svg viewBox="0 0 24 24" preserveAspectRatio="xMidYMid meet" focusable="false" class="style-scope yt-icon" style="pointer-events: none; display: block; width: 100%; height: 100%;"><g height="24" viewBox="0 0 24 24" width="24" class="style-scope yt-icon"><path d="M10 14.65v-5.3L15 12l-5 2.65zm7.77-4.33c-.77-.32-1.2-.5-1.2-.5L18 9.06c1.84-.96 2.53-3.23 1.56-5.06s-3.24-2.53-5.07-1.56L6 6.94c-1.29.68-2.07 2.04-2 3.49.07 1.42.93 2.67 2.22 3.25.03.01 1.2.5 1.2.5L6 14.93c-1.83.97-2.53 3.24-1.56 5.07.97 1.83 3.24 2.53 5.07 1.56l8.5-4.5c1.29-.68 2.06-2.04 1.99-3.49-.07-1.42-.94-2.68-2.23-3.25zm-.23 5.86l-8.5 4.5c-1.34.71-3.01.2-3.72-1.14-.71-1.34-.2-3.01 1.14-3.72l2.04-1.08v-1.21l-.69-.28-1.11-.46c-.99-.41-1.65-1.35-1.7-2.41-.05-1.06.52-2.06 1.46-2.56l8.5-4.5c1.34-.71 3.01-.2 3.72 1.14.71 1.34.2 3.01-1.14 3.72L15.5 9.26v1.21l1.8.74c.99.41 1.65 1.35 1.7 2.41.05 1.06-.52 2.06-1.46 2.56z" class="style-scope yt-icon"></path></g></svg>
            </div>
            <div>
                <h1 class="inline-bloc font-semibold">Shorts</h1>
            </div>
        </div>
        <div class="flex hover:bg-slate-200 hover:cursor-pointer py-2 rounded-xl">
            <div class="mx-4 h-6">
                <svg viewBox="0 0 24 24" preserveAspectRatio="xMidYMid meet" focusable="false" class="style-scope yt-icon" style="pointer-events: none; display: block; width: 100%; height: 100%;"><g class="style-scope yt-icon"><path d="M10,18v-6l5,3L10,18z M17,3H7v1h10V3z M20,6H4v1h16V6z M22,9H2v12h20V9z M3,10h18v10H3V10z" class="style-scope yt-icon"></path></g></svg>
            </div>
            <div>
                <h1 class="inline-bloc font-semibold">Subscriptions</h1>
            </div>
        </div>
        
        <div v-for="value in dummyArray" :key="value">
            <div class="flex hover:bg-slate-200 hover:cursor-pointer py-2 rounded-xl">
                <div class="mx-4 bg-slate-300 w-6 h-6 rounded-full"></div>
                <div class="bg-slate-300 w-28 h-4 my-auto"></div>
            </div>
        </div>


    </div>
</template>

<script>
    export default {
        computed: {
            dummyArray() {
                return Array.from({ length: 25 }, (_, index) => index);
            }
        }
    }
</script>