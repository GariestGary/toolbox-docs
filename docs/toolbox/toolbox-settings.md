From this window you can adjust main settings, edit initial pools, set up audios and edit properties in database.

'Toolbox Settings' window has four tabs:

- Main Settings
- Pooler
- Audio Player
- Database

Let's look all them.

##Main Settings

<img src="main_settings.png">

There you can edit following properties:

- `Resolve Scenes On Play`: Changes OnPlay behaviour. If enabled, then Toolbox will close all opened scenes and start all with `MAIN` scene (after stop playing, all scenes will be restored).
- `Time Scale`: An ordinary time scale, that affects all scripts, derived from `MonoCached`.
- `Target Frame Rate`: Default target frame rate option, which will be setted at startup.
- `Initial Scene Name`: The scene that will be loaded first after `MAIN` scene loaded.
- `Initial Scene Args`: Arguments for initial scene.
- `Manual Fade Out`: If enabled, then you can manually control when black screen will be faded out after initial scene loaded, otherwise Toolbox automatically fades it out right after initial scene loaded.
- `Fade Out Duration`: Simply controls fade out duration when `Manual Fade Out` disabled.

##Pooler

<img src="pooler_empty.png">

From this window you can edit initial pools list and adjust properties of each.

You can create new pool by clicking 'Add Pool' button.

<img src="pool_added.png">

Each pool has following settings:

- `Pool Tag`: The tag through which yo can retrieve pooled object.
- `Prefab`: Prefab which pool will instantiate objects.
- `Initial Pool Size`: Count of an objects tha will be added to the pool at start.

<img src="pool_filled.png">

To delete pool, simply click button with trash icon.

You can also search necessary pool by writing its tag in search field.

##Audio Player

<img src="audio_player_empty.png">

From this window you can edit audio albums list and adjust properties of each.

You can create new album by clicking 'Add Album' button.

<img src="album_added.png">

Each album has following settings:

- 