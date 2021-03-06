# Imaris

Here I will try to document my Imaris related Python libraries, as well as my Python XTensions.

In particular,
* [[BridgeLib|BridgeLib]] is a library I independently wrote to interface Python code with Imaris.
* [[TkDialog|TkDialog]] is the library I use to rapidly build simple Tk user interfaces for my XTensions.

# Tutorials:
* **Tutorial 0:** Here's a [Hello Imaris](https://github.com/zindy/Imaris/blob/master/tutorials/hello_imaris.ipynb) tutorial showing how to link Imaris and jupyter-notebook.

* **Tutorial 1:** [Number of cells vs time](https://github.com/zindy/Imaris/blob/master/tutorials/ncells_vs_time.ipynb) tutorial showing how to perform spot operations (counting unique spots / timepoints) using numpy and plotting the result using matplotlib.

* **Tutorial 2:** [Plotting tracks](https://github.com/zindy/Imaris/blob/master/tutorials/plotting_tracks.ipynb) tutorial showing how to extract track data (position and statistics) and plot various types of graphs (2-D data for now).

* **Tutorial 3:** [Tracking maggots](https://github.com/zindy/Imaris/blob/master/tutorials/tracking_maggots.ipynb) tutorial showing how to load a video in Python (hackish way using FFMpeg), do some image processing to remove the background, then send the data to Imaris and track the maggots using surfaces.

* **Tutorial 4:** [Working with surfaces](https://github.com/zindy/Imaris/blob/master/tutorials/pull_surfaces.ipynb) tutorial showing how to pull surfaces from Imaris. **TODO:** Will flesh this one out to show how to send surfaces back into Imaris.
