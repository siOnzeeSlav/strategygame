#Strategy Game ![alt text][progress]

This project have a unknown name. I'm decided to make strategy multiplayer game. Firstly sorry for my wrong English. I'm from the Czech Republic. This strategy game happening at a time **UNKNOWN**. There is all allowed from Zero to Future.
The game will be maded in Unity3D PRO.

## Goal

The Strategy Game must have
* Multiplayer
* Big scale of units and builds
* Good interface (HUD -> UI)
* Textures what will looks great on 4K resolution


## Code Style

If you want contribute you must write in this style. If not and the contribute will be right. I remake it!


##### Fields

I don't recommend declare it in static style but in something as constructor.

```cs
  /* There Are Publics */
  public Field field;
  
  /* There Are Publics ReadOnly */
  private readonly Field rfield;
  
  /* There Are Privates */
  private Field _field;
  
  /* There Are Privates ReadOnly */
  private readonly Field r_field;
```

##### Methods

All methods start LowerCase then any next word first char is Upper.
Every method must have documentation. Everyone want know for what is this method.

```cs
/// <summary>Method what send message container to specific Player</summary> 
/// <param name="from">Player who sending message</param>
/// <param name="to">Player what receive message</param>
/// <param name="mc">Message</param>
public void sendMessage(Player from, Player to, MessageContainer mc) {

}
```

[progress]: http://progressed.io/bar/0 "Progress"
