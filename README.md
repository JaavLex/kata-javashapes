# kata-javashapes

## Introduction
This is a recreation of an exam I had. The objective is to create
a java app/form with a graphical interface. 

The form's objective is to have an app that can draw polygons inside 
a circle, and the polygons angles must align perfectly with the perimeter
of the circle.

---

## Window

- 800px by 850px.
- Resizable.
- Exits application when clicking on the default X button.
- Must be named "Kata - Javashapes".

## Pannels

### Top part

- 1 Combo box to choose a polygon (By default must select an empty space).
- 1 Combo box to choose a color for the polygon (By default must be set to gray).

### Middle part

- 1 JPannel that must be resizable with the window.
- The pannel must be gray, and it must have a circle shape that has half the area size of the JPannel in the middle.
- The pannel must be in a separate class, and be called as an object.

### Bottom part

- There must be two buttons that are configured in a separate class.
- 1 delete button. The text must be set to the following settings (Verdana, 20px, White). The button must have a red background.
- 1 draw button. The text must be set to the following settings (Verdana, 20px, White). The button must have a blue background.

## Functionnality

- When a shape and color is selected, the app must draw the shape in the middle of the circle, with all angles aligned to the circle's perimeter. It must also be the right color.
