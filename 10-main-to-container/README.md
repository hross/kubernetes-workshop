# Going from a main() to a container

In these examples we provide a similar building parlance regardless of the programming language.

```
make container
```

Build and generate a container image locally for the program

```
make push
```

Push a previously generated container image for the program

```
make container push
```

Perform both steps in one fell swoop

# Contributing an example

It's probably easiest to copy an existing example.

Make sure it works, it runs in a container, and follows the Makefile parlance.

# Running docker commands

Building and running these containers in Docker examples:

```
cd [language]
docker build -t krisnova/kubernetes-workshop-app .
docker run -it krisnova/kubernetes-workshop-app
docker push krisnova/kubernetes-workshop-app
docker run krisnova/kubernetes-workshop-app:latest
```
