# Renderer
- Need spline renderer & graph renderer to work together to make an automated system.
	- Intersection isn't too bad see [this](https://medium.com/@all2one/intersecting-two-splines-70a1d901c446) article
	- If we use Python, we can use a basic UI library, scipy, and good graph optimization libraries (matplotlib + networkx)
	- Also Sai said that they don't want an animated renderer, but I kinda like the idea? To get timelord vibes? I understand that UNLWS is meant to be handwritten, but sliders to control perturbations or a phase-space explorer would be really neat for digital-native works
- What's difficult is designing a markup language that's not tedious to write out but is powerful enough to express non-linear writing structures.
	- Maybe have an english creole with binding markers (e.g. `me(a);eat(a,b);fish(b);large(b)` for the example in §*Bindings*)
	- A UNLWS-native system would be much more complicated, but more compressed (see Alex & Sai's [design](https://docs.google.com/document/d/1iQS-oAaCk2mpT2h6nLK8AAvYH84n4_aHvZT7dDo_MeY/edit) [docs](https://docs.google.com/document/d/1BfuloI902lfpVOC6UFhrx3pO-WYRaoGCd8IhUxrhCfA/edit))
		- Personally, I prefer markup legibility to compactness but I see why they would think that
- It might also be cool to include a native 3D embedding if it's not too much more complicated?  Future feature.