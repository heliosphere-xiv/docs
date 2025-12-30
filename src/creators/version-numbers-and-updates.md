# Version numbers and updates

## Version numbers

Heliosphere expects you to version your mods using something called
[Semantic Versioning][semver]. In practice, this just means that your mods will
always show up with version numbers like x.y.z (e.g. 1.2.3, 2.0.0).

**Importantly**, you do not set the version while uploading your mod. You set it
while creating it, either in Penumbra or TexTools. Heliosphere just reads the
version number out of your mod.

> Heliosphere is lenient with your uploads, so if you set the version of your
mod pack to 1 or 2.0 or even 1.0.0.0, Heliosphere will probably be able to
convert it into an equivalent compatible version number.

There are three important things to take away from this:
- you can't upload the same version number inside the same variant twice
- new versions should have a higher version number than old versions
- you probably don't need to change how you're doing things

Essentially, if you're uploading an update, make sure that you've incremented
either the x, y, or z in x.y.z.

Some versioning advice you don't have to follow is that:
- bug fixes should change the z in x.y.z (1.2.3 → 1.2.4)
- new options should change the y in x.y.z (1.2.3 → 1.3.0)
- big overhauls/reworks/redesigns should change the x in x.y.z (1.2.3 → 2.0.0)

## Updates

The reason all of this is important is that updates need a higher version number
to be recognised by Heliosphere. Importantly, this also means that **you should
not delete an old version and re-upload it to fix things**. Just upload the fix
with a higher version number. If you delete the old version and replace it with
a different mod pack using the same version number, you'll mess up the
auto-updates, and your existing users won't get the fix.

Of course, you can choose to delete the old version and upload a *new, higher*
version with the fix. That will work just fine.

Just in case you were wondering, Heliosphere does need you to upload the whole
mod pack for each update. Even though it will screen out all the unchanged
files, it's important for determining which files to have users download when
they install your mod.

> There is an experimental way to do *delta updates*, which only require you to
upload new or changed files. If you would like to help test those, ask about it
on [our forums][forums].

[semver]: https://semver.org/
[forums]: https://forums.heliosphere.app/
