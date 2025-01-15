### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Compose the music

## Step 1
The song is still missing something. Let's add a medium tempo ``||hoc:drum||`` beat.

#### ~ tutorialhint
Add a medium tempo drum beat by adding the ``||hoc:drum||`` block to the top of the code.

```ghost
    hoc._add_instrument_activity()
    hoc.note()
    hoc.drums()
```
```template
    hoc._add_instrument_activity(Instrument_Activity.Xylophone)
    hoc._add_instrument_activity(Instrument_Activity.Guitar)
    hoc.note(Note.La)
    hoc.note(Note.Re)
    hoc.note(Note.So)
    hoc.note(Note.Do)
```

```package
hoc2024-ts=github:fc-minecraft/hoc2024-ts/n/music
```