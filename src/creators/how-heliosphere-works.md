# How Heliosphere works

Heliosphere works differently than other mod websites. Like other mod websites,
it lets you, as a creator, upload your mods in two formats: PMP and TTMP.
However, unlike other mod websites, Heliosphere will then process your uploaded
mod.

Without going into too much technical detail, Heliosphere unpacks your mod,
checks to see if the files inside have already been uploaded, then compresses
and uploads any new files to its own storage servers.

After the website processes your mod, users will be able to download it either
as a PMP on the website or directly into Penumbra via the in-game plugin. Both
methods use the same behind-the-scenes logic: all the files are individually
downloaded and decompressed and then reconstructed into one coherent mod pack.

> [!NOTE]
> Heliosphere will never offer TTMP downloads. However, most people want TTMPs
so they can import into TexTools. TexTools has added PMP support in their
Dawntrail release, which means you are able to import Heliosphere mods into
TexTools (and export PMPs out of it)!

One of the many benefits of this system is that you can offer streamlined mod
updates just by uploading a new version of your mod. Users can get those updates
automatically if they choose to, and otherwise, they're only a click away. When
they receive these updates, they are only downloading new or changed files
instead of redownloading the entire mod.

If this is sounding good to you so far, you'll probably like Heliosphere's way
of doing things. However, the rabbit hole goes deeper, as Heliosphere has some
more-complex systems available to creators. In order for you to best understand
how to use Heliosphere, we'll take a step back and define some terms in the next
section.
