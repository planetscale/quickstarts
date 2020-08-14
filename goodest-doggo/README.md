Prebuilt binaries
-----------------

* Above, you will find prebuilt-binaries for Mac OSX, Windows and Linux
* Download the archive containing the name of your platform above and extract it to your preferred location.
  * On Windows, navigate Explorer to that location and double-click `goodest-doggo.exe`.
  * On Linux and OSX, navigate a terminal to that location and run `./goodest-doggo`; note that it's important for the current working directory to be the location containing the binary and other artifacts.


Running the Application
=======================
Once you've selected a method and have the daemon running, navigate to http://localhost:8000/ in your browser, enter the database URL that was displayed in your PlanetScaleDB Quick Start screen, create an account, and start rating doggos!

Docker
------
```bash
docker run --name=goodest-doggo -p8000:8000 goodest-doggo
```
We also have a container image on Docker Hub.


Source Code
===========
If you are interested in building and running the Rust app, the source code is here: https://www.github.com/planetscale/goodest-doggo 

we have archives with prebuilt binaries and all other required artifacts for Linux, Wndows, and OSX, and 






