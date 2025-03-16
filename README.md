## FalconD
FalconD is the daemon for the FalconCP. It dont need to run using docker.

### Installation
1. Clone the repository:
`git clone https://github.com/DemonZDev/FalconD.git`

2. Go to the repository:
`cd FalconD`

3. Install dependencies:
`npm install`

4. Configure HydraDAEMON:
- Get your Panel's access key from the Hydra panel's config.json file and set it as 'remoteKey'. Do the same for the other way, set your HydraDaemon access key and configure it on the Panel.

5. Start the Daemon:
`node .`

### Usage
The daemon runs as a background service, interfacing with the FalconCP for operational commands and status updates. It is not typically interacted with directly by end-users.

### Contributing
Contributions to enhance the functionality or performance of the FalconD are encouraged. Please submit pull requests for any enhancements.

### Credit
- HydrenLabs
