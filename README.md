//# myFirstScript
//This is actually my first code that i have written so please if you read my code please be constructive in your criticism. Thank you.
echo "# myFirstScript" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/Dante-Evans/myFirstScript.git
git push -u origin master

// Hopefully this will be a character sheet that I made.
// Hopefully this turns out halfway decent.
// The next nine lines should be player stats that can be changed throughout the game.
var str = "";  
var end = "";
var per = "";
var agi = "";
var inte = "";    //intelligence
var wis = "";
var luck = "";
var wpnDam = "";
var armRat = "";
var equPri = "";    //equip primary hand
var equArm = "";
var equOff = "";    //equip off hand
var equHed = "";
var equNec = "";
var equLftEar = "";    //equip left ear
var equRghEar = "";    //equip left ear
var equLegs = "";
var equBoots = "";
var equLftFing = "";    //equip left finger
var equRghFing = "";    //equip right finger


// The next function should give the player their hitPoints.

function hitPoints(agi , end) {
	console.log(agi + end);
	if (hitPoints !== 0) {
		return (hitPoints);
	} else if (hitPoints === 0) {
	return "You have Died.";
	}
}

// This next function should give the player their manaPoints.

function manaPoints(inte , wis) {
	console.log(inte + wis);
	if (manaPoints !== 0) {
		return (manaPoints);
	} else if (manaPoints === 0) {
	return "I need to rest and recharge.";
	}
}

// This next function should give the player the amount of damage they do.

function damage(str , agi) {
	console.log(str + agi + wpnDam);
	if (damage <= armRat) {
		return (armRat - damage);
	} else if (armRat <= damage) {
		return (damage - armRat);
	}
}

// The next few functions should be character races.
// However I haven't actually haven't come up with the details as of yet.
