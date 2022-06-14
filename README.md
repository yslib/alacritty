<p align="center">
    <img width="200" alt="Alacritty Logo" src="https://raw.githubusercontent.com/alacritty/alacritty/master/extra/logo/compat/alacritty-term%2Bscanlines.png">
</p>

<h1 align="center">Alacritty - A fast, cross-platform, OpenGL terminal emulator</h1>

<p align="center">
  <img width="600"
       alt="Alacritty - A fast, cross-platform, OpenGL terminal emulator"
       src="https://user-images.githubusercontent.com/8886672/103264352-5ab0d500-49a2-11eb-8961-02f7da66c855.png">
</p>


Original project is here: https://github.com/alacritty/alacritty

## About this modification

This fork is integrated with [VLC](https://github.com/videolan/vlc) Video player for ~~slacking off immersively~~ when coding.😝

![feature](feature.png)

This project is based on the VLC of a preview release 4.0+.

It needs an exporting library (.lib) for linking to VLC runtime if it will be compiled successfully on Windows. But I have not yet provided this .lib file. You could generate it according to this [tutorial](https://wiki.videolan.org/GenerateLibFromDll/). It lacks of a GUI based control panel for video playing and will be added later.