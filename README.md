# Introduction

This repo contains the configuration to run the buyer mock engine. These configuration are responsible for the rendering of input fields and order of transcation.

# Repository Structure

- config/
  - index.yaml [ALL]
  - fis.yaml [FIS]
  - trv.yaml [TRV]
- build/
  - build-FIS.yaml
  - build-TRV.yaml
  - build-ALL.yaml
- app.js

# Change set/changelog

This is the version 1.0.0 of the buyer mock configs

# Contribution

Contributions can be made using the following branching structure:

```
    Branches: master -> Integ -> feat/fix/feature
```

# Pre-requisite

- Node.js
- git
- npm

# How to use

- The app.js script is used to build single config file out the the configs which is then used by the buyer mock engine.

- To create a build for a particular domain use the following command.

```
    node app trv
    node app fis
```

- Check the build folder for the generated json file.
- To craete a single file whith all domain.

```
    node app
```

# Config Structure
