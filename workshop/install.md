# Docker Install Instructions

By Samantha Fritz (Archives Unleashed, University of Waterloo)

This quick guide will walk through how to install Docker for Mac users

## Resources
* [Docker Community for MAC CE](https://store.docker.com/editions/community/docker-ce-desktop-mac)

## Install Docker 
1. To install Docker for a Mac OS, use this [link](https://store.docker.com/editions/community/docker-ce-desktop-mac). Scroll down the page to select Docker CE for Mac (Stable)
![install-2](https://user-images.githubusercontent.com/7362321/35658635-4eb04e74-06d0-11e8-8258-30c63c1cb7b2.png)

2. From the downloads folder, double click to start installation (.dmg file)
![install-3](https://user-images.githubusercontent.com/7362321/35658636-4ebca34a-06d0-11e8-8470-6b87fc01b086.png)

3. Once file has been verified you can drag and drop into your applications folder, then launch application.
![install-4](https://user-images.githubusercontent.com/7362321/35658637-4ece0a2c-06d0-11e8-9066-fccb115bc951.png)

<i>Please note</i>, depending on your security preferences a notice may show up warning you, you are about to open an application from the web. Select open to continue. 

![install-5](https://user-images.githubusercontent.com/7362321/35658638-4edeb1b0-06d0-11e8-8bef-4b7b5ad9143d.png)

4. The Docker icon should appear in your menu bar along the top of your screen. When you click on the icon, there should be a green dot indicating docker is running
![install-6](https://user-images.githubusercontent.com/7362321/35658925-a6a1b0ae-06d1-11e8-8948-f4efc70962ab.png)
![install-7](https://user-images.githubusercontent.com/7362321/35699127-27b4c768-075d-11e8-8314-7d5fae02f26d.png)

Now that the Docker application is installed you can log in with your Docker IDif you have one. You can create one at https://cloud.docker.com

## Run Docker and Install AUT

5. Open your terminal and try out some Docker commands. On a Mac, you can find a terminal window by going to your Applications Folder, selecting "Utilities," and then opening up "Terminal."" 

Try running the following two commands:

| Command        | Purpose           |
| ------------- |:-------------:|
| docker version | to check that you have the latest release installed |
| docker run hello-world | to verify that Docker is pulling images and running as expected |

![install-8](https://user-images.githubusercontent.com/7362321/35699395-f100c91e-075d-11e8-824b-2578698fe6dd.png)

6. Now you're ready to install AUT. Type the following command:

```
docker run --rm -it archivesunleashed/docker-aut
```

This will take a while to download and install. Eventually, you'll hopefully see:

```
Welcome to
      ____              __
     / __/__  ___ _____/ /__
    _\ \/ _ \/ _ `/ __/  '_/
   /___/ .__/\_,_/_/ /_/\_\   version 2.1.1
      /_/

Using Scala version 2.11.8 (OpenJDK 64-Bit Server VM, Java 1.8.0_151)
Type in expressions to have them evaluated.
Type :help for more information.

scala>
```

You're now ready for the workshop!