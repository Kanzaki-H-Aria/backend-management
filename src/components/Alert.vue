<template>
    <div id="alert">
        <div class="alert alert-success alert-dismissible" role="alert">
            <button type="button" class="close" data-dismiss="alert" aria-label="Close"><span aria-hidden="true">&times;</span></button>
            {{mes}}
        </div>
    </div>
</template>
<script>
export default {
    name:'alert',
    props:["mes"]
};
</script>
