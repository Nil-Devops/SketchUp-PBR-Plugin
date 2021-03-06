
SketchUp PBR plugin help
========================

In SketchUp
-----------

### Known issue and workaround

Issue | Workaround
:--- | :---
glTF export failed. | Be sure **all** texture images are in JPEG or PNG format. Else, convert them with a tool like [this](https://image.online-convert.com/convert-to-png) then reimport them in SketchUp.

### How to add a light to model?

1. Click on "Add an Artificial Light" in PBR Toolbar or Menu.
2. Sphere created is your light. Move it. Paint it with a color.
3. Reopen PBR Viewport and voilà!

You can add many lights to model.

### How to uninstall PBR plugin?

Open Extension Manager. Disable PBR plugin **before** uninstall it.

In PBR Viewport
---------------

### Known issues and workaround

Issue | Workaround
:--- | :---
Texture is fully opaque whereas I set opacity to *n* %. | With your preferred photo editing software, set opacity **directly** to texture image. Use PNG as exchange format to preserve opacity. Reimport texture image in SketchUp.
Texture is incorrect. | Reverse back face where texture is applied. Paint texture on front face.<br> If problem persists: triangulate **then** map entity with [SketchUV](https://extensions.sketchup.com/content/sketchuv) plugin.

### How to control scene camera?

Control scene camera with a mouse:

Orbit with **middle drag**. Pan with **left drag**. Zoom with **wheel**.

It's also possible to control camera with a standard gamepad.

### How to export render to an image?

Do a right click anywhere then click on "Save image as ...".
