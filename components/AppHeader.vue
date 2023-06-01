<template>
    <div class="flex h-14 px-4 py-1">
        <div class="flex-none w-40 my-auto">
            <div class="flex">
                <button class="p-1 hover:bg-slate-200 rounded-full h-10 w-10 py-auto my-auto ">
                    <svg class="" height="24" viewBox="0 0 24 24" width="24" focusable="false" style="pointer-events: none; display: block; width: 100%; height: 100%;"><path d="M21 6H3V5h18v1zm0 5H3v1h18v-1zm0 6H3v1h18v-1z"></path></svg>
                </button>
                <div class="p-4">
                    <img
                    class="w-24"
                    src="~/assets/yt_logo_rgb_light.png"
                    />
                </div>
            </div>
        </div>
        <div class="grow my-auto">
            <div class="justify-center hidden sm:flex">  
                <form class="grow max-w-xl text-gray-500 flex">
                    <input class="shadow appearance-none border rounded-l-full border-gray-300 w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus::shadow-outline focus:border-blue-400" 
                    id="search" 
                    type="text" 
                    placeholder="Search" 
                    />
                    <button type="submit" class="shadow appearance-none border rounded-r-full flex-none border-gray-300">
                        <div class="py-2 px-5 bg-gray-200 hover:bg-gray-300 rounded-r-full">
                            <img
                                class="h-6"
                                src="~/assets/search.png"
                            />
                        </div>
                    </button>
                </form>
            </div>
        </div>
        <div class="flex-none w-40 my-auto">
            <div class="flex my-auto">
                <div class="flex-1 py-0 my-auto sm:hidden">
                    <img
                        class="h-6 mx-auto block"
                        src="~/assets/search.png"
                    />
                </div>
                <div class="flex-1 h-7">
                    <svg viewBox="0 0 24 24" preserveAspectRatio="xMidYMid meet" focusable="false" class="style-scope yt-icon" style="pointer-events: none; display: block; width: 100%; height: 100%;"><g class="style-scope yt-icon"><path d="M14,13h-3v3H9v-3H6v-2h3V8h2v3h3V13z M17,6H3v12h14v-6.39l4,1.83V8.56l-4,1.83V6 M18,5v3.83L22,7v8l-4-1.83V19H2V5H18L18,5 z" class="style-scope yt-icon"></path></g></svg>
                </div>
                <div class="flex-1 h-7">
                    <svg viewBox="0 0 24 24" preserveAspectRatio="xMidYMid meet" focusable="false" class="style-scope yt-icon" style="pointer-events: none; display: block; width: 100%; height: 100%;"><g class="style-scope yt-icon"><path d="M10,20h4c0,1.1-0.9,2-2,2S10,21.1,10,20z M20,17.35V19H4v-1.65l2-1.88v-5.15c0-2.92,1.56-5.22,4-5.98V3.96 c0-1.42,1.49-2.5,2.99-1.76C13.64,2.52,14,3.23,14,3.96l0,0.39c2.44,0.75,4,3.06,4,5.98v5.15L20,17.35z M19,17.77l-2-1.88v-5.47 c0-2.47-1.19-4.36-3.13-5.1c-1.26-0.53-2.64-0.5-3.84,0.03C8.15,6.11,7,7.99,7,10.42v5.47l-2,1.88V18h14V17.77z" class="style-scope yt-icon"></path></g></svg>
                </div>
                <div class="flex-1 h-7">
                    <img class="rounded-full h-7 mx-auto" src="https://yt3.ggpht.com/yti/AHyvSCDOPaafCFjUv5xbSkzTnnuxZ2HmTUYuRwpRrrSAaA=s88-c-k-c0x00ffffff-no-rj-mo" alt="">
                </div>
            </div>
        </div>
    </div>
</template>