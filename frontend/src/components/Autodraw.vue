<template>


<div id="canvasContainer">
    <canvas id="canvas" width="700" height="400">
        This text is displayed if your browser does not support HTML5 Canvas.
    </canvas>
    <canvas id="canvas2" width="700" height="400">
        This text is displayed if your browser does not support HTML5 Canvas.
    </canvas>
    <canvas id="canvas3" width="700" height="400">
        This text is displayed if your browser does not support HTML5 Canvas.
    </canvas>



    <div id="buttons">
        <input type="button" id="clear" value="Clear">
        <input type="button" id="reset" value="Reset">
    </div>
</div>


</template>

<!--
<script type="text=/javascript" src='../script.js'></script>
-->

<script>

</script>



<style scoped>
canvas {
    border: 1px solid black;

}

#suggestions{
    width: 720px;
    margin:0 -5px;
}

#suggestions img{
    margin:4px 5px;
    width: 60px;
    height: 60px;


    border: 1px solid black;
}

#canvasContainer{
    width: 708px;
    height: 400px;
    position:relative;
    margin-bottom:5px;

}

#canvasContainer canvas{
    width: 100%;
    height: 100%;
    position: absolute;
    top:0;
    left:0;

}

#canvas{
    z-index: 99999;
}
#canvas2{
    z-index: -99999;
}

#buttons {
    position: absolute;
    right: -50px;
    width: 50px;
    margin-right: -5px;
}

#buttons input {
    float: left;
    width: 100%;
    margin: 0 0 2px 0;
    padding: 8px;
    font-size: 12px;
}


</style>