<!DOCTYPE html>
<html lang="fr">
	<head>
		<meta charset="utf-8">

		<!-- Always force latest IE rendering engine (even in intranet) & Chrome Frame
		Remove this if you use the .htaccess -->
		<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
         <link href="/CSS/design.css" rel="stylesheet" >
         <link rel="stylesheet" href="animate.css">
		<title>Machine à sous</title>
		<meta name="description" content="">
        
		<meta name="viewport" content="width=device-width; initial-scale=1.0">

		<script src="script.js"></script>
	</head>

	<body>
	<div  id="Machine" align="center">
		<img src="logo_casino.png" alt="">

		
    <div id="zone_image">
		<img id="img_sous_1" src="img_0.png" style="with:20px ;height:50px" />
		<img id="img_sous_2" src="img_1.png" style="with:20px ;height:50px"/>
		<img id="img_sous_3" src="img_2.png" style="with:20px ;height:50px"/>
		<img id="img_sous_4" src="img_3.png" style="with:20px ;height:50px" />
    </div>
		
		<button class="exercice" onclick="machineASous();" id="spin">GO !</button><br />
		
		<p>Votre crédit est de </p><input id="credit" type="text" value="20" disabled="disabled"><br /><p>Votre meilleur score est de :</p><input id="highscore" type="text" value="20" disabled="disabled">
		
		
     </div>   
     <br><br><br>
	<div class="footer"></div>
	</body>
</html>
