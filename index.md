<html>
    <head>
<title>NFL Playoff Bracket Challenge</title>
       <h1> NFL Playoff Bracket Challenge </h1>
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

<div class = "AFC">
    <h1>Week 2 AFC</h1>
    <label>Choose a team:</label>
    <input id ="Week 2 AFC" type="text" list="AFC Teams a"/>
<datalist id="AFC Teams a">
    <option value="Number 4 Seed">
    <option value="Wildcard 1">
</datalist>
    <p>PLAYS AGAINST</p>
    <p>"Number 1 Seed (Division Winner)"</p>
    <hr />
    <label>Choose a team:</label>
    <input id ="Week 2 AFC" type="text" list="AFC Teams b"/>
<datalist id="AFC Teams b">
    <option value="Number 2 Seed">
    <option value="Wildcard 3">
</datalist>
    <p>PLAYS AGAINST</p>
    <label>Choose a team:</label>
    <input id ="Week 2 AFC" type="text" list="AFC Teams c"/>
<datalist id="AFC Teams c">
    <option value="Number 3 Seed">
    <option value="Wildcard 2">
</datalist>
    <hr />
</div>

<div class = "NFC">
       <h1>Week 2 NFC</h1>
    <label>Choose a team:</label>
    <input id ="Week 2 NFC" type="text" list="NFC Teams a"/>
<datalist id="NFC Teams a">
    <option value="Number 4 Seed">
    <option value="Wildcard 1"> 
</datalist>
    <p>PLAYS AGAINST</p>
    <p>"Number 1 Seed (Division Winner)"</p>
    <hr />
    <label>Choose a team:</label>
    <input id ="Week 2 NFC" type="text" list="NFC Teams b"/>
<datalist id="NFC Teams b">
    <option value="Number 2 Seed">
    <option value="Wildcard 3">
</datalist>
    <p>PLAYS AGAINST</p>
    <label>Choose a team:</label>
    <input id ="Week 2 NFC" type="text" list="NFC Teams c"/>
<datalist id="NFC Teams c">
    <option value="Number 3 Seed">
    <option value="Wildcard 2">
</datalist>
    <hr />
</div>

 
<h1>Championship Weekend</h1>

<p class= "ChampWeek">
<div class="AFCCW">
    <input id="Championship Weekend" type="text" list="AFC Championship Contenders"/>
<datalist id="AFC Championship Contenders">
    <option value="Lower Seed Winner">
    <option value="Higher Seed Winner">
</datalist>
</div>

 PLAYS AGAINST
 
<div class="NFCCW">
    <input id="Championship Weekend" type="text" list="NFC Championship Contenders"/>
<datalist id="NFC Championship Contenders">
    <option value="Lower Seed Winner">
    <option value="Higher Seed Winner">
</datalist>
</div>
    <hr />
</p>
<div class="hr">
    <hr /><hr /><hr /><hr /><hr />
</div>
    
<div class="SBS">
    <h1>Super Bowl Sunday</h1>
    <input id="Super Bowl Sunday" type="text" list="Championship Teams"/>
<datalist id="Championship Teams">
    <option value="AFC Champions">
    <option value="NFC Champions">
</datalist>
    <hr /><hr />

</div>

    </body>

<style>
h1{
text_align:middle;
}


body{

}



p.ChampWeek{
float:right;
    
}
div.AFC{
float:left;
width:200px    
}

div.AFCCW{
float: left;
width:200px
}

div.NFCCW{
float:right;
width:200px
}

div.NFC{
float:right;
width:200px
}

div.SBS{
width:200px
}
</style>
</html>