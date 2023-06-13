<template>
    <div class="container-malla bg-dark m-0 d-flex">
        <div class="p-5 w-100">
            <div class="table">
                <div class="bg-white w-100 content-years">
                    <h3 class="h3-year">Año 1</h3>
                    <h3 class="h3-year">Año 2</h3>
                    <h3 class="h3-year">Año 3</h3>
                    <h3 class="h3-year">Año 4</h3>
                    <h3 class="h3-year">Año 5</h3>
                    <h3 class="h3-year">Año 6</h3>
                </div>
                <div class="modulos-semestre">
                    <div>
                        Semestre 1
                    </div>
                    <div v-for="items in items"></div>
                </div>
            </div>
            
        </div>
    </div>
</template>

<script>
import {malla_computacion} from './data/Mallas.js';
</script>

<style>
.container-malla{
    padding-left: 4rem;
    padding-right: 4rem;
    padding-top: 1rem;
    padding-bottom: 1rem;
}
.content-years{
    display: flex;
    justify-content: space-evenly;
}
.h3-year{
    text-align: center;
}
</style>