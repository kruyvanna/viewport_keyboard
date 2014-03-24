viewport_keyboard
=================

Adjust viewport with respect to ios version.

This solves keyboard pushing content up on iOS devices.

Usage
======

* Add viewport.js

		<script type"viewport.js"></script>



* Initialize

		var viewport = new Vieport();
		viewport.setup();


Ignore
=======

The viewport.js will ingore viewport element with attribute data-no-adjust="true"

    <meta name="viewport" data-no-adjust="true">