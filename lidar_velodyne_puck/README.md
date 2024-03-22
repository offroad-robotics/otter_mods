# OtterMods --- LiDAR: Velodyne Puck

## Description
This folder contains the parts required to add the Velodyne Puck LiDAR to the Otter USV.

## File List
1. `puck_hook_mount.stl`: Ready to print file to mount the Velodyne Puck LiDAr with an interface plate to the top of the Targa on the Otter USV. 
2. `puck_hook_mount.sldprt` is a modifiable version of the LiDAR mount. Useful for reusing the hook interface to mount other hardware to the top of the hook.
3. `harness_box.stl` (and `harness_box.sldprt`): Box to adapt permanent (and not waterproof)cabling from the Puck LiDAR to IP67 connectors. Need may vary depending on LiDAR accessories purchased. Requires additional connectors for use.
4. `harness_box_lid.stl` (and `harness_box_lid.sldprt`): Lid for the harness box.
 
## Build Guide
There are two 3D printed components required: an interface box and a LiDAR mounting interface. Panel connectors are designed to insert into the holes in the harness box.

### Parts List
| Part name                    | Part number        | Count     |
| ---------------------------- | ------------------ | --------- |
| LiDAR Mount                  | `puck_hook_mount`  | 2         |
| Fasteners (mount)            | TBD                | 4         |
| Nuts (mount)                 | TBD                | 4         |
| Rubber (mount, optional)     | TBD                | 1         |
| Harness box                  | `harness_box`      | 1         |
| Harness lid                  | `harness_box_lid`  | 1         |
| Screws (harness box)         | TBD                | 4         |
| Nuts (harness box)           | TBD                | 4         |
| Zipties/velcro (harness box) | (Generic)          | As needed |
| Ethernet bulkhead connector  | ROP-5SPFFH-TCU7001 | 1         |
| Power connector              | UTS78E3S           | 1         |

### Supplier examples
- [UTS78E3S](https://www.mouser.ca/ProductDetail/Souriau/UTS78E3S?qs=Ss%252BeIZbYHa%2FnTzrz1Y%252Bq9g%3D%3D)
- [ROP-5SPFFH-TCU7001](https://www.mouser.ca/ProductDetail/Amphenol-LTW/ROP-5SPFFH-TCU7001?qs=Wmhir8UuqEnvZ%2F9ok5VlUw%3D%3D)