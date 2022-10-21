# ros2uni
I am trying to learn ros platform at university
## Create a package

## Creating subscriber publisher in python
I created two nodes to publish and subscribe to data over a topic. Before running them, I added their dependencies and entry points to the package configuration files.
You can find its working video in py_pubsub file

## Creating service and client in python
I created two nodes to request and respond to data over a service. I added their dependencies and executables to the package configuration files so that I could build and run them, allowing me to see a service/client system at work. You can find its video in py_srvcli file

## Using parameters in python class
I created a node with a custom parameter, that can be set either from a launch file or the command line. I added the dependencies, executables, and a launch file to the package configuration files so that you could build and run them, and see the parameter in action.

## Using ros2doctor to identify issues
ros2doctor will inform us of problems in our ROS 2 setup and running systems. We can get a deeper look at information behind those warnings by using the --report argument.

Keep in mind, ros2doctor is not a debug tool; it won’t help with errors in our code or on the implementation side of our system.

## Creating an action
In this tutorial, I learned the structure of an action definition. I also learned how to correctly build a new action interface using CMakeLists.txt and package.xml, and how to verify a successful build.

There is a picture of it by the name CreatingAction.png above
