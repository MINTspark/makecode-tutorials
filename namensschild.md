# micro:bit Namensschild

```blocks
input.onButtonPressed(Button.A, function () {
	
})
input.onSound(DetectedSound.Loud, function () {
	
})
input.onGesture(Gesture.Shake, function () {
	
})
input.onLogoEvent(TouchButtonEvent.Pressed, function () {
	
})
basic.showNumber(0)
basic.showLeds(`
    . . . . .
    . . . . .
    . . . . .
    . . . . .
    . . . . .
    `)
basic.showIcon(IconNames.Heart)
basic.showString("Hello!")
basic.clearScreen()
basic.pause(100)
music.play(music.stringPlayable("- - - - - - - - ", 120), music.PlaybackMode.UntilDone)
music._playDefaultBackground(music.builtInPlayableMelody(Melodies.Dadadadum), music.PlaybackMode.InBackground)
music.play(music.builtinPlayableSoundEffect(soundExpression.giggle), music.PlaybackMode.UntilDone)
music.play(music.tonePlayable(262, music.beat(BeatFraction.Whole)), music.PlaybackMode.UntilDone)

```

## Erstelle Dein eigenes digitales Namensschild mit dem micro:bit!
Verwende diese **"Input"** Ereignisse: Knopf A, Knopf B, Knopf A+B, schütteln **V2:** es its laut, Logo gedrückt  
Verwende diese **"Output"** Möglichkeiten: Zeige Text, Zeige Zahl, Zeige ein Bild (LEDs oder Symbol) **V2:** Spiele eine Melodie
### @hideDone true