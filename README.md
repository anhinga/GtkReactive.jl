# My personal fork of Julia GtkReactive

The `imshow` of ImageView package can be called on a 3D array. In this case, a two-directional movie player is created:

https://github.com/JuliaImages/ImageView.jl

My goal here is to tweak the player, so that the movie does not stop when the end is reached, but instead starts playing in the opposite direction, and so on indefinitely. 

The current version is semi-successful: the slider stops moving after one back-and-forth, 
the player keeps playing, but is gradually slowing down, so there might be memory management
issues or something like this. So, not quite done yet.

# GtkReactive

[![Build Status](https://travis-ci.org/JuliaGizmos/GtkReactive.jl.svg?branch=master)](https://travis-ci.org/JuliaGizmos/GtkReactive.jl)

[![codecov](https://codecov.io/gh/JuliaGizmos/GtkReactive.jl/branch/master/graph/badge.svg)](https://codecov.io/gh/JuliaGizmos/GtkReactive.jl)

GtkReactive is designed to simplify the creation of graphical user interfaces (GUIs) using [Gtk](https://github.com/JuliaGraphics/Gtk.jl) and Julia.
GtkReactive descended from
[GtkInteract](https://github.com/jverzani/GtkInteract.jl), and mimics
aspects of the design of
[Interact](https://github.com/JuliaGizmos/Interact.jl). To learn how
to use this package, please see the documentation:

[![](https://img.shields.io/badge/docs-stable-blue.svg)](https://juliagizmos.github.io/GtkReactive.jl/stable)
[![](https://img.shields.io/badge/docs-latest-blue.svg)](https://juliagizmos.github.io/GtkReactive.jl/latest)
