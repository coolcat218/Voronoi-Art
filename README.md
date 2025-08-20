# Voronoi-Art
breaking down images into voronoi segments; using vgg19 neural network to apply cezanne's style to new images

A Voronoi diagram is a partition of a plane into regions close to each of a given set of objects. It starts with points (called seeds) on a plane. For each seed there is a corresponding region, called a Voronoi cell, consisting of all points of the plane closer to that seed than to any other.

It can be observed naturally in plant cells, tree canopies, butterfly wings, etc.

Separately, Paul Cezanne was a French painter who breaks down images into their representational geometric primitives (and is also one of my favorite artists!). Each patch of color seems to represent a plane and multiple planes overlap to mimic space and depth.

This will plot seeds at high-contrast edges of the provided image, break down an image with a Voronoi tesselation with each fragment colored a representation of the contained pixels, and apply Cezanne's "style" onto the image.
