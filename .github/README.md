# Probmods.jl

A port of [probmods.org](http://probmods.org) to Julia. Below is a description
of each directory of interest.

```
chapters/
| reprints/  # A port to Julia along with rephrasing in my own words
| verbatim/  # A verbatim port to Julia, in Probmods.org's terminology
```

## Getting Started

1. Download Docker and Docker Compose (see below for links).
1. Clone/download this repository and navigate to it on your local filesystem.
1. Right-click the folder and "Open in Terminal/PowerShell" (based on your OS).
1. Launch Probmods.jl by running: `docker-compose up` (keep this window open).
1. Open your browser and navigate to [http://localhost:7655/lab][localhost]

### Docker downloads

- **Windows**: https://docs.docker.com/docker-for-windows/install/
- **MacOS**: https://docs.docker.com/docker-for-mac/install/
- **Linux (Ubuntu)**: https://docs.docker.com/engine/install/ubuntu/
  - You'll need to manually install Docker Compose as well. (DigitalOcean
    often has good guides for this.)

[localhost]: http://localhost:7655/lab
