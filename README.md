<h1>3D Renderer</h1>
<p>Final project for CS260(Computer Graphics) made in collaberation with Zach Abbey. </p>
<p>Renders a 3d scene and turns it into a ppm image. Images can be generated using ray tracing, meshs, and different textures. Multiple images can be turned into an animation. </p>
<p>Deliverable: An animation of a desk setup. It features multiple complex meshes and rotating peices. </p>

<h3>Project Elements</h3>
<ul>
  <li>
    <h3>Bounding Box</h3>
    <p><b>Description: </b>An axis-aligned box that provides a fast hit test along with convenient methods for transformation and expanding a box to encompass new objects.</p>
    <p><b>Location: </b>bbox.py</p>
  </li>
  <li>
    <h3>Camera</h3>
    <p><b>Description: </b>Allows the user to set a viewpoint into the scene. </p>
    <p><b>Location: </b>camera.py</p>
  </li>
  <li>
    <h3>Image</h3>
    <p><b>Description: </b>A class that allows for the manipulation of a simple raster image. </p>
    <p><b>Location: </b>image.py</p>
  </li>
  <li>
    <h3>Materials</h3>
    <p><b>Description: </b>Allows for objects to be "skinned" with different materials. Some example materials are provided by OpenGL. </p>
    <p><b>Location: </b>materials.py</p>
  </li>
  <li>
    <h3>Math 3D</h3>
    <p><b>Description: </b>Contians an implementation of points and vectors in 3d space. </p>
    <p><b>Location: </b>math3d.py</p>
  </li>
  <li>
    <h3>Matrix</h3>
    <p><b>Description: </b>A set of functions for operating on matrices. </p>
    <p><b>Location: </b>matrix.py</p>
  </li>
  <li>
    <h3>Mesh</h3>
    <p><b>Description: </b>A class allowing for a OFF file containing a mesh to be rendered. </p>
    <p><b>Location: </b>mesh.py</p>
  </li>
  <li>
    <h3>Models</h3>
    <p><b>Description: </b>Contains several classes for basic 3d shapes. These shapes can be added to a scene and then rendered. </p>
    <p><b>Location: </b>models.py</p>
  </li>
  <li>
    <h3>ppm Viewer</h3>
    <p><b>Description: </b>Allows the user to view a ppm image. </p>
    <p><b>Location: </b>ppmview.py</p>
  </li>
  <li>
    <h3>3D Rays</h3>
    <p><b>Description: </b>A ray that travels through a 3 demensional space. This is useful for ray traced rendering. Rays locations can also be found at a given point in time. </p>
    <p><b>Location: </b>ray3d.py</p>
  </li>
  <li>
    <h3>Object-based Rendering</h3>
    <p><b>Description: </b>Renders a scene using onlt the objects in it. </p>
    <p><b>Location: </b>render_oo.py</p>
  </li>
  <li>
    <h3>Ray Tracing</h3>
    <p><b>Description: </b>Renders a scene using ray tracing. </p>
    <p><b>Location: </b>render_ray.py</p>
  </li>
  <li>
    <h3>RGB</h3>
    <p><b>Description: </b>An rgb object contains the color for every point in an object. It also allows these values to be scaled and modified. </p>
    <p><b>Location: </b>rgb.py</p>
  </li>
  <li>
    <h3>Scene</h3>
    <p><b>Description: </b>A scene is the basic container that is 3d rendered. The base class acts like a header and contains the basics of a scene but no objects. </p>
    <p><b>Location: </b>scenedef.py</p>
  </li>
  <li>
    <h3>Textures</h3>
    <p><b>Description: </b>Simple texture mapping for the Box and Sphere objects. </p>
    <p><b>Location: </b>textures.py</p>
  </li>
  <li>
    <h3>Trans 3D</h3>
    <p><b>Description: </b>Contains functions that use matricies to perform 3D transformations in homogeneous coordinates. </p>
    <p><b>Location: </b>trans3d.py</p>
  </li>
</ul>
