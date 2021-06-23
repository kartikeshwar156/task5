<!DOCTYPE html>
<html>
  <head>
    <link href="styles/grid55.css" rel="stylesheet">
    <link href="styles/stop-watch.css" rel="stylesheet">  
    <meta charset="utf-8">
    <title>My test page</title>
  </head>
  <body>
   
    <h1 class="heading1"> The Grid Game </h1>

    <div class="photo"><img  src="images/grid33-final.PNG" rel="stylesheet"></div>
    
    <div class="Myresultfinal"><p class="caption" id="Myresult"><strong>Convert the grid in the given image</strong></p></div>
    


    <div id="table" class="Table" style="display: table;">
        <div id="row1" style="display: table-row;">
           <div id="cell11" class="tile1" style="display: table-cell;" onClick="clickTile(1,1);"></div>
           <div id="cell12" class="tile2" style="display: table-cell;" onClick="clickTile(1,2);"></div>
           <div id="cell13" class="tile3" style="display: table-cell;" onClick="clickTile(1,3);"></div>
           <div id="cell14" class="tile4" style="display: table-cell;" onClick="clickTile(1,4);"></div>
           <div id="cell15" class="tile5" style="display: table-cell;" onClick="clickTile(1,5);"></div>
        </div>
        <div id="row2" style="display: table-row;">
           <div id="cell21" class="tile6" style="display: table-cell;" onClick="clickTile(2,1);"></div>
           <div id="cell22" class="tile7" style="display: table-cell;" onClick="clickTile(2,2);"></div>
           <div id="cell23" class="tile8" style="display: table-cell;" onClick="clickTile(2,3);"></div>
           <div id="cell24" class="tile9" style="display: table-cell;" onClick="clickTile(2,4);"></div>
           <div id="cell25" class="tile10" style="display: table-cell;" onClick="clickTile(2,5);"></div>
        </div>
        <div id="row3" style="display: table-row;">
           <div id="cell31" class="tile11" style="display: table-cell;" onClick="clickTile(3,1);"></div>
           <div id="cell32" class="tile12" style="display: table-cell;" onClick="clickTile(3,2);"></div>
           <div id="cell33" class="tile13" style="display: table-cell;" onClick="clickTile(3,3);"></div>
           <div id="cell34" class="tile14" style="display: table-cell;" onClick="clickTile(3,4);"></div>
           <div id="cell35" class="tile15" style="display: table-cell;" onClick="clickTile(3,5);"></div>
        </div>
        <div id="row4" style="display: table-row;">
            <div id="cell41" class="tile16" style="display: table-cell;" onClick="clickTile(4,1);"></div>
            <div id="cell42" class="tile17" style="display: table-cell;" onClick="clickTile(4,2);"></div>
            <div id="cell43" class="tile18" style="display: table-cell;" onClick="clickTile(4,3);"></div>
            <div id="cell44" class="tile19" style="display: table-cell;" onClick="clickTile(4,4);"></div>
            <div id="cell45" class="tile20" style="display: table-cell;" onClick="clickTile(4,5);"></div>
         </div>
         <div id="row3" style="display: table-row;">
            <div id="cell51" class="tile21" style="display: table-cell;" onClick="clickTile(5,1);"></div>
            <div id="cell52" class="tile22" style="display: table-cell;" onClick="clickTile(5,2);"></div>
            <div id="cell53" class="tile23" style="display: table-cell;" onClick="clickTile(5,3);"></div>
            <div id="cell54" class="tile24" style="display: table-cell;" onClick="clickTile(5,4);"></div>
            <div id="cell55" class="tile25" style="display: table-cell;" onClick="clickTile(5,5);"></div>
         </div>
     </div>
    <button class="buttondesign" onClick="location.reload()">New Game</button>
    
    

    <aside>
        <div class="stopwatch">
            <h1 class="head">STOPWATCH</h1>
            <div class="circles">
            <span class="time" id="display" >00:00:00:000</span>
            </div>
          </div>
    </aside>
   <div id="Audio">
   <audio controls loop autoplay>
      <source src="sound/mappy-land-tune.mp3" type="audio/mp3">
   </audio>
   </div> 
    
    <script src="scripts/function-shuffle-tiles55.js"></script>
    <script src="scripts/grid-55-practical.js"></script>
    <script src="scripts/stop-watch-practical.js"></script>
    
    
    

  </body>
</html> 
