<template>
    <div class="col-sm-6 col-md-4 col-lg-3">
        <div class="panel panel-default"></div>
        <div class="panel-body quote">
            <slot></slot>
        </div>

    </div>
</template>

<script>
</script>

<style scoped>
    .panel-body {
        font-family: 'Indie Flower', cursive;
        font-size: 24px;
        color: gray;
    }

    .panel {
        border-color: grey;
        margin: 0px;

    }

   .quote {
       cursor: pointer;
   }

   .quote:hover {
       background-color: blanchedalmond ;
   }
</style>