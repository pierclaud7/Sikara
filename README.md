# Responsive
Exercise 1: WEB page

Code a template containing text and complying with the following instructions:
- Containers containing text are displayed in columns above 640px, then one below the other below
- A header is visible only for screens above 800px
- A footer is visible only when printed

Exercise 2: Weather

Reproduce the behavior of this weather site with the data of your choice (link to cool icons! https://www.shareicon.net/). 

Mobile screen + intermediate screen :
<img src=http://superadmin.sikara.fr/uploads/005exo2.png />

Widescreen display :
<img src=http://superadmin.sikara.fr/uploads/006exo2.PNG />

Exercise 3: The Grid

To define a grid, we need 3 elements: a container, a rows class and a set of columns classes.
- Define a container class that takes up the entire width of the screen. If you want to go further, you can even define another container-fluid class that takes 100% of the width on small screens but adds margins on a large screen.
- To create our grid, we'll divide the page into 12 sub-elements of equal size per row. So define a class, row, corresponding to the line, which will take 100% of the width of its container.
- For each column, you'll need to define the classes corresponding to its size.
- For a size corresponding to 1 column, we divide 100% / 12, for a size corresponding to 2 columns, we multiply by 2 what we've just found, and so on up to 12.
<img src=http://superadmin.sikara.fr/uploads/007exo3.PNG width= 300 />
- To make these columns responsive, we'll use the same principle, but for different screen sizes: Screen > 700px (sm) || Screen > 900px (md) || Screen > 1200px (lg) Example :
<img src=http://superadmin.sikara.fr/uploads/008exo3.PNG width= 300 />

Use the grid system you've just created to reproduce the following site (from largest to smallest):
<img src=http://superadmin.sikara.fr/uploads/009exo3.PNG  />
<img src=http://superadmin.sikara.fr/uploads/010exo3.PNG />
<img src=http://superadmin.sikara.fr/uploads/011exo3.PNG />
<img src=http://superadmin.sikara.fr/uploads/012exo3.PNG />

The menu disappears to make way for a hamburger (mobile drop-down menu).
