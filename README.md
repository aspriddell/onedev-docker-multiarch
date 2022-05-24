# OneDev multiarch Docker builds
[![Docker Pulls](https://img.shields.io/docker/pulls/aspriddell/onedev?style=flat-square)](https://hub.docker.com/r/aspriddell/onedev)

### Overview
This repo automatically builds and publishes versions of [OneDev](https://github.com/theonedev/onedev) Server and CI Agents on a weekly basis.

#### Server Images
- `aspriddell/onedev:server`
- `aspriddell/onedev:server-[version]`

#### CI Agent Images
- `aspriddell/onedev:agent`
- `aspriddell/onedev:agent-[version]`

### Usage
Follow the installation guide at either https://code.onedev.io/projects/162/files/main/pages/quickstart.md or https://code.onedev.io/projects/162/files/main/pages/installation-guide.md but replace `1dev/server` with the apropriate image above

### Issues
For issues related to the arm64 version of the build issues should be reported here, otherwise issues should be directed to the [OneDev developers](https://code.onedev.io/)
