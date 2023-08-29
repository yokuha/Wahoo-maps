# Wahoo-maps

Documentation and personal adaptations of homebuilt Wahoo maps and themes.

In this project, I'll try to provide a consistent, hopefully easily accessible,
documentation of the installation of updated maps for Wahoo Roam and Bolt GPS
cycling computers. This discussion is focused on, and often limited to, the Bolt
v2 and Roam v2 computers, which I will jointly refer to as ``WAHOO'' in this
documentation (while ``Wahoo'' refers to the company).

This is really a very simple and small project standing on the shoulders of
Giants, or even more so, simply trying to provide a single-stop documentation
for newbies. Any feedback and help in that respect is very welcome.



# Improving the maps on Wahoo bike computers

The easiest update to implement is to use an updated render theme, as the on
contained in this project. This can be done by copying the files from the
[render-theme in this project](https://github.com/yokuha/Bolt2-Mapsforge-VTM-Rendertheme)
or the one by
[zenziwerken](https://github.com/zenziwerken/Bolt2-Mapsforge-VTM-Rendertheme)to
your Wahoo:
* connect the WAHOO to the computer _via_ USB and turn it on
* create `maps/vtm-elemnt`, for instance, using [Android File transfer](#android-file-transfer)
* copy the content of (render-theme/) on your computer to `maps/vtm-elemnt` on
  the WAHOO.


## Showing points of interest (POIs)

The updated render theme will provide a cleaned up map with, e.g., building
areas in red and forests in light green. Moreover, it will turn on the display
of interesting POIs – such as gas stations, bakeries, etc. – at stronger Zoom
levels, e.g., "500 m" and below. However, while generic POIs are included in the
Wahoo maps on the Roam2, **they are not included in the Wahoo-provided maps on
the Bolt2**. For the Bolt2, you will also need to [install updated maps](#updated-maps).


## Updated maps

While Wahoo provides optimized maps for pretty much the whole world, they are
only very infrequently updated. Homebuilt maps allow you to both use newer map
material as well as to include further, or selected, information. The latter
could include, for instance, more or other points of interest.

### Obtaining maps

The straightforward approach is to download pre-built maps. A great resource is
the
[OneDrive folder](https://onedrive.live.com/?authkey=%21AM8e4ViJIHdmOyU&id=F4E28DC020FD3904%21120&cid=F4E28DC020FD3904)
of ebe, which contains a large set of maps and routing tiles for direct use.

Currently, these maps contain many POIs for Zoom levels "100 m" and below.

### Creating your own maps

You can create your own maps using
[wahooMapsCreator](https://github.com/treee111/wahooMapsCreator). Details on
usage are available in the project, some guidelines will follow here.


### Installing maps


# Access options to your GPS computer

## Android File transfer

## Android Debug bridge (adb)

## The vti/elemntary app




# Other resources

## Information on Zoom-level scales

* https://github.com/treee111/wahooMapsCreator/blob/develop/docs/TAGS_ON_MAP_AND_DEVICE.md#zoom-levels-and-scale
