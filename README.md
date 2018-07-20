# Orient

Hackathon project inspired by pydeface to generate a tool that robustly registers a brain image to a template. This is for the purposes of defacing; Once registered the image voxels of the face can be masked for the purposes of de-indentification.

In order to be scalable this project uses Dask.

In order to be easy to use for as many datasets as possible in a reliable manner the input to the tool must be a BIDS dataset.