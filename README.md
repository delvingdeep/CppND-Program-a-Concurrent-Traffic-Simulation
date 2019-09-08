### Lesson-1 Project
Sandbox for implementing the project
![Sandbox image](/images/sandbox_image.png)

### Project TODO list
- Task L1.1 : In the base class `TrafficObject`, set up a thread barrier in its destructor that ensures
that all the thread objects in the member vector ` _threads` are joined.

- Task L1.2 : In the `Vehicle` class, start a thread with the member function `drive` and the
object `this` as the launch parameters. Also, add the created thread into the `_thread` vector of
the parent class.

- Task L1.3 : Vary the number of simulated vehicles in `main` and use the top function on the terminal
or the task manager of your system to observe the number of threads used by the simulation.

Project flowchart is outlined as below:
![Project flowchart](/images/project_flowchart.png)

#### Build instructions
```bash
$ mkdir build
$ cd build
$ cmake .. && make
```

#### Run the simulator
Once the project is build, run the simulator from the `/build` sub-directory
```bash
$ ./traffic_simulation
```
