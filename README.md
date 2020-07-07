# pvea
pvea (pronounced pea-va) is a node.js client for the proxmox api. primarily focused on LXC containers functionality, but is still feature-packed.

## To-Do List:

- [X] Core functionality.
    - [X] Authenticate with Proxmox VE API.
    - [X] Get version.
    - [X] Get cluster status.
    - [X] Get cluster backup schedule.
    - [X] Get node networks.
    - [X] Get node interface.

- [ ]  LXC Container Functionality. (Priority)
    - [ ] Create LXC containers.
    - [ ] Remove LXC containers.
    - [ ] Configure/Modify LXC containers.

- [ ] Firewall functionality.
    - [ ] List firewall rules.


## Main contributors
As of now, [Ami](https://github.com/AmiCole) is the only main contributor.


## Notes
Thanks to [ttarvis](https://github.com/ttarvis) for writing [node-proxmox](https://github.com/ttarvis/node-proxmox)! Code was used for reference and function names are taken from it. Also thanks to [alo-is](https://github.com/alo-is) for writing another module also called [node-proxmox](https://github.com/alo-is/node-proxmox).

## License

Copyright 2020 Ami Cole

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
