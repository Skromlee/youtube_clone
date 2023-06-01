<template>
    <div class="max-h-screen overflow-y-auto">
        <div class="flex flex-row space-x-4 my-4 mb-6 overflow-x-auto max-w-7xl mx-auto pb-4">
            <span class="bg-slate-200 px-2 rounded-md" v-for="category in categoryArr" :key="category">{{ category }}</span>
        </div>
        <div class="grid sm:grid-cols-1 md:grid-cols-2 lg:grid-cols-3 2xl:grid-cols-4 gap-4 justify-center px-4">
            <Card>
                <div class="max-w-sm m-auto">
                    <div class="relative">
                        <img
                        class="w-full rounded-xl"
                        src="https://i.ytimg.com/vi/x-sBN7bSexw/hq720.jpg?sqp=-oaymwEcCNAFEJQDSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLBStAVtNalieWL9wKvlGUzy5TynJA"
                        alt="Sunset in the mountains"
                        />
                        <span class="absolute bg-slate-800 text-white text-xs px-1 rounded-md bottom-2 right-2">3:57</span>
                    </div>
                    <div class="mt-2">
                        <div class="flex items-start">
                                <img
                                class="w-9 rounded-full"
                                src="https://yt3.ggpht.com/1UF91Z0ezdx6jtYuaDSiisarXkjjkaXcHXjyMGVPEO2oGpjA660kZDErB6KO1GpIrruv48XrhQ=s88-c-k-c0x00ffffff-no-rj"
                                
                                />
                            <div class="ml-3">
                                <h1 class="line-clamp-2">รักแรก - NONT TANONT | ส้ม มารี (Zom Marie) [COVER] | Ost.รักแรกโคตรลืมยาก</h1>
                                <p class="text-xs font-semibold text-gray-500 mt-2">ZOMMARIE MUSIC</p>
                                <p class="text-xs font-semibold text-gray-500 mt-1">150K views 1 day ago</p>
                            </div>
                        </div>
                    </div>
                </div>
            </Card>
            <Card>
                <div class="max-w-sm m-auto">
                    <div class="relative">
                        <img
                        class="w-full rounded-xl"
                        src="https://i.ytimg.com/vi/3s6EZBrM5uQ/hq720_live.jpg?sqp=CPC44KMG-oaymwEcCNAFEJQDSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLDpOJTSD0wIQMiqau2T5s1gdY9i9A"
                        alt="Sunset in the mountains"
                        />
                        <span class="absolute bg-slate-800 text-white text-xs px-1 rounded-md bottom-2 right-2">3:57</span>
                    </div>
                    <div class="mt-2">
                        <div class="flex items-start">
                                <img
                                class="w-9 rounded-full"
                                src="https://yt3.ggpht.com/jCetADktKYN-Q-QCbeoW4VmOKMIKVFB-NOmAbrfWTICSWC8DfbVkDS9lCFYeK1ZCinD5ZRJJZA=s68-c-k-c0x00ffffff-no-rj"
                                
                                />
                            <div class="ml-3">
                                <h1 class="line-clamp-2">🔴 โรมโต้วิษณุ หลังแย้มอาจเลือกตั้งซ่อมใหม่ | เที่ยงทันข่าว | 1 มิ.ย. 66</h1>
                                <p class="text-xs font-semibold text-gray-500 mt-2">PPTV HD 36</p>
                                <p class="text-xs font-semibold text-gray-500 mt-1">1.6K watching</p>
                                <span class="text-xs font-semibold text-white mt-1 bg-red-700 px-2">(( )) LIVE</span>
                            </div>
                        </div>
                    </div>
                </div>
            </Card>
            <Card>
                <div class="max-w-sm m-auto">
                    <div class="relative">
                        <img
                        class="w-full rounded-xl"
                        src="https://i.ytimg.com/vi/rfyyqTKm_W8/hq720.jpg?sqp=-oaymwEcCNAFEJQDSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLCg0f2WWWnfu6AK-zBGS-t_hSiu6g"
                        alt="Sunset in the mountains"
                        />
                        <span class="absolute bg-slate-800 text-white text-xs px-1 rounded-md bottom-2 right-2">3:57</span>
                    </div>
                    <div class="mt-2">
                        <div class="flex items-start">
                                <img
                                class="w-9 rounded-full"
                                src="https://yt3.ggpht.com/ytc/AGIKgqPHlQ-X2roxOaGO1TMyv2-Cz1sQZzVcZHFGKtCvxQ=s68-c-k-c0x00ffffff-no-rj"
                                
                                />
                            <div class="ml-3">
                                <h1 class="line-clamp-2">$1 million !? Amazing Giant bluefin tuna cutting Master, Luxurious Sashimi / 驚人的！巨大黑鮪魚切割技巧, 香煎黑鮪魚大腹</h1>
                                <p class="text-xs font-semibold text-gray-500 mt-2">Cate Food Travel 凱特食旅</p>
                                <p class="text-xs font-semibold text-gray-500 mt-1">3.9M views 3 weeks ago</p>
                            </div>
                        </div>
                    </div>
                </div>
            </Card>
            <Card>
                <div class="max-w-sm m-auto">
                    <div class="relative">
                        <img
                        class="w-full rounded-xl"
                        src="https://i.ytimg.com/vi/2IVOBqLyHtY/hq720.jpg?sqp=-oaymwEcCNAFEJQDSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLArqSsNggq2o1Mwg0O_TsFsLCBcLA"
                        alt="Sunset in the mountains"
                        />
                        <span class="absolute bg-slate-800 text-white text-xs px-1 rounded-md bottom-2 right-2">3:57</span>
                    </div>
                    <div class="mt-2">
                        <div class="flex items-start">
                                <img
                                class="w-9 rounded-full"
                                src="https://yt3.ggpht.com/fVM9Z0F0XwLMUceWrEAQk2ZzMk-NYTqHmx6Zb-C5IWyiSFKbSiXTTPVghzMFUyY9ppsNKw2f=s68-c-k-c0x00ffffff-no-rj"
                                
                                />
                            <div class="ml-3">
                                <h1 class="line-clamp-2">process of making Damascus knife. Korea's top handmade knife master.</h1>
                                <p class="text-xs font-semibold text-gray-500 mt-2">프로세스 케이 Process K</p>
                                <p class="text-xs font-semibold text-gray-500 mt-1">7.4M views 6 months ago</p>
                            </div>
                        </div>
                    </div>
                </div>
            </Card>
            <Card>
                <div class="max-w-sm m-auto">
                    <div class="relative">
                        <img
                        class="w-full rounded-xl"
                        src="https://i.ytimg.com/vi/4fezP875xOQ/hq720.jpg?sqp=-oaymwEcCNAFEJQDSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLA6DxTQcHwWbrPrLktaiIWvD3u6yQ"
                        alt="Sunset in the mountains"
                        />
                        <span class="absolute bg-slate-800 text-white text-xs px-1 rounded-md bottom-2 right-2">3:57</span>
                    </div>
                    <div class="mt-2">
                        <div class="flex items-start">
                                <img
                                class="w-9 rounded-full"
                                src="https://yt3.ggpht.com/ytc/AGIKgqPVx4t04xOyWwX5pD3AIOIbG64iDAE4zmzj1zb7Aw=s68-c-k-c0x00ffffff-no-rj"
                                
                                />
                            <div class="ml-3">
                                <h1 class="line-clamp-2">4 Hours Chopin for Studying, Concentration & Relaxation</h1>
                                <p class="text-xs font-semibold text-gray-500 mt-2">HALIDONMUSIC</p>
                                <p class="text-xs font-semibold text-gray-500 mt-1">12M views 1 year ago</p>
                            </div>
                        </div>
                    </div>
                </div>
            </Card>
            <Card>
                <div class="max-w-sm m-auto">
                    <div class="relative">
                        <img
                        class="w-full rounded-xl"
                        src="https://i.ytimg.com/vi/D5AsoC2qUOw/hq720.jpg?sqp=-oaymwEcCNAFEJQDSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLBPvaqooM8Aev9YXC3HmPz0CGFJXw"
                        alt="Sunset in the mountains"
                        />
                        <span class="absolute bg-slate-800 text-white text-xs px-1 rounded-md bottom-2 right-2">3:57</span>
                    </div>
                    <div class="mt-2">
                        <div class="flex items-start">
                                <img
                                class="w-9 rounded-full"
                                src="https://yt3.ggpht.com/1UF91Z0ezdx6jtYuaDSiisarXkjjkaXcHXjyMGVPEO2oGpjA660kZDErB6KO1GpIrruv48XrhQ=s88-c-k-c0x00ffffff-no-rj"
                                
                                />
                            <div class="ml-3">
                                <h1 class="line-clamp-2">June 6, 1944, D-Day, Operation Overlord | Colorized WW2</h1>
                                <p class="text-xs font-semibold text-gray-500 mt-2">imineo Documentaires</p>
                                <p class="text-xs font-semibold text-gray-500 mt-1">16M views 11 months ago</p>
                            </div>
                        </div>
                    </div>
                </div>
            </Card>

            <Card v-for="value in dummyArray" :key="value">
                <div class="max-w-sm m-auto">
                    <div class="relative">
                        <img
                        class="w-full rounded-xl"
                        src="https://i.ytimg.com/vi/D5AsoC2qUOw/hq720.jpg?sqp=-oaymwEcCNAFEJQDSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLBPvaqooM8Aev9YXC3HmPz0CGFJXw"
                        alt="Sunset in the mountains"
                        />
                        <span class="absolute bg-slate-800 text-white text-xs px-1 rounded-md bottom-2 right-2">3:57</span>
                    </div>
                    <div class="mt-2">
                        <div class="flex items-start">
                                <img
                                class="w-9 rounded-full"
                                src="https://yt3.ggpht.com/1UF91Z0ezdx6jtYuaDSiisarXkjjkaXcHXjyMGVPEO2oGpjA660kZDErB6KO1GpIrruv48XrhQ=s88-c-k-c0x00ffffff-no-rj"
                                
                                />
                            <div class="ml-3">
                                <h1 class="line-clamp-2">June 6, 1944, D-Day, Operation Overlord | Colorized WW2</h1>
                                <p class="text-xs font-semibold text-gray-500 mt-2">imineo Documentaires</p>
                                <p class="text-xs font-semibold text-gray-500 mt-1">16M views 11 months ago</p>
                            </div>
                        </div>
                    </div>
                </div>
            </Card>

            
            
        </div>
    </div>
</template>


<script>
    
    export default {
        computed: {
            dummyArray() {
                return Array.from({ length: 25 }, (_, index) => index);
            }
        },
        data() {
            return {
                categoryArr: [
                    "All", "Live", "Gaming", "Music", "News", "Mixes", "fi", 
                    "Apple", "Playlists", "drives", "Science", "Ghosts", "Computers", 
                    "analysis", "MOBA", "Statistics", "games", "Anime", "uploaded", 
                    "Watched", "you"
            ]
            };
        }
    };
</script>