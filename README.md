

# <img src="/favicon.png" width="48" height="48" valign="bottom"> Neumorphism.Avalonia

Easy to use and customizable Neumorphism Design implementation for [AvaloniaUI](http://avaloniaui.net/) framework.



![Screenshot](Avalonia.Neumorphism.Demo.gif)


# <img src="/favicon.png" width="32" height="32"> Overview

This library is a collection of styles to help you build your Avalonia app with a ready to go Neumorphism Design theme.

This Avalonia UI Neumorphic theme was inspired by another great Avalonia UI theme : [Material.Avalonia] (https://github.com/AvaloniaCommunity/Material.Avalonia)

As neumorphism has no official specifications, this is my own personal interpretation of Neumorphism general guidelines i found on the web (mainly on Dribble).

It also uses some elements of Material Design such as :
- Primary and Secondary (Accent) color with light and dark variants
- A light theme and a dark theme (you can switch between them at runtime)
- Material Design Icons (must be installed separately)

For the moment only the following controls are fully themed :
- Buttons
- ToggleButtons
- RadioButtons
- Checkboxes
- Textboxes
- Comboboxes

More controls should be themed soon.



# <img src="/favicon.png" width="32" height="32"> How to start ?

- Single .net Standard Library DLL (Neumorphism.Avalonia.dll)
- Should be used with .net Core 3.x, .net5, .net6...
- .Net 6 demo application project


# <img src="/favicon.png" width="32" height="32"> How to start ?


# <img src="/favicon.png" width="32" height="32"> Getting started

1. Add [Material.Avalonia][nuget] nuget package to your project:

       dotnet add package Material.Avalonia

2. Edit `App.xaml` file:

      ```xaml
      <Application ...
          xmlns:themes="clr-namespace:Neumorphism.Avalonia.Styles.Themes;assembly=Neumorphism.Avalonia"
          ...>
          <Application.Styles>
              <themes:MaterialTheme BaseTheme="Dark" PrimaryColor="Purple" SecondaryColor="Lime" />
          </Application.Styles>
      </Application>
      ```

