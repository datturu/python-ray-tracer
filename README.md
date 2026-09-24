# Python Ray Tracer

A basic ray tracer written from scratch in Python with NumPy. It renders a 3D scene of two spheres on a plane and saves the image to `raytraced_scene.png`.

![Rendered scene](raytraced_scene.png)

## How It Works

1. **Camera rays** – cast one ray from the camera through each pixel of the image plane.
2. **Intersection** – test each ray against the spheres and the plane and keep the closest hit.
3. **Shading** – color each hit point based on the surface normal and the light direction.
4. **Output** – write the pixel colors to a PNG image.

## Tech Stack

- Python 3
- NumPy (vector math)
- Pillow (image output)
- Jupyter Notebook

## Project Structure

```
rayTrace.py              # full ray tracer
rayTracingBasic.ipynb    # step-by-step notebook version
raytraced_scene.png      # rendered output
*.jpg, artwork.key       # diagrams explaining the method
```

## Getting Started

```bash
pip install numpy Pillow
python rayTrace.py
```

Or open `rayTracingBasic.ipynb` in Jupyter to follow the method step by step.

## Credits

Started from course sample code by [Eraldo Ribeiro](https://github.com/eraldoribeiro/raycasting). I extended `rayTrace.py` into a complete ray tracer with camera rays, sphere and plane intersection, and shading.
