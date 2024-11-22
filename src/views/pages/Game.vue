<script setup>
// import { maps } from '@/maps';
// import { game } from '@/game';

// onMounted(() => {
//     initializeGame('game');
// });
</script>

<template>

    <div id="game-container">
        <canvas id="game"></canvas>
        <div class="btn">
            <Button id="up" label="Arriba" rounded class="!text-xl mt-8 !px-4"></Button>
            <Button id="left" label="Izquierda" rounded class="!text-xl mt-8 !px-4"></Button>
            <Button id="right" label="Derecha" rounded class="!text-xl mt-8 !px-4"></Button>
            <Button id="down" label="Abajo" rounded class="!text-xl mt-8 !px-4"></Button>
        </div>
    </div>

    <div>
        <!-- pendiente -->
        <p>parrafo</p>
    </div>

</template>
