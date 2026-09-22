<script setup>
import { RouterView } from 'vue-router';
import AppNavBar from "@/components/layout/AppNavbar.vue";
import AppSidebar from "@/components/layout/AppSidebar.vue";
</script>

<template>
    <AppNavBar/>

    <div class="container-fluid">
        <div class="row">
            <aside class="col-md-3"></aside>
        </div>

    </div>
</template>