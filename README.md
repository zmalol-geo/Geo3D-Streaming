# Geo3D Streaming - visualisation of (very) large geological models meshes

This project aims to provide efficient streaming of large 3D geological models to the [Geo3D Web Viewer](https://geo3d.pgi.gov.pl/), a platform for visualizing complex geological structures directly within a web browser. As 3D models continue to grow in size and complexity, geologists need a seamless way to publish and explore them across desktop and mobile devices.

## Project Overview

The geological models we work with are continuously increasing in size, making it necessary to develop a robust solution for streaming these massive datasets without sacrificing performance. This project will explore existing methods for mesh streaming, and if needed, develop a new solution tailored specifically for the Geo3D viewer.

### Key Objectives:
- Stream large geological meshes efficiently to the Geo3D viewer.
- Ensure compatibility across desktop and mobile platforms.
- Investigate and implement existing streaming solutions, or develop a new method optimized for Geo3D.
  
## Potential Solutions

Currently, the most promising candidate for mesh streaming is the [Nexus](https://github.com/cnr-isti-vclab/nexus) framework, which specializes in progressive streaming of large-scale 3D models. However, we will evaluate other solutions as well to determine the best fit for Geo3D's specific requirements.

### Why Nexus?
- Nexus provides adaptive streaming, allowing for real-time rendering of 3D models as they load progressively.
- It is designed to handle large-scale meshes efficiently, making it a strong contender for this project.

### Additional Considerations:
- Compatibility with geological data formats.
- Ease of integration with the Geo3D web viewer.
- Performance on various devices, including mobile phones and tablets.

## Future Plans
If none of the existing solutions meet our performance and usability needs, we may develop a custom streaming method, tailor-made for Geo3D, focusing on optimizing the viewer's performance and user experience.

## How to Get Involved
Contributions are welcome! Whether you have experience with 3D rendering, web development, or geological modeling, we’d love to collaborate. Feel free to open an issue or submit a pull request to discuss ideas or improvements.
