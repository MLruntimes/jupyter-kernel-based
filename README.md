# Jupyter Kernel based ML Runtime

Creating a custom ML Runtime
1. Create or Modify a Dockerfile
2. Build the Docker Image  ---example-  docker build --network=host -t <docker registry>/<user>/<image name>:<tag>. -f Dockerfile  
3. Push the image to the your Docker Registry
4. Add Dockee image to the ML Runtime Catalog in your CML Workspace
5. Add the ML Runtime to your project and test it
  
  
