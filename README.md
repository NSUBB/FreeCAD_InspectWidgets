## FreeCAD Inspect Widgets Addon
Inspect widgets in FreeCAD

This fork aims to simplify installation of the macro by encapsulating the functions of the supporting files directly into the .FCmacro so that a single file can be added to FreeCAD Macros folder and run. This version was tested on Windows 11 installation of FreeCAD v1.0.1.

![Inspect-Widget-Addon](https://user-images.githubusercontent.com/4140247/107982828-b8b96c00-6f92-11eb-9c38-b7b13330042d.png)

## Description

This addon will expose the qss path to elements in the Qt interface. This helps stylesheet creators find the right selectors to modify in stylesheets in order to customize the UI.

## Background

A request was made in the FreeCAD community to have a sort of Chrome dev tools but for Qt. This addon was created in response.

## Installation

* Open your Macro folder. The path can be found by goin to Macro > Macros... from the main FreeCAD GUI. The folder path is listed at the bottom of the Execute Macro dialog box in the User macros Location.
* Copy the InspectWidgets.FCmacro file to the Macro folder location.
* Restart FreeCAD  
* Activate via `Macro > Macros... > select the InspectWidgets.FCmacro from the User Macros list > Execute.  

## Usage 

* An 'Inspect Widgets' docker panel will be visible in the left panel pane.  
* Press `Inspect` button
Result: the qss path will be dynamically update as the mouse hovers over an aspect of the interface. Press Shift key to hold the current property and stop the inspection.

## Developer

[@hyarion](https://github.com/hyarion/)

## Licence
