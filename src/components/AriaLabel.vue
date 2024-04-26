<template>
<div class="card container">
    <h2>Providing group label with Aria</h2>
    <p class="visuallyhidden">WAI-ARIA not fully supported in all web browser and screen reader combinations</p>
    <div role="group" aria-labelledby="shipping_head">
        <div role="application">
            <div id="shipping_head">Select Color:</div>
            <div>
                <input type="radio" name="format1" id="txt1" value="txt" checked>
                <label for="txt1">White</label>
            </div>
            <div>
                <input type="radio" name="format1" id="csv1" value="csv">
                <label for="csv1">Pink</label>
        </div>
    </div>
</div>
</div>
</template>
<script>
export default {

}
</script>
<style scoped>
.visuallyhidden {
    position:absolute;
    left:-10000px;
    top:auto;
    width:1px;
    height:1px;
    overflow:hidden;
}
.card {
  box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
  transition: 0.3s;
  width: 40%;
}

.card:hover {
  box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
}

.container {
  padding: 5px 16px;
}
</style>