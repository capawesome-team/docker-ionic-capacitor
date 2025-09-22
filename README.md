# docker-ionic-capacitor

🐳 Docker image for building Ionic apps with Capacitor.

<div class="capawesome-z29o10a">
  <a href="https://cloud.capawesome.io/" target="_blank">
    <img alt="Deliver Live Updates to your Capacitor app with Capawesome Cloud" src="https://cloud.capawesome.io/assets/banners/cloud-deploy-real-time-app-updates.png?t=1" />
  </a>
</div>

## How to use this image

### Pull image

Pull from GitHub Container Registry:  

```
docker pull ghcr.io/capawesome-team/docker-ionic-capacitor:latest
```

### Build image

Build locally:  

```
docker build -t capawesome-team/ionic-capacitor .
```

Build from GitHub:  

```
docker build -t capawesome-team/ionic-capacitor https://github.com/capawesome-team/docker-ionic-capacitor.git#main
```

Available build arguments:  

- JAVA_VERSION (Default: `17`)
- NODEJS_VERSION (Default: `20`)
- ANDROID_SDK_VERSION (Default: `11076708`)
- ANDROID_BUILD_TOOLS_VERSION (Default: `34.0.0`)
- ANDROID_PLATFORMS_VERSION (Default: `34`)
- GRADLE_VERSION (Default: `8.2.1`)
- IONIC_VERSION (Default: `7.2.0`)
- CAPACITOR_VERSION (Default: `6.0.0`)

### Run image

Run the docker image:  

```
docker run -it capawesome-team/ionic-capacitor bash
```

## Questions / Issues

If you got any questions or problems using the image, please visit my [GitHub Repository](https://github.com/capawesome-team/docker-ionic-capacitor) and write an issue.
