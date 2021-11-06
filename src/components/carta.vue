<template>
    <div class="card">
        <div class="card-header">Crear tarea</div>
        <div class="card-body">
            <form id="task-form">
                <div class="form-group">
                    <input type="text" id="name" placeholder="Tarea" class="form-control">
                </div>
                <div class="form-group">
                    <textarea id="description" cols="30" rows="10"
                    class="form-control" placeholder="Descripción de la tarea"
                    ></textarea>
                </div>
                <div class="d-grid gap-2">
                    <button class="btn btn-primary" type="submit">Guardar</button>
                </div>
            </form>
        </div>
    </div>
</template>

<script>
export default {
    name: 'carta'
}
</script>