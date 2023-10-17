# GitOps standard folder layout for OpenShift multi-cluster day-two configurations

As the title suggest this standard layout is laser focused on addressing the infrastructure configurations (a.k.a. day-two) for a multi-cluster deployment of OpenShift.

## Repo Structure

These are the main folders:

### Components

This folder contains all of the root pieces of configurations. Each piece of configuration resides in its own subfolder. These components should never derive from anything (i.e. their resources and components lists in the `kustomization.yaml` file are empty)

### Groups



| Folder      | Description |
| :----------- | :----------- |
| Components      |         |
| Groups   | This folder contains common pieces of configurations that can be applied to a group of clusters. Each group has its        |


## Design Decisions

## How to use this repo

## Use cases

