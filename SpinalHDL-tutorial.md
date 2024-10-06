# SpinalHDL

## Build docker image
``` bash
# cd .devcontainer
docker build -t my-spinalhdl-dev:latest -f Dockerfile-spinalhdl .
# on apple silicon mac
# docker build --platform linux/amd64 -t my-spinalhdl-dev:latest -f Dockerfile-spinalhdl .
```

## Spinal-Bootcamp
```bash
git clone https://github.com/jijingg/Spinal-bootcamp
jupyter lab
```

## Pipeline Api
[doc](https://spinalhdl.github.io/SpinalDoc-RTD/master/SpinalHDL/Libraries/Pipeline/introduction.html)
- `CtrlLink`, `StageLink`

## Plugin
[doc](https://spinalhdl.github.io/SpinalDoc-RTD/master/SpinalHDL/Libraries/Misc/service_plugin.html)
- `FiberPlugin`
- Example: DecoderSimplePlugin

## tilelink.fabric
[doc](https://spinalhdl.github.io/SpinalDoc-RTD/master/SpinalHDL/Libraries/Bus/tilelink/tilelink_fabric.html)

