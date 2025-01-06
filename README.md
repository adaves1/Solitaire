Solitaire
=====================

This is a bite-size Solitaire game for Windows 10.

![Screenshot](/doc/screenshots/solitaire_2.png?raw=true)


Building and deploying
-------------------------------------------------------------------------------

1. Install Microsoft Visual Studio.
2. Open the SLN file: File > Open Project, select the file `Solitaire.sln`.
3. Select the target, either emulator or device.
4. Press F5 to build the project and run it on the selected target.


Important files and classes
-------------------------------------------------------------------------------

* `Game1.cs`: Main game class derived from Microsoft.Xna.Framework.Game. In this 
  class the game content is loaded, game update requests are received, and the 
  drawing is handled.
* `Card.cs`: A single Solitaire card.
* `Deck.cs`, `SourceDeck.cs`, and `TargetDeck.cs`: The decks of cards.


Version history
-------------------------------------------------------------------------------

* Version Initial: The first version and the initial version.
