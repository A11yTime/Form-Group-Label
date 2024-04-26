<template>
    <div class="card container">
        <h1>Providing group lable with native html</h1> 
        <fieldset>
        <legend>Select Color: </legend>
        <div role="application">
            <div>
                <input type="radio" name="format" id="txt" value="txt" checked>
                <label for="txt">White</label>
            </div>
            <div>
                <input type="radio" name="format" id="csv" value="csv">
                <label for="csv">Pink</label>
            </div>
        </div>
        </fieldset>
    </div>

</template>
<script>
export default {

}
</script>
<style scoped>
fieldset {
    border: 0;
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