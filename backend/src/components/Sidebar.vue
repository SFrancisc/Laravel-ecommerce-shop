<template>
    <div class="w-[200px] transition-all bg-indigo-700 py-4 px-2">
        <router-link :to="{name: 'app.dashboard'}" class="flex items-center p-2 rounded transition-colors hover:bg-black/30">
            <span class="mr-2 text-gray-300">
                <HomeIcon class="w-5"/>

            </span>
            <span class="text-sm text-gray-300">
                Dashboard
            </span>
        </router-link>

        <router-link :to="{name: 'app.products'}" class="flex items-center p-2 rounded transition-colors hover:bg-black/30">
            <span class="mr-2 text-gray-300">
                <ListBulletIcon class="w-5"/>

            </span>
            <span class="text-sm text-gray-300">
                Products
            </span>
        </router-link>

        <router-link :to="{name: 'app.dashboard'}" class="flex items-center p-2 rounded transition-colors hover:bg-black/30">
            <span class="mr-2 text-gray-300">
                <UsersIcon class="w-5"/>

            </span>
            <span class="text-sm text-gray-300">
                Users
            </span>
        </router-link>

        <router-link :to="{name: 'app.dashboard'}" class="flex items-center p-2 rounded transition-colors hover:bg-black/30">
            <span class="mr-2 text-gray-300">
                <ChartBarIcon class="w-5"/>

            </span>
            <span class="text-sm text-gray-300">
                Reports
            </span>
        </router-link>
    </div>
</template>

<script setup>
import {HomeIcon, UsersIcon, ListBulletIcon, ChartBarIcon} from '@heroicons/vue/24/outline'
</script>

<style scooped>

</style>
