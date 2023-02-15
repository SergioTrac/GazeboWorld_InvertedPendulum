# Inverted Pendulum Gazebo World

<p>
This is a simple Inverted Pendulum robot simulation build in a
Gazebo World.
</p>

## Usage

<p>
You can simply start the simulation using the following:
</p>

```bash
export GZ_SIM_RESOURCE_PATH=./local_models/
gz sim world_basic.sdf
```
<p>
<strong>GZ_SIM_RESOURCE_PATH</strong> represents the folder where the
Gazebo simulator it's gonna find the local models of this simulation. You can
define a different path or a global path for all your models.
</p>

<p>
That's all! Enjoy it!
</p>

### Usage with Gazebo2Robocomp
<p>
If you have installed <strong>Yakuake</strong> in your system you can use
</p>

```bash
./run_basic.sh
```

<p>
for a more easy start of the simulation and your Gazebo2Robocomp component all in one.
</p>

<p>
If you don't have Yakuake installed, you can do it with the following:
</p>

```bash
sudo apt-get update
sudo apt-get -y install yakuake
sudo apt-get install qdbus-qt5
```

<p>
Have fun!
</p>


