<script setup lang="ts"></script>
<template>
    <div class="flex flex-col items-center justify-center h-full w-full min-h-[200px] p-8">
        <div class="flex items-center justify-center w-16 h-16 mb-4">
            <svg xmlns="http://www.w3.org/2000/svg" width="48" height="48" viewBox="0 0 24 24" fill="currentColor"
                class="icon icon-tabler icons-tabler-filled icon-tabler-file-x text-rose-500">
                <path stroke="none" d="M0 0h24v24H0z" fill="none" />
                <path
                    d="M12 2l.117 .007a1 1 0 0 1 .876 .876l.007 .117v4l.005 .15a2 2 0 0 0 1.838 1.844l.157 .006h4l.117 .007a1 1 0 0 1 .876 .876l.007 .117v9a3 3 0 0 1 -2.824 2.995l-.176 .005h-10a3 3 0 0 1 -2.995 -2.824l-.005 -.176v-14a3 3 0 0 1 2.824 -2.995l.176 -.005h5zm-1.489 9.14a1 1 0 0 0 -1.301 1.473l.083 .094l1.292 1.293l-1.292 1.293l-.083 .094a1 1 0 0 0 1.403 1.403l.094 -.083l1.293 -1.292l1.293 1.292l.094 .083a1 1 0 0 0 1.403 -1.403l-.083 -.094l-1.292 -1.293l1.292 -1.293l.083 -.094a1 1 0 0 0 -1.403 -1.403l-.094 .083l-1.293 1.292l-1.293 -1.292l-.094 -.083l-.102 -.07z" />
                <path d="M19 7h-4l-.001 -4.001z" />
            </svg>
        </div>

        <h3 class="text-xl font-semibold text-[#808080] mb-2">
            Failed to Load PDF
        </h3>

        <p class="text-md text-[#808080] text-center mb-4 max-w-sm">
            The PDF document could not be loaded or displayed due to an error.
        </p>

        <p class="text-sm text-[#808080] mt-4">
            If the problem persists, please check your connection or contact support.
        </p>
    </div>
</template>