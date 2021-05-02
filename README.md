# OBS-Studio-Raspberry-Pi
OBS Studio for Raspberry Pi Models : 3B/3B+/3A+/4B

<p>In the terminal do :
<pre><code>chmod +x install_obs_studio_raspberry_pi.sh
./install_obs_studio_raspberry_pi.sh</pre></code>

Once finished, to force Raspbian to use OpenGL version 3.3 do this :</p>

![1.png](https://github.com/cmder-unx/OBS-Studio-Raspberry-Pi/blob/main/screenshots/1.png)
![2.png](https://github.com/cmder-unx/OBS-Studio-Raspberry-Pi/blob/main/screenshots/2.png)

<p>Double-click on OBS Studio, you're going to have this :</p>

![3.png](https://github.com/cmder-unx/OBS-Studio-Raspberry-Pi/blob/main/screenshots/3.png)

<p>In the <code>Command</code> input add <code>env MESA_GL_OVERRIDE=3.3</code> before <code>obs</code>, you're going to have something like this <code>env MESA_GL_OVERRIDE=3.3 obs</code> in the input, now you can validate the modifications and run OBS Studio like this :</p>

![4.png](https://github.com/cmder-unx/OBS-Studio-Raspberry-Pi/blob/main/screenshots/4.png)
![5.png](https://github.com/cmder-unx/OBS-Studio-Raspberry-Pi/blob/main/screenshots/5.png)
