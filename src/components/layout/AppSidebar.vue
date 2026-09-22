<script setup>
import { RouterLink } from 'vue-router';

</script>

<template>
    <nav>
        <div class="flex-column nav-pills gap-1">
            <RouterLink to="/pets">
                <i class="bi bi-plus-circle me-2">
                </i>"
                Novo Pet
            </RouterLink>

        </div>
    </nav>
</template>