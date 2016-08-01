# Scene navigation

When building scenes of your game in the [Scene Editor](xref:scene-editor), you need to move around a scene to accurately place entities in the scene.

This page will show you how to quickly and easily navigate in the Scene Editor as well as how to use the navigation controls, and navigation [gizmos](xref:gizmo).

## Navigation controls

### Walk in a scene

You can use the [Walk Navigation](xref:walk-navigation) mode by pressing the left mouse button and moving the mouse in the corresponding direction. The Walk Navigation mode lets you freely move along the X and Z dimensions of the scene.

>**Note:** In any navigation mode, holding doen the **Shift** key will speed up the action. This applies for all movement and rotation actions described in this chapter

The following video shows how to walk in a scene.

<video controls autoplay loop height="480" width="640">
                <source src="media/navigate-in-scene-walk-in-the-scene.mp4" type="video/mp4">
</video>

_Video: Walk in a scene_

### Fly in a scene

The fly navigation mode, allows you to move freely in all 3 dimensions. Just click and hold the right mouse button to activate the fly mode.

My moving the mouse you change the view angle of the camera. And you can use the **A**, **S**, **D**, **Q**, **W**, and **E** keys to move in different directions.

Action                          | Effect
--------------------------------|--------------
Right mouse button              | Rotate the camera
**A** key + Right mouse button  | Camera moves to the left
**D** key + Right mouse button  | Camera moves to the right
**S** key + Right mouse button  | Camera moves backward
**W** key + Right mouse button  | Camera moves forward
**Q** key + Right mouse button  | Camera moves downward
**E** key + Right mouse button  | Camera moves upward


The following video shows the sample actions and effects as listed in the above table.
 
<video controls autoplay loop height="480" width="640">
                <source src="media/navigate-in-scene-fly-in-the-scene.mp4" type="video/mp4">
</video>
 
_Video: Fly in a scene_

### Orbital rotation

When you want to rotate around objects of your scene, you can use the orbital rotation by pressing the **Alt** key and the left mouse button.

   ![Orbital rotation schema](media/navigate-in-scene-orbital-rotation-schema.png)
   
   _Orbital rotation schema_

The point of rotation is always the center of the screen and the distance to the center can be adjusted with the mouse wheel.

<video controls autoplay loop height="480" width="640">
                <source src="media/navigate-in-scene-orbital-rotation.mp4" type="video/mp4">
</video>
 
_Video: Orbital rotation _

### Controls summary

The following table shows a summary of all navigation actions and their controls.

Action                 | Controls
-----------------------|--------------
Translate              | Arrow keys, Any mouse button pressed + **A**, **S**, **D**, **Q**, **W**, and **E** keys
Walk                   | Left mouse button
Look around in a scene | Right mouse button
Orbital rotation       | **Alt** key + Left mouse button
Zoom in or zoom out    | Rotate mouse wheel, **Alt** key + Right mouse button
Pan                    | Press middle mouse button

## Navigation gizmos

Navigation gizmos are small objects present on the Scene Editor that help you navigate inside a scene.

By using the view camera gizmo, you can change the camera view angle and switch projection modes. You can use the scene orientation gizmo to know the current orientation of your scene.

### View camera gizmo

You can use the view camera gizmo cube to change the orientation of the camera. The view camera gizmo is present on the top-right corner of the Scene Editor. The following image displays the view camera gizmo.

   ![View camera gizmo](media/navigate-in-a-scene-view-camera-gizmo.png)

   _View camera gizmo_

By using this gizmo, you can easily set the camera view angle to the preset values and switch between the [Perspective](xref:perspective-projection) and [Orthographic](xref:orthographic-projection) projections.

### Change camera view angle

To change a view angle of the editor camera, simply click the corresponding face or edge or corner of the view camera gizmo cube.

The following table shows the actions and the corresponding changes in the camera orientations.

Click    | To change orientation of camera so that
---------|--------------
Face     | It faces the selected face
Edge     | It faces the two adjacent faces with a 45° angle
Corner   | It faces the three adjacent faces with a 45° angle

The following video shows how to change a camera view angle using the view camera gizmo.

<video controls autoplay loop height="480" width="640">
                <source src="media/navigate-in-scene-change-view-angle.mp4" type="video/mp4">
</video>

_Video: Change view angle using view camera gizmo_

### Scene orientation gizmo

The scene orientation gizmo is displayed in the bottom-left corner of the Scene Editor.

This gizmo indicates the current orientation of the scene.

   ![Scene orientation gizmo](media/navigate-in-a-scene-scene-orientation-gizmo.png)

   _Scene orientation gizmo_

You’ve explored how to navigate through a scene. Next we'll show you how to move and rotate your entities, see [Positioning entities](positioning-entities.md).