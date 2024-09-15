# LM-prompt-optimization-examples

## Setting up ollama

Based on the following guides:

- [Install Docker](https://docs.docker.com/engine/install/ubuntu/)

- [Installing the NVIDIA Container Toolkit](https://docs.docker.com/engine/install/ubuntu/)


## Run Ollama inside a Docker container

```docker run -d --gpus=all -v ollama:/root/.ollama -p 11434:11434 --name ollama ollama/ollama```

## Run a model

Now you can run a model like Llama 2 inside the container.

```docker exec -it ollama ollama run llama2```
