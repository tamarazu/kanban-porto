<template>
  <div>
    <div class="jumbotron">
        <div class="text-center"><i class="fa fa-5x fa-frown-o" style="color:#d9534f;"></i></div>
        <h1 class="text-center">404 Not Found<p> </p><p><small class="text-center"> Oh noes everything broke</small></p></h1>
        <p class="text-center">Try pressing the back button or clicking on this button.</p>
        <p class="text-center"><a class="btn btn-primary" href="#"><i class="fa fa-home"></i> Take Me Home</a></p>
    </div>
</div>
</template>

<script>
export default {
  name: "ErrorTaskKanban",
  props: {
    err : Object    
  }
}
</script>

<style>

</style>