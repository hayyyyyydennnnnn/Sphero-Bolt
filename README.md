//Programmers: Hayden Coates.  Roman Cleary 
//Date: 5.26.2023
//Program: Competition
async function startProgram() {
	await scrollMatrixText('Start!', { r: 10, g: 255, b: 10 }, 20, true);
	await roll(0, 75, 2.05);
	setMainLed({ r: 0, g: 0, b: 90 });
	await roll(90, 80, 1.5);
    await Sound.Animal.play(true);
	await roll(180, 0, 0);
}

	