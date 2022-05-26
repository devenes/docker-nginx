<div align="center" id="top"> 
  <!-- <img src="./.github/app.gif" alt="Docker" /> -->

  &#xa0;

  <!-- <a href="https://docker.netlify.app">Demo</a> -->
</div>

<h1 align="center">Docker</h1>

<p align="center">
  <img alt="Github top language" src="https://img.shields.io/github/languages/top/devenes/docker-nginx?color=56BEB8">

  <img alt="Github language count" src="https://img.shields.io/github/languages/count/devenes/docker-nginx?color=56BEB8">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/devenes/docker-nginx?color=56BEB8">

  <img alt="License" src="https://img.shields.io/github/license/devenes/docker-nginx?color=56BEB8">

  <!-- <img alt="Github issues" src="https://img.shields.io/github/issues/devenes/docker-nginx?color=56BEB8" /> -->

  <!-- <img alt="Github forks" src="https://img.shields.io/github/forks/devenes/docker-nginx?color=56BEB8" /> -->

  <!-- <img alt="Github stars" src="https://img.shields.io/github/stars/devenes/docker-nginx?color=56BEB8" /> -->
</p>

<!-- Status -->

<!-- <h4 align="center"> 
	🚧  Docker 🚀 Under construction...  🚧
</h4> 

<hr> -->

<p align="center">
  <a href="#dart-about">About</a> &#xa0; | &#xa0;   
  <a href="#rocket-technologies">Technologies</a> &#xa0; | &#xa0;
  <a href="#white_check_mark-requirements">Requirements</a> &#xa0; | &#xa0;
  <a href="#checkered_flag-starting">Starting</a> &#xa0; | &#xa0;
  <a href="#memo-license">License</a> &#xa0; | &#xa0;
  <a href="https://github.com/devenes" target="_blank">Author</a>
</p>

<br>

## :dart: About ##

This is a simple Nginx web server that runs on a Docker container.

<!-- ## :sparkles: Features ##
:heavy_check_mark: Feature 1;\
:heavy_check_mark: Feature 2;\
:heavy_check_mark: Feature 3; -->

## :rocket: Technologies ##

The following tools were used in this project:

- [Docker](https://www.docker.com/)
- [Nginx](https://nginx.org/)

## :white_check_mark: Requirements ##

Before starting :checkered_flag:, you need to have [Docker](https://www.docker.com/) installed.

## :checkered_flag: Starting ##

```bash
# Clone this project to your local machine
git clone https://github.com/devenes/docker-nginx.git
```

```bash
# Access the project directory
cd docker-nginx
```

```bash
# Build Docker image 
docker build -t devenes/webapp:1 .
```

```bash
# Run the image in a container
docker run --rm -i -t -d -p 8080:80 devenes/webapp:1
```

## The server will initialize in the <http://localhost:8080>


## :memo: License ##

This project is under license from MIT. For more details, see the [LICENSE](LICENSE) file.


Made with :heart: by <a href="https://github.com/devenes" target="_blank">devenes</a>

&#xa0;

<a href="#top">Back to top</a>
