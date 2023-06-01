<template>
    <div>
        <AppHeader class="sticky top-0 z-50 bg-white" />
        <div class="flex flex-row h-screen">
            <SideNav class="sticky left-0 z-40 h-full max-h-screen overflow-y-auto hidden sm:hidden md:hidden lg:block w-64" />
            <MiniSideNav class="sticky left-0 z-40 h-full max-h-screen overflow-y-auto block sm:block md:block lg:hidden " />
            <slot class="w-5/6" />
        </div>
        <!-- <AppFooter /> -->
    </div>
</template>