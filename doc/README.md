The main goal is to provide a webcomponent displaying tiles into a view port

a tile is displayed only if it could be fully displayed. As assumption, each tile should have a given size.

A tile could be added or removed simply by adding or removing the node into the DOM.

the tiler is displayed as a carousel. This carousel could have many page. the displayed page could be given by the "selected" property, the first (default one) is 0.

the size of a tile could be driven by properties ( with and height ) or by CSS rules. if given by CSS, the component will have to draw a tile to know its size, and as drawback if the CSS rule is modified the component will have no knowledge of that.

The content of the tile is let to the imagination of the designer, so we acan't take no assumption of the content and base the size of the tile by its content could have drawback effect.

The tiler must be sized.  