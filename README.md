# window_frame_transparency
very much hacked together fork of YAL's window_frame_transparency that allows one color to be set transparent 

currently set to #999900, the worst color.

using window frame is needed because draw calls seem to fail when gamemakers window is changed to a layered one.
the solution is setting the parent window to a layered window, then using the chroma feature on the parent window which somehow applies to the child (gamemaker)
