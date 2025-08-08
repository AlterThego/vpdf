<template>
    <div class="max-h-full max-w-full min-h-0 min-w-0 flex-auto transition-all md:ml-4">
        <div class="flex h-full items-center justify-center p-8">
            <div class="h-full animate-pulse flex items-center justify-center">
                <div class="flex flex-col items-center gap-4">
                    <div class="w-16 h-20 bg-[#808080] rounded"></div>
                    <div class="h-4 bg-[#808080] rounded w-24"></div>
                    <div class="h-3 bg-[#808080] rounded w-16"></div>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
@keyframes pulse {

    0%,
    100% {
        opacity: 1;
    }

    50% {
        opacity: 0.5;
    }
}

.animate-pulse {
    animation: pulse 2s cubic-bezier(0.4, 0, 0.6, 1) infinite;
}
</style>