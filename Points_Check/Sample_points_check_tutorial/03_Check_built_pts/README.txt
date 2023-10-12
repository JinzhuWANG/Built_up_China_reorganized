We create bulit_pts from [rural] and [Urban] regions, seperately.

The reason is that built_pts needs to be more densified in [Urban] regions;
otherwise the classification on built_up_land will be compromised by [Rural] points.

	One example is that when we use randomly scatters samplt points in the {xinan} region,
	where most of the points come from rural locations, the final classification can not
	distinguish moutains and built_up areas.  