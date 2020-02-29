  AddDetailDoodads.exe
    Adds detail doodads per texture filename.

    Usage: "AddDetailDoodads.exe <map filename>"
    Built at: Oct 12 2009
	
  AllOcean3.0.exe
    Fills the ADT with ocean 3.* style where no terrain is above 0.

    Usage: "AllOcean3.0.exe <map filename> [<depthfactor>]"
    Built at: Oct 12 2009
	
  AllWater.exe
    Adds a flat water layer at the given height or 0.

    Usage: "AllWater.exe <map filename> [<level: 0>] [<flags: 20>]"
    Built at: Oct 12 2009
	
  CoverWithWater.exe
    [NOT STABLE] Covers the whole ADT by water that is above the terrain..

    Usage: "CoverWithWater.exe <map filename> [<depthfactor>]"
    Built at: Oct 12 2009
	
  CreateWDT.exe
    Makes a WDT file telling that the specified ADT tiles are present.

    Usage: "CreateWDT.exe <MapName> <LowerX> <LowerY> <UpperX> <UpperY>"
    Built at: Oct 12 2009
	
  FileInfo.exe
    Saves info about an ADT into a txt file.

    Usage: "FileInfo.exe <ADT filename>"
    Built at: Oct 12 2009
	
  FixAllOcean3.0.exe
    Deletes all MCLQ chunks.

    Usage: "FixAllOcean3.0.exe <map filename>"
    Built at: Oct 12 2009
	
  GetSlopePicture.exe
    [NOT STABLE] Tries to make a pgm-image from the slopes in the terrain.

    Usage: "GetSlopePicture.exe <map filename>"
    Built at: Oct 12 2009
	
  LoadInfo.exe
    Loads info from a txt file made by FileInfo back into the ADT.

    Usage: "LoadInfo.exe <ADT filename>"
    Built at: Oct 12 2009
	
  MakeMap.exe
    Combines multiple .raw maps made by Noggit into one big one.

    Usage: "MakeMap.exe <map name> <xOff> <yOff> <tWidth> <tHeight>"
    Built at: Oct 12 2009
	
  MapMover.exe
    Moves ADT tiles according to the given parameters.
    Needs to have "OffsetFix" in the same directory.

    Usage: "MapMover.exe <OldMapName> <LowerX> <LowerY> <UpperX> <UpperY> <NewMapName> <OffsetX> <OffsetY>"
    Built at: Oct 12 2009
	
  ModelSwap.exe
    Replaces a model filename with another one of the same or less length in an ADT.

    Usage: "ModelSwap.exe <map filename> <old filename> <new filename>"
    Built at: Oct 12 2009
	
  OffsetFix.exe
    Fixes several offsets that are wrong after moving an ADT and can move it upwards.

    Usage: "OffsetFix.exe <map filename> [<z change>]"
    Built at: Oct 12 2009
	
  PatchHoles.exe
    Removes all holes in the terrain.

    Usage: "PatchHoles.exe <map filename>"
    Built at: Oct 12 2009
	
  RaiseTerrain.exe
    Raises all terrain.

    Usage: "RaiseTerrain.exe <map filename> <difference>"
    Built at: Oct 12 2009
	
  RemoveSound.exe
    Deletes all mapchunk soundemitters in the ADT.

    Usage: "RemoveSound.exe <map filename>"
    Built at: Oct 12 2009
	
  RemoveTheWalls.exe
    Removes unpassable chunks of an ADT.

    Usage: "RemoveTheWalls.exe <map filename>"
    Built at: Oct 12 2009
	
  SetChunkFlags.exe
    Sets the MCNK flags for all chunks in an ADT.

    Usage: "SetChunkFlags.exe <map filename> [<flag = 8>]
      magma = 16, ocean = 8, river = 4"
    Built at: Oct 12 2009
