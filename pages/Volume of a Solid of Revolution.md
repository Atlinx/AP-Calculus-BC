Tags: #Topic 

# Volume of a Solid of Revolution

**Solid of Revolution** - A solid formed by taking the 2-D area and rotating it around an axis.

## Disk Method

Used to calculate the volume of a solid of revolution around an axis that is connected to the area.

Sums together multiple thin disks.

This is often times just one function bounding the top of the 2-D along with the x-axis bounding the lower part of the 2-D area.

The solid formed should be solid and have no holes.

$$\Large V = \int_a^b \pi |f(x)^2| dx$$

> **NOTE:**
> If you are rotating around the y-axis and the given equations are in $f(x)$, you must change the equations into $f(y)$ to use the disk method. 
> 
> Alternatively, you could just use the shell method.

## Washer Method

Used to calculate the volume of a solid of revolution around an axis that may be disconnected from the axis.

Sums together multiple thin washers.

Essentially the same as the disk method except there is another function bounding the lower part of the 2-D area.

The solid formed can have a hold through the axis it was formed around. 

$$\Large V= \int_a^b \pi |f(x)^2 - g(x)^2| dx$$

## Shell Method

Used to calculate the volume of a solid of revolution around an axis that is perpendicular the axis of the function that bounds the 2-D area.

Useful for when you are given two $y=\ldots$ functions and must rotate the area between the two functions around the y-axis.

Sums together multiple thing cylindrical shells. Since a shell that is cut on one-side and then rolled out is similar to a rectangular prism, the volume of a single shell is treated as a $(2 \pi x) \cdot dx \cdot f(x)$, which is in the format of $lwh$.

$$\Large V = \int_a^b 2 \pi x f(x) dx$$