<html>
    <head>
<title>NFL Playoff Bracket Challenge</title>
       <h1 align= "center"> NFL Playoff Bracket Challenge </h1>
	<p align= "center">You pick the winner from the week before to choose who you think will play that weekend.</p>
        <hr /><hr />
    </head>
    <body>
<div class = "AFC">
    <h1>Week 1 AFC</h1>
    <p>These teams are set to play:</p>
    <hr />
    <p>"Number 2 Seed (Division Winner)"</p>
    <p>PLAYS AGAINST</p>
    <p>"Wildcard 3"</p>
    <hr />
    <p> "Number 3 Seed (Division Winner)"</p>
    <p>PLAYS AGAINST</p>
    <p>"Wildcard 2"</p>
    <hr />
    <p> "Number 4 Seed (Division Winner)"</p>
    <p>PLAYS AGAINST</p>
       <p>"Wildcard 1"</p>
       <hr />
</div>

<div class = "NFC">
    <h1>Week 1 NFC</h1>
    <p>These teams are set to play:</p>
    <hr />
    <p>"Number 2 Seed (Division Winner)"</p>
    <p>PLAYS AGAINST</p>
    <p>"Wildcard 3"</p>
    <hr />
    <p> "Number 3 Seed (Division Winner)"</p>
    <p>PLAYS AGAINST</p>
    <p>"Wildcard 2"</p>
    <hr />
    <p> "Number 4 Seed (Division Winner)"</p>
    <p>PLAYS AGAINST</p>
       <p>"Wildcard 1"</p>
        <hr />
</div>
<div class="hr">
    <hr /><hr /><hr /><hr /><hr />
</div>
<form id="main" action="https://brokenfast.github.io/NFL-Playoff-Bracket-Challenge-Website-Project/bracketresults.php">
<div class = "AFC">
    <h1>Week 2 AFC</h1>
    <label>Choose a team:</label>
    <select id ="Week 2 AFC" type="text" list="AFC Teams a">
<datalist id="AFC Teams a">
	<option value="DEFAULT">----------------------------</option>
    <option value="Number 4 Seed">Number 4 Seed</option>
    <option value="Wildcard 1">Wildcard 1</option>
	</select>
</datalist>
    <p>PLAYS AGAINST</p>
<p>"Number 1 Seed (Division Winner)"</p>
    <hr />
    <label>Choose a team:</label>
    <select id ="Week 2 AFC" type="text" list="AFC Teams b">
<datalist id="AFC Teams b">
	<option value="DEFAULT">----------------------------</option>    
    <option value="Number 2 Seed">Number 2 Seed</option>
    <option value="Wildcard 3">Wildcard 3</option>
	</select>
</datalist>
    <p>PLAYS AGAINST</p>
    <label>Choose a team:</label>
    <select id ="Week 2 AFC" type="text" list="AFC Teams c">
<datalist id="AFC Teams c">
	<option value="DEFAULT">----------------------------</option>   
    <option value="Number 3 Seed">Number 3 Seed</option>
    <option value="Wildcard 2">Wildcard 2</option>
	</select>
</datalist>
    <hr /><hr />
</div>
<div class = "NFC">
    <h1>Week 2 NFC</h1>
    <label>Choose a team:</label>
    <select id ="Week 2 NFC" type="text" list="NFC Teams a">
<datalist id="NFC Teams a">
	<option value="DEFAULT">----------------------------</option>   
    <option value="Number 4 Seed">Number 4 Seed</option>
    <option value="Wildcard 1">Wildcard 1</option>
	</select>
</datalist>
    <p>PLAYS AGAINST</p>
<p>"Number 1 Seed (Division Winner)"</p>
    <hr />
    <label>Choose a team:</label>
    <select id ="Week 2 NFC" type="text" list="NFC Teams b">
<datalist id="NFC Teams b">
	<option value="DEFAULT">----------------------------</option>   
    <option value="Number 2 Seed">Number 2 Seed</option>
    <option value="Wildcard 3">Wildcard 3</option>
	</select>
</datalist>
    <p>PLAYS AGAINST</p>
    <label>Choose a team:</label>
    <select id ="Week 2 NFC" type="text" list="NFC Teams c">
<datalist id="NFC Teams c">
	<option value="DEFAULT">----------------------------</option>   
    <option value="Number 3 Seed">Number 3 Seed</option>
    <option value="Wildcard 2">Wildcard 2</option>
	</select>
</datalist>
    <hr /><hr />
</div>
<div class="hr">
    <hr /><hr /><hr /><hr /><hr />
</div>
<div class="AFCCW">
<h1 align="center">Championship Weekend</h1>
    <select id="Championship Weekend" type="text" list="AFC Championship Contenders">
<datalist id="AFC Championship Contenders">
	<option value="DEFAULT">----------------------------</option>   
    <option value="Lower Seed Winner">Lower Seed Winner</option>
    <option value="Higher Seed Winner">Higher Seed Winner</option>
	</select>
</datalist>
</div>
 PLAYS AGAINST 
<p class= "ChampWeek">
<div class="NFCCW">
    <select id="Championship Weekend" type="text" list="NFC Championship Contenders">
<datalist id="NFC Championship Contenders">
	<option value="DEFAULT">----------------------------</option>   
    <option value="Lower Seed Winner">Lower Seed Winner</option>
    <option value="Higher Seed Winner">Higher Seed Winner</option>
	</select>
</datalist>
</div>
</p>
    <hr />
<div class="hr">
    <hr /><hr /><hr /><hr /><hr />
</div> 
<div class="SBS" align="center">
    <h1>Super Bowl Sunday</h1>
    <select id="Super Bowl Sunday" type="text" list="Championship Teams">
<datalist id="Championship Teams">
	<option value="DEFAULT">----------------------------</option>   
    <option value="AFC Champions">AFC Champions</option>
    <option value="NFC Champions">NFC Champions</option>
	</select>
</datalist>
    <hr /><hr />
</div>
<div class="hr">
    <hr /><hr /><hr /><hr /><hr />
</div>
<div class="hr">
    <hr /><hr /><hr /><hr /><hr />
</div>
<div class="hr">
    <hr /><hr /><hr /><hr /><hr />
</div>
<div align="center">
<input type= "submit" value= "Submit"/>
</div>
</form>
    </body>
<style>
h1{
text-align:center;
}
body{
background-color:green;
text-align:center;
}
p.ChampWeek{
float:right;   
}   
div.AFC{
float:left;
width:191px;    
}
div.NFC{
float:right;
width:191px;
}
div.AFCCW{
float:left;
}
div.NFCCW{
float:right;
width:191px;
}
div.SBS{
}
</style>
</html>