<template>
    <div class="container p-4">
        <div class="row">
            <div class="col-md-5">
                <carta></carta>
            </div>
            <div class="col-md-7">
                <tabla></tabla>
            </div>
        </div>
    </div>
</template>

<script>
import carta from './carta.vue'
import tabla from './tabla.vue'
export default {
    name: 'cuerpo',
    components: {tabla, carta}
    
}

</script>