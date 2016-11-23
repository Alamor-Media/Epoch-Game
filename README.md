# Epoch-Game
An incremental game inspired by "a dark room", "Kittens", and "Trimps", and "Civilization".

//learning how to do this...

<!DOCTYPE html>
<html>
        <head>
        <meta charset="utf-8">
        <title>Epoch Game</title>
        <Style>
        body {background-color: grey;}
        
        #inventory {
            background: rgb(209, 201, 209);
            width: 20%;
            height: 75%;
            overflow-y: auto;
            margin: 0px 0px 0px 5px;
            border: 5px solid rgb(73, 77, 153);
            padding: 0px 5px 5px 5px;
            position: fixed;
            top: 100px;
            }
        .subtitle {
            font-family: fantasy;
            font-size: 34px;
            margin: 0px 0px 0px -1px;
        }
        h3 {
            font-family: sans-serif;
            font-size: 15px;
            margin: 5px 0px 0px 0px;
            }
        
        #Gathering {
            background: rgb(228, 227, 230);
            border: 5px solid rgb(73, 77, 153);
            width: 75%;
            height: 75%;
            overflow-y: auto;
            margin: 0px 0px 0px 0px;
            padding: 5px 5px 0px 5px;
            position: relative;
            top: 100px;
            left: 200px;
        }
        
        h4 {border: 1px solid;
            width: 100px;
        }
        
        Button {
            width: 100px;
            height: 25px;
            padding: 0px 0px 0px 0px;
            margin: 0px 0px 0px 0px;
            border: 3px solid;
            background: rgb(189, 182, 189);
            font-family: cursive;
        }
        
        .announcement {
            font-family: fantasy;
            font-size: 30px;
            position: absolute;
            top: -10px;
            left: 100px;
        }
        
        #tabsHeading {
            border: 2px solid rgb(73, 77, 153);
            height: 27px;
            width: 557px;
            position: absolute;
            top: 55px;
        }
        
        .tab {
            margin: 5px -0px 0px 0px;
            padding: 5px 5px 5px 5px;
            font-size: 15px;
            border: 1px solid;
        }
        
        .menu {
            position: fixed;
            top: -10px;
        }
        .technical {
            position: fixed;
            right: 35px;
        }
        
        .rewards {
            position: fixed;
            top: 5px;
        }
        </Style>
        <h1 class= "announcement">You are a Prehistoric Human</h1>
    </head>
    
    <body>
    
    <div id="tabsHeading">
        <h3><span class ="tab">Production</span><span class ="tab">Research</span><span class ="tab">Religion</span><span class ="tab">Warfare</span><span class ="tab">Society</span><span class ="tab">Civics</span><span class ="tab">Exploration</span><span class ="tab">Age</span></h3>
    </div>
    
    
    <div id="inventory">
    <h2><span class="subtitle">Inventory</span></h2>
    <h3><span class="invItem">Food=</span></h3>
    <h3><span class="invItem">Wood=</span></h3>
    <h3><span class="invItem">Flint=</span></h3>
    <h3><span class="invItem">Health=</span></h3>
    <h3><span class="invItem">Population=</span></h3>
    <h3><span class="invItem">Territory=</span></h3>
    
    </div>
 
    <div id="Gathering">
<h4><Button id="gatherFood" onClick="foodClick(1)">Gather Food</Button></h4>
<h4><Button id="gatherWood" onClick="woodClick(1)">Gather Wood</Button></h4>
<h4><Button id="gatherFlint" onClick="flintClick(1)">Gather Flint</Button></h4>

</div>

<h5 class= "menu technical">Options</h5>
<h5 class= "menu rewards">Achievements</h5>
<h5 class= "menu">Stats</h5>
    </body>
</html>

